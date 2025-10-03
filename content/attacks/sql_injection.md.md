

---
title: "SQL Injection"
date: 2025-10-03
---

# SQL Injection (SQLi)  

**SQL Injection** is a web attack where attackers insert malicious SQL queries into input fields to gain unauthorized access to a database.  

## How It Works  
- User input is not properly validated.  
- Attackers insert SQL commands (`' OR '1'='1`) into login forms.  
- The database executes the command, exposing data.  

## Example  
An attacker enters this into a login field:  


This trick can bypass authentication if not protected.  

## Prevention  
- Use **prepared statements** and parameterized queries.  
- Sanitize all user inputs.  
- Employ web application firewalls (WAFs).  

---
**See also:** [Phishing](phishing.md) | [Encryption](../defenses/encryption.md)  
