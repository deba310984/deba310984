<!-- ╔══════════════════════════════ HERO ══════════════════════════════╗ -->
<div align="center">

<img src="./assets/banners/hero.svg" alt="Debjit Sarkar — DevOps & Cloud Engineer. Infrastructure Automation, Kubernetes, AWS, Reliability Engineering." width="100%" />

</div>

<p align="center">
  <a href="https://github.com/deba310984"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" /></a>
  <a href="mailto:debjitsrkr310984@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-0D1117?style=flat-square&logo=gmail&logoColor=EA4335" /></a>
  <img alt="Focus" src="https://img.shields.io/badge/Focus-DevOps%20%C2%B7%20Cloud%20%C2%B7%20SRE-0D1117?style=flat-square&labelColor=0D1117&color=38BDF8" />
</p>

> Building repeatable, secure, and observable cloud infrastructure — provisioned as code, delivered through pipelines, and monitored by default.

---

<!-- ═══════════════════════ 2 · ENGINEERING SNAPSHOT ═══════════════════════ -->
## ⬢ Engineering Snapshot

<div align="center">

<img src="./assets/diagrams/engineering-snapshot.svg" alt="Control panel of six domains — Cloud: AWS, Terraform; Platform: Docker, Kubernetes, EKS; Delivery: GitHub Actions, Jenkins, Git; Reliability: Prometheus, Grafana, CloudWatch; Security: Trivy, Checkov, IAM; Automation: Python, Bash, Ansible, Claude Code." width="100%" />

</div>

---

<!-- ═══════════════════════ 3 · DEVOPS LIFECYCLE ═══════════════════════ -->
## ⬢ DevOps Lifecycle

<div align="center">

<img src="./assets/diagrams/devops-lifecycle.svg" alt="Delivery pipeline: Plan, Code (Git), Build (Maven), Test, Scan (Trivy/Checkov), Package (Docker), Deploy (Kubernetes/EKS), Observe (Prometheus/Grafana), Improve — orchestrated by GitHub Actions and Jenkins, with a continuous feedback loop." width="100%" />

</div>

---

<!-- ═══════════════════════ 4 · CLOUD ARCHITECTURE ═══════════════════════ -->
## ⬢ Cloud Architecture

Reference architecture from my AWS / Terraform work — a highly-available, multi-AZ design with a load-balanced application tier and a private, encrypted database tier.

<div align="center">

<a href="https://github.com/deba310984/aws-two-tier-terraform">
  <img src="./assets/architecture/aws-two-tier.svg" alt="AWS two-tier architecture: Internet Gateway to Application Load Balancer in public subnets, Auto Scaling EC2 in private app subnets across two AZs, encrypted RDS MySQL in private data subnets, NAT Gateway for outbound, SSM Session Manager access, CloudWatch observability — all inside a VPC." width="100%" />
</a>

<sub>Diagram built from <a href="https://github.com/deba310984/aws-two-tier-terraform"><code>aws-two-tier-terraform</code></a> — click to open the repository.</sub>

</div>

---

<!-- ═══════════════════════ 5 · FEATURED PROJECTS ═══════════════════════ -->
## ⬢ Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### ☁️ aws-two-tier-terraform
A highly-available, multi-AZ AWS architecture provisioned end to end as code.

**Stack:** `AWS` · `Terraform` · `ALB` · `ASG` · `RDS` · `IAM` · `SSM`

**Engineering**
- Database in private subnets, encrypted at rest
- Operator access via **SSM Session Manager** — no open SSH
- Least-privilege security groups; validated with Terraform tests

<a href="https://github.com/deba310984/aws-two-tier-terraform">Repository</a> ·
<a href="https://github.com/deba310984/aws-two-tier-terraform#readme">Docs</a> ·
<a href="#-cloud-architecture">Architecture ↑</a>

</td>
<td width="50%" valign="top">

### 🧩 aws-terraform-modules
A composable module library — the *same* network, cheap for dev and resilient for prod, from one codebase.

**Stack:** `Terraform` · `AWS` · `VPC` · `Security Groups` · `GitHub Actions`

**Engineering**
- Reusable, rule-driven VPC & security-group modules
- Dev = single NAT (cost-lean); prod = per-AZ NAT (resilient)
- CI validation on every change

<a href="https://github.com/deba310984/aws-terraform-modules">Repository</a> ·
<a href="https://github.com/deba310984/aws-terraform-modules#readme">Docs</a>

