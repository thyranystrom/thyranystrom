# Hi, I'm Thyra

I'm a 3rd-year Computer Science student (Karlstad University), focused on cybersecurity. I like understanding how systems break and then making sure they don't — from the application layer down to the network. My goal is to work as a security engineer, and to start a master's in cybersecurity.

Most of what I build follows one thread: find vulnerabilities, fix them, verify the fix, and make sure the next attack gets detected.

## Featured projects

[ad-lab](https://github.com/thyranystrom/ad-lab) — Active Directory attack & detection lab Built a Windows AD domain from scratch, attacked it from Kali (BloodHound, Kerberoasting, password spraying), then detected each attack in the logs — including finding that the right audit policy wasn't enabled. Full write-ups with MITRE ATT&CK mappings and remediation. Next: forwarding logs to Microsoft Sentinel with KQL detection rules.

[scanner](https://github.com/thyranystrom/scanner) — SAST tool for WooCommerce/WordPress A static analysis tool with AST-based taint analysis and a WordPress-aware rule set (OWASP Top 10). Includes inter-procedural taint tracking, confidence scoring, an auto-fix engine, and CI that fails the build if detection regresses. I also turned it on itself and documented the security bugs it found in its own code.

[home-lab](https://github.com/thyranystrom/home-lab) — SOC home lab A blue-team lab on Wazuh SIEM: simulating attacks, detecting them, and writing incident reports mapped to MITRE ATT&CK — including a full SQL injection → RCE chain and its remediation.

## Currently working on
- A firewall in C (NFQUEUE) that blocks the attacks from my labs and feeds alerts to Wazuh — low-level packet parsing, fuzz-tested.
- Phase 3 of the AD lab: Microsoft Sentinel + KQL detection-as-code.

## Experience

Hands-on experience through an IT internship covering QA testing, penetration testing and software engineering.

## Tools & tech used across these projects

Python · C · PowerShell · Active Directory · Wazuh · BloodHound · Impacket · hashcat · MITRE ATT&CK · OWASP · Linux
