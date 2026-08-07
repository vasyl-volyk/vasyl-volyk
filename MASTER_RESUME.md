# MASTER RESUME — Vasyl Volyk

*This is a complete inventory of experience, skills, and background — not a resume to send anywhere as-is. Used as source material for tailored, role-specific resumes.*

---

## Contact Information

- **Name:** Vasyl Volyk
- **Phone:** +1 343 998 1748
- **Email:** vasyl.volyk@outlook.com
- **LinkedIn:** linkedin.com/in/vasylvolyk/
- **GitHub:** github.com/vasyl-volyk/
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
Large-scale Azure multitenant environments (5 tenants, 1,700 users, 500 servers); cross-tenant application deployment, automation, and Azure AD / Entra ID group & user syncing; VNets, NSGs, VPN/ExpressRoute, RBAC, Conditional Access. Microsoft Fabric (exposure/light use) — light, occasional hands-on use in current role to store and manage group, user, and approval data backing a self-service Power Platform portal (see Power Platform entry below). Hands-on AWS (familiar) — EC2, S3, and IAM policy configuration, used in a supporting capacity alongside the primary Azure environment. GCP (exposure) — hands-on labs (Compute, IAM, etc.) completed as part of a DevOps training course; no production experience.

**Cloud Cost Management / FinOps**
Azure Cost Management + Billing (expert) — tag governance enforced via Azure Policy at the resource-group level, invoice section–based cost allocation, cost/resource owner identification for accountability, and proactive identification and remediation of unused/idle resources. Implemented initially as a dedicated project, then sustained as ongoing governance work across the multitenant environment; outcome was cost savings and improved right-targeting of spend to owners/teams (qualitative — no formal $ or % figure captured). Power BI (familiar) — connected data sources and built visuals (not full end-to-end reports) to support FinOps/cloud cost reporting, current role (Sitecore, 2021–present).

**Microsoft Power Platform**
Power Apps and Power Automate (proficient) — built and maintain a self-service access-request portal: a Power Apps GUI/web-form interface where users submit group-membership requests via button-triggered actions, paired with Power Automate workflows that execute the corresponding approval/provisioning process. Supports access management across 1,500+ users and thousands of groups, current role (Sitecore, 2021–present). Microsoft Fabric (exposure/light use) — used to store and manage the group, user, and approval data backing the portal. Power BI (familiar) — see Cloud Cost Management / FinOps.
Note: no experience with Microsoft Dynamics 365 CRM specifically — Power Platform experience here is Power Apps/Power Automate for an internal access-management portal, not CRM administration or CRM-integrated app development. See "Not yet captured" for details.

**Identity & API Integration**
Microsoft Graph API for automated user onboarding/offboarding, lifecycle management, and hybrid AD-to-Entra ID group synchronization — including an automated validator (expert level) that compares user/group attributes across both directories and flags mismatched or out-of-sync records for remediation; REST API integration across business and security systems including Workday, Expensify, OnTime, Meraki, Palo Alto Networks, DigiCert, and LastPass for reporting, provisioning, and network/security automation. LastPass Enterprise administration (expert level) — direct hands-on administration of the platform itself, not just API-level reporting: user/group management, shared folder access policies, and vault-level security policy configuration (MFA, SSO integration, password policies), across the organization's full license base (500–1,700 users), current role (Sitecore, 2021–present). Entra ID Conditional Access and internal identity/RBAC administration at scale (see Cloud & Multitenant Architecture); Azure AD B2B (proficient) — configured guest invitations and guest-access policies for external partner identity, current role (Sitecore, 2021–present); Azure AD B2C (proficient) — set up a B2C tenant and user flow for external/customer-facing application identity, current role (Sitecore, 2021–present).

**Infrastructure & Systems**
Windows/Linux server administration, Active Directory (enterprise-scale), Windows Server Network Load Balancing (NLB), Hyper-V/VMware virtualization, NAS/iSCSI storage, backup & disaster recovery, ITIL-aligned operations, capacity planning, performance tuning, patch management. Out-of-band server management — Dell iDRAC, HPE iLO (proficient) — occasional/basic use for remote console access and hardware monitoring on physical servers, spanning the KL office build (2015–2017) and current role (2021–present); note: generic IPMI protocol and Redfish API specifically not separately confirmed — vendor BMC tools (iDRAC/iLO) only. MS SQL database administration and schema design (proficient) — designed and managed database schemas supporting Exchange mail servers and other business systems (2008–2012). MongoDB (familiar) — set up and maintained backups for a MongoDB instance supporting a proof-of-concept project, approximately 6 months, IT Administrator role (Sitecore, 2012–2015); held a MongoDB certification at the time (now expired; exact name/date not recalled — add if it becomes available); no production/scale experience. Azure File Sync (advanced) — initial setup and ongoing management/troubleshooting (including error resolution) across 3 servers in company infrastructure, current role (Sitecore, 2021–present). Azure Virtual Desktop (AVD) — confirmed as of Aug 2026, no direct experience deploying or configuring AVD.

**Endpoint & Device Management**
Microsoft Intune and SCCM (System Center Configuration Manager) — device enrollment, compliance policy configuration, application deployment, and patch management within a single large-scale organization (Sitecore). Proficiency level and environment scale (device count) not yet specified — add if it becomes available. Jamf (familiar) — macOS device management for approximately 500 Mac devices, current role (Sitecore, 2021–present), alongside Intune for Windows — mixed Windows/macOS fleet administration.

