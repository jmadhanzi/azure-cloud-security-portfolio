# Azure Cloud Security Portfolio

> **Hands-on Cloud Security Engineering | DevSecOps Automation | Threat Detection**

## 👋 About Me

I'm **Jacob Madhanzi**, an early-career security professional with specialized expertise in **Azure Cloud Security**, **DevSecOps automation**, and **cloud threat detection engineering**. This portfolio showcases real, production-ready work across enterprise security domains.

### 🎯 What You'll Find Here

✅ **End-to-end threat detection engineering** (Sentinel SIEM/SOAR, KQL, 20+ detections)  
✅ **Secure infrastructure-as-code** (Bicep/Terraform, zero-trust architecture)  
✅ **DevSecOps pipelines** (GitHub Actions, automated security scanning, OIDC)  
✅ **Multi-cloud security** (AWS CloudTrail + Azure correlation)  
✅ **Security automation** (Logic Apps SOAR playbooks, incident response)  
✅ **Cloud governance** (Policy-as-Code, compliance, centralized logging)  

**All projects are fully reproducible in a student Azure subscription.**

---

## 🎓 Certification & Skills Alignment

### Certifications
| Exam | Focus | Demonstrated Skills |
|---|---|---|
| **AZ-500** | Azure Security Engineer | Identity & access, platform protection, security ops, data security |
| **SC-100** | Cybersecurity Architect | Zero Trust, security strategy, infrastructure, compliance |
| **SC-200** | Security Operations Analyst | KQL, threat detection, incident response, threat hunting |

### Key Competencies
`Azure Security` • `Microsoft Sentinel` • `KQL (Kusto Query Language)` • `Bicep/Terraform` • `GitHub Actions` • `Threat Detection` • `MITRE ATT&CK` • `Security Automation` • `Zero Trust Architecture` • `Cloud Threat Hunting` • `Incident Response` • `SIEM/SOAR` • `DevSecOps` • `Cloud Governance`

---

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| **☁️ Cloud Platform** | Azure, Entra ID, Defender for Cloud, Log Analytics, Sentinel, Defender for Endpoint |
| **🏗️ Infrastructure-as-Code** | Bicep, Terraform, ARM Templates, Azure Policy |
| **🔄 DevSecOps & CI/CD** | GitHub Actions, OIDC (federated identity), CodeQL, tfsec, Checkov, Trivy |
| **🖥️ Systems & Endpoints** | Windows Server, Ubuntu Linux, Sysmon, Azure Monitor Agent, Azure Bastion |
| **🔍 Detection & Hunting** | KQL, MITRE ATT&CK Framework, Sigma Rules, ASIM Normalization |
| **🔐 Security & Access** | NSGs, Key Vault, Azure Bastion, NAT Gateway, Managed Identities, Zero Trust |
| **📊 Monitoring & Logging** | Log Analytics Workspaces, Data Collection Rules, Flow Logs, Diagnostic Settings |
| **⚙️ Automation** | Logic Apps, Azure Functions, Managed Identities, API Integrations |

---

## ⭐ Key Achievements

✅ **Built a full-stack threat detection lab** with Sysmon telemetry, centralized logging, and advanced analytics  
✅ **Developed 20+ KQL detection rules** mapped to MITRE ATT&CK framework (T1110, T1059, T1003, T1021, T1547, T1087, etc.)  
✅ **Architected multi-cloud threat detection** by integrating AWS CloudTrail with Microsoft Sentinel  
✅ **Engineered cross-cloud correlation** joining AWS and Azure data on source IP and user activity  
✅ **Automated security incident response** via Logic Apps SOAR playbooks with Slack notifications  
✅ **Implemented secure IaC deployments** using Bicep & Terraform with zero exposed secrets  
✅ **Built DevSecOps pipelines** with CodeQL, tfsec, Checkov, and container scanning  
✅ **Deployed zero-trust infrastructure** using GitHub Actions + OIDC (federated credentials, no PATs)  
✅ **Designed Landing Zone Lite** blueprint for restricted tenants and student subscriptions  
✅ **Established centralized logging** with Azure Monitor Agent and Data Collection Rules at scale  
✅ **Deployed Azure Bastion** for secure, passwordless, zero-trust administrative access  

