# SQL Injection Analysis – Web Application Penetration Testing

## 🔍 Project Overview
This project demonstrates the discovery and exploitation of SQL Injection (SQLi) vulnerabilities in a deliberately insecure web application for educational purposes.

## 🛠️ Tools Used
- Burp Suite Community Edition
- sqlmap
- Firefox/Chrome browser
- DVWA / Mutillidae (Lab environment)

## 🧪 Methodology
1. Identified vulnerable input fields using Burp Suite (intercepted login requests).
2. Performed manual SQLi payloads to bypass login authentication.
3. Used `sqlmap` to automate extraction of:
   - Database names
   - Tables
   - Records (usernames, passwords)
4. Documented findings with screenshots and output logs.

## 📁 Project Files
- `burp-suite-screenshots/` – Contains request/response screenshots.
- `sqlmap-logs/` – Outputs and extracted database structure.
- `manual-sqli/` – Steps to reproduce the manual SQL injection.
- `reports/` – Final PDF report of the entire testing process.
- `legal-disclaimer.txt` – This was done in a controlled environment for training only.

## ⚠️ Legal Disclaimer
All testing was performed in a safe, controlled environment (offline lab). This project is strictly for educational purposes only.

## 📚 Author
**Arvind** – Cybersecurity Enthusiast | Ethical Hacker