**Automation & Infrastructure as Code**
Advanced PowerShell scripting; Bash scripting (proficient) — used for automation tooling, Rush/ISD, Ukrainian State Air Traffic Service Enterprise role (2004–2007), alongside Shell/Perl; Azure CLI (az cli) (proficient) — regular part of scripting/automation workflows alongside PowerShell, current role (Sitecore, 2021–present); Azure Functions (expert) — timer-triggered PowerShell Function Apps for automated operational tasks (e.g., Azure DNS zone backup); Terraform for governance-scale, auditable provisioning (management groups, Azure subscriptions, Azure Policy definitions/assignments, IAM/RBAC role assignments) and Bicep for workload provisioning (virtual machines, internal network integration, Active Directory domain join); ARM (Azure Resource Manager) templates (familiar) — used earlier for deploying Azure VMs with internal network connectivity and Active Directory domain join, the same workload later standardized on Bicep going forward; ARM is prior/adjacent experience rather than current active tooling. CI/CD pipeline design and automation (Azure DevOps — Pipelines, Repos, Boards (expert), Artifacts (proficient); TeamCity, Git); Docker for deployment consistency (no orchestrator — Kubernetes/AKS/EKS/ECS/Nomad/Swarm not used; confirmed as of Jul 2026); GitOps (ArgoCD) — exposure only, via personal/training labs; no production experience; Documentation as Code (Azure DevOps Wiki + MkDocs static-site publishing pipelines); rolling/canary-style deployment rollouts for VM/server updates via custom PowerShell scripting (familiar) — minimizing environment-wide risk during updates, qualitative outcome, no formal metrics captured. Ansible — confirmed as of Aug 2026, no experience (no direct or adjacent config-management tool — Puppet, Chef, Salt also not used); existing IaC/automation tooling is Terraform, Bicep, ARM (prior), PowerShell, and Bash only.

**Application Platforms (Build/Deploy & Infra Support)**
.NET / C# ecosystem (familiar) — supported CI/CD build and deployment pipelines and infrastructure (IIS, app pools, environment configuration) for Sitecore CMS, a large-scale .NET/C# product.

**Network & Cloud Security**
Enterprise-grade next-generation firewalls (Palo Alto Networks); network security architecture including hub-spoke topology (expert) — multiple VNets connected to a centralized Azure Firewall hub; Private Endpoints (expert) for securing qualifying Azure resources on the internal network; Azure Private DNS (expert) — internal DNS zone registration and internal IP resolution for privately-connected resources; Zero Trust security principles; Defender for Cloud, Key Vault, cryptography, PKI, identity federation, secure infrastructure hardening; SSH administration and SFTP/FTP file transfer, plus SSL/TLS certificate configuration (expert) — mixed use covering secure file transfers with vendors/partners, SSH access for Linux server administration, and SSL/TLS certificate configuration on services, current role (Sitecore, 2021–present); Wiz (familiar) — reviewing cloud vulnerability and misconfiguration findings and coordinating remediation, current role (Sitecore, 2021–present); SOC 2 Type 2 compliance — one of several key points of contact for the audit (not sole owner of the auditor relationship) across approximately 5 annual audit cycles (Sitecore, 2021–present); supported technical and infrastructure-related controls (access, logging, policy), coordinated evidence collection, and addressed auditor requests in partnership with relevant teams; packet capture and protocol analysis with Wireshark for firewall, DNS, and authentication-flow troubleshooting; new-site network design (LAN/WAN/VPN/firewall) for greenfield office buildout (Kuala Lumpur APAC office, 2015–2017). Cloudflare (familiar) — DNS and WAF configuration via admin console, current role (Sitecore, 2021–present).

**ISP / Telecom Vendor Management**
Evaluated and negotiated with ISP/telecom vendors across 7 country offices, leading consolidation from per-country ISP contracts to a single global ISP provider — improving pricing, standardizing SLA terms, and simplifying ongoing vendor management. Spans the Kuala Lumpur greenfield office buildout (2015–2017) and continues in the current role (Sitecore, 2021–present). Qualitative outcome; exact consolidation completion timeframe and formal SLA/cost metrics not yet captured — add if they become available **[NEEDS INPUT]**.

**Monitoring & Observability**
Azure Monitor, Log Analytics, Application Insights, Microsoft Sentinel — used for security incident investigation and root cause analysis (Sentinel alert rules, Log Analytics queries); Grafana, Prometheus, Zabbix, SolarWinds, LogicMonitor — used for proactive infrastructure alerting to detect and address issues before impact; NOC/SOC-aligned monitoring and threat visibility. (Threshold-based alerting and RCA practice; not a formal SLO/SLI/error-budget framework.) HP OVO, SCOM, SiteScope — confirmed as of Aug 2026, no experience.

**Incident & IT Service Management Tooling**
ServiceNow — used for incident logging and tracking of issues responded to, as well as broader IT service management processes (change management, problem management), current role (Sitecore, 2021–present). Not yet confirmed: Microsoft ICM (Incident Case Management) or an equivalent fleet-scale incident platform specifically — revisit if gained. AutoSys scheduling tool — confirmed as of Aug 2026, no experience.

**On-Call Operations**
Participated in a 3-person on-call rotation (Senior Infrastructure & Cloud Engineer role) carrying a phone and responding to incidents escalated from the support service desk, at a frequency of roughly one incident per week. (Participant in an existing rotation; did not personally design the rotation schedule or escalation policy.)

