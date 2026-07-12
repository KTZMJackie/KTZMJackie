# Hi, I'm Khine Thazin Myint (Jackie)

**Cloud & DevOps Engineer with a reliability and release-engineering** background from regulated biotech instrumentation. Azure-certified (AZ-104, AZ-900), building production-style CI/CD, Infrastructure as Code, and observability projects across Azure and Kubernetes — and currently extending into AWS.

I don't just deploy things. I come from a world where software failure on an instrument meant a blocked production line or a corrupted blood-sample run, so I build for reliability, secure-by-default auth, and clean recovery.

---

## What I Bring

Before moving into cloud, I spent my previous role as the first point of contact for software failures on air-gapped biotech instruments at Standard BioTools:

- Wrote quality-control test scripts in Python for fluidic chips and libraries — correlating chip design to automated tests for connection, blockage, and failure, with guided technician prompts.

- Owned the software side of NPI (new product introduction) — validating every software release on simulated and real instruments, installing Azure DevOps artifacts, running tests, and triaging failures.

- Ran instrument reliability testing — MTBF calculation, accelerated and real-time lifespan testing at module and full-instrument level to meet guaranteed-lifetime commitments to customers.

- Logged and fixed bugs in Azure DevOps, was manufacturing's go-to for any software issue, and rolled out hotfixes during live customer complaints after releases.

That's release engineering, test automation, and incident response — the SRE mindset — applied to hardware I couldn't SSH into. I'm now applying the same discipline to cloud infrastructure.

## Certifications

| Certification | Status |
|---|---|
| Microsoft Certified: Azure Administrator Associate (AZ-104) | ✅ Passed — April 2026 |
| Microsoft Certified: Azure Fundamentals (AZ-900) | ✅ Passed — April 2026 |

---

## Technical Stack

**Cloud & Infrastructure**
Azure Container Apps · Azure Container Registry · Azure Key Vault · Azure Blob Storage · Azure Virtual Networks · Azure DNS · Azure Load Balancer · Azure Monitor

**DevOps & CI/CD**
GitHub Actions · Azure DevOps (Boards, Repos, Pipelines) · Docker · Terraform

**Containers & Observability**
Kubernetes · AKS · Helm · Prometheus · Grafana · Alertmanager · Ansible

**Security & Identity**
Managed Identity · RBAC · Azure Key Vault · Zero-credential architecture

**Languages & Frameworks**
Python · FastAPI · HCL (Terraform) · YAML · Bash

---

## Featured Projects

### [azure-fastapi-project](https://github.com/KTZMJackie/azure-fastapi-project)
Production-style deployment of a containerized FastAPI application on Azure using Terraform, Managed Identity, Key Vault, Blob Storage, and GitHub Actions CI/CD. No hardcoded credentials. Infrastructure fully managed as code.

`Python` `Terraform` `Docker` `Azure Container Apps` `GitHub Actions` `Key Vault` `Managed Identity`

---

### [azure-devops-cicd](https://github.com/KTZMJackie/azure-devops-cicd)
Production-style 3-stage Azure DevOps pipeline: automated pytest → Docker buildx amd64 image pushed to ACR → zero-downtime deployment to Azure Container Apps. No hardcoded credentials via service connection.

`Python` `Azure DevOps` `Docker` `ACR` `Azure Container Apps` `pytest` `YAML`

---

### [k8s-observability-platform](https://github.com/KTZMJackie/k8s-observability-platform)

Kubernetes observability platform deployed on both **Minikube** (local) and **AKS on Azure** (cloud). FastAPI deployed via Helm, monitored with Prometheus and Grafana. Includes Terraform IaC for AKS provisioning, 4 Prometheus alert rules with Alertmanager routing, incident runbook + postmortem, and 4 Bash ops scripts.

`Python` `Kubernetes` `AKS` `Terraform` `Helm` `Prometheus` `Grafana` `Ansible` `Bash` `GitHub Actions`

---

### [hello-azure-fastapi](https://github.com/KTZMJackie/hello-azure-fastapi)
End-to-end FastAPI microservice deployed to Azure Container Apps with automated CI/CD via GitHub Actions and secure secret retrieval from Azure Key Vault using Managed Identity.
**Live demo available.**

`Python` `Docker` `Azure Container Apps` `GitHub Actions` `Key Vault`

---

## Background

12 years in biotech and life science engineering. 8 years specialising in automation scripting, software validation, and product/script release management in regulated environments. 4 years hands-on with Azure DevOps — bug tracking, code review, pipeline management, and deployment workflows.

Transitioning into cloud and DevOps engineering with a focus on Azure infrastructure, automation, and secure cloud-native architecture.

---

## Currently

- 🎯 Targeting: **Cloud Engineer · DevOps Engineer · Azure Administrator · SRE** roles in Singapore
- 🔧 Building:

     - AWS deployment mirroring my Azure work — containerized app on ECS Fargate with Terraform, GitHub Actions, Secrets Manager, and IAM roles (multi-cloud).

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/khine-thazin-myint-1b498152/)

> *Based in Singapore · Open to full-time opportunities*
