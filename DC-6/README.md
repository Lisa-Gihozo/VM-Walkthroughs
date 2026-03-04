# VM Walkthrough: DC-6 (VulnHub)
**Severity Rating:** High (CVSS 8.4)  
**Objective:** Escalate privileges from a web-user to root and retrieve the final flag.

### 🛡️ Vulnerability Overview
DC-6 focuses on the exploitation of an outdated CMS and the abuse of administrative scripts to gain higher privileges.

* **CMS Exploitation:** Vulnerability in a WordPress plugin (Plainview Activity Monitor).
* **Credential Discovery:** Brute-forcing a specific user identified through web enumeration.
* **Privilege Escalation:** Exploiting a `sudo` misconfiguration on a custom backup script.

### 🛠️ Tools Used
* **Recon:** Nmap, WPScan
* **Exploitation:** Metasploit / Python exploit scripts
* **Password Cracking:** Wpscan
* **Linux Internals:** Sudo, Bash scripting
