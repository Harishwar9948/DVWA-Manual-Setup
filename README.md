# DVWA Manual Setup – Kali Linux

This repository documents the complete step-by-step **manual installation and configuration** of the **Damn Vulnerable Web Application (DVWA)** on Kali Linux. This project demonstrates my ability to set up vulnerable environments for practicing web application penetration testing.

---

## Objectives

- Manually install and configure DVWA from scratch
- Set up required services: Apache, MySQL, PHP
- Modify config files to run DVWA correctly
- Learn about security levels in DVWA and their purpose
- Create a secure and functional pentest environment

---

## Tools & Tech Stack

- Kali Linux (as host OS)
- DVWA (cloned from GitHub)
- Apache2 (web server)
- MySQL / MariaDB (database server)
- PHP 7.x

---

## Steps Covered

1. Update & install required packages
2. Configure Apache and MySQL
3. Clone DVWA repo
4. Set DB credentials in `config.inc.php`
5. Grant DB permissions to DVWA user
6. Restart services and verify setup
7. Access DVWA through `http://localhost/dvwa`
8. Set security level and test vulnerabilities

---

## Files Included

- `Installation and Configuration of DVWA on Kali Linux VM.pdf`  
  → Contains detailed steps with screenshots

---

## Learning Outcomes

- Practical knowledge of Linux web server configuration
- Understanding DVWA’s structure and backend setup
- Ability to troubleshoot Apache/PHP/DB errors
- Secure vulnerable environments for hands-on pentesting

---

## Disclaimer

This environment is intentionally insecure and must be run in a **controlled lab setup only**.  
DVWA is designed for ethical hacking and cybersecurity training.  
**Never expose it to the internet or real-world networks.**

---

## Next Steps

- Begin vulnerability exploitation using DVWA modules
- Integrate Burp Suite for manual testing
- Practice OWASP Top 10 in a lab environment
