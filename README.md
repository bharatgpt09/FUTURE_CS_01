# FUTURE_CS_01
Security testing using Burp Suite and SQLMap to identify SQLi, XSS, and authentication flaws.
# Web Application Security Testing

This repository contains documentation and evidence of a hands-on security testing task using *Burp Suite* and *SQLMap* on a legal test site:  
🔗 http://testphp.vulnweb.com

## 🔧 Tools Used
- *Burp Suite Community Edition*
- *SQLMap*
- *Kali Linux*
- *Browser (configured for Burp proxy)*

## 🛡 Vulnerabilities Tested

### 🔸 SQL Injection (SQLi)
- Tested GET parameter artist=1 using SQLMap
- Discovered and enumerated databases (acuart, mysql, etc.)
- Dumped tables like users

### 🔸 Cross-Site Scripting (XSS)
- Injected payloads like <script>alert(1)</script> into query parameters
- Verified reflected XSS on search.php

### 🔸 Authentication Flaws
- Identified login page at login.php
- Performed brute-force test using Burp Intruder
- Observed no account lockout or rate limiting

## 📁 Project Structure