</td>
</tr>
<tr>
<td colspan="2">

<div align="center">
<img src="./assets/architecture/aws-modules.svg" alt="Module composition: reusable vpc and security-group modules compose a dev environment (2 AZs, single NAT) and a prod environment (3 AZs, per-AZ NAT), both CI-validated." width="100%" />
</div>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🚀 trendforge_ai
A cloud-native application with a full infrastructure and delivery setup around it.

**Stack:** `Docker` · `Kubernetes` · `Helm` · `GitHub Actions` · `Trivy` · `Prometheus` · `Terraform/EKS`

**Engineering**
- CI runs lint, tests, **Trivy** scan, and K8s manifest validation
- Workloads ship with autoscaling and network policies
- Observability wired in via the Prometheus Operator

<a href="https://github.com/deba310984/trendforge_ai">Repository</a> ·
<a href="https://github.com/deba310984/trendforge_ai#readme">Docs</a>

</td>
<td width="50%" valign="top">

### 🔁 CodeAlpha_Project1
A containerized web app with an end-to-end CI/CD pipeline to the cloud.

**Stack:** `Node.js` · `Docker` · `Azure Container Registry` · `Azure App Service` · `Azure DevOps`

**Engineering**
- Build once as an image, push to a registry, deploy to a managed host
- Automated pipeline instead of manual uploads

<a href="https://github.com/deba310984/CodeAlpha_Project1">Repository</a> ·
<a href="https://github.com/deba310984/CodeAlpha_Project1#readme">Docs</a>

</td>
</tr>
</table>

<sub>Also exploring upstream cloud-native security tooling through <strong>forks</strong> of <a href="https://github.com/deba310984/trivy">Trivy</a> and <a href="https://github.com/deba310984/kyverno">Kyverno</a>, and Docker fundamentals in <a href="https://github.com/deba310984/CodeAlpha_Web_Server_Docker">CodeAlpha_Web_Server_Docker</a>.</sub>

---

<!-- ═══════════════════════ 6 · TECH ECOSYSTEM ═══════════════════════ -->
## ⬢ Tech Ecosystem

