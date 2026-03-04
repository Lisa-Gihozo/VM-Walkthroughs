# VM Walkthrough: Skydog CTF
**Severity Rating:** High (CVSS 8.2)  
**Objective:** Navigate a multi-stage puzzle to recover credentials and gain system access.

### 🛡️ Vulnerability Overview
This challenge focuses heavily on web-based reconnaissance and the exploitation of common misconfigurations in web applications.

* **Broken Access Control:** Hidden directories and files accessible via poor configuration.
* **Credential Stuffing/Cracking:** Use of custom wordlists and brute-force techniques.
* **Insecure Communication:** Discovery of sensitive data via HTTP headers/source code.

### 🛠️ Tools Used
* **Recon:** Nmap, Nikto, Gobuster
* **Web Analysis:** Browser Developer Tools
