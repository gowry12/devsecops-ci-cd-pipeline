# DevSecOps Secure CI/CD Pipeline

Secure CI/CD pipeline project integrating automated security testing tools with a vulnerable Flask application.

---

# Overview

This project demonstrates a secure DevSecOps pipeline using:

- GitLab CI/CD
- Semgrep (SAST)
- Gitleaks (Secret Scanning)
- Wapiti (DAST)
- Docker
- Flask
- SQLite

The pipeline performs automated security testing during application deployment.

---

# Architecture Flow

Developer → GitLab CI/CD → Security Scans → Vulnerability Detection → Reports

---

# Security Testing Implemented

## SAST
- Semgrep static analysis

## Secret Scanning
- Gitleaks detection

## DAST
- Wapiti runtime testing

## Manual Testing
- SQL Injection
- XSS
- IDOR
- Authentication Testing

---

# Vulnerabilities Demonstrated

| Vulnerability | Severity |
|---|---|
| SQL Injection | Critical |
| Hardcoded Secrets | Critical |
| XSS | High |
| IDOR | High |
| Broken Authentication | High |
| Missing Security Headers | Medium |

---

# Technologies Used

| Tool | Purpose |
|---|---|
| Flask | Web Application |
| GitLab CI/CD | Pipeline Automation |
| Semgrep | SAST |
| Gitleaks | Secret Detection |
| Wapiti | DAST |
| Docker | Containerization |

---

# Key Learning Outcomes

- Secure CI/CD implementation
- Automated security testing
- Vulnerability assessment
- OWASP Top 10 testing
- DevSecOps workflows
- Container security basics

---

# Reports

- VAPT Report
- DAST Scan Report
- CI/CD Pipeline Documentation

---

# Author

Gowry N  
Cybersecurity Enthusiast | SOC Analyst Aspirant
