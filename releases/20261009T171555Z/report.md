# Threat intelligence report 20261009T171555Z

Generated 2026-10-09 17:15 UTC. **Valid until 2026-10-12 17:15 UTC**; do not enforce these lists after that.

| Confident (validated) | Blocking candidates | Hunting only | Enrichment only |
|---|---|---|---|
| 45 | 1426 | 7996 | 5648 |

## Block now

Reported as malicious by at least 2 independent publishers, passed every safety check, and validated (see METHODOLOGY.md). These are in `confident/`. Impact on your own network is not assessed here: check your traffic first.

| Indicator | Role | Publishers | First reported | What it is | Block scope |
|---|---|---|---|---|---|
| `npm-cache[.]com` | c2 | 4: Elastic Security Labs, Microsoft Threat Intelligence, Unit 42, Zscaler ThreatLabz | 2026-08-04 | registered 2026-05-22 (74 days before the report), suspended by registrar | domain and subdomains |
| `awqhnjewqjkl[.]icu` | c2 | 3: Elastic Security Labs, Unit 42, Zscaler ThreatLabz | 2026-08-06 | registered 2026-08-04 (1 days before the report) | domain and subdomains |
| `hxxps://npm-cache[.]com:443/router` | c2 | 3: Microsoft Threat Intelligence, Unit 42, Zscaler ThreatLabz | 2026-08-04 | registered 2026-05-22 (74 days before the report), suspended by registrar | exact url |
| `617b67a8e1210e4fc87c92d1d1da45a2f311c08d26e89b12307cf583c900d101` | malware file | 3: Elastic Security Labs, Microsoft Threat Intelligence, NVISO Labs | 2026-03-31 | not established | file hash |
| `92ff08773995ebc8d55ec4b8e1a225d0d1e51efa4ef88b8849d0071230c9645a` | malware file | 3: Elastic Security Labs, Microsoft Threat Intelligence, NVISO Labs | 2026-03-31 | not established | file hash |
| `fcb81618bb15edfdedfb638b4c08a2af9cac9ecfa551af135a8402bf980375cf` | malware file | 3: Elastic Security Labs, Microsoft Threat Intelligence, NVISO Labs | 2026-03-31 | not established | file hash |
| `cf903e4a1629aa0582fd0363b5786676` | malware file | 2: CISA Cybersecurity Advisories, Securelist | 2026-07-30 | not established | file hash |
| `fc96a04c615847f0fb1391f04d9d1aac7f78ddfb7d459168df0a4172b98354e2` | malware file | 2: Huntress, Microsoft Threat Intelligence | 2026-09-09 | not established | file hash |
| `add-passkey[.]com` | listed ioc | 2: Google Threat Intelligence / Mandiant, Microsoft Threat Intelligence | 2026-08-06 | registered 2026-07-13 (24 days before the report), suspended by registrar | domain and subdomains |
| `keysyncos[.]com` | phishing | 2: Google Threat Intelligence / Mandiant, Microsoft Threat Intelligence | 2026-08-06 | registered 2026-06-30 (36 days before the report), suspended by registrar | domain and subdomains |
| `myconnectkey[.]com` | listed ioc | 2: Google Threat Intelligence / Mandiant, Microsoft Threat Intelligence | 2026-08-06 | registered 2026-06-13 (54 days before the report), suspended by registrar | domain and subdomains |
| `oskeyconnect[.]com` | listed ioc | 2: Google Threat Intelligence / Mandiant, Microsoft Threat Intelligence | 2026-08-06 | registered 2026-06-17 (49 days before the report), suspended by registrar | domain and subdomains |
| `oskeysync[.]com` | phishing | 2: Google Threat Intelligence / Mandiant, Microsoft Threat Intelligence | 2026-08-06 | registered 2026-06-20 (46 days before the report), suspended by registrar | domain and subdomains |
| `passkeyhelpdesk[.]com` | phishing | 2: Google Threat Intelligence / Mandiant, Microsoft Threat Intelligence | 2026-08-06 | registered 2026-07-10 (26 days before the report), suspended by registrar | domain and subdomains |
| `portalsetuphub[.]com` | listed ioc | 2: Google Threat Intelligence / Mandiant, Microsoft Threat Intelligence | 2026-08-06 | registered 2026-06-10 (56 days before the report), suspended by registrar | domain and subdomains |
| `secure-passkey[.]com` | listed ioc | 2: Google Threat Intelligence / Mandiant, Microsoft Threat Intelligence | 2026-08-06 | registered 2026-07-21 (15 days before the report), suspended by registrar | domain and subdomains |
| `4fff28eecc0ab6303e4948df77671009dda5b93ed3d1cead527b02d1317426bc` | malware file | 2: Group-IB, Infoblox Threat Intel | 2026-04-10 | not established | file hash |
| `be99857449d2856dd5a84e21c8a3d5e0e01456adb44062ddec5a6b4970d8d42c` | malware file | 2: Microsoft Threat Intelligence, Zscaler ThreatLabz | 2026-07-31 | not established | file hash |
| `918fa52ae45ed60ba7cc8bdc99c3cbe9ab92e0375ec31fc05d0d4513be11c593` | malware file | 2: Microsoft Threat Intelligence, Zscaler ThreatLabz | 2026-07-31 | not established | file hash |
| `js-mirror[.]com` | c2 | 2: Microsoft Threat Intelligence, Unit 42 | 2026-08-04 | registered 2026-05-22 (74 days before the report) | domain and subdomains |
| `pypi-get[.]com` | c2 | 2: Microsoft Threat Intelligence, Unit 42 | 2026-08-04 | registered 2026-05-22 (74 days before the report) | domain and subdomains |
| `54dc7ea54a1317cca0e890a2770630cf7fa6c97813e0cb9d2caa93012b350668` | malware file | 2: Elastic Security Labs, Microsoft Threat Intelligence | 2026-08-04 | not established | file hash |
| `9fc2570b7cef51c1b8df116d144d11ff4096357be7d2c4c6367cfc2509cf1bcc` | malware file | 2: Elastic Security Labs, Microsoft Threat Intelligence | 2026-08-04 | not established | file hash |
| `fd3ca4007b225fdf8de7af4345a19179d5efa8c4bb9205f88cda806e5684b1eb` | malware file | 2: Elastic Security Labs, Microsoft Threat Intelligence | 2026-08-04 | not established | file hash |
| `8e07beb854f77e90c174829bd4e01e86779d596710ad161dbc0e02a219d6227f` | malware file | 2: Microsoft Threat Intelligence, Sekoia | 2025-12-15 | not established | file hash |
| `22b38dad7da097ea03aa28d0614164cd25fafeb1383dbc15047e34c8050f6f67` | malware file | 2: Check Point Research, Microsoft Threat Intelligence | 2026-04-20 | not established | file hash |
| `fe1033335a045c696c900d435119d210361966e2fb5cd1ba3382608cfa2c8e68` | malware file | 2: Check Point Research, Microsoft Threat Intelligence | 2026-04-20 | not established | file hash |
| `0db36a04d304ad96f9e6f97b531934594cd95a5cea9ff2c9af249201089dc864` | malware file | 2: Check Point Research, Unit 42 | 2026-05-22 | not established | file hash |
| `332ba2f0297dfb1599adecc3e9067893e7cf243aa23aedce4906a4c480574c17` | malware file | 2: Check Point Research, Unit 42 | 2026-05-22 | not established | file hash |
| `38bd137c672bd58d08c4f0502f993a6561e2c3411773d1ae57ee0151a0a9d11d` | malware file | 2: Check Point Research, Unit 42 | 2026-05-22 | not established | file hash |
| `43dc62cef52ebdd69e79f10015b3e13890f26c058325c0ff139c70f8d8eadcfa` | malware file | 2: Check Point Research, Unit 42 | 2026-05-22 | not established | file hash |
| `44f4f7aca7f1d9bfdaf7b3736934cbe19f851a707662f8f0b0c49b383e054250` | malware file | 2: Check Point Research, Unit 42 | 2026-05-22 | not established | file hash |
| `74882085db2088356ed7f72f01e0404a0a98cda88ef56fb15ce74c1f36b26d27` | malware file | 2: Check Point Research, Unit 42 | 2026-05-22 | not established | file hash |
| `8808c794c24367438f183e4be941876f1d3ecd0c8d2eb43b10d2380841d2283b` | malware file | 2: Check Point Research, Unit 42 | 2026-05-22 | not established | file hash |
| `9cf029daca89523d917dafed0568d11d00e45ec96b5b90b4a1f7fd4018c7da84` | malware file | 2: Check Point Research, Unit 42 | 2026-05-22 | not established | file hash |
| `9e4a658e6d831c9e9bdfe11884a75b7c64812ed0a80e8495ddf6b316505acac1` | malware file | 2: Check Point Research, Unit 42 | 2026-05-22 | not established | file hash |
| `b19e06da580cf91691eda066ac9ee4b09c6e5dc26c367af12660fe1f9306eec4` | malware file | 2: Check Point Research, Unit 42 | 2026-05-22 | not established | file hash |
| `bc3b44154518c5794ce639108e7b9c5fecb0c189607a26de1aaed518d890c7ad` | malware file | 2: Check Point Research, Unit 42 | 2026-05-22 | not established | file hash |
| `d4a7e9f107fe40c1a5d0139c6c6e25bf6bf57f61feff090bee28f476bb3cc3c2` | malware file | 2: Check Point Research, Unit 42 | 2026-05-22 | not established | file hash |
| `05eac3663d47a29da0d32f67e10d161f831138e10958dcd88b9dc97038948f69` | malware file | 2: Check Point Research, Unit 42 | 2026-01-13 | not established | file hash |
| `ed8560c1ac7ceb6983ba995124d5917dc1a00288912387a6389296637d5f815c` | malware file | 2: Microsoft Threat Intelligence, NVISO Labs | 2026-04-01 | not established | file hash |
| `f7d335205b8d7b20208fb3ef93ee6dc817905dc3ae0c10a0b164f4e7d07121cd` | malware file | 2: Microsoft Threat Intelligence, NVISO Labs | 2026-03-31 | not established | file hash |
| `6f079c1e2655ed391fb8f0b6bfafa126acf905732b5554f38a9d32d0b9ca407d` | malware file | 2: Seqrite, Unit 42 | 2025-12-22 | not established | file hash |
| `4ec3c90846af6b79ee1a5188eefa3fd21f6d4cf6` | malware file | 2: ESET WeLiveSecurity, Elastic Security Labs | 2026-01-23 | not established | file hash |
| `f9dd0b57a5c133ca0c4cab3cca1ac8debdc4a798b452167a1e5af78653af00c1` | malware file | 2: Check Point Research, Elastic Security Labs | 2025-10-22 | not established | file hash |

## Validation

Every blocking candidate is checked before it is recommended: what the destination is, whether it existed long before the report (a compromised or repurposed site), whether it is shared infrastructure, whether a file is a known legitimate one, and how current the evidence is. Only BLOCK_CANDIDATE indicators are in `blocking/` and `confident/`; the rest wait in `hunting/`.

| Decision | Indicators |
|---|---|
| REVIEW | 4419 |
| BLOCK_CANDIDATE | 1426 |

Most common reasons: `IDENTITY_UNVERIFIED` 4379, `EXPLICIT_ROLE` 4118, `NO_RECENT_REPORT` 3553, `LISTED_WITHOUT_ROLE` 1727, `NOT_A_KNOWN_FILE` 595, `NEWLY_REGISTERED` 350, `SHARED_INFRASTRUCTURE` 156.

## Trusted services named in attacks

Reports describe these as part of an attack, but they are services many organisations depend on, so they are never blocked here. Attackers abuse them (a messaging API as C2, a code host for payloads) or compromise them. If you do not use one, consider blocking it yourself; if you do, hunt for unusual use.

| Indicator | Role | Publishers | Last reported |
|---|---|---|---|
| `hxxps://github[.]com/cloudflare/cloudflared/releases/latest/download/cloudflared-windows-amd64.msi` | payload delivery | Elastic Security Labs, Huntress | 2026-02-10 |
| `hxxps://t[.]me/YATA0000` | c2 | Censys | 2026-10-07 |
| `hxxps://api[.]github[.]com/repos/peakyblinders-tm/myLic/contents/` | payload delivery | Unit 42 | 2026-10-06 |
| `hxxps://github[.]com/GreenBeret0` | c2 | Unit 42 | 2026-10-06 |
| `hxxps://github[.]com/peakyblinders-tm` | c2 | Unit 42 | 2026-10-06 |
| `hxxps://pastebin[.]com/raw/9ChwVzzw` | listed ioc | Group-IB | 2026-10-02 |
| `hxxps://pastebin[.]com/raw/aF0WCxia` | listed ioc | Group-IB | 2026-10-02 |
| `hxxps://pastebin[.]com/raw/hM0nXNBP` | listed ioc | Group-IB | 2026-10-02 |
| `hxxps://sites[.]google[.]com/view/antibot172881` | listed ioc | Huntress | 2026-09-28 |
| `hxxp://caldav[.]icloud[.]com/published/2/MTk1NDMwMDMzNTUxOTU0M1aHCZ-nMxiyGzBTzPiodOf44DtKJ6PpjftAG28_ui2NCYMpL_vu4pF4ddsJ8ysg0QI7pR0VEIEbZYdilVZRw08` | payload delivery | Securelist | 2026-09-24 |
| `hxxps://caldav[.]icloud[.]com/published/2/MTk1NDMwMDMzNTUxOTU0M1aHCZ-nMxiyGzBTzPiodOf44DtKJ6PpjftAG28_ui2NCYMpL_vu4pF4ddsJ8ysg0QI7pR0VEIEbZYdilVZRw08` | listed ioc | Securelist | 2026-09-24 |
| `hxxps://gateway[.]icloud[.]com/caldav/1_MTk1NDMwMDMzNTUxOTU0M0pybtJB186GzhogprwCQUjY3oZNiDFHH8WVo6bmgUtI/attach/4GE4TKNBTGAYDGMZVGUYTSNJUGOAALDAFMDOJBGWNUCYJLZRNDCLCO2YMQ3I64RLGMNXVG3KYBPWQOGYIEI7MPBDDYHECFDYVENTXIYFNDCPOVRMCTYI236RCYZAE63V5U3RTUYGUMO2CO7PKCLWMCXE73M7OPTHSGRWH5DXQ4PCUQU4ELZTLW54JSTK2H7VQ6PD26WOA2R7PPIQ6RTJWDEWP34U3HB4YWMXXC6EJ6PKWILSPYRSDEVY6QGMWSIUN6PR5W35KO3D4QZE7CFPUVBAEKI/Loader.app.tar.gz/YXR0YWNoYXR0YWNoYXR0YRhrE8mQ0E-b_dTUSGStQgTQ0ULFxCanei3Ke-EuEyQL` | payload delivery | Securelist | 2026-09-24 |
| `hxxps://api[.]telegram[.]org/bot783XXXX576` | payload delivery | Group-IB | 2026-09-17 |
| `hxxps://api[.]telegram[.]org/file/` | payload delivery | Group-IB | 2026-09-17 |
| `hxxps://github[.]com/browserthemes/resourcepack` | listed ioc | Securelist | 2026-09-16 |
| `hxxps://github[.]com/browserthemes/resourcepack/releases/download/main/resource-pack.zip` | payload delivery | Securelist | 2026-09-16 |
| `hxxps://github[.]com/mirror-js/mirror-js` | listed ioc | Securelist | 2026-09-16 |
| `hxxps://discord[.]com/api/webhooks/995445114254139543/NmpxQmuBCD6sm3UkVvupGtx-Y0M_A86oJHp00O-l8F4jakfVhqFXzMBoy1uBDdj2rBLc` | listed ioc | Huntress | 2026-09-09 |
| `hxxps://oracle-challenge[.]s3[.]us-east-1[.]amazonaws[.]com/Front-Technical-Challenge.zip` | payload delivery | Securelist | 2026-09-01 |
| `hxxps://raw[.]githubusercontent[.]com/askaboutme121/Xusyahfd/refs/heads/main/Jhinstaller.ps1` | listed ioc | Huntress | 2026-08-31 |
| `hxxps://meeting[.]tencent[.]com/download/` | payload delivery | Securelist | 2026-08-31 |
| `hxxps://raw[.]githubusercontent[.]com/mmarln/pi-mono/refs/heads/main/packages/pods/src/array12.json` | c2 | Securelist | 2026-08-13 |
| `hxxps://github[.]com/Mash3Do/` | listed ioc | Unit 42 | 2026-08-10 |
| `hxxps://github[.]com/lencod/` | listed ioc | Unit 42 | 2026-08-10 |
| `hxxps://cas5-0-urlprotect[.]trendmicro[.]com/wis/clicktime/v1/query?url=hxxps%3a%2f%2fpoa.sp.gov.br%2fdown.php&umid=a1a41f4a-228b-4622-9a1f-5fd4cbc68d26&rct=1779114363&auth=18576cf8abd7812271cef15c8c401c7207caa231-a9e499076e60cd525b23d7c667f1929bc0a9b294` | listed ioc | ANY.RUN | 2026-07-16 |
| `hxxps://github[.]com/helloworm00/hello-world` | c2 | Unit 42 | 2026-07-15 |
| `hxxps://github[.]com/oven-sh/bun/releases/download/bun-v1.3.13/` | payload delivery | Unit 42 | 2026-07-15 |
| `hxxps://github[.]com/Open-Agent-Utilities/bot-compliance-middleware` | listed ioc | Zscaler ThreatLabz | 2026-07-02 |
| `hxxps://github[.]com/Open-Agent-Utilities/digital-asset-arbitrage-cli` | listed ioc | Zscaler ThreatLabz | 2026-07-02 |
| `hxxps://github[.]com/Open-Agent-Utilities/global-visa-automation-cli` | listed ioc | Zscaler ThreatLabz | 2026-07-02 |
| `hxxps://github[.]com/Open-Agent-Utilities/llm-fact-check-protocol` | listed ioc | Zscaler ThreatLabz | 2026-07-02 |
| `hxxps://github[.]com/Open-Agent-Utilities/mig-institutional-api-client` | listed ioc | Zscaler ThreatLabz | 2026-07-02 |
| `hxxps://github[.]com/Open-Agent-Utilities/opentable-resy-bypasser` | listed ioc | Zscaler ThreatLabz | 2026-07-02 |
| `hxxps://github[.]com/Open-Agent-Utilities/requests-secure-v2` | listed ioc | Zscaler ThreatLabz | 2026-07-02 |
| `hxxps://github[.]com/Open-Agent-Utilities/royalty-free-image-scraper` | listed ioc | Zscaler ThreatLabz | 2026-07-02 |
| `hxxps://github[.]com/Open-Agent-Utilities/session-token-leak-detector` | listed ioc | Zscaler ThreatLabz | 2026-07-02 |
| `hxxps://github[.]com/Open-Agent-Utilities/sneaker-drop-monitor-v2` | listed ioc | Zscaler ThreatLabz | 2026-07-02 |
| `hxxps://github[.]com/bolubey/CVE-2026-0257` | payload delivery | Sekoia | 2026-06-30 |
| `hxxps://github[.]com/bolubey/CVE-2026-50751` | payload delivery | Sekoia | 2026-06-30 |
| `hxxps://github[.]com/lincemorado97/CVE-2025-14847` | payload delivery | Sekoia | 2026-06-30 |

## Changes since the previous release

Compared with release 20261009T162334Z: 283 added to blocking, 0 removed.

**Added**, highest priority first:

- `617b67a8e1210e4fc87c92d1d1da45a2f311c08d26e89b12307cf583c900d101` malware file, high confidence (Elastic Security Labs, Huntress, Microsoft Threat Intelligence, NVISO Labs, Unit 42)
- `92ff08773995ebc8d55ec4b8e1a225d0d1e51efa4ef88b8849d0071230c9645a` malware file, high confidence (Elastic Security Labs, Huntress, Microsoft Threat Intelligence, NVISO Labs, Unit 42)
- `fcb81618bb15edfdedfb638b4c08a2af9cac9ecfa551af135a8402bf980375cf` malware file, high confidence (Elastic Security Labs, Huntress, Microsoft Threat Intelligence, NVISO Labs, Unit 42)
- `be99857449d2856dd5a84e21c8a3d5e0e01456adb44062ddec5a6b4970d8d42c` malware file, high confidence (Google Threat Intelligence / Mandiant, Microsoft Threat Intelligence, Zscaler ThreatLabz)
- `918fa52ae45ed60ba7cc8bdc99c3cbe9ab92e0375ec31fc05d0d4513be11c593` malware file, high confidence (Microsoft Threat Intelligence, Zscaler ThreatLabz)
- `js-mirror[.]com` c2, high confidence (Microsoft Threat Intelligence, Unit 42)
- `pypi-get[.]com` c2, high confidence (Microsoft Threat Intelligence, Unit 42)
- `54dc7ea54a1317cca0e890a2770630cf7fa6c97813e0cb9d2caa93012b350668` malware file, high confidence (Elastic Security Labs, Microsoft Threat Intelligence, Unit 42)
- `9fc2570b7cef51c1b8df116d144d11ff4096357be7d2c4c6367cfc2509cf1bcc` malware file, high confidence (Elastic Security Labs, Microsoft Threat Intelligence, Unit 42)
- `fd3ca4007b225fdf8de7af4345a19179d5efa8c4bb9205f88cda806e5684b1eb` malware file, high confidence (Elastic Security Labs, Microsoft Threat Intelligence, Unit 42)
- `8e07beb854f77e90c174829bd4e01e86779d596710ad161dbc0e02a219d6227f` malware file, high confidence (Microsoft Threat Intelligence, Sekoia)
- `22b38dad7da097ea03aa28d0614164cd25fafeb1383dbc15047e34c8050f6f67` malware file, high confidence (Check Point Research, Microsoft Threat Intelligence)
- `fe1033335a045c696c900d435119d210361966e2fb5cd1ba3382608cfa2c8e68` malware file, high confidence (Check Point Research, Microsoft Threat Intelligence)
- `0db36a04d304ad96f9e6f97b531934594cd95a5cea9ff2c9af249201089dc864` malware file, high confidence (Check Point Research, Unit 42)
- `332ba2f0297dfb1599adecc3e9067893e7cf243aa23aedce4906a4c480574c17` malware file, high confidence (Check Point Research, Unit 42)
- `38bd137c672bd58d08c4f0502f993a6561e2c3411773d1ae57ee0151a0a9d11d` malware file, high confidence (Check Point Research, Unit 42)
- `43dc62cef52ebdd69e79f10015b3e13890f26c058325c0ff139c70f8d8eadcfa` malware file, high confidence (Check Point Research, Unit 42)
- `44f4f7aca7f1d9bfdaf7b3736934cbe19f851a707662f8f0b0c49b383e054250` malware file, high confidence (Check Point Research, Unit 42)
- `74882085db2088356ed7f72f01e0404a0a98cda88ef56fb15ce74c1f36b26d27` malware file, high confidence (Check Point Research, Unit 42)
- `8808c794c24367438f183e4be941876f1d3ecd0c8d2eb43b10d2380841d2283b` malware file, high confidence (Check Point Research, Unit 42)
- `9cf029daca89523d917dafed0568d11d00e45ec96b5b90b4a1f7fd4018c7da84` malware file, high confidence (Check Point Research, Unit 42)
- `9e4a658e6d831c9e9bdfe11884a75b7c64812ed0a80e8495ddf6b316505acac1` malware file, high confidence (Check Point Research, Unit 42)
- `b19e06da580cf91691eda066ac9ee4b09c6e5dc26c367af12660fe1f9306eec4` malware file, high confidence (Check Point Research, Unit 42)
- `bc3b44154518c5794ce639108e7b9c5fecb0c189607a26de1aaed518d890c7ad` malware file, high confidence (Check Point Research, Unit 42)
- `d4a7e9f107fe40c1a5d0139c6c6e25bf6bf57f61feff090bee28f476bb3cc3c2` malware file, high confidence (Check Point Research, Unit 42)
- and 258 more; see `changes.json`

