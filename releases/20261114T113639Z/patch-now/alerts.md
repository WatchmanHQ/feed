# Patch now

WatchmanHQ patch-now alerts, release 20261114T113639Z, built 2026-11-14 11:36 UTC.

Flaws attackers are exploiting, in equipment small firms and their IT providers run. Each one is in CISA's Known Exploited Vulnerabilities catalog, so attackers are already using it, and a report we read names it. Newest first.

**If you run one of these:** Install the vendor's update, or its workaround until there is one, then follow the advisory's steps to look for signs of compromise: an update closes the hole, it does not remove an attacker who got in first. If the device gets no more updates (past its end of life), take it off the internet and replace it.

24 alerts: 7 newly exploited, 17 older. [CISA catalog](<https://www.cisa.gov/known-exploited-vulnerabilities-catalog>) version 2026.11.13, read 2026-11-14.

## Newly exploited

CISA added these to its catalog in the last 30 days.

### CVE-2026-123039: Check Point Multiple Products

Firewall, VPN or other appliance (Check Point). **Check Point Multiple Products Incorrect Permission Assignment for Critical Resource Vulnerability.** Check Point Firewall, Multi-Domain Security Management Server, Scalable Platforms, Security Gateway, and Security Management Server contain an incorrect permissions assignment for critical resources vulnerability when the Gaia OS DynamicCLI daemon runs as root and listens on a world-writable local socket without authenticating connecting processes. An authenticated local user can send a command to the socket and have it executed as root.

- Exploited: CISA listed it on 2026-11-13.
- Vendor advisory: [support.checkpoint.com](<https://support.checkpoint.com/results/sk/sk1000362>)
- Reported by: [Check Point warns of zero-day flaw exploited for root access](<https://www.bleepingcomputer.com/news/security/check-point-patches-zero-day-that-lets-hackers-get-root-access/>) (BleepingComputer, 2026-11-13); [Check Point gateways hacked via PHP2Shell to deploy VMware ESXi wiper](<https://www.bleepingcomputer.com/news/security/check-point-gateways-hacked-via-php2shell-to-deploy-vmware-esxi-wiper/>) (BleepingComputer, 2026-11-13); [PHP2Shell Exploitation on Check Point Gateway](<https://research.checkpoint.com/2026/php2shell-exploitation-on-check-point-gateway/>) (Check Point Research, 2026-11-12)
- Details: [CVE-2026-123039 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-123039>)

### CVE-2026-19868: SonicWall SonicOS SSLVPN

Firewall, VPN or other appliance (SonicWall). **SonicWall SonicOS SSLVPN Use of Single-factor Authentication Vulnerability.** SonicWall SonicOS SSLVPN contains a use of single-factor authentication vulnerability that may allow a user with valid credentials for an alternate authentication method to bypass SAML authentication controls. Successful exploitation may also bypass SAML-enforced multi-factor authentication (MFA).

- Exploited: CISA listed it on 2026-11-06.
- Vendor advisory: [psirt.global.sonicwall.com](<https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2026-0014>)
- Reported by: [9th November – Threat Intelligence Report](<https://research.checkpoint.com/2026/9th-november-threat-intelligence-report/>) (Check Point Research, 2026-11-09); [SonicWall warns of new SSL-VPN MFA bypass flaw exploited in attacks](<https://www.bleepingcomputer.com/news/security/sonicwall-warns-of-new-ssl-vpn-mfa-bypass-flaw-exploited-in-attacks/>) (BleepingComputer, 2026-11-07)
- Details: [CVE-2026-19868 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-19868>)

### CVE-2025-61624: Fortinet Multiple Products

Firewall, VPN or other appliance (Fortinet). **Fortinet Multiple Products Path Traversal Vulnerability.** FortiOS, FortiPAM, FortiProxy, and FortiSwitchManager contain a path traversal vulnerability that may allow an authenticated attacker with admin profile and at least read-write permissions to write or delete arbitrary files via specific CLI commands.

- Exploited: CISA listed it on 2026-10-16.
- Vendor advisory: [fortiguard.fortinet.com](<https://fortiguard.fortinet.com/psirt/FG-IR-26-122>)
- Reported by: [October 2026 CVE Landscape](<https://www.recordedfuture.com/blog/october-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-11-06); [Unit 42 Uncovers PEERSTITCH, a Stealthy FortiGate Implant](<https://unit42.paloaltonetworks.com/fortimanager-cve-2024-47575-peerstitch-malware/>) (Unit 42, 2026-10-14)
- Details: [CVE-2025-61624 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2025-61624>)

### CVE-2026-102764: BeyondTrust Remote Support

Remote support (BeyondTrust). **BeyondTrust Remote Support Authentication Bypass by Spoofing Vulnerability.** BeyondTrust Remote Support contains an authentication bypass by spoofing vulnerability that could allow a remote attacker to perform file operations on the appliance.

- Exploited: CISA listed it on 2026-10-16.
- Vendor advisory: [www.beyondtrust.com](<https://www.beyondtrust.com/trust-center/security-advisories/bt26-05>)
- Reported by: [October 2026 CVE Landscape](<https://www.recordedfuture.com/blog/october-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-11-06); [Rapid7 Analysis: Unauthenticated File Upload to RCE in BeyondTrust Remote Support (CVE-2026-102764)](<https://www.rapid7.com/blog/post/ra-rapid7-analysis-unauthenticated-file-upload-to-rce-in-beyondtrust-remote-support-cve-2026-102764>) (Rapid7, 2026-10-30); [CVE-2026-102764: Critical BeyondTrust Remote Support Authentication Bypass Exploited in the Wild](<https://www.rapid7.com/blog/post/etr-cve-2026-102764-critical-beyondtrust-remote-support-authentication-bypass-exploited-in-the-wild>) (Rapid7, 2026-10-19); [19th October – Threat Intelligence Report](<https://research.checkpoint.com/2026/19th-october-threat-intelligence-report/>) (Check Point Research, 2026-10-19); [BeyondTrust patches zero-day exploited in attacks since August](<https://www.bleepingcomputer.com/news/security/beyondtrust-patches-zero-day-exploited-in-attacks-since-august/>) (BleepingComputer, 2026-10-16) and 1 more
- Details: [CVE-2026-102764 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-102764>)

### CVE-2026-111357: Ivanti Connect Secure

VPN or device management (Ivanti). **Ivanti Connect Secure Missing Authentication for Critical Function Vulnerability.** Ivanti Connect Secure contains a missing authentication for critical function vulnerability that could allow a local authenticated attacker to escalate their privileges. This vulnerability can be chained with CVE-2026-104935 and CVE-2026-118527.

- Exploited: CISA listed it on 2026-10-30.
- Vendor advisory: [hub.ivanti.com](<https://hub.ivanti.com/s/article/Security-Advisory-Ivanti-Connect-Secure-CVE-2026-104935?language=en_US>)
- Reported by: [October 2026 CVE Landscape](<https://www.recordedfuture.com/blog/october-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-11-06); [Additional Ivanti Connect Secure zero-days exploited in the wild (CVE-2026-111357, CVE-2026-118527)](<https://www.rapid7.com/blog/post/etr-additional-ivanti-connect-secure-zero-days-exploited-in-the-wild-cve-2026-111357-cve-2026-118527>) (Rapid7, 2026-11-02); [Ivanti patches two more Connect Secure zero-days chained in attacks](<https://www.bleepingcomputer.com/news/security/ivanti-patches-two-more-connect-secure-zero-days-chained-in-attacks/>) (BleepingComputer, 2026-11-02); [A Series of Unauthenticated Events: Chained Exploitation of Ivanti Connect Secure Zero-Days](<https://www.volexity.com/blog/2026/10/13/a-series-of-unauthenticated-events-chained-exploitation-of-ivanti-connect-secure-zero-days/>) (Volexity, 2026-10-13)
- Details: [CVE-2026-111357 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-111357>)

### CVE-2026-118527: Ivanti Connect Secure

VPN or device management (Ivanti). **Ivanti Connect Secure Generation of Predictable Numbers or Identifiers Vulnerability.** Ivanti Connect Secure contains a generation of predictable numbers or identifiers vulnerability that allows a remote authenticated attacker to upload files with attacker-controlled content to a known location on disk. This vulnerability can be chained with CVE-2026-104935 and CVE-2026-111357.

- Exploited: CISA listed it on 2026-10-30.
- Vendor advisory: [hub.ivanti.com](<https://hub.ivanti.com/s/article/Security-Advisory-Ivanti-Connect-Secure-CVE-2026-104935?language=en_US>)
- Reported by: [October 2026 CVE Landscape](<https://www.recordedfuture.com/blog/october-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-11-06); [Additional Ivanti Connect Secure zero-days exploited in the wild (CVE-2026-111357, CVE-2026-118527)](<https://www.rapid7.com/blog/post/etr-additional-ivanti-connect-secure-zero-days-exploited-in-the-wild-cve-2026-111357-cve-2026-118527>) (Rapid7, 2026-11-02); [Ivanti patches two more Connect Secure zero-days chained in attacks](<https://www.bleepingcomputer.com/news/security/ivanti-patches-two-more-connect-secure-zero-days-chained-in-attacks/>) (BleepingComputer, 2026-11-02)
- Details: [CVE-2026-118527 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-118527>)

### CVE-2026-76418: Cisco Secure Firewall ASA Software and Cisco Secure FTD Software

Firewall, VPN or office router (Cisco). **Cisco Secure Firewall ASA Software and Cisco Secure FTD Software Unchecked Return Value to NULL Pointer Dereference Vulnerability.** Cisco Secure Firewall ASA Software and Cisco Secure FTD Software contains an unchecked return value to NULL pointer dereference vulnerability that could allow an unauthenticated, remote attacker to cause the device to reload unexpectedly, resulting in a denial of service (DoS) condition.

- Exploited: CISA listed it on 2026-10-29.
- Vendor advisory: [sec.cloudapps.cisco.com](<https://sec.cloudapps.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-asaftd-tunnel-dos-s6mgkb75>)
- Reported by: [October 2026 CVE Landscape](<https://www.recordedfuture.com/blog/october-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-11-06); [2nd November – Threat Intelligence Report](<https://research.checkpoint.com/2026/2nd-november-threat-intelligence-report/>) (Check Point Research, 2026-11-02); [New Cisco firewall zero-day exploited to crash SSL VPN devices](<https://www.bleepingcomputer.com/news/security/cisco-warns-of-firewall-zero-day-exploited-to-crash-ssl-vpn-devices/>) (BleepingComputer, 2026-10-29)
- Details: [CVE-2026-76418 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-76418>)

## Older flaws, exploited again

CISA listed these earlier, and at least 2 publishers named them in the last 30 days: devices never updated, or past their end of life, are the targets.

### CVE-2026-84869: ConnectWise ScreenConnect

Remote support or IT management (ConnectWise). **ConnectWise ScreenConnect Improper Privilege Management and Missing Authorization Vulnerability.** ConnectWise ScreenConnect contains both an improper privilege management and missing authorization vulnerability that may allow an attacker to transfer and execute files through an active remote session without authorization or host confirmation.

- Exploited: CISA listed it on 2026-09-11.
- Vendor advisory: [www.connectwise.com](<https://www.connectwise.com/company/trust/security-bulletins/2026-09-08-screenconnect-bulletin>)
- Reported by: [Attackers use Crypto Exchange Names to Disguise Unauthorized Sessions on 100+ ScreenConnect Servers](<https://www.huntress.com/blog/fake-crypto-exchange-sessions-screenconnect>) (Huntress, 2026-11-14); [SCKit abuses ScreenConnect to deploy remote access and target technician sessions](<https://www.microsoft.com/en-us/security/blog/2026/11/13/sckit-abuses-screenconnect-deploy-remote-access-target-technician-sessions/>) (Microsoft Threat Intelligence, 2026-11-13); [SCKit Worm Installs Rogue ScreenConnect Clients and Session Cookie Relays Across Hundreds of Endpoints](<https://www.huntress.com/blog/sckit-worm-rogue-screenconnect>) (Huntress, 2026-11-12); [New worm-like 'SCKit' malware targets MSPs in ScreenConnect attacks](<https://www.bleepingcomputer.com/news/security/new-worm-like-sckit-malware-targets-msps-in-screenconnect-attacks/>) (BleepingComputer, 2026-11-12); [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13) and 1 more
- Details: [CVE-2026-84869 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-84869>)

### CVE-2026-0257: Palo Alto Networks PAN-OS

Firewall or VPN (Palo Alto Networks). **Palo Alto Networks PAN-OS Authentication Bypass Vulnerability.** Palo Alto Networks PAN-OS contains an authentication bypass vulnerability that allows attackers to bypass security restrictions and establish an unauthorized VPN connection.

- Exploited: CISA listed it on 2026-05-29. Used in ransomware attacks.
- Vendor advisory: [security.paloaltonetworks.com](<https://security.paloaltonetworks.com/CVE-2026-0257>)
- Reported by: [GhostFrame: A new ESXi Implant Linked to Settra Ransomware](<https://www.recordedfuture.com/blog/ghostframe-esxi-implant-settra-ransomware>) (Recorded Future Insikt Group, 2026-11-10); [IT threat evolution in Q3 2026. Non-mobile statistics](<https://securelist.com/malware-report-q3-2026-pc-iot-statistics/121843/>) (Securelist, 2026-11-10); [October 2026 CVE Landscape](<https://www.recordedfuture.com/blog/october-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-11-06); [Stray Cat, Open Doors: How k0t Wanders Through the Network Edge](<https://www.group-ib.com/blog/stray-cat-network-edge/>) (Group-IB, 2026-10-21); [Threat Brief: Critical Vulnerabilities in PHP: CVE-2026-109618, CVE-2026-109619](<https://unit42.paloaltonetworks.com/cve-2026-109618-cve-2026-109619/>) (Unit 42, 2026-10-21) and 3 more
- Details: [CVE-2026-0257 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-0257>)

### CVE-2026-15409: SonicWall SMA1000 Appliances

Firewall, VPN or other appliance (SonicWall). **SonicWall SMA1000 Appliances Server-Side Request Forgery Vulnerability.** SonicWall SMA1000 Appliances contain a server-side request forgery vulnerability that could allow a remote unauthenticated attacker to potentially cause the appliance to make requests to unintended location.

- Exploited: CISA listed it on 2026-07-14. Used in ransomware attacks.
- Vendor advisory: [psirt.global.sonicwall.com](<https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2026-0008>)
- Reported by: [IT threat evolution in Q3 2026. Non-mobile statistics](<https://securelist.com/malware-report-q3-2026-pc-iot-statistics/121843/>) (Securelist, 2026-11-10); [SonicWall warns of unpatched flaws in end-of-life GMS software](<https://www.bleepingcomputer.com/news/security/sonicwall-warns-of-unpatched-flaws-in-end-of-life-gms-software/>) (BleepingComputer, 2026-11-04); [Max severity SonicWall SMA1000 flaw now exploited in attacks](<https://www.bleepingcomputer.com/news/security/max-severity-sonicwall-sma1000-flaw-now-exploited-in-attacks/>) (BleepingComputer, 2026-10-09); [Fake AI, real malware: Attackers impersonating AI brands](<https://www.sophos.com/en-us/blog/fake-ai-real-malware-attackers-impersonating-ai-brands>) (Sophos Threat Research, 2026-08-19); [July 2026 CVE Landscape](<https://www.recordedfuture.com/blog/july-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-08-07) and 1 more
- Details: [CVE-2026-15409 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-15409>)

### CVE-2026-15410: SonicWall SMA1000 Appliances

Firewall, VPN or other appliance (SonicWall). **SonicWall SMA1000 Appliances Code Injection Vulnerability.** SonicWall SMA1000 Appliances contain a code injection vulnerability which in specific conditions could potentially enable a remote authenticated attacker as administrator to execute arbitrary OS commands.

- Exploited: CISA listed it on 2026-07-14. Used in ransomware attacks.
- Vendor advisory: [psirt.global.sonicwall.com](<https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2026-0008>)
- Reported by: [IT threat evolution in Q3 2026. Non-mobile statistics](<https://securelist.com/malware-report-q3-2026-pc-iot-statistics/121843/>) (Securelist, 2026-11-10); [SonicWall warns of unpatched flaws in end-of-life GMS software](<https://www.bleepingcomputer.com/news/security/sonicwall-warns-of-unpatched-flaws-in-end-of-life-gms-software/>) (BleepingComputer, 2026-11-04); [Max severity SonicWall SMA1000 flaw now exploited in attacks](<https://www.bleepingcomputer.com/news/security/max-severity-sonicwall-sma1000-flaw-now-exploited-in-attacks/>) (BleepingComputer, 2026-10-09); [Fake AI, real malware: Attackers impersonating AI brands](<https://www.sophos.com/en-us/blog/fake-ai-real-malware-attackers-impersonating-ai-brands>) (Sophos Threat Research, 2026-08-19); [July 2026 CVE Landscape](<https://www.recordedfuture.com/blog/july-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-08-07) and 1 more
- Details: [CVE-2026-15410 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-15410>)

### CVE-2026-18556: N-able N-central

IT management (N-able). **N-able N-central Authentication Bypass Using an Alternate Path or Channel Vulnerability.** N-able N-central contains an authentication bypass using an alternate path or channel that allows for authentication bypass.

- Exploited: CISA listed it on 2026-08-04.
- Vendor advisory: [uptime.n-able.com](<https://uptime.n-able.com/>), [status.n-able.com](<https://status.n-able.com/2026/08/02/n-central-2026-3-hotfix-1-mitigation-for-cve-2026-18577/>)
- Reported by: [N-able Disables Cloud Services Following Disclosure of "Able2Shell" Exploit Chains](<https://www.huntress.com/blog/n-able-disables-cloud-services-following-disclosure-of-able2shell-exploit-chains>) (Huntress, 2026-11-09); [The Race Against the 3-Day Clock: How Rapid7 Helps Meet BOD 26-04 Compliance](<https://www.rapid7.com/blog/post/it-racing-the-three-day-clock-cisa-bod-26-04>) (Rapid7, 2026-11-04); [August 2026 CVE Landscape](<https://www.recordedfuture.com/blog/august-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-09-08)
- Details: [CVE-2026-18556 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-18556>)

### CVE-2026-18577: N-able N-central

IT management (N-able). **N-able N-central Authentication Bypass Using an Alternate Path or Channel Vulnerability.** N-able N-central contains an authentication bypass using an alternate path or channel allows for authentication bypass and account takeover in N-central. This vulnerability is the result of an incomplete patch for CVE-2026-18556.

- Exploited: CISA listed it on 2026-08-03.
- Vendor advisory: [documentation.n-able.com](<https://documentation.n-able.com/N-central/Release_Notes/GA/Content/N-central_2026.3_HF1_Release_Notes.htm>), [status.n-able.com](<https://status.n-able.com/2026/08/02/n-central-2026-3-hotfix-1-mitigation-for-cve-2026-18577/>)
- Reported by: [N-able Disables Cloud Services Following Disclosure of "Able2Shell" Exploit Chains](<https://www.huntress.com/blog/n-able-disables-cloud-services-following-disclosure-of-able2shell-exploit-chains>) (Huntress, 2026-11-09); [The Race Against the 3-Day Clock: How Rapid7 Helps Meet BOD 26-04 Compliance](<https://www.rapid7.com/blog/post/it-racing-the-three-day-clock-cisa-bod-26-04>) (Rapid7, 2026-11-04); [August 2026 CVE Landscape](<https://www.recordedfuture.com/blog/august-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-09-08)
- Details: [CVE-2026-18577 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-18577>)

### CVE-2026-0322: Palo Alto Networks PAN-OS

Firewall or VPN (Palo Alto Networks). **Palo Alto Networks PAN-OS Code Injection Vulnerability.** Palo Alto Networks PAN-OS contains a code injection vulnerability that could allow an authenticated attacker with network access to execute arbitrary code with root privileges on the firewall.

- Exploited: CISA listed it on 2026-10-14.
- Vendor advisory: [security.paloaltonetworks.com](<https://security.paloaltonetworks.com/CVE-2026-0322>)
- Reported by: [October 2026 CVE Landscape](<https://www.recordedfuture.com/blog/october-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-11-06); [InfraTrust report warns of exploited flaws in critical network infrastructure](<https://www.bleepingcomputer.com/news/security/infratrust-report-warns-of-exploited-flaws-in-critical-network-infrastructure/>) (BleepingComputer, 2026-10-28); [Palo Alto Networks warns of PAN-OS RCE flaw exploited in attacks](<https://www.bleepingcomputer.com/news/security/palo-alto-networks-warns-of-pan-os-rce-flaw-exploited-in-attacks/>) (BleepingComputer, 2026-10-14)
- Details: [CVE-2026-0322 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-0322>)

### CVE-2026-104286: Fortinet FortiMail

Firewall, VPN or other appliance (Fortinet). **Fortinet FortiMail Path Traversal Vulnerability.** Fortinet FortiMail contains a path traversal and an improper neutralization of NULL byte or NULL character vulnerability that may allow an unauthenticated attacker to write arbitrary files on the underlying system via crafted HTTP or HTTPS requests.

- Exploited: CISA listed it on 2026-10-01.
- Vendor advisory: [fortiguard.fortinet.com](<https://fortiguard.fortinet.com/psirt/FG-IR-26-175>)
- Reported by: [October 2026 CVE Landscape](<https://www.recordedfuture.com/blog/october-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-11-06); [InfraTrust report warns of exploited flaws in critical network infrastructure](<https://www.bleepingcomputer.com/news/security/infratrust-report-warns-of-exploited-flaws-in-critical-network-infrastructure/>) (BleepingComputer, 2026-10-28); [Microsoft October 2026 Patch Tuesday fixes 1,411 flaws, 3 zero-days](<https://www.bleepingcomputer.com/news/microsoft/microsoft-october-2026-patch-tuesday-fixes-1-411-flaws-3-zero-days/>) (BleepingComputer, 2026-10-13); [CISA Adds One Known Exploited Vulnerability to Catalog](<https://www.cisa.gov/news-events/alerts/2026/10/01/cisa-adds-one-known-exploited-vulnerability-catalog>) (CISA Cybersecurity Advisories, 2026-10-01)
- Details: [CVE-2026-104286 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-104286>)

### CVE-2026-104935: Ivanti Connect Secure

VPN or device management (Ivanti). **Ivanti Connect Secure Authentication Bypass by Spoofing Vulnerability.** Ivanti Connect Secure contains an authentication bypass by spoofing vulnerability that allows a remote unauthenticated attacker to execute arbitrary commands.

- Exploited: CISA listed it on 2026-10-13.
- Reported by: [October 2026 CVE Landscape](<https://www.recordedfuture.com/blog/october-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-11-06); [Additional Ivanti Connect Secure zero-days exploited in the wild (CVE-2026-111357, CVE-2026-118527)](<https://www.rapid7.com/blog/post/etr-additional-ivanti-connect-secure-zero-days-exploited-in-the-wild-cve-2026-111357-cve-2026-118527>) (Rapid7, 2026-11-02); [Ivanti patches two more Connect Secure zero-days chained in attacks](<https://www.bleepingcomputer.com/news/security/ivanti-patches-two-more-connect-secure-zero-days-chained-in-attacks/>) (BleepingComputer, 2026-11-02); [InfraTrust report warns of exploited flaws in critical network infrastructure](<https://www.bleepingcomputer.com/news/security/infratrust-report-warns-of-exploited-flaws-in-critical-network-infrastructure/>) (BleepingComputer, 2026-10-28); [19th October – Threat Intelligence Report](<https://research.checkpoint.com/2026/19th-october-threat-intelligence-report/>) (Check Point Research, 2026-10-19) and 5 more
- Details: [CVE-2026-104935 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-104935>)

### CVE-2026-88771: Citrix NetScaler

Remote access or file sharing (Citrix). **Citrix NetScaler Improper Input Validation Vulnerability.** Citrix NetScaler ADC and NetScaler Gateway contain an improper input validation vulnerability that could allow an unauthenticated attacker to execute arbitrary commands.

- Exploited: CISA listed it on 2026-09-27.
- Vendor advisory: [community.citrix.com](<https://community.citrix.com/techzone-blogs/110_security-updates/netscaler-adc-and-netscaler-gateway-security-bulletin-for-cve-2026-88771-through-cve-2026-88778>), [support.citrix.com](<https://support.citrix.com/support-home/kbsearch/article?articleNumber=CTX697096>), [support.citrix.com](<https://support.citrix.com/external/article/CTX694799/steps-to-take-if-netscaler-adc-is-suspec.html>)
- Reported by: [Metasploit Wrapup: Unauth RCE modules in Network Perimeter Devices and much more](<https://www.rapid7.com/blog/post/pt-metasploit-wrapup-unauth-rce-modules-in-network-perimeter-devices-and-much-more>) (Rapid7, 2026-11-06); [CVE-2026-111497: Node2Shell / HTTP2Shell Vulnerability May Allow RCE](<https://www.zscaler.com/blogs/security-research/cve-2026-111497-node2shell-http2shell-vulnerability-may-allow-rce>) (Zscaler ThreatLabz, 2026-10-28); [InfraTrust report warns of exploited flaws in critical network infrastructure](<https://www.bleepingcomputer.com/news/security/infratrust-report-warns-of-exploited-flaws-in-critical-network-infrastructure/>) (BleepingComputer, 2026-10-28); [CVE-2026-109618 and CVE-2026-109619: PHP Vulnerable to Unauthenticated RCE Attacks](<https://www.zscaler.com/blogs/security-research/cve-2026-109618-and-cve-2026-109619-php-vulnerable-unauthenticated-rce>) (Zscaler ThreatLabz, 2026-10-21); [Threat Brief: Critical Vulnerabilities in PHP: CVE-2026-109618, CVE-2026-109619](<https://unit42.paloaltonetworks.com/cve-2026-109618-cve-2026-109619/>) (Unit 42, 2026-10-21) and 13 more
- Details: [CVE-2026-88771 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-88771>)

### CVE-2026-88779: Citrix NetScaler

Remote access or file sharing (Citrix). **Citrix NetScaler Improper Restriction of Operations within the Bounds of a Memory Buffer Vulnerability.** Citrix NetScaler ADC (formerly Citrix ADC) and Citrix NetScaler Gateway (formerly Citrix Gateway) contain an improper restriction of operations within the bounds of a memory buffer vulnerability that could allow for a denial of service.

- Exploited: CISA listed it on 2026-10-04.
- Vendor advisory: [support.citrix.com](<https://support.citrix.com/support-home/kbsearch/article?articleNumber=CTX697174>), [community.citrix.com](<https://community.citrix.com/techzone-blogs/110_security-updates/understanding-and-addressing-cve-2026-88779-in-citrix-netscaler-adc-and-citrix-netscaler-gateway/>)
- Reported by: [October 2026 CVE Landscape](<https://www.recordedfuture.com/blog/october-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-11-06); [InfraTrust report warns of exploited flaws in critical network infrastructure](<https://www.bleepingcomputer.com/news/security/infratrust-report-warns-of-exploited-flaws-in-critical-network-infrastructure/>) (BleepingComputer, 2026-10-28); [Rapid7 Analysis: NetScaler intrusions chaining CVE-2026-88771 and CVE-2026-88779](<https://www.rapid7.com/blog/post/ra-netscaler-intrusions-chaining-cve-2026-88771-and-cve-2026-88779>) (Rapid7, 2026-10-19); [12th October – Threat Intelligence Report](<https://research.checkpoint.com/2026/12th-october-threat-intelligence-report/>) (Check Point Research, 2026-10-12); [Citrix warns admins to patch new NetScaler RCE flaw immediately](<https://www.bleepingcomputer.com/news/security/citrix-warns-admins-to-patch-new-netscaler-rce-flaw-immediately/>) (BleepingComputer, 2026-10-09) and 4 more
- Details: [CVE-2026-88779 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-88779>)

### CVE-2026-0300: Palo Alto Networks PAN-OS

Firewall or VPN (Palo Alto Networks). **Palo Alto Networks PAN-OS Out-of-bounds Write Vulnerability.** Palo Alto Networks PAN-OS contains an out-of-bounds write vulnerability in the User-ID Authentication Portal (aka Captive Portal) service that can allow an unauthenticated attacker to execute arbitrary code with root privileges on the PA-Series and VM-Series firewalls by sending specially crafted packets.

- Exploited: CISA listed it on 2026-05-06.
- Vendor advisory: [security.paloaltonetworks.com](<https://security.paloaltonetworks.com/CVE-2026-0300>)
- Reported by: [The Race Against the 3-Day Clock: How Rapid7 Helps Meet BOD 26-04 Compliance](<https://www.rapid7.com/blog/post/it-racing-the-three-day-clock-cisa-bod-26-04>) (Rapid7, 2026-11-04); [Threat Brief: Critical Vulnerabilities in PHP: CVE-2026-109618, CVE-2026-109619](<https://unit42.paloaltonetworks.com/cve-2026-109618-cve-2026-109619/>) (Unit 42, 2026-10-21); [Threat Brief: NetScaler Zero Days CVE-2026-88771 and CVE-2026-88772 Exploited in the Wild (Updated September 30)](<https://unit42.paloaltonetworks.com/netscaler-zero-days-exploited/>) (Unit 42, 2026-09-30); [August 2026 CVE Landscape](<https://www.recordedfuture.com/blog/august-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-09-08)
- Details: [CVE-2026-0300 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-0300>)

### CVE-2023-46805: Ivanti Connect Secure and Policy Secure

VPN or device management (Ivanti). **Ivanti Connect Secure and Policy Secure Authentication Bypass Vulnerability.** Ivanti Connect Secure (ICS, formerly known as Pulse Connect Secure) and Ivanti Policy Secure gateways contain an authentication bypass vulnerability in the web component that allows an attacker to access restricted resources by bypassing control checks. This vulnerability can be leveraged in conjunction with CVE-2024-21887, a command injection vulnerability.

- Exploited: CISA listed it on 2024-01-10. Used in ransomware attacks.
- Vendor advisory: [forums.ivanti.com](<https://forums.ivanti.com/s/article/KB-CVE-2023-46805-Authentication-Bypass-CVE-2024-21887-Command-Injection-for-Ivanti-Connect-Secure-and-Ivanti-Policy-Secure-Gateways?language=en_US>)
- Reported by: [Ivanti patches two more Connect Secure zero-days chained in attacks](<https://www.bleepingcomputer.com/news/security/ivanti-patches-two-more-connect-secure-zero-days-chained-in-attacks/>) (BleepingComputer, 2026-11-02); [BeyondTrust patches zero-day exploited in attacks since August](<https://www.bleepingcomputer.com/news/security/beyondtrust-patches-zero-day-exploited-in-attacks-since-august/>) (BleepingComputer, 2026-10-16); [ARMORY CASTLE Exploits BeyondTrust](<https://cloud.google.com/blog/topics/threat-intelligence/armory-castle-exploits-beyondtrust/>) (Google Threat Intelligence / Mandiant, 2026-10-15); [CISA warns admins to immediately fix Ivanti flaw exploited as zero-day](<https://www.bleepingcomputer.com/news/security/cisa-warns-admins-to-immediately-fix-ivanti-flaw-exploited-as-zero-day/>) (BleepingComputer, 2026-10-14); [Ivanti warns of Connect Secure zero-day exploited in attacks](<https://www.bleepingcomputer.com/news/security/ivanti-warns-of-connect-secure-zero-day-exploited-in-attacks/>) (BleepingComputer, 2026-10-13) and 2 more
- Details: [CVE-2023-46805 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2023-46805>)

### CVE-2024-21887: Ivanti Connect Secure and Policy Secure

VPN or device management (Ivanti). **Ivanti Connect Secure and Policy Secure Command Injection Vulnerability.** Ivanti Connect Secure (ICS, formerly known as Pulse Connect Secure) and Ivanti Policy Secure contain a command injection vulnerability in the web components of these products, which can allow an authenticated administrator to send crafted requests to execute code on affected appliances. This vulnerability can be leveraged in conjunction with CVE-2023-46805, an authenticated bypass issue.

- Exploited: CISA listed it on 2024-01-10. Used in ransomware attacks.
- Vendor advisory: [forums.ivanti.com](<https://forums.ivanti.com/s/article/KB-CVE-2023-46805-Authentication-Bypass-CVE-2024-21887-Command-Injection-for-Ivanti-Connect-Secure-and-Ivanti-Policy-Secure-Gateways?language=en_US>)
- Reported by: [Ivanti patches two more Connect Secure zero-days chained in attacks](<https://www.bleepingcomputer.com/news/security/ivanti-patches-two-more-connect-secure-zero-days-chained-in-attacks/>) (BleepingComputer, 2026-11-02); [BeyondTrust patches zero-day exploited in attacks since August](<https://www.bleepingcomputer.com/news/security/beyondtrust-patches-zero-day-exploited-in-attacks-since-august/>) (BleepingComputer, 2026-10-16); [ARMORY CASTLE Exploits BeyondTrust](<https://cloud.google.com/blog/topics/threat-intelligence/armory-castle-exploits-beyondtrust/>) (Google Threat Intelligence / Mandiant, 2026-10-15); [CISA warns admins to immediately fix Ivanti flaw exploited as zero-day](<https://www.bleepingcomputer.com/news/security/cisa-warns-admins-to-immediately-fix-ivanti-flaw-exploited-as-zero-day/>) (BleepingComputer, 2026-10-14); [Ivanti warns of Connect Secure zero-day exploited in attacks](<https://www.bleepingcomputer.com/news/security/ivanti-warns-of-connect-secure-zero-day-exploited-in-attacks/>) (BleepingComputer, 2026-10-13) and 2 more
- Details: [CVE-2024-21887 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2024-21887>)

### CVE-2026-88772: Citrix NetScaler

Remote access or file sharing (Citrix). **Citrix NetScaler Improper Restriction of Operations within the Bounds of a Memory Buffer Vulnerability.** Citrix NetScaler ADC and NetScaler Gateway contain an improper restriction of operations within the bounds of a memory buffer vulnerability that could allow for remote code execution or denial of service

- Exploited: CISA listed it on 2026-09-27.
- Vendor advisory: [community.citrix.com](<https://community.citrix.com/techzone-blogs/110_security-updates/netscaler-adc-and-netscaler-gateway-security-bulletin-for-cve-2026-88771-through-cve-2026-88778>), [support.citrix.com](<https://support.citrix.com/support-home/kbsearch/article?articleNumber=CTX697096>), [support.citrix.com](<https://support.citrix.com/external/article/CTX694799/steps-to-take-if-netscaler-adc-is-suspec.html>)
- Reported by: [InfraTrust report warns of exploited flaws in critical network infrastructure](<https://www.bleepingcomputer.com/news/security/infratrust-report-warns-of-exploited-flaws-in-critical-network-infrastructure/>) (BleepingComputer, 2026-10-28); [Threat Brief: Critical Vulnerabilities in PHP: CVE-2026-109618, CVE-2026-109619](<https://unit42.paloaltonetworks.com/cve-2026-109618-cve-2026-109619/>) (Unit 42, 2026-10-21); [Rapid7 Analysis: NetScaler intrusions chaining CVE-2026-88771 and CVE-2026-88779](<https://www.rapid7.com/blog/post/ra-netscaler-intrusions-chaining-cve-2026-88771-and-cve-2026-88779>) (Rapid7, 2026-10-19); [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13); [Citrix warns admins to patch new NetScaler RCE flaw immediately](<https://www.bleepingcomputer.com/news/security/citrix-warns-admins-to-patch-new-netscaler-rce-flaw-immediately/>) (BleepingComputer, 2026-10-09) and 8 more
- Details: [CVE-2026-88772 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-88772>)

### CVE-2023-4966: Citrix NetScaler ADC and NetScaler Gateway

Remote access or file sharing (Citrix). **Citrix NetScaler ADC and NetScaler Gateway Buffer Overflow Vulnerability.** Citrix NetScaler ADC and NetScaler Gateway contain a buffer overflow vulnerability that allows for sensitive information disclosure when configured as a Gateway (VPN virtual server, ICA Proxy, CVPN, RDP Proxy) or AAA virtual server.

- Exploited: CISA listed it on 2023-10-18. Used in ransomware attacks.
- Vendor advisory: [www.netscaler.com](<https://www.netscaler.com/blog/news/cve-2023-4966-critical-security-update-now-available-for-netscaler-adc-and-netscaler-gateway/>), [support.citrix.com](<https://support.citrix.com/article/CTX579459/netscaler-adc-and-netscaler-gateway-security-bulletin-for-cve20234966-and-cve20234967>)
- Reported by: [PHP2Shell Was Exploited Before the Patch](<https://www.sekoia.com/blog/php2shell-was-exploited-before-the-patch-expect-more-of-it>) (Sekoia, 2026-10-27); [BeyondTrust patches zero-day exploited in attacks since August](<https://www.bleepingcomputer.com/news/security/beyondtrust-patches-zero-day-exploited-in-attacks-since-august/>) (BleepingComputer, 2026-10-16)
- Details: [CVE-2023-4966 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2023-4966>)

### CVE-2026-1731: BeyondTrust Remote Support (RS) and Privileged Remote Access (PRA)

Remote support (BeyondTrust). **BeyondTrust Remote Support (RS) and Privileged Remote Access (PRA) OS Command Injection Vulnerability.** BeyondTrust Remote Support (RS) and Privileged Remote Access (PRA)contain an OS command injection vulnerability. Successful exploitation could allow an unauthenticated remote attacker to execute operating system commands in the context of the site user. Successful exploitation requires no authentication or user interaction and may lead to system compromise, including unauthorized access, data exfiltration, and service disruption.

- Exploited: CISA listed it on 2026-02-13. Used in ransomware attacks.
- Vendor advisory: [www.beyondtrust.com](<https://www.beyondtrust.com/trust-center/security-advisories/bt26-02>)
- Reported by: [Threat Brief: Critical Vulnerabilities in PHP: CVE-2026-109618, CVE-2026-109619](<https://unit42.paloaltonetworks.com/cve-2026-109618-cve-2026-109619/>) (Unit 42, 2026-10-21); [CVE-2026-102764: Critical BeyondTrust Remote Support Authentication Bypass Exploited in the Wild](<https://www.rapid7.com/blog/post/etr-cve-2026-102764-critical-beyondtrust-remote-support-authentication-bypass-exploited-in-the-wild>) (Rapid7, 2026-10-19); [BeyondTrust patches zero-day exploited in attacks since August](<https://www.bleepingcomputer.com/news/security/beyondtrust-patches-zero-day-exploited-in-attacks-since-august/>) (BleepingComputer, 2026-10-16); [Threat Brief: NetScaler Zero Days CVE-2026-88771 and CVE-2026-88772 Exploited in the Wild (Updated September 30)](<https://unit42.paloaltonetworks.com/netscaler-zero-days-exploited/>) (Unit 42, 2026-09-30); [Vulnerability Discovery and Exploitation Trends in the AI Era](<https://cloud.google.com/blog/topics/threat-intelligence/vulnerability-discovery-and-exploitation-trends-in-the-ai-era/>) (Google Threat Intelligence / Mandiant, 2026-09-30) and 1 more
- Details: [CVE-2026-1731 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-1731>)

---

Published by WatchmanHQ (https://watchmanhq.com). Free, best effort, provided as is, with no warranty of any kind.
Check the vendor's advisory before you change a device. CISA's catalog is public domain (CC0); these alerts are CC BY 4.0: credit WatchmanHQ.