**☁ Cloud**
&nbsp;![AWS](https://img.shields.io/badge/AWS-0D1117?style=flat-square&logo=amazonwebservices&logoColor=FF9900)

**🏗 Infrastructure**
&nbsp;![Terraform](https://img.shields.io/badge/Terraform-0D1117?style=flat-square&logo=terraform&logoColor=7C3AED)
![Ansible](https://img.shields.io/badge/Ansible-0D1117?style=flat-square&logo=ansible&logoColor=38BDF8)
![Linux](https://img.shields.io/badge/Linux-0D1117?style=flat-square&logo=linux&logoColor=FCC624)

**📦 Containers &nbsp;·&nbsp; ☸ Orchestration**
&nbsp;![Docker](https://img.shields.io/badge/Docker-0D1117?style=flat-square&logo=docker&logoColor=2496ED)
![Kubernetes](https://img.shields.io/badge/Kubernetes-0D1117?style=flat-square&logo=kubernetes&logoColor=326CE5)
![EKS](https://img.shields.io/badge/Amazon%20EKS-0D1117?style=flat-square&logo=amazoneks&logoColor=FF9900)
![Helm](https://img.shields.io/badge/Helm-0D1117?style=flat-square&logo=helm&logoColor=38BDF8)

**🔄 CI/CD**
&nbsp;![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-0D1117?style=flat-square&logo=githubactions&logoColor=38BDF8)
![Jenkins](https://img.shields.io/badge/Jenkins-0D1117?style=flat-square&logo=jenkins&logoColor=D24939)
![Git](https://img.shields.io/badge/Git-0D1117?style=flat-square&logo=git&logoColor=F05032)
![Maven](https://img.shields.io/badge/Maven-0D1117?style=flat-square&logo=apachemaven&logoColor=C71A36)

**📊 Observability**
&nbsp;![Prometheus](https://img.shields.io/badge/Prometheus-0D1117?style=flat-square&logo=prometheus&logoColor=E6522C)
![Grafana](https://img.shields.io/badge/Grafana-0D1117?style=flat-square&logo=grafana&logoColor=F46800)
![CloudWatch](https://img.shields.io/badge/CloudWatch-0D1117?style=flat-square&logo=amazoncloudwatch&logoColor=FF4F8B)

**🔐 Security / DevSecOps**
&nbsp;![Trivy](https://img.shields.io/badge/Trivy-0D1117?style=flat-square&logo=aquasecurity&logoColor=38BDF8)
![Checkov](https://img.shields.io/badge/Checkov-0D1117?style=flat-square&logo=checkmarx&logoColor=7C3AED)
![IAM](https://img.shields.io/badge/IAM%20%26%20Secrets-0D1117?style=flat-square&logo=amazonwebservices&logoColor=FF9900)

**💻 Automation / Languages**
&nbsp;![Python](https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=3776AB)
![Bash](https://img.shields.io/badge/Bash-0D1117?style=flat-square&logo=gnubash&logoColor=4EAA25)
![Go](https://img.shields.io/badge/Go-0D1117?style=flat-square&logo=go&logoColor=00ADD8)
![YAML](https://img.shields.io/badge/YAML-0D1117?style=flat-square&logo=yaml&logoColor=CB171E)

**🤖 AI-Assisted Engineering**
&nbsp;![Claude Code](https://img.shields.io/badge/Claude%20Code-0D1117?style=flat-square&logo=anthropic&logoColor=D97757)
![GitHub Copilot](https://img.shields.io/badge/GitHub%20Copilot-0D1117?style=flat-square&logo=githubcopilot&logoColor=38BDF8)

<sub>Icons indicate tools I use or am actively learning — not a claim of expert-level mastery in each.</sub>

---

<!-- ═══════════════════════ 7 · AI-ASSISTED DEVOPS ═══════════════════════ -->
## ⬢ AI-Assisted DevOps

How AI fits into my workflow — used to accelerate **codebase analysis, infrastructure drafting, test generation, documentation, and incident investigation**, always behind a human-review gate for high-impact infrastructure changes. No claim of autonomous production operation.

<div align="center">

<img src="./assets/diagrams/ai-devops-workflow.svg" alt="AI-assisted DevOps workflow: Developer uses AI-assisted analysis to help produce code, Terraform and Kubernetes changes, which pass through tests and security scans, then a required human-review gate for high-impact changes, then deployment and monitoring that feeds back to the developer." width="100%" />

</div>

---

<!-- ═══════════════════════ 8 · ENGINEERING PRINCIPLES ═══════════════════════ -->
## ⬢ Engineering Principles

| Principle | In practice |
| :-- | :-- |
| **Infrastructure as Code** | Everything reproducible from version-controlled Terraform — no console drift. |
| **Secure by default** | Private data tiers, encryption on, no unnecessary open ports. |
| **Least privilege** | Scoped IAM roles and tight, rule-driven security groups. |
| **Automated validation** | Lint, plan, test, and scan in CI before anything reaches an environment. |
| **Observable systems** | Metrics, dashboards, and alerts that point to actionable problems. |
| **Repeatable deployments** | Pipeline-driven releases with a rollback path in mind. |
| **Cost awareness** | Right-sized resources and cleanup — single NAT for dev, per-AZ only in prod. |
| **Human-in-the-loop AI** | AI-assisted infrastructure changes always get human review before they ship. |

---

<!-- ═══════════════════════ 9 · GITHUB ACTIVITY ═══════════════════════ -->
## ⬢ GitHub Activity

<div align="center">

<img height="150" alt="Debjit's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=deba310984&show_icons=true&hide_border=true&count_private=true&theme=github_dark&title_color=38BDF8&icon_color=A78BFA&bg_color=0D1117" />
<img height="150" alt="Debjit's most used languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=deba310984&layout=compact&hide_border=true&langs_count=8&theme=github_dark&title_color=38BDF8&bg_color=0D1117" />

<sub>Secondary context only — rendered by github-readme-stats; refresh if a card is slow to load. Explore the work directly at <a href="https://github.com/deba310984?tab=repositories">github.com/deba310984</a>.</sub>

</div>

---

<!-- ═══════════════════════ 10 · CONTACT ═══════════════════════ -->
## ⬢ Contact

<p align="center">
  <a href="https://github.com/deba310984"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" /></a>
  <a href="mailto:debjitsrkr310984@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-0D1117?style=flat-square&logo=gmail&logoColor=EA4335" /></a>
  <!-- Add your verified LinkedIn URL below, then uncomment this badge:
  <a href="https://www.linkedin.com/in/YOUR-HANDLE"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  -->
</p>

<div align="center"><sub><code>Infrastructure as Code</code> · <code>Automation</code> · <code>Reliability</code></sub></div>
