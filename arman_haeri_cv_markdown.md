---
pdf_options:
  format: A4
  margin: 20mm
stylesheet:
  - https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css
  - https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap
css: |
  body { font-family: 'Inter', sans-serif; font-size: 11pt; line-height: 1.5; color: #333; }
  h1 { color: #1a1a1a; border-bottom: 2px solid #2563eb; padding-bottom: 8px; margin-bottom: 4px; }
  h1 + p { margin-top: 0; }
  h2 { color: #1e40af; font-size: 14pt; margin-top: 20px; border-bottom: 1px solid #e5e7eb; padding-bottom: 4px; }
  h3 { color: #374151; font-size: 12pt; margin-bottom: 4px; }
  h4 { color: #4b5563; font-size: 11pt; margin-top: 12px; margin-bottom: 4px; }
  a { color: #2563eb; text-decoration: none; }
  a:hover { text-decoration: underline; }
  hr { border: none; border-top: 1px solid #e5e7eb; margin: 16px 0; }
  ul { margin-top: 8px; margin-bottom: 8px; }
  li { margin-bottom: 4px; }
  strong { color: #1f2937; }
  p { margin: 8px 0; }
  .fa-solid, .fa-brands { color: #6b7280; margin-right: 4px; }
---

# Arman Haeri

**Senior Azure Consultant | AI & Integration | Technical Discovery & POCs | .NET | VR/XR ᯅ**

<i class="fa-solid fa-envelope"></i>&nbsp; haeri.arman@gmail.com  
<i class="fa-solid fa-phone"></i>&nbsp; +351 912 32 7427  
<i class="fa-solid fa-location-dot"></i>&nbsp; Lisbon, Portugal  
<i class="fa-brands fa-linkedin"></i>&nbsp; [linkedin.com/in/armanhaeri](https://www.linkedin.com/in/armanhaeri/)  
<i class="fa-brands fa-github"></i>&nbsp; [github.com/CyberEgo](https://github.com/CyberEgo/)

---

## Summary

Senior Software Engineer with 20+ years in IT, including 10+ years of experience building and operating cloud-native systems with Microsoft Azure and .NET. Strong background in distributed systems, CI/CD automation, and developer enablement (SDKs, tooling, documentation). Currently architecting a cross-platform automation product: .NET Aspire backend with MCP-based plugin orchestration, Unity desktop/mobile clients, and AI-assisted workflows.

---

## Core Competencies

- **Cloud:** Azure (Functions, App Service, Container Apps, Logic Apps, Service Bus, Storage, Key Vault, APIM, RBAC, IAM, OAuth2, OIDC)
- **Software Design:** Clean Architecture, DDD, TDD, patterns (repository, factory, adapter, decorator, observer, plugin/extensibility)
- **Cloud Patterns:** Publisher/Subscriber, Queue-Based Load Leveling, CQRS, Saga; resilience (Retry, Circuit Breaker, Bulkhead)
- **Backend:** C# / .NET, Python, .NET Aspire, MCP Server/Client, Web APIs/BFF, EF Core, OpenAPI Spec, n8n (service prototyping)
- **DevOps & IaC:** GitHub Actions, Azure DevOps, Docker, Bicep, GitHub CLI, Azure CLI, PowerShell, Bash
- **AI & Agent Development:** Azure AI Foundry, Microsoft.Agents SDK, Semantic Kernel, tool-calling models, MCP integration, agent orchestration
- **Data & RAG:** Azure SQL, PostgreSQL, Cosmos DB, embedding models, vector search
- **Testing & Quality:** xUnit, integration testing, pipeline quality gates
- **Client & Tooling:** Unity, Blazor, SDK/NuGet design, automation tooling
- **Technical Documentation:** Architecture diagrams (PlantUML, Mermaid, Draw.io), Docusaurus, ADRs
- **Observability:** OpenTelemetry, Application Insights, Log Analytics, KQL
- **AI-Assisted Development:** GitHub Copilot, Claude Code, Codex, agentic workflows; prompt engineering, Perplexity

---

## Professional Experience

### Independent Software Engineer (Startup Founder)
**Sep 2024 – Present**  
**Project:** Cross-platform Automation App

- Architected and led development of backend services using **.NET 8** and **.NET Aspire**, covering authentication, licensing, and plugin orchestration via **WebSockets**, **JSON schema contracts**, and **MCP-style interfaces**.
- Built an **AI Voice Agent** system integrating **Azure AI Foundry**, **Semantic Kernel**, and tool-calling capabilities; supports multi-model switching (Azure OpenAI, Anthropic Claude, GitHub Copilot models) with dynamic endpoint abstraction.
- Implemented **MCP tool integration** enabling the AI agent to discover and invoke external tools dynamically.
- Implemented authentication and SSO with **Azure AD B2C** (**OIDC/OAuth2**), enforcing scoped access via claims-/policy-based authorization and **RBAC**.
- Designed and delivered cross-platform **Unity** clients (Windows desktop & Android) for profile management, automation workflow authoring, plugin lifecycle control.
- Designed and published a **Plugin SDK** (**NuGet** + GitHub samples) enabling CLI-invoked extensions with standardized JSON contracts.
- Built an **Azure-hosted marketplace portal** for user accounts, license management, plugin distribution, contributor onboarding, and documentation; integrated **Stripe** (payment gateway) using **webhooks** to automate billing workflows.
- Implemented automated build, packaging, and deployment pipelines using **GitHub Actions, AZD, Bicep, PowerShell, YAML**, and **Docker**.
- Delivered signed installers using **WiX (MSI)** with update channels and rollback support.
- Implemented CI/CD quality gates in **GitHub Actions** (build, tests, static analysis, dependency scanning) and set up observability with **OpenTelemetry**, **Application Insights**, and **Log Analytics**.
- Authored developer and user documentation to support onboarding and extension development (Docusaurus, Markdown, Mermaid).

**Technologies:** .NET 8, .NET Aspire, EF Core, Azure SQL, Azure Storage, RBAC, Key Vault, Azure AI Foundry, Microsoft.Agents SDK, Semantic Kernel, MCP, Unity (IL2CPP), Blazor, OAuth2, OIDC, Azure AD B2C, NuGet, Stripe, GitHub Actions, AZD, Bicep, Docker, WiX/MSIX, OpenTelemetry

---

### Azure Consultant — Codit PT (Portugal, remote)

#### Customer: Port of Antwerp · Project: NxtPort (Belgium, remote)
**Jan 2024 – Aug 2024**
- Researched and implemented semi-automated **BFF/backend scaffolding** from **OpenAPI specifications** using **NSwag** to accelerate service scaffolding and standardize API contracts.
- Designed and delivered **CI/CD pipelines** in **Azure DevOps**, including quality gates for build, automated tests, and deployment.
- Authored and maintained **xUnit** unit tests and contributed to **integration test** suites; wired both into the pipeline to improve reliability.
- Implemented/maintained **API versioning**, and improved observability via structured logging and **Log Analytics** integration.
- Integrated a **third-party B2C identity provider** (**OIDC/OAuth2**) into the backend authentication and authorization flow.

**Technologies:** Azure Container Apps, ACR, Azure DevOps, Storage Accounts, RBAC/IAM, OAuth2, APIM, Key Vault, Azure SQL, Service Bus, Application Insights, Log Analytics, .NET 8, xUnit, PowerShell, Bicep

#### Customer: Codit Customer Care · Project: Azure Alert Enricher (Belgium, remote)
**Oct 2023 – Jan 2024**
- Designed and developed a tool to enrich monitoring alerts by querying **Azure Resource Graph** and **ARM APIs** for resource metadata (subscription/resource group, resource type/name, region, tags).
- Implemented an end-to-end CI/CD pipeline in **GitHub Actions** (build/test, Docker image build + publish to **ACR**, and automated deployments).

**Technologies:** Azure Resource Graph, ARM APIs, Container Apps, ACR, GitHub Actions, Key Vault, .NET 6, Bicep, PowerShell, Bash

---

### Integration Consultant — Codit PT (Portugal, remote)
**Mar 2023 – Oct 2023**  
**Customer:** Hiscox UK (remote) · **Project:** Nexus Integration Platform

- Contributed to migration planning from **Azure App Service Environment (ASE) v2** to a cost-optimized Azure hosting model centered on **Azure Functions**.
- Implemented network isolation (**VNet integration**, **NSGs**, **UDRs**, **Private Endpoints**) for key dependencies including **Service Bus**, **Storage Accounts**, **Key Vault**, and **API Management**.
- Provisioned and updated infrastructure using **Terraform**; adapted application code and CI/CD pipelines for the new deployment and networking model.
- Defined and executed a migration validation plan (connectivity, Service Bus message flows, APIM routing/policies) and updated project documentation.

**Technologies:** Azure Functions, Logic Apps, Storage Accounts, Key Vault, Service Bus, Application Insights, Log Analytics, APIM, VNET, Azure DevOps, RBAC/IAM, KQL, Terraform

---

### Dev Support Engineer — Microsoft (Lisbon, Portugal, remote)
**Dec 2021 – Apr 2023**

- Troubleshot production incidents and configuration issues for **Azure Function Apps** and **App Service** for enterprise customers (Premier/ProDirect SLAs).
- Aggregated telemetry and logs across customer environments and performed deep-dive investigations using **KQL** (Application Insights, Log Analytics, Azure Data Explorer) to identify root causes and mitigations.
- Led/participated in incident triage with Technical Support Managers and coordinated with internal SMEs for complex cross-team escalations.

**Technologies:** Function Apps, App Services, C#, PowerShell, Azure CLI, Bash, KQL, Application Insights, Log Analytics, Azure Data Explorer, ARM templates

---

### Lead Developer / Azure Integration — Newhotel Software (Lisbon, Portugal, hybrid)
**May 2019 – Oct 2021**

- Led design and POC development of distributed integration solutions using **Azure Service Bus, Functions, Logic Apps, and Blob Storage**; drove implementation and knowledge transfer.
- Built ETL pipelines and reporting systems.
- Developed mobile applications for hotel guests (check-in/out, smart device integration).
- Migrated PMS systems to **.NET Core** and refactored shared libraries into **NuGet packages**.
- Contributed to CI/CD pipelines in **Azure DevOps**.

**Technologies:** Azure Service Bus, Function Apps, Logic Apps, C#, .NET Core, Dapper, Oracle, MongoDB, Docker, Ionic (Angular), Stripe APIs, GraphQL, SignalR, Entity Framework

---

### Freelance Developer
**Apr 2016 – Present**

- Developed Android, PC, and VR games using **Unity3D**.
- Built chatbots for **Discord** and **Twitch**.
- Implemented ML-based skin lesion classification using **CNNs** and **OpenCV**.
- Created Android services for file sync and location sharing.
- Built web applications and small-business websites.

**Technologies:** Unity3D, C#, Python, CNNs, OpenCV, Firebase, Docker, Java, .NET, MSSQL, ASP.NET, Bootstrap

---

### Lead .NET & Android Developer — Shirin Asal (Iran, on-site)
**Dec 2013 – Apr 2016**

- Led technical research, POC development, and solution design; drove implementation and knowledge transfer.
- Implemented new features, refactored and enhanced CRM and POS systems.
- Built socket-based services for GPS data ingestion.
- Developed Android applications integrated with CRM/POS workflows.
- Implemented reporting, data validation, and visualization features; contributed to SEO improvements.

**Technologies:** C#, ASP.NET, MSSQL, Java, SQLite, SOAP Web Services, Google Maps APIs, Teltonika GPS, HTML5, CSS3, JavaScript, D3.js, Bootstrap

---

## Current Top Technical Interests (in order)
- AI Agents (MCP, A2A, Semantic Kernel)
- Microsoft Azure & Azure AI Foundry
- Voice AI (Azure Speech, ElevenLabs)
- VR / AR / XR (Unity)
- C# / .NET
- GenAI 
- RAG
- CLI Tools & Automation
- Containerization & DevOps
- PowerShell & KQL

---

## Personal Interests
Metaverse, Aviation & Drones, Brain–Computer Interfaces, Automation, Robotics, Psychology, Philosophy

---

## Certifications
- Azure Fundamentals (AZ-900)
- MCITP 2008 (legacy)
- MCSE 2003 (legacy)

---

## Education
**Bachelor of Computer Engineering (40 units completed)**  
Azad University of Garmsar — 2004–2009

---

## Languages
- English — Fluent (full professional proficiency)

