# MASTER RESUME — Vasyl Volyk

*This is a complete inventory of experience, skills, and background — not a resume to send anywhere as-is. Used as source material for tailored, role-specific resumes.*

---

## Contact Information

- **Name:** Vasyl Volyk
- **Phone:** +1 343 998 1748
- **Email:** vasyl.volyk@outlook.com
- **LinkedIn:** linkedin.com/in/vasylvolyk/
- **Citizenship:** Canadian Citizen
- **Location:** Ottawa, Ontario, Canada

---

## Target Role / Headline

Senior Infrastructure & Cloud Engineer

---

## Professional Summary

Results-driven infrastructure specialist with hands-on experience designing, deploying, and securing mission-critical systems across multitenant cloud environments. Proven expertise in Azure cloud automation, cross-tenant infrastructure engineering, identity and API-driven integration, and virtualization at scale. Looking to join a friendly, collaborative team where I can share my experience and knowledge with colleagues while continuing to learn and grow, supporting enterprise cloud and infrastructure operations.

---

## Core Technical Competencies (by category)

**Cloud & Multitenant Architecture**
Large-scale Azure multitenant environments (5 tenants, 1,700 users, 500 servers); cross-tenant application deployment, automation, and Azure AD / Entra ID group & user syncing; VNets, NSGs, VPN/ExpressRoute, RBAC, Conditional Access. Hands-on AWS (familiar) — EC2, S3, and IAM policy configuration, used in a supporting capacity alongside the primary Azure environment.

**Identity & API Integration**
Microsoft Graph API for automated user onboarding/offboarding, lifecycle management, and hybrid AD-to-Entra ID group synchronization; REST API integration across business and security systems including Workday, Expensify, OnTime, Meraki, Palo Alto Networks, DigiCert, and LastPass for reporting, provisioning, and network/security automation.

**Infrastructure & Systems**
Windows/Linux server administration, Active Directory (enterprise-scale), Windows Server Network Load Balancing (NLB), Hyper-V/VMware virtualization, NAS/iSCSI storage, backup & disaster recovery, ITIL-aligned operations, capacity planning, performance tuning, patch management.

**Automation & Infrastructure as Code**
Advanced PowerShell scripting; Terraform for governance-scale, auditable provisioning (management groups, Azure subscriptions, Azure Policy definitions/assignments, IAM/RBAC role assignments) and Bicep for workload provisioning (virtual machines, internal network integration, Active Directory domain join); CI/CD pipeline design and automation (Azure DevOps, TeamCity, Git); Docker for deployment consistency; Documentation as Code (Azure DevOps Wiki + MkDocs static-site publishing pipelines).

**Application Platforms (Build/Deploy & Infra Support)**
.NET / C# ecosystem (familiar) — supported CI/CD build and deployment pipelines and infrastructure (IIS, app pools, environment configuration) for Sitecore CMS, a large-scale .NET/C# product.

**Network & Cloud Security**
Enterprise-grade next-generation firewalls (Palo Alto Networks); network security architecture; Zero Trust security principles; Defender for Cloud, Key Vault, cryptography, PKI, identity federation, secure infrastructure hardening; packet capture and protocol analysis with Wireshark for firewall, DNS, and authentication-flow troubleshooting.

**Monitoring & Observability**
Azure Monitor, Log Analytics, Application Insights, Microsoft Sentinel; Grafana, Prometheus, Zabbix, SolarWinds, LogicMonitor; proactive alerting, troubleshooting, root cause analysis, NOC/SOC-aligned monitoring and threat visibility.

**Enterprise Services & Collaboration (Office 365)**
Exchange Online mailbox administration, Microsoft Teams, SharePoint, licensing management, security & compliance policies; automated onboarding/offboarding workflows; MS SQL, VDI/Terminal Services, VoIP systems.

**Application Development & Cloud-Native Deployment**
Python (FastAPI) web application development; OAuth2/Entra ID app registration and delegated Microsoft Graph permissions for secure authentication; Azure Blob Storage; Docker containerization; Azure Container Registry (ACR) and Azure App Service deployment; Azure DevOps YAML pipelines for automated build & deploy; Jinja2/HTML templating; TLS/SSL and custom domain configuration.

**Emerging Technologies & Leadership**
AI-driven tools integrated into infrastructure operations and troubleshooting workflows, including GitHub Copilot agent mode in VS Code (proficient — regular part of workflow) for scripting (PowerShell, Terraform, Bicep), debugging/troubleshooting, and general coding across projects; leadership of a 7-person infrastructure team; vendor management and equipment procurement; SAFe, ITIL, Agile/Scrum, Waterfall methodologies.

---

## Projects

