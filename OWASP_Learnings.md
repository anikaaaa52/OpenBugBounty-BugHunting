# OWASP Learnings Summary

This file contains a basic summary of what I learned from OWASP Top 10 vulnerabilities.

## 1. XSS (Cross-Site Scripting)
XSS allows attackers to inject malicious JavaScript into webpages. It can be used to steal cookies, sessions, or redirect users. It often happens when user input is not properly sanitized.

## 2. SQL Injection (SQLi)
SQL Injection allows attackers to manipulate SQL queries through input fields. It can be used to view, modify, or delete data in the database. Common payload: `' OR 1=1 --`

## 3. Importance of Input Validation
Most web vulnerabilities are due to lack of input validation. It's important to sanitize and validate all user inputs to prevent attacks.

These are the first and most important vulnerabilities I learned about while preparing for my bug hunting project.
