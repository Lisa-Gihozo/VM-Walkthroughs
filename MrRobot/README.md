# VM Walkthrough: Mr. Robot (VulnHub / TryHackMe)
**Severity Rating:** High (CVSS 8.5)  
**Objective:** Capture hidden flag

### 🛡️ Vulnerability Overview
This machine simulates a multi-stage compromise starting from public information disclosure and leading to root access via legacy binary exploitation.

* **Information Disclosure:** Sensitive files leaked via `robots.txt`.
* **Broken Authentication:** WordPress admin panel accessible via brute-force.
* **Privilege Escalation:** Exploitation of SUID bit on a legacy `nmap` binary.

### 🛠️ Tools Used
* **Recon:** Nmap, Dirb
* **Cracking:** Hydra
* **Exploitation:** Python PTY, Netcat