**Enterprise Services & Collaboration (Office 365)**
Exchange Online mailbox administration, Microsoft Teams, SharePoint, licensing management, security & compliance policies; automated onboarding/offboarding workflows; VDI/Terminal Services, VoIP systems. Google Workspace — no experience (Microsoft 365/Exchange Online only; confirmed as of Jul 2026).

**Application Development & Cloud-Native Deployment**
Python (FastAPI) web application development; OAuth2/Entra ID app registration and delegated Microsoft Graph permissions for secure authentication; Azure Blob Storage; Docker containerization; Azure Container Registry (ACR) and Azure App Service deployment; Azure DevOps YAML pipelines for automated build & deploy; Jinja2/HTML templating; TLS/SSL and custom domain configuration. Azure Queue Storage, Azure Table Storage — confirmed as of Aug 2026, no experience (Blob Storage only). Azure pub/sub messaging (Service Bus, Event Grid, Event Hub) — confirmed as of Aug 2026, no experience. Azure Cosmos DB — confirmed as of Aug 2026, no experience. Ruby, PHP — confirmed as of Aug 2026, no scripting/development experience with either. React / JavaScript frameworks — confirmed as of Aug 2026, no experience; existing web development experience is Python/FastAPI + Jinja2/HTML templating only.

**Emerging Technologies & Leadership**
AI-driven tools integrated into infrastructure operations and troubleshooting workflows, including GitHub Copilot agent mode in VS Code (proficient — regular part of workflow) for scripting (PowerShell, Terraform, Bicep), debugging/troubleshooting, and general coding across projects; Claude (Claude Code, Claude Desktop/Projects) (advanced) — used for software development, information gathering/scraping, and documentation improvement; leadership of a 7-person infrastructure team; company APAC expansion — major contributor to greenfield IT infrastructure buildout for a new 100+ staff development office (Kuala Lumpur); vendor management and equipment procurement; SAFe, ITIL, Agile/Scrum, Waterfall methodologies.

---

## Projects

### Kuala Lumpur APAC Office Build — IT Infrastructure from Scratch
- Major contributor (alongside others) to standing up full IT infrastructure for Sitecore's new Kuala Lumpur development office as the company expanded into APAC, scaling to support 100+ staff.
- Scope included network design and setup (LAN/WAN/VPN/firewall), server and Active Directory/domain provisioning, end-user device/workstation environment, vendor selection and procurement, and coordination of the physical site/datacenter buildout.
- Included occasional/basic use of Dell iDRAC / HPE iLO for remote console access and hardware monitoring on physical servers during buildout and ongoing operations.
- Evaluated and negotiated ISP/telecom vendor contracts as part of the office buildout, contributing to a broader consolidation effort across country offices (see ISP/Telecom Vendor Management competency).
- Timeframe: 2015–2017 (Infrastructure & Cloud Engineer role) — exact start/end dates within this window **[NEEDS INPUT]**.

### CSV Web Viewer — Secure Azure Web Application
- Designed and built a secure, containerized web application (Python/FastAPI) for uploading and viewing CSV files, with authentication via Azure Entra ID (OAuth2, delegated Microsoft Graph permissions) and group-based access control.
- Implemented Azure Blob Storage for persistent, scalable file storage and Dockerized the application for consistent deployment across environments.
- Built and deployed the application to Azure App Service via Azure Container Registry, with an Azure DevOps YAML pipeline automating build, image push, and deployment (CI/CD).
- Configured custom domain binding, TLS/SSL certificates, and HTTPS-only enforcement for secure production access.
- Published on GitHub: github.com/vasyl-volyk/CSVwebViewer

### PowerShell Reporting & Automation Framework
- Built a modular, config-driven PowerShell automation framework that runs scheduled reporting jobs via Azure DevOps pipelines, with results uploaded automatically to Azure Blob Storage.
- Authored a wide library of report scripts integrating with Microsoft Graph API, Azure AD/Entra ID, Conditional Access, and Defender for Cloud, including a hybrid AD-to-Entra ID group synchronization validator that compares user/group attributes across both directories and flags mismatched or out-of-sync records for remediation (expert level).
- Built REST API integrations with third-party platforms — including Palo Alto Panorama, Meraki, DigiCert (SSL certificate lifecycle monitoring), LastPass Enterprise, and Workday — to centralize security, access, and asset reporting.
- Automated authentication via Azure Service Principal and orchestrated all jobs through a single runner script driven by JSON configuration, making it easy to add new reports without changing core logic.
- Published on GitHub: github.com/vasyl-volyk/azure-reporting-toolkit

### Azure DNS Zone Backup — Serverless Automation
- Built a timer-triggered Azure Function App (PowerShell) to automatically back up all Azure DNS zones on a schedule, addressing a gap in native Azure functionality (no built-in DNS zone backup).
- Authenticated to Azure resources using Managed Identity and persisted backups to Azure Blob Storage.
- Outcome: 100% protection of DNS zone configurations against accidental deletion or modification, with a reliable restore point always available.

### Documentation as Code — Azure DevOps Wiki + MkDocs Publishing Pipeline
- Led a Documentation as Code initiative, migrating all team documentation (~100 pages) into Azure DevOps Wiki and organizing it into a structured folder tree, replacing scattered, ad-hoc docs with a single version-controlled source of truth.
- Configured an Azure DevOps pipeline to automatically build and publish the documentation as a static website using MkDocs, keeping the published site in sync with the wiki on every change.
- Improved documentation discoverability, consistency, and maintainability across the infrastructure team.

