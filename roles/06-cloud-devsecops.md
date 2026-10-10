# ☁️ Cloud Security & DevSecOps Roadmap (100% Free Labs)

> **Role Overview:** Cloud Security & DevSecOps Engineers integrate security controls into CI/CD pipelines, secure cloud infrastructure (AWS, Azure, GCP), enforce IAM policies, monitor container deployments (Docker/Kubernetes), and automate compliance checks.

---

## 🎯 Key Competencies & Skill Matrix

```
       [ Cloud Fundamentals ]  ──────────► ( AWS IAM, S3 Bucket Security, Azure AD )
                 │
       [ Container Security ]  ──────────► ( Docker Bench Security, Kubernetes Hardening )
                 │
       [ DevSecOps & CI/CD ]   ──────────► ( SAST, DAST, Secret Scanning, Git Hooks )
                 │
       [ Infrastructure as Code]─────────► ( Terraform Security, Trivy, Checkov )
```

---

## 🎓 Aligned Industry Certifications
- **AWS Certified Security - Specialty**
- **Microsoft Certified: Azure Security Engineer** (AZ-500)
- **Certified Kubernetes Security Specialist** (CKS)
- **Certified DevSecOps Professional** (CDP)

---

## 🚀 Phase 1: Cloud Security Fundamentals

| # | Room Name | Difficulty | Est. Time | Direct Link | Primary Skill / Learning Objective |
|---|-----------|------------|-----------|-------------|-----------------------------------|
| 1 | **Intro to Cloud** | Easy | 45 mins | [Access THM](https://tryhackme.com/room/introcloud) | Cloud service models (IaaS, PaaS, SaaS) & shared responsibility |
| 2 | **Intro to AWS** | Easy | 1 hr | [Access THM](https://tryhackme.com/room/awsintro) | AWS console navigation, EC2, S3, IAM user setup |
| 3 | **Cloud Security Intro** | Easy | 1 hr | [Access THM](https://tryhackme.com/room/cloudsecurityintro) | Cloud misconfigurations, public S3 buckets, IAM privilege leaks |

---

## 🐳 Phase 2: Container Security & Kubernetes

| # | Room Name | Difficulty | Est. Time | Direct Link | Primary Skill / Learning Objective |
|---|-----------|------------|-----------|-------------|-----------------------------------|
| 4 | **Docker Security** | Easy/Medium | 1.5 hrs | [Access THM](https://tryhackme.com/room/dockersecurity) | Container escape vulnerabilities, non-root users, Trivy scans |
| 5 | **Kubernetes Fundamentals** | Medium | 1.5 hrs | [Access THM](https://tryhackme.com/room/kubernetes) | Pods, Deployments, RBAC, API Server security |
| 6 | **Container Vulnerabilities** | Medium | 2 hrs | [Access THM](https://tryhackme.com/room/containervulnerabilities) | Exploiting misconfigured Docker sockets and API endpoints |

---

## 🔒 Phase 3: DevSecOps & Pipeline Security

| # | Room Name | Difficulty | Est. Time | Direct Link | Primary Skill / Learning Objective |
|---|-----------|------------|-----------|-------------|-----------------------------------|
| 7 | **DevSecOps Intro** | Easy | 1 hr | [Access THM](https://tryhackme.com/room/devsecopsintro) | Integrating security into DevOps (Shift Left), SAST vs DAST |
| 8 | **Source Code Analysis** | Medium | 1.5 hrs | [Access THM](https://tryhackme.com/room/sourcecodeanalysis) | Static Application Security Testing (SAST) & code auditing |
| 9 | **Secret Scanning** | Easy | 45 mins | [Access THM](https://tryhackme.com/room/secretscanning) | Finding leaked API keys, tokens, and credentials in Git |

---

## 💻 Recommended Portfolio Projects for DevSecOps
1. **GitHub Actions Security Pipeline:** Build a GitHub Actions workflow that automatically scans pull requests using Trivy (containers), Semgrep (SAST), and TruffleHog (secret scanning).
2. **Terraform IaC Security Audit:** Create misconfigured Terraform scripts and demonstrate automated remediation using Checkov/tfsec.
