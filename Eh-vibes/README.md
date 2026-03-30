# VM Walkthrough: Eh-vibes
**Severity Rating:** Critical (CVSS 9.8)  
**Objective:** Capture 2 flags.

### 🛡️ Vulnerability Overview
This lab focuses on the exploitation of a misconfigured cron job and capturing 2 flags.

* **Information Disclosure:** Sensitive folder locations revealed via `robots.txt`.
* **Remote Code Execution (RCE):** Unrestricted file upload allows for PHP shell execution.
* **Misconfigured Cron job:** Allows payload injection in misconfigured cron job

### 🛠️ Tools Used
* **Recon:** Nmap, Nikto, Gobuster
* **Web Exploitation:** PUT method
* **Post-Exploitation:** Netcat (Reverse Shell), Python PTY, Payload injection in misconfigured cron job 
