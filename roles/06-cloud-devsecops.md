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

## 🚀 Phase 1: Cloud & Infrastructure Fundamentals

| # | Room Name | Difficulty | Est. Time | Direct Link | Primary Skill / Learning Objective |
|---|-----------|------------|-----------|-------------|-----------------------------------|
| 1 | **Virtualization and Containers** | Easy | 45 mins | [Access THM](https://tryhackme.com/room/virtualizationandcontainers) | Cloud service models, Docker & container concepts |
| 2 | **Intro to IaC** | Easy | 1 hr | [Access THM](https://tryhackme.com/room/introtoiac) | Infrastructure as Code basics, Terraform fundamentals |
| 3 | **Cluster Hardening** | Easy | 1 hr | [Access THM](https://tryhackme.com/room/clusterhardening) | Cloud misconfigurations & Kubernetes network hardening |

---

## 🐳 Phase 2: Container Security & Kubernetes

| # | Room Name | Difficulty | Est. Time | Direct Link | Primary Skill / Learning Objective |
|---|-----------|------------|-----------|-------------|-----------------------------------|
| 4 | **Virtualization and Containers** | Easy/Medium | 1.5 hrs | [Access THM](https://tryhackme.com/room/virtualizationandcontainers) | Container escape vulnerabilities, Docker isolation |
| 5 | **Intro to Kubernetes** | Medium | 1.5 hrs | [Access THM](https://tryhackme.com/room/introkubernetes) | Pods, Deployments, RBAC, API Server security |
| 6 | **K8s Best Security Practices** | Medium | 2 hrs | [Access THM](https://tryhackme.com/room/k8sbestsecuritypractices) | Exploiting misconfigured Docker sockets and API endpoints |

---

## 🔒 Phase 3: DevSecOps & Pipeline Security

| # | Room Name | Difficulty | Est. Time | Direct Link | Primary Skill / Learning Objective |
|---|-----------|------------|-----------|-------------|-----------------------------------|
| 7 | **Intro to DevSecOps** | Easy | 1 hr | [Access THM](https://tryhackme.com/room/introdevsecops) | Integrating security into DevOps (Shift Left), SAST vs DAST |
| 8 | **Source Code Analysis** | Medium | 1.5 hrs | [Access THM](https://tryhackme.com/room/sourcecodeanalysis) | Static Application Security Testing (SAST) & code auditing |
| 9 | **Secret Scanning** | Easy | 45 mins | [Access THM](https://tryhackme.com/room/secretscanning) | Finding leaked API keys, tokens, and credentials in Git |

---

## 💻 Recommended Portfolio Projects for DevSecOps
1. **GitHub Actions Security Pipeline:** Build a GitHub Actions workflow that automatically scans pull requests using Trivy (containers), Semgrep (SAST), and TruffleHog (secret scanning).
2. **Terraform IaC Security Audit:** Create misconfigured Terraform scripts and demonstrate automated remediation using Checkov/tfsec.
