<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:185FA5,100:0A66C2&height=120&section=header&text=&fontSize=0" width="100%"/>

# Upendra Verma

### DevOps Engineer · Cloud Infrastructure · CI/CD · DevSecOps

<p>
  <a href="https://linkedin.com/in/upendra-verma-3a3212293">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:devopsupendra23@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/Upendra-23-cmd">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
  </a>
  <img src="https://img.shields.io/badge/Open%20to%20Work-2EA44F?style=flat-square&logo=checkmarx&logoColor=white"/>
  <img src="https://komarev.com/ghpvc/?username=Upendra-23-cmd&style=flat-square&color=185FA5&label=Profile+Views"/>
</p>

</div>

---

## About Me

I am a **DevOps Engineer** focused on building scalable, secure, and automated cloud systems.
I work across **AWS, Docker, Kubernetes, Terraform, GitHub Actions, and DevSecOps tooling**
to improve delivery speed, reliability, and security posture across the full software lifecycle.

- Reduced deployment time by **30%** through CI/CD pipeline automation
- Cut manual monitoring effort by **40%** using Bash scripting and CloudWatch dashboards
- Implemented end-to-end security scanning with **Gitleaks, Trivy, and tfsec**
- Built production-grade **Go microservices** with gRPC, Redis cache, and AI integration
- Hands-on with **AWS infrastructure, containerisation, and production observability**
- Passionate about **zero-downtime deployments, GitOps, and cloud reliability**

---

## Impact at a Glance

| Metric | Result | How |
|--------|--------|-----|
| Deployment speed | **30% faster** | CI/CD pipeline with GitHub Actions |
| Manual monitoring | **40% reduction** | Bash automation + CloudWatch dashboards |
| Pipeline uptime | **99.8%** | Rolling updates and canary rollout strategy |
| Security coverage | **End-to-end** | Gitleaks · Trivy · tfsec · GuardDuty · OWASP |
| API response time | **<50ms** | Redis cache-aside with write-through invalidation |

---

## Tech Stack

**Cloud & Infrastructure**

`AWS EC2` `S3` `IAM` `VPC` `RDS` `Lambda` `ECS` `Route53` `CloudFront` `CloudWatch` `SNS` `GuardDuty` `CloudTrail` `Azure Fundamentals`

**CI/CD & Infrastructure as Code**

`GitHub Actions` `Terraform` `Jenkins` `CloudFormation` `GitOps`

**Containers & Orchestration**

`Docker` `Docker Compose` `Kubernetes` `Helm` `Multi-stage Builds`

**Backend & Distributed Systems**

`Go (Golang)` `gRPC` `Protocol Buffers` `REST APIs` `JWT Auth` `API Gateway` `Microservices`

**Databases & Cache**

`PostgreSQL` `MongoDB` `Redis` `Polyglot Persistence` `Redis Pub/Sub`

**AI & ML Integration**

`Anthropic Claude API` `Agentic AI` `Structured Output Prompting` `Clinical Decision Support`

**DevSecOps**

`Gitleaks` `Trivy` `tfsec` `Dependabot` `npm audit` `AWS GuardDuty` `OWASP Basics`

**Monitoring & Observability**

`Prometheus` `Grafana` `CloudWatch` `Logging & Alerting` `Incident Response` `Zap Structured Logs`

**Frontend**

`React` `TypeScript` `Vite` `Zustand` `TanStack Query`

**Core Tools**

`Bash` `Linux` `Python` `Git` `YAML`

---

## Experience

### DevOps Engineer Trainee · Hisan Labs
`July 2025 – Dec 2025`  Pune, India

- Deployed a student registration application using **Docker containers on AWS EC2/S3** with **canary rollout** and rollback strategies, minimising deployment risk in production
- Automated daily cloud health checks using **Bash scripts** and **CloudWatch dashboards**, reducing manual monitoring effort by **40%**
- Provisioned and configured AWS resources including **EC2, S3, IAM roles, and VPC security groups** with least-privilege access principles
- Authored **runbooks, deployment SOPs, and incident response checklists**, improving team response time and reducing knowledge silos

---

## Projects

### AI-Clinical-Platform-Go-gRPC-React-PostgreSQL-MongoDB-Redis
`Go` `gRPC` `Protocol Buffers` `React` `TypeScript` `PostgreSQL` `MongoDB` `Redis` `Claude AI` `JWT`

A production-grade, AI-powered hospital management platform built with **5 independent Go microservices** communicating over gRPC. Features a **Claude AI diagnostic engine** for real-time symptom analysis, drug interaction checking, and risk scoring. Backed by **PostgreSQL** (patient records), **MongoDB** (appointments + analytics events), and **Redis** (15-minute cache-aside layer + pub/sub for real-time notifications via SSE). Secured by a **JWT-authenticated API gateway** with token-bucket rate limiting and reverse proxy routing. Paired with a dark-themed **React/TypeScript** clinical dashboard.

