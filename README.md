# Hi, I'm Aditya Halbe 👋

DevSecOps & Cloud Security Engineer — I build and secure 
production systems on AWS.

🌐 pyshala.in | 📧 halbeadi@gmail.com
🔗 linkedin.com/in/aditya-halbe

---

## 🛡️ Security Projects

### 🔐 Pyshala — Secure Python Learning Platform
Live Django platform on AWS EC2 with full DevSecOps pipeline.
- Hardened Docker image (non-root user, slim base) — eliminated 
  2 HIGH Django CVEs via Trivy scanning
- Nginx security headers (Grade A), Fail2Ban, rate limiting, 
  CloudTrail logging
- Bandit SAST + Trivy container scan in GitHub Actions CI/CD

🔗 pyshala.in | github.com/halbeadi/pyshala

---

### ☁️ Terraform AWS Infrastructure + tfsec
IaC for Pyshala AWS infrastructure with security scanning.
- Found 3 CRITICAL misconfigurations via tfsec
- Fixed S3 encryption, access logging, and security group issues
- tfsec integrated into GitHub Actions CI/CD

🔗 github.com/halbeadi/terraform-pyshala

---

### 🔍 AWS Security Auditor
Python/Boto3 tool to detect AWS misconfigurations.
- Detected real HIGH severity finding on live EC2 (public SSH 
  0.0.0.0/0) and remediated it
- Audits IAM, S3, EC2, and CloudTrail

🔗 github.com/halbeadi/aws-auditor

---

### 🕷️ Web Vulnerability Scanner
Python CLI tool for web application security testing.
- Detects SQLi, XSS, missing headers, sensitive file exposure
- Found 23 vulnerabilities (14 HIGH) during testing
- Automated HTML report generation

🔗 github.com/halbeadi/web-vuln-scanner

---

## 🧰 Tech Stack

**Cloud:** AWS (EC2, S3, IAM, VPC, CloudTrail, GuardDuty)  
**IaC:** Terraform, tfsec  
**DevSecOps:** GitHub Actions, Bandit, Trivy, OWASP ZAP  
**Security:** Burp Suite, Nmap, DVWA, OWASP Top 10  
**Languages:** Python, Bash  
**Stack:** Django, Gunicorn, Nginx, PostgreSQL, Docker  

---

## 📜 Certifications

- CEH — EC-Council (Renewal in Progress)

---

## 📫 Connect

🔗 [LinkedIn](https://linkedin.com/in/aditya-halbe) | 
📧 halbeadi@gmail.com