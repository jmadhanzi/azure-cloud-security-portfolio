# Azure Cloud Security Portfolio

> **Cloud Security Engineering • DevSecOps • Threat Detection**

Hi! I'm **Jacob Madhanzi**, an early-career security professional focused on Azure Cloud Security, DevSecOps automation, and cloud threat detection engineering.

This portfolio showcases real, hands-on work across:

✅ Cloud security engineering  
✅ DevSecOps pipelines (secure CI/CD)  
✅ Cloud threat detection & KQL analytics  
✅ Infrastructure-as-Code (Bicep/Terraform)  
✅ Security automation & governance  

**All projects are designed to run inside a student Azure subscription, making them reproducible and accessible.**

---

## 📋 Quick Links
- [Learning Objectives](#-learning-objectives)
- [Tech Stack](#-tech-stack)
- [Highlights](#-highlights)
- [Project A – Cloud Threat Detection Lab](#-project-a--cloud-threat-detection-lab)
- [Project B – Azure Landing Zone Lite](#-project-b--azure-landing-zone-lite)
- [Project C – DevSecOps Pipelines](#-project-c--devsecops-pipelines)
- [Architecture Docs](#-additional-resources)

---

## 🎯 Learning Objectives

This portfolio demonstrates proficiency in:

| Certification | Skills Demonstrated |
|---|---|
| **AZ-500** (Azure Security Engineer) | Identity & access management, platform protection, security operations, data & application security |
| **SC-100** (Cybersecurity Architect) | Zero Trust architecture, security operations strategy, infrastructure security, compliance |
| **SC-200** (Security Operations Analyst) | Threat detection with KQL, incident response, threat hunting, Sentinel SIEM/SOAR |

### Additional Competencies
- Infrastructure-as-Code (Bicep/Terraform)
- CI/CD security automation
- MITRE ATT&CK framework
- Windows & Linux security hardening
- Cloud-native security tooling

---

## 🛠 Tech Stack

| Area | Technologies |
|---|---|
| **☁️ Cloud** | Azure, Entra ID, Defender for Cloud, Log Analytics, Sentinel |
| **🏗 IaC** | Bicep, Terraform, ARM Templates |
| **🔄 DevSecOps** | GitHub Actions, OIDC, CodeQL, tfsec, Checkov, Trivy |
| **🖥 Systems** | Windows Server, Ubuntu Linux, Sysmon, Azure Monitor Agent |
| **🔍 Detection** | KQL, MITRE ATT&CK, Sigma Rules |
| **🔐 Security** | NSGs, Azure Bastion, Key Vault, NAT Gateway, Zero Trust |
| **📊 Monitoring** | Log Analytics Workspaces, Data Collection Rules, Flow Logs |

---

## ⭐ Highlights

✅ Built a full cloud threat detection lab using Sysmon + Log Analytics  
✅ Developed 20+ KQL detections mapped to MITRE ATT&CK  
✅ Integrated AWS CloudTrail with Microsoft Sentinel for multi-cloud threat detection  
✅ Built cross-cloud correlation joining AWS and Azure data on source IP  
✅ Automated Slack incident notifications via Logic App SOAR playbook  
✅ Created secure IaC deployments using Bicep & Terraform  
✅ Implemented DevSecOps pipelines with CodeQL, tfsec & Checkov  
✅ Automated Azure deployments using GitHub Actions + OIDC (no secrets!)  
✅ Architected a "Landing Zone Lite" blueprint for student subscriptions  
✅ Established centralized logging with AMA and Data Collection Rules  
✅ Deployed Azure Bastion for secure, zero-trust administrative access  

---

## 📁 Project A — Cloud Threat Detection Lab

**📂 Location**: `/projects/project-a-cloud-detection-lab`  
**📊 Status**: 🟩 Complete

A comprehensive cloud detection engineering environment featuring:

- **Defender for Endpoint**: 3 onboarded devices with 5 custom detection rules
- **Microsoft Sentinel**: 11+ analytics rules with MITRE ATT&CK mapping
- **SOAR Automation**: 6 Logic Apps playbooks for incident response
- **Threat Hunting**: 5 hypothesis-driven KQL hunting queries
- **Workbooks**: 4 operational dashboards for analysis and investigation
- **Azure Log Analytics**: Centralized log aggregation and analysis
- **Sysmon/AMA Integration**: Advanced telemetry collection

### 🎯 Security Operations Capabilities

**Detection & Response:**
- 11+ Sentinel analytics rules (credential access, privilege escalation, UEBA, AWS threat detection, cross-cloud correlation)
- 5 Defender for Endpoint custom detections (T1059, T1003, T1021, T1547, T1087)
- ASIM-based multi-source brute force detection
- Behavioral analytics with UEBA

**Automation & SOAR:**
- Automated incident containment (session revocation, account disable)
- High-severity email notifications
- Content Hub solution deployment

**Threat Hunting:**
- Off-hours administrative activity detection
- Rapid privilege escalation chain analysis
- Mass user modification detection
- Suspicious IP pattern identification
- Failed login spike analysis

### 📖 Documentation

| Document | Description | Status |
|---|---|---|
| Lab 01 — RDP Brute Force Detection | T1110 credential access detection and investigation | ✅ Complete |
| Lab 02 — Suspicious Process Creation | T1059.001 PowerShell execution analysis | ✅ Complete |
| Lab 03 — AWS-Sentinel Multi-Cloud Detection | AWS CloudTrail integration, 4 cross-cloud detection rules | ✅ Complete |
| Defender for Endpoint | 3 devices, 5 custom detection rules | ✅ Complete |
| Automation Playbooks | 6 Logic Apps SOAR workflows | ✅ Complete |
| Playbook Case Studies | 3 detailed automation implementations | ✅ Complete |
| Analytics Rules | 11+ Sentinel detection rules | ✅ Complete |
| Workbooks | 4 investigation and hunting dashboards | ✅ Complete |
| Threat Hunting Queries | 5 hypothesis-driven hunts | ✅ Complete |

### 🛠 Key Technologies

**Detection & Monitoring:**
- Microsoft Sentinel (SIEM/SOAR)
- AWS CloudTrail (via S3/SQS integration)
- Cross-cloud threat correlation (AWS + Azure)
- Defender for Cloud CSPM (multi-cloud posture)
- Defender for Endpoint (EDR)
- Windows Security Events (4624, 4625, 4688)
- Sysmon (Event IDs 1, 3, 7, 11)
- Azure Monitor Agent (AMA)
- UEBA (User & Entity Behavior Analytics)

**Automation & Response:**
- Logic Apps (SOAR workflows)
- Content Hub solutions
- Managed identities (secure authentication)

**Analysis & Hunting:**
- KQL (Kusto Query Language)
- Sentinel Workbooks
- ASIM normalization
- MITRE ATT&CK framework

### 📈 Skills Demonstrated

**Detection Engineering:**
- Cloud threat detection with Sentinel and Defender for Endpoint
- KQL query development and optimization
- Multi-cloud SIEM integration (AWS CloudTrail + Sentinel)
- Cross-cloud threat correlation using KQL joins
- CloudTrail JSON parsing and nested field extraction
- MITRE ATT&CK framework mapping
- Multi-source correlation with ASIM
- Behavioral analytics (UEBA) implementation

**Security Automation (SOAR):**
- Logic Apps workflow design and implementation
- Automated incident containment
- Content Hub solution deployment
- Managed identity configuration

**Threat Hunting:**
- Hypothesis-driven hunting methodology
- Risk scoring algorithm development
- Workbook development for operational efficiency
- Hunt-to-rule promotion workflows

**Investigation & Analysis:**
- Incident response and triage
- Attack simulation and validation
- Sysmon configuration and log analysis
- Cross-environment correlation

📖 [View Project A Details](./projects/project-a-cloud-detection-lab/)

---

## 📁 Project B — Azure Landing Zone Lite (Infrastructure-as-Code)

**📂 Location**: `/projects/project-b-landing-zone-lite`  
**📊 Status**: 🟩 Complete

A minimal, secure Azure Landing Zone designed for restricted tenants and student subscriptions.

### 🏗 Core Components

- **Network Segmentation**: VNet with isolated subnets (App, Mgmt, Logging)
- **Secure Access**: Azure Bastion for RDP/SSH (no public IPs on VMs)
- **Controlled Egress**: NAT Gateway for predictable outbound traffic
- **Identity Security**: Key Vault for secrets management
- **Monitoring**: Centralized logging with Log Analytics Workspace
- **Security**: Network Security Groups with least-privilege rules
- **Diagnostics**: Flow logs and Activity logs enabled

### 📚 Documentation

| Document | Description |
|---|---|
| Landing Zone Overview | Architecture overview and design principles |
| Networking Deep Dive | Detailed networking configuration |
| Troubleshooting Guide | Common issues and solutions |
| Hybrid AD Setup | On-premises DC with Entra Connect |
| Architecture Diagram | Visual architecture documentation |

### 🔧 IaC Available In
- `infra/bicep/` — 🟩 Core networking module completed
- `infra/terraform/` — Terraform alternative (planned)

### 🔐 Security Features

✅ Zero public IPs on VMs  
✅ Azure Bastion for secure administrative access  
✅ Network Security Groups with default-deny rules  
✅ NAT Gateway for controlled outbound connectivity  
✅ Flow logs enabled for network visibility  
✅ Diagnostic settings on all key resources  
✅ Centralized logging to Log Analytics  
✅ Microsoft Sentinel for threat detection  

### 📈 Skills Demonstrated

- Azure network design and segmentation
- Zero Trust security model implementation
- Infrastructure-as-Code development
- Secure VM deployment patterns
- Cloud architecture diagramming
- Azure Bastion configuration
- NAT Gateway implementation
- Log Analytics integration

📖 [View Project B Details](./projects/project-b-landing-zone-lite/)

---

## 📁 Project C — DevSecOps Pipelines

**📂 Location**: `/projects/project-c-devsecops-pipelines`  
**📊 Status**: 🟨 Planned

Secure CI/CD pipelines for automated infrastructure deployment and security validation.

### 🎯 Planned Features

**Security Scanning:**
- IaC linting and validation
- IaC security scanning (Checkov, tfsec)
- CodeQL static analysis
- Secret scanning
- Container image scanning (Trivy)
- Dependency vulnerability scanning

**Deployment Automation:**
- GitHub OIDC → Azure (no stored secrets)
- Automated Bicep/Terraform deployments
- Environment promotion workflows
- Rollback capabilities

**Governance & Compliance:**
- Policy-as-Code enforcement
- Drift detection
- Compliance reporting
- Automated documentation

### 🔮 Future Enhancements

- Automated Sentinel rule deployment
- Policy-as-Code with Azure Policy
- Workbook automation
- Logic App playbook deployment
- Defender for Cloud integration
- Compliance scanning and reporting

📖 [View Project C Details](./projects/project-c-devsecops-pipelines/)

---

## 📂 Repository Structure

```
azure-cloud-security-portfolio/
│
├── README.md
├── GETTING_STARTED.md
├── ARCHITECTURE.md
├── LICENSE
├── .gitignore
│
├── .github/
│   └── copilot-instructions.md
│
├── docs/
│   ├── architecture/
│   │   ├── cloud-detection-lab-architecture.md
│   │   └── landing-zone-lite-architecture.md
│   ├── COST_OPTIMIZATION.md
│   ├── KQL_REFERENCE.md
│   └── TROUBLESHOOTING.md
│
├── infra/
│   ├── bicep/
│   │   └── landing-zone-lite/
│   │       └── main.bicep
│   └── terraform/
│       └── .gitkeep
│
├── projects/
│   ├── project-a-cloud-detection-lab/
│   │   ├── README.md
│   │   ├── labs/
│   │   │   ├── lab-01-bruteforce-detection.md
│   │   │   ├── lab-02-process-creation.md
│   │   │   └── lab-03-aws-sentinel-integration.md
│   │   ├── playbooks/
│   │   │   ├── playbook-01-revoke-user-signin.md
│   │   │   ├── playbook-02-high-severity-notification.md
│   │   │   └── playbook-03-content-hub-block-user.md
│   │   ├── automation-playbooks.md
│   │   ├── defender-for-endpoint.md
│   │   ├── detections.md
│   │   ├── hunting-queries.md
│   │   └── workbooks.md
│   │
│   ├── project-b-landing-zone-lite/
│   │   ├── README.md
│   │   ├── hybrid-ad-setup.md
│   │   ├── landing-zone-lite.md
│   │   ├── networking.md
│   │   └── troubleshooting.md
│   │
│   └── project-c-devsecops-pipelines/
│       ├── README.md
│       ├── .github/
│       │   └── workflows/
│       │       ├── iac-scan.yml
│       │       └── deploy.yml
│       └── scripts/
│
└── scripts/
    ├── install-ama.ps1
    └── install-sysmon.ps1
```

---

## 🚀 Getting Started

### Prerequisites

**Azure Requirements:**
- Active Azure subscription (Student or Free Tier works)
- Owner or Contributor role on subscription
- Resource quota for VMs and networking

**Local Development:**
- Azure CLI installed
- PowerShell 7+ (for scripts)
- Git
- Text editor (VS Code recommended)

**Recommended Knowledge:**
- Basic Azure concepts (VMs, networking, storage)
- PowerShell fundamentals
- KQL basics (for detection work)

### Quick Start - Project A

```bash
# Clone the repository
git clone https://github.com/jmadhanzi/azure-cloud-security-portfolio.git
cd azure-cloud-security-portfolio

# Log in to Azure
az login

# Navigate to Project A
cd projects/project-a-cloud-detection-lab

# Follow the project-specific README
cat README.md
```

**Create base infrastructure:**
1. Create a Resource Group: `rg-sc200-lab`
2. Deploy Windows VM
3. Create Log Analytics Workspace
4. Configure Azure Monitor Agent

**Install Sysmon (optional but recommended):**
```powershell
.\scripts\install-sysmon.ps1
```

**Configure Data Collection Rules:**
- Windows Security Events
- Sysmon Events (if installed)

**Enable Microsoft Sentinel:**
1. Navigate to Log Analytics Workspace
2. Enable Sentinel
3. Import analytics rules from detection pack

**Run test scenarios:**
- Follow lab guides in `projects/project-a-cloud-detection-lab/labs/`

### Quick Start - Project B

1. Review architecture in `landing-zone-lite.md`
2. Review networking configuration in `networking.md`
3. Deploy components (manual for now, IaC coming):
   - VNet with subnets
   - Azure Bastion
   - NAT Gateway
   - Management VMs
   - Log Analytics Workspace
4. Configure monitoring:
   - Enable Flow Logs
   - Configure Data Collection Rules
   - Enable Sentinel
5. Validate security posture:
   - Test Bastion connectivity
   - Verify NAT Gateway routing
   - Confirm log ingestion

---

## 💰 Cost Management

**Running these labs in Azure incurs costs. Here are estimated monthly costs for a student subscription:**

| Component | Estimated Cost (USD/month) | Notes |
|---|---|---|
| Windows VM (B2s) | ~$30 | Can be deallocated when not in use |
| Linux VM (B2s) | ~$15 | Can be deallocated when not in use |
| Log Analytics (10GB/month) | ~$2.50 | First 5GB free per workspace |
| Sentinel | ~$0-5 | Based on ingestion volume |
| Azure Bastion (Basic) | ~$135 | Major cost driver |
| NAT Gateway | ~$35 | Includes data processing |
| Storage (Logs) | ~$1 | Minimal with retention limits |
| **Total (with Bastion)** | **~$220** | |
| **Total (without Bastion)** | **~$85** | Using NSG + JIT instead |

### 💡 Cost Optimization Tips

- **Deallocate VMs when not in use** (saves ~50% on compute)
  ```bash
  az vm deallocate --resource-group rg-sc200-lab --name vm-win-sc200-lab
  ```
- Use Azure Bastion Developer SKU when available ($5/month vs $135/month)
- Limit Log Analytics retention to 30 days for lab work
- Delete resources when lab is complete
  ```bash
  az group delete --name rg-sc200-lab --yes --no-wait
  ```
- Use Azure Cost Management alerts to monitor spending
- Consider Azure for Students ($100 free credit)

📖 See [COST_OPTIMIZATION.md](./docs/COST_OPTIMIZATION.md) for detailed guidance.

---

## 📖 Additional Resources

### Official Microsoft Documentation
- [Microsoft Sentinel Documentation](https://learn.microsoft.com/en-us/azure/sentinel/)
- [Azure Security Best Practices](https://learn.microsoft.com/en-us/azure/security/)
- [KQL Quick Reference](https://learn.microsoft.com/en-us/azure/data-explorer/kusto/query/)

### Learning Paths
- [AZ-500: Azure Security Administrator](https://learn.microsoft.com/en-us/certifications/exams/az-500)
- [SC-200: Security Operations Analyst](https://learn.microsoft.com/en-us/certifications/exams/sc-200)
- [SC-100: Cybersecurity Architect](https://learn.microsoft.com/en-us/certifications/exams/sc-100)

### Community Resources
- [MITRE ATT&CK Framework](https://attack.mitre.org/)
- [Sysmon Config (SwiftOnSecurity)](https://github.com/SwiftOnSecurity/sysmon-config)
- [Sigma Rules](https://github.com/SigmaHQ/sigma)
- [LOLBAS Project](https://lolbas-project.github.io/)

---

## 📫 Contact

**Jacob Madhanzi**
- GitHub: [@jmadhanzi](https://github.com/jmadhanzi)
- LinkedIn: [jacob-madhanzi](https://linkedin.com/in/jacob-madhanzi)
- Email: [your-email@example.com]

---

## 📜 License

This portfolio is open-source under the **MIT License**. See [LICENSE](./LICENSE) for details.

---

## 🙏 Acknowledgments

- Microsoft Learn for comprehensive Azure documentation
- MITRE ATT&CK team for threat framework
- SwiftOnSecurity for Sysmon configuration baseline
- Azure security community for shared knowledge

---

⭐ **If you find this portfolio helpful, please consider starring the repository!**

**Last Updated**: October 2026  
**Status**: Active Development 🚀
