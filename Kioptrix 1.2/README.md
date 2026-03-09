# VM Walkthrough: Kioptrix 1.2

**Severity Rating**: Critical (CVSS 9.8)

**Objective**: Gain initial access through a vulnerable web application and escalate privileges from a web-user to root.

🛡️ Vulnerability Overview

Kioptrix 1.2 (Level 3) focuses on the exploitation of an abandoned CMS and an outdated operating system kernel to gain full system control.

* **CMS Exploitation**: Remote Code Execution (RCE) vulnerability in LotusCMS via the eval() function in the page parameter.
* **Privilege Escalation** : Decoding credentials found in phpMyAdmin after obtaining config file.

🛠️ Tools Used

* **Recon**: Nmap, Nikto

* **Exploitation**: Netcat

* **Payload Delivery**: Reverse shells (PHP)
