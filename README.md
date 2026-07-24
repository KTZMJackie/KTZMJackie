# Hi, I'm Khine Thazin Myint (Jackie)

**Software Test & Validation Engineer + Azure DevOps / Cloud Practitioner**

12 years in regulated (ISO 9001 / 13485) biotech instrumentation · Test automation · Release-gating · CI/CD · Reliability

I build and automate the parts that keep software trustworthy: **automated testing, release-gating, and reliability** — the overlap where QA/Test engineering and DevOps meet. My background is software validation, release engineering, and reliability testing on regulated biotech instruments, and I bring that same discipline to modern cloud-native tooling. Azure-certified (AZ-104, AZ-900), building test-gated CI/CD, Infrastructure-as-Code, and observability projects across Azure and Kubernetes.

I don't just deploy things. I come from a world where software failure on an instrument meant a blocked production line or a corrupted blood-sample run, so I build for reliability, secure-by-default auth, and clean recovery.

---

## What I Bring

For 12 years at Standard BioTools, I was the first point of contact for software failures on air-gapped biotech instruments, owning test, validation, and release across the lifecycle:

- **Test automation:** Wrote quality-control test scripts in Python for fluidic chips and libraries — correlating chip design to automated tests for connection, blockage, and failure, with guided technician prompts and pass/fail classification.
  
- **Software validation & release:** Owned the software side of NPI — validating every software release on simulated and real instruments, installing Azure DevOps artifacts, running test suites, and triaging failures before release.
  
- **Reliability testing:** Ran instrument reliability testing — MTBF calculation, accelerated and real-time lifespan testing at module and full-instrument level — to meet guaranteed-lifetime commitments to customers.
  
- **Defect management & incident response:** Logged and fixed bugs in Azure DevOps, was manufacturing's go-to for any software issue, and rolled out hotfixes during live customer complaints after releases.

That's **test automation, release engineering, and incident response — the SRE mindset — applied to hardware I couldn't SSH into.** I now bring the same discipline to software and cloud systems.

## Certifications

| Certification | Status |
|---|---|
| Microsoft Certified: Azure Administrator Associate (AZ-104) | ✅ Passed — April 2026 |
| Microsoft Certified: Azure Fundamentals (AZ-900) | ✅ Passed — April 2026 |
| ISO 9001 & ISO 13485 Internal Auditor | Certified |

---

## Technical Stack

**Test & Validation**
Software / system / functional / integration / regression testing · DVT · EVT · MVT · IQ · OQ · PQ · V&V · MTBF · FMEA · defect triage & management · release gating · audit traceability

**Test Automation & Scripting**
Python · C# · pytest · regression automation · pass/fail test classification · Bash

**CI/CD & DevOps**
Azure DevOps (Boards, Repos, Pipelines) · GitHub Actions · Git · pull-request gating · quality-gate approvals · Docker · Terraform · TFLint · Checkov · pre-commit

**Cloud & Infrastructure**
Azure Container Apps · App Service · Azure SQL · Container Registry · Key Vault · Blob Storage · Virtual Networks · Private Endpoints · Azure Monitor · Log Analytics · Application Insights

**Containers & Observability**
Kubernetes · AKS · Helm · Prometheus · Grafana · Alertmanager · Ansible

**Security & Identity**
Managed Identity · RBAC · Entra ID · OIDC Federation · Key Vault · Policy-as-Code · zero-credential architecture
---

## Featured Projects


**[terraform-azure-infra](https://github.com/KTZMJackie/terraform-azure-infra) — Security-hardened Azure platform as code**
A modular, security-hardened Azure environment built entirely as Infrastructure-as-Code:
private-networked App Service, Azure SQL (Entra-ID-only auth), Key Vault, and storage — no public
data plane and no stored secrets (Managed Identity + RBAC). Reusable modules, dev/prod parity,
Azure AD-authenticated remote state, and a secretless OIDC GitHub Actions pipeline gated by
Checkov security scanning.

`Terraform` `Azure` `IaC` `Private Endpoints` `OIDC` `Checkov` `TFLint` `Managed Identity` `RBAC`

**[azure-devops-cicd](https://github.com/KTZMJackie/azure-devops-cicd) — Automated test & release-gating pipeline**
A **pytest suite as a mandatory quality gate**: if any test fails, the build and deployment are
blocked (Test → Build → Deploy on Azure DevOps → Azure Container Apps). The automated version of
the pull-request-gated, test-first release discipline I ran in regulated production.

`pytest` `Azure DevOps` `Docker` `ACR` `Azure Container Apps` `YAML`

**[azure-fastapi-project](https://github.com/KTZMJackie/azure-fastapi-project) — Production-style deployment**
Containerized FastAPI on Azure with Terraform IaC, Managed Identity, Key Vault, and Blob Storage.
No hardcoded credentials; infrastructure fully managed as code.

`Python` `Terraform` `Docker` `Azure Container Apps` `Key Vault` `Managed Identity`

**[k8s-observability-platform](https://github.com/KTZMJackie/k8s-observability-platform) — Monitoring & alerting**
FastAPI on Kubernetes (Minikube + AKS) via Helm, monitored with Prometheus and Grafana. Includes
4 Prometheus alert rules with Alertmanager routing, an incident runbook + postmortem, and Bash
ops scripts — early failure detection, the observability half of quality.

`Kubernetes` `AKS` `Terraform` `Helm` `Prometheus` `Grafana` `Ansible`

**[hello-azure-fastapi](https://github.com/KTZMJackie/hello-azure-fastapi) — CI/CD microservice**
End-to-end FastAPI microservice deployed to Azure Container Apps with GitHub Actions CI/CD and
secure secret retrieval from Key Vault via Managed Identity.

`Python` `Docker` `Azure Container Apps` `GitHub Actions` `Key Vault`

---

## Background

12 years in biotech and life-science engineering: 8 years specializing in test automation, software validation, and product/script release management in regulated (ISO 9001/13485) environments, and 4 years hands-on with Azure DevOps — bug tracking, code review, pipeline management, and PR-gated deployment workflows. NUS Electronics Engineering graduate.

---

## Currently

- **Open to:** Software Test Development · Validation / V&V · SDET · QA Automation · CSV — **and** Azure DevOps / CI/CD / Cloud / Platform roles in Singapore
- **Building:** a dedicated test-automation framework (data-driven pytest suite with reporting & coverage), plus an AWS deployment mirroring my Azure work (ECS Fargate + Terraform + GitHub Actions)

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/khine-thazin-myint-1b498152/)

> *Based in Singapore · Open to full-time opportunities*
