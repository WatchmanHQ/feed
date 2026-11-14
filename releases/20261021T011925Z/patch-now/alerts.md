# Patch now

WatchmanHQ patch-now alerts, release 20261021T011925Z, built 2026-10-21 01:19 UTC.

Flaws attackers are exploiting, in equipment small firms and their IT providers run. Each one is in CISA's Known Exploited Vulnerabilities catalog, so attackers are already using it, and a report we read names it. Newest first.

**If you run one of these:** Install the vendor's update, or its workaround until there is one, then follow the advisory's steps to look for signs of compromise: an update closes the hole, it does not remove an attacker who got in first. If the device gets no more updates (past its end of life), take it off the internet and replace it.

63 alerts: 12 newly exploited, 51 older. [CISA catalog](<https://www.cisa.gov/known-exploited-vulnerabilities-catalog>) version 2026.10.20, read 2026-10-21.

## Newly exploited

CISA added these to its catalog in the last 30 days.

### CVE-2026-102764: BeyondTrust Remote Support

Remote support (BeyondTrust). **BeyondTrust Remote Support Authentication Bypass by Spoofing Vulnerability.** BeyondTrust Remote Support contains an authentication bypass by spoofing vulnerability that could allow a remote attacker to perform file operations on the appliance.

- Exploited: CISA listed it on 2026-10-16.
- Vendor advisory: [www.beyondtrust.com](<https://www.beyondtrust.com/trust-center/security-advisories/bt26-05>)
- Reported by: [CVE-2026-102764: Critical BeyondTrust Remote Support Authentication Bypass Exploited in the Wild](<https://www.rapid7.com/blog/post/etr-cve-2026-102764-critical-beyondtrust-remote-support-authentication-bypass-exploited-in-the-wild>) (Rapid7, 2026-10-19); [19th October – Threat Intelligence Report](<https://research.checkpoint.com/2026/19th-october-threat-intelligence-report/>) (Check Point Research, 2026-10-19); [BeyondTrust patches zero-day exploited in attacks since August](<https://www.bleepingcomputer.com/news/security/beyondtrust-patches-zero-day-exploited-in-attacks-since-august/>) (BleepingComputer, 2026-10-16); [ARMORY CASTLE Exploits BeyondTrust](<https://cloud.google.com/blog/topics/threat-intelligence/armory-castle-exploits-beyondtrust/>) (Google Threat Intelligence / Mandiant, 2026-10-15)
- Details: [CVE-2026-102764 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-102764>)

### CVE-2026-104935: Ivanti Connect Secure

VPN or device management (Ivanti). **Ivanti Connect Secure Authentication Bypass by Spoofing Vulnerability.** Ivanti Connect Secure contains an authentication bypass by spoofing vulnerability that allows a remote unauthenticated attacker to execute arbitrary commands.

- Exploited: CISA listed it on 2026-10-13.
- Reported by: [19th October – Threat Intelligence Report](<https://research.checkpoint.com/2026/19th-october-threat-intelligence-report/>) (Check Point Research, 2026-10-19); [The Q3 Vulnerability Pulse: Discovery ≠ Exploitation](<https://blog.talosintelligence.com/the-q3-vulnerability-pulse-discovery-exploitation/>) (Cisco Talos, 2026-10-15); [CISA warns admins to immediately fix Ivanti flaw exploited as zero-day](<https://www.bleepingcomputer.com/news/security/cisa-warns-admins-to-immediately-fix-ivanti-flaw-exploited-as-zero-day/>) (BleepingComputer, 2026-10-14); [A Series of Unauthenticated Events: Chained Exploitation of Ivanti Connect Secure Zero-Days](<https://www.volexity.com/blog/2026/10/13/a-series-of-unauthenticated-events-chained-exploitation-of-ivanti-connect-secure-zero-days/>) (Volexity, 2026-10-13); [Ivanti Connect Secure zero-day exploited in the wild (CVE-2026-104935)](<https://www.rapid7.com/blog/post/etr-ivanti-connect-secure-zero-day-exploited-in-the-wild-cve-2026-104935>) (Rapid7, 2026-10-13) and 1 more
- Details: [CVE-2026-104935 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-104935>)

### CVE-2026-88771: Citrix NetScaler

Remote access or file sharing (Citrix). **Citrix NetScaler Improper Input Validation Vulnerability.** Citrix NetScaler ADC and NetScaler Gateway contain an improper input validation vulnerability that could allow an unauthenticated attacker to execute arbitrary commands.

- Exploited: CISA listed it on 2026-09-27.
- Vendor advisory: [community.citrix.com](<https://community.citrix.com/techzone-blogs/110_security-updates/netscaler-adc-and-netscaler-gateway-security-bulletin-for-cve-2026-88771-through-cve-2026-88778>), [support.citrix.com](<https://support.citrix.com/support-home/kbsearch/article?articleNumber=CTX697096>), [support.citrix.com](<https://support.citrix.com/external/article/CTX694799/steps-to-take-if-netscaler-adc-is-suspec.html>)
- Reported by: [Rapid7 Analysis: NetScaler intrusions chaining CVE-2026-88771 and CVE-2026-88779](<https://www.rapid7.com/blog/post/ra-netscaler-intrusions-chaining-cve-2026-88771-and-cve-2026-88779>) (Rapid7, 2026-10-19); [CVE-2026-88771: Inside the Exploitation of a Critical NetScaler RCE Vulnerability](<https://www.zscaler.com/blogs/security-research/cve-2026-88771-inside-exploitation-critical-netscaler-rce-vulnerability>) (Zscaler ThreatLabz, 2026-10-16); [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13); [Citrix warns admins to patch new NetScaler RCE flaw immediately](<https://www.bleepingcomputer.com/news/security/citrix-warns-admins-to-patch-new-netscaler-rce-flaw-immediately/>) (BleepingComputer, 2026-10-09); [Blinder Tunnel Campaign Targets Iraqi Infrastructure](<https://unit42.paloaltonetworks.com/blinder-tunnel-targets-critical-infrastructure/>) (Unit 42, 2026-10-06) and 8 more
- Details: [CVE-2026-88771 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-88771>)

### CVE-2026-88772: Citrix NetScaler

Remote access or file sharing (Citrix). **Citrix NetScaler Improper Restriction of Operations within the Bounds of a Memory Buffer Vulnerability.** Citrix NetScaler ADC and NetScaler Gateway contain an improper restriction of operations within the bounds of a memory buffer vulnerability that could allow for remote code execution or denial of service

- Exploited: CISA listed it on 2026-09-27.
- Vendor advisory: [community.citrix.com](<https://community.citrix.com/techzone-blogs/110_security-updates/netscaler-adc-and-netscaler-gateway-security-bulletin-for-cve-2026-88771-through-cve-2026-88778>), [support.citrix.com](<https://support.citrix.com/support-home/kbsearch/article?articleNumber=CTX697096>), [support.citrix.com](<https://support.citrix.com/external/article/CTX694799/steps-to-take-if-netscaler-adc-is-suspec.html>)
- Reported by: [Rapid7 Analysis: NetScaler intrusions chaining CVE-2026-88771 and CVE-2026-88779](<https://www.rapid7.com/blog/post/ra-netscaler-intrusions-chaining-cve-2026-88771-and-cve-2026-88779>) (Rapid7, 2026-10-19); [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13); [Citrix warns admins to patch new NetScaler RCE flaw immediately](<https://www.bleepingcomputer.com/news/security/citrix-warns-admins-to-patch-new-netscaler-rce-flaw-immediately/>) (BleepingComputer, 2026-10-09); [Blinder Tunnel Campaign Targets Iraqi Infrastructure](<https://unit42.paloaltonetworks.com/blinder-tunnel-targets-critical-infrastructure/>) (Unit 42, 2026-10-06); [Q3 2026 Attack Techniques Trend Report](<https://asec.ahnlab.com/en/95733/>) (AhnLab ASEC, 2026-10-06) and 6 more
- Details: [CVE-2026-88772 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-88772>)

### CVE-2026-88779: Citrix NetScaler

Remote access or file sharing (Citrix). **Citrix NetScaler Improper Restriction of Operations within the Bounds of a Memory Buffer Vulnerability.** Citrix NetScaler ADC (formerly Citrix ADC) and Citrix NetScaler Gateway (formerly Citrix Gateway) contain an improper restriction of operations within the bounds of a memory buffer vulnerability that could allow for a denial of service.

- Exploited: CISA listed it on 2026-10-04.
- Vendor advisory: [support.citrix.com](<https://support.citrix.com/support-home/kbsearch/article?articleNumber=CTX697174>), [community.citrix.com](<https://community.citrix.com/techzone-blogs/110_security-updates/understanding-and-addressing-cve-2026-88779-in-citrix-netscaler-adc-and-citrix-netscaler-gateway/>)
- Reported by: [Rapid7 Analysis: NetScaler intrusions chaining CVE-2026-88771 and CVE-2026-88779](<https://www.rapid7.com/blog/post/ra-netscaler-intrusions-chaining-cve-2026-88771-and-cve-2026-88779>) (Rapid7, 2026-10-19); [12th October – Threat Intelligence Report](<https://research.checkpoint.com/2026/12th-october-threat-intelligence-report/>) (Check Point Research, 2026-10-12); [Citrix warns admins to patch new NetScaler RCE flaw immediately](<https://www.bleepingcomputer.com/news/security/citrix-warns-admins-to-patch-new-netscaler-rce-flaw-immediately/>) (BleepingComputer, 2026-10-09); [Making sure the checks get printed](<https://blog.talosintelligence.com/making-sure-the-checks-get-printed/>) (Cisco Talos, 2026-10-08); [Citrix NetScaler vulnerability (CVE-2026-88779) in active exploitation](<https://www.sophos.com/en-us/blog/citrix-netscaler-vulnerability-cve-2026-88779-in-active-exploitation>) (Sophos Threat Research, 2026-10-05) and 1 more
- Details: [CVE-2026-88779 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-88779>)

### CVE-2025-61624: Fortinet Multiple Products

Firewall, VPN or other appliance (Fortinet). **Fortinet Multiple Products Path Traversal Vulnerability.** FortiOS, FortiPAM, FortiProxy, and FortiSwitchManager contain a path traversal vulnerability that may allow an authenticated attacker with admin profile and at least read-write permissions to write or delete arbitrary files via specific CLI commands.

- Exploited: CISA listed it on 2026-10-16.
- Vendor advisory: [fortiguard.fortinet.com](<https://fortiguard.fortinet.com/psirt/FG-IR-26-122>)
- Reported by: [Unit 42 Uncovers PEERSTITCH, a Stealthy FortiGate Implant](<https://unit42.paloaltonetworks.com/fortimanager-cve-2024-47575-peerstitch-malware/>) (Unit 42, 2026-10-14)
- Details: [CVE-2025-61624 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2025-61624>)

### CVE-2026-0322: Palo Alto Networks PAN-OS

Firewall or VPN (Palo Alto Networks). **Palo Alto Networks PAN-OS Code Injection Vulnerability.** Palo Alto Networks PAN-OS contains a code injection vulnerability that could allow an authenticated attacker with network access to execute arbitrary code with root privileges on the firewall.

- Exploited: CISA listed it on 2026-10-14.
- Vendor advisory: [security.paloaltonetworks.com](<https://security.paloaltonetworks.com/CVE-2026-0322>)
- Reported by: [Palo Alto Networks warns of PAN-OS RCE flaw exploited in attacks](<https://www.bleepingcomputer.com/news/security/palo-alto-networks-warns-of-pan-os-rce-flaw-exploited-in-attacks/>) (BleepingComputer, 2026-10-14)
- Details: [CVE-2026-0322 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-0322>)

### CVE-2026-104286: Fortinet FortiMail

Firewall, VPN or other appliance (Fortinet). **Fortinet FortiMail Path Traversal Vulnerability.** Fortinet FortiMail contains a path traversal and an improper neutralization of NULL byte or NULL character vulnerability that may allow an unauthenticated attacker to write arbitrary files on the underlying system via crafted HTTP or HTTPS requests.

- Exploited: CISA listed it on 2026-10-01.
- Vendor advisory: [fortiguard.fortinet.com](<https://fortiguard.fortinet.com/psirt/FG-IR-26-175>)
- Reported by: [Microsoft October 2026 Patch Tuesday fixes 1,411 flaws, 3 zero-days](<https://www.bleepingcomputer.com/news/microsoft/microsoft-october-2026-patch-tuesday-fixes-1-411-flaws-3-zero-days/>) (BleepingComputer, 2026-10-13)
- Details: [CVE-2026-104286 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-104286>)

### CVE-2026-67279: MikroTik RouterOS

Router (MikroTik). **Mikrotik RouterOS Improper Enforcement of Behavioral Workflow Vulnerability.** Mikrotik RouterOS contains an improper enforcement of behavioral workflow vulnerability that could allow an unauthenticated client to open a session channel and send an exec request. This vulnerability can be chained to achieve unauthenticated exploitation of CVE-2026-86060.

- Exploited: CISA listed it on 2026-09-25.
- Vendor advisory: [mikrotik.com](<https://mikrotik.com/supportsec/september-2026-vulnerability/?utm_source=chatgpt.com>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13)
- Details: [CVE-2026-67279 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-67279>)

### CVE-2026-7273: Zyxel GS1900 Series Switches

Firewall, router or storage (Zyxel). **Zyxel GS1900 Series Switches Stack-Based Buffer Overflow Vulnerability.** Zyxel GS1900 series switches contain a stack-based buffer overflow vulnerability in the CGI program which could allow a LAN-based, unauthenticated attacker to exploit the flaw and potentially execute OS commands via a crafted HTTP request.

- Exploited: CISA listed it on 2026-09-21.
- Vendor advisory: [www.zyxel.com](<https://www.zyxel.com/global/en/support/security-advisories/zyxel-security-advisory-for-stack-based-buffer-overflow-vulnerability-in-gs1900-series-switches-06-16-2026>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13)
- Details: [CVE-2026-7273 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-7273>)

### CVE-2026-85102: Check Point Multiple Products

Firewall, VPN or other appliance (Check Point). **Check Point Multiple Products Improper Certificate Validation Vulnerability.** Check Point Security Gateway and Check Point Spark Firewall using Site to Site VPN or Remote Access VPN contain an improper certificate validation vulnerability which could allow an unauthenticated remote attacker to execute arbitrary code on the Gateway.

- Exploited: CISA listed it on 2026-09-22.
- Vendor advisory: [support.checkpoint.com](<https://support.checkpoint.com/results/sk/sk1000117>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13); [Q3 2026 Vulnerability Trend Report](<https://asec.ahnlab.com/en/95741/>) (AhnLab ASEC, 2026-10-06); [28th September – Threat Intelligence Report](<https://research.checkpoint.com/2026/28th-september-threat-intelligence-report/>) (Check Point Research, 2026-09-28)
- Details: [CVE-2026-85102 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-85102>)

### CVE-2026-93616: Check Point Multiple Products

Firewall, VPN or other appliance (Check Point). **Check Point Multiple Products Path Traversal Vulnerability.** Check Point Security Management Server, Multi-Domain Security Management Server, Log Server, Multi-Domain Log Server, and SmartEvent contain a path traversal vulnerability that allows an unauthenticated attacker to upload and execute arbitrary scripts.

- Exploited: CISA listed it on 2026-09-22.
- Vendor advisory: [support.checkpoint.com](<https://support.checkpoint.com/results/sk/sk1000171/>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13); [28th September – Threat Intelligence Report](<https://research.checkpoint.com/2026/28th-september-threat-intelligence-report/>) (Check Point Research, 2026-09-28)
- Details: [CVE-2026-93616 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-93616>)

## Older flaws, exploited again

CISA listed these earlier, and a report from the last 30 days says attackers use them now: devices never updated, or past their end of life, are the targets.

### CVE-2024-1708: ConnectWise ScreenConnect

Remote support or IT management (ConnectWise). **ConnectWise ScreenConnect Path Traversal Vulnerability.** ConnectWise ScreenConnect contains a path traversal vulnerability which could allow an attacker to execute remote code or directly impact confidential data and critical systems.

- Exploited: CISA listed it on 2026-04-28. Used in ransomware attacks.
- Vendor advisory: [www.connectwise.com](<https://www.connectwise.com/company/trust/security-bulletins/connectwise-screenconnect-23.9.8>)
- Reported by: [Identity Posture Assessment for Microsoft 365 \| Managed ISPM](<https://www.huntress.com/blog/identity-posture-assessment-microsoft-365>) (Huntress, 2026-10-20); [CMMC Level 2 Non-Negotiable Requirements Explained \| Huntress](<https://www.huntress.com/blog/cmmc-level-2-non-negotiable-requirements>) (Huntress, 2026-10-12)
- Details: [CVE-2024-1708 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2024-1708>)

### CVE-2024-1709: ConnectWise ScreenConnect

Remote support or IT management (ConnectWise). **ConnectWise ScreenConnect Authentication Bypass Vulnerability.** ConnectWise ScreenConnect contains an authentication bypass vulnerability that allows an attacker with network access to the management interface to create a new, administrator-level account on affected devices.

- Exploited: CISA listed it on 2024-02-22. Used in ransomware attacks.
- Vendor advisory: [www.connectwise.com](<https://www.connectwise.com/company/trust/security-bulletins/connectwise-screenconnect-23.9.8>)
- Reported by: [Identity Posture Assessment for Microsoft 365 \| Managed ISPM](<https://www.huntress.com/blog/identity-posture-assessment-microsoft-365>) (Huntress, 2026-10-20); [CMMC Level 2 Non-Negotiable Requirements Explained \| Huntress](<https://www.huntress.com/blog/cmmc-level-2-non-negotiable-requirements>) (Huntress, 2026-10-12)
- Details: [CVE-2024-1709 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2024-1709>)

### CVE-2026-1731: BeyondTrust Remote Support (RS) and Privileged Remote Access (PRA)

Remote support (BeyondTrust). **BeyondTrust Remote Support (RS) and Privileged Remote Access (PRA) OS Command Injection Vulnerability.** BeyondTrust Remote Support (RS) and Privileged Remote Access (PRA)contain an OS command injection vulnerability. Successful exploitation could allow an unauthenticated remote attacker to execute operating system commands in the context of the site user. Successful exploitation requires no authentication or user interaction and may lead to system compromise, including unauthorized access, data exfiltration, and service disruption.

- Exploited: CISA listed it on 2026-02-13. Used in ransomware attacks.
- Vendor advisory: [www.beyondtrust.com](<https://www.beyondtrust.com/trust-center/security-advisories/bt26-02>)
- Reported by: [CVE-2026-102764: Critical BeyondTrust Remote Support Authentication Bypass Exploited in the Wild](<https://www.rapid7.com/blog/post/etr-cve-2026-102764-critical-beyondtrust-remote-support-authentication-bypass-exploited-in-the-wild>) (Rapid7, 2026-10-19); [BeyondTrust patches zero-day exploited in attacks since August](<https://www.bleepingcomputer.com/news/security/beyondtrust-patches-zero-day-exploited-in-attacks-since-august/>) (BleepingComputer, 2026-10-16); [Threat Brief: NetScaler Zero Days CVE-2026-88771 and CVE-2026-88772 Exploited in the Wild (Updated September 30)](<https://unit42.paloaltonetworks.com/netscaler-zero-days-exploited/>) (Unit 42, 2026-09-30); [Vulnerability Discovery and Exploitation Trends in the AI Era](<https://cloud.google.com/blog/topics/threat-intelligence/vulnerability-discovery-and-exploitation-trends-in-the-ai-era/>) (Google Threat Intelligence / Mandiant, 2026-09-30); [Exploits and vulnerabilities in Q2 2026](<https://securelist.com/vulnerabilities-and-exploits-in-q2-2026/121091/>) (Securelist, 2026-08-26)
- Details: [CVE-2026-1731 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-1731>)

### CVE-2023-3519: Citrix NetScaler ADC and NetScaler Gateway

Remote access or file sharing (Citrix). **Citrix NetScaler ADC and NetScaler Gateway Code Injection Vulnerability.** Citrix NetScaler ADC and NetScaler Gateway contains a code injection vulnerability that allows for unauthenticated remote code execution.

- Exploited: CISA listed it on 2023-07-19. Used in ransomware attacks.
- Vendor advisory: [support.citrix.com](<https://support.citrix.com/article/CTX561482/citrix-adc-and-citrix-gateway-security-bulletin-for-cve20233519-cve20233466-cve20233467>)
- Reported by: [CVE-2026-88771: Inside the Exploitation of a Critical NetScaler RCE Vulnerability](<https://www.zscaler.com/blogs/security-research/cve-2026-88771-inside-exploitation-critical-netscaler-rce-vulnerability>) (Zscaler ThreatLabz, 2026-10-16)
- Details: [CVE-2023-3519 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2023-3519>)

### CVE-2023-46805: Ivanti Connect Secure and Policy Secure

VPN or device management (Ivanti). **Ivanti Connect Secure and Policy Secure Authentication Bypass Vulnerability.** Ivanti Connect Secure (ICS, formerly known as Pulse Connect Secure) and Ivanti Policy Secure gateways contain an authentication bypass vulnerability in the web component that allows an attacker to access restricted resources by bypassing control checks. This vulnerability can be leveraged in conjunction with CVE-2024-21887, a command injection vulnerability.

- Exploited: CISA listed it on 2024-01-10. Used in ransomware attacks.
- Vendor advisory: [forums.ivanti.com](<https://forums.ivanti.com/s/article/KB-CVE-2023-46805-Authentication-Bypass-CVE-2024-21887-Command-Injection-for-Ivanti-Connect-Secure-and-Ivanti-Policy-Secure-Gateways?language=en_US>)
- Reported by: [BeyondTrust patches zero-day exploited in attacks since August](<https://www.bleepingcomputer.com/news/security/beyondtrust-patches-zero-day-exploited-in-attacks-since-august/>) (BleepingComputer, 2026-10-16); [ARMORY CASTLE Exploits BeyondTrust](<https://cloud.google.com/blog/topics/threat-intelligence/armory-castle-exploits-beyondtrust/>) (Google Threat Intelligence / Mandiant, 2026-10-15); [CISA warns admins to immediately fix Ivanti flaw exploited as zero-day](<https://www.bleepingcomputer.com/news/security/cisa-warns-admins-to-immediately-fix-ivanti-flaw-exploited-as-zero-day/>) (BleepingComputer, 2026-10-14); [Ivanti warns of Connect Secure zero-day exploited in attacks](<https://www.bleepingcomputer.com/news/security/ivanti-warns-of-connect-secure-zero-day-exploited-in-attacks/>) (BleepingComputer, 2026-10-13); [ClingSTUN Linux Backdoor Abuses Public STUN Infrastructure](<https://feeds.fortinet.com/~/971007764/0/fortinet/blog/threat-research~ClingSTUN-Linux-Backdoor-Abuses-Public-STUN-Infrastructure>) (Fortinet Threat Research, 2026-10-05) and 1 more
- Details: [CVE-2023-46805 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2023-46805>)

### CVE-2023-4966: Citrix NetScaler ADC and NetScaler Gateway

Remote access or file sharing (Citrix). **Citrix NetScaler ADC and NetScaler Gateway Buffer Overflow Vulnerability.** Citrix NetScaler ADC and NetScaler Gateway contain a buffer overflow vulnerability that allows for sensitive information disclosure when configured as a Gateway (VPN virtual server, ICA Proxy, CVPN, RDP Proxy) or AAA virtual server.

- Exploited: CISA listed it on 2023-10-18. Used in ransomware attacks.
- Vendor advisory: [www.netscaler.com](<https://www.netscaler.com/blog/news/cve-2023-4966-critical-security-update-now-available-for-netscaler-adc-and-netscaler-gateway/>), [support.citrix.com](<https://support.citrix.com/article/CTX579459/netscaler-adc-and-netscaler-gateway-security-bulletin-for-cve20234966-and-cve20234967>)
- Reported by: [BeyondTrust patches zero-day exploited in attacks since August](<https://www.bleepingcomputer.com/news/security/beyondtrust-patches-zero-day-exploited-in-attacks-since-august/>) (BleepingComputer, 2026-10-16)
- Details: [CVE-2023-4966 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2023-4966>)

### CVE-2024-12356: BeyondTrust Privileged Remote Access (PRA) and Remote Support (RS)

Remote support (BeyondTrust). **BeyondTrust Privileged Remote Access (PRA) and Remote Support (RS) Command Injection Vulnerability.** BeyondTrust Privileged Remote Access (PRA) and Remote Support (RS) contain a command injection vulnerability, which can allow an unauthenticated attacker to inject commands that are run as a site user.

- Exploited: CISA listed it on 2024-12-19.
- Vendor advisory: [www.beyondtrust.com](<https://www.beyondtrust.com/trust-center/security-advisories/bt24-10>)
- Reported by: [BeyondTrust patches zero-day exploited in attacks since August](<https://www.bleepingcomputer.com/news/security/beyondtrust-patches-zero-day-exploited-in-attacks-since-august/>) (BleepingComputer, 2026-10-16); [Exploits and vulnerabilities in Q2 2026](<https://securelist.com/vulnerabilities-and-exploits-in-q2-2026/121091/>) (Securelist, 2026-08-26)
- Details: [CVE-2024-12356 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2024-12356>)

### CVE-2024-12686: BeyondTrust Privileged Remote Access (PRA) and Remote Support (RS)

Remote support (BeyondTrust). **BeyondTrust Privileged Remote Access (PRA) and Remote Support (RS) OS Command Injection Vulnerability.** BeyondTrust Privileged Remote Access (PRA) and Remote Support (RS) contain an OS command injection vulnerability that can be exploited by an attacker with existing administrative privileges to upload a malicious file. Successful exploitation of this vulnerability can allow a remote attacker to execute underlying operating system commands within the context of the site user.

- Exploited: CISA listed it on 2025-01-13.
- Vendor advisory: [www.beyondtrust.com](<https://www.beyondtrust.com/trust-center/security-advisories/bt24-11>)
- Reported by: [BeyondTrust patches zero-day exploited in attacks since August](<https://www.bleepingcomputer.com/news/security/beyondtrust-patches-zero-day-exploited-in-attacks-since-august/>) (BleepingComputer, 2026-10-16)
- Details: [CVE-2024-12686 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2024-12686>)

### CVE-2024-21887: Ivanti Connect Secure and Policy Secure

VPN or device management (Ivanti). **Ivanti Connect Secure and Policy Secure Command Injection Vulnerability.** Ivanti Connect Secure (ICS, formerly known as Pulse Connect Secure) and Ivanti Policy Secure contain a command injection vulnerability in the web components of these products, which can allow an authenticated administrator to send crafted requests to execute code on affected appliances. This vulnerability can be leveraged in conjunction with CVE-2023-46805, an authenticated bypass issue.

- Exploited: CISA listed it on 2024-01-10. Used in ransomware attacks.
- Vendor advisory: [forums.ivanti.com](<https://forums.ivanti.com/s/article/KB-CVE-2023-46805-Authentication-Bypass-CVE-2024-21887-Command-Injection-for-Ivanti-Connect-Secure-and-Ivanti-Policy-Secure-Gateways?language=en_US>)
- Reported by: [BeyondTrust patches zero-day exploited in attacks since August](<https://www.bleepingcomputer.com/news/security/beyondtrust-patches-zero-day-exploited-in-attacks-since-august/>) (BleepingComputer, 2026-10-16); [ARMORY CASTLE Exploits BeyondTrust](<https://cloud.google.com/blog/topics/threat-intelligence/armory-castle-exploits-beyondtrust/>) (Google Threat Intelligence / Mandiant, 2026-10-15); [CISA warns admins to immediately fix Ivanti flaw exploited as zero-day](<https://www.bleepingcomputer.com/news/security/cisa-warns-admins-to-immediately-fix-ivanti-flaw-exploited-as-zero-day/>) (BleepingComputer, 2026-10-14); [Ivanti warns of Connect Secure zero-day exploited in attacks](<https://www.bleepingcomputer.com/news/security/ivanti-warns-of-connect-secure-zero-day-exploited-in-attacks/>) (BleepingComputer, 2026-10-13); [ClingSTUN Linux Backdoor Abuses Public STUN Infrastructure](<https://feeds.fortinet.com/~/971007764/0/fortinet/blog/threat-research~ClingSTUN-Linux-Backdoor-Abuses-Public-STUN-Infrastructure>) (Fortinet Threat Research, 2026-10-05) and 1 more
- Details: [CVE-2024-21887 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2024-21887>)

### CVE-2025-0282: Ivanti Connect Secure, Policy Secure, and ZTA Gateways

VPN or device management (Ivanti). **Ivanti Connect Secure, Policy Secure, and ZTA Gateways Stack-Based Buffer Overflow Vulnerability.** Ivanti Connect Secure, Policy Secure, and ZTA Gateways contain a stack-based buffer overflow which can lead to unauthenticated remote code execution.

- Exploited: CISA listed it on 2025-01-08. Used in ransomware attacks.
- Vendor advisory: [forums.ivanti.com](<https://forums.ivanti.com/s/article/Security-Advisory-Ivanti-Connect-Secure-Policy-Secure-ZTA-Gateways-CVE-2025-0282-CVE-2025-0283>)
- Reported by: [BeyondTrust patches zero-day exploited in attacks since August](<https://www.bleepingcomputer.com/news/security/beyondtrust-patches-zero-day-exploited-in-attacks-since-august/>) (BleepingComputer, 2026-10-16); [CISA warns admins to immediately fix Ivanti flaw exploited as zero-day](<https://www.bleepingcomputer.com/news/security/cisa-warns-admins-to-immediately-fix-ivanti-flaw-exploited-as-zero-day/>) (BleepingComputer, 2026-10-14); [Ivanti warns of Connect Secure zero-day exploited in attacks](<https://www.bleepingcomputer.com/news/security/ivanti-warns-of-connect-secure-zero-day-exploited-in-attacks/>) (BleepingComputer, 2026-10-13)
- Details: [CVE-2025-0282 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2025-0282>)

### CVE-2026-20131: Cisco Secure Firewall Management Center (FMC)

Firewall, VPN or office router (Cisco). **Cisco Secure Firewall Management Center (FMC) Software and Cisco Security Cloud Control (SCC) Firewall Management Deserialization of Untrusted Data Vulnerability.** Cisco Secure Firewall Management Center (FMC) Software and Cisco Security Cloud Control (SCC) Firewall Management contain a deserialization of untrusted data vulnerability in the web-based management interface that could allow an unauthenticated, remote attacker to execute arbitrary Java code as root on an affected device.

- Exploited: CISA listed it on 2026-03-19. Used in ransomware attacks.
- Vendor advisory: [sec.cloudapps.cisco.com](<https://sec.cloudapps.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-fmc-rce-NKhnULJh>)
- Reported by: [CVE-2026-88771: Inside the Exploitation of a Critical NetScaler RCE Vulnerability](<https://www.zscaler.com/blogs/security-research/cve-2026-88771-inside-exploitation-critical-netscaler-rce-vulnerability>) (Zscaler ThreatLabz, 2026-10-16)
- Details: [CVE-2026-20131 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-20131>)

### CVE-2024-3272: D-Link Multiple NAS Devices

Router or network device (D-Link). **D-Link Multiple NAS Devices Use of Hard-Coded Credentials Vulnerability.** D-Link DNS-320L, DNS-325, DNS-327L, and DNS-340L contains a hard-coded credential that allows an attacker to conduct authenticated command injection, leading to remote, unauthorized code execution.

- Exploited: CISA listed it on 2024-04-11.
- Vendor advisory: [supportannouncement.us.dlink.com](<https://supportannouncement.us.dlink.com/security/publication.aspx?name=SAP10383>)
- Reported by: [Hackers hijack D-Link, Ubiquiti devices to resell your stolen bandwidth](<https://www.bleepingcomputer.com/news/security/hackers-hijack-d-link-ubiquiti-devices-to-resell-your-stolen-bandwidth/>) (BleepingComputer, 2026-10-15)
- Details: [CVE-2024-3272 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2024-3272>)

### CVE-2024-3273: D-Link Multiple NAS Devices

Router or network device (D-Link). **D-Link Multiple NAS Devices Command Injection Vulnerability.** D-Link DNS-320L, DNS-325, DNS-327L, and DNS-340L contain a command injection vulnerability. When combined with CVE-2024-3272, this can lead to remote, unauthorized code execution.

- Exploited: CISA listed it on 2024-04-11.
- Vendor advisory: [supportannouncement.us.dlink.com](<https://supportannouncement.us.dlink.com/security/publication.aspx?name=SAP10383>)
- Reported by: [Hackers hijack D-Link, Ubiquiti devices to resell your stolen bandwidth](<https://www.bleepingcomputer.com/news/security/hackers-hijack-d-link-ubiquiti-devices-to-resell-your-stolen-bandwidth/>) (BleepingComputer, 2026-10-15)
- Details: [CVE-2024-3273 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2024-3273>)

### CVE-2024-21893: Ivanti Connect Secure, Policy Secure, and Neurons

VPN or device management (Ivanti). **Ivanti Connect Secure, Policy Secure, and Neurons Server-Side Request Forgery (SSRF) Vulnerability.** Ivanti Connect Secure (ICS, formerly known as Pulse Connect Secure), Ivanti Policy Secure, and Ivanti Neurons contain a server-side request forgery (SSRF) vulnerability in the SAML component that allows an attacker to access certain restricted resources without authentication.

- Exploited: CISA listed it on 2024-01-31. Used in ransomware attacks.
- Vendor advisory: [forums.ivanti.com](<https://forums.ivanti.com/s/article/KB-CVE-2023-46805-Authentication-Bypass-CVE-2024-21887-Command-Injection-for-Ivanti-Connect-Secure-and-Ivanti-Policy-Secure-Gateways?language=en_US>)
- Reported by: [CISA warns admins to immediately fix Ivanti flaw exploited as zero-day](<https://www.bleepingcomputer.com/news/security/cisa-warns-admins-to-immediately-fix-ivanti-flaw-exploited-as-zero-day/>) (BleepingComputer, 2026-10-14); [Ivanti warns of Connect Secure zero-day exploited in attacks](<https://www.bleepingcomputer.com/news/security/ivanti-warns-of-connect-secure-zero-day-exploited-in-attacks/>) (BleepingComputer, 2026-10-13)
- Details: [CVE-2024-21893 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2024-21893>)

### CVE-2024-47575: Fortinet FortiManager

Firewall, VPN or other appliance (Fortinet). **Fortinet FortiManager Missing Authentication Vulnerability.** Fortinet FortiManager contains a missing authentication vulnerability in the fgfmd daemon that allows a remote, unauthenticated attacker to execute arbitrary code or commands via specially crafted requests.

- Exploited: CISA listed it on 2024-10-23.
- Vendor advisory: [fortiguard.fortinet.com](<https://fortiguard.fortinet.com/psirt/FG-IR-24-423>)
- Reported by: [Unit 42 Uncovers PEERSTITCH, a Stealthy FortiGate Implant](<https://unit42.paloaltonetworks.com/fortimanager-cve-2024-47575-peerstitch-malware/>) (Unit 42, 2026-10-14)
- Details: [CVE-2024-47575 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2024-47575>)

### CVE-2025-22457: Ivanti Connect Secure, Policy Secure, and ZTA Gateways

VPN or device management (Ivanti). **Ivanti Connect Secure, Policy Secure, and ZTA Gateways Stack-Based Buffer Overflow Vulnerability.** Ivanti Connect Secure, Policy Secure, and ZTA Gateways contains a stack-based buffer overflow vulnerability that allows a remote unauthenticated attacker to achieve remote code execution.

- Exploited: CISA listed it on 2025-04-04. Used in ransomware attacks.
- Vendor advisory: [forums.ivanti.com](<https://forums.ivanti.com/s/article/April-Security-Advisory-Ivanti-Connect-Secure-Policy-Secure-ZTA-Gateways-CVE-2025-22457>)
- Reported by: [CISA warns admins to immediately fix Ivanti flaw exploited as zero-day](<https://www.bleepingcomputer.com/news/security/cisa-warns-admins-to-immediately-fix-ivanti-flaw-exploited-as-zero-day/>) (BleepingComputer, 2026-10-14); [Ivanti warns of Connect Secure zero-day exploited in attacks](<https://www.bleepingcomputer.com/news/security/ivanti-warns-of-connect-secure-zero-day-exploited-in-attacks/>) (BleepingComputer, 2026-10-13)
- Details: [CVE-2025-22457 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2025-22457>)

### CVE-2025-25257: Fortinet FortiWeb

Firewall, VPN or other appliance (Fortinet). **Fortinet FortiWeb SQL Injection Vulnerability.** Fortinet FortiWeb contains a SQL injection vulnerability that may allow an unauthenticated attacker to execute unauthorized SQL code or commands via crafted HTTP or HTTPs requests.

- Exploited: CISA listed it on 2025-07-18.
- Vendor advisory: [fortiguard.fortinet.com](<https://fortiguard.fortinet.com/psirt/FG-IR-25-151>)
- Reported by: [Break the silence: Kazakhstan-nexus UAT-6275 targets CIS government organizations](<https://blog.talosintelligence.com/break-the-silence-kazakhstan-nexus-uat-6275-targets-cis-government-organizations/>) (Cisco Talos, 2026-10-14)
- Details: [CVE-2025-25257 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2025-25257>)

### CVE-2025-59718: Fortinet Multiple Products

Firewall, VPN or other appliance (Fortinet). **Fortinet Multiple Products Improper Verification of Cryptographic Signature Vulnerability.** Fortinet FortiOS, FortiSwitchMaster, FortiProxy, and FortiWeb contain an improper verification of cryptographic signature vulnerability that may allow an unauthenticated attacker to bypass the FortiCloud SSO login authentication via a crafted SAML message. Please be aware that CVE-2025-59719 pertains to the same problem and is mentioned in the same vendor advisory. Ensure to apply all patches mentioned in the advisory.

- Exploited: CISA listed it on 2025-12-16.
- Vendor advisory: [fortiguard.fortinet.com](<https://fortiguard.fortinet.com/psirt/FG-IR-25-647>), [docs.fortinet.com](<https://docs.fortinet.com/upgrade-tool/fortigate>)
- Reported by: [Unit 42 Uncovers PEERSTITCH, a Stealthy FortiGate Implant](<https://unit42.paloaltonetworks.com/fortimanager-cve-2024-47575-peerstitch-malware/>) (Unit 42, 2026-10-14)
- Details: [CVE-2025-59718 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2025-59718>)

### CVE-2024-21762: Fortinet FortiOS

Firewall, VPN or other appliance (Fortinet). **Fortinet FortiOS Out-of-Bound Write Vulnerability.** Fortinet FortiOS contains an out-of-bound write vulnerability that allows a remote unauthenticated attacker to execute code or commands via specially crafted HTTP requests.

- Exploited: CISA listed it on 2024-02-09. Used in ransomware attacks.
- Vendor advisory: [fortiguard.fortinet.com](<https://fortiguard.fortinet.com/psirt/FG-IR-24-015>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13)
- Details: [CVE-2024-21762 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2024-21762>)

### CVE-2025-25249: Fortinet Multiple Products

Firewall, VPN or other appliance (Fortinet). **Fortinet Multiple Products Heap-based Buffer Overflow Vulnerability.** Fortinet FortiOS, FortiSwitchManager, and FortiSASE contain a heap-based buffer overflow vulnerability that allows an attacker to execute unauthorized code or commands via specially crafted packets.

- Exploited: CISA listed it on 2026-09-09.
- Vendor advisory: [fortiguard.fortinet.com](<https://fortiguard.fortinet.com/psirt/FG-IR-25-084>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13)
- Details: [CVE-2025-25249 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2025-25249>)

### CVE-2026-19490: Citrix NetScaler

Remote access or file sharing (Citrix). **Citrix NetScaler Authentication Bypass Using an Alternate Path or Channel Vulnerability.** Citrix NetScaler ADC and NetScaler Gateway contain an authentication-bypass vulnerability involving an alternate path or channel. When the NetScaler appliance is configured as an AAA virtual server or as a Gateway (SSL VPN, ICA Proxy, CVPN, or RDP Proxy), an unauthenticated remote threat actor may be able to bypass authentication.

- Exploited: CISA listed it on 2026-09-09.
- Vendor advisory: [support.citrix.com](<https://support.citrix.com/external/article/CTX696939/netscaler-adc-and-netscaler-gateway-secu.html>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13); [24th August – Threat Intelligence Report](<https://research.checkpoint.com/2026/24th-august-threat-intelligence-report/>) (Check Point Research, 2026-08-24)
- Details: [CVE-2026-19490 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-19490>)

### CVE-2026-20079: Cisco Secure Firewall Management Center (FMC) and Security Cloud Control (SCC) Firewall Management

Firewall, VPN or office router (Cisco). **Cisco Firewall Management Center Authentication Bypass Using an Alternate Path or Channel Vulnerability.** Cisco Secure Firewall Management Center (FMC) Software and Cisco Security Cloud Control (SCC) Firewall Management contain an authentication Bypass using an alternate path or channel vulnerability that could allow an unauthenticated, remote attacker to bypass authentication and execute script files on an affected device to obtain root access to the underlying operating system.

- Exploited: CISA listed it on 2026-09-09.
- Vendor advisory: [sec.cloudapps.cisco.com](<https://sec.cloudapps.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-onprem-fmc-authbypass-5JPp45V2>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13); [Q3 2026 Attack Techniques Trend Report](<https://asec.ahnlab.com/en/95733/>) (AhnLab ASEC, 2026-10-06)
- Details: [CVE-2026-20079 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-20079>)

### CVE-2026-20316: Cisco Secure Firewall Management Center (FMC)

Firewall, VPN or office router (Cisco). **Cisco Secure Firewall Management Center Use of Hard-coded Password Vulnerability.** Cisco Secure Firewall Management Center (FMC) formerly known as Firepower Management Center contains a use of hard-coded password vulnerability that could allow an unauthenticated, remote attacker to log in to an affected device using a low-privileged account to access sensitive data within the impacted systems.

- Exploited: CISA listed it on 2026-07-29. Used in ransomware attacks.
- Vendor advisory: [sec.cloudapps.cisco.com](<https://sec.cloudapps.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-fmc-static-cred-BET3Cjh>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13); [Q3 2026 Attack Techniques Trend Report](<https://asec.ahnlab.com/en/95733/>) (AhnLab ASEC, 2026-10-06); [July 2026 CVE Landscape](<https://www.recordedfuture.com/blog/july-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-08-07)
- Details: [CVE-2026-20316 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-20316>)

### CVE-2026-34908: Ubiquiti UniFi OS

Router or network device (Ubiquiti). **Ubiquiti UniFi OS Improper Access Control Vulnerability.** Ubiquiti UniFi OS contains an improper access control vulnerability which could allow a malicious actor with access to the network to make unauthorized changes to the system.

- Exploited: CISA listed it on 2026-06-23.
- Vendor advisory: [community.ui.com](<https://community.ui.com/releases/Security-Advisory-Bulletin-064-064/84811c09-4cf4-42ab-bd61-cc994445963b>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13)
- Details: [CVE-2026-34908 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-34908>)

### CVE-2026-34909: Ubiquiti UniFi OS

Router or network device (Ubiquiti). **Ubiquiti UniFi OS Path Traversal Vulnerability.** Ubiquiti UniFi OS contains a path traversal vulnerability which could allow a malicious actor with access to the network to access files on the underlying system that could be manipulated to access an underlying account.

- Exploited: CISA listed it on 2026-06-23.
- Vendor advisory: [community.ui.com](<https://community.ui.com/releases/Security-Advisory-Bulletin-064-064/84811c09-4cf4-42ab-bd61-cc994445963b>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13)
- Details: [CVE-2026-34909 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-34909>)

### CVE-2026-34910: Ubiquiti UniFi OS

Router or network device (Ubiquiti). **Ubiquiti UniFi OS Improper Input Validation Vulnerability.** Ubiquiti UniFi OS contains an improper input validation vulnerability which could allow a malicious actor with access to the network to conduct command injection.

- Exploited: CISA listed it on 2026-06-23.
- Vendor advisory: [community.ui.com](<https://community.ui.com/releases/Security-Advisory-Bulletin-064-064/84811c09-4cf4-42ab-bd61-cc994445963b>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13)
- Details: [CVE-2026-34910 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-34910>)

### CVE-2026-67277: MikroTik RouterOS

Router (MikroTik). **MikroTik RouterOS Missing Authentication for Critical Function Vulnerability.** MikroTik RouterOS contains a missing authentication for critical function vulnerability which allows kernel memory disclosure and denial of service in the btest service.

- Exploited: CISA listed it on 2026-09-10.
- Vendor advisory: [mikrotik.com](<https://mikrotik.com/supportsec/september-2026-vulnerability/>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13)
- Details: [CVE-2026-67277 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-67277>)

### CVE-2026-83548: SonicWall SMA1000 Appliances

Firewall, VPN or other appliance (SonicWall). **SonicWall SMA1000 Appliances Server-Side Request Forgery Vulnerability.** SonicWall SMA1000 Appliances contains a server-side request forgery vulnerability that could allow a remote unauthenticated attacker to gain unauthorized access to sensitive functionality and perform unauthorized operations.

- Exploited: CISA listed it on 2026-09-02.
- Vendor advisory: [psirt.global.sonicwall.com](<https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2026-0016>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13); [Max severity SonicWall SMA1000 flaw now exploited in attacks](<https://www.bleepingcomputer.com/news/security/max-severity-sonicwall-sma1000-flaw-now-exploited-in-attacks/>) (BleepingComputer, 2026-10-09); [7th September – Threat Intelligence Report](<https://research.checkpoint.com/2026/7th-september-threat-intelligence-report/>) (Check Point Research, 2026-09-07); [SonicWall 83548 83549](<https://www.sophos.com/en-us/blog/sonicwall-83548-83549>) (Sophos Threat Research, 2026-09-02)
- Details: [CVE-2026-83548 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-83548>)

### CVE-2026-83549: SonicWall SMA1000 Appliances

Firewall, VPN or other appliance (SonicWall). **SonicWall SMA1000 Appliances OS Command Injection Vulnerability.** SonicWall SMA1000 Appliances contains an OS command injection vulnerability that could enable a remote authenticated attacker as administrator to execute arbitrary OS commands, resulting in remote code execution.

- Exploited: CISA listed it on 2026-09-02.
- Vendor advisory: [psirt.global.sonicwall.com](<https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2026-0016>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13); [Max severity SonicWall SMA1000 flaw now exploited in attacks](<https://www.bleepingcomputer.com/news/security/max-severity-sonicwall-sma1000-flaw-now-exploited-in-attacks/>) (BleepingComputer, 2026-10-09); [7th September – Threat Intelligence Report](<https://research.checkpoint.com/2026/7th-september-threat-intelligence-report/>) (Check Point Research, 2026-09-07); [SonicWall 83548 83549](<https://www.sophos.com/en-us/blog/sonicwall-83548-83549>) (Sophos Threat Research, 2026-09-02)
- Details: [CVE-2026-83549 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-83549>)

### CVE-2026-84869: ConnectWise ScreenConnect

Remote support or IT management (ConnectWise). **ConnectWise ScreenConnect Improper Privilege Management and Missing Authorization Vulnerability.** ConnectWise ScreenConnect contains both an improper privilege management and missing authorization vulnerability that may allow an attacker to transfer and execute files through an active remote session without authorization or host confirmation.

- Exploited: CISA listed it on 2026-09-11.
- Vendor advisory: [www.connectwise.com](<https://www.connectwise.com/company/trust/security-bulletins/2026-09-08-screenconnect-bulletin>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13); [Q3 2026 Vulnerability Trend Report](<https://asec.ahnlab.com/en/95741/>) (AhnLab ASEC, 2026-10-06)
- Details: [CVE-2026-84869 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-84869>)

### CVE-2026-86060: MikroTik RouterOS

Router (MikroTik). **MikroTik RouterOS Improper Neutralization of Argument Delimiters in a Command Vulnerability.** MikroTik RouterOS contains an improper neutralization of argument delimiters in a command vulnerability which allows an attacker to change the trusted RouterOS policy mask, leading to privilege escalation.

- Exploited: CISA listed it on 2026-09-10.
- Vendor advisory: [mikrotik.com](<https://mikrotik.com/supportsec/september-2026-vulnerability>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13); [14th September – Threat Intelligence Report](<https://research.checkpoint.com/2026/14th-september-threat-intelligence-report/>) (Check Point Research, 2026-09-14)
- Details: [CVE-2026-86060 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-86060>)

### CVE-2026-86218: N-able N-central

IT management (N-able). **N-able N-central Static Code Injection Vulnerability.** N-able N-central contains a static code injection vulnerability that could allow for pre-authentication remote code execution.

- Exploited: CISA listed it on 2026-09-08.
- Vendor advisory: [status.n-able.com](<https://status.n-able.com/2026/09/06/n-central-2026-3-hotfix-4-cve-2026-86218/>), [me.n-able.com](<https://me.n-able.com/s/security-advisory/aArVy0000002Ld3KAE/cve202686218-preauthentication-remote-code-execution>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13); [Metasploit Wrap Up: A Collection of What Can Only Be Called Eclectic Modules](<https://www.rapid7.com/blog/post/pt-metasploit-wrap-up-a-collection-of-what-can-only-be-called-eclectic-modules>) (Rapid7, 2026-10-09)
- Details: [CVE-2026-86218 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-86218>)

### CVE-2026-15409: SonicWall SMA1000 Appliances

Firewall, VPN or other appliance (SonicWall). **SonicWall SMA1000 Appliances Server-Side Request Forgery Vulnerability.** SonicWall SMA1000 Appliances contain a server-side request forgery vulnerability that could allow a remote unauthenticated attacker to potentially cause the appliance to make requests to unintended location.

- Exploited: CISA listed it on 2026-07-14. Used in ransomware attacks.
- Vendor advisory: [psirt.global.sonicwall.com](<https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2026-0008>)
- Reported by: [Max severity SonicWall SMA1000 flaw now exploited in attacks](<https://www.bleepingcomputer.com/news/security/max-severity-sonicwall-sma1000-flaw-now-exploited-in-attacks/>) (BleepingComputer, 2026-10-09); [Fake AI, real malware: Attackers impersonating AI brands](<https://www.sophos.com/en-us/blog/fake-ai-real-malware-attackers-impersonating-ai-brands>) (Sophos Threat Research, 2026-08-19); [July 2026 CVE Landscape](<https://www.recordedfuture.com/blog/july-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-08-07); [Proxying to Compromise: SonicWall Secure Mobile Access 0-day Exploitation](<https://www.volexity.com/blog/2026/07/17/proxying-to-compromise-sonicwall-secure-mobile-access-0-day-exploitation/>) (Volexity, 2026-07-17)
- Details: [CVE-2026-15409 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-15409>)

### CVE-2026-15410: SonicWall SMA1000 Appliances

Firewall, VPN or other appliance (SonicWall). **SonicWall SMA1000 Appliances Code Injection Vulnerability.** SonicWall SMA1000 Appliances contain a code injection vulnerability which in specific conditions could potentially enable a remote authenticated attacker as administrator to execute arbitrary OS commands.

- Exploited: CISA listed it on 2026-07-14. Used in ransomware attacks.
- Vendor advisory: [psirt.global.sonicwall.com](<https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2026-0008>)
- Reported by: [Max severity SonicWall SMA1000 flaw now exploited in attacks](<https://www.bleepingcomputer.com/news/security/max-severity-sonicwall-sma1000-flaw-now-exploited-in-attacks/>) (BleepingComputer, 2026-10-09); [Fake AI, real malware: Attackers impersonating AI brands](<https://www.sophos.com/en-us/blog/fake-ai-real-malware-attackers-impersonating-ai-brands>) (Sophos Threat Research, 2026-08-19); [July 2026 CVE Landscape](<https://www.recordedfuture.com/blog/july-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-08-07); [Proxying to Compromise: SonicWall Secure Mobile Access 0-day Exploitation](<https://www.volexity.com/blog/2026/07/17/proxying-to-compromise-sonicwall-secure-mobile-access-0-day-exploitation/>) (Volexity, 2026-07-17)
- Details: [CVE-2026-15410 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-15410>)

### CVE-2026-3055: Citrix NetScaler

Remote access or file sharing (Citrix). **Citrix NetScaler Out-of-Bounds Read Vulnerability.** Citrix NetScaler ADC (formerly Citrix ADC), NetScaler Gateway (formerly Citrix Gateway) and NetScaler ADC FIPS and NDcPP contain an out-of-bounds reads vulnerability when configured as a SAML IDP leading to memory overread.

- Exploited: CISA listed it on 2026-03-30.
- Vendor advisory: [support.citrix.com](<https://support.citrix.com/support-home/kbsearch/article?articleNumber=CTX696300&articleURL=NetScaler_ADC_and_NetScaler_Gateway_Security_Bulletin_for_CVE_2026_3055_and_CVE_2026_4368>)
- Reported by: [Citrix warns admins to patch new NetScaler RCE flaw immediately](<https://www.bleepingcomputer.com/news/security/citrix-warns-admins-to-patch-new-netscaler-rce-flaw-immediately/>) (BleepingComputer, 2026-10-09); [August 2026 CVE Landscape](<https://www.recordedfuture.com/blog/august-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-09-08); [July 2026 CVE Landscape](<https://www.recordedfuture.com/blog/july-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-08-07)
- Details: [CVE-2026-3055 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-3055>)

### CVE-2019-11510: Ivanti Pulse Connect Secure

VPN or device management (Ivanti). **Ivanti Pulse Connect Secure Arbitrary File Read Vulnerability.** Ivanti Pulse Connect Secure contains an arbitrary file read vulnerability that allows an unauthenticated remote attacker with network access via HTTPS to send a specially crafted URI.

- Exploited: CISA listed it on 2021-11-03. Used in ransomware attacks.
- Reported by: [FBI disrupts Chinese hacking tools used to breach critical infrastructure](<https://www.bleepingcomputer.com/news/security/fbi-disrupts-chinese-hacking-tools-used-to-breach-critical-infrastructure/>) (BleepingComputer, 2026-10-08)
- Details: [CVE-2019-11510 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2019-11510>)

### CVE-2019-17621: D-Link DIR-859 Router

Router or network device (D-Link). **D-Link DIR-859 Router Command Execution Vulnerability.** D-Link DIR-859 router contains a command execution vulnerability in the UPnP endpoint URL, /gena.cgi. Exploitation allows an unauthenticated remote attacker to execute system commands as root by sending a specially crafted HTTP SUBSCRIBE request to the UPnP service when connecting to the local network.

- Exploited: CISA listed it on 2023-06-29.
- Vendor advisory: [supportannouncement.us.dlink.com](<https://supportannouncement.us.dlink.com/announcement/publication.aspx?name=SAP10147>)
- Reported by: [ClingSTUN Linux Backdoor Abuses Public STUN Infrastructure](<https://feeds.fortinet.com/~/971007764/0/fortinet/blog/threat-research~ClingSTUN-Linux-Backdoor-Abuses-Public-STUN-Infrastructure>) (Fortinet Threat Research, 2026-10-05)
- Details: [CVE-2019-17621 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2019-17621>)

### CVE-2022-37055: D-Link Routers

Router or network device (D-Link). **D-Link Routers Buffer Overflow Vulnerability.** D-Link Routers contains a buffer overflow vulnerability that has a high impact on confidentiality, integrity, and availability. The impacted products could be end-of-life (EoL) and/or end-of-service (EoS). Users should discontinue product utilization.

- Exploited: CISA listed it on 2025-12-08.
- Vendor advisory: [supportannouncement.us.dlink.com](<https://supportannouncement.us.dlink.com/security/publication.aspx?name=SAP10308>)
- Reported by: [ClingSTUN Linux Backdoor Abuses Public STUN Infrastructure](<https://feeds.fortinet.com/~/971007764/0/fortinet/blog/threat-research~ClingSTUN-Linux-Backdoor-Abuses-Public-STUN-Infrastructure>) (Fortinet Threat Research, 2026-10-05)
- Details: [CVE-2022-37055 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2022-37055>)

### CVE-2023-1389: TP-Link Archer AX21

Router or network device (TP-Link). **TP-Link Archer AX-21 Command Injection Vulnerability.** TP-Link Archer AX-21 contains a command injection vulnerability that allows for remote code execution.

- Exploited: CISA listed it on 2023-05-01.
- Vendor advisory: [www.tp-link.com](<https://www.tp-link.com/us/support/download/archer-ax21/v3/#Firmware>)
- Reported by: [ClingSTUN Linux Backdoor Abuses Public STUN Infrastructure](<https://feeds.fortinet.com/~/971007764/0/fortinet/blog/threat-research~ClingSTUN-Linux-Backdoor-Abuses-Public-STUN-Infrastructure>) (Fortinet Threat Research, 2026-10-05)
- Details: [CVE-2023-1389 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2023-1389>)

### CVE-2023-33538: TP-Link Multiple Routers

Router or network device (TP-Link). **TP-Link Multiple Routers Command Injection Vulnerability.** TP-Link TL-WR940N V2/V4, TL-WR841N V8/V10, and TL-WR740N V1/V2 contain a command injection vulnerability via the component /userRpm/WlanNetworkRpm. The impacted products could be end-of-life (EoL) and/or end-of-service (EoS). Users should discontinue product utilization.

- Exploited: CISA listed it on 2025-06-16.
- Vendor advisory: [www.tp-link.com](<https://www.tp-link.com/nordic/support/faq/3562/>)
- Reported by: [Threat Brief: NetScaler Zero Days CVE-2026-88771 and CVE-2026-88772 Exploited in the Wild (Updated September 30)](<https://unit42.paloaltonetworks.com/netscaler-zero-days-exploited/>) (Unit 42, 2026-09-30)
- Details: [CVE-2023-33538 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2023-33538>)

### CVE-2026-0257: Palo Alto Networks PAN-OS

Firewall or VPN (Palo Alto Networks). **Palo Alto Networks PAN-OS Authentication Bypass Vulnerability.** Palo Alto Networks PAN-OS contains an authentication bypass vulnerability that allows attackers to bypass security restrictions and establish an unauthorized VPN connection.

- Exploited: CISA listed it on 2026-05-29. Used in ransomware attacks.
- Vendor advisory: [security.paloaltonetworks.com](<https://security.paloaltonetworks.com/CVE-2026-0257>)
- Reported by: [Threat Brief: NetScaler Zero Days CVE-2026-88771 and CVE-2026-88772 Exploited in the Wild (Updated September 30)](<https://unit42.paloaltonetworks.com/netscaler-zero-days-exploited/>) (Unit 42, 2026-09-30); [July 2026 CVE Landscape](<https://www.recordedfuture.com/blog/july-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-08-07)
- Details: [CVE-2026-0257 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-0257>)

### CVE-2026-0300: Palo Alto Networks PAN-OS

Firewall or VPN (Palo Alto Networks). **Palo Alto Networks PAN-OS Out-of-bounds Write Vulnerability.** Palo Alto Networks PAN-OS contains an out-of-bounds write vulnerability in the User-ID Authentication Portal (aka Captive Portal) service that can allow an unauthenticated attacker to execute arbitrary code with root privileges on the PA-Series and VM-Series firewalls by sending specially crafted packets.

- Exploited: CISA listed it on 2026-05-06.
- Vendor advisory: [security.paloaltonetworks.com](<https://security.paloaltonetworks.com/CVE-2026-0300>)
- Reported by: [Threat Brief: NetScaler Zero Days CVE-2026-88771 and CVE-2026-88772 Exploited in the Wild (Updated September 30)](<https://unit42.paloaltonetworks.com/netscaler-zero-days-exploited/>) (Unit 42, 2026-09-30); [August 2026 CVE Landscape](<https://www.recordedfuture.com/blog/august-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-09-08)
- Details: [CVE-2026-0300 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-0300>)

### CVE-2026-1281: Ivanti Endpoint Manager Mobile (EPMM)

VPN or device management (Ivanti). **Ivanti Endpoint Manager Mobile (EPMM) Code Injection Vulnerability.** Ivanti Endpoint Manager Mobile (EPMM) contains a code injection vulnerability that could allow attackers to achieve unauthenticated remote code execution.

- Exploited: CISA listed it on 2026-01-29.
- Vendor advisory: [forums.ivanti.com](<https://forums.ivanti.com/s/article/Security-Advisory-Ivanti-Endpoint-Manager-Mobile-EPMM-CVE-2026-1281-CVE-2026-1340>), [support.mobileiron.com](<https://support.mobileiron.com/mi/vsp/AB1771634/ivanti-security-update-1761642-1.0.0S-5.noarch.rpm>), [support.mobileiron.com](<https://support.mobileiron.com/mi/vsp/AB1771634/ivanti-security-update-1761642-1.0.0L-5.noarch.rpm>)
- Reported by: [Threat Brief: NetScaler Zero Days CVE-2026-88771 and CVE-2026-88772 Exploited in the Wild (Updated September 30)](<https://unit42.paloaltonetworks.com/netscaler-zero-days-exploited/>) (Unit 42, 2026-09-30)
- Details: [CVE-2026-1281 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-1281>)

### CVE-2026-1340: Ivanti Endpoint Manager Mobile (EPMM)

VPN or device management (Ivanti). **Ivanti Endpoint Manager Mobile (EPMM) Code Injection Vulnerability.** Ivanti Endpoint Manager Mobile (EPMM) contains a code injection vulnerability that could allow attackers to achieve unauthenticated remote code execution.

- Exploited: CISA listed it on 2026-04-08.
- Vendor advisory: [hub.ivanti.com](<https://hub.ivanti.com/s/article/Security-Advisory-Ivanti-Endpoint-Manager-Mobile-EPMM-CVE-2026-1281-CVE-2026-1340?language=en_US>), [support.mobileiron.com](<https://support.mobileiron.com/mi/vsp/AB1786671/ivanti-security-update-1761642-1.1.0S-5.noarch.rpm>), [support.mobileiron.com](<https://support.mobileiron.com/mi/vsp/AB1786671/ivanti-security-update-1761642-1.1.0L-5.noarch.rpm>)
- Reported by: [Threat Brief: NetScaler Zero Days CVE-2026-88771 and CVE-2026-88772 Exploited in the Wild (Updated September 30)](<https://unit42.paloaltonetworks.com/netscaler-zero-days-exploited/>) (Unit 42, 2026-09-30)
- Details: [CVE-2026-1340 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-1340>)

### CVE-2026-73570: Synacor Zimbra Collaboration Suite (ZCS)

Email server (Zimbra). **Zimbra Collaboration Suite (ZCS) OS Command Injection Vulnerability.** Zimbra Collaboration Suite (ZCS) contains an OS command injection vulnerability which could allow an unauthenticated attacker to send specially crafted SMTP requests that may result in execution of arbitrary operating system commands as the Zimbra user.

- Exploited: CISA listed it on 2026-08-21.
- Vendor advisory: [wiki.zimbra.com](<https://wiki.zimbra.com/wiki/Zimbra_Security_Advisories>), [blog.zimbra.com](<https://blog.zimbra.com/2026/07/patch-release-update-zimbra-10-1-20/>)
- Reported by: [Unauthenticated command injection on internet-facing mail servers: tracking CVE-2026-73570](<https://www.microsoft.com/en-us/security/blog/2026/09/30/unauthenticated-command-injection-on-internet-facing-mail-servers-tracking-cve-2026-73570/>) (Microsoft Threat Intelligence, 2026-09-30); [When Business Email Compromise Starts Rewriting Reality](<https://www.rapid7.com/blog/post/ve-business-email-compromise-rewriting-reality-zimbra-cve>) (Rapid7, 2026-09-24); [August 2026 CVE Landscape](<https://www.recordedfuture.com/blog/august-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-09-08)
- Details: [CVE-2026-73570 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-73570>)

### CVE-2024-3400: Palo Alto Networks PAN-OS

Firewall or VPN (Palo Alto Networks). **Palo Alto Networks PAN-OS Command Injection Vulnerability.** Palo Alto Networks PAN-OS GlobalProtect feature contains a command injection vulnerability that allows an unauthenticated attacker to execute commands with root privileges on the firewall.

- Exploited: CISA listed it on 2024-04-12. Used in ransomware attacks.
- Vendor advisory: [security.paloaltonetworks.com](<https://security.paloaltonetworks.com/CVE-2024-3400>)
- Reported by: [Inside the Telecom Attack Surface: SS7, BGP Hijacking, and the Technical Reality of Nation-State Intrusions](<https://cyble.com/blog/ss7-bgp-nation-state-intrusions/>) (Cyble, 2026-09-25)
- Details: [CVE-2024-3400 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2024-3400>)

### CVE-2022-27925: Synacor Zimbra Collaboration Suite (ZCS)

Email server (Zimbra). **Synacor Zimbra Collaboration Suite (ZCS) Arbitrary File Upload Vulnerability.** Synacor Zimbra Collaboration Suite (ZCS) contains flaw in the mboximport functionality, allowing an authenticated attacker to upload arbitrary files to perform remote code execution. This vulnerability was chained with CVE-2022-37042 which allows for unauthenticated remote code execution.

- Exploited: CISA listed it on 2022-08-11. Used in ransomware attacks.
- Vendor advisory: [blog.zimbra.com](<https://blog.zimbra.com/2022/08/authentication-bypass-in-mailboximportservlet-vulnerability/>)
- Reported by: [When Business Email Compromise Starts Rewriting Reality](<https://www.rapid7.com/blog/post/ve-business-email-compromise-rewriting-reality-zimbra-cve>) (Rapid7, 2026-09-24); [August 2026 CVE Landscape](<https://www.recordedfuture.com/blog/august-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-09-08)
- Details: [CVE-2022-27925 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2022-27925>)

### CVE-2022-37042: Synacor Zimbra Collaboration Suite (ZCS)

Email server (Zimbra). **Synacor Zimbra Collaboration Suite (ZCS) Authentication Bypass Vulnerability.** Synacor Zimbra Collaboration Suite (ZCS) contains an authentication bypass vulnerability in MailboxImportServlet. This vulnerability was chained with CVE-2022-27925 which allows for unauthenticated remote code execution.

- Exploited: CISA listed it on 2022-08-11. Used in ransomware attacks.
- Vendor advisory: [blog.zimbra.com](<https://blog.zimbra.com/2022/08/authentication-bypass-in-mailboximportservlet-vulnerability/>)
- Reported by: [When Business Email Compromise Starts Rewriting Reality](<https://www.rapid7.com/blog/post/ve-business-email-compromise-rewriting-reality-zimbra-cve>) (Rapid7, 2026-09-24)
- Details: [CVE-2022-37042 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2022-37042>)

### CVE-2023-37580: Synacor Zimbra Collaboration Suite (ZCS)

Email server (Zimbra). **Synacor Zimbra Collaboration Suite (ZCS) Cross-Site Scripting (XSS) Vulnerability.** Synacor Zimbra Collaboration Suite (ZCS) contains a cross-site scripting vulnerability impacting the confidentiality and integrity of data.

- Exploited: CISA listed it on 2023-07-27.
- Vendor advisory: [wiki.zimbra.com](<https://wiki.zimbra.com/wiki/Security_Center>)
- Reported by: [When Business Email Compromise Starts Rewriting Reality](<https://www.rapid7.com/blog/post/ve-business-email-compromise-rewriting-reality-zimbra-cve>) (Rapid7, 2026-09-24)
- Details: [CVE-2023-37580 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2023-37580>)

### CVE-2024-45519: Synacor Zimbra Collaboration Suite (ZCS)

Email server (Zimbra). **Synacor Zimbra Collaboration Suite (ZCS) Command Execution Vulnerability.** Synacor Zimbra Collaboration Suite (ZCS) contains an unspecified vulnerability in the postjournal service that may allow an unauthenticated user to execute commands.

- Exploited: CISA listed it on 2024-10-03.
- Vendor advisory: [wiki.zimbra.com](<https://wiki.zimbra.com/wiki/Zimbra_Security_Advisories>)
- Reported by: [When Business Email Compromise Starts Rewriting Reality](<https://www.rapid7.com/blog/post/ve-business-email-compromise-rewriting-reality-zimbra-cve>) (Rapid7, 2026-09-24)
- Details: [CVE-2024-45519 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2024-45519>)

### CVE-2025-27915: Synacor Zimbra Collaboration Suite (ZCS)

Email server (Zimbra). **Synacor Zimbra Collaboration Suite (ZCS) Cross-site Scripting Vulnerability.** Synacor Zimbra Collaboration Suite (ZCS) contains a cross-site scripting vulnerability that exists in the Classic Web Client due to insufficient sanitization of HTML content in ICS files. When a user views an e-mail message containing a malicious ICS entry, its embedded JavaScript executes via an ontoggle event inside a tag. This allows an attacker to run arbitrary JavaScript within the victim's session, potentially leading to unauthorized actions such as setting e-mail filters to redirect messages to an attacker-controlled address. As a result, an attacker can perform unauthorized actions on the victim's account, including e-mail redirection and data exfiltration.

- Exploited: CISA listed it on 2025-10-07.
- Vendor advisory: [wiki.zimbra.com](<https://wiki.zimbra.com/wiki/Security_Center>)
- Reported by: [When Business Email Compromise Starts Rewriting Reality](<https://www.rapid7.com/blog/post/ve-business-email-compromise-rewriting-reality-zimbra-cve>) (Rapid7, 2026-09-24)
- Details: [CVE-2025-27915 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2025-27915>)

---

Published by WatchmanHQ (https://watchmanhq.com). Free, best effort, provided as is, with no warranty of any kind.
Check the vendor's advisory before you change a device. CISA's catalog is public domain (CC0); these alerts are CC BY 4.0: credit WatchmanHQ.
