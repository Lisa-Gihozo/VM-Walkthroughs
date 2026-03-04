# VM Walkthrough: Mr. Photographer (VulnHub)
**Severity Rating:** Critical (CVSS 9.0)  
**Objective:** Gain root access and retrieve the user and root flags.

### 🛡️ Vulnerability Overview
This machine highlights the risks of outdated Content Management Systems (CMS) and insecure sudo permissions.

* **Information Disclosure:** Sensitive credentials found via site metadata/source.
* **Exploitation:** Remote Code Execution (RCE) via Koken CMS vulnerability.
* **Privilege Escalation:** Insecure Sudo permissions on the `php` binary.

### 🛠️ Tools Used
* **Recon:** Nmap, Nikto
* **Exploitation:** Metasploit (or manual PHP shell upload)
* **Privilege Escalation:** GTFOBins (PHP Sudo breakout)