**Architecture highlights:**
- 5 bounded-context microservices — Patient · Appointment · AI Diagnostic · Notification · Analytics
- gRPC with `.proto` contracts for type-safe inter-service communication
- Polyglot persistence — PostgreSQL + MongoDB + Redis in a single platform
- Redis fail-open cache — outage degrades performance, never availability
- Agentic AI chat with emergency escalation detection powered by Claude
- Real-time SSE push notifications via Redis pub/sub channels

[![Repo](https://img.shields.io/badge/View_Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Upendra-23-cmd/AI-Clinical-Platform-Go-gRPC-React-PostgreSQL-MongoDB-Redis)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Claude AI](https://img.shields.io/badge/Claude_AI-7c4dff?style=flat-square)

---

### Full-Stack-Microservice-Boilerplate-Go-React-PostgreSQL-Redis
`Go` `Gin` `React` `PostgreSQL` `Redis` `JWT` `Docker` `Docker Compose`

A production-ready microservice starter kit for DevOps learners and backend engineers. **Go (Gin) REST API** with JWT authentication, **Redis caching**, and **PostgreSQL** — paired with a **React frontend**. Fully containerised with **Docker Compose** for one-command local setup. Designed as a clean, extensible foundation for teams building new microservices without starting from scratch.

**Architecture highlights:**
- Go Gin REST API with structured routing and middleware chain
- JWT auth with refresh token rotation
- Redis cache layer with TTL-based invalidation
- PostgreSQL with connection pooling and migration support
- Docker Compose multi-service orchestration with health checks
- React frontend with Axios interceptors and protected routes

[![Repo](https://img.shields.io/badge/View_Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Upendra-23-cmd/Full-Stack-Microservice-Boilerplate-Go-React-PostgreSQL-Redis)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

---

### Full-Stack CI/CD Pipeline
`React` `Spring Boot` `MariaDB` `Docker` `Docker Compose` `GitHub Actions` `AWS`

Built a production-grade full-stack application with multi-container orchestration and a
**3-stage CI/CD pipeline** — build → test → deploy — using GitHub Actions and AWS.
Achieved **99.8% uptime** through rolling updates, health checks, and proper environment isolation.

[![Repo](https://img.shields.io/badge/View_Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Upendra-23-cmd/EasyCRUD)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)

---

### DevSecOps Pipeline
`Terraform` `AWS GuardDuty` `CloudTrail` `GitHub Actions` `Gitleaks` `Trivy` `tfsec` `Dependabot`

End-to-end DevSecOps pipeline with security scanning integrated at every stage of the CI/CD workflow.
Enabled real-time threat detection via **AWS GuardDuty and CloudTrail**.
Automated dependency vulnerability checks with **Dependabot** and **npm audit**.

[![Repo](https://img.shields.io/badge/View_Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Upendra-23-cmd/timofx-main)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square)

---

### Cloud-Deployed Monolithic App
`AWS EC2` `Linux` `Bash`

Provisioned a cloud instance for a monolithic web application.
Added health monitoring scripts and auto-restart logic for basic self-healing,
improving service reliability without requiring manual intervention on failure.

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## GitHub Stats

<div align="center">
  <img
    src="https://github-readme-stats.vercel.app/api?username=Upendra-23-cmd&show_icons=true&theme=default&hide_border=true&title_color=185FA5&icon_color=185FA5&text_color=333333&bg_color=ffffff"
    height="165"
  />
  <img
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=Upendra-23-cmd&layout=compact&theme=default&hide_border=true&title_color=185FA5&text_color=333333&bg_color=ffffff"
    height="165"
  />
</div>

<div align="center">
  <img
    src="https://github-readme-streak-stats.herokuapp.com?user=Upendra-23-cmd&theme=default&hide_border=true&ring=185FA5&fire=185FA5&currStreakLabel=185FA5"
    height="165"
  />
</div>

---

## Education

**B.Tech — Computer Science and Engineering**
UIT RGPV Shivpuri, Madhya Pradesh · 2022 – 2026 · CGPA: 7.00 / 10.0

---

## Certifications & Achievements

| Certification / Achievement | Status |
|-----------------------------|--------|
| AWS Cloud Practitioner Essentials | Completed |
| AWS CLF-C02 | Preparing |
| HashiCorp Terraform Associate | Preparing |
| Docker & Kubernetes: The Complete Guide | Completed |
| Vice President — Technoverse Tech Club | Leadership |
| Coordinator — codeManthan 2025 | Event Lead |
| Cybersecurity Hackathon | Participant |

---

## Let's Connect

<div align="center">

  <a href="https://linkedin.com/in/upendra-verma-3a3212293">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:devopsupendra23@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/Upendra-23-cmd">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>

<br/><br/>

<i>"Automating infrastructure, securing delivery, and building reliable systems — one service at a time."</i>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A66C2,100:185FA5&height=80&section=footer" width="100%"/>

</div>