### Self-Service Access Portal — Power Platform (Power Apps + Power Automate) + Microsoft Fabric
- Built and maintain a self-service access-request portal (proficient level) using Power Apps for the GUI/web-form interface — users submit group-membership requests via button-triggered actions.
- Built corresponding Power Automate workflows that execute the approval/provisioning process triggered by the form submissions.
- Used Microsoft Fabric (light/occasional hands-on use) to store and manage the group, user, and approval data backing the portal.
- Supports access management across 1,500+ users and thousands of groups, current role (Sitecore, 2021–present).

---

## Professional Experience

### Senior Infrastructure & Cloud Engineer
**Sitecore** | Jan 2021 – Present

- Lead a 7-person infrastructure team managing a large-scale multitenant Azure environment spanning 5 tenants, 1,700 users, and 500 servers, overseeing cross-tenant application deployment, automation, and Azure AD group/user synchronization.
- Implemented Azure cost governance as a FinOps practice (expert level): enforced resource-group tagging via Azure Policy, used invoice sections for cost allocation, identified resource/cost owners for accountability, and proactively identified unused/idle resources — initially delivered as a project, then sustained as ongoing governance work, driving cost savings and improved right-targeting of spend across the multitenant environment. Connected data sources and built Power BI visuals (familiar level) to support FinOps/cloud cost reporting.
- Automated user lifecycle management (onboarding/offboarding) using Microsoft Graph API, standardizing account provisioning and de-provisioning across tenants and reducing manual identity administration.
- Built and maintained a hybrid AD-to-Entra ID group synchronization validator (expert level) that compares user/group attributes across both directories and flags mismatched or out-of-sync records for remediation, ensuring identity data consistency across the hybrid environment.
- Built REST API integrations connecting core infrastructure and business systems — including Workday, Expensify, OnTime, Meraki, and Palo Alto Networks — to automate reporting, streamline provisioning, and centralize network/security data.
- Administered LastPass Enterprise (expert level) across the organization's full license base (500–1,700 users): user/group management, shared folder access policies, and vault-level security policy configuration (MFA, SSO integration, password policies) — direct admin-console administration, in addition to REST API integration for centralized reporting.
- Configured Azure AD B2B (proficient level) guest invitations and guest-access policies for external partner identity, and set up an Azure AD B2C tenant and user flow (proficient level) for external/customer-facing application identity.
- Built and maintain a self-service access-request portal using Power Apps and Power Automate (proficient level): a GUI/web-form interface where users submit group-membership requests via button-triggered actions, paired with automated approval/provisioning workflows — supporting access management across 1,500+ users and thousands of groups. Used Microsoft Fabric (light/occasional use) to store and manage the underlying group, user, and approval data.
- Administered the Office 365 environment (Exchange Online, Teams, SharePoint), including licensing management, security and compliance policies, and fully automated onboarding/offboarding procedures.
- Managed endpoint devices using Microsoft Intune and SCCM (Windows) and Jamf (macOS, ~500 devices, familiar level), including device enrollment, compliance policy configuration, application deployment, and patch management across a mixed Windows/macOS fleet.
- Designed, developed, and deployed secure cloud-based systems leveraging Azure best practices to support enterprise operations.
- Drove infrastructure-as-code and automation adoption across the environment using PowerShell, Azure CLI (az cli), Terraform, and Bicep, reducing deployment time and human error by approximately 50% while ensuring infrastructure consistency.
- Codified Azure governance and landing-zone infrastructure in Terraform — provisioning management groups, subscriptions, Azure Policy definitions/assignments, and IAM/RBAC role assignments — fully automated through Azure DevOps pipelines for repeatable, version-controlled, and auditable deployments.
- Developed Bicep templates to provision Azure virtual machines end-to-end, including internal network connectivity and automated Active Directory domain join, standardizing VM builds and removing manual post-deployment configuration; this workflow was earlier implemented using ARM templates (familiar level) before being standardized on Bicep.
- Performed rolling/canary-style deployment rollouts for VM and server updates using custom PowerShell scripting, minimizing the risk of environment-wide issues during updates (familiar level; qualitative outcome, no formal metrics captured).
- Built a timer-triggered Azure Function App (PowerShell) to automatically back up all Azure DNS zones to Blob Storage, authenticating via Managed Identity — closing a gap in native Azure functionality and providing 100% protection of DNS zone configurations against accidental deletion or modification.
- Designed and implemented a hub-spoke network architecture, connecting multiple VNets to a centralized Azure Firewall hub; secured qualifying Azure resources requiring internal-only connectivity via Private Endpoints and registered them in Azure Private DNS zones with internal IP addresses for internal resolution.
- Administered SSH access for Linux server administration, managed SFTP/FTP secure file transfers with vendors and partners, and configured SSL/TLS certificates on services (expert level) as part of ongoing infrastructure operations.
- Occasional/basic use of Dell iDRAC / HPE iLO for out-of-band remote console access and hardware monitoring on physical servers (proficient level).
- Logged and tracked incidents in ServiceNow, also using it for broader IT service management processes including change management and problem management.
- Gained hands-on AWS experience (EC2, S3, IAM policy configuration), supporting workloads alongside the primary Azure environment.
- Led a Documentation as Code initiative: migrated ~100 pages of team documentation into Azure DevOps Wiki, organized into a structured folder tree, and built a pipeline that automatically publishes it as a static MkDocs website, giving the team a single, searchable, version-controlled knowledge base updated on every commit.
- Tracked and managed infrastructure and operations work using Azure Boards (expert level); used Azure Artifacts to host and distribute feeds of operational reports and pre-configuration files across the team.
- Performed packet-level network troubleshooting using Wireshark, diagnosing firewall policy issues, DNS resolution failures, and a complex MFA authentication infinite-loop by analyzing captured traffic.
- Participated in a 3-person on-call rotation, carrying a phone and responding to incidents escalated from the support service desk at a frequency of roughly one incident per week.
- Served as one of several key points of contact for Sitecore's SOC 2 Type 2 compliance audits across approximately 5 annual audit cycles (2021–present, not sole owner of the auditor relationship): supported technical and infrastructure-related controls (access, logging, policy), coordinated evidence collection, and addressed auditor requests in partnership with relevant teams.
- Reviewed cloud vulnerability and misconfiguration findings in Wiz (familiar level) and coordinated remediation with relevant teams.
- Continued evaluating and negotiating ISP/telecom vendor relationships as part of the broader global ISP consolidation effort spanning 7 country offices (see ISP/Telecom Vendor Management competency).
- Leveraged AI-driven tools and workflows — including GitHub Copilot agent mode in VS Code and Claude (Claude Code, Claude Desktop/Projects) — to enhance operational efficiency, assist with scripting (PowerShell, Terraform, Bicep), debugging, information gathering, and documentation improvement, augmenting team performance on complex infrastructure challenges.
- Identified and resolved infrastructure vulnerabilities and application deployment issues through systematic troubleshooting and root cause analysis.
- Collaborated with engineering, development, and security teams to architect optimal cloud solutions aligned with organizational objectives.
- Implemented new cloud technologies (Entra ID, Key Vault, Defender for Cloud) and led team education initiatives on security and operational best practices.
- Applied Zero Trust security principles across the multitenant Azure environment and deployed Microsoft Sentinel alongside Defender for Cloud and Azure Monitor for centralized, SOC-aligned threat detection and monitoring.
- Managed vendor relationships and equipment procurement, evaluating and negotiating with hardware/software vendors to support infrastructure budget planning and lifecycle refresh.
- Configured Windows Server Network Load Balancing (NLB) to ensure high availability for critical internal services.
- Set up and managed Azure File Sync (advanced level) across 3 servers in company infrastructure, including ongoing troubleshooting and error resolution.
- Configured and maintained Cloudflare DNS and WAF settings (familiar level) via the admin console.
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