---

## 📋 Projects Overview

### 📁 [Project A — Cloud Threat Detection Lab](./projects/project-a-cloud-detection-lab)

**Status**: 🟩 **Complete**  
**Focus**: Detection Engineering + Threat Hunting + Security Automation

A production-grade cloud security operations center (SOC) built on Azure Sentinel and Defender for Endpoint.

**What's Included:**
- 🔍 **11+ Microsoft Sentinel analytics rules** with MITRE ATT&CK mapping
- 🛡️ **5 Defender for Endpoint custom detections** (EDR rules)
- 🔴 **UEBA & behavioral analytics** for insider threat detection
- 🌍 **Cross-cloud threat correlation** (AWS CloudTrail + Azure logs)
- ⚙️ **6 Logic Apps SOAR playbooks** for automated incident response
- 📊 **4 operational Sentinel Workbooks** for investigation and hunting
- 🎯 **5 hypothesis-driven KQL hunting queries** for threat hunting
- 📝 **Lab walkthroughs** covering detection, investigation, and response

**Key Detection Areas:**
- Credential Access (T1110 - RDP brute force, T1110.001 - password spray)
- Execution (T1059 - PowerShell execution, T1059.001 - suspicious scripts)
- Privilege Escalation (T1547, T1003 - credential dumping)
- Defense Evasion (T1562 - log clearing)
- Multi-cloud (AWS CloudTrail anomalies, cross-cloud pivots)

**Technologies**: Microsoft Sentinel, Defender for Endpoint, Log Analytics, Azure Monitor Agent, Sysmon, KQL, Logic Apps, UEBA, ASIM, MITRE ATT&CK

[**View Full Project Details →**](./projects/project-a-cloud-detection-lab)

---

### 📁 [Project B — Azure Landing Zone Lite](./projects/project-b-landing-zone-lite)

**Status**: 🟩 **Complete**  
**Focus**: Infrastructure Security + Zero Trust Architecture

A minimal, secure, and scalable Azure Landing Zone designed for restricted tenants, startups, and student subscriptions.

**What's Included:**
- 🏗️ **Hub-spoke network architecture** with isolated subnets
- 🔒 **Zero public IPs** on VMs (all access via Azure Bastion)
- 🌐 **Network segmentation** with NSGs and User-Defined Routes (UDRs)
- 🚪 **Azure Bastion** for secure RDP/SSH without public endpoints
- 🔄 **NAT Gateway** for controlled, predictable outbound traffic
- 🔐 **Key Vault** integration for secrets management
- 📊 **Centralized logging** with Log Analytics and Flow Logs
- 🛡️ **Microsoft Sentinel** integrated for threat detection
- 📋 **Azure Policy** for governance and compliance enforcement

**Security Architecture:**
- Zero Trust network segmentation
- Principle of least privilege on all security groups
- Centralized logging with retention and archival
- Activity logging and diagnostic settings on all resources
- Network flow visibility for threat hunting

**Infrastructure-as-Code:**
- 🟩 **Bicep templates** (completed) - modular, reusable components
- 🟨 **Terraform modules** (planned) - multi-cloud capability

**Technologies**: Bicep, Terraform, Azure VNet, NSGs, NAT Gateway, Azure Bastion, Log Analytics, Microsoft Sentinel, Azure Policy, Key Vault

[**View Full Project Details →**](./projects/project-b-landing-zone-lite)

---

### 📁 [Project C — DevSecOps Pipelines](./projects/project-c-devsecops-pipelines)

**Status**: 🟨 **In Development**  
**Focus**: Secure CI/CD + Automated Security Scanning

Enterprise-grade DevSecOps pipelines for automated infrastructure deployment with integrated security validation.

**Planned Features:**

**Security Scanning:**
- IaC validation and linting
- IaC security scanning (Checkov, tfsec)
- Static application security testing (CodeQL)
- Secret detection and rotation
- Container image scanning (Trivy)
- Dependency vulnerability analysis

