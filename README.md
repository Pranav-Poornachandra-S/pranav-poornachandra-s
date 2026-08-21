# Hi, I'm Pranav Poornachandra S

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/pranav-poornachandra-s)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@pranav-poornachandra-s)

## About Me
I am an aspiring Purple Teamer driven by a dual-perspective approach: understanding how adversaries breach systems to build resilient automated defences. My work spans offensive penetration testing and defensive engineering, bridging the gap between red and blue team operations.

* **Currently Building:** Enterprise Security Automation & Active Directory Attack/Defend Labs.
* **Core Focus:** Defensive Detection Engineering, Offensive Security Testing, Network Security.
* **Certifications:** Junior Penetration Tester (eJPTv2) | INE Certified Cloud Associate (ICCA) | Google Cybersecurity Professional.

---

## Technical Stack & Tools

### Security Operations & Detection Engineering (SIEM / SOAR / EDR)
![Microsoft Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-0089D6?style=flat&logo=microsoftazure&logoColor=white)
![Splunk Enterprise](https://img.shields.io/badge/Splunk_Enterprise-000000?style=flat&logo=splunk&logoColor=white)
![ELK Stack](https://img.shields.io/badge/ELK_Stack-005571?style=flat&logo=elastic&logoColor=white)
![LimaCharlie](https://img.shields.io/badge/LimaCharlie_EDR-blue?style=flat&logo=shield)
![Tines](https://img.shields.io/badge/Tines_SOAR-purple?style=flat)

### Offensive Security & Vulnerability Assessment
![Nmap](https://img.shields.io/badge/Nmap-002B49?style=flat&logo=nmap&logoColor=white)
![SQLMap](https://img.shields.io/badge/SQLMap-D22128?style=flat)
![Nessus](https://img.shields.io/badge/Nessus-00A3E0?style=flat)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6600?style=flat&logo=burpsuite&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP_Top_10-000000?style=flat&logo=owasp)

### Languages, Frameworks & Environments
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![Python](https://img.shields.io/badge/Python_3-3776AB?style=flat&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)
![KQL](https://img.shields.io/badge/KQL_(Kusto)-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![ES|QL](https://img.shields.io/badge/ES|QL-005571?style=flat&logo=elastic&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-123456?style=flat&logo=metasploit&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-FF6600?style=flat&logo=mitre&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat&logo=windows11&logoColor=white)

---

## Skills & Project Mapping Matrix

| Technical Skill | Primary Application | Featured Repository |
| :--- | :--- | :--- |
| **Active Directory & Threat Hunting** | Simulating RDP brute-force, local account creation & querying telemetry via Splunk SPL. | [`active-directory-incident-response`](https://github.com/Pranav-Poornachandra-S/active-directory-incident-response) |
| **Detection Engineering, SOAR & EDR** | Custom YAML D&R rules for `LaZagne` execution & host telemetry. Automated Slack/Email alerts with interactive network isolation prompts. | [`soar-edr-security-automation`](https://github.com/Pranav-Poornachandra-S/soar-edr-security-automation) |
| **Web Application Pentesting** | Exploiting SQLi, Broken Access Control, DOM XSS on OWASP Juice Shop. | [`owasp-juice-shop-security-assessment`](https://github.com/Pranav-Poornachandra-S/owasp-juice-shop-security-assessment) |
| **Applied Cryptography & Web Security** | Byte-level AES-256-CFB file encryption and short-lived buffer cleanup in Flask. | [`secure-file-sharing-flask-aes`](https://github.com/Pranav-Poornachandra-S/secure-file-sharing-flask-aes) |
| **Command-Line Security Utilities** | OpenSSL-backed random password generation and symmetric GPG file protection. | [`password-generator-bash`](https://github.com/Pranav-Poornachandra-S/password-generator-bash) <br> [`file-encryptor-decryptor-bash`](https://github.com/Pranav-Poornachandra-S/file-encryptor-decryptor-bash) </br> |

---

## Featured Security Projects

### [Active Directory Incident Response](https://github.com/Pranav-Poornachandra-S/active-directory-incident-response)
* **Tech Stack:** `Active Directory` `Splunk Enterprise` `Sysmon` `Atomic Red Team` `Linux`
* Implemented an enterprise Active Directory domain (adir.local) with Windows Server 2022, Windows 10 endpoints and Sysmon event collection.
* Simulated RDP password spraying via Crowbar and automated local account persistence using Atomic Red Team (T1136.001).
* Configured Splunk Enterprise & Splunk Universal Forwarders to write targeted SPL queries for detecting brute-force and unauthorized user account creation.

### [SOAR EDR Security Automation](https://github.com/Pranav-Poornachandra-S/soar-edr-security-automation)
* **Tech Stack:** `LimaCharlie EDR` `Tines SOAR` `YAML` `Slack API`
* Built an automated incident response pipeline connecting LimaCharlie EDR to Tines SOAR.
* Authored custom Detection & Response (D&R) rules to identify credential harvesting (LaZagne.exe) and automated one-click host network isolation via Slack prompts.

### [OWASP Juice Shop Security Assessment](https://github.com/Pranav-Poornachandra-S/owasp-juice-shop-security-assessment)
* **Tech Stack:** `Burp Suite` `Gray Box Pentesting` `OWASP Top 10`
* Conducted a Gray Box security assessment identifying 5 critical/high vulnerabilities including SQL Injection, Broken Access Control and DOM XSS.
* Authored a professional security report complete with risk ratings, proof-of-concept evidence and remediation steps.

### [Secure File Sharing System](https://github.com/Pranav-Poornachandra-S/secure-file-sharing-flask-aes)
* **Tech Stack:** `Python` `Flask` `PyCryptodome` `Bootstrap 5`
* Developed an end-to-end web portal executing client file encryption using AES-256-CFB prior to disk storage.
* Features automated 60-second temporary buffer cleanup to reduce server-side data exposure.

### [GPG File Encryptor & Decryptor](https://github.com/Pranav-Poornachandra-S/file-encryptor-decryptor-bash)
* **Tech Stack:** `Bash` `GnuPG (GPG)` `Linux`
* CLI utility automating symmetric passphrase encryption and decryption using GPG.
* Includes defensive file validation to prevent script execution failures.

### [OpenSSL Password Generator](https://github.com/Pranav-Poornachandra-S/password-generator-bash)
* **Tech Stack:** `Bash` `OpenSSL` `Linux`
* Command-line password generator leveraging cryptographically secure random number generator (CSRNG) for cryptographic entropy.
* Validates length parameters and generates 5 high-entropy password options per run.

---
