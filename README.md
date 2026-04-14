# Hi, I'm Aditya Halbe 👋
DevSecOps & Cloud Security Engineer — I build and secure  
production systems on AWS.

🌐 [pyshala.in](https://pyshala.in) | 📧 halbeadi@gmail.com  
🔗 [linkedin.com/in/aditya-halbe](https://linkedin.com/in/aditya-halbe)

---

## 🛡️ Security Projects

### 🔐 Pyshala — Secure Python Learning Platform
Live Django platform on AWS EC2 with full DevSecOps pipeline.
- Hardened Docker image (non-root user, slim base) — eliminated 2 HIGH Django CVEs via Trivy scanning
- Nginx security headers (Grade A), Fail2Ban, rate limiting, CloudTrail logging
- Bandit SAST + Trivy container scan in GitHub Actions CI/CD (~46s deploys)

🔗 [pyshala.in](https://pyshala.in) | [github.com/halbeadi/pyshala](https://github.com/halbeadi/pyshala)

---

### ☁️ Terraform AWS Infrastructure + tfsec
IaC for Pyshala AWS infrastructure with security scanning.
- Found 3 CRITICAL misconfigurations via tfsec — all remediated
- Fixed S3 encryption (AES256), access logging, and public access blocking
- tfsec gating integrated into GitHub Actions CI/CD

🔗 [github.com/halbeadi/terraform-pyshala](https://github.com/halbeadi/terraform-pyshala)

---

### 🤖 AI-Powered AWS Security Auditor + Amazon Bedrock
Python/Boto3 auditor extended with LLM-powered analysis via Amazon Bedrock.
- Detected real HIGH severity finding on live EC2 (public SSH 0.0.0.0/0) and remediated it
- Audits IAM, S3, CloudTrail, and Security Groups
- Bedrock integration: AI risk scoring (1–10), step-by-step remediations, and dynamic check suggestions
- Least-privilege IAM scoped to exact Bedrock model ARN — not wildcard `*`

🔗 [github.com/halbeadi/aws-auditor](https://github.com/halbeadi/aws-auditor)

---

### 🕷️ Web Vulnerability Scanner
Python CLI tool for web application security testing.
- Detects SQLi, XSS, missing headers, sensitive file exposure
- Found 23 vulnerabilities (14 HIGH) during testing
- Automated HTML report generation

🔗 [github.com/halbeadi/web-vuln-scanner](https://github.com/halbeadi/web-vuln-scanner)

---

## 🧰 Tech Stack

**Cloud:** AWS (EC2, S3, IAM, VPC, CloudTrail, GuardDuty) | Azure (AZ-104, AZ-500 — in progress)  
**AI/LLM:** Amazon Bedrock, Amazon Nova  
**IaC:** Terraform, tfsec  
**DevSecOps:** GitHub Actions, Bandit, Trivy, OWASP ZAP  
**Security:** Burp Suite, Nmap, DVWA, OWASP Top 10, VirusTotal API  
**Languages:** Python, Bash  
**Stack:** Django, Gunicorn, Nginx, PostgreSQL, Docker  

---

## 📜 Certifications

- CEH — EC-Council (Renewal in Progress)
- AZ-104 Microsoft Azure Administrator — In Progress
- AZ-500 Microsoft Azure Security Engineer — In Progress

---

## 📫 Connect

🔗 [LinkedIn](https://linkedin.com/in/aditya-halbe) | 📧 halbeadi@gmail.com
