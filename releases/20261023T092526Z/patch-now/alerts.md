# Patch now

WatchmanHQ patch-now alerts, release 20261023T092526Z, built 2026-10-23 09:25 UTC.

Flaws attackers are exploiting, in equipment small firms and their IT providers run. Each one is in CISA's Known Exploited Vulnerabilities catalog, so attackers are already using it, and a report we read names it. Newest first.

**If you run one of these:** Install the vendor's update, or its workaround until there is one, then follow the advisory's steps to look for signs of compromise: an update closes the hole, it does not remove an attacker who got in first. If the device gets no more updates (past its end of life), take it off the internet and replace it.

22 alerts: 9 newly exploited, 13 older. [CISA catalog](<https://www.cisa.gov/known-exploited-vulnerabilities-catalog>) version 2026.10.21, read 2026-10-23.

## Newly exploited

CISA added these to its catalog in the last 30 days.

### CVE-2026-88771: Citrix NetScaler

Remote access or file sharing (Citrix). **Citrix NetScaler Improper Input Validation Vulnerability.** Citrix NetScaler ADC and NetScaler Gateway contain an improper input validation vulnerability that could allow an unauthenticated attacker to execute arbitrary commands.

- Exploited: CISA listed it on 2026-09-27.
- Vendor advisory: [community.citrix.com](<https://community.citrix.com/techzone-blogs/110_security-updates/netscaler-adc-and-netscaler-gateway-security-bulletin-for-cve-2026-88771-through-cve-2026-88778>), [support.citrix.com](<https://support.citrix.com/support-home/kbsearch/article?articleNumber=CTX697096>), [support.citrix.com](<https://support.citrix.com/external/article/CTX694799/steps-to-take-if-netscaler-adc-is-suspec.html>)
- Reported by: [CVE-2026-109618 and CVE-2026-109619: PHP Vulnerable to Unauthenticated RCE Attacks](<https://www.zscaler.com/blogs/security-research/cve-2026-109618-and-cve-2026-109619-php-vulnerable-unauthenticated-rce>) (Zscaler ThreatLabz, 2026-10-21); [Threat Brief: Critical Vulnerabilities in PHP: CVE-2026-109618, CVE-2026-109619](<https://unit42.paloaltonetworks.com/cve-2026-109618-cve-2026-109619/>) (Unit 42, 2026-10-21); [Rapid7 Analysis: NetScaler intrusions chaining CVE-2026-88771 and CVE-2026-88779](<https://www.rapid7.com/blog/post/ra-netscaler-intrusions-chaining-cve-2026-88771-and-cve-2026-88779>) (Rapid7, 2026-10-19); [CVE-2026-88771: Inside the Exploitation of a Critical NetScaler RCE Vulnerability](<https://www.zscaler.com/blogs/security-research/cve-2026-88771-inside-exploitation-critical-netscaler-rce-vulnerability>) (Zscaler ThreatLabz, 2026-10-16); [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13) and 10 more
- Details: [CVE-2026-88771 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-88771>)

### CVE-2026-88772: Citrix NetScaler

Remote access or file sharing (Citrix). **Citrix NetScaler Improper Restriction of Operations within the Bounds of a Memory Buffer Vulnerability.** Citrix NetScaler ADC and NetScaler Gateway contain an improper restriction of operations within the bounds of a memory buffer vulnerability that could allow for remote code execution or denial of service

- Exploited: CISA listed it on 2026-09-27.
- Vendor advisory: [community.citrix.com](<https://community.citrix.com/techzone-blogs/110_security-updates/netscaler-adc-and-netscaler-gateway-security-bulletin-for-cve-2026-88771-through-cve-2026-88778>), [support.citrix.com](<https://support.citrix.com/support-home/kbsearch/article?articleNumber=CTX697096>), [support.citrix.com](<https://support.citrix.com/external/article/CTX694799/steps-to-take-if-netscaler-adc-is-suspec.html>)
- Reported by: [Threat Brief: Critical Vulnerabilities in PHP: CVE-2026-109618, CVE-2026-109619](<https://unit42.paloaltonetworks.com/cve-2026-109618-cve-2026-109619/>) (Unit 42, 2026-10-21); [Rapid7 Analysis: NetScaler intrusions chaining CVE-2026-88771 and CVE-2026-88779](<https://www.rapid7.com/blog/post/ra-netscaler-intrusions-chaining-cve-2026-88771-and-cve-2026-88779>) (Rapid7, 2026-10-19); [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13); [Citrix warns admins to patch new NetScaler RCE flaw immediately](<https://www.bleepingcomputer.com/news/security/citrix-warns-admins-to-patch-new-netscaler-rce-flaw-immediately/>) (BleepingComputer, 2026-10-09); [Blinder Tunnel Campaign Targets Iraqi Infrastructure](<https://unit42.paloaltonetworks.com/blinder-tunnel-targets-critical-infrastructure/>) (Unit 42, 2026-10-06) and 7 more
- Details: [CVE-2026-88772 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-88772>)

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
- Vendor advisory: [mikrotik.com](<https://mikrotik.com/supportsec/september-2026-vulnerability>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13)
- Details: [CVE-2026-67279 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-67279>)

## Older flaws, exploited again

CISA listed these earlier, and at least 2 publishers named them in the last 30 days: devices never updated, or past their end of life, are the targets.

### CVE-2026-0257: Palo Alto Networks PAN-OS

Firewall or VPN (Palo Alto Networks). **Palo Alto Networks PAN-OS Authentication Bypass Vulnerability.** Palo Alto Networks PAN-OS contains an authentication bypass vulnerability that allows attackers to bypass security restrictions and establish an unauthorized VPN connection.

- Exploited: CISA listed it on 2026-05-29. Used in ransomware attacks.
- Vendor advisory: [security.paloaltonetworks.com](<https://security.paloaltonetworks.com/CVE-2026-0257>)
- Reported by: [Stray Cat, Open Doors: How k0t Wanders Through the Network Edge](<https://www.group-ib.com/blog/stray-cat-network-edge/>) (Group-IB, 2026-10-21); [Threat Brief: Critical Vulnerabilities in PHP: CVE-2026-109618, CVE-2026-109619](<https://unit42.paloaltonetworks.com/cve-2026-109618-cve-2026-109619/>) (Unit 42, 2026-10-21); [“Next Exploit Opportunities”: How a Threat Actor Used AI to Help Plan and Execute Multiple Types of Cybercrime Activities](<https://unit42.paloaltonetworks.com/ai-assisted-cybercrime-analysis/>) (Unit 42, 2026-10-21); [Threat Brief: NetScaler Zero Days CVE-2026-88771 and CVE-2026-88772 Exploited in the Wild (Updated September 30)](<https://unit42.paloaltonetworks.com/netscaler-zero-days-exploited/>) (Unit 42, 2026-09-30); [July 2026 CVE Landscape](<https://www.recordedfuture.com/blog/july-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-08-07)
- Details: [CVE-2026-0257 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-0257>)

### CVE-2026-1731: BeyondTrust Remote Support (RS) and Privileged Remote Access (PRA)

Remote support (BeyondTrust). **BeyondTrust Remote Support (RS) and Privileged Remote Access (PRA) OS Command Injection Vulnerability.** BeyondTrust Remote Support (RS) and Privileged Remote Access (PRA)contain an OS command injection vulnerability. Successful exploitation could allow an unauthenticated remote attacker to execute operating system commands in the context of the site user. Successful exploitation requires no authentication or user interaction and may lead to system compromise, including unauthorized access, data exfiltration, and service disruption.

- Exploited: CISA listed it on 2026-02-13. Used in ransomware attacks.
- Vendor advisory: [www.beyondtrust.com](<https://www.beyondtrust.com/trust-center/security-advisories/bt26-02>)
- Reported by: [Threat Brief: Critical Vulnerabilities in PHP: CVE-2026-109618, CVE-2026-109619](<https://unit42.paloaltonetworks.com/cve-2026-109618-cve-2026-109619/>) (Unit 42, 2026-10-21); [CVE-2026-102764: Critical BeyondTrust Remote Support Authentication Bypass Exploited in the Wild](<https://www.rapid7.com/blog/post/etr-cve-2026-102764-critical-beyondtrust-remote-support-authentication-bypass-exploited-in-the-wild>) (Rapid7, 2026-10-19); [BeyondTrust patches zero-day exploited in attacks since August](<https://www.bleepingcomputer.com/news/security/beyondtrust-patches-zero-day-exploited-in-attacks-since-august/>) (BleepingComputer, 2026-10-16); [Threat Brief: NetScaler Zero Days CVE-2026-88771 and CVE-2026-88772 Exploited in the Wild (Updated September 30)](<https://unit42.paloaltonetworks.com/netscaler-zero-days-exploited/>) (Unit 42, 2026-09-30); [Vulnerability Discovery and Exploitation Trends in the AI Era](<https://cloud.google.com/blog/topics/threat-intelligence/vulnerability-discovery-and-exploitation-trends-in-the-ai-era/>) (Google Threat Intelligence / Mandiant, 2026-09-30) and 1 more
- Details: [CVE-2026-1731 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-1731>)

### CVE-2023-46805: Ivanti Connect Secure and Policy Secure

VPN or device management (Ivanti). **Ivanti Connect Secure and Policy Secure Authentication Bypass Vulnerability.** Ivanti Connect Secure (ICS, formerly known as Pulse Connect Secure) and Ivanti Policy Secure gateways contain an authentication bypass vulnerability in the web component that allows an attacker to access restricted resources by bypassing control checks. This vulnerability can be leveraged in conjunction with CVE-2024-21887, a command injection vulnerability.

- Exploited: CISA listed it on 2024-01-10. Used in ransomware attacks.
- Vendor advisory: [forums.ivanti.com](<https://forums.ivanti.com/s/article/KB-CVE-2023-46805-Authentication-Bypass-CVE-2024-21887-Command-Injection-for-Ivanti-Connect-Secure-and-Ivanti-Policy-Secure-Gateways?language=en_US>)
- Reported by: [BeyondTrust patches zero-day exploited in attacks since August](<https://www.bleepingcomputer.com/news/security/beyondtrust-patches-zero-day-exploited-in-attacks-since-august/>) (BleepingComputer, 2026-10-16); [ARMORY CASTLE Exploits BeyondTrust](<https://cloud.google.com/blog/topics/threat-intelligence/armory-castle-exploits-beyondtrust/>) (Google Threat Intelligence / Mandiant, 2026-10-15); [CISA warns admins to immediately fix Ivanti flaw exploited as zero-day](<https://www.bleepingcomputer.com/news/security/cisa-warns-admins-to-immediately-fix-ivanti-flaw-exploited-as-zero-day/>) (BleepingComputer, 2026-10-14); [Ivanti warns of Connect Secure zero-day exploited in attacks](<https://www.bleepingcomputer.com/news/security/ivanti-warns-of-connect-secure-zero-day-exploited-in-attacks/>) (BleepingComputer, 2026-10-13); [ClingSTUN Linux Backdoor Abuses Public STUN Infrastructure](<https://feeds.fortinet.com/~/971007764/0/fortinet/blog/threat-research~ClingSTUN-Linux-Backdoor-Abuses-Public-STUN-Infrastructure>) (Fortinet Threat Research, 2026-10-05) and 1 more
- Details: [CVE-2023-46805 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2023-46805>)

### CVE-2024-21887: Ivanti Connect Secure and Policy Secure

VPN or device management (Ivanti). **Ivanti Connect Secure and Policy Secure Command Injection Vulnerability.** Ivanti Connect Secure (ICS, formerly known as Pulse Connect Secure) and Ivanti Policy Secure contain a command injection vulnerability in the web components of these products, which can allow an authenticated administrator to send crafted requests to execute code on affected appliances. This vulnerability can be leveraged in conjunction with CVE-2023-46805, an authenticated bypass issue.

- Exploited: CISA listed it on 2024-01-10. Used in ransomware attacks.
- Vendor advisory: [forums.ivanti.com](<https://forums.ivanti.com/s/article/KB-CVE-2023-46805-Authentication-Bypass-CVE-2024-21887-Command-Injection-for-Ivanti-Connect-Secure-and-Ivanti-Policy-Secure-Gateways?language=en_US>)
- Reported by: [BeyondTrust patches zero-day exploited in attacks since August](<https://www.bleepingcomputer.com/news/security/beyondtrust-patches-zero-day-exploited-in-attacks-since-august/>) (BleepingComputer, 2026-10-16); [ARMORY CASTLE Exploits BeyondTrust](<https://cloud.google.com/blog/topics/threat-intelligence/armory-castle-exploits-beyondtrust/>) (Google Threat Intelligence / Mandiant, 2026-10-15); [CISA warns admins to immediately fix Ivanti flaw exploited as zero-day](<https://www.bleepingcomputer.com/news/security/cisa-warns-admins-to-immediately-fix-ivanti-flaw-exploited-as-zero-day/>) (BleepingComputer, 2026-10-14); [Ivanti warns of Connect Secure zero-day exploited in attacks](<https://www.bleepingcomputer.com/news/security/ivanti-warns-of-connect-secure-zero-day-exploited-in-attacks/>) (BleepingComputer, 2026-10-13); [ClingSTUN Linux Backdoor Abuses Public STUN Infrastructure](<https://feeds.fortinet.com/~/971007764/0/fortinet/blog/threat-research~ClingSTUN-Linux-Backdoor-Abuses-Public-STUN-Infrastructure>) (Fortinet Threat Research, 2026-10-05) and 1 more
- Details: [CVE-2024-21887 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2024-21887>)

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

### CVE-2026-85102: Check Point Multiple Products

Firewall, VPN or other appliance (Check Point). **Check Point Multiple Products Improper Certificate Validation Vulnerability.** Check Point Security Gateway and Check Point Spark Firewall using Site to Site VPN or Remote Access VPN contain an improper certificate validation vulnerability which could allow an unauthenticated remote attacker to execute arbitrary code on the Gateway.

- Exploited: CISA listed it on 2026-09-22.
- Vendor advisory: [support.checkpoint.com](<https://support.checkpoint.com/results/sk/sk1000117>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13); [Q3 2026 Vulnerability Trend Report](<https://asec.ahnlab.com/en/95741/>) (AhnLab ASEC, 2026-10-06); [28th September – Threat Intelligence Report](<https://research.checkpoint.com/2026/28th-september-threat-intelligence-report/>) (Check Point Research, 2026-09-28)
- Details: [CVE-2026-85102 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-85102>)

### CVE-2026-86218: N-able N-central

IT management (N-able). **N-able N-central Static Code Injection Vulnerability.** N-able N-central contains a static code injection vulnerability that could allow for pre-authentication remote code execution.

- Exploited: CISA listed it on 2026-09-08.
- Vendor advisory: [status.n-able.com](<https://status.n-able.com/2026/09/06/n-central-2026-3-hotfix-4-cve-2026-86218/>), [me.n-able.com](<https://me.n-able.com/s/security-advisory/aArVy0000002Ld3KAE/cve202686218-preauthentication-remote-code-execution>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13); [Metasploit Wrap Up: A Collection of What Can Only Be Called Eclectic Modules](<https://www.rapid7.com/blog/post/pt-metasploit-wrap-up-a-collection-of-what-can-only-be-called-eclectic-modules>) (Rapid7, 2026-10-09)
- Details: [CVE-2026-86218 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-86218>)

### CVE-2026-93616: Check Point Multiple Products

Firewall, VPN or other appliance (Check Point). **Check Point Multiple Products Path Traversal Vulnerability.** Check Point Security Management Server, Multi-Domain Security Management Server, Log Server, Multi-Domain Log Server, and SmartEvent contain a path traversal vulnerability that allows an unauthenticated attacker to upload and execute arbitrary scripts.

- Exploited: CISA listed it on 2026-09-22.
- Vendor advisory: [support.checkpoint.com](<https://support.checkpoint.com/results/sk/sk1000171/>)
- Reported by: [September 2026 CVE Landscape](<https://www.recordedfuture.com/blog/september-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-10-13); [28th September – Threat Intelligence Report](<https://research.checkpoint.com/2026/28th-september-threat-intelligence-report/>) (Check Point Research, 2026-09-28)
- Details: [CVE-2026-93616 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-93616>)

### CVE-2026-73570: Synacor Zimbra Collaboration Suite (ZCS)

Email server (Zimbra). **Zimbra Collaboration Suite (ZCS) OS Command Injection Vulnerability.** Zimbra Collaboration Suite (ZCS) contains an OS command injection vulnerability which could allow an unauthenticated attacker to send specially crafted SMTP requests that may result in execution of arbitrary operating system commands as the Zimbra user.

- Exploited: CISA listed it on 2026-08-21.
- Vendor advisory: [wiki.zimbra.com](<https://wiki.zimbra.com/wiki/Zimbra_Security_Advisories>), [blog.zimbra.com](<https://blog.zimbra.com/2026/07/patch-release-update-zimbra-10-1-20/>)
- Reported by: [Unauthenticated command injection on internet-facing mail servers: tracking CVE-2026-73570](<https://www.microsoft.com/en-us/security/blog/2026/09/30/unauthenticated-command-injection-on-internet-facing-mail-servers-tracking-cve-2026-73570/>) (Microsoft Threat Intelligence, 2026-09-30); [When Business Email Compromise Starts Rewriting Reality](<https://www.rapid7.com/blog/post/ve-business-email-compromise-rewriting-reality-zimbra-cve>) (Rapid7, 2026-09-24); [August 2026 CVE Landscape](<https://www.recordedfuture.com/blog/august-2026-cve-landscape>) (Recorded Future Insikt Group, 2026-09-08)
- Details: [CVE-2026-73570 at NVD](<https://nvd.nist.gov/vuln/detail/CVE-2026-73570>)

---

Published by WatchmanHQ (https://watchmanhq.com). Free, best effort, provided as is, with no warranty of any kind.
Check the vendor's advisory before you change a device. CISA's catalog is public domain (CC0); these alerts are CC BY 4.0: credit WatchmanHQ.
