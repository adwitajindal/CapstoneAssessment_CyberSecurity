# Cybersecurity Capstone Project: VAPT Report

## Overview

This repository contains a comprehensive **Vulnerability Assessment and Penetration Testing (VAPT) Report** for a cybersecurity capstone project conducted as part of the Paytm Payments Services cybersecurity training program in partnership with Zell Education and Chitkara University.

**Project Team:** SecureOps  
**Report Date:** April 20, 2026  
**Document ID:** CAPSTONE-VAPT-001 (v1.0)  
**Prepared by:** Adwita Jindal  
**Reviewed by:** Mukesh Chaudhari (Instructor)

---

## Project Scope

This capstone project focuses on conducting a real-world security audit of intentionally vulnerable web applications used for educational purposes:

### Target Applications

| Application | Criticality | URL | Type |
|-------------|-------------|-----|------|
| AltoroMutual Demo Bank | High | https://demo.testfire.net | Web Application |
| Zero Web App Security | High | http://zero.webappsecurity.com | Web Application |

---

## Key Areas of Assessment

### In Scope
- Authentication mechanisms (login, session management)
- Input validation (SQL injection, XSS, command injection)
- Access control (IDOR, privilege escalation, path traversal)
- Session management (timeout, concurrent sessions, token security)
- Security headers and configuration
- Error handling and information disclosure

### Out of Scope
- Denial of Service (DoS) attacks
- Social engineering
- Physical security
- Network infrastructure testing
- Server-side code review (black-box testing only)

---

## Project Structure

```
CapstoneProject_CyberSecurity/
├── README.md                      # This file
├── Capstone_VAPT_Report.md        # Comprehensive VAPT report
└── POC/                           # Proof-of-concept screenshots
    ├── poc1.png
    ├── poc2.png
    ├── poc3.png
    ├── poc4.png
    ├── poc5.png
    └── poc6.png
```

---

## Methodology

The assessment followed the **OWASP Testing Guide v4** methodology with the following phases:

### Phase 1: Information Gathering
- Identified target URLs and application features
- Mapped the attack surface (login, search, transfer, feedback, bill pay)
- Identified technologies and server headers

### Phase 2: Automated Scanning
- Configured Burp Suite Community Edition proxy for HTTP traffic interception
- Built site map by browsing all application features
- Reviewed HTTP history for interesting endpoints and parameters

### Phase 3: Manual Testing
- Conducted targeted testing for identified vulnerability classes
- Documented proof-of-concept evidence for each finding
- Assessed business impact and severity

---

## Tools Used

- **Burp Suite Community Edition** - Web application vulnerability scanner and proxy
- **Manual Testing Techniques** - OWASP Top 10 vulnerability assessment

---

## Key Findings

The report identifies and documents:
- **Authentication & Session Management Vulnerabilities**
- **Input Validation Issues** (SQL Injection, XSS, Command Injection)
- **Access Control Flaws** (IDOR, Privilege Escalation, Path Traversal)
- **Security Header Misconfigurations**
- **Information Disclosure Vulnerabilities**

Each finding includes:
- Vulnerability description
- Severity classification
- Proof-of-concept evidence (screenshots in POC folder)
- Business impact assessment
- Remediation recommendations

---

## Document Contents

### Capstone_VAPT_Report.md

The comprehensive report includes:
1. **Introduction** - Project background and objectives
2. **Engagement Scope** - In-scope and out-of-scope items
3. **Assessment Methodology** - OWASP-based testing phases
4. **Tools Used** - Technologies employed
5. **Executive Summary** - High-level findings and risk overview
6. **Detailed Observations** - In-depth vulnerability analysis
7. **Recommendations Summary** - Remediation guidance
8. **Appendix: Screenshots** - Proof-of-concept evidence

---

## Proof of Concept (POC)

The `POC/` folder contains 6 screenshot evidence files demonstrating:
- Vulnerability exploitation techniques
- Real-world attack scenarios
- Impact demonstration

These screenshots serve as visual proof-of-concept for each documented vulnerability.

---

## Report Format & Compliance

This report follows:
- **CERT-In Audit Report Format** - Indian cybersecurity standards
- **OWASP Testing Guide v4 Methodology** - Industry best practices
- **Professional Penetration Testing Standards** - Enterprise-grade reporting

---

## Educational Context

This capstone project demonstrates comprehensive knowledge of:
- Cryptography fundamentals
- Web security principles
- OWASP Top 10 vulnerabilities
- Ethical hacking techniques
- Regulatory compliance requirements
- Professional penetration testing methodology

---

## Important Notes

⚠️ **Legal & Ethical Considerations:**
- Testing was conducted on publicly available demo/training applications
- All applications are intentionally vulnerable for educational purposes
- Testing was performed with proper authorization
- Findings reflect the application state at the time of testing (April 20, 2026)

---

## Usage

1. Review the [Capstone_VAPT_Report.md](Capstone_VAPT_Report.md) for the complete assessment details
2. Examine the [POC/](POC/) folder for evidence screenshots
3. Use findings for:
   - Educational reference
   - Security awareness training
   - Understanding common web application vulnerabilities
   - Learning penetration testing methodology

---

## Contact & Attribution

**Prepared by:** Adwita Jindal  
**Reviewed by:** Mukesh Chaudhari (Instructor)  
**Organization:** Paytm Payments Services x Zell Education x Chitkara University  
**Report Version:** 1.0 (April 20, 2026)

---

## Disclaimer

This report is provided for educational purposes only. The methodologies and findings documented here should only be applied to systems you own or have explicit permission to test. Unauthorized access to computer systems is illegal.

---

**Last Updated:** April 20, 2026  
**Document ID:** CAPSTONE-VAPT-001