### CSV Web Viewer — Secure Azure Web Application
- Designed and built a secure, containerized web application (Python/FastAPI) for uploading and viewing CSV files, with authentication via Azure Entra ID (OAuth2, delegated Microsoft Graph permissions) and group-based access control.
- Implemented Azure Blob Storage for persistent, scalable file storage and Dockerized the application for consistent deployment across environments.
- Built and deployed the application to Azure App Service via Azure Container Registry, with an Azure DevOps YAML pipeline automating build, image push, and deployment (CI/CD).
- Configured custom domain binding, TLS/SSL certificates, and HTTPS-only enforcement for secure production access.
- Published on GitHub: github.com/vasyl-volyk/CSVwebViewer

### PowerShell Reporting & Automation Framework
- Built a modular, config-driven PowerShell automation framework that runs scheduled reporting jobs via Azure DevOps pipelines, with results uploaded automatically to Azure Blob Storage.
- Authored a wide library of report scripts integrating with Microsoft Graph API, Azure AD/Entra ID, Conditional Access, and Defender for Cloud, including a hybrid AD-to-Entra ID group synchronization validator.
- Built REST API integrations with third-party platforms — including Palo Alto Panorama, Meraki, DigiCert (SSL certificate lifecycle monitoring), LastPass Enterprise, and Workday — to centralize security, access, and asset reporting.
- Automated authentication via Azure Service Principal and orchestrated all jobs through a single runner script driven by JSON configuration, making it easy to add new reports without changing core logic.
- Published on GitHub: github.com/vasyl-volyk/azure-reporting-toolkit

### Documentation as Code — Azure DevOps Wiki + MkDocs Publishing Pipeline
- Led a Documentation as Code initiative, migrating all team documentation (~100 pages) into Azure DevOps Wiki and organizing it into a structured folder tree, replacing scattered, ad-hoc docs with a single version-controlled source of truth.
- Configured an Azure DevOps pipeline to automatically build and publish the documentation as a static website using MkDocs, keeping the published site in sync with the wiki on every change.
- Improved documentation discoverability, consistency, and maintainability across the infrastructure team.

---

## Professional Experience

### Senior Infrastructure & Cloud Engineer
**Sitecore** | Jan 2021 – Present

- Lead a 7-person infrastructure team managing a large-scale multitenant Azure environment spanning 5 tenants, 1,700 users, and 500 servers, overseeing cross-tenant application deployment, automation, and Azure AD group/user synchronization.
- Automated user lifecycle management (onboarding/offboarding) using Microsoft Graph API, standardizing account provisioning and de-provisioning across tenants and reducing manual identity administration.
- Built REST API integrations connecting core infrastructure and business systems — including Workday, Expensify, OnTime, Meraki, and Palo Alto Networks — to automate reporting, streamline provisioning, and centralize network/security data.
- Administered the Office 365 environment (Exchange Online, Teams, SharePoint), including licensing management, security and compliance policies, and fully automated onboarding/offboarding procedures.
- Designed, developed, and deployed secure cloud-based systems leveraging Azure best practices to support enterprise operations.
- Drove infrastructure-as-code and automation adoption across the environment using PowerShell, Terraform, and Bicep, reducing deployment time and human error by approximately 50% while ensuring infrastructure consistency.
- Codified Azure governance and landing-zone infrastructure in Terraform — provisioning management groups, subscriptions, Azure Policy definitions/assignments, and IAM/RBAC role assignments — fully automated through Azure DevOps pipelines for repeatable, version-controlled, and auditable deployments.
- Developed Bicep templates to provision Azure virtual machines end-to-end, including internal network connectivity and automated Active Directory domain join, standardizing VM builds and removing manual post-deployment configuration.
- Gained hands-on AWS experience (EC2, S3, IAM policy configuration), supporting workloads alongside the primary Azure environment.
- Led a Documentation as Code initiative: migrated ~100 pages of team documentation into Azure DevOps Wiki, organized into a structured folder tree, and built a pipeline that automatically publishes it as a static MkDocs website, giving the team a single, searchable, version-controlled knowledge base updated on every commit.
- Performed packet-level network troubleshooting using Wireshark, diagnosing firewall policy issues, DNS resolution failures, and a complex MFA authentication infinite-loop by analyzing captured traffic.
- Leveraged AI-driven tools and workflows — including GitHub Copilot agent mode in VS Code — to enhance operational efficiency, assist with scripting (PowerShell, Terraform, Bicep) and debugging, and augment team performance on complex infrastructure challenges.
- Identified and resolved infrastructure vulnerabilities and application deployment issues through systematic troubleshooting and root cause analysis.
- Collaborated with engineering, development, and security teams to architect optimal cloud solutions aligned with organizational objectives.
- Implemented new cloud technologies (Entra ID, Key Vault, Defender for Cloud) and led team education initiatives on security and operational best practices.
- Applied Zero Trust security principles across the multitenant Azure environment and deployed Microsoft Sentinel alongside Defender for Cloud and Azure Monitor for centralized, SOC-aligned threat detection and monitoring.
- Managed vendor relationships and equipment procurement, evaluating and negotiating with hardware/software vendors to support infrastructure budget planning and lifecycle refresh.
- Configured Windows Server Network Load Balancing (NLB) to ensure high availability for critical internal services.
- Ensured adherence to ITIL principles and security standards across the cloud infrastructure lifecycle.
- Provided and maintained the working environment for developers and technical specialists; regularly encountered new and unfamiliar tasks, requiring fast learning and quick delivery of working solutions.