**Deployment Automation:**
- GitHub Actions workflows
- OIDC authentication to Azure (no stored secrets)
- Automated Bicep/Terraform deployments
- Environment promotion (dev → staging → prod)
- Automated rollback on policy violations

**Governance & Compliance:**
- Azure Policy enforcement
- Drift detection
- Compliance reporting and attestation
- Automated security posture documentation

**Planned Integrations:**
- Automated Sentinel rule deployment
- Policy-as-Code with Azure Policy
- Workbook automation
- Logic App playbook deployment
- Defender for Cloud posture integration

**Technologies**: GitHub Actions, Bicep, Terraform, CodeQL, tfsec, Checkov, Trivy, OWASP tools, Azure Policy

[**View Full Project Details →**](./projects/project-c-devsecops-pipelines)

---

## 📚 Repository Structure

```
azure-cloud-security-portfolio/
│
├── README.md                          # Main portfolio overview (you are here)
├── GETTING_STARTED.md                 # Setup & deployment guide
├── PORTFOLIO_INDEX.md                 # Quick reference index
├── LICENSE                            # MIT License
├── .gitignore
│
├── .github/
│   └── copilot-instructions.md        # GitHub Copilot prompt
│
├── docs/
│   ├── architecture/
│   │   ├── cloud-detection-lab-architecture.md
│   │   ├── landing-zone-lite-architecture.md
│   │   └── diagrams/                  # Mermaid/visio diagrams
│   ├── COST_OPTIMIZATION.md           # Budget breakdown & tips
│   ├── KQL_REFERENCE.md               # KQL patterns & examples
│   └── TROUBLESHOOTING.md             # Common issues & fixes
│
├── infra/
│   ├── bicep/
│   │   ├── landing-zone-lite/
│   │   │   ├── main.bicep
│   │   │   ├── networking.bicep
│   │   │   ├── security.bicep
│   │   │   └── monitoring.bicep
│   │   └── modules/                   # Reusable modules
│   └── terraform/
│       └── landing-zone-lite/         # Terraform equivalents
│
├── projects/
│   │
│   ├── project-a-cloud-detection-lab/
│   │   ├── README.md                  # Project overview
│   │   ├── QUICKSTART.md              # 15-minute setup
│   │   ├── labs/
│   │   │   ├── lab-01-bruteforce-detection.md
│   │   │   ├── lab-02-process-creation.md
│   │   │   ├── lab-03-aws-sentinel-integration.md
│   │   │   └── lab-04-threat-hunting.md
│   │   ├── kql/
│   │   │   ├── detections/            # Analytics rules
│   │   │   ├── hunting-queries/       # Threat hunting queries
│   │   │   └── workbooks/             # KQL for dashboards
│   │   ├── playbooks/
│   │   │   ├── playbook-01-revoke-user-signin.md
│   │   │   ├── playbook-02-incident-notification.md
│   │   │   └── playbook-03-containment.md
│   │   ├── scripts/
│   │   │   ├── deploy-sentinel.sh
│   │   │   └── configure-dcr.sh
│   │   ├── images/                    # Screenshots & diagrams
│   │   ├── automation-playbooks.md
│   │   ├── defender-for-endpoint.md
│   │   ├── detections.md
│   │   ├── hunting-queries.md
│   │   └── workbooks.md
│   │
│   ├── project-b-landing-zone-lite/
│   │   ├── README.md                  # Project overview
│   │   ├── QUICKSTART.md              # 30-minute setup
│   │   ├── architecture.md            # Design principles
│   │   ├── networking.md              # Network deep dive
│   │   ├── hybrid-ad-setup.md         # Entra Connect guide
│   │   ├── troubleshooting.md         # Common issues
│   │   ├── images/                    # Architecture diagrams
│   │   └── bicep/                     # IaC templates
│   │
│   └── project-c-devsecops-pipelines/
│       ├── README.md                  # Project overview
│       ├── ROADMAP.md                 # Development roadmap
│       ├── .github/
│       │   └── workflows/
│       │       ├── iac-validate.yml
│       │       ├── security-scan.yml
│       │       └── deploy.yml
│       ├── scripts/
│       │   ├── lint-bicep.sh
│       │   ├── scan-iac.sh
│       │   └── promote-environment.sh
│       └── config/
│           ├── checkov.yaml
│           ├── tfsec.yaml
│           └── codeql-config.yml
│
└── scripts/
    ├── install-ama.ps1                # Azure Monitor Agent setup
    ├── install-sysmon.ps1             # Sysmon installation
    └── azure-cost-monitoring.sh        # Cost tracking
```

