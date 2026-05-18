<!-- ═══════════════════════════════════════════════════════════════ -->
<!--           MANIKANDAN | GITHUB PROFILE README                  -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║     ██████╗ ███████╗██╗   ██╗ ██████╗ ██████╗ ███████╗     ║
║     ██╔══██╗██╔════╝██║   ██║██╔═══██╗██╔══██╗██╔════╝     ║
║     ██║  ██║█████╗  ██║   ██║██║   ██║██████╔╝███████╗     ║
║     ██║  ██║██╔══╝  ╚██╗ ██╔╝██║   ██║██╔═══╝ ╚════██║     ║
║     ██████╔╝███████╗ ╚████╔╝ ╚██████╔╝██║     ███████║     ║
║     ╚═════╝ ╚══════╝  ╚═══╝   ╚═════╝ ╚═╝     ╚══════╝     ║
║                                                              ║
║               C L O U D  &  D E V O P S  E N G I N E E R   ║
╚══════════════════════════════════════════════════════════════╝
```

</div>

---

<div align="center">

<!-- Typing SVG -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00D4FF&center=true&vCenter=true&width=600&lines=Cloud+%26+DevOps+Engineer+%F0%9F%9A%80;AWS+%7C+Kubernetes+%7C+Terraform+%E2%98%81%EF%B8%8F;CI%2FCD+Pipeline+Architect+%F0%9F%94%A7;Infrastructure+as+Code+Enthusiast+%F0%9F%8F%97%EF%B8%8F)](https://git.io/typing-svg)

</div>

---

## 🌐 About Me

```yaml
name:       Manikandan
location:   Chennai, India  🇮🇳
role:       Cloud & DevOps Engineer
experience: 1+ year in AWS production environments
focus:
  - Infrastructure Automation & IaC (Terraform)
  - Container Orchestration (EKS / Kubernetes)
  - CI/CD Pipeline Design (Jenkins, GitHub Actions)
  - Serverless & Cloud Migrations
  - Security Operations & Incident Response
currently:  @ Blackdart Labs Private Limited
contact:    manikandanpro2020@gmail.com
```

---

## ⚡ Tech Arsenal

### ☁️ Cloud Platforms
<p>
  <img src="https://img.shields.io/badge/Amazon%20AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=black" />
  <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />
</p>

<details>
<summary><b>🔍 AWS Services I work with daily</b></summary>

| Compute & Containers | Networking | Storage & DB | Messaging | Security |
|---|---|---|---|---|
| EC2, EKS, Lambda | VPC, Route 53, CloudFront | S3, RDS | SQS, SNS, SES | IAM, ACM |
| ECR | Client VPN, ALB | DynamoDB | EventBridge | CloudTrail |

</details>

---

### 🔧 DevOps & IaC
<p>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/GitLab%20CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" />
</p>

---

### 🐳 Containers & Orchestration
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white" />
  <img src="https://img.shields.io/badge/Argo%20CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white" />
  <img src="https://img.shields.io/badge/Amazon%20ECR-FF9900?style=for-the-badge&logo=amazonaws&logoColor=black" />
</p>

---

### 📊 Monitoring & Observability
<p>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/Amazon%20CloudWatch-FF9900?style=for-the-badge&logo=amazonaws&logoColor=black" />
  <img src="https://img.shields.io/badge/Alertmanager-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" />
</p>

---

### 💻 Languages & Tools
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
</p>

---

## 🏗️ Featured Projects

<table>
<tr>
<td width="50%">

### 🚀 AWS Infrastructure with Terraform
> Production-grade modular IaC

```hcl
module "eks_cluster" {
  source  = "./modules/eks"
  vpc_id  = module.vpc.id
  backend = "s3+dynamodb"
}
```

**Stack:** `Terraform` `EKS` `RDS` `ALB` `VPC`

✅ S3 remote state + DynamoDB locking  
✅ Modular VPC, EKS, RDS, ALB  
✅ Security group dependency resolution

</td>
<td width="50%">

### 🔄 GitOps CI/CD on EKS
> Full pipeline with security scanning

```yaml
pipeline:
  - build:    Docker image
  - scan:     Trivy vulnerability check
  - push:     Amazon ECR
  - deploy:   ArgoCD → EKS
```

**Stack:** `Jenkins` `ArgoCD` `Docker` `ECR` `Trivy`

✅ Automated Docker build & scan  
✅ ECR image management  
✅ GitOps deployment via ArgoCD

</td>
</tr>
</table>

---

## 💼 Experience Timeline

```
2026 Mar ──────────────────────────────────── Present
         🟢 Blackdart Labs Pvt. Ltd.
            DevOps Engineer
            ├── AWS full-stack provisioning (EKS, VPC, Lambda, SES, SQS)
            ├── EventBridge automation & API destinations
            ├── AWS Client VPN for secure developer access
            ├── EKS probe tuning & CrashLoopBackOff resolution
            └── Billing analysis & cost optimization

2025 Jul ──────────────────────────────── 2026 Feb
         🔵 Energetics AI Pvt. Ltd.
            DevOps Engineer
            ├── Migrated 6 microservices across AWS accounts (zero downtime)
            ├── Jenkins pipelines: Docker → ECR → EC2/Lambda/EKS/S3
            ├── Private Jenkins with OpenVPN + secure AWS networking
            ├── Security incident response (CloudTrail + IAM rotation)
            └── Cross-account AWS migrations (EKS, Lambda, RDS, Route 53)
```

---

## 🎓 Certifications

<div align="center">

| Badge | Certification | Issuer | Date |
|:---:|---|:---:|:---:|
| 🏅 | **Manage Kubernetes in Google Cloud** | Google Cloud | May 2026 |
| 🏅 | **Create & Manage Cloud SQL for PostgreSQL** | Google Cloud | May 2026 |

</div>

---

## 📈 GitHub Stats

<div align="center">

![Manikandan's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Manikandan24&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00d4ff&icon_color=00d4ff&text_color=c9d1d9)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Manikandan24&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00d4ff&text_color=c9d1d9)

</div>

---

## 🤝 Connect with Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/manikandan01)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Manikandan24)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:manikandanpro2020@gmail.com)

</div>

---

<div align="center">

```
┌─────────────────────────────────────────────────────────────┐
│  "Infrastructure is not just code — it's the backbone of    │
│   every product your users love."                           │
│                                          — Manikandan       │
└─────────────────────────────────────────────────────────────┘
```

![Profile Views](https://komarev.com/ghpvc/?username=Manikandan24&color=00d4ff&style=flat-square&label=Profile+Views)

</div>
