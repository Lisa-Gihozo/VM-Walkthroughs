# VM Walkthrough: VulnUpload (JIS-CTF)
**Severity Rating:** Critical (CVSS 9.8)  
**Objective:** Recover 5 hidden flags by exploiting web vulnerabilities and escalating privileges.

### 🛡️ Vulnerability Overview
This lab focuses on the exploitation of insecure file upload handlers and the discovery of sensitive data via web enumeration.

* **Broken Access Control:** Hidden "flag" directory accessible without authentication.
* **Information Disclosure:** Sensitive folder locations revealed via `robots.txt`.
* **Remote Code Execution (RCE):** Unrestricted file upload allows for PHP shell execution.
* **Credential Flaw:** Plaintext credentials found in web-accessible files.

### 🛠️ Tools Used
* **Recon:** Nmap, Nikto
* **Web Exploitation:** Burp Suite, Browser DevTools
* **Post-Exploitation:** Netcat (Reverse Shell), Python PTY