## Reports in this release

595 articles contributed blocking or hunting indicators, newest first.

| Published | Publisher | Report | Blocking | Hunting |
|---|---|---|---|---|
| 2026-10-09 | Jamf Threat Labs | [Fake Zoom installer uses .NET downloader to deliver Overlord RAT on macOS](<https://www.jamf.com/blog/fake-zoom-installer-delivers-overlord-rat-macos/>) | 4 | 0 |
| 2026-10-09 | Jamf Threat Labs | [AmnesiaStealer: a multi-stage Rust-based macOS infostealer that hijacks Chromium browsers](<https://www.jamf.com/blog/amnesia-stealer-macos-infostealer-clickfix/>) | 3 | 0 |
| 2026-10-09 | Objective-See | [Website Launch](<https://objective-see.org/blog.html#blogEntry1>) | 2 | 0 |
| 2026-10-09 | Objective-See | [Dylib Hijack Scanner Released](<https://objective-see.org/blog.html#blogEntry2>) | 2 | 0 |
| 2026-10-09 | Objective-See | [Phoenix: RootPipe lives! ...even on OS X 10.10.3](<https://objective-see.org/blog.html#blogEntry3>) | 2 | 0 |
| 2026-10-09 | Objective-See | [More on, "Adware for OS X Distributes Trojans"](<https://objective-see.org/blog.html#blogEntry4>) | 2 | 0 |
| 2026-10-09 | Objective-See | [CVE-2015-3673: Goodbye Rootpipe...(for now?)](<https://objective-see.org/blog.html#blogEntry5>) | 2 | 0 |
| 2026-10-09 | Objective-See | [Building HackingTeam's OS X Implant For Fun & Profit](<https://objective-see.org/blog.html#blogEntry6>) | 2 | 0 |
| 2026-10-09 | Objective-See | [Reversing to Engineer: Learning to 'Secure' XPC from a Patch](<https://objective-see.org/blog.html#blogEntry7>) | 2 | 0 |
| 2026-10-09 | Objective-See | [Kernel Debugging a Virtualized OS X El Capitan Image](<https://objective-see.org/blog.html#blogEntry8>) | 2 | 0 |
| 2026-10-09 | Objective-See | [Monitoring Process Creation via the Kernel (Part I)](<https://objective-see.org/blog.html#blogEntry9>) | 2 | 0 |
| 2026-10-09 | Objective-See | [Analyzing the Anti-Analysis Logic of an Adware Installer](<https://objective-see.org/blog/blog_0x0C.html>) | 1 | 0 |
| 2026-10-09 | Objective-See | [HackingTeam Reborn; A Brief Analyis of the RCS Implant Installer](<https://objective-see.org/blog/blog_0x0D.html>) | 1 | 0 |
| 2026-10-09 | Objective-See | [Analysis of an Intrusive Cross-Platform Adware; OSX/Pirrit](<https://objective-see.org/blog/blog_0x0E.html>) | 2 | 0 |
| 2026-10-09 | Objective-See | [From Italy With Love?](<https://objective-see.org/blog/blog_0x18.html>) | 1 | 0 |
| 2026-10-09 | Objective-See | [HandBrake Hacked! OSX/Proton (re)Appears](<https://objective-see.org/blog/blog_0x1D.html>) | 2 | 0 |
| 2026-10-09 | Objective-See | [OSX/Proton.B; a brief analysis, 6 miles up](<https://objective-see.org/blog/blog_0x1F.html>) | 2 | 0 |
| 2026-10-09 | Objective-See | [WTF is Mughthesec!? poking on a piece of undetected adware](<https://objective-see.org/blog/blog_0x20.html>) | 1 | 0 |
| 2026-10-09 | Objective-See | [All Your Docs Are Belong To Us](<https://objective-see.org/blog/blog_0x22.html>) | 1 | 0 |
| 2026-10-09 | Objective-See | [Analyzing CrossRAT](<https://objective-see.org/blog/blog_0x28.html>) | 1 | 0 |
| 2026-10-09 | Objective-See | [Tearing Apart the Undetected (OSX)Coldroot RAT](<https://objective-see.org/blog/blog_0x2A.html>) | 1 | 0 |
| 2026-10-09 | Objective-See | [Who Moved My Pixels?!](<https://objective-see.org/blog/blog_0x2C.html>) | 2 | 0 |
| 2026-10-09 | Objective-See | [A Deceitful 'Doctor' in the Mac App Store](<https://objective-see.org/blog/blog_0x37.html>) | 7 | 0 |
| 2026-10-09 | Objective-See | [Middle East Cyber-Espionage](<https://objective-see.org/blog/blog_0x3B.html>) | 4 | 0 |
| 2026-10-09 | Objective-See | [The Mac Malware of 2018](<https://objective-see.org/blog/blog_0x3C.html>) | 0 | 2 |
| 2026-10-09 | Objective-See | [Middle East Cyber-Espionage (part two)](<https://objective-see.org/blog/blog_0x3D.html>) | 1 | 0 |
| 2026-10-09 | Objective-See | [Burned by Fire(fox) (Part I)](<https://objective-see.org/blog/blog_0x43.html>) | 1 | 0 |
| 2026-10-09 | Objective-See | [Burned by Fire(fox) (Part II)](<https://objective-see.org/blog/blog_0x44.html>) | 3 | 0 |
| 2026-10-09 | Objective-See | [Burned by Fire(fox) (Part III)](<https://objective-see.org/blog/blog_0x45.html>) | 3 | 0 |
| 2026-10-09 | Objective-See | [Pass the AppleJeus](<https://objective-see.org/blog/blog_0x49.html>) | 1 | 0 |
| 2026-10-09 | Objective-See | [Lazarus Group Goes 'Fileless'](<https://objective-see.org/blog/blog_0x51.html>) | 2 | 0 |
| 2026-10-09 | Objective-See | [Mass Surveillance, is an (un)Complicated Business](<https://objective-see.org/blog/blog_0x52.html>) | 1 | 0 |
| 2026-10-09 | Objective-See | [The Mac Malware of 2019](<https://objective-see.org/blog/blog_0x53.html>) | 5 | 0 |
| 2026-10-09 | Objective-See | [Weaponizing a Lazarus Group Implant](<https://objective-see.org/blog/blog_0x54.html>) | 2 | 0 |
| 2026-10-09 | Objective-See | [The Dacls RAT ...now on macOS!](<https://objective-see.org/blog/blog_0x57.html>) | 6 | 0 |
| 2026-10-09 | Jamf Threat Labs | [Contagious Interview steps outside the developer workflow](<https://www.jamf.com/blog/contagious-interview-trojanized-macos-installers/>) | 1 | 8 |
| 2026-10-09 | Jamf Threat Labs | [PamStealer adapts again: a move to Swift with a server-side decryption chain](<https://www.jamf.com/blog/pamstealer-wavel-macos-infostealer/>) | 2 | 1 |
| 2026-10-09 | Infoblox Threat Intel | [When a Wallet Drainer Asks DNS Where to Go](<https://www.infoblox.com/blog/threat-intelligence/when-a-wallet-drainer-asks-dns-where-to-go/>) | 3 | 0 |
| 2026-10-09 | Socket | [New GhostAction Wave Hits Hundreds of Repos, Expanding Beyond CI/CD Secrets to Cloud Credentials](<https://socket.dev/blog/ghostaction-cloud-credentials?utm_medium=feed>) | 1 | 0 |
| 2026-10-08 | Huntress | [Threat Actors Exploit Critical AhsayCBS Flaws to Drop Webshells and XMRig Cryptominer](<https://www.huntress.com/blog/ahsaycbs-flaws-exploit>) | 8 | 8 |
| 2026-10-08 | Cisco Talos | [Making sure the checks get printed](<https://blog.talosintelligence.com/making-sure-the-checks-get-printed/>) | 10 | 0 |
| 2026-10-08 | Bitdefender Labs | [The phone was compromised before the user turned it on: the rise of Midnight Mimosa](<https://www.bitdefender.com/en-us/blog/labs/midnight-mimosa-malware>) | 127 | 8 |
| 2026-10-08 | CISA Cybersecurity Advisories | [Chinese Government-linked Cyber Threat Actors Combine Automated and Hands-on Hacking Tools to Steal Sensitive Data](<https://www.cisa.gov/news-events/cybersecurity-advisories/aa26-281a>) | 60 | 735 |
| 2026-10-08 | ESET WeLiveSecurity | [MATCHBOIL: New tricks, same old evil intentions](<https://www.welivesecurity.com/en/eset-research/matchboil-new-tricks-same-old-evil-intentions/>) | 4 | 0 |
| 2026-10-08 | Socket | [TensorLake npm SDK Compromised in ChainDrop Shai-Hulud Credential-Stealing Attack](<https://socket.dev/blog/tensorlake-compromise?utm_medium=feed>) | 2 | 0 |
| 2026-10-07 | Censys | [DarkSword/Coruna Open Directory Finding Report](<https://censys.com/blog/darksword-coruna-open-directory-finding-report/>) | 17 | 15 |
| 2026-10-07 | Socket | [16 Malicious Firefox Extensions Steal Cryptocurrency Wallet Credentials](<https://socket.dev/blog/firefox-crypto-wallet-stealers?utm_medium=feed>) | 10 | 0 |
| 2026-10-07 | Huntress | [Phishing Campaign Abuses Microsoft Power BI to Deploy Rogue RMMs](<https://www.huntress.com/blog/screenconnect-power-bi>) | 3 | 2 |
| 2026-10-06 | Socket | [Introducing Socket Scanning for VS Code Marketplace Extensions](<https://socket.dev/blog/vscode-extensions?utm_medium=feed>) | 2 | 0 |
| 2026-10-06 | SANS Internet Storm Center | [More RMM Tools In the Wild, (Tue, Oct 6th)](<https://isc.sans.edu/diary/rss/33400>) | 2 | 3 |
| 2026-10-06 | Huntress | [Up a Creek Without a Command Line: Mapping an Akira Ransomware Attack](<https://www.huntress.com/blog/mapping-akira-ransomware-attack>) | 3 | 0 |
| 2026-10-06 | ANY.RUN | [IronChain Ransomware Threatens Businesses with Permanent Data Loss and Costly Downtime](<https://any.run/cybersecurity-blog/ironchain-analysis/>) | 5 | 0 |
| 2026-10-06 | Unit 42 | [Blinder Tunnel Campaign Targets Iraqi Infrastructure](<https://unit42.paloaltonetworks.com/blinder-tunnel-targets-critical-infrastructure/>) | 20 | 6 |
| 2026-10-05 | Fortinet Threat Research | [ClingSTUN Linux Backdoor Abuses Public STUN Infrastructure](<https://feeds.fortinet.com/~/971007764/0/fortinet/blog/threat-research~ClingSTUN-Linux-Backdoor-Abuses-Public-STUN-Infrastructure>) | 3 | 0 |
| 2026-10-02 | Rapid7 | [SMTP is the key: BPFDoor and AVERAT hitting the network edge](<https://www.rapid7.com/blog/post/tr-smtp-is-the-key-bpfdoor-averat-hitting-the-network-edge>) | 11 | 0 |
| 2026-10-02 | Group-IB | [Anatomía de BraZetsu: Cómo los cibercriminales abastecen el ecosistema clandestino](<https://www.group-ib.com/blog/brazetsu-ai-enhanced-iab-marketplace-es/>) | 21 | 4 |
| 2026-10-02 | Socket | [Pretty Themes, Hidden Loaders: GlassWorm-Linked Extensions Span VS Code Marketplace and Open VSX](<https://socket.dev/blog/glassworm-vscode-themes?utm_medium=feed>) | 6 | 0 |
| 2026-10-01 | Cisco Talos | [Give yourself room to be human](<https://blog.talosintelligence.com/give-yourself-room-to-be-human/>) | 10 | 0 |
| 2026-10-01 | Malwarebytes Labs | [Fake xStocks, Pendle, and other sites bait crypto users with rewards votes](<https://www.malwarebytes.com/blog/threat-intel/2026/10/fake-xstocks-pendle-and-other-sites-bait-crypto-users-with-rewards-votes>) | 0 | 70 |
| 2026-10-01 | Lab52 | [Backdoors in the Dungeon – TURN & MQTT Abused by DragonForce](<https://lab52.io/blog/backdoors-in-the-dungeon-turn-mqtt-abused-by-dragonforce/>) | 1 | 7 |
| 2026-10-01 | Proofpoint Threat Insight | [Hallucinating Credibility: China-Aligned TA419 Impersonates its Way into US AI Policy Circles](<https://www.proofpoint.com/us/blog/threat-insight/hallucinating-credibility-china-aligned-ta419-impersonates-its-way-us-ai-policy>) | 5 | 1 |
| 2026-09-30 | Unit 42 | [Threat Brief: NetScaler Zero Days CVE-2026-88771 and CVE-2026-88772 Exploited in the Wild (Updated September 30)](<https://unit42.paloaltonetworks.com/netscaler-zero-days-exploited/>) | 9 | 1 |
| 2026-09-30 | ReversingLabs | [Restrospective: How Malicious Updates Poison Your Environment](<https://www.reversinglabs.com/blog/a-software-supply-chain-attack-retrospective>) | 4 | 0 |
| 2026-09-30 | Zscaler ThreatLabz | [2CLoader: A New Malware Loader Delivering Vidar and Remus](<https://www.zscaler.com/blogs/security-research/2cloader-new-malware-loader-delivering-vidar-and-remus>) | 2 | 1 |
| 2026-09-30 | Microsoft Threat Intelligence | [Unauthenticated command injection on internet-facing mail servers: tracking CVE-2026-73570](<https://www.microsoft.com/en-us/security/blog/2026/09/30/unauthenticated-command-injection-on-internet-facing-mail-servers-tracking-cve-2026-73570/>) | 15 | 10 |
| 2026-09-30 | Cisco Talos | [China-nexus UAT-11587 targets government and policy organizations across Asia with Antino backdoor](<https://blog.talosintelligence.com/china-nexus-uat-11587-targets-government-and-policy-organizations-across-asia-with-antino-backdoor/>) | 150 | 1 |
| 2026-09-30 | Huntress | [Determined Attacker Uploads Malicious Webshells to Parks and Rec Management Platform Servers](<https://www.huntress.com/blog/parks-recreation-platform-webshell-attack>) | 7 | 1 |
| 2026-09-29 | Microsoft Threat Intelligence | [Phishing Abuses RMM Tools for Persistent Access](<https://www.microsoft.com/en-us/security/blog/2026/09/29/phishing-abuses-rmm-tools-persistent-access/>) | 32 | 5 |
| 2026-09-29 | Microsoft Threat Intelligence | [Star Blizzard refines phishing and malware delivery with the RedFlick technique](<https://www.microsoft.com/en-us/security/blog/2026/09/29/star-blizzard-refines-phishing-and-malware-delivery-with-the-redflick-technique/>) | 24 | 0 |
| 2026-09-29 | K7 Labs | [From KMS Auto to Scareware: Tracking a Multi-Stage Intrusion Linked to APT36?](<https://labs.k7computing.com/index.php/from-kms-auto-to-scareware-tracking-a-multi-stage-intrusion-linked-to-apt36/>) | 5 | 0 |
| 2026-09-28 | Huntress | [Attackers Abuse ChatGPT Custom GPTs to Deliver RAT via ClickFix](<https://www.huntress.com/blog/chatgpt-custom-gpts-clickfix-rat>) | 15 | 10 |
| 2026-09-28 | Microsoft Threat Intelligence | [NeedyMantis: Unpacking a post-compromise malware family used in targeted operations](<https://www.microsoft.com/en-us/security/blog/2026/09/28/needymantis-unpacking-a-post-compromise-malware-family-used-in-targeted-operations/>) | 4 | 0 |
| 2026-09-28 | Rapid7 | [Zero-Day Exploitation of Citrix NetScaler ADC and Gateway: CVE-2026-88771 and CVE-2026-88772](<https://www.rapid7.com/blog/post/etr-zero-day-exploitation-of-citrix-netscaler-adc-and-gateway-cve-2026-88771-and-cve-2026-88772>) | 1 | 0 |
| 2026-09-25 | Zscaler ThreatLabz | [Threat Actors Use Google Ads To Target Ledger Users](<https://www.zscaler.com/blogs/security-research/threat-actors-use-google-ads-target-ledger-users>) | 5 | 0 |
| 2026-09-25 | Microsoft Threat Intelligence | [Storm-3168: Agentic-driven cloud attacks using compromised service principals](<https://www.microsoft.com/en-us/security/blog/2026/09/25/storm-3168-agentic-driven-cloud-attacks-using-compromised-service-principals/>) | 2 | 1 |
| 2026-09-25 | Google Threat Intelligence / Mandiant | [ShinyHunters Renewed Mass Exploitation Campaign Targeting Oracle PeopleSoft](<https://cloud.google.com/blog/topics/threat-intelligence/shinyhunters-renewed-mass-exploitation-campaign-targeting-oracle-peoplesoft/>) | 1 | 0 |
| 2026-09-25 | K7 Labs | [The Stealer Factory: Unpacking a Python-Based MaaS Infostealer Builder](<https://labs.k7computing.com/index.php/the-stealer-factory-unpacking-a-python-based-maas-infostealer-builder/>) | 0 | 1 |
| 2026-09-24 | Cisco Talos | [Trust and the enticing consultancy offer](<https://blog.talosintelligence.com/trust-and-the-enticing-consultancy-offer/>) | 10 | 0 |
| 2026-09-24 | Censys | [Introducing Censys CLI Skills: AI-Assisted Investigations at Scale](<https://censys.com/blog/introducing-censys-cli-skills/>) | 1 | 1 |
| 2026-09-24 | Darktrace | [Darktrace / SECURE AI: Behavioral Security for the AI enterprise](<https://www.darktrace.com/blog/darktrace-secure-ai-extending-behavioral-security-for-the-age-of-agentic-ai>) | 0 | 13 |
| 2026-09-24 | Sekoia | [Gotta Breach 'Em All! The Journey Of ShinyHunters](<https://www.sekoia.com/blog/gotta-breach-em-all-the-journey-of-shinyhunters>) | 4 | 1 |
| 2026-09-24 | Arctic Wolf | [The Psychedelic Stealer: When a CAPTCHA Becomes an Installer](<https://arcticwolf.com/resources/blog/psychedelic-stealer-fake-clickfix-captcha-targets-ukraine/>) | 7 | 1 |
| 2026-09-24 | Fortinet Threat Research | [Uncovering a SectopRAT Variant Embedded in Legitimate Software](<https://feeds.fortinet.com/~/969841961/0/fortinet/blog/threat-research~Uncovering-a-SectopRAT-Variant-Embedded-in-Legitimate-Software>) | 2 | 0 |
| 2026-09-24 | Huntress | [The Not So Silent Miner: Threat Actor Compiles Cryptominer on the Endpoint](<https://www.huntress.com/blog/threat-actor-compiles-cryptominer>) | 1 | 0 |
| 2026-09-24 | Securelist | [MacSync under the microscope: new delivery methods and a new payload](<https://securelist.com/macsync-new-version/121383/>) | 26 | 13 |
| 2026-09-23 | Darktrace | [Agent Hijacks: How Conversation History Poisoning Can Turn AI Agents Into Attackers](<https://www.darktrace.com/blog/hijacking-agentic-harnesses-to-attack-an-organization>) | 0 | 13 |
| 2026-09-23 | Group-IB | [RemControl: AI Built the Overlays. Victims Lose their PINs](<https://www.group-ib.com/blog/remcontrol-android-banking-trojan/>) | 26 | 6 |
| 2026-09-22 | Huntress | [DarkMe RAT: A VB6 APT Trojan Turned Conventional Infostealer](<https://www.huntress.com/blog/darkme-rat-abandons-exploits>) | 6 | 11 |
| 2026-09-22 | Darktrace | [Detecting Rogue AI Agents: When Enterprise Agents Turn to Hacking](<https://www.darktrace.com/blog/detecting-rogue-agent-behavior-in-the-enterprise>) | 0 | 13 |
| 2026-09-22 | ReversingLabs | [Malicious npm campaign targets developers integrating Twilio](<https://www.reversinglabs.com/blog/malicious-npm-campaign-twilio>) | 0 | 3 |
| 2026-09-22 | Silent Push | [Bandwidth-Sharing App Can Turn Employee Devices Into Gateways to Internal Networks](<https://cybersecuritynews.com/bandwidth-sharing-app/#new_tab?utm_source=rss&utm_medium=rss&utm_campaign=bandwidth-sharing-app-can-turn-employee-devices-into-gateways-to-internal-networks>) | 0 | 9 |
| 2026-09-22 | ANY.RUN | [CSuite Targets US and EU Organizations with Device-Code Phishing and Remote Access](<https://any.run/cybersecurity-blog/csuite-attack-analysis/>) | 28 | 3 |
| 2026-09-22 | Cisco Talos | [The Closed Quorum: Inside the first reported autonomous AI C2 implant](<https://blog.talosintelligence.com/the-closed-quorum-inside-the-first-reported-autonomous-ai-c2-implant/>) | 0 | 6 |
| 2026-09-21 | Volexity | [Mind the (Patch) Gap, Part 2: Fake Websites Used to Deploy Chrome & Windows 0-Day Exploits](<https://www.volexity.com/blog/2026/09/21/mind-the-patch-gap-part-2-fake-websites-used-to-deploy-chrome-windows-0-day-exploits/>) | 2 | 1 |
| 2026-09-21 | Darktrace | [Human Judgement in the Agentic AI Age \| Darktrace](<https://www.darktrace.com/blog/the-problem-of-re-defining-human-value-in-the-agentic-age>) | 0 | 13 |
| 2026-09-21 | Silent Push | [Peer2Profit Turns Employee Devices Into AstroProxy Nodes That Can Expose Internal Networks](<https://gbhackers.com/peer2profit-proxy-threat/#new_tab?utm_source=rss&utm_medium=rss&utm_campaign=peer2profit-turns-employee-devices-into-astroproxy-nodes-that-can-expose-internal-networks>) | 0 | 5 |
| 2026-09-21 | Zscaler ThreatLabz | [Vidar Adds Virtual Machine and Custom Stream Ciphers For String Obfuscation](<https://www.zscaler.com/blogs/security-research/vidar-adds-virtual-machine-and-custom-stream-ciphers-string-obfuscation>) | 4 | 0 |
| 2026-09-21 | Huntress | [The Tale of Two INC Ransom Notes: A Ransomware Timeline \| Huntress](<https://www.huntress.com/blog/two-inc-ransom-notes>) | 1 | 0 |
| 2026-09-21 | Securelist | [Group Policy hijacked: PAYLOAD ransomware weaponizes Active Directory GPO](<https://securelist.com/tr/payload-ransomware-via-group-policy/121335/>) | 12 | 0 |
| 2026-09-18 | SentinelLabs | [Don’t Call Us, We’ll Call Your APIs \| TraderTraitor Backdoors Resurface on Victim With No Crypto Ties](<https://www.sentinelone.com/labs/dont-call-us-well-call-your-apis-tradertraitor-backdoors-resurface-on-victim-with-no-crypto-ties/>) | 9 | 1 |
| 2026-09-18 | K7 Labs | [From Registry-Stored PowerShell to In-Memory Cryptocurrency Mining: A Multi-Stage Infection Chain](<https://labs.k7computing.com/index.php/from-registry-stored-powershell-to-in-memory-cryptocurrency-mining-a-multi-stage-infection-chain/>) | 3 | 7 |
| 2026-09-17 | Cisco Talos | [Should you care about an “AI slowdown?”](<https://blog.talosintelligence.com/should-you-care-about-an-ai-slowdown/>) | 8 | 2 |
| 2026-09-17 | Securelist | [The Odyssey and Trojans again: MovieReaper attacks users in multiple countries through compromised torrents](<https://securelist.com/moviereaper-malware-torrent-odyssey-solana/121344/>) | 6 | 0 |
| 2026-09-17 | Huntress | [Ready, Settra, Go: New Settra Ransomware Variant Deploys MeshAgent RMM](<https://www.huntress.com/blog/new-settra-ransomware-variant>) | 1 | 1 |
| 2026-09-17 | ESET WeLiveSecurity | [Beware the SparroWock: The backdoor that bites, the commands that catch](<https://www.welivesecurity.com/en/eset-research/beware-sparrowock-backdoor-bites-commands-catch/>) | 0 | 1 |
| 2026-09-17 | Group-IB | [HEAVYGRAM: A Telegram-based Surveillance Backdoor Linked to Handala Hack](<https://www.group-ib.com/blog/heavygram-handala-hack-telegram-c2/>) | 0 | 9 |
| 2026-09-16 | Zscaler ThreatLabz | [Operation RapidRust: APT36 Deploys RUSTYSHADE, RUSTYMOVE, PSNATCH, and BASHNATCH](<https://www.zscaler.com/blogs/security-research/operation-rapidrust-apt36-deploys-rustyshade-rustymove-psnatch-and>) | 2 | 0 |
| 2026-09-16 | SentinelLabs | [Agents at Large \| Tracing Illicit OpenAI Agent Activity on Hugging Face](<https://www.sentinelone.com/labs/agents-at-large-tracing-illicit-openai-agent-activity-on-hugging-face/>) | 1 | 0 |
| 2026-09-16 | Securelist | [NightEagle targets Russian companies](<https://securelist.com/tr/nighteagle-apt-ghostcontainer-and-tunneling/121323/>) | 5 | 3 |
| 2026-09-16 | Unit 42 | [Atomic macOS (AMOS) Stealer Activity](<https://unit42.paloaltonetworks.com/atomic-macos-amos-stealer-activity/>) | 11 | 2 |
| 2026-09-15 | Censys | [Mythic C2 Activity at Internet Scale](<https://censys.com/blog/mythic-c2/>) | 3 | 0 |
| 2026-09-15 | Silent Push | [Silent Push Tracks a Mass Phishing Operation Through Fast Flux](<https://www.silentpush.com/blog/fast-flux-phishing/?utm_source=rss&utm_medium=rss&utm_campaign=fast-flux-phishing>) | 1 | 0 |
| 2026-09-15 | Infoblox Threat Intel | [How Money Laundering, Scams, and Espionage Hide in a Web Full of Casino Garbage](<https://www.infoblox.com/blog/threat-intelligence/how-money-laundering-scams-and-espionage-hide-in-a-web-full-of-casino-garbage/>) | 24 | 2 |
| 2026-09-15 | Huntress | [Google Doc Sidebar Sends Mac and Windows Users Down Different Paths to Malware](<https://www.huntress.com/blog/google-doc-sidebar-malware-mac-windows>) | 4 | 0 |
| 2026-09-14 | Sekoia | [Exvicy: A Copycat of the ErrTraffic Malware Distribution Framework](<https://www.sekoia.com/blog/exvicy-a-copycat-of-the-errtraffic-malware-distribution-framework>) | 88 | 2 |
| 2026-09-14 | Elastic Security Labs | [The extension you never installed: KREMLIN forges Chrome's own integrity checks to steal banking sessions](<https://www.elastic.co/security-labs/threat-command/malicious-browser-extension-kremlin-banking-malware>) | 45 | 21 |
| 2026-09-10 | Microsoft Threat Intelligence | [Protecting organizations from AI-assisted executive impersonation and invoice fraud](<https://www.microsoft.com/en-us/security/blog/2026/09/10/protecting-organizations-ai-assisted-executive-impersonation-invoice-fraud/>) | 2 | 0 |
| 2026-09-10 | Zscaler ThreatLabz | [SloppyRAT: A New Tool For Ransomware Attacks](<https://www.zscaler.com/blogs/security-research/sloppyrat-new-tool-ransomware-attacks>) | 29 | 0 |
| 2026-09-10 | Unit 42 | [The Machine With Many Faces: Post-Exploitation Identity Misuse in SPIFFE/SPIRE](<https://unit42.paloaltonetworks.com/kubernetes-spiffe-spire-identity-spoofing/>) | 0 | 2 |
| 2026-09-09 | Microsoft Threat Intelligence | [Passkey-themed social engineering leads to identity and cloud compromise](<https://www.microsoft.com/en-us/security/blog/2026/09/09/passkey-themed-social-engineering-leads-identity-cloud-compromise/>) | 17 | 0 |
| 2026-09-09 | Volexity | [Mind the (Patch) Gap: Multiple Chinese Threat Actors Chain 0-day Exploits in Chrome & Windows](<https://www.volexity.com/blog/2026/09/09/mind-the-patch-gap-multiple-chinese-threat-actors-chain-0-day-exploits-in-chrome-windows/>) | 9 | 1 |
| 2026-09-09 | Proofpoint Threat Insight | [Once in a BlueMoon: Multiple State-Aligned Threat Actors Rapidly Adopt Novel Exploit Chain Using Chrome and Windows Zero-Days](<https://www.proofpoint.com/us/blog/threat-insight/once-bluemoon-multiple-state-aligned-threat-actors-rapidly-adopt-novel-exploit>) | 12 | 7 |
| 2026-09-09 | Huntress | [Grand Theft Auto VI hype leads to malware](<https://www.huntress.com/blog/fake-gta6-download-malware-analysis>) | 1 | 20 |
| 2026-09-09 | Huntress | [Phishing Attacks Serve Browser-in-the-Browser Pages, Rogue RMM Persistence](<https://www.huntress.com/blog/phishing-bitb-rmm-attacks>) | 4 | 7 |
| 2026-09-09 | Unit 42 | [Untracked Nightmares: The Threats Hiding Behind Commodity Infrastructure](<https://unit42.paloaltonetworks.com/ppi-network-malware-campaign-analysis/>) | 13 | 286 |
| 2026-09-09 | Group-IB | [Vwork: Weaponized Open-source Software as an Addon for Gigabud](<https://www.group-ib.com/blog/vwork-app-cloning-gigabud-goldfactory/>) | 9 | 0 |
| 2026-09-09 | Huntress | [Rogue ScreenConnect Installations Across Unrelated Hosts Suggest Worm-Like Activity](<https://www.huntress.com/blog/rogue-screenconnect-installations>) | 0 | 12 |
| 2026-09-08 | ANY.RUN | [HVNC Backdoor Targets LATAM Organizations with Fake Tax and DocuSign Lures](<https://any.run/cybersecurity-blog/hvnc-backdoor-targets-latam/>) | 0 | 14 |
| 2026-09-08 | Seqrite | [MacSync: The Evasive macOS Stealer Exploiting ClickFix Lures](<https://www.seqrite.com/blog/macsync-the-evasive-macos-stealer-exploiting-clickfix-lures/>) | 0 | 1 |
| 2026-09-06 | Huntress | [Critical N-able N-central Vulnerability and Active Exploitation](<https://www.huntress.com/blog/n-able-vulnerability-exploitation>) | 0 | 15 |
| 2026-09-04 | Securelist | [Angry Birds: Toy Ghouls’ new toys](<https://securelist.com/toy-ghouls-new-hivemq-and-element-backdoors/121270/>) | 2 | 1 |
| 2026-09-03 | Unit 42 | [Attackers Expose Ongoing AI Tool Use Targeting Organizations in Latin America](<https://unit42.paloaltonetworks.com/ai-tool-use-targeting-latam-orgs/>) | 4 | 9 |
| 2026-09-02 | Microsoft Threat Intelligence | [Impersonating IT support: how threat actors turn a remote session into enterprise-wide access](<https://www.microsoft.com/en-us/security/blog/2026/09/02/impersonating-it-support-threat-actors-turn-remote-session-into-enterprise-wide-access/>) | 5 | 4 |
| 2026-09-02 | Huntress | [Inside Knight Office, a New M365 AiTM Phishing Kit](<https://www.huntress.com/blog/inside-knight-office-m365-aitm-attack>) | 0 | 28 |
| 2026-09-02 | Check Point Research | [Gaming the system: how a Chinese-speaking actor turned Brazilian government sites into an SEO weapon](<https://research.checkpoint.com/2026/gaming-the-system-how-a-chinese-speaking-actor-turned-brazilian-government-sites-into-an-seo-weapon/>) | 18 | 106 |
| 2026-09-02 | Elastic Security Labs | [REVSTEALER ramps up: analysis of up-and-coming infostealer](<https://www.elastic.co/security-labs/threat-command/revstealer-credential-harvesting-infostealer>) | 7 | 8 |
| 2026-09-01 | Microsoft Threat Intelligence | [Counterfeit installers to system compromise: Tracking a deceptive software download campaign](<https://www.microsoft.com/en-us/security/blog/2026/09/01/counterfeit-installers-system-compromise-tracking-deceptive-software-download-campaign/>) | 9 | 18 |
| 2026-09-01 | Google Threat Intelligence / Mandiant | [Financially Motivated Threat Actor BREEZE COMET Targets Brazil](<https://cloud.google.com/blog/topics/threat-intelligence/financially-motivated-threat-actor-breeze-comet-targets-brazil/>) | 1 | 32 |
| 2026-09-01 | Securelist | [Mirage Kitten targeting aviation and FinTech sectors across the Middle East and Africa with a new malware set](<https://securelist.com/mirage-kitten-new-backdoors-noderabbit-pollcat/121244/>) | 37 | 3 |
| 2026-09-01 | Huntress | [The Crypto Wallet That Never Opened: Tampered Exodus Installer Hides a Modular RAT](<https://www.huntress.com/blog/exodus-crypto-wallet-installer-rat>) | 34 | 19 |
| 2026-08-31 | Huntress | [Daisy-Chaining Trust: Investigating Faronics Deploy Abuse](<https://www.huntress.com/blog/faronics-deploy-abuse>) | 0 | 1 |
| 2026-08-31 | Censys | [So Your CFO's Phone Has Been Pwned: A DFIR Journey](<https://censys.com/blog/so-your-cfos-phone-has-been-pwned-a-dfir-journey/>) | 1 | 2 |
| 2026-08-31 | Check Point Research | [Breaking the Seal: Static Deobfuscation of JSCeal’s Compiled V8 Bytecode](<https://research.checkpoint.com/2026/breaking-the-seal-static-deobfuscation-of-jsceals-compiled-v8-bytecode/>) | 0 | 5 |
| 2026-08-31 | Unit 42 | [Spring Ring: An Inside Look at Voice Phishing Campaigns in Microsoft Teams](<https://unit42.paloaltonetworks.com/spring-ring-voice-phishing-campaigns/>) | 2 | 17 |
| 2026-08-31 | Securelist | [ValleyRAT masquerading as adware](<https://securelist.com/valleyrat-backdoor-adware/121175/>) | 0 | 3 |
| 2026-08-31 | Group-IB | [Anatomy of BraZetsu: How Cybercriminals Fuel the Underground Ecosystem](<https://www.group-ib.com/blog/brazetsu-ai-enhanced-iab-marketplace/>) | 21 | 4 |
| 2026-08-29 | Microsoft Threat Intelligence | [TerminalFix campaign deploys a reverse tunnel through multistage intrusion](<https://www.microsoft.com/en-us/security/blog/2026/08/28/terminalfix-campaign-deploys-reverse-tunnel-through-multistage-intrusion/>) | 2 | 2 |
| 2026-08-28 | Censys | [The Video That Plays You: Fake MP4 File Carries Malicious Payload](<https://censys.com/blog/fake-mp4-file-carries-malicious-payload/>) | 51 | 54 |
| 2026-08-27 | Censys | [Open Directory Exposes Moobot Source Code and Ongoing Activity Post 2024 Court-Authorized Disruption](<https://censys.com/blog/open-directory-exposes-moobot-source-code-and-activity/>) | 0 | 1 |
| 2026-08-27 | Proofpoint Threat Insight | [Carry-On Compromise: TA4922 Packs PackClient](<https://www.proofpoint.com/us/blog/threat-insight/carry-compromise-ta4922-packs-packclient>) | 1 | 15 |
| 2026-08-27 | Huntress | [The AI Attack Surface: How Threat Actors Abuse Trusted AI Platforms](<https://www.huntress.com/blog/ai-attack-surface>) | 0 | 1 |
| 2026-08-26 | ReversingLabs | [Infostealers highlight malware-as-a-service trend](<https://www.reversinglabs.com/blog/infostealers-highlight-malware-as-a-service-trend>) | 15 | 5 |
| 2026-08-26 | Arctic Wolf | [Dark Caracal Reloaded: New Malware, Same Hunting Grounds](<https://arcticwolf.com/resources/blog/dark-caracal-reloaded-new-malware-same-hunting-grounds/>) | 4 | 33 |
| 2026-08-26 | Group-IB | [Tortoiseshell: New Toolset and Operational Infrastructure Exposed](<https://www.group-ib.com/blog/tortoiseshell-apt-toolset-infrastructure/>) | 2 | 84 |
| 2026-08-25 | Group-IB | [Balonx Sistema: El Rostro Detrás del PhaaS que Impacta la Banca Mexicana](<https://www.group-ib.com/blog/balonx-sistema-mexico-phaas-es/>) | 0 | 9 |
| 2026-08-25 | Darktrace | [Why Trust is the New Attack Surface: Mid-Year Threat Update 2026](<https://www.darktrace.com/blog/why-trust-is-the-new-attack-surface-darktraces-mid-year-threat-update-2026>) | 0 | 13 |
| 2026-08-25 | Censys | [What the ERMAC Source Leak Says About HookBot](<https://censys.com/blog/ermac-source-leak-hookbot/>) | 5 | 17 |
| 2026-08-25 | ANY.RUN | [A Single Canadian Tax Lure Spread into a 46-Country, US-First RMM Campaign](<https://any.run/cybersecurity-blog/us-campaign-malware-analysis/>) | 6 | 23 |
| 2026-08-24 | The DFIR Report | [BengalSEO Part 1: Anatomy of the Operation](<https://thedfirreport.com/2026/08/24/bengalseo-part-1-anatomy-of-the-operation/>) | 17 | 10 |
| 2026-08-24 | Darktrace | [Securing AI Agents: What NCSC Guidance Means for Security Teams](<https://www.darktrace.com/blog/ai-agents-securing-the-path-from-intent-to-action>) | 0 | 13 |
| 2026-08-23 | Darktrace | [When AI Becomes the Lure: A Fake Gemini Installer Delivers Vidar](<https://www.darktrace.com/blog/when-ai-becomes-the-lure-a-fake-gemini-installer-delivers-vidar>) | 2 | 16 |
| 2026-08-21 | Securelist | [The invisible passenger in your car](<https://securelist.com/android-head-unit-malware/121106/>) | 10 | 12 |
| 2026-08-20 | Red Canary | [Intelligence Insights: August 2026](<https://redcanary.com/blog/threat-intelligence/intelligence-insights-august-2026/>) | 0 | 2 |
| 2026-08-20 | Google Threat Intelligence / Mandiant | [Going with the Flow(s): Distinct Clusters Target Individuals of Interest to Russia](<https://cloud.google.com/blog/topics/threat-intelligence/distinct-clusters-target-individuals-of-interest-to-russia/>) | 5 | 7 |
| 2026-08-20 | Silent Push | [How Peer2Profit and Astroproxy Turn Your Bandwidth Into Someone Else's Product](<https://www.silentpush.com/blog/peer2profit-astroproxy/?utm_source=rss&utm_medium=rss&utm_campaign=peer2profit-astroproxy>) | 0 | 9 |
| 2026-08-20 | ANY.RUN | [North Korean IT Workers Scheme: Detection IOCs and Tactics for Government and Corporate SOCs](<https://any.run/cybersecurity-blog/how-to-protect-organization-against-north-korean-it-workers/>) | 0 | 8 |
| 2026-08-19 | Huntress | [Post-DEF CON Phishing Uses Malicious Google Doc to Deliver Malware](<https://www.huntress.com/blog/defcon-phishing-google-doc-malware>) | 17 | 15 |
| 2026-08-19 | ANY.RUN | [Hunt Malware & Phishing Threats with ANY.RUN for Proactive Enterprise Security](<https://any.run/cybersecurity-blog/proactive-threat-hunting/>) | 0 | 3 |
| 2026-08-19 | Group-IB | [Balonx Sistema: The Face Behind the PhaaS Affecting Mexican Banking](<https://www.group-ib.com/blog/balonx-sistema-mexico-phaas/>) | 0 | 9 |
| 2026-08-18 | Silent Push | [Weekly Recap: Rogue AI Models, $88M Bitcoin Theft, Water-System Attacks and Dangling DNS Hijacks](<https://thehackernews.com/2026/08/weekly-recap-rogue-ai-models-88m.html#new_tab?utm_source=rss&utm_medium=rss&utm_campaign=weekly-recap-rogue-ai-models-88m-bitcoin-theft-water-system-attacks-and-dangling-dns-hijacks>) | 0 | 1 |
| 2026-08-18 | Check Point Research | [Thousands of Hacked WordPress Sites, One Operation: Unmasking StopAndProtect](<https://research.checkpoint.com/2026/thousands-of-hacked-wordpress-sites-one-operation-unmasking-stopandprotect/>) | 1 | 31 |
| 2026-08-18 | ANY.RUN | [Mirage2FA Hijacks Companies’ Microsoft 365 Sessions, with Over 4K Victims in the US](<https://any.run/cybersecurity-blog/mirage2fa-phishing-targets-us-companies/>) | 21 | 67 |
| 2026-08-18 | Recorded Future Insikt Group | [CopyCop Targets AI Investment in Armenia](<https://www.recordedfuture.com/blog/copycop-targets-ai-investment>) | 2 | 0 |
| 2026-08-17 | Zscaler ThreatLabz | [C2Looper: A New Backdoor Likely Tied To Ransomware With GitHub C2](<https://www.zscaler.com/blogs/security-research/c2looper-new-backdoor-likely-tied-ransomware-github-c2>) | 0 | 4 |
| 2026-08-17 | Seqrite | [Operation QUICSILVER: China-Nexus Actor Targets Myanmar Diplomats via VHD-Delivered Go Backdoor](<https://www.seqrite.com/blog/operation-quicsilver-china-nexus-actor-targets-myanmar-diplomats-via-vhd-delivered-go-backdoor/>) | 4 | 13 |
| 2026-08-14 | Securelist | [APT group HoneyMyte upgrades CoolClient: the backdoor gets a kernel-level Windows rootkit](<https://securelist.com/honeymyte-coolclient-driver-rootkit/121028/>) | 0 | 15 |
| 2026-08-13 | Fortinet Threat Research | [Multi-Functional Linux Botnet “Evooo1Bot”](<https://feeds.fortinet.com/~/967797734/0/fortinet/blog/threat-research~MultiFunctional-Linux-Botnet-EvoooBot>) | 0 | 1 |
| 2026-08-13 | Infoblox Threat Intel | [$7 Million in Expired Domains Fuel a Streaming Empire with a Malware Secret](<https://www.infoblox.com/blog/threat-intelligence/7-million-in-expired-domains-fuel-a-streaming-empire-with-a-malware-secret/>) | 6 | 14 |
| 2026-08-13 | Infoblox Threat Intel | [Dropcatch Scavengers: Expired Malicious Domains Become Cash Cows](<https://www.infoblox.com/blog/threat-intelligence/dropcatch-scavengers-expired-malicious-domains-become-cash-cows/>) | 0 | 4 |
| 2026-08-13 | Securelist | [Armored Likho expands its cyber-espionage toolkit](<https://securelist.com/armored-likho-still-toolkit/121033/>) | 0 | 25 |
| 2026-08-13 | K7 Labs | [When SQL Server Becomes the Initial Launcher: A Deep Dive into Weaxor Ransomware Execution](<https://labs.k7computing.com/index.php/when-sql-server-becomes-the-initial-launcher-a-deep-dive-into-weaxor-ransomware-execution/>) | 0 | 1 |
| 2026-08-12 | Huntress | [Akira Hits Safe Mode: Ransomware Rebooting Around EDR](<https://www.huntress.com/blog/akira-hits-safe-mode-ransomware-rebooting-around-edr>) | 0 | 3 |
| 2026-08-12 | Group-IB | [Gone with the WindRelay: A New Malware Combo Behind a Growing Fraud Scheme](<https://www.group-ib.com/blog/windrelay-nfc-spynote-rat-combo-fraud/>) | 0 | 33 |
| 2026-08-11 | Zscaler ThreatLabz | [CaptiveCrunch: Midnight Blizzard Weaponizes Hotel Wi-Fi Captive Portals to Steal Microsoft 365 Credentials](<https://www.zscaler.com/blogs/security-research/captivecrunch-midnight-blizzard-weaponizes-hotel-wi-fi-captive-portals>) | 2 | 0 |
| 2026-08-11 | Zscaler ThreatLabz | [Tracking Shai-Hulud: Inside the ChainDrop NPM Worm](<https://www.zscaler.com/blogs/security-research/tracking-shai-hulud-inside-chaindrop-npm-worm>) | 3 | 3 |
| 2026-08-11 | Check Point Research | [Shattering the Dream – When a Job Offer Becomes a Zero-Day Attack](<https://research.checkpoint.com/2026/shattering-the-dream-when-a-job-offer-becomes-a-zero-day-attack/>) | 0 | 45 |
| 2026-08-11 | Securelist | [Head Mare APT is exploiting vulnerabilities in an unpatched TrueConf server to deliver PhantomCore and PhantomGraph to video conference participants](<https://securelist.com/tr/head-mare-targets-trueconf-server-with-phantomcore/120988/>) | 0 | 8 |
| 2026-08-11 | Securelist | [Project CAV3RN continues: Google Apps Script as C2 relay and DNS-based C2 channel selection](<https://securelist.com/project-cav3rn-continues/120991/>) | 0 | 9 |
| 2026-08-11 | Unit 42 | [Kimwolf v7: An Evolution of the Kimwolf Botnet](<https://unit42.paloaltonetworks.com/kimwolf-v7-botnet-malware/>) | 0 | 22 |
| 2026-08-10 | Unit 42 | [The Permanent Threat: Analyzing Aeternum’s Blockchain-Based C2 Operations and Communications](<https://unit42.paloaltonetworks.com/aeternum-blockchain-c2-analysis/>) | 1 | 46 |
| 2026-08-10 | Zscaler ThreatLabz | [Abyssos: Technical Analysis of a New Modular RAT](<https://www.zscaler.com/blogs/security-research/abyssos-technical-analysis-new-modular-rat>) | 0 | 4 |
| 2026-08-10 | Microsoft Threat Intelligence | [DeadLock ransomware: Breaking down a Rust-based encryptor with decentralized recovery infrastructure](<https://www.microsoft.com/en-us/security/blog/2026/08/10/deadlock-ransomware-breaking-down-a-rust-based-encryptor-with-decentralized-recovery-infrastructure/>) | 0 | 8 |
| 2026-08-10 | ANY.RUN | [Smile, You’re on Camera. Part 2: Hiring Lazarus APT’s IT Workers in a Fake DeFi Startup](<https://any.run/cybersecurity-blog/lazarus-group-it-workers-investigation-part-two/>) | 0 | 9 |
| 2026-08-07 | Elastic Security Labs | [Living off the coding agent: Two tales of tunnels and LaunchAgents](<https://www.elastic.co/security-labs/threat-command/coding-agent-launchagent-tunnel-detection>) | 0 | 1 |
| 2026-08-06 | Unit 42 | [ChainDrop: Inside a Self-Propagating npm Worm](<https://unit42.paloaltonetworks.com/chaindrop-npm-worm-analysis/>) | 9 | 0 |
| 2026-08-06 | Google Threat Intelligence / Mandiant | [UNC6671 Rebrands: Multi-Brand Vishing Extortion Targets Financial Services and Enterprise Cloud Environments](<https://cloud.google.com/blog/topics/threat-intelligence/unc6671-targets-financial-services-and-enterprise-cloud-environments/>) | 19 | 54 |
| 2026-08-06 | Huntress | [Mac Malware Drains Crypto Wallets Via Fake CAPTCHA Scam](<https://www.huntress.com/blog/mac-crypto-draining-malware>) | 0 | 8 |
| 2026-08-06 | Unit 42 | [Token Jacking: Cybercriminals Could Be Stealing Your AI Resources](<https://unit42.paloaltonetworks.com/ai-token-jacking/>) | 0 | 18 |
| 2026-08-06 | Elastic Security Labs | [Shai-Hulud strikes again: CHAINDROP worm hits 400+ npm packages](<https://www.elastic.co/security-labs/threat-command/shai-hulud-chaindrop-npm-supply-chain>) | 5 | 0 |
| 2026-08-05 | Microsoft Threat Intelligence | [From open lures to cloaked gates: How a macOS ClickFix campaign learned to hide](<https://www.microsoft.com/en-us/security/blog/2026/08/05/macos-clickfix-campaign-learned-hide/>) | 0 | 17 |
| 2026-08-05 | ReversingLabs | [How to Leverage Spectra Analyze's Search for SVG Analysis](<https://www.reversinglabs.com/blog/spectra-analyze-search-function-for-svg-analysis>) | 0 | 1 |
| 2026-08-05 | Huntress | [Inside an Oracle Database SQL Injection Attack \| Huntress](<https://www.huntress.com/blog/khunt-malware-sql-injection-oracle>) | 0 | 1 |
| 2026-08-04 | Microsoft Threat Intelligence | [ChainDrop supply chain compromise: Anatomy of a self-propagating worm](<https://www.microsoft.com/en-us/security/blog/2026/08/04/chaindrop-supply-chain-compromise-anatomy-self-propagating-worm/>) | 7 | 0 |
| 2026-08-04 | Fortinet Threat Research | [QuickFox Supply Chain Attack Used to Deploy FDMTP Implant](<https://feeds.fortinet.com/~/966214247/0/fortinet/blog/threat-research~QuickFox-Supply-Chain-Attack-Used-to-Deploy-FDMTP-Implant>) | 0 | 54 |
| 2026-08-04 | Huntress | [Bank of America Phishing Email Delivers ScreenConnect Malware](<https://www.huntress.com/blog/bank-spam-rmm>) | 0 | 16 |
| 2026-08-04 | Unit 42 | [Almost Half of Malware Samples Communicate Direct to IP](<https://unit42.paloaltonetworks.com/malware-bypass-dns-direct-to-ip/>) | 0 | 16 |
| 2026-08-03 | Zscaler ThreatLabz | [Targeted Attack on Government Entities in the Middle East \| Part 2](<https://www.zscaler.com/blogs/security-research/targeted-attack-government-entities-middle-east-part-2>) | 2 | 4 |
| 2026-08-03 | Bitdefender Labs | [Fake Xeno Roblox Cheats Deliver Powerful Java Stealer Through Discord and Forums](<https://www.bitdefender.com/en-us/blog/labs/fake-xeno-roblox-discord-executor>) | 0 | 15 |
| 2026-08-03 | K7 Labs | [Octagon: Technical Analysis of a Fake Bahrain Civil Defense Application](<https://labs.k7computing.com/index.php/octagon-technical-analysis-of-a-fake-bahrain-civil-defense-application/>) | 0 | 5 |
| 2026-07-31 | Microsoft Threat Intelligence | [CaptiveCrunch: Midnight Blizzard targets travelers worldwide for malware delivery and credential theft](<https://www.microsoft.com/en-us/security/blog/2026/07/31/captivecrunch-midnight-blizzard-targets-travelers-worldwide-for-malware-delivery-and-credential-theft/>) | 4 | 13 |
| 2026-07-31 | Censys | [DarkSword's Panel Sprawl: How One Body Hash Unravels a Six-Panel, Two-Codebase Operator Cluster](<https://censys.com/blog/darkswords-panel-sprawl/>) | 1 | 46 |
| 2026-07-31 | Huntress | [Device Code Phishing Keeps Evolving. Here’s What to Watch For](<https://www.huntress.com/blog/device-code-phishing-evolving-threats>) | 0 | 4 |
| 2026-07-31 | Unit 42 | [The Xcode Assassin Returns: A Deep Dive Into the Latest XCSSET Version](<https://unit42.paloaltonetworks.com/xcsset-v40-malware-analysis/>) | 0 | 76 |
| 2026-07-30 | Censys | [A Chill in the Air: Cl0p Targets Windchill, Another Enterprise Software Product](<https://censys.com/blog/cl0p-targets-windchill/>) | 0 | 4 |
| 2026-07-30 | Securelist | [OctLurk and SilkLurk: newly identified tailored backdoors in cyber-espionage campaign in Central Asia](<https://securelist.com/octlurk-silklurk-backdoors-central-asia/120840/>) | 3 | 37 |
| 2026-07-30 | Unit 42 | [Chinese-Speaking Threat Actor Harnesses AI Models for Autonomous Cyberattacks](<https://unit42.paloaltonetworks.com/autonomous-ai-cyber-attack-campaign/>) | 0 | 3 |
| 2026-07-30 | Securelist | [Toy Ghouls’ new toy: the GenieLocker ransomware](<https://securelist.com/genielocker-ransomware-for-windows-linux-and-esxi/120843/>) | 0 | 3 |
| 2026-07-30 | Group-IB | [XMRig Covert Ops: The Cryptomining Campaign That Abuses Trusted Access and Deploys Forensic Smokescreens](<https://www.group-ib.com/blog/xmrig-covert-linux-pam-abuse/>) | 0 | 1 |
| 2026-07-29 | Huntress | [Reverse Engineering the Six Stages of MacSync Stealer and RAT](<https://www.huntress.com/blog/macsync-stealer-rat-reverse-engineering>) | 0 | 12 |
| 2026-07-28 | Darktrace | [What the OpenAI and Hugging Face Incident Means for Defenders](<https://www.darktrace.com/blog/when-ai-agents-go-off-script-what-the-openai-and-hugging-face-incident-means-for-defenders>) | 0 | 13 |
| 2026-07-28 | Huntress | [Credential Stuffing Campaign Hits SonicWall \| Huntress SOC Tracking](<https://www.huntress.com/blog/sonicwall-credential-stuffing-campaign>) | 0 | 5 |
| 2026-07-28 | Securelist | [Mirage Kitten targets Middle East and Africa region with new malware](<https://securelist.com/mirage-kitten-new-tools/120811/>) | 2 | 9 |
| 2026-07-27 | Zscaler ThreatLabz | [Helpdesk Hijackers: Teams Vishing, Quick Assist, and GoGRPC Backdoor](<https://www.zscaler.com/blogs/security-research/helpdesk-hijackers-teams-vishing-quick-assist-and-gogrpc-backdoor>) | 0 | 15 |
| 2026-07-27 | Darktrace | [When Guardrails Break: Why Securing AI Requires Behavioral Detection and Autonomous Containment](<https://www.darktrace.com/blog/when-guardrails-break-why-securing-ai-requires-behavioral-detection-and-autonomous-containment>) | 0 | 13 |
| 2026-07-26 | Darktrace | [Uncovering a Multi-Stage Ransomware Attack Through Behavioral Detection](<https://www.darktrace.com/blog/hiding-in-plain-sight-uncovering-a-multi-stage-ransomware-attack-through-behavioral-detection>) | 0 | 17 |
| 2026-07-25 | Darktrace | [When AI Infrastructure Becomes Part of the Attack Surface](<https://www.darktrace.com/blog/when-ai-infrastructure-becomes-part-of-the-attack-surface>) | 0 | 17 |
| 2026-07-23 | Red Canary | [Intelligence Insights: July 2026](<https://redcanary.com/blog/threat-intelligence/intelligence-insights-july-2026/>) | 3 | 2 |
| 2026-07-23 | Microsoft Threat Intelligence | [Email threat landscape: Q2 2026 trends and insights](<https://www.microsoft.com/en-us/security/blog/2026/07/23/email-threat-landscape-q2-2026-trends-and-insights/>) | 0 | 15 |
| 2026-07-23 | Proofpoint Threat Insight | [TA488 Targets Zimbra Mailservers with Half-Click Exploits](<https://www.proofpoint.com/us/blog/threat-insight/ta488-targets-zimbra-mailservers-half-click-exploits>) | 0 | 4 |
| 2026-07-23 | Group-IB | [JadeProx: Tracing a China-nexus Operation Through an OPSEC Mistake](<https://www.group-ib.com/blog/jadeprox-china-nexus-triback-loader/>) | 0 | 45 |
| 2026-07-22 | Huntress | [Inside FakeAgent: How a Claude Desktop Malvertising Campaign Hit 29 Organizations with SectopRAT](<https://www.huntress.com/blog/fakeagent-claude-desktop-malvertising-ends-in-dotnet-rat>) | 0 | 30 |
| 2026-07-22 | Fortinet Threat Research | [Inside a TrickBot Variant Using DNS Tunneling for C2](<https://feeds.fortinet.com/~/961655441/0/fortinet/blog/threat-research~Inside-a-TrickBot-Variant-Using-DNS-Tunneling-for-C>) | 0 | 6 |
| 2026-07-22 | Seqrite | [Abusing Trusted Business Workflows: A Multi-Stage Phantom Stealer Campaign](<https://www.seqrite.com/blog/abusing-trusted-business-workflows-a-multi-stage-phantom-stealer-campaign/>) | 0 | 5 |
| 2026-07-21 | Infoblox Threat Intel | [The Procurement Trap: Inside an AiTM Campaign Targeting Global Institutions](<https://www.infoblox.com/blog/threat-intelligence/the-procurement-trap-inside-an-aitm-campaign-targeting-global-institutions/>) | 0 | 1 |
| 2026-07-21 | ReversingLabs | [Hidden in plain sight: How SVGs carry malicious scripts](<https://www.reversinglabs.com/blog/how-svgs-carry-dangerous-scripts>) | 0 | 26 |
| 2026-07-21 | Censys | [Censys Is The OmniFeed: Crunch Your Own Threat Intelligence](<https://censys.com/blog/censys-is-the-omnifeed-crunch-your-own-threat-intelligence/>) | 0 | 3 |
| 2026-07-21 | Securelist | [New Project CAV3RN module abuses Outlook calendar events for C2 and DNS AAAA records for configuration recovery](<https://securelist.com/project-cav3rn-cyberespionage-framework-using-outlook-and-dns/120757/>) | 0 | 7 |
| 2026-07-21 | ANY.RUN | [Kali365 Targets US Organizations with Data Theft via Device Code Phishing](<https://any.run/cybersecurity-blog/kali365-phishing-targeting-us/>) | 1 | 33 |
| 2026-07-20 | Proofpoint Threat Insight | [Unpacking “Cruciferra”: An Analysis of a Sophisticated Crypter Service](<https://www.proofpoint.com/us/blog/threat-insight/unpacking-cruciferra-analysis-sophisticated-crypter-service>) | 2 | 46 |
| 2026-07-20 | Zscaler ThreatLabz | [Targeted Attack on Government Entities in the Middle East \| Part 1](<https://www.zscaler.com/blogs/security-research/targeted-attack-government-entities-middle-east-part-1>) | 1 | 3 |
| 2026-07-18 | Elastic Security Labs | [New North Korean campaign uses fake coding interviews to steal developer credentials](<https://www.elastic.co/security-labs/threat-command/contagious-interview-malware-svg-steganography>) | 0 | 16 |
| 2026-07-17 | Huntress | [It’s Not Safe To Pay SafePa](<https://www.huntress.com/blog/its-not-safe-to-pay-safepay>) | 0 | 1 |
| 2026-07-17 | Seqrite | [Behind the Refund: From GST Phishing to Remcos RAT Through a Multi-Stage .NET Infection Chain](<https://www.seqrite.com/blog/behind-the-refund-from-gst-phishing-to-remcos-rat-through-a-multi-stage-net-infection-chain/>) | 0 | 6 |
| 2026-07-16 | Microsoft Threat Intelligence | [ACR Stealer: Two observed intrusion chains amid increased threat activity](<https://www.microsoft.com/en-us/security/blog/2026/07/16/acr-stealer-two-observed-intrusion-chains-amid-increased-threat-activity/>) | 0 | 16 |
| 2026-07-16 | Securelist | [HelloNet campaign: new malicious modules launched through the ViPNet update system](<https://securelist.com/tr/hellonet-vipnet/120700/>) | 0 | 10 |
| 2026-07-16 | Fortinet Threat Research | [The TTF Trap: A Global Campaign of a Low-Detection Lua Loader](<https://feeds.fortinet.com/~/960560447/0/fortinet/blog/threat-research~The-TTF-Trap-A-Global-Campaign-of-a-LowDetection-Lua-Loader>) | 5 | 3 |
| 2026-07-16 | Securelist | [GoSerpent: a persistent threat evolves with sophisticated data collection and exfiltration](<https://securelist.com/goserpent-backdoor-in-southeast-asia/120687/>) | 0 | 11 |
| 2026-07-16 | ANY.RUN | [Hidden Infrastructure Exposed: ANY.RUN Reveals Hijacked Gov Websites Delivering Malware](<https://any.run/cybersecurity-blog/phantomenigma-research/>) | 0 | 76 |
| 2026-07-16 | Microsoft Threat Intelligence | [Unpacking the AsyncAPI npm supply chain compromise and import-time payload delivery](<https://www.microsoft.com/en-us/security/blog/2026/07/15/unpacking-asyncapi-npm-supply-chain-compromise-import-time-payload-delivery/>) | 0 | 14 |
| 2026-07-16 | Elastic Security Labs | [TELEPUZ: a modular MaaS malware spreading via CLICKFIX-VIDAR chains](<https://www.elastic.co/security-labs/threat-command/telepuz-maas-malware-clickfix>) | 0 | 17 |
| 2026-07-15 | Unit 42 | [The npm Threat Landscape: Attack Surface and Mitigations (Updated July 15)](<https://unit42.paloaltonetworks.com/monitoring-npm-supply-chain-attacks/>) | 0 | 20 |
| 2026-07-15 | Zscaler ThreatLabz | [ClaudeFix: Shared Claude Chats Meet ClickFix](<https://www.zscaler.com/blogs/security-research/claudefix-shared-claude-chats-meet-clickfix>) | 0 | 1 |
| 2026-07-15 | Unit 42 | [TuxBot v3: Inside an IoT Botnet Framework With LLM-Assisted Development](<https://unit42.paloaltonetworks.com/tuxbot-v3-evolution-iot-botnet/>) | 0 | 56 |
| 2026-07-15 | Securelist | [OkoBot: new sophisticated malware framework targets cryptocurrency users](<https://securelist.com/okobot-framework-targets-cryptocurrency-wallets/120660/>) | 0 | 4 |
| 2026-07-14 | Seqrite | [Operation ShadowRecruit: A Recruitment-Themed Malware Campaign Leveraging ControlR and Google Sheets to Target Indian Job Seekers](<https://www.seqrite.com/blog/operation-shadowrecruit-a-recruitment-themed-malware-campaign-leveraging-controlr-and-google-sheets-to-target-indian-job-seekers/>) | 0 | 8 |
| 2026-07-14 | ANY.RUN | [​​Kratos PhaaS Targets US and EU: How to Reduce Microsoft 365 Account Takeover Risk​](<https://any.run/cybersecurity-blog/kratos-phaas-account-takeover/>) | 0 | 20 |
| 2026-07-14 | ESET WeLiveSecurity | [Forgotten UEFI shims undermining Secure Boot](<https://www.welivesecurity.com/en/eset-research/forgotten-uefi-shims-undermining-secure-boot/>) | 0 | 12 |
| 2026-07-09 | Microsoft Threat Intelligence | [GigaWiper: Anatomy of a destructive backdoor assembled from multiple malware](<https://www.microsoft.com/en-us/security/blog/2026/07/09/gigawiper-anatomy-of-a-destructive-backdoor-assembled-from-multiple-malware/>) | 0 | 10 |
| 2026-07-09 | Huntress | [CitrixBleed 2 (CVE-2025-5777) 7Steps to Dragonforce Ransomware \| Huntress](<https://www.huntress.com/blog/citrixbleed-2-dragonforce-ransomware>) | 0 | 6 |
| 2026-07-08 | ReversingLabs | [Hunting Device Code Phishing Pages](<https://www.reversinglabs.com/blog/device-code-phishing-walkthrough>) | 0 | 1 |
| 2026-07-08 | Elastic Security Labs | [ClickFix to Cash-Out: Anatomy of a Mexican Banking-Fraud Toolkit](<https://www.elastic.co/security-labs/threat-command/mexican-banking-fraud-scmbanker-ref6045>) | 0 | 42 |
| 2026-07-07 | Unit 42 | [Vidar Stealer Unmasked: Code Signing Abuse, Go Loaders and File Inflation](<https://unit42.paloaltonetworks.com/vidar-stealer-xmrig-miner-campaign-analysis/>) | 0 | 7 |
| 2026-07-07 | ANY.RUN | [Banana RAT Evolves: Comparing Two Recent Branches Through ANY.RUN](<https://any.run/cybersecurity-blog/banana-rat-evolution-analysis/>) | 0 | 6 |
| 2026-07-07 | Infoblox Threat Intel | [Fake Installers, Fake Reviews, Fake Services – Real Proxies, Real Victims](<https://www.infoblox.com/blog/threat-intelligence/fake-installers-fake-reviews-fake-services-real-proxies-real-victims/>) | 0 | 13 |
| 2026-07-07 | Huntress | [Meta Phishers Abuse Business Account Manager Service \| Huntress](<https://www.huntress.com/blog/meta-business-manager-phishing>) | 0 | 4 |
| 2026-07-07 | Seqrite | [From Invoice to AnyDesk: Uncovering a Phishing Campaign Targeting Russian Aerospace Organizations](<https://www.seqrite.com/blog/from-invoice-to-anydesk-uncovering-a-phishing-campaign-targeting-russian-aerospace-organizations/>) | 0 | 7 |
| 2026-07-06 | Check Point Research | [Cavern Manticore: Exposing Iran-Linked Modular C2 Framework](<https://research.checkpoint.com/2026/cavern-manticore-exposing-iran-linked-modular-c2-framework/>) | 0 | 8 |
| 2026-07-06 | Huntress | [Plain Text Passwords: The Risks of Storing Them](<https://www.huntress.com/blog/dangers-of-storing-unencrypted-passwords>) | 0 | 2 |
| 2026-07-03 | K7 Labs | [Boss Scam: Don’t Trust Every “Urgent” Email or WhatsApp Message from Your Boss!](<https://labs.k7computing.com/index.php/boss-scam-dont-trust-every-urgent-message-from-your-boss/>) | 0 | 3 |
| 2026-07-03 | Securelist | [Armored Likho digging a snake pit: inside the covert BusySnake Stealer campaign](<https://securelist.com/tr/armored-likho-apt-with-busysnake-stealer/120292/>) | 0 | 17 |
| 2026-07-02 | Censys | [Roblox, Minecraft, and the Insidious Internet for Children](<https://censys.com/blog/roblox-minecraft-and-the-insidious-internet-for-children/>) | 0 | 40 |
| 2026-07-02 | Zscaler ThreatLabz | [Indirect Prompt Injection in Web Content Targets AI Agents](<https://www.zscaler.com/blogs/security-research/indirect-prompt-injection-web-content-targets-ai-agents>) | 0 | 21 |
| 2026-07-01 | Securelist | [The SOC Files: ScreenConnect masked as freeware. An inside look at a large-scale campaign](<https://securelist.com/tr/the-soc-files-screenconnect-campaign-with-asyncrat/120472/>) | 0 | 29 |
| 2026-07-01 | Unit 42 | [Phantom Squatting: AI-Hallucinated Domains as a Software Supply Chain Vector](<https://unit42.paloaltonetworks.com/phantom-squatting-hallucinated-web-domains/>) | 0 | 4 |
| 2026-06-30 | Sekoia | [Don't Eat the ChocoPoCs: Trojanised PoCs Hit Researchers](<https://www.sekoia.com/blog/dont-eat-the-chocopocs-how-vulnerability-researchers-were-repeatedly-targeted-by-trojanised-exploits>) | 0 | 13 |
| 2026-06-30 | Securelist | [ToddyCat: your hidden email assistant. Part 2](<https://securelist.com/toddycat-apt-umbrij-tool-and-oauth/120251/>) | 0 | 10 |
| 2026-06-30 | Cyble | [Glitch SPY: An Emerging Android RAT Distributed Through a Fake Polish Rental App](<https://cyble.com/blog/glitch-spy-rat-distributed-via-fake-polish-app/>) | 0 | 5 |
| 2026-06-30 | Darktrace | [Cybersecurity for the Sports Sector: The Threats Facing a Digitized Industry in 2026](<https://www.darktrace.com/blog/cybersecurity-for-the-sports-sector-the-threats-facing-a-digitized-industry-in-2026>) | 0 | 13 |
| 2026-06-29 | The DFIR Report | [From Bing Search to Ransomware: Bumblebee and AdaptixC2 Deliver Akira](<https://thedfirreport.com/2026/06/29/from-bing-search-to-ransomware-bumblebee-and-adaptixc2-deliver-akira-3/>) | 0 | 38 |
| 2026-06-29 | Securelist | [The Gentlemen are knocking: сustom backdoors and evolving tactics](<https://securelist.com/the-gentlemen-raas/120447/>) | 0 | 1 |
| 2026-06-29 | Darktrace | [Protecting Stadiums & Events with AI](<https://www.darktrace.com/blog/protecting-global-stadiums-and-events-with-self-learning-ai>) | 0 | 13 |
| 2026-06-29 | Huntress | [Defence Impairment Olympics](<https://www.huntress.com/blog/mimikatz-credential-dumping-defence-impairment>) | 0 | 6 |
| 2026-06-28 | Darktrace | [The Curious Case of Prompt Language Analysis](<https://www.darktrace.com/blog/a-new-security-challenge-the-curious-case-of-prompt-language-analysis>) | 0 | 13 |
| 2026-06-27 | Darktrace | [Shadow AI Detection: The First Step Toward Securing AI](<https://www.darktrace.com/blog/shadow-ai-detection-the-first-step-toward-securing-ai>) | 0 | 13 |
| 2026-06-26 | Securelist | [Beware of the license manager: how a Schneider Electric software vulnerability puts industrial facilities at risk](<https://securelist.com/tr/schneider-electric-cve-2024-2658-vulnerability/120436/>) | 0 | 2 |
| 2026-06-26 | Fortinet Threat Research | [From CI/CD to Cloud Data: How Shai Hulud Persistence Leads to Redshift Breach](<https://feeds.fortinet.com/~/958459373/0/fortinet/blog/threat-research~From-CICD-to-Cloud-Data-How-Shai-Hulud-Persistence-Leads-to-Redshift-Breach>) | 0 | 1 |
| 2026-06-26 | Seqrite | [Operation DragonReturn: China-Nexus Cyber Espionage Campaign Targeting Govt. of India/MoF Tax Infrastructure via Multi-Stage DcRAT Deployment](<https://www.seqrite.com/blog/operation-dragonreturn-china-nexus-cyber-espionage-campaign-targeting-govt-of-india-mof-tax-infrastructure-via-multi-stage-dcrat-deployment/>) | 0 | 37 |
| 2026-06-25 | Unit 42 | [CL-STA-1062 Targets Southeast Asian Governments and Critical Infrastructure](<https://unit42.paloaltonetworks.com/cl-sta-1062-tinyrct-backdoor/>) | 0 | 12 |
| 2026-06-25 | Google Threat Intelligence / Mandiant | [STOCKSTAY Another Day: The Latest Addition to Turla’s Intelligence Gathering Apparatus](<https://cloud.google.com/blog/topics/threat-intelligence/stockstay-turla-intelligence-gathering/>) | 0 | 9 |
| 2026-06-25 | Infoblox Threat Intel | [From San Pedro to Salinas: How a Chinese Framework “DCloud Uni-App” Powers a Global Scam Economy](<https://www.infoblox.com/blog/threat-intelligence/from-san-pedro-to-salinas-how-a-chinese-framework-dcloud-uni-app-powers-a-global-scam-economy/>) | 0 | 7 |
| 2026-06-24 | Microsoft Threat Intelligence | [StealC and Amadey: Breaking down infostealers and the cybercrime services that deliver them](<https://www.microsoft.com/en-us/security/blog/2026/06/24/stealc-and-amadey-breaking-down-infostealers-and-the-cybercrime-services-that-deliver-them/>) | 0 | 39 |
| 2026-06-24 | Google Threat Intelligence / Mandiant | [Zero-Day Exploitation of Vulnerability (CVE-2026-20245) in Cisco Catalyst SD-WAN Manager](<https://cloud.google.com/blog/topics/threat-intelligence/zero-day-exploitation-cisco-catalyst-sd-wan-manager/>) | 0 | 8 |
| 2026-06-24 | Securelist | [StrikeShark: investigating a new campaign delivering Cobalt Strike through SharkLoader](<https://securelist.com/strikeshark-campaign/120326/>) | 0 | 12 |
| 2026-06-23 | Unit 42 | [OpenClaw’s Skill Marketplace and the Emerging AI Supply Chain Threat](<https://unit42.paloaltonetworks.com/openclaw-ai-supply-chain-risk/>) | 0 | 15 |
| 2026-06-23 | SentinelLabs | [macOS.Gaslight \| Rust Backdoor Turns Prompt Injection on the Analyst, Not the Sandbox](<https://www.sentinelone.com/labs/macos-gaslight-rust-backdoor-turns-prompt-injection-on-the-analyst-not-the-sandbox/>) | 0 | 5 |
| 2026-06-23 | Zscaler ThreatLabz | [Payouts King Ransomware Initial Access Broker Deploys New Edgecution Malware](<https://www.zscaler.com/blogs/security-research/payouts-king-ransomware-initial-access-broker-deploys-new-edgecution>) | 0 | 2 |
| 2026-06-23 | Bitdefender Labs | [Fake shops target shoppers across Europe with fake Samsung deals, counterfeit goods and World Cup scams](<https://www.bitdefender.com/en-us/blog/labs/fake-shops-europe-samsung-world-cup-scams>) | 0 | 29 |
| 2026-06-23 | ANY.RUN | [EvilTokens: How “Ghost” Code Threatens US and European Businesses](<https://any.run/cybersecurity-blog/eviltokens-ghost-code-analysis/>) | 0 | 1 |
| 2026-06-22 | Sekoia | [ErrTraffic: A Growing ClickFix Malware Distribution Framework](<https://www.sekoia.com/blog/unveiling-errtraffic-inside-a-growing-clickfix-malware-distribution-framework>) | 0 | 7 |
| 2026-06-22 | Securelist | [A VBScript campaign distributed through WhatsApp deploying RMM software](<https://securelist.com/whatsapp-vbs-rmm-campaign/120290/>) | 0 | 6 |
| 2026-06-19 | Seqrite | [Threat Actors Weaponizing RAR Archives to Target Thailand’s Healthcare Sector](<https://www.seqrite.com/blog/threat-actors-weaponizing-rar-archives-to-target-thailands-healthcare-sector/>) | 0 | 8 |
| 2026-06-19 | Elastic Security Labs | [Lost in relocation: analysis of a new loader distributing CASTLESTEALER](<https://www.elastic.co/security-labs/threat-command/oxloader-malware-loader-infostealer>) | 0 | 9 |
| 2026-06-18 | Zscaler ThreatLabz | [SmartApeSG Launches Okendo Reviews Supply Chain Attack](<https://www.zscaler.com/blogs/security-research/smartapesg-launches-okendo-reviews-supply-chain-attack>) | 0 | 6 |
| 2026-06-18 | Huntress | [Cybercrime Breaches Klue: Salesforce Data Impacted for Many Victims, including Huntress](<https://www.huntress.com/blog/klue-breach-investigation>) | 0 | 1 |
| 2026-06-18 | Microsoft Threat Intelligence | [From package to postinstall payload: Inside the Mastra npm supply chain compromise by Sapphire Sleet](<https://www.microsoft.com/en-us/security/blog/2026/06/17/postinstall-payload-inside-mastra-npm-supply-chain-compromise/>) | 0 | 14 |
| 2026-06-17 | Zscaler ThreatLabz | [ClickFix Campaign Generated Via AI Delivers SmartRAT](<https://www.zscaler.com/blogs/security-research/clickfix-campaign-generated-ai-delivers-smartrat>) | 0 | 12 |
| 2026-06-17 | Censys | [AdaptixC2: Fingerprinting an Open-Source C2 Framework at Scale](<https://censys.com/blog/adaptixc2-open-source-c2-framework/>) | 0 | 27 |
| 2026-06-17 | Check Point Research | [From Stars to Upvotes: Fake Reputation Fueling a Crypto Clipboard Hijacker](<https://research.checkpoint.com/2026/from-stars-to-upvotes-fake-reputation-fueling-a-crypto-clipboard-hijacker/>) | 0 | 14 |
| 2026-06-16 | Huntress | [Potemkin Loader & RMMProject The Anatomy of a ClickFix Attack](<https://www.huntress.com/blog/potemkin-loader-rmmproject-clickfix-attack>) | 0 | 12 |
| 2026-06-16 | Securelist | [Dozens of malicious wallpapers found on Steam Workshop: gamers’ accounts at risk](<https://securelist.com/dozens-of-malicious-wallpapers-found-on-steam-workshop/120186/>) | 0 | 37 |
| 2026-06-16 | ESET WeLiveSecurity | [FishMonger’s arsenal upgraded: SprySOCKS for Windows](<https://www.welivesecurity.com/en/eset-research/fishmongers-arsenal-upgraded-sprysocks-windows/>) | 0 | 2 |
| 2026-06-15 | Huntress | [The Devil, Eight Million Emails, and a Whole Lot of Milk \| Phishing Stager Exposed](<https://www.huntress.com/blog/terminal-server-phishing-stager-exposed>) | 0 | 4 |
| 2026-06-12 | Zscaler ThreatLabz | [Shai-Hulud Campaign Evolution: Miasma, Hades, and AI Scanner Evasion](<https://www.zscaler.com/blogs/security-research/shai-hulud-campaign-evolution-miasma-hades-and-ai-scanner-evasion>) | 0 | 1 |
| 2026-06-12 | Censys | [The Package That Never Shipped: Following a USPS Smishing Kit Through Censys DNS Data](<https://censys.com/blog/following-a-usps-smishing-kit-through-censys-dns-data/>) | 0 | 5 |
| 2026-06-12 | Huntress | [Akira, LimeWire, and the Sour Taste of Data Exfiltration](<https://www.huntress.com/blog/akira-ransomware-limewire-data-exfiltration>) | 0 | 1 |
| 2026-06-12 | Cyble | [Borrowed Trust – Systematic Exploitation of Abandoned Cloud DNS Delegations to serve Thai Gambling SEO Content](<https://cyble.com/blog/borrowed-trust-cloud-dns-takeover-thai-gambling-seo-poisoning/>) | 0 | 4 |
| 2026-06-11 | Sekoia | [FSB’s matryoshka #3/3: Gamaredon's Gammasteel Infostealer](<https://www.sekoia.com/blog/fsbs-matryoshka-3-3-gamaredons-gifts-that-keeps-unpacking-gammasteel>) | 0 | 10 |
| 2026-06-11 | Sekoia | [FSB’s matryoshka #2/3: Gamaredon's Gammaload Malware](<https://www.sekoia.com/blog/fsbs-matryoshka-2-3-gamaredons-gifts-that-keeps-unpacking-gammaload>) | 0 | 22 |
| 2026-06-11 | Sekoia | [FSB’s matryoshka #1/3: Inside Gamaredon Cyber Operations](<https://www.sekoia.com/blog/fsbs-matryoshka-1-3-gamaredons-gifts-that-keeps-unpacking-gammaphish-and-gammaworm>) | 0 | 6 |
| 2026-06-11 | Sekoia | [From APT28 to RePythonNET: automating .NET malware analysis](<https://www.sekoia.com/blog/apt28-to-repythonnet-automating-net-malware-analysis>) | 0 | 1 |
| 2026-06-11 | Sekoia | [EvilTokens Kit: Device Code Phishing-as-a-service - Part 1](<https://www.sekoia.com/blog/new-widespread-eviltokens-kit-device-code-phishing-as-a-service-part-1>) | 0 | 35 |
| 2026-06-11 | Sekoia | [Silver Fox: The only Tax Audit Where Fine Print Installs Malware](<https://www.sekoia.com/blog/silver-fox-the-only-tax-audit-where-the-fine-print-installs-malware>) | 0 | 57 |
| 2026-06-11 | Sekoia | [OysterLoader Unmasked: The Multi-Stage Evasion Loader](<https://www.sekoia.com/blog/oysterloader-unmasked-the-multi-stage-evasion-loader>) | 0 | 15 |
| 2026-06-11 | Sekoia | [Meet IClickFix: a widespread framework using the ClickFix tactic](<https://www.sekoia.com/blog/meet-iclickfix-a-widespread-wordpress-targeting-framework-using-the-clickfix-tactic>) | 0 | 19 |
| 2026-06-11 | Sekoia | [Advent of Config Extraction, Part 4: Extracting TinyShell Configs](<https://www.sekoia.com/blog/advent-of-configuration-extraction-part-4-turning-capa-into-a-configuration-extractor-for-tinyshell-variant>) | 1 | 0 |
| 2026-06-11 | Sekoia | [Advent of Configuration Extraction, Part 3: SNOWLIGHT Config](<https://www.sekoia.com/blog/advent-of-configuration-extraction-part-3-mapping-got-plt-and-disassembling-the-snowlight-loader>) | 0 | 1 |
| 2026-06-11 | Sekoia | [Advent of Configuration Extraction, Part 2: QuasarRAT Config](<https://www.sekoia.com/blog/advent-of-configuration-extraction-part-2-unwrapping-quasarrats-configuration>) | 0 | 1 |
| 2026-06-11 | Sekoia | [Advent of Configuration Extraction, Part 1: Kaiji Configuration](<https://www.sekoia.com/blog/advent-of-configuration-extraction-part-1-pipeline-overview-first-steps-with-kaiji-configuration-unboxing>) | 0 | 1 |
| 2026-06-11 | Sekoia | [French NGO reporters without borders targeted by Calisto](<https://www.sekoia.com/blog/ngo-reporters-without-borders-targeted-by-calisto-in-recent-campaign>) | 0 | 16 |
| 2026-06-11 | Sekoia | [Booking.com Phishing Campaign Targeting Hotels and Customers](<https://www.sekoia.com/blog/phishing-campaigns-i-paid-twice-targeting-booking-com-hotels-and-customers>) | 0 | 5 |
| 2026-06-11 | Sekoia | [TransparentTribe Targets Indian Military with DeskRAT Malware](<https://www.sekoia.com/blog/transparenttribe-targets-indian-military-organisations-with-deskrat>) | 0 | 8 |
| 2026-06-11 | Sekoia | [PolarEdge Backdoor on QNAP: CVE-2023-20118 Analysis](<https://www.sekoia.com/blog/polaredge-backdoor-qnap-cve-2023-20118-analysis>) | 0 | 1 |
| 2026-06-11 | Sekoia | [APT28 Operation Phantom Net Voxel: BeardShell & Covenant](<https://www.sekoia.com/blog/apt28-operation-phantom-net-voxel>) | 0 | 20 |
| 2026-06-11 | Sekoia | [Silent Smishing : The Hidden Abuse of Cellular Router APIs](<https://www.sekoia.com/blog/silent-smishing-the-hidden-abuse-of-cellular-router-apis>) | 0 | 231 |
| 2026-06-11 | Sekoia | [The Sharp Taste of Mimo'lette: Mimo Targets Craft CMS](<https://www.sekoia.com/blog/the-sharp-taste-of-mimolette-analyzing-mimos-latest-campaign-targeting-craft-cms>) | 0 | 11 |
| 2026-06-11 | Sekoia | [ViciousTrap: Turning Edge Devices into Honeypots at Scale](<https://www.sekoia.com/blog/vicioustrap-infiltrate-control-lure-turning-edge-devices-into-honeypots-en-masse>) | 0 | 16 |
| 2026-06-11 | Sekoia | [Detecting Multi-Stage Infection Chains Madness](<https://www.sekoia.com/blog/detecting-multi-stage-infection-chains-madness>) | 0 | 5 |
| 2026-06-11 | Sekoia | [Interlock Ransomware: Evolving Under the Radar with ClickFix](<https://www.sekoia.com/blog/interlock-ransomware-evolving-under-the-radar>) | 0 | 61 |
| 2026-06-11 | Sekoia | [Lazarus ClickFake Interview Campaign: ClickFix Malware](<https://www.sekoia.com/blog/clickfake-interview-campaign-by-lazarus>) | 0 | 36 |
| 2026-06-11 | Sekoia | [ClearFake's Variant: Web3 Exploitation for Malware Delivery](<https://www.sekoia.com/blog/clearfakes-new-widespread-variant-increased-web3-exploitation-for-malware-delivery>) | 0 | 94 |
| 2026-06-11 | Sekoia | [PolarEdge: Unveiling an uncovered ORB network](<https://www.sekoia.com/blog/polaredge-unveiling-an-uncovered-iot-botnet>) | 0 | 31 |
| 2026-06-11 | Sekoia | [Cyber Threat Actors Impacting the Financial Sector in 2024](<https://www.sekoia.com/blog/cyber-threats-impacting-the-financial-sector-in-2024-focus-on-the-main-actors>) | 0 | 2 |
| 2026-06-11 | Sekoia | [RATatouille: Cooking Up Chaos in the I2P Kitchen](<https://www.sekoia.com/blog/ratatouille-cooking-up-chaos-in-the-i2p-kitchen>) | 0 | 4 |
| 2026-06-11 | Sekoia | [Supply Chain Attack Against Chrome Browser Extensions](<https://www.sekoia.com/blog/targeted-supply-chain-attack-against-chrome-browser-extensions>) | 0 | 88 |
| 2026-06-11 | Sekoia | [Sneaky 2FA: exposing a new AiTM Phishing-as-a-Service](<https://www.sekoia.com/blog/sneaky-2fa-exposing-a-new-aitm-phishing-as-a-service>) | 0 | 97 |
| 2026-06-11 | Sekoia | [Double-Tap: APT28-Linked Espionage on Kazakhstan](<https://www.sekoia.com/blog/double-tap-campaign-russia-nexus-apt-possibly-related-to-apt28-conducts-cyber-espionage-on-central-asia-and-kazakhstan-diplomatic-relations>) | 0 | 13 |
| 2026-06-11 | Sekoia | [Helldown Ransomware: An Overview of this Emerging Threat](<https://www.sekoia.com/blog/helldown-ransomware-an-overview-of-this-emerging-threat>) | 0 | 13 |
| 2026-06-11 | Sekoia | [ClickFix tactic: Revenge of detection – Detect Fake CAPTCHA](<https://www.sekoia.com/blog/clickfix-tactic-revenge-of-detection>) | 0 | 1 |
| 2026-06-11 | Sekoia | [ClickFix tactic: The Phantom Meet Infostealer Campaign](<https://www.sekoia.com/blog/clickfix-tactic-the-phantom-meet>) | 0 | 23 |
| 2026-06-11 | Sekoia | [Bulbature, beneath the waves of GobRAT](<https://www.sekoia.com/blog/bulbature-beneath-the-waves-of-gobrat>) | 0 | 55 |
| 2026-06-11 | Sekoia | [Hadooken and K4Spreader: The 8220 Gang's Latest Arsenal](<https://www.sekoia.com/blog/hadooken-and-k4spreader-the-8220-gangs-latest-arsenal>) | 0 | 7 |
| 2026-06-11 | Sekoia | [SilentSelfie: Major Campaign Against Kurdish Websites](<https://www.sekoia.com/blog/silentselfie-uncovering-a-major-watering-hole-campaign-against-kurdish-websites>) | 0 | 35 |
| 2026-06-11 | Sekoia | [WebDAV-as-a-Service: The Infrastructure Behind Emmenhtal](<https://www.sekoia.com/blog/webdav-as-a-service-uncovering-the-infrastructure-behind-emmenhtal-loader-distribution>) | 0 | 16 |
| 2026-06-11 | Sekoia | [Hunting typosquatted domains during the 2024 Olympics](<https://www.sekoia.com/blog/securing-gold-hunting-typosquatted-domains-during-the-olympics>) | 0 | 10 |
| 2026-06-11 | Sekoia | [Quad7 Operators' Next Moves And Associated Botnets](<https://www.sekoia.com/blog/a-glimpse-into-the-quad7-operators-next-moves-and-associated-botnets>) | 0 | 26 |
| 2026-06-11 | Sekoia | [Emulating and Detecting Scattered Spider-like Attacks](<https://www.sekoia.com/blog/emulating-and-detecting-scattered-spider-like-attacks>) | 0 | 1 |
| 2026-06-11 | Sekoia | [Solving the 7777 Botnet enigma: A cybersecurity quest](<https://www.sekoia.com/blog/solving-the-7777-botnet-enigma-a-cybersecurity-quest>) | 0 | 9 |
| 2026-06-11 | Sekoia | [MuddyWater replaces Atera by custom MuddyRot implant](<https://www.sekoia.com/blog/muddywater-replaces-atera-by-custom-muddyrot-implant-in-a-recent-campaign>) | 0 | 6 |
| 2026-06-11 | Sekoia | [PikaBot: a Guide to its Deep Secrets and Operations](<https://www.sekoia.com/blog/pikabot-a-guide-to-its-deep-secrets-and-operations>) | 0 | 1 |
| 2026-06-11 | ESET WeLiveSecurity | [OceanLotus: From external espionage to domestic targeting](<https://www.welivesecurity.com/en/eset-research/oceanlotus-external-espionage-domestic-targeting/>) | 0 | 4 |
| 2026-06-10 | Cyble | [FIFA World Cup 2026 Scams Are Already Active: Fake Domains, Phishing Sites, and How to Stay Safe](<https://cyble.com/blog/fifa-world-cup-2026-scams/>) | 0 | 1 |
| 2026-06-09 | Zscaler ThreatLabz | [Technical Analysis of MLTBackdoor](<https://www.zscaler.com/blogs/security-research/technical-analysis-mltbackdoor>) | 0 | 12 |
| 2026-06-08 | Microsoft Threat Intelligence | [AI brands as bait: How threat actors are using the AI hype in social engineering](<https://www.microsoft.com/en-us/security/blog/2026/06/08/ai-brands-as-bait-how-threat-actors-are-using-the-ai-hype-in-social-engineering/>) | 0 | 17 |
| 2026-06-08 | Securelist | [From cause to cash: a cross-border look at hacktivist activity](<https://securelist.com/tr/hacktivists-broaden-attack-geography/120115/>) | 0 | 110 |
| 2026-06-04 | Volexity | [VerdantBamboo: Just Another BRICKSTORM in the Firewall](<https://www.volexity.com/blog/2026/06/04/verdantbamboo-just-another-brickstorm-in-the-firewall/>) | 0 | 1 |
| 2026-06-03 | Huntress | [Inside .NET Loader Analysis: From Malspam to In-Memory Loader](<https://www.huntress.com/blog/malspam-to-loader-delivery-chain-analysis>) | 0 | 18 |
| 2026-06-03 | Check Point Research | [Impersonation, Click Hijacking, and TDS: Inside a Malware Distribution Ecosystem](<https://research.checkpoint.com/2026/impersonation-click-hijacking-and-tds-inside-a-malware-distribution-ecosystem/>) | 0 | 62 |
| 2026-06-03 | Securelist | [Argamal: Malware hidden in hentai games](<https://securelist.com/argamal-rat-distributed-with-hentai-games/119999/>) | 0 | 27 |
| 2026-06-02 | ANY.RUN | [From Fake Purchase Orders to Remote Access: Analyzing the JS.MonoGlyphRAT Threat to US Enterprises](<https://any.run/cybersecurity-blog/monoglyphrat-attacks-us-enterprise/>) | 0 | 6 |
| 2026-06-02 | Unit 42 | [Operation FlutterBridge: macOS Malvertising Campaign Spreads New FlutterShell Backdoor](<https://unit42.paloaltonetworks.com/flutterbridge-new-fluttershell-backdoor/>) | 0 | 17 |
| 2026-05-29 | Seqrite | [Operation Dragon Weave : Uncovering a China-Linked Campaign Targeting Czech Republic and Taiwan Using Azure Cloud C2](<https://www.seqrite.com/blog/operation-dragon-weave-uncovering-a-china-linked-campaign-targeting-czech-republic-and-taiwan-using-azure-cloud-c2/>) | 0 | 13 |
| 2026-05-29 | Seqrite | [Operation XENOFISCAL: SideCopy deploying persistent XenoRAT targeting the MoF, Afghanistan](<https://www.seqrite.com/blog/operation-xenofiscal-sidecopy-deploying-persistent-xenorat-targeting-the-mof-afghanistan/>) | 0 | 14 |
| 2026-05-28 | Microsoft Threat Intelligence | [The Gentlemen ransomware: Dissecting a self-propagating Go encryptor](<https://www.microsoft.com/en-us/security/blog/2026/05/28/the-gentlemen-ransomware-dissecting-a-self-propagating-go-encryptor/>) | 2 | 1 |
| 2026-05-28 | Darktrace | [How to Evaluate AI Vendors: 5 Key categories for AI Adoption](<https://www.darktrace.com/blog/how-to-evaluate-ai-vendors-5-key-categories-for-ai-adoption>) | 0 | 13 |
| 2026-05-28 | Securelist | [Pirates in the crosshairs: how one cybercrime gang has been infecting book, movie, and TV show fans for years](<https://securelist.com/video-books-pirates-miners-rat/119943/>) | 0 | 13 |
| 2026-05-27 | Darktrace | [How Multi-Layered AI Detects Email Threats \| Darktrace / EMAIL](<https://www.darktrace.com/blog/how-multi-layered-ai-works-in-darktrace-email>) | 0 | 13 |
| 2026-05-27 | Cyble | [OverlayPhantom: The Android Banking Trojan Hiding in Plain Sight](<https://cyble.com/blog/overlayphantom-android-banking-trojan/>) | 0 | 5 |
| 2026-05-26 | Red Canary | [Intelligence Insights: May 2026](<https://redcanary.com/blog/threat-intelligence/intelligence-insights-may-2026/>) | 0 | 2 |
| 2026-05-26 | Darktrace | [77% of security stacks include AI, but trust is lagging](<https://www.darktrace.com/blog/state-of-ai-cybersecurity-2026-77-of-security-stacks-include-ai-but-trust-is-lagging>) | 0 | 13 |
| 2026-05-24 | Darktrace | [Chinese APT Campaign Targets Entities with Updated FDMTP Backdoor](<https://www.darktrace.com/blog/chinese-apt-campaign-targets-entities-with-updated-fdmtp-backdoor>) | 0 | 26 |
| 2026-05-22 | Check Point Research | [Fast and Furious – Nimbus Manticore Operations During the Iranian Conflict](<https://research.checkpoint.com/2026/fast-and-furious-nimbus-manticore-operations-during-the-iranian-conflict/>) | 12 | 39 |
| 2026-05-22 | Unit 42 | [Tracking Iranian APT Screening Serpens’ 2026 Espionage Campaigns](<https://unit42.paloaltonetworks.com/tracking-iran-apt-screening-serpens/>) | 12 | 25 |
| 2026-05-22 | Securelist | [Cloud Atlas activity in the second half of 2025 and early 2026: new tools and a new payload](<https://securelist.com/cloud-atlas-2026/119895/>) | 0 | 105 |
| 2026-05-22 | Elastic Security Labs | [PHANTOMPULSE: anatomy of a hijackable blockchain-C2 RAT](<https://www.elastic.co/security-labs/threat-command/blockchain-c2-phantompulse-rat-sinkhole>) | 0 | 12 |
| 2026-05-21 | Cyble | [JOMANGY: INJ3CTOR3’s Self-Healing FreePBX Toll Fraud Campaign](<https://cyble.com/blog/jomangy-inj3ctor3s-self-healing-freepbx-toll-fraud-campaign/>) | 0 | 15 |
| 2026-05-21 | Huntress | [The Gentleman Ransomware \| Defense Evasion TTPs Uncovered \| Huntress](<https://www.huntress.com/blog/the-gentlemen-ransomware-defense-evasion-ttps>) | 0 | 2 |
| 2026-05-20 | Seqrite | [Operation Dragon Whistle: UNG0002 Targets Chinese Academia via Weaponized Institutional Lure](<https://www.seqrite.com/blog/operation-dragon-whistle-ung002-targets-chinese-academia-via-weaponized-institutional-lure/>) | 0 | 9 |
| 2026-05-20 | Unit 42 | [Tracking TamperedChef Clusters via Certificate and Code Reuse](<https://unit42.paloaltonetworks.com/tracking-tampered-chef-clusters/>) | 0 | 6 |
| 2026-05-19 | Microsoft Threat Intelligence | [Exposing Fox Tempest: A malware-signing service operation](<https://www.microsoft.com/en-us/security/blog/2026/05/19/exposing-fox-tempest-a-malware-signing-service-operation/>) | 0 | 5 |
| 2026-05-19 | Bitdefender Labs | [Microsoft’s MSHTA Legacy Tool Still Powers Malware Campaigns on Windows](<https://www.bitdefender.com/en-us/blog/labs/microsofts-mshta-legacy-malware-windows>) | 0 | 11 |
| 2026-05-15 | Unit 42 | [Gremlin Stealer's Evolved Tactics: Hiding in Plain Sight With Resource Files](<https://unit42.paloaltonetworks.com/gremlin-stealer-evolution/>) | 0 | 12 |
| 2026-05-14 | Microsoft Threat Intelligence | [Kazuar: Anatomy of a nation-state botnet](<https://www.microsoft.com/en-us/security/blog/2026/05/14/kazuar-anatomy-of-a-nation-state-botnet/>) | 0 | 5 |
| 2026-05-14 | Securelist | [Kimsuky targets organizations with PebbleDash-based tools](<https://securelist.com/kimsuky-appleseed-pebbledash-campaigns/119785/>) | 0 | 30 |
| 2026-05-14 | Infoblox Threat Intel | [Lookalike Domains Expose the iPhone Theft Economy](<https://www.infoblox.com/blog/threat-intelligence/lookalike-domains-expose-the-iphone-theft-economy/>) | 0 | 3 |
| 2026-05-14 | ESET WeLiveSecurity | [FrostyNeighbor: Fresh mischief and digital shenanigans](<https://www.welivesecurity.com/en/eset-research/frostyneighbor-fresh-mischief-digital-shenanigans/>) | 0 | 4 |
| 2026-05-13 | Check Point Research | [Thus Spoke…The Gentlemen](<https://research.checkpoint.com/2026/thus-spoke-the-gentlemen/>) | 1 | 32 |
| 2026-05-12 | Censys | [The Ultimate Guide to Detection Engineering with Censys](<https://censys.com/blog/ultimate-guide-to-detection-engineering-with-censys/>) | 0 | 1 |
| 2026-05-11 | The DFIR Report | [Flash Alert: EtherRat and TukTuk C2 End in The Gentleman Ransomware](<https://thedfirreport.com/2026/05/11/flash-alert-etherrat-and-tuktuk-c2-end-in-the-gentleman-ransomware/>) | 0 | 19 |
| 2026-05-07 | Huntress | [Threat Actors Weaponize Tiflux RMMs in Malspam Attacks](<https://www.huntress.com/blog/tiflux-rmm-install>) | 0 | 11 |
| 2026-05-07 | Seqrite | [Operation GriefLure: Dissecting an APT Campaign Targeting Vietnam’s Military Telecom & Philippine Healthcare](<https://www.seqrite.com/blog/operation-grieflure-dissecting-an-apt-campaign-targeting-vietnams-military-telecom-philippine-healthcare/>) | 0 | 2 |
| 2026-05-07 | Cyble | [Operation HumanitarianBait: An Infostealer Campaign in Disguise](<https://cyble.com/blog/operation-humanitarianbait-infostealer-campaign/>) | 0 | 7 |
| 2026-05-07 | Unit 42 | [Threat Brief: Exploitation of PAN-OS Captive Portal Zero-Day for Unauthenticated Remote Code Execution](<https://unit42.paloaltonetworks.com/captive-portal-zero-day/>) | 0 | 7 |
| 2026-05-07 | Elastic Security Labs | [TCLBANKER: Brazilian Banking Trojan Spreading via WhatsApp and Outlook](<https://www.elastic.co/security-labs/threat-command/tclbanker-brazilian-banking-trojan>) | 0 | 18 |
| 2026-05-06 | Securelist | [OceanLotus suspected of using PyPI to deliver ZiChatBot malware](<https://securelist.com/oceanlotus-suspected-pypi-zichatbot-campaign/119603/>) | 0 | 17 |
| 2026-05-06 | Seqrite | [Operation Silent Rotor: Targeted Campaign Compromises Unmanned Aviation Sector Ahead of Moscow Summit](<https://www.seqrite.com/blog/operation-silent-rotor-rust-malware-unmanned-aviation-sector/>) | 0 | 11 |
| 2026-05-05 | Darktrace | [Why behavioral AI is the answer to Mythos](<https://www.darktrace.com/blog/why-behavioral-ai-is-the-answer-to-mythos>) | 0 | 13 |
| 2026-05-05 | Zscaler ThreatLabz | [Malicious OpenClaw Skill Distributes Remcos RAT and GhostLoader](<https://www.zscaler.com/blogs/security-research/malicious-openclaw-skill-distributes-remcos-rat-and-ghostloader>) | 0 | 22 |
| 2026-05-05 | Securelist | [DAEMON Tools software infected — supply chain attack ongoing since April 8, 2026](<https://securelist.com/tr/daemon-tools-backdoor/119654/>) | 0 | 28 |
| 2026-05-05 | ESET WeLiveSecurity | [A rigged game: ScarCruft compromises gaming platform in a supply-chain attack](<https://www.welivesecurity.com/en/eset-research/rigged-game-scarcruft-compromises-gaming-platform-supply-chain-attack/>) | 0 | 6 |
| 2026-05-04 | Darktrace | [Anthropic’s Mythos and what it means for security teams](<https://www.darktrace.com/blog/mythos-vs-ethos-defending-in-an-era-of-ai-accelerated-vulnerability-discovery>) | 0 | 13 |
| 2026-05-04 | Microsoft Threat Intelligence | [Breaking the code: Multi-stage ‘code of conduct’ phishing campaign leads to AiTM token compromise](<https://www.microsoft.com/en-us/security/blog/2026/05/04/breaking-the-code-multi-stage-code-of-conduct-phishing-campaign-leads-to-aitm-token-compromise/>) | 0 | 8 |
| 2026-05-04 | Huntress | [dMSA Ouroboros: Self-Sustaining Credential Extraction in Windows Server 2025](<https://www.huntress.com/blog/dmsa-ouroboros-credential-extraction-windows-server-2025>) | 0 | 1 |
| 2026-05-03 | Darktrace | [87% of security professionals are seeing more AI-driven threats, but few feel prepared to stop them](<https://www.darktrace.com/blog/state-of-ai-cybersecurity-2026-87-of-security-professionals-are-seeing-more-ai-driven-threats-but-few-feel-ready-to-stop-them>) | 0 | 13 |
| 2026-05-02 | Darktrace | [Email prompt injection attacks on enterprise AI explained: Risks & impact](<https://www.darktrace.com/blog/how-email-delivered-prompt-injection-attacks-can-target-enterprise-ai-and-why-it-matters>) | 0 | 13 |
| 2026-05-01 | Censys | [The cPanel Situation Is…](<https://censys.com/blog/the-cpanel-situation-is/>) | 0 | 1 |
| 2026-04-30 | Unit 42 | [That AI Extension Helping You Write Emails? It’s Reading Them First](<https://unit42.paloaltonetworks.com/high-risk-gen-ai-browser-extensions/>) | 0 | 17 |
| 2026-04-30 | Microsoft Threat Intelligence | [Email threat landscape: Q1 2026 trends and insights](<https://www.microsoft.com/en-us/security/blog/2026/04/30/email-threat-landscape-q1-2026-trends-and-insights/>) | 0 | 3 |
| 2026-04-30 | Huntress | [ClickFix Removes Your Background but Leaves the Malware](<https://www.huntress.com/blog/clickfix-castleloader-backgroundfix>) | 0 | 22 |
| 2026-04-30 | Huntress | [Komari Red: The Monitoring Tool with a Built-in Reverse Shell](<https://www.huntress.com/blog/komari-c2-agent-abuse>) | 0 | 3 |
| 2026-04-29 | Bitdefender Labs | [Operation Road Trap: Fake toll and parking texts are spreading worldwide](<https://www.bitdefender.com/en-us/blog/labs/operation-road-trap>) | 0 | 10 |
| 2026-04-28 | Check Point Research | [VECT: Ransomware by design, Wiper by accident](<https://research.checkpoint.com/2026/vect-ransomware-by-design-wiper-by-accident/>) | 0 | 6 |
| 2026-04-24 | Cyble | [Operation TrustTrap: Anatomy of a Large-Scale Deceptive Domain Spoofing Campaign](<https://cyble.com/blog/operation-trusttrap-domain-spoofing-campaign/>) | 0 | 1 |
| 2026-04-23 | Infoblox Threat Intel | [Hold the Phone! International Revenue Share Fraud Driven by Fake CAPTCHAs](<https://www.infoblox.com/blog/threat-intelligence/hold-the-phone-international-revenue-share-fraud-driven-by-fake-captchas/>) | 0 | 6 |
| 2026-04-22 | Censys | [Oluomo: Microsoft OAuth AiTM Phishing Using a Naturalization-Form Lure](<https://censys.com/blog/oluomo-microsoft-oauth-aitm-phishing-using-a-naturalization-form-lure/>) | 0 | 28 |
| 2026-04-22 | Zscaler ThreatLabz | [Tropic Trooper Pivots to AdaptixC2 and Custom Beacon Listener](<https://www.zscaler.com/blogs/security-research/tropic-trooper-pivots-adaptixc2-and-custom-beacon-listener>) | 0 | 2 |
| 2026-04-22 | The DFIR Report | [Bissa Scanner Exposed: AI-Assisted Mass Exploitation and Credential Harvesting](<https://thedfirreport.com/2026/04/22/bissa-scanner-exposed-ai-assisted-mass-exploitation-and-credential-harvesting/>) | 0 | 2 |
| 2026-04-22 | Huntress | [Untangling a Linux Incident With an OpenAI Twist (Part 2)](<https://www.huntress.com/blog/codex-part-two>) | 0 | 9 |
| 2026-04-20 | Huntress | [Nightmare-Eclipse Tooling Seen in Real-World Intrusion](<https://www.huntress.com/blog/nightmare-eclipse-intrusion>) | 0 | 4 |
| 2026-04-20 | Check Point Research | [DFIR Report – The Gentlemen & SystemBC: A Sneak Peek Behind the Proxy](<https://research.checkpoint.com/2026/dfir-report-the-gentlemen/>) | 2 | 28 |
| 2026-04-17 | Unit 42 | [Threat Brief: Escalation of Cyber Risk Related to Iran (Updated April 17)](<https://unit42.paloaltonetworks.com/iranian-cyberattacks-2026/>) | 0 | 106 |
| 2026-04-17 | Huntress | [Uptick in Bomgar RMM Exploitation](<https://www.huntress.com/blog/uptick-bomgar-exploitation>) | 0 | 5 |
| 2026-04-17 | Huntress | [Untangling a Linux Incident With an OpenAI Twist](<https://www.huntress.com/blog/codex-part-one>) | 0 | 1 |
| 2026-04-16 | Unit 42 | [A Deep Dive Into Attempted Exploitation of CVE-2023-33538](<https://unit42.paloaltonetworks.com/exploitation-of-cve-2023-33538/>) | 0 | 27 |
| 2026-04-16 | Zscaler ThreatLabz | [Payouts King Takes Aim at the Ransomware Throne](<https://www.zscaler.com/blogs/security-research/payouts-king-takes-aim-ransomware-throne>) | 0 | 2 |
| 2026-04-16 | Microsoft Threat Intelligence | [Dissecting Sapphire Sleet’s macOS intrusion from lure to compromise](<https://www.microsoft.com/en-us/security/blog/2026/04/16/dissecting-sapphire-sleets-macos-intrusion-from-lure-to-compromise/>) | 0 | 22 |
| 2026-04-15 | Cyble | [MiningDropper – A Global Modular Android Malware Campaign Operating at Scale](<https://cyble.com/blog/miningdropper-global-modular-android-malware/>) | 0 | 28 |
| 2026-04-14 | Huntress | [When PUPs Grow Fangs: Dragon Boss Solutions' $10 Supply Chain Risk](<https://www.huntress.com/blog/pups-grow-fangs>) | 0 | 12 |
| 2026-04-14 | Elastic Security Labs | [Phantom in the vault: Obsidian abused to deliver PhantomPulse RAT](<https://www.elastic.co/security-labs/threat-command/phantom-in-the-vault>) | 0 | 14 |
| 2026-04-10 | Infoblox Threat Intel | [Scams, Slaves and (Malware-as-a) Service: Tracking a Trojan to Cambodia’s Scam Centers](<https://www.infoblox.com/blog/threat-intelligence/scams-slaves-and-malware-as-a-service-tracking-a-trojan-to-cambodias-scam-centers/>) | 1 | 16 |
| 2026-04-09 | Zscaler ThreatLabz | [In-Memory Loader Drops ScreenConnect](<https://www.zscaler.com/blogs/security-research/memory-loader-drops-screenconnect>) | 0 | 11 |
| 2026-04-07 | Unit 42 | [Cracks in the Bedrock: Escaping the AWS AgentCore Sandbox](<https://unit42.paloaltonetworks.com/bypass-of-aws-sandbox-network-isolation-mode/>) | 0 | 1 |
| 2026-04-07 | Huntress | [Decoding NightSpire: Ransomware IOCs Aren't Set in Stone](<https://www.huntress.com/blog/nightspire-ransomware>) | 0 | 2 |
| 2026-04-06 | Unit 42 | [Understanding Current Threats to Kubernetes Environments](<https://unit42.paloaltonetworks.com/modern-kubernetes-threats/>) | 1 | 7 |
| 2026-04-06 | Microsoft Threat Intelligence | [Storm-1175 focuses gaze on vulnerable web-facing assets in high-tempo Medusa ransomware operations](<https://www.microsoft.com/en-us/security/blog/2026/04/06/storm-1175-focuses-gaze-on-vulnerable-web-facing-assets-in-high-tempo-medusa-ransomware-operations/>) | 0 | 7 |
| 2026-04-06 | Censys | [Hackers Are Attempting to Turn ComfyUI Servers Into a Cryptomining Proxy Botnet](<https://censys.com/blog/comfyui-servers-cryptomining-proxy-botnet/>) | 0 | 6 |
| 2026-04-06 | Seqrite | [Advisory: Middle East Conflict & Cyber Escalation](<https://www.seqrite.com/blog/iran-us-israel-cyberwar-2026-analysis/>) | 0 | 4 |
| 2026-04-03 | Zscaler ThreatLabz | [Supply Chain Attacks Surge in March 2026](<https://www.zscaler.com/blogs/security-research/supply-chain-attacks-surge-march-2026>) | 0 | 3 |
| 2026-04-03 | NVISO Labs | [The Axios npm supply chain incident: fake dependency, real backdoor](<https://blog.nviso.eu/2026/04/03/the-axios-npm-supply-chain-incident-fake-dependency-real-backdoor/>) | 5 | 10 |
| 2026-04-02 | Censys | [Cutting Through the Noise: A Technique-Based Approach to Hunting Web-Delivered Malware](<https://censys.com/blog/technique-based-approach-hunting-web-delivered-malware/>) | 0 | 18 |
| 2026-04-01 | Microsoft Threat Intelligence | [Mitigating the Axios npm supply chain compromise](<https://www.microsoft.com/en-us/security/blog/2026/04/01/mitigating-the-axios-npm-supply-chain-compromise/>) | 5 | 3 |
| 2026-04-01 | Zscaler ThreatLabz | [Anthropic Claude Code Leak](<https://www.zscaler.com/blogs/security-research/anthropic-claude-code-leak>) | 0 | 16 |
| 2026-04-01 | Unit 42 | [Threat Brief: Widespread Impact of the Axios Supply Chain Attack](<https://unit42.paloaltonetworks.com/axios-supply-chain-attack/>) | 4 | 10 |
| 2026-04-01 | Elastic Security Labs | [Elastic releases detections for the Axios supply chain compromise](<https://www.elastic.co/security-labs/blog/axios-supply-chain-compromise-detections>) | 2 | 6 |
| 2026-04-01 | Elastic Security Labs | [Inside the Axios supply chain compromise - one RAT to rule them all](<https://www.elastic.co/security-labs/threat-command/axios-one-rat-to-rule-them-all>) | 3 | 3 |
| 2026-03-31 | Huntress | [Supply Chain Compromise of axios npm Package](<https://www.huntress.com/blog/supply-chain-compromise-axios-npm-package>) | 4 | 5 |
| 2026-03-31 | Unit 42 | [Weaponizing the Protectors: TeamPCP’s Multi-Stage Supply Chain Attack on Security Infrastructure](<https://unit42.paloaltonetworks.com/teampcp-supply-chain-attacks/>) | 0 | 2 |
| 2026-03-31 | Zscaler ThreatLabz | [Latest Xloader Obfuscation Methods and Network Protocol](<https://www.zscaler.com/blogs/security-research/latest-xloader-obfuscation-methods-and-network-protocol>) | 0 | 3 |
| 2026-03-31 | Infoblox Threat Intel | [Patterns, Pirates, and Provider Action: What We Learned Working with Keitaro](<https://www.infoblox.com/blog/threat-intelligence/patterns-pirates-and-provider-action-what-we-learned-working-with-keitaro/>) | 0 | 1 |
| 2026-03-31 | Check Point Research | [Operation TrueChaos: 0-Day Exploitation Against Southeast Asian Government Targets](<https://research.checkpoint.com/2026/operation-truechaos-0-day-exploitation-against-southeast-asian-government-targets/>) | 0 | 6 |
| 2026-03-31 | Darktrace | [92% of Security Pros Concerned About AI Agents](<https://www.darktrace.com/blog/state-of-ai-cybersecurity-2026-92-of-security-professionals-concerned-about-the-impact-of-ai-agents>) | 0 | 13 |
| 2026-03-31 | Unit 42 | [Double Agents: Exposing Security Blind Spots in GCP Vertex AI](<https://unit42.paloaltonetworks.com/double-agents-vertex-ai/>) | 0 | 1 |
| 2026-03-31 | Seqrite | [Operation DualScript – A Multi-Stage PowerShell Malware Campaign Targeting Cryptocurrency and Financial Activity](<https://www.seqrite.com/blog/operation-dualscript-powershell-malware-retrorat-analysis/>) | 0 | 2 |
| 2026-03-31 | Elastic Security Labs | [Fake Installers to Monero: A Multi-Tool Mining Operation](<https://www.elastic.co/security-labs/threat-command/fake-installers-to-monero>) | 0 | 37 |
| 2026-03-30 | Cyble | [Professional Networks Under Attack: Vietnam-Linked Actors Deploy PXA Stealer in Global Infostealer Campaign](<https://cyble.com/blog/professional-networks-under-attack-by-infostealer/>) | 0 | 5 |
| 2026-03-30 | Darktrace | [NetSupport RAT: Why Legitimate Tools Are as Damaging as Malware](<https://www.darktrace.com/blog/netsupport-rat-how-legitimate-tools-can-be-as-damaging-as-malware>) | 0 | 30 |
| 2026-03-29 | Darktrace | [Darktrace Identifies Encryption in a World Leaks Ransomware Attack](<https://www.darktrace.com/blog/when-reality-diverges-from-the-playbook-darktrace-identifies-encryption-in-a-world-leaks-ransomware-attack>) | 0 | 17 |
| 2026-03-28 | Darktrace | [Darktrace Launches Unified Security Awareness Training and Messaging Security](<https://www.darktrace.com/blog/darktrace-unites-human-behavior-and-threat-detection-across-email-slack-teams-and-zoom>) | 0 | 13 |
| 2026-03-27 | Censys | [Under CTRL: Dissecting a Previously Undocumented Russian .Net Access Framework](<https://censys.com/blog/under-ctrl-dissecting-a-previously-undocumented-russian-net-access-framework/>) | 0 | 4 |
| 2026-03-27 | ESET WeLiveSecurity | [A cunning predator: How Silver Fox preys on Japanese firms this tax season](<https://www.welivesecurity.com/en/business-security/cunning-predator-how-silver-fox-preys-japanese-firms-tax-season/>) | 0 | 1 |
| 2026-03-27 | Elastic Security Labs | [Elastic Security Labs uncovers BRUSHWORM and BRUSHLOGGER](<https://www.elastic.co/security-labs/threat-command/brushworm-targets-financial-services>) | 0 | 3 |
| 2026-03-26 | Unit 42 | [Converging Interests: Analysis of Threat Clusters Targeting a Southeast Asian Government](<https://unit42.paloaltonetworks.com/espionage-campaigns-target-se-asian-government-org/>) | 0 | 13 |
| 2026-03-26 | Infoblox Threat Intel | [No Reach, No Risk: The Keitaro Abuse in Modern Cybercrime Distribution](<https://www.infoblox.com/blog/threat-intelligence/no-reach-no-risk-the-keitaro-abuse-in-modern-cybercrime-distribution/>) | 0 | 37 |
| 2026-03-26 | Elastic Security Labs | [Illuminating VoidLink: Technical analysis of the VoidLink rootkit framework](<https://www.elastic.co/security-labs/threat-command/illuminating-voidlink>) | 0 | 2 |
| 2026-03-24 | Unit 42 | [Threat Brief: Recruiting Scheme Impersonating Palo Alto Networks Talent Acquisition Team](<https://unit42.paloaltonetworks.com/phishing-attackers-pose-as-panw-recruiters/>) | 0 | 1 |
| 2026-03-23 | Huntress | [Threat Actors Abuse Railway.com PaaS as Microsoft 365 Token Attack Infrastructure](<https://www.huntress.com/blog/railway-paas-m365-token-replay-campaign>) | 0 | 13 |
| 2026-03-20 | Elastic Security Labs | [Linux & Cloud Detection Engineering - TeamPCP Container Attack Scenario](<https://www.elastic.co/security-labs/blog/teampcp-container-attack-scenario>) | 0 | 4 |
| 2026-03-19 | Red Canary | [Intelligence Insights: March 2026](<https://redcanary.com/blog/threat-intelligence/intelligence-insights-march-2026/>) | 0 | 3 |
| 2026-03-19 | Microsoft Threat Intelligence | [When tax season becomes cyberattack season: Phishing and malware campaigns using tax-related lures](<https://www.microsoft.com/en-us/security/blog/2026/03/19/when-tax-season-becomes-cyberattack-season-phishing-and-malware-campaigns-using-tax-related-lures/>) | 0 | 7 |
| 2026-03-19 | Huntress | [How a Tax Search Leads to Kernel-Mode AV/EDR Kill](<https://www.huntress.com/blog/w2-malvertising-to-kernel-mode-edr-kill>) | 0 | 20 |
| 2026-03-19 | Unit 42 | [Analyzing the Current State of AI Use in Malware](<https://unit42.paloaltonetworks.com/ai-use-in-malware/>) | 0 | 4 |
| 2026-03-19 | Elastic Security Labs | [From Invitation to Infection: How SILENTCONNECT Delivers ScreenConnect](<https://www.elastic.co/security-labs/threat-command/silentconnect-delivers-screenconnect>) | 0 | 10 |
| 2026-03-18 | Bitdefender Labs | [Windsurf IDE Extension Drops Malware via Solana Blockchain](<https://www.bitdefender.com/en-us/blog/labs/windsurf-extension-malware-solana>) | 0 | 1 |
| 2026-03-17 | Seqrite | [Operation GhostMail: Russian APT exploits Zimbra Webmail to Target Ukraine State Agency](<https://www.seqrite.com/blog/operation-ghostmail-zimbra-xss-russian-apt-ukraine/>) | 0 | 3 |
| 2026-03-16 | Unit 42 | [Boggy Serpens Threat Assessment](<https://unit42.paloaltonetworks.com/boggy-serpens-threat-assessment/>) | 1 | 20 |
| 2026-03-13 | Seqrite | [Operation CamelClone: Multi-Region Espionage Campaign Targets Government and Defense Entities Amidst Regional Tensions](<https://www.seqrite.com/blog/operation-camelclone-multi-region-espionage-campaign-targets-government-and-defense-entities-amidst-regional-tensions/>) | 0 | 16 |
| 2026-03-13 | Lab52 | [DRILLAPP: new backdoor targeting Ukrainian entities with possible links to Laundry Bear](<https://lab52.io/blog/drillapp-new-backdoor-targeting-ukrainian-entities-with-possible-links-to-laundry-bear/>) | 0 | 15 |
| 2026-03-12 | Unit 42 | [Suspected China-Based Espionage Operation Against Military Targets in Southeast Asia](<https://unit42.paloaltonetworks.com/espionage-campaign-against-military-targets/>) | 0 | 15 |
| 2026-03-12 | Check Point Research | [“Handala Hack” – Unveiling Group’s Modus Operandi](<https://research.checkpoint.com/2026/handala-hack-unveiling-groups-modus-operandi/>) | 0 | 9 |
| 2026-03-12 | Microsoft Threat Intelligence | [Storm-2561 uses SEO poisoning to distribute fake VPN clients for credential theft](<https://www.microsoft.com/en-us/security/blog/2026/03/12/storm-2561-uses-seo-poisoning-to-distribute-fake-vpn-clients-for-credential-theft/>) | 0 | 29 |
| 2026-03-12 | Huntress | [Data Exfiltration and Threat Actor Infrastructure Exposed](<https://www.huntress.com/blog/data-exfiltration-threat-actor-infrastructure-exposed>) | 0 | 2 |
| 2026-03-12 | Red Canary | [Moving up the Assemblyline: Exposing malicious code in browser extensions](<https://redcanary.com/blog/threat-detection/assemblyline-browser-extensions/>) | 0 | 1 |
| 2026-03-11 | Huntress | [How Threat Actors Abuse Remote Management Tools \| Huntress](<https://www.huntress.com/blog/daisy-chaining-rogue-rmm-tools>) | 4 | 1 |
| 2026-03-11 | Bitdefender Labs | [Windows and macOS Malware Spreads via Fake “Claude Code” Google Ads](<https://www.bitdefender.com/en-us/blog/labs/fake-claude-code-google-ads-malware>) | 0 | 11 |
| 2026-03-10 | ESET WeLiveSecurity | [Sednit reloaded: Back in the trenches](<https://www.welivesecurity.com/en/eset-research/sednit-reloaded-back-trenches/>) | 0 | 2 |
| 2026-03-06 | Huntress | [A Threat Actor Abuses Another Free Trial](<https://www.huntress.com/blog/threat-actor-abuses-elastic-cloud-siem>) | 0 | 2 |
| 2026-03-06 | Zscaler ThreatLabz | [Middle East Conflict Fuels Opportunistic Cyber Attacks](<https://www.zscaler.com/blogs/security-research/middle-east-conflict-fuels-opportunistic-cyber-attacks>) | 0 | 11 |
| 2026-03-06 | Huntress | [Unmasking an Attack Chain of MuddyWater](<https://www.huntress.com/blog/muddywater-attack-chain>) | 0 | 4 |
| 2026-03-06 | Unit 42 | [An Investigation Into Years of Undetected Operations Targeting High-Value Sectors](<https://unit42.paloaltonetworks.com/cl-unk-1068-targets-critical-sectors/>) | 0 | 35 |
| 2026-03-04 | Microsoft Threat Intelligence | [Inside Tycoon2FA: How a leading AiTM phishing kit operated at scale](<https://www.microsoft.com/en-us/security/blog/2026/03/04/inside-tycoon2fa-how-a-leading-aitm-phishing-kit-operated-at-scale/>) | 0 | 20 |
| 2026-03-04 | Huntress | [How Fake OpenClaw Installers Spread GhostSocks Malware](<https://www.huntress.com/blog/openclaw-github-ghostsocks-infostealer>) | 0 | 29 |
| 2026-03-03 | Check Point Research | [Silver Dragon Targets Organizations in Southeast Asia and Europe](<https://research.checkpoint.com/2026/silver-dragon-targets-organizations-in-southeast-asia-and-europe/>) | 0 | 45 |
| 2026-03-03 | Unit 42 | [Fooling AI Agents: Web-Based Indirect Prompt Injection Observed in the Wild](<https://unit42.paloaltonetworks.com/ai-agent-prompt-injection/>) | 0 | 19 |
| 2026-03-02 | Darktrace | [What the Darktrace Annual Threat Report 2026 Means for Security Leaders](<https://www.darktrace.com/blog/what-the-darktrace-annual-threat-report-2026-means-for-security-leaders>) | 0 | 13 |
| 2026-03-02 | Zscaler ThreatLabz | [Dust Specter APT Targets Government Officials in Iraq](<https://www.zscaler.com/blogs/security-research/dust-specter-apt-targets-government-officials-iraq>) | 0 | 1 |
| 2026-03-02 | Huntress | [Fake Tech Support Delivers Havoc Command & Control](<https://www.huntress.com/blog/fake-tech-support-havoc-command-control>) | 0 | 13 |
| 2026-03-01 | Darktrace | [AppleScript Abuse: Unpacking a macOS Phishing Campaign](<https://www.darktrace.com/blog/applescript-abuse-unpacking-a-macos-phishing-campaign>) | 0 | 21 |
| 2026-02-28 | Darktrace | [CVE-2026-1731: How Darktrace Sees the BeyondTrust Exploitation Wave Unfolding](<https://www.darktrace.com/blog/cve-2026-1731-how-darktrace-sees-the-beyondtrust-exploitation-wave-unfolding>) | 0 | 24 |
| 2026-02-26 | Infoblox Threat Intel | [Abusing .arpa: The TLD That Isn’t Supposed to Host Anything](<https://www.infoblox.com/blog/threat-intelligence/abusing-arpa-the-tld-that-isnt-supposed-to-host-anything/>) | 0 | 2 |
| 2026-02-26 | Zscaler ThreatLabz | [APT37 Adds New Capabilities for Air-Gapped Networks](<https://www.zscaler.com/blogs/security-research/apt37-adds-new-capabilities-air-gapped-networks>) | 0 | 6 |
| 2026-02-26 | Lab52 | [PlugX Meeting Invitation via MSBuild and GDATA](<https://lab52.io/blog/plugx-meeting-invitation-via-msbuild-and-gdata/>) | 0 | 7 |
| 2026-02-23 | Check Point Research | [2025: The Untold Stories of Check Point Research](<https://research.checkpoint.com/2026/2025-the-untold-stories-of-check-point-research/>) | 0 | 5 |
| 2026-02-23 | The DFIR Report | [Apache ActiveMQ Exploit Leads to LockBit Ransomware](<https://thedfirreport.com/2026/02/23/apache-activemq-exploit-leads-to-lockbit-ransomware/>) | 0 | 7 |
| 2026-02-20 | Elastic Security Labs | [MIMICRAT: ClickFix Campaign Delivers Custom RAT via Compromised Legitimate Websites](<https://www.elastic.co/security-labs/threat-command/mimicrat-custom-rat-mimics-c2-frameworks>) | 0 | 8 |
| 2026-02-19 | ESET WeLiveSecurity | [PromptSpy ushers in the era of Android threats using GenAI](<https://www.welivesecurity.com/en/eset-research/promptspy-ushers-in-era-android-threats-using-genai/>) | 0 | 4 |
| 2026-02-18 | Elastic Security Labs | [Speeding APT Attack Confirmation with Attack Discovery, Workflows, and Agent Builder](<https://www.elastic.co/security-labs/blog/speeding-apt-attack-discovery-confirmation-with-attack-discovery-workflows-and-agent-builder>) | 0 | 1 |
| 2026-02-16 | Huntress | [A New RAT and a Hands-on-Keyboard Intrusion](<https://www.huntress.com/blog/clickfix-matanbuchus-astarionrat-analysis>) | 0 | 12 |
| 2026-02-13 | Lab52 | [Operation MacroMaze: new APT28 campaign using basic tooling and legit infrastructure](<https://lab52.io/blog/operation-macromaze-new-apt28-campaign-using-basic-tooling-and-legit-infrastructure/>) | 0 | 17 |
| 2026-02-11 | Huntress | [Employee Monitoring and SimpleHelp Software Abused in \| Huntress](<https://www.huntress.com/blog/employee-monitoring-simplehelp-abused-in-ransomware-operations>) | 0 | 12 |
| 2026-02-11 | Bitdefender Labs | [LummaStealer Is Getting a Second Life Alongside CastleLoader](<https://www.bitdefender.com/en-us/blog/labs/lummastealer-second-life-castleloader>) | 0 | 3 |
| 2026-02-11 | Elastic Security Labs | [BADIIS to the Bone: New Insights to a Global SEO Poisoning Campaign](<https://www.elastic.co/security-labs/threat-command/badiis-to-the-bone-new-insights-to-global-seo-poisoning-campaign>) | 0 | 13 |
| 2026-02-10 | Elastic Security Labs | [SolarWinds Web Help Desk Exploitation - February 2026](<https://www.elastic.co/security-labs/blog/solarwinds-whd-exploitation>) | 0 | 5 |
| 2026-02-08 | Huntress | [Active Exploitation of SolarWinds Web Help Desk (CVE-2025-26399)](<https://www.huntress.com/blog/active-exploitation-solarwinds-web-help-desk-cve-2025-26399>) | 0 | 12 |
| 2026-02-06 | Elastic Security Labs | [DYNOWIPER: Destructive Malware Targeting Poland's Energy Sector](<https://www.elastic.co/security-labs/blog/dynowiper>) | 1 | 7 |
| 2026-02-05 | Bitdefender Labs | [Helpful Skills or Hidden Payloads? Bitdefender Labs Dives Deep into the OpenClaw Malicious Skill Trap](<https://www.bitdefender.com/en-us/blog/labs/helpful-skills-or-hidden-payloads-bitdefender-labs-dives-deep-into-the-openclaw-malicious-skill-trap>) | 0 | 2 |
| 2026-02-05 | Zscaler ThreatLabz | [Technical Analysis of Marco Stealer](<https://www.zscaler.com/blogs/security-research/technical-analysis-marco-stealer>) | 0 | 3 |
| 2026-02-04 | Huntress | [They Got In Through SonicWall. Then They Tried to Kill \| Huntress](<https://www.huntress.com/blog/encase-byovd-edr-killer>) | 0 | 4 |
| 2026-02-04 | Check Point Research | [Amaranth-Dragon: Weaponizing CVE-2025-8088 for Targeted Espionage in the Southeast Asia](<https://research.checkpoint.com/2026/amaranth-dragon-weaponizes-cve-2025-8088-for-targeted-espionage/>) | 0 | 67 |
| 2026-02-03 | Infoblox Threat Intel | [Compromised Routers, DNS, and a TDS Hidden in Aeza Networks](<https://www.infoblox.com/blog/threat-intelligence/compromised-routers-dns-and-a-tds-hidden-in-aeza-networks/>) | 0 | 2 |
| 2026-01-30 | ESET WeLiveSecurity | [DynoWiper update: Technical analysis and attribution](<https://www.welivesecurity.com/en/eset-research/dynowiper-update-technical-analysis-attribution/>) | 1 | 7 |
| 2026-01-29 | Bitdefender Labs | [Android Trojan Campaign Uses Hugging Face Hosting for RAT Payload Delivery](<https://www.bitdefender.com/en-us/blog/labs/android-trojan-campaign-hugging-face-hosting-rat-payload>) | 0 | 16 |
| 2026-01-27 | Darktrace | [The Year Ahead: AI Cybersecurity Trends to Watch in 2026](<https://www.darktrace.com/blog/the-year-ahead-ai-cybersecurity-trends-to-watch-in-2026>) | 0 | 13 |
| 2026-01-27 | Zscaler ThreatLabz | [APT Attacks Target Indian Government Using SHEETCREEP, FIREPOWER, and MAILCREEP \| Part 2](<https://www.zscaler.com/blogs/security-research/apt-attacks-target-indian-government-using-sheetcreep-firepower-and>) | 0 | 2 |
| 2026-01-26 | Darktrace | [Darktrace Identifies Campaign Targeting South Korea Leveraging VS Code for Remote Access](<https://www.darktrace.com/blog/darktrace-identifies-campaign-targeting-south-korea-leveraging-vs-code-for-remote-access>) | 0 | 14 |
| 2026-01-26 | Zscaler ThreatLabz | [APT Attacks Target Indian Government Using GOGITTER, GITSHELLPAD, and GOSHELL \| Part 1](<https://www.zscaler.com/blogs/security-research/apt-attacks-target-indian-government-using-gogitter-gitshellpad-and-goshell>) | 0 | 4 |
| 2026-01-25 | Darktrace | [How a Leading Bank is Prioritizing Risk Management with Darktrace](<https://www.darktrace.com/blog/how-a-leading-bank-is-prioritizing-risk-management-to-power-a-resilient-future>) | 0 | 13 |
| 2026-01-24 | Darktrace | [Medusa Ransomware 2025: RMM Abuse in Ransomware Campaigns](<https://www.darktrace.com/blog/under-medusas-gaze-how-darktrace-uncovers-rmm-abuse-in-ransomware-campaigns>) | 0 | 29 |
| 2026-01-23 | ESET WeLiveSecurity | [ESET Research: Sandworm behind cyberattack on Poland’s power grid in late 2025](<https://www.welivesecurity.com/en/eset-research/eset-research-sandworm-cyberattack-poland-power-grid-late-2025/>) | 1 | 0 |
| 2026-01-22 | Huntress | [Huntress Catches SmarterMail Account Takeover Leading to RCE](<https://www.huntress.com/blog/smartermail-account-takeover-leading-to-rce>) | 0 | 28 |
| 2026-01-22 | Check Point Research | [KONNI Adopts AI to Generate PowerShell Backdoors](<https://research.checkpoint.com/2026/konni-targets-developers-with-ai-malware/>) | 0 | 14 |
| 2026-01-20 | Seqrite | [Operation DupeHike : UNG0902 targets Russian employees with DUPERUNNER and AdaptixC2](<https://www.seqrite.com/blog/operation-dupehike-ung0902-targets-russian-employees-with-duperunner-and-adaptixc2/>) | 0 | 12 |
| 2026-01-19 | Seqrite | [Operation Nomad Leopard: Targeted Spear-Phishing Campaign Against Government Entities in Afghanistan](<https://www.seqrite.com/blog/operation-nomad-leopard-targeted-spear-phishing-campaign-against-government-entities-in-afghanistan/>) | 0 | 9 |
| 2026-01-16 | Huntress | [Dissecting CrashFix: KongTuke's New Toy](<https://www.huntress.com/blog/malicious-browser-extention-crashfix-kongtuke>) | 0 | 13 |
| 2026-01-14 | Microsoft Threat Intelligence | [Inside RedVDS: How a single virtual desktop provider fueled worldwide cybercriminal operations](<https://www.microsoft.com/en-us/security/blog/2026/01/14/inside-redvds-how-a-single-virtual-desktop-provider-fueled-worldwide-cybercriminal-operations/>) | 0 | 4 |
| 2026-01-14 | Check Point Research | [Sicarii Ransomware: Truth vs Myth](<https://research.checkpoint.com/2026/sicarii-ransomware-truth-vs-myth/>) | 0 | 41 |
| 2026-01-13 | Check Point Research | [Unveiling VoidLink – A Stealthy, Cloud-Native Linux Malware Framework](<https://research.checkpoint.com/2026/voidlink-the-cloud-native-malware-framework/>) | 1 | 8 |
| 2026-01-12 | Huntress | [Reflecting on AI in 2025: Faster Attacks, Same Old Tradecraft](<https://www.huntress.com/blog/ai-2025-faster-attacks-same-tradecraft>) | 0 | 6 |
| 2026-01-08 | Infoblox Threat Intel | [Scaling the Fraud Economy: Pig Butchering as a Service](<https://www.infoblox.com/blog/threat-intelligence/scaling-the-fraud-economy-pig-butchering-as-a-service/>) | 0 | 1 |
| 2026-01-07 | Huntress | [ESXi Exploitation in the Wild](<https://www.huntress.com/blog/esxi-vm-escape-exploit>) | 0 | 5 |
| 2026-01-07 | Check Point Research | [Inside GoBruteforcer: AI-Generated Server Defaults, Weak Passwords, and Crypto-Focused Campaigns](<https://research.checkpoint.com/2026/inside-gobruteforcer-ai-generated-server-defaults-weak-passwords-and-crypto-focused-campaigns/>) | 0 | 14 |
| 2026-01-06 | Microsoft Threat Intelligence | [Phishing actors exploit complex routing and misconfigurations to spoof domains](<https://www.microsoft.com/en-us/security/blog/2026/01/06/phishing-actors-exploit-complex-routing-and-misconfigurations-to-spoof-domains/>) | 0 | 13 |
| 2026-01-05 | Darktrace | [Enterprise AI Security Framework for Models, Data and Agents](<https://www.darktrace.com/blog/how-to-secure-ai-in-the-enterprise-a-practical-framework-for-models-data-and-agents>) | 0 | 13 |
| 2026-01-04 | Darktrace | [How to Manage Risk in Amazon Bedrock](<https://www.darktrace.com/blog/securing-generative-ai-managing-risk-in-amazon-bedrock-with-darktrace-cloud>) | 0 | 13 |
| 2026-01-03 | Darktrace | [AI Maturity Model: A Roadmap for Security](<https://www.darktrace.com/blog/introducing-the-ai-maturity-model-for-cybersecurity>) | 0 | 13 |
| 2026-01-01 | Darktrace | [Darktrace delivers the next evolution of unified and proactive NDR](<https://www.darktrace.com/blog/darktrace-redefines-ndr-industry-first-autonomous-threat-investigation-from-network-to-endpoint-with-agentic-ai>) | 0 | 13 |
| 2026-01-01 | Objective-See | [The Mac Malware of 2025](<https://objective-see.org/blog/blog_0x84.html>) | 0 | 6 |
| 2025-12-31 | Huntress | [Rogue RMMs: Common Social Engineering Tactics We Saw in 2025](<https://www.huntress.com/blog/rogue-screenconnect-social-engineering-tactics-2025>) | 0 | 2 |
| 2025-12-22 | Seqrite | [UNG0801: Tracking Threat Clusters obsessed with AV Icon Spoofing targeting Israel](<https://www.seqrite.com/blog/ung0801-tracking-threat-clusters-obsessed-with-av-icon-spoofing-targeting-israel/>) | 1 | 7 |
| 2025-12-22 | Seqrite | [Indian Income Tax-Themed Phishing Campaign Targets Local Businesses](<https://www.seqrite.com/blog/indian-income-tax-themed-phishing-campaign-targets-local-businesses/>) | 0 | 5 |
| 2025-12-22 | Huntress | [Trial, Error & Typos: Malware Isn't Always 'Sophisticated' \| Huntress](<https://www.huntress.com/blog/trial-error-typos-malware-attacks-sophisticated>) | 0 | 5 |
| 2025-12-18 | Huntress | [Gladinet CentreStack/Triofox: Cryptography Vulnerability \| Huntress](<https://www.huntress.com/blog/active-exploitation-gladinet-centrestack-triofox-insecure-cryptography-vulnerability>) | 0 | 2 |
| 2025-12-18 | Huntress | [A Series of Unfortunate (RMM) Events](<https://www.huntress.com/blog/series-of-unfortunate-rmm-events>) | 0 | 11 |
| 2025-12-17 | The DFIR Report | [Cat’s Got Your Files: Lynx Ransomware](<https://thedfirreport.com/2025/12/17/cats-got-your-files-lynx-ransomware/>) | 0 | 12 |
| 2025-12-17 | Check Point Research | [GachiLoader: Defeating Node.js Malware with API Tracing](<https://research.checkpoint.com/2025/gachiloader-node-js-malware-with-api-tracing/>) | 0 | 324 |
| 2025-12-16 | Zscaler ThreatLabz | [BlindEagle Targets Colombian Government Agency with Caminho and DCRAT](<https://www.zscaler.com/blogs/security-research/blindeagle-targets-colombian-government-agency-caminho-and-dcrat>) | 0 | 3 |
| 2025-12-16 | Infoblox Threat Intel | [Parked Domains Become Weapons with Direct Search Advertising](<https://www.infoblox.com/blog/threat-intelligence/parked-domains-become-weapons-with-direct-search-advertising/>) | 0 | 12 |
| 2025-12-16 | Check Point Research | [Inside Ink Dragon: Revealing the Relay Network and Inner Workings of a Stealthy Offensive Operation](<https://research.checkpoint.com/2025/ink-dragons-relay-network-and-offensive-operation/>) | 1 | 16 |
| 2025-12-16 | NVISO Labs | [The Detection & Response Chronicles: Exploring Telegram Abuse](<https://blog.nviso.eu/2025/12/16/the-detection-response-chronicles-exploring-telegram-abuse/>) | 0 | 61 |
| 2025-12-15 | Microsoft Threat Intelligence | [Defending against the CVE-2025-55182 (React2Shell) vulnerability in React Server Components](<https://www.microsoft.com/en-us/security/blog/2025/12/15/defending-against-the-cve-2025-55182-react2shell-vulnerability-in-react-server-components/>) | 1 | 51 |
| 2025-12-12 | Seqrite | [Operation MoneyMount-ISO — Deploying Phantom Stealer via ISO-Mounted Executables](<https://www.seqrite.com/blog/operation-moneymount-iso-deploying-phantom-stealer-via-iso-mounted-executables/>) | 0 | 4 |
| 2025-12-11 | Elastic Security Labs | [NANOREMOTE, cousin of FINALDRAFT](<https://www.elastic.co/security-labs/threat-command/nanoremote>) | 0 | 6 |
| 2025-12-10 | Check Point Research | [Cracking ValleyRAT: From Builder Secrets to Kernel Rootkits](<https://research.checkpoint.com/2025/cracking-valleyrat-from-builder-secrets-to-kernel-rootkits/>) | 0 | 39 |
| 2025-12-10 | Huntress | [PeerBlight Linux Backdoor Exploits React2Shell CVE-2025-55182](<https://www.huntress.com/blog/peerblight-linux-backdoor-exploits-react2shell>) | 0 | 40 |
| 2025-12-09 | Bitdefender Labs | [CVE-2025-55182 Exploitation Hits the Smart Home](<https://www.bitdefender.com/en-us/blog/labs/cve-2025-55182-exploitation-hits-the-smart-home>) | 0 | 2 |
| 2025-12-09 | Huntress | [AI-Poisoning & AMOS Stealer: The Biggest Mac Threat \| Huntress](<https://www.huntress.com/blog/amos-stealer-chatgpt-grok-ai-trust>) | 0 | 4 |
| 2025-12-04 | Volexity | [Dangerous Invitations: Russian Threat Actor Spoofs European Security Events in Targeted Phishing Attacks](<https://www.volexity.com/blog/2025/12/04/dangerous-invitations-russian-threat-actor-spoofs-european-security-events-in-targeted-phishing-attacks/>) | 0 | 2 |
| 2025-12-03 | Huntress | [Velociraptor Misuse, Pt. II: The Eye of the Storm](<https://www.huntress.com/blog/velociraptor-misuse-part-two-eye-of-the-storm>) | 0 | 5 |
| 2025-12-01 | Infoblox Threat Intel | [DNS Uncovers Infrastructure Used in SSO Attacks](<https://www.infoblox.com/blog/threat-intelligence/dns-uncovers-infrastructure-used-in-sso-attacks/>) | 0 | 1 |
| 2025-11-28 | Darktrace | [Phishing attacks surge by 620% in the lead-up to Black Friday](<https://www.darktrace.com/blog/phishing-attacks-surge-by-620-in-the-lead-up-to-black-friday>) | 0 | 13 |
| 2025-11-27 | Darktrace | [Tracking a Dragon: Investigating a DragonForce-affiliated ransomware attack with Darktrace](<https://www.darktrace.com/blog/tracking-a-dragon-investigating-a-dragonforce-affiliated-ransomware-attack-with-darktrace>) | 0 | 14 |
| 2025-11-26 | Darktrace | [Why API + Journaling Delivers Faster, SLA-Backed Email Security for Microsoft 365](<https://www.darktrace.com/blog/why-api-journaling-delivers-faster-sla-backed-email-security-for-microsoft-365>) | 0 | 13 |
| 2025-11-24 | Darktrace | [Vo1d Botnet Exposed: How Darktrace Detected a Global Android Threat](<https://www.darktrace.com/blog/unmasking-vo1d-inside-darktraces-botnet-detection>) | 0 | 21 |
| 2025-11-24 | Huntress | [ClickFix Gets Creative: Malware Buried in Images](<https://www.huntress.com/blog/clickfix-malware-buried-in-images>) | 0 | 38 |
| 2025-11-20 | Huntress | [Velociraptor WSUS Exploitation, Pt. I: WSUS-Up?](<https://www.huntress.com/blog/velociraptor-misuse-part-one-wsus-up>) | 0 | 2 |
| 2025-11-15 | Elastic Security Labs | [RONINGLOADER: DragonBreath’s New Path to PPL Abuse](<https://www.elastic.co/security-labs/threat-command/roningloader>) | 0 | 13 |
| 2025-11-13 | NVISO Labs | [Contagious Interview Actors Now Utilize JSON Storage Services for Malware Delivery](<https://blog.nviso.eu/2025/11/13/contagious-interview-actors-now-utilize-json-storage-services-for-malware-delivery/>) | 0 | 51 |
| 2025-11-05 | Huntress | [Gootloader \| Threat Detection Overview](<https://www.huntress.com/blog/gootloader-threat-detection-woff2-obfuscation>) | 0 | 89 |
| 2025-10-30 | Darktrace | [Salty Much: Darktrace’s take on a recent Salt Typhoon intrusion](<https://www.darktrace.com/blog/salty-much-darktraces-view-on-a-recent-salt-typhoon-intrusion>) | 0 | 32 |
| 2025-10-29 | Darktrace | [Akira SonicWall Campaign Uncovered](<https://www.darktrace.com/blog/inside-akiras-sonicwall-campaign-darktraces-detection-and-response>) | 0 | 23 |
| 2025-10-28 | Darktrace | [Detecting Vendor Compromise and Trusted Relationship Abuse with Darktrace](<https://www.darktrace.com/blog/out-of-character-detecting-vendor-compromise-and-trusted-relationship-abuse-with-darktrace>) | 0 | 16 |
| 2025-10-23 | Infoblox Threat Intel | [Vault Viper: High Stakes, Hidden Threats](<https://www.infoblox.com/blog/threat-intelligence/vault-viper-high-stakes-hidden-threats/>) | 0 | 11 |
| 2025-10-22 | Huntress | [Looking Through a Pinhole at a Qilin Ransomware Attack](<https://www.huntress.com/blog/looking-at-qilin-ransomware-attack>) | 0 | 2 |
| 2025-10-22 | Elastic Security Labs | [TOLLBOOTH: What's yours, IIS mine](<https://www.elastic.co/security-labs/threat-command/tollbooth>) | 1 | 11 |
| 2025-10-15 | Huntress | [The Crown Prince, Nezha \| Huntress](<https://www.huntress.com/blog/nezha-china-nexus-threat-actor-tool>) | 0 | 15 |
| 2025-10-14 | Elastic Security Labs | [NightMARE on 0xelm Street, a guided tour](<https://www.elastic.co/security-labs/threat-command/nightmare-on-0xelm-street>) | 0 | 19 |
| 2025-09-08 | The DFIR Report | [Blurring the Lines: Intrusion Shows Connection With Three Major Ransomware Gangs](<https://thedfirreport.com/2025/09/08/blurring-the-lines-intrusion-shows-connection-with-three-major-ransomware-gangs/>) | 0 | 30 |

## Named by several publishers but not blocked

Corroboration does not override a safety check. Each one says why.

- `github[.]com` (12 publishers, enrichment): sources disagree: at least one describes it as a victim or legitimate service
- `raw[.]githubusercontent[.]com` (6 publishers, enrichment): githubusercontent.com is on the allowlist (hard policy)
- `sfrclak[.]com` (6 publishers, hunting): sources disagree: at least one describes it as a victim or legitimate service
- `142[.]11[.]206[.]73` (5 publishers, hunting): past its 30-day blocking lifetime, counted from first publication
- `api[.]telegram[.]org` (5 publishers, enrichment): telegram.org is on the allowlist (hard policy)
- `api[.]ipify[.]org` (4 publishers, hunting): sources disagree: at least one describes it as a victim or legitimate service
- `google[.]com` (4 publishers, enrichment): google.com is on the allowlist (hard policy)
- `hxxp://sfrclak[.]com:8000/6202033` (4 publishers, hunting): sources disagree: at least one describes it as a victim or legitimate service
- `login[.]microsoftonline[.]com` (4 publishers, enrichment): microsoftonline.com is on the allowlist (hard policy)
- `steamcommunity[.]com` (4 publishers, hunting): popular site (steamcommunity.com is ranked #432); often a victim, lure or abused service
- `t[.]me` (4 publishers, enrichment): t.me is on the allowlist (hard policy)
- `telegram[.]me` (4 publishers, hunting): popular site (telegram.me is ranked #297); often a victim, lure or abused service
- `www[.]dropbox[.]com` (4 publishers, enrichment): dropbox.com is on the allowlist (hard policy)
- `arch2[.]maxdatahost1[.]cyou` (3 publishers, hunting): past its 90-day blocking lifetime, counted from first publication
- `archive[.]org` (3 publishers, hunting): sources disagree: at least one describes it as a victim or legitimate service
- `buisness-centeral-transportation[.]com` (3 publishers, hunting): past its 90-day blocking lifetime, counted from first publication
- `business-startup[.]azurewebsites[.]net` (3 publishers, hunting): past its 90-day blocking lifetime, counted from first publication
- `businessstartup[.]azurewebsites[.]net` (3 publishers, hunting): past its 90-day blocking lifetime, counted from first publication
- `callnrwise[.]com` (3 publishers, hunting): past its 90-day blocking lifetime, counted from first publication
- `e10b1fa84f1d6481625f741b69892780140d4e0e7769e7491e5f4d894c2e0e09` (3 publishers, hunting): reported as malware file; passed every safety check
- `e49c2732fb9861548208a78e72996b9c3c470b6b562576924bcc3a9fb75bf9ff` (3 publishers, hunting): reported as malware file; passed every safety check
- `gofile[.]io` (3 publishers, hunting): popular site (gofile.io is ranked #5260); often a victim, lure or abused service
- `ipinfo[.]io` (3 publishers, hunting): popular site (ipinfo.io is ranked #572); often a victim, lure or abused service
- `packages[.]npm[.]org` (3 publishers, hunting): past its 90-day blocking lifetime, counted from first publication
- `pastebin[.]com` (3 publishers, enrichment): pastebin.com is on the allowlist (hard policy)

## Feed health

- BleepingComputer: read, but none of its 15 recent articles had indicators.
- **Sophos Threat Research: failed, failing for 4 runs since 2026-10-09.** The read operation timed out

## How to use this

- `confident/`: corroborated and validated; check against your own traffic, then block. `blocking/`: validated; run in alert-only mode first. `hunting/`: search logs, never block. Every file expires with the release.
- `domains.txt` holds registered domains: block them with their subdomains. `hosts.txt` holds exact host names, such as one tenant on a shared platform: never widen them to the parent.
- Corroboration counts independent sources: one publisher's articles count once, and an article that links to another report counts with it. Uncited copying and joint research cannot be detected.
- Evidence, reasons and source excerpts for every indicator: `indicators.json`.
- Indicators in this report are defanged. The lists are not.