- Major contributor to building the IT infrastructure for Sitecore's new Kuala Lumpur (APAC) development office from scratch as the company expanded into the APAC region, scaling to support 100+ staff — covering network design (LAN/WAN/VPN/firewall), server and Active Directory/domain setup, end-user workstation environment, vendor selection and procurement, and physical site/datacenter buildout coordination.
- Ensured high availability and performance of critical infrastructure and applications through proactive monitoring and optimization.
- Implemented and supported enterprise-grade firewalls across multi-site infrastructure, enhancing security posture and compliance.
- Managed virtualized environments (Hyper-V, VMware) and executed VM migrations with minimal downtime.
- Evaluated and negotiated ISP/telecom vendor contracts as part of the office buildout and the broader multi-country ISP consolidation effort (see ISP/Telecom Vendor Management competency).
- Occasional/basic use of Dell iDRAC / HPE iLO for out-of-band remote console access and hardware monitoring on physical servers during the office buildout (proficient level).
- Automated daily operational tasks using PowerShell, improving efficiency and consistency across infrastructure teams.
- Administered MS Active Directory across global network infrastructure; deployed and secured development environments.

### IT Administrator
**Sitecore** | Oct 2012 – Sep 2015

- Maintained enterprise IT infrastructure backbone supporting hundreds of users across multiple locations.
- Ensured availability of critical infrastructure and applications through proactive maintenance and incident response.
- Implemented IT policies, security controls, and compliance frameworks (ITIL standards).
- Managed security systems, access controls, and infrastructure hardening initiatives.
- Set up and maintained backups for a MongoDB instance (familiar level) supporting a proof-of-concept project, over approximately 6 months. Earned a MongoDB certification at the time (now expired; exact name/date not recalled — add if recalled).

### Senior System Administrator
**Sitecore** | 2007 – Oct 2012

- Led infrastructure team; administered MS Active Directory, Windows server clusters (2003–2012), and workstation environments (XP/Vista/7).
- Configured and managed Hyper-V clusters and NAS storage (iSCSI), supporting business continuity.
- Managed critical systems: Exchange mail servers (2003/2010), enterprise firewalls, MS SQL databases (2008/2010).
- Designed and managed MS SQL database schemas (proficient level) supporting Exchange mail servers and other business systems.
- Administered network infrastructure: switches, routing, VoIP systems, Terminal Servers; provided technical support and mentoring.

### Security Engineer
**Home Credit Bank** | Mar 2007 – Oct 2007

- Designed and implemented security analytics systems on Unix platforms for threat monitoring and incident detection.
- Developed and deployed new security infrastructure systems enhancing organizational security posture.

### IT Administrator (Managed Services / Multi-Client Support)
**Epicenter** | ~2004 – 2007 (exact start/end dates and sequencing relative to other roles in this period **[NEEDS INPUT]**) — approx. 1 year in this role

- Provided subscription-based, on-site IT infrastructure management and support for approximately 20 external client companies, covering the full range of IT administrative needs — servers, networking, printers, and client/end-user devices.
- Acted as the on-site technical resource for each client engagement, diagnosing and resolving infrastructure and end-user issues across a variety of small-business environments.
- Managed relationships and technical delivery across a multi-client, multi-environment support model (no formal metrics captured — client count only).