---

## 🚀 Quick Start

### Prerequisites

**Azure:**
- Active Azure subscription (Student/Free tier works)
- Owner or Contributor IAM role
- VM/networking resource quotas available

**Local:**
- `az` CLI ([install](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli))
- PowerShell 7+ ([install](https://github.com/PowerShell/PowerShell))
- Git
- VS Code (recommended)

### Get Started in 3 Steps

#### 1️⃣ Clone & Navigate
```bash
git clone https://github.com/jmadhanzi/azure-cloud-security-portfolio.git
cd azure-cloud-security-portfolio
az login
```

#### 2️⃣ Choose a Project

**Project A (Threat Detection)** — 2-3 hours
```bash
cd projects/project-a-cloud-detection-lab
cat QUICKSTART.md
```

**Project B (Landing Zone)** — 3-4 hours
```bash
cd projects/project-b-landing-zone-lite
cat QUICKSTART.md
```

**Project C (DevSecOps)** — Coming soon
```bash
cd projects/project-c-devsecops-pipelines
cat ROADMAP.md
```

#### 3️⃣ Follow the Guides

Each project includes:
- ✅ **QUICKSTART.md** — Get running in 15-30 minutes
- 📖 **README.md** — Full technical documentation
- 🎯 **Lab walkthroughs** — Step-by-step exercises
- 📊 **Architecture diagrams** — Visual reference
- 🛠️ **Deployment scripts** — Automated setup

---

## 💰 Estimated Costs

**Running these labs will incur Azure charges. Here's the breakdown:**

| Component | Est. Cost/Month | Optimization |
|---|---:|---|
| **Windows VM (B2s)** | ~$30 | Deallocate when not in use (-50%) |
| **Linux VM (B2s)** | ~$15 | Deallocate when not in use (-50%) |
| **Log Analytics** | ~$2.50 | First 5GB free per workspace |
| **Sentinel** | ~$0–5 | Scales with ingestion volume |
| **Azure Bastion (Basic)** | ~$135 | Use Developer SKU when available (~$5) |
| **NAT Gateway** | ~$35 | Can be eliminated with NSG rules |
| **Storage (Logs)** | ~$1 | Minimal with 30-day retention |
| | | |
| **Total (with Bastion)** | **~$220/mo** | |
| **Total (optimized)** | **~$50/mo** | Deallocate VMs, use Dev Bastion |

### 💡 Cost Optimization Tips

```bash
# Deallocate VMs to save 50% on compute costs
az vm deallocate --resource-group rg-sc200-lab --name vm-win

# Set Log Analytics retention to 30 days
az monitor log-analytics workspace update \
  --resource-group rg-sc200-lab \
  --workspace-name law-sc200-lab \
  --retention-time 30

# Delete entire lab when done
az group delete --name rg-sc200-lab --yes --no-wait

# Monitor spending with alerts
az monitor metrics alert create \
  --resource-group rg-sc200-lab \
  --scopes /subscriptions/{sub-id}/resourcegroups/rg-sc200-lab \
  --condition "avg BudgetThreshold > 100"
```

📖 See [COST_OPTIMIZATION.md](./docs/COST_OPTIMIZATION.md) for detailed breakdown and Azure for Students benefits.

---

## 📖 Learning Resources

### Microsoft Learn Paths
- **[AZ-500: Azure Security Engineer](https://learn.microsoft.com/en-us/certifications/exams/az-500)** — Platform protection, identity & access, data security
- **[SC-200: Security Operations Analyst](https://learn.microsoft.com/en-us/certifications/exams/sc-200)** — Threat detection, incident response, hunting
- **[SC-100: Cybersecurity Architect](https://learn.microsoft.com/en-us/certifications/exams/sc-100)** — Zero Trust, enterprise security strategy

### Official Documentation
- [Microsoft Sentinel](https://learn.microsoft.com/en-us/azure/sentinel/)
- [Azure Security Benchmark](https://learn.microsoft.com/en-us/security/benchmark/azure/)
- [Kusto Query Language (KQL)](https://learn.microsoft.com/en-us/azure/data-explorer/kusto/query/)
- [Azure Bicep](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/overview)

### Community & Frameworks
- **[MITRE ATT&CK](https://attack.mitre.org/)** — Threat intelligence framework
- **[Sysmon Config](https://github.com/SwiftOnSecurity/sysmon-config)** — SwiftOnSecurity baseline
- **[Sigma Rules](https://github.com/SigmaHQ/sigma)** — Detection rule repository
- **[LOLBAS](https://lolbas-project.github.io/)** — Living off the Land Binaries

### Additional Reading
- [Zero Trust Adoption Guide](https://learn.microsoft.com/en-us/security/zero-trust/)
- [Azure Well-Architected Review](https://learn.microsoft.com/en-us/assessments/azure-architecture-review/)
- [Cloud Security Alliance Guidance](https://cloudsecurityalliance.org/)

---

## 🎓 What You'll Learn

By working through these projects, you'll develop skills in:

### Detection Engineering
- Cloud threat detection architectures (SIEM/SOAR)
- KQL query optimization and advanced analytics
- Multi-cloud threat correlation (AWS + Azure)
- MITRE ATT&CK framework mapping
- Behavioral analytics and anomaly detection
- Threat hunting methodologies

### Cloud Security
- Azure security services configuration
- Identity and Access Management (Entra ID)
- Network segmentation and Zero Trust
- Cloud compliance and governance
- Azure Policy enforcement
- Security baseline implementation

### Infrastructure-as-Code
- Bicep template development
- Terraform module design
- Infrastructure versioning and CI/CD
- Policy-as-Code (Azure Policy)
- Drift detection and remediation
- Disaster recovery automation

### DevSecOps
- Secure CI/CD pipeline design
- GitHub Actions workflow creation
- OIDC federated credentials (no PATs)
- Infrastructure security scanning
- Secret management and rotation
- Compliance automation

### Security Operations
- Incident response procedures
- SOAR automation (Logic Apps)
- Alert tuning and optimization
- Security metrics and KPIs
- Post-incident analysis
- Playbook development

---

## 📫 Contact & Connect

**Jacob Madhanzi**

- 🔗 **GitHub**: [@jmadhanzi](https://github.com/jmadhanzi)
- 💼 **LinkedIn**: [jacob-madhanzi](https://www.linkedin.com/in/jacob-madhanzi/)
- 📧 **Email**: your-email@example.com

---

## 📜 License & Attribution

This portfolio is licensed under the **MIT License**. See [LICENSE](./LICENSE) for details.

### Acknowledgments

- **Microsoft Learn** — Comprehensive Azure documentation and learning paths
- **MITRE ATT&CK** — Threat intelligence framework and tactic/technique taxonomy
- **SwiftOnSecurity** — Sysmon configuration baseline
- **Azure Security Community** — Shared knowledge and best practices

---

## ⭐ Support This Portfolio

If this portfolio helped you learn or prepare for your security career, please consider:
- ⭐ Starring this repository
- 🔗 Sharing it with others
- 💬 Providing feedback or suggestions
- 🤝 Contributing improvements

---

**Last Updated**: October 2026  
**Status**: Active Development 🚀

---

### 🔐 Security Notice

This portfolio contains example detection rules, configurations, and techniques for **educational purposes only**. Always:
- Validate rules in your environment before production use
- Follow your organization's security policies
- Report actual security incidents to your SOC
- Keep Azure credentials and API keys secure (never commit to git)
