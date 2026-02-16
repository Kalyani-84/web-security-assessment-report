# Web Application Security Assessment

## Overview
This repository contains a structured manual security assessment of the intentionally vulnerable web application "Hack Yourself First".

The objective of this project was to identify common web application security weaknesses using manual testing techniques and document the findings in a professional security report format.

---

## Scope of Testing
The assessment included testing of publicly accessible features of the application, focusing on:

- Access control mechanisms
- Authentication functionality
- Input validation
- Error handling behavior
- Security configuration and HTTP headers

Testing was performed in a controlled environment without destructive techniques.

---

## Methodology

The following manual testing techniques were used:

1. Application mapping and reconnaissance
2. URL parameter manipulation
3. Access control testing
4. Input validation testing
5. Error message analysis
6. HTML source review

No automated vulnerability scanners were used.

---

## Findings Summary

Total vulnerabilities identified: **16**

- High Severity: 2  
- Medium Severity: 8  
- Low Severity: 6  

### Key High-Severity Issues
- Insecure Direct Object Reference (IDOR)
- User Enumeration via Registration Errors

---

## Security Impact

The identified vulnerabilities demonstrate real-world risks such as:

- Unauthorized data access
- Account enumeration
- Exposure to injection risks
- Missing security controls
- Increased attack surface

---

## Tools Used
- Manual browser testing
- HTTP request manipulation
- Developer tools for response inspection

---

## Full Report

A redacted version of the complete professional security assessment report is available below:

[Download Report](./Web_Application_Security_Assessment_Redacted.pdf)

---

## Key Learning Outcomes

- Practical understanding of broken access control vulnerabilities
- Experience with structured vulnerability reporting
- Improved knowledge of attack surface analysis
- Hands-on exposure to real-world web security issues

---

## Ethical Notice
This assessment was conducted strictly for educational purposes on an intentionally vulnerable application in a controlled lab environment.