### Additional Experience
**Rush, ISD, Ukrainian State Air Traffic Service Enterprise** | 2004 – 2007

- Unix/Linux server administration (FreeBSD, Linux), communications infrastructure, mail and firewall management.
- Network design and support, local area networks, customer integration, testing software deployment (AIX).
- Developed automation tools using Bash, Shell, and Perl scripting (Bash — proficient level).

---

## Education

- **Master's degree in Applied Mathematics** — Dnipropetrovsk National University, Ukraine, 1996–2001

---

## Certifications

- Microsoft Certified: Azure Administrator Associate
- Microsoft Certified: DevOps Engineer Expert
- Microsoft Certified: Azure Security Engineer Associate
- Microsoft Certified: Azure Fundamentals
- AWS Certified Cloud Practitioner
- MongoDB certification (expired) — held during IT Administrator role, Sitecore (~2012–2015); exact name/date not recalled — add if it becomes available.

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
- Kuala Lumpur APAC office build (2015–2017, Infrastructure & Cloud Engineer role): exact start/end dates within the 2015–2017 window not yet specified — add if it becomes available. Also add: whether this was a permanent on-site posting vs. remote/periodic travel, team size specifically on this project (vs. the 100+ staff the office grew to support), and any metrics (timeline to stand up the office, budget, downtime/incident figures) if they become available.
- Optional future metrics (left qualitative for now by choice): Terraform governance provisioning (counts of management groups/subscriptions/policies/role assignments) and Bicep VM provisioning (number of VMs, time saved per build). Documentation as Code metric captured (~100 pages migrated). AWS captured at familiar level (EC2, S3, IAM) — add scale/impact if it grows. Azure FinOps/cost governance captured (expert level, tagging/invoice sections/owner ID/idle resource cleanup) — add hard $ or % savings figure if it becomes available. Hub-spoke/Private Endpoints/Private DNS scale (number of VNets, endpoints, or zones) — add if it becomes available; currently qualitative only. On-call rotation captured at participant level (3-person rotation, ~weekly incidents) — add MTTR/noise-reduction figures if they become available, and note if role evolves to include designing the rotation/escalation policy itself. Rolling/canary deployment rollouts (familiar level, custom PowerShell scripting for VM/server updates) — add scale/frequency/incident-reduction metrics if they become available. AD-to-Entra ID reconciliation validator (expert level, reports + flags mismatches) — add scale (number of accounts/groups covered, frequency) if it becomes available. MS SQL schema design (proficient, 2007–2012) — add scale/specifics if recalled. SOC 2 audit participation (Sitecore) — scope now captured (one of several key points of contact, ~5 annual cycles, 2021–present, technical/infra controls + evidence coordination); revisit if role evolves toward sole ownership of the auditor relationship or toward leading expansion of Trust Services Criteria (e.g., Confidentiality, Availability) beyond Security.
- GitOps (ArgoCD) — confirmed as of Jul 2026, exposure level only via personal/training labs; no production experience. Revisit if production experience is gained.
- Open gaps surfaced during tailoring (no experience confirmed yet): Kubernetes/EKS/AKS (confirmed as of Jul 2026 — no experience, Docker only, no orchestrator of any kind), Helm (confirmed as of Jul 2026 — no experience, follows from no Kubernetes experience), Puppet, CloudFormation, Ansible (confirmed — Terraform/Bicep only; no adjacent config-management tool either — Puppet/Chef/Salt also not used, confirmed Aug 2026), ELK/OpenSearch stack (confirmed — no experience), container security tools — Falco, OPA/Gatekeeper, image scanning, runtime protection (confirmed — no experience), AWS Security Specialist/OSCP/CKS/GCPN/CISSP certs (confirmed — none held), Azure Data Factory, Synapse, Databricks, Jupyter Notebook (confirmed as of Jul 2026 — no hands-on experience; Fabric confirmed at light/occasional use), Kubecost/OpenCost, CUR-based pipelines, Karpenter, Graviton, AWS Savings Plans/RIs, GitHub Actions, Go, PAM, SOAR, executive technical/financial roadmap presentation. Bash confirmed as of Aug 2026 — proficient level, Rush/ISD role (2004–2007) alongside Shell/Perl. OpenTelemetry/distributed tracing (confirmed as of Jul 2026 — no experience; existing tracing-adjacent work is Wireshark packet capture and Application Insights APM, not OpenTelemetry specifically). Chaos engineering/fault-injection testing (confirmed as of Jul 2026 — no experience). Formal production-readiness reviews partnering with software teams pre-launch (confirmed as of Jul 2026 — no experience; adjacent CI/CD deployment support exists but not a formal PRR process). Web3/crypto-native engineering (confirmed as of Jul 2026 — no experience). Formal SLO/SLI/error-budget frameworks (confirmed as of Jul 2026 — no experience; existing practice is threshold-based alerting and RCA via Sentinel/Log Analytics for security and Grafana/Prometheus/Zabbix for proactive infra monitoring, not formal SLO definitions). Jenkins, GitLab CI, and AWS CodePipeline (confirmed as of Jul 2026 — no direct experience; existing CI/CD tooling is TeamCity and Azure DevOps Pipelines only). CloudWatch (confirmed as of Jul 2026 — no experience; existing AWS work is EC2/S3/IAM at familiar level, monitoring done via Azure Monitor/Grafana/Prometheus/Zabbix, not CloudWatch). Formal Master Data Management (MDM)/master data/reference data concepts (confirmed as of Jul 2026 — no experience beyond the AD-to-Entra ID reconciliation validator, which is attribute comparison/flagging, not a formal MDM discipline). Client-facing/consulting experience — note: the Epicenter role (~2004–2007) involved on-site IT support for ~20 external client companies, which is genuine client-facing experience; revisit any tailored resumes built before this note (e.g., the CluedIn Data Implementation Consultant resume) to reflect this if relevant. Formal data quality/governance rule configuration on a dedicated data platform (confirmed as of Jul 2026 — closest adjacent experience is Azure cost/tag governance and the AD-to-Entra ID reconciliation validator, not a data quality/mastering rules engine).
- GCP: confirmed exposure only (Jul 2026) — hands-on labs (Compute, IAM, etc.) completed as part of a DevOps training course; no production experience. Revisit if production GCP work is gained.
- Government of Canada security clearance: confirmed as of Jul 2026 — does NOT currently hold Reliability or higher. Relevant for future gov't-adjacent postings; revisit if clearance is obtained.
- RMM/PSA platforms (ConnectWise, NinjaOne, etc.) — confirmed as of Jul 2026, no experience. Relevant for MSP-context roles; revisit if gained.
- DLP (Data Loss Prevention) and formal compliance framework work (HIPAA, HITRUST) — confirmed as of Jul 2026, no direct experience captured. SOC 2 experience is now captured in more detail (Sitecore audit participation — one of several key points of contact, ~5 annual cycles, technical controls implementation + evidence coordination for auditors; see Network & Cloud Security and Senior Infrastructure & Cloud Engineer role). Revisit HIPAA/HITRUST if gained.
- Intune/SCCM proficiency level and environment scale (device count) not yet specified — add if it becomes available. Jamf (macOS) now captured: familiar level, ~500 devices, current role (2021–present).
- Epicenter role exact dates and sequencing relative to Rush/ISD/Ukrainian State ATSE (all within 2004–2007) — add if it becomes available.
- Out-of-band server management confirmed as of Jul 2026: Dell iDRAC / HPE iLO, proficient level, occasional/basic use — spans KL office build (2015–2017) and current role (2021–present). Generic IPMI protocol and Redfish API specifically not separately confirmed — only vendor tools (iDRAC/iLO) used. Bare-metal provisioning at scale (racking, datacenter-wide hardware rollout, fleet-level BMC automation/scripting) not confirmed — revisit if gained.
- Compliance automation platforms (Vanta, Drata, Secureframe) — confirmed as of Jul 2026, no experience. Sitecore's SOC 2 program details (tooling used to manage the audit, if any) not specified. Revisit if Vanta or similar platform experience is gained.
- Google Workspace — confirmed as of Jul 2026, no experience. Existing enterprise collaboration experience is Microsoft 365 (Exchange Online, Teams, SharePoint) only. Revisit if gained.
- Vulnerability management / CSPM tooling — Wiz confirmed as of Jul 2026: familiar level, current role (2021–present), reviewing cloud vulnerability/misconfiguration findings and coordinating remediation. Not confirmed: ownership of a formal vulnerability management program (scanning cadence, SLA tracking, patch remediation metrics) — this is findings review/remediation coordination, not a formally owned vuln-management process end-to-end.
- SOC 2 program ownership/expansion — confirmed as of Jul 2026: role has been one of several key points of contact for the audit (not sole owner of the auditor relationship), supporting technical/infrastructure controls and evidence coordination across ~5 annual cycles. No experience owning/expanding Trust Services Criteria scope (e.g., adding Confidentiality or Availability to an existing Security-only audit) or acting as sole auditor-relationship owner. Revisit if this scope is gained.
- **Cisco core networking (routing, switching, enterprise infrastructure)** — confirmed as of Jul 2026: NO experience. No CCNA/CCNP/CCIE certifications held. Existing network security experience is Palo Alto Networks (NGFW) and Azure-native networking (VNets, NSGs, hub-spoke, Private Endpoints/DNS), not Cisco hardware/IOS. Revisit if gained.
- **Cisco VPN / Cisco Firepower Management Center (FMC)** — confirmed as of Jul 2026: NO experience. Closest adjacent experience is Palo Alto Networks NGFW policy management and Azure VPN/ExpressRoute, not Cisco-specific tooling. Revisit if gained.
- **Passive Optical Network (PON) design/implementation** — confirmed as of Jul 2026: NO experience. Existing physical network design experience is LAN/WAN/VPN/firewall for the Kuala Lumpur greenfield office buildout (2015–2017), not PON/fiber-optic architecture specifically. Revisit if gained.
- **NetBox (or equivalent IPAM/network source-of-truth tooling)** — confirmed as of Jul 2026: NO experience with NetBox or an equivalent dedicated IPAM platform. Revisit if gained.
- **Degree level/naming discrepancy (resolved Jul 2026):** the credential is a Ukrainian "Dyplom spetsialista" (Diploma of Specialist), not a Western-style Bachelor's degree. A third-party credential evaluation (2026) confirmed Canadian equivalency as a **Master's degree**. Tailored resumes built before this date list it as a Bachelor's degree and should be revisited/reissued if being reused.
- **Power BI — confirmed as of Jul 2026:** familiar level — connected data sources and built visuals (not full end-to-end report ownership) to support FinOps/cloud cost reporting, current role (Sitecore, 2021–present). Revisit if usage deepens toward full report/dashboard ownership. Tableau still not confirmed — no experience.
- **Azure CLI (az cli) — confirmed as of Jul 2026:** proficient level — regular part of scripting/automation workflows alongside PowerShell, current role (Sitecore, 2021–present).
- **1Password Enterprise Password Manager (EPM)** — confirmed as of Jul 2026: NO direct experience with 1Password specifically. Genuinely equivalent experience held instead: LastPass Enterprise administration at expert level (users/groups, shared folders, vault-level security policies including MFA/SSO/password policies), across the org's full 500–1,700-user license base, current role (Sitecore, 2021–present) — see Identity & API Integration competency and Senior Infrastructure & Cloud Engineer role. Revisit if direct 1Password experience is gained.
- **ARM (Azure Resource Manager) templates — confirmed as of Aug 2026:** familiar level — used to deploy Azure VMs with internal network connectivity and Active Directory domain join; this was the earlier approach for that workflow, later standardized on Bicep. Treat as prior/adjacent IaC experience rather than current active tooling.
- **Azure Virtual Desktop (AVD)** — confirmed as of Aug 2026: NO experience deploying or configuring AVD.
- **Azure Queue Storage / Azure Table Storage** — confirmed as of Aug 2026: NO experience. Existing Azure Storage experience is Blob Storage only (CSV Web Viewer project, PowerShell reporting framework, DNS backup automation).
- **Azure pub/sub messaging (Service Bus, Event Grid, Event Hub)** — confirmed as of Aug 2026: NO experience.
- **Azure Cosmos DB** — confirmed as of Aug 2026: NO experience.
- **Azure AD B2C / B2B — confirmed as of Aug 2026:** proficient level — configured Azure AD B2B guest invitations and guest-access policies for external partner identity, and set up an Azure AD B2C tenant and user flow for external/customer-facing application identity, current role (Sitecore, 2021–present). Revisit if scale/scope expands (e.g., number of external partners/apps, custom policies).
- **MongoDB** — confirmed as of Aug 2026: familiar level — setup and backup administration for a ~6-month POC project, IT Administrator role (Sitecore, 2012–2015); held a MongoDB certification at the time, now expired (name/date not recalled — add if recalled). No production/scale experience. No experience with Elasticsearch or Redis specifically — revisit if gained.
- **Elasticsearch, Redis** — confirmed as of Aug 2026: NO experience. Revisit if gained.
- **CDN — confirmed as of Aug 2026:** Cloudflare (familiar) — DNS and WAF configuration via admin console, current role (Sitecore, 2021–present). No experience with Azure Front Door/CDN, Fastly, Akamai, or CloudFront specifically. Note: this experience is DNS/WAF-focused, not confirmed for CDN edge-caching/content-delivery configuration specifically — revisit if that scope is used.
- **Azure File Sync — confirmed as of Aug 2026:** advanced level — initial setup and ongoing management/troubleshooting across 3 servers in company infrastructure, current role (Sitecore, 2021–present).
- **OpenTofu** — confirmed as of Aug 2026: not separately confirmed; existing IaC experience is Terraform (governance-scale) and Bicep. Revisit if OpenTofu specifically is used.
- **Bash scripting — confirmed as of Aug 2026:** proficient level — Rush/ISD, Ukrainian State Air Traffic Service Enterprise role (2004–2007), alongside Shell/Perl automation tooling. Distinct confirmation from the pre-existing Shell/Perl entry.
- **SSH administration, SFTP/FTP file transfer, SSL/TLS certificate configuration — confirmed as of Aug 2026:** expert level — mixed use (secure file transfers with vendors/partners, SSH access for Linux server administration, SSL/TLS cert configuration on services), current role (Sitecore, 2021–present).
- **Ansible / config-management tools (Puppet, Chef, Salt) — confirmed as of Aug 2026:** NO experience with Ansible or any adjacent config-management tool. Existing automation/IaC tooling is Terraform, Bicep, ARM (prior), PowerShell, and Bash only. Revisit if gained.
- **HP OVO, SCOM, SiteScope (monitoring) — confirmed as of Aug 2026:** NO experience. Existing monitoring tooling is Azure Monitor/Sentinel/Log Analytics/Application Insights and Grafana/Prometheus/Zabbix/SolarWinds/LogicMonitor.
- **AutoSys (job scheduling) — confirmed as of Aug 2026:** NO experience.
- **Secure Transport (secure file transfer product) — confirmed as of Aug 2026:** NO experience with this specific product. SSH/SFTP/FTP administration confirmed separately at expert level, current role.
- **Ruby, PHP scripting — confirmed as of Aug 2026:** NO experience with either.
- **HP ALM or other formal QA tooling — confirmed as of Aug 2026:** NO experience.
- **React / JavaScript frameworks — confirmed as of Aug 2026:** NO experience. Existing web development experience is Python/FastAPI + Jinja2/HTML templating only.
- **Microsoft Dynamics 365 CRM — confirmed as of Aug 2026:** NO experience. Existing Power Platform experience (Power Apps + Power Automate, proficient, self-service access-request portal — see Microsoft Power Platform competency) is an internal access-management tool, not CRM administration, CRM configuration, or CRM-integrated app development. Revisit if D365 CRM experience is gained — this is a recurring requirement in DevOps/infrastructure postings that touch business-systems support.
- **Microsoft Power Platform (Power Apps + Power Automate) — confirmed as of Aug 2026:** proficient level — built and maintain a self-service access-request portal: Power Apps GUI/web-form interface for group-membership requests (button-triggered), paired with Power Automate approval/provisioning workflows. Scale: 1,500+ users, thousands of groups. Current role (Sitecore, 2021–present). Distinct and more specific than the previously-listed Fabric-only entry; Fabric remains the light/occasional-use data layer behind this portal.
