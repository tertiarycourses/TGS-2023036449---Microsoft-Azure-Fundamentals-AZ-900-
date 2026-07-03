# TGS-2023036449 — Microsoft Azure Fundamentals (AZ-900) Hands-On Labs

> **Course:** WSQ — Microsoft Azure Fundamentals (AZ-900)
> **Course Code:** TGS-2023036449
> **Register here:** https://www.tertiarycourses.com.sg/wsq-microsoft-azure-fundamentals-az-900.html

These are the official hands-on lab exercises for the WSQ Microsoft Azure Fundamentals (AZ-900) course delivered by [**Tertiary Infotech Academy Pte Ltd**](https://www.tertiarycourses.com.sg/).

A complete set of **16 step-by-step labs** aligned to the Microsoft AZ-900 exam skills outline. Every lab runs on a **free Azure account** (https://azure.microsoft.com/free) in the Azure Portal and Azure Cloud Shell — no local install required.

---

## Courseware

| Artifact | File |
|----------|------|
| **Learner Guide (Markdown)** — all 16 labs, step by step | [LG-Microsoft Azure Fundamentals (AZ-900).md](LG-Microsoft%20Azure%20Fundamentals%20%28AZ-900%29.md) |
| **Lab index** — labs grouped by exam domain | [labs/README.md](labs/README.md) |

> **Note:** the confidential WSQ **assessment** materials (Written Assessment, Practical Performance and their answer keys) are intentionally **not** published to this repository.

---

## How to use

1. Sign up for a free Azure account: https://azure.microsoft.com/free (USD 200 credit for 30 days + always-free services).
2. Sign in to the Azure Portal: https://portal.azure.com — CLI labs use Azure Cloud Shell: https://shell.azure.com.
3. Pick a lab from the catalogue below and follow the steps in order — the labs build on each other (the resource group `rg-az900-labs` is reused throughout).
4. **Always run the Clean up section** at the end of each lab so you don't burn your free credit. Lab 16 finishes with the full course clean-up.

---

## Lab catalogue

### Day 1

#### Domain 1 — Describe Cloud Concepts (25–30%)
- [Lab 1 — Tour the Azure Portal and Create Your First Resource Group](labs/lab-01-azure-portal-tour.md)
- [Lab 2 — Get Started with Azure Cloud Shell (CLI and PowerShell)](labs/lab-02-cloud-shell-cli.md)
- [Lab 3 — Explore Regions, Region Pairs and Availability Zones](labs/lab-03-regions-availability-zones.md)

#### Domain 2 — Describe Azure Architecture and Services (35–40%)
- [Lab 4 — Create a Windows Virtual Machine in the Portal](labs/lab-04-windows-vm-portal.md)
- [Lab 5 — Create a Linux VM with the Azure CLI](labs/lab-05-linux-vm-cli.md)
- [Lab 6 — Create a Web App with Azure App Service](labs/lab-06-app-service-webapp.md)
- [Lab 7 — Deploy a Container with Azure Container Instances](labs/lab-07-container-instances.md)
- [Lab 8 — Create a Virtual Network and Test Private Connectivity](labs/lab-08-virtual-network.md)

### Day 2

#### Domain 2 — Describe Azure Architecture and Services (continued)
- [Lab 9 — Create a Storage Account and Work with Blob Storage](labs/lab-09-storage-blobs.md)
- [Lab 10 — Create an Azure SQL Database](labs/lab-10-azure-sql.md)
- [Lab 11 — Explore Microsoft Entra ID: Users and Groups](labs/lab-11-entra-id.md)

#### Domain 3 — Describe Azure Management and Governance (30–35%)
- [Lab 12 — Manage Access with Azure RBAC](labs/lab-12-rbac.md)
- [Lab 13 — Apply Resource Tags and Resource Locks](labs/lab-13-tags-locks.md)
- [Lab 14 — Enforce Standards with Azure Policy](labs/lab-14-azure-policy.md)
- [Lab 15 — Estimate and Control Costs: Pricing Calculator, TCO and Budgets](labs/lab-15-cost-management.md)
- [Lab 16 — Monitor Your Environment: Advisor, Service Health and Azure Monitor](labs/lab-16-monitoring.md)

---

## Reference

- [labs/README.md](labs/README.md) — Lab index grouped by exam domain, with requirements per lab
- Official AZ-900 study guide: https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-900
- Official Microsoft Learning AZ-900 labs: https://github.com/MicrosoftLearning/AZ-900-Microsoft-Azure-Fundamentals
- AZ-900 free practice assessment: https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/practice/assessment?assessment-type=practice&assessmentId=23

---

## Cost

All labs are designed for the **Azure free account** (USD 200 / 30-day credit) using the smallest billable SKUs (`Standard_B1s`/`Standard_B2s` VMs, `F1` App Service plan, `Standard LRS` storage, Basic/serverless SQL). Total cost if you complete all 16 labs and clean up as instructed is **well under USD 5 of the free credit**. The Pricing Calculator and TCO Calculator labs (Lab 15) are 100% free web tools.
