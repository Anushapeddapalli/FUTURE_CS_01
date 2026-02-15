# FUTURE_CS_01
# Vulnerability Assessment Report

## Overview  
This repository contains a Vulnerability Assessment Report created as part of an internship and learning task. The assessment was performed on a public demo website using a read-only approach to identify visible security weaknesses and document them in a clear and professional manner.

The final report is designed in Canva and exported as a PDF, along with supporting screenshots and tool outputs.

## Target Website  
- Public test website (OWASP Juice Shop)  
- Assessment Type: Read-only vulnerability assessment

## Tools Used  
- **Nmap** – Used to identify exposed services and open ports  
- **OWASP ZAP** – Used to scan the web application for security issues using passive scanning, Spider, and AJAX Spider

## Scope of the Assessment  
The scope includes identifying exposed services, checking for missing security headers, detecting visible configuration issues, and finding outdated components where possible. No exploitation or active attacks were performed.

## Summary of Findings  
The assessment identified several security issues, mainly related to missing security configurations and outdated components. Key findings include missing Content Security Policy (CSP), session IDs exposed in URLs, vulnerable JavaScript libraries, missing security headers, and information disclosure issues. These issues can weaken the security of a real-world application if not fixed.

## Repository Contents  
- **Report.pdf** – Final report  
- **Screenshots/** – Supporting evidence  
- **README.md** – Project description
