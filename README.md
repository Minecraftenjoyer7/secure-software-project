# secure-software-project
| Name                       | ID      |
| -------------------------- | ------- |
| **Youssef Hassan Youssef** | 2305049 |
| **Youssef Ahmed**          | 2305048 |
| **Mina Ayman**             | 2305073 |

# Project Overview

This project is a deliberately vulnerable Node.js + Express web application designed for educational purposes.
The goal is to identify, exploit, analyze, and document security vulnerabilities based on the OWASP Top 10 (2021) list.
The application includes multiple intentional weaknesses such as:
- Broken Access Control
- Injection vulnerabilities (SQL Injection, XSS, SSTI)
- Insecure Design flaws
- Security Misconfigurations


# Static Analysis
This project includes custom Semgrep rules to detect:
- SQL Injection
- Reflected XSS
- Server-Side Template Injection (SSTI)
- Verbose error messages
- Debug logging in production
These rules demonstrate how static analysis tools can assist in identifying insecure patterns in source code.

# Vulnerabilities Covered (OWASP Top 10 – 2021)
| ID  | Vulnerability               | Status         |
| --- | --------------------------- | -------------- |
| A01 | Broken Access Control       | ✔️ Implemented |
| A02 | Cryptographic Failures      | ✔️ Implemented |
| A03 | Injection (SQLi, XSS, SSTI) | ✔️ Implemented |
| A04 | Insecure Design             | ✔️ Implemented |
| A05 | Security Misconfiguration   | ✔️ Implemented |
