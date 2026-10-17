# WatchmanHQ public feed

Free daily block lists for nonprofits, small businesses and the people who look after their
networks. Built from public threat research, checked before anything is recommended, and
cited back to the report behind every entry. Browse them at **https://watchmanhq.com/watch/**.

Published by WatchmanHQ (https://watchmanhq.com). Free, best effort, provided as is, with no warranty of any kind. Check every entry against your own traffic before you block it. Terms: https://watchmanhq.com/terms/ Wrong entry? https://watchmanhq.com/false-positives/ . License: CC BY 4.0; credit WatchmanHQ when you share it.

## Pick a list

| Folder | What's in it | What to do with it |
|---|---|---|
| `confident/` | Validated, and either reported as malicious by two or more independent sources, or registered by the attacker shortly before a recent report | Block |
| `blocking/` | Validated, and reported by at least one credible team. Includes Confident | Alert for a week or two, then block |
| `fresh/` | The domains and URLs in Blocking first reported in the last 14 days, none taken down. No IPs or hashes. The newest names, which free filtering DNS services (Quad9, Cloudflare) have had the least time to add | Load beside a filtering DNS service: alert for a few days, then block |
| `hunting/` | Linked to suspicious activity, not proven enough to block | Search your logs. Never block |
| `compromise-check/` | Reported domains already suspended or sinkholed: blocking them does little. Part of Hunting | Search your DNS and proxy logs from the last 30 to 90 days. A hit suggests an infected device. Never block |

Each folder has plain lists (`domains.txt`, `hosts.txt`, `ips.txt`, `urls.txt`,
`hashes.txt`), and `confident/`, `blocking/` and `fresh/` have ready-to-load formats in `export/`:
Pi-hole and AdGuard (`abp.txt`), dnsmasq, Unbound, RPZ, `/etc/hosts`, FortiGate, Palo Alto
and Microsoft Defender. Step-by-step setup: https://watchmanhq.com/how-to-block/

`fresh/` has only `domains.txt`, `hosts.txt` and `urls.txt`, and its `export/` keeps the DNS,
firewall, proxy and Defender formats, without the IP and hash files.

`compromise-check/` has `domains.txt`, `hosts.txt` and `urls.txt`, and comment-free copies in
`export/plain-domains.txt` and `export/plain-urls.txt` for log searches. In `lookup.csv` its
entries have `suspended` or `sinkholed` in the `compromise_check` column.

## Pull it automatically

These addresses never change. The lists are rebuilt once a day, ready by 10:00 AM US
Eastern, and **every list expires 72 hours after it is built**, so refresh daily and stop
enforcing a list that has expired (`valid_until` in `manifest.json`).

```
https://watchmanhq.com/feed/confident/export/abp.txt
https://watchmanhq.com/feed/fresh/export/abp.txt
https://watchmanhq.com/feed/blocking/export/fortigate-domains.txt
https://watchmanhq.com/feed/blocking/export/plain-ips.txt
https://watchmanhq.com/feed/stix-bundle.json
```

## Check what you download

`CURRENT` names the latest release. Every release folder, `releases/<id>/`, has a
`manifest.json` with a SHA-256 checksum for every file. About a month of releases is kept
here, and older ones are attached to this repository's GitHub Releases.

```python
import hashlib, json, urllib.request

base = "https://watchmanhq.com/feed/"
get = lambda path: urllib.request.urlopen(base + path).read()
release = get("CURRENT").decode().strip()
manifest = json.loads(get(f"releases/{release}/manifest.json"))
name = "confident/domains.txt"
data = get(f"releases/{release}/{name}")
assert hashlib.sha256(data).hexdigest() == manifest["files"][name]["sha256"]
print(release, name, "verified")
```

## What else is here

- `evidence.json.gz`: every blocking and hunting indicator with its role, dates and links to
  the reports it came from. Article text is not included; follow the links.
- `track_record.json`: every run, including the ones the release gate refused, and every
  false positive taken off the lists, with when and why.
- `stix-bundle.json` (STIX 2.1) and `lookup.csv` for threat-intel platforms and SIEMs.
- `status.json`: how the latest run went. If it says `failed`, the previous release is still
  current and still valid until it expires.

## How it's made

- Methodology, every check before an entry reaches a block list: https://watchmanhq.com/methodology/
- How it's built, secured and monitored: https://watchmanhq.com/how-its-built/
- Track record: https://watchmanhq.com/watch/track-record/

## Found a mistake?

Report a false positive: https://watchmanhq.com/false-positives/ . Entries come off first; we investigate
after.

## License

The lists and data are CC BY 4.0: use them freely, including commercially, and credit
WatchmanHQ (https://watchmanhq.com). See `LICENSE`.
