# Web Application & Network Security Audit
Final Year B.Sc. Cyber Security Project  
June 2025  
 


## 🔒 Project Overview
This project focuses on identifying, analyzing, and mitigating vulnerabilities across both web applications and network infrastructures. Using industry-standard methodologies and tools, it provides a comprehensive security audit to improve an organization’s overall cyber resilience.

## 📌 Objectives
- Perform Web Application Penetration Testing (WAPT)
- Conduct Network Vulnerability Assessment and Penetration Testing (VAPT)
- Simulate real-world attack scenarios
- Document vulnerabilities and provide remediation strategies

## 🧪 Methodology
The testing approach followed standard phases:
- 🔎 Information Gathering
- 🛡️ Vulnerability Detection
- ⚔️ Exploitation & Privilege Escalation
- 📊 Risk Analysis & Reporting

## 🛠️ Tools Used
- **Nmap** – Network mapping and port scanning
- **Nessus** – Network vulnerability scanner
- **Burp Suite** – Web vulnerability scanner and HTTP interception
- **OWASP ZAP** – Web application security scanner
- **Advanced IP Scanner** – Host detection
- **Wireshark** – Network traffic analysis
- **Kali Linux** – Operating environment

## 🔍 Key Vulnerabilities Identified
### Web Application (WAPT)
- Full account takeover via password reset
- Cleartext password transmission (no HTTPS)
- Broken CAPTCHA allowing brute-force
- EXIF data leakage from uploaded images
- Cross-Domain Script Inclusion (XSSI)
- Improper error handling & debug info leakage
- Concurrent login without session restrictions

### Network (VAPT)
- Outdated Dropbear SSH vulnerable to RCE (CVE-2016-7406+)
- SSL 2.0/3.0 enabled – vulnerable to POODLE attack
- DNS Cache Snooping
- Self-signed or untrusted SSL certificates
- RC4 Cipher support (weak encryption)

## 📑 Standards Followed
- **OWASP Top 10 – 2021**
- **CVSS v3.1 Scoring**
- **Risk Level Categorization (Critical, High, Medium, Low, Informational)**

## 📈 Results
Each vulnerability was documented with:
- Proof of Concept (PoC)
- Risk level (CVSS)
- Impact and exploitation analysis
- Recommended solutions for mitigation

## 📚 Report
The full project report includes:
- Executive summary  
- Tools and techniques used  
- Screenshots and findings  
- Detailed analysis and remediation steps

---

## 👩‍💻 Author
**Mrittika Debnath**  
Cybersecurity Enthusiast | RHCSA Certified | Passionate about Cloud & Network Security

---

## 🏷️ Tags
`Cybersecurity` `VAPT` `WAPT` `OWASP` `Nmap` `BurpSuite` `Nessus` `Linux` `NetworkSecurity` `WebSecurity`  `KaliLinux`