### Senior DevOps Engineer
**Sitecore** | Jan 2018 – Dec 2020

- Led design and delivery of CI/CD pipelines using TeamCity and Azure DevOps, enabling rapid and reliable software delivery for Sitecore CMS, a large-scale .NET/C# product.
- Supported build, deployment, and infrastructure (IIS, app pools, environment configuration) for the .NET/C# CMS platform, working closely with development teams on release processes.
- Utilized Azure Cloud services for seamless integration, automation, and scalability across development and production environments.
- Developed infrastructure automation and deployment utilities using PowerShell, supporting infrastructure-as-code practices.
- Supported development teams within Agile/Scrum/SAFe frameworks, enabling rapid software iteration and continuous improvement.
- Collaborated with systems administrators and development teams to optimize deployment processes and infrastructure reliability.

### Infrastructure & Cloud Engineer
**Sitecore** | Sep 2015 – Dec 2017

- Ensured high availability and performance of critical infrastructure and applications through proactive monitoring and optimization.
- Implemented and supported enterprise-grade firewalls across multi-site infrastructure, enhancing security posture and compliance.
- Managed virtualized environments (Hyper-V, VMware) and executed VM migrations with minimal downtime.
- Automated daily operational tasks using PowerShell, improving efficiency and consistency across infrastructure teams.
- Administered MS Active Directory across global network infrastructure; deployed and secured development environments.

### IT Administrator
**Sitecore** | Oct 2012 – Sep 2015

- Maintained enterprise IT infrastructure backbone supporting hundreds of users across multiple locations.
- Ensured availability of critical infrastructure and applications through proactive maintenance and incident response.
- Implemented IT policies, security controls, and compliance frameworks (ITIL standards).
- Managed security systems, access controls, and infrastructure hardening initiatives.

### Senior System Administrator
**Sitecore** | 2007 – Oct 2012

- Led infrastructure team; administered MS Active Directory, Windows server clusters (2003–2012), and workstation environments (XP/Vista/7).
- Configured and managed Hyper-V clusters and NAS storage (iSCSI), supporting business continuity.
- Managed critical systems: Exchange mail servers (2003/2010), enterprise firewalls, MS SQL databases (2008/2010).
- Administered network infrastructure: switches, routing, VoIP systems, Terminal Servers; provided technical support and mentoring.

### Security Engineer
**Home Credit Bank** | Mar 2007 – Oct 2007

- Designed and implemented security analytics systems on Unix platforms for threat monitoring and incident detection.
- Developed and deployed new security infrastructure systems enhancing organizational security posture.

### Additional Experience
**Rush, Epicenter, ISD, Ukrainian State Air Traffic Service Enterprise** | 2004 – 2007

- Unix/Linux server administration (FreeBSD, Linux), communications infrastructure, mail and firewall management.
- Network design and support, local area networks, customer integration, testing software deployment (AIX).
- Developed automation tools using Shell and Perl scripting.

---

## Education

- **Bachelor's Degree in Applied Mathematics** — Dnepropetrovsk State University, 1996–2001

---

## Certifications

- Microsoft Certified: Azure Administrator Associate
- Microsoft Certified: DevOps Engineer Expert
- Microsoft Certified: Azure Security Engineer Associate
- Microsoft Certified: Azure Fundamentals
- AWS Certified Cloud Practitioner

---

## Languages

- English (Professional)
- Ukrainian (Native)
- Russian (Professional)

---

## Not yet captured (flag for future updates)

- Publications, talks, patents, awards — none currently listed. Add if applicable.
- Certification dates (skipped for now).
- Team headcount for the 2007–2012 Senior System Administrator role (different era/team than the current 7-person team).
- Optional future metrics (left qualitative for now by choice): Terraform governance provisioning (counts of management groups/subscriptions/policies/role assignments) and Bicep VM provisioning (number of VMs, time saved per build). Documentation as Code metric captured (~100 pages migrated). AWS captured at familiar level (EC2, S3, IAM) — add scale/impact if it grows.
- Open gaps surfaced during tailoring (no experience confirmed yet): Kubernetes, CloudFormation, GitHub Actions, FinOps/cost optimization, PAM, SOAR, executive technical/financial roadmap presentation. Bash to be confirmed vs. existing Shell/Perl.