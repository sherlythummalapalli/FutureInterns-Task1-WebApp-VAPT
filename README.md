
# Task 1: Web Application VAPT

**Internship:** Future Interns  
**Target:** http://demo.testfire.net  
**Tools Used:** OWASP ZAP, Nmap

**Critical Vulnerabilities Found:**
1. **SQL Injection (CWE-89)** - Critical - Login bypass using `' OR '1'='1`
2. **Cross-Site Scripting (CWE-79)** - High - Payload executed in search field
3. **Missing Security Headers (CWE-693)** - Medium - X-Frame-Options, HSTS missing

**Methodology:** Recon → Automated Scan → Manual Validation → Reporting

**Files:** 
- `Task1_Report.pdf` - Detailed assessment report
- `/screenshots` - ZAP & Nmap proof

**Skills:** VAPT, OWASP Top 10, Risk Assessment, Technical Writing

**Disclaimer:** Performed on authorized test environment for educational purposes.
