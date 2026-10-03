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
- [Portfolio Index](#-navigation)
- [Project A – Cloud Threat Detection Lab](#-project-a--cloud-threat-detection-lab)
- [Project B – Azure Landing Zone Lite](#-project-b--azure-landing-zone-lite)
- [Project C – DevSecOps Pipelines](#-project-c--devsecops-pipelines)
- [Architecture Docs](#-additional-resources)

---

## 📚 Navigation

### 🎯 Learning Objectives
- Deploy and configure Azure security services (Defender for Cloud, Sentinel, Key Vault)
- Build threat detection rules using KQL (Kusto Query Language)
- Implement Infrastructure-as-Code with Bicep and Terraform
- Automate security scanning in CI/CD pipelines with GitHub Actions
- Design cloud governance and compliance frameworks
- Analyze and respond to cloud security incidents

### 🛠 Tech Stack
| Category | Technologies |
|----------|---------------|
| **Cloud Platform** | Microsoft Azure, Azure Government (optional) |
| **IaC** | Bicep, Terraform, ARM Templates |
| **CI/CD** | GitHub Actions, Azure DevOps |
| **Monitoring & Detection** | Azure Sentinel, Defender for Cloud, Log Analytics |
| **Query Language** | KQL (Kusto Query Language) |
| **Security Tools** | KeyVault, Network Security Groups, Application Insights |
| **Compliance** | AZ-500, SC-100, SC-200 aligned |

### ⭐ Highlights
- **100% Student-Friendly**: All projects fit within Azure free tier / student credits
- **Reproducible**: Deploy with single Bicep/Terraform commands
- **Real-World Scenarios**: Actual threat detection, incident response workflows
- **Well-Documented**: Architecture diagrams, deployment guides, KQL examples included
- **GitHub-Native**: GitHub Actions for CI/CD, no external platforms required

---

## 📁 Project A – Cloud Threat Detection Lab

**Objective**: Deploy a cloud-native threat detection environment with Azure Sentinel and Defender for Cloud.

**What You'll Build**:
- Log Analytics Workspace with data connectors
- Azure Sentinel with KQL detection rules
- Custom threat detection playbooks
- Incident response automation

**Tech Stack**: Bicep, KQL, Azure Sentinel, Defender for Cloud  
**Duration**: ~2-3 hours  
**Cost**: Free tier eligible

📖 [View Project A Details](./projects/01-threat-detection-lab/)

---

## 📁 Project B – Azure Landing Zone Lite

**Objective**: Design and deploy a secure, scalable Azure landing zone using Infrastructure-as-Code.

**What You'll Build**:
- Multi-subscription architecture (hub-spoke model)
- Network segmentation with NSGs and UDRs
- Policy-as-Code for governance
- Key Vault with RBAC and access policies
- Monitoring and logging centralization

**Tech Stack**: Terraform, Bicep, Azure Policy  
**Duration**: ~3-4 hours  
**Cost**: Low (mostly free tier eligible)

📖 [View Project B Details](./projects/02-azure-landing-zone/)

---

## 📁 Project C – DevSecOps Pipelines

**Objective**: Implement secure CI/CD pipelines with automated security scanning and compliance checks.

**What You'll Build**:
- GitHub Actions workflows for IaC deployment
- Container image scanning with Trivy/Snyk
- Static code analysis (SAST) integration
- Secret scanning and rotation
- Automated compliance reporting

**Tech Stack**: GitHub Actions, Bicep/Terraform, OWASP tools, KQL  
**Duration**: ~2-3 hours  
**Cost**: Free (GitHub Actions included)

📖 [View Project C Details](./projects/03-devsecops-pipelines/)

---

## 📂 Repository Structure

```text
azure-cloud-security-portfolio/
├── README.md                          # You are here
├── GETTING_STARTED.md                 # Setup guide
├── ARCHITECTURE.md                    # System design & diagrams
│
├── projects/
│   ├── 01-threat-detection-lab/
│   │   ├── README.md
│   │   ├── bicep/                     # IaC templates
│   │   ├── kql/                       # Detection rules
│   │   └── playbooks/                 # Sentinel playbooks
│   │
│   ├── 02-azure-landing-zone/
│   │   ├── README.md
│   │   ├── terraform/                 # Terraform modules
│   │   ├── bicep/                     # Bicep templates
│   │   └── policies/                  # Azure Policy definitions
│   │
│   └── 03-devsecops-pipelines/
│       ├── README.md
│       ├── .github/workflows/         # GitHub Actions
│       ├── scripts/                   # Automation scripts
│       └── config/                    # Tool configurations
│
├── docs/
│   ├── COST_OPTIMIZATION.md           # Staying within Azure credits
│   ├── KQL_REFERENCE.md               # KQL examples & patterns
│   └── TROUBLESHOOTING.md             # Common issues & fixes
│
└── .github/
    └── ISSUE_TEMPLATE/                # Issue templates for contributors
```

---

## 🚀 Getting Started

### Prerequisites
- Microsoft Azure account (free tier / student subscription)
- GitHub account
- `az` CLI installed ([install here](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli))
- `terraform` CLI (for Project B) ([install here](https://www.terraform.io/downloads.html))

### Quick Start (5 minutes)

```bash
# Clone this repository
git clone https://github.com/jmadhanzi/azure-cloud-security-portfolio.git
cd azure-cloud-security-portfolio

# Log in to Azure
az login

# Navigate to a project
cd projects/01-threat-detection-lab

# Follow the project-specific README
cat README.md
```

For detailed setup instructions, see [GETTING_STARTED.md](./GETTING_STARTED.md).

---

## 💰 Cost Management

**All projects are optimized for Azure free tier / student credits.**

| Project | Estimated Monthly Cost | Free Tier Eligible |
|---------|----------------------|------------------|
| Threat Detection Lab | $5–15 | ✅ Yes |
| Azure Landing Zone | $10–25 | ✅ Yes |
| DevSecOps Pipelines | $0 (GitHub Actions free) | ✅ Yes |

💡 **Tips**:
- Use `GETTING_STARTED.md` for cost-saving configurations
- Monitor Azure costs with `az cost-management` CLI
- Delete unused resources with provided cleanup scripts

📖 See [COST_OPTIMIZATION.md](./docs/COST_OPTIMIZATION.md) for detailed guidance.

---

## 📖 Additional Resources

### Documentation
- [Microsoft Azure Documentation](https://learn.microsoft.com/en-us/azure/)
- [Azure Security Benchmark](https://learn.microsoft.com/en-us/security/benchmark/azure/)
- [Kusto Query Language (KQL) Reference](https://learn.microsoft.com/en-us/azure/data-explorer/kusto/query/)
- [Terraform Azure Provider](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs)

### Certifications This Portfolio Supports
- **AZ-500**: Azure Security Administrator
- **SC-100**: Microsoft Cybersecurity Architect
- **SC-200**: Microsoft Security Operations Analyst

### Learning Paths
- [Microsoft Learn: Azure Security](https://learn.microsoft.com/en-us/training/paths/implement-cloud-security-controls-azure/)
- [Cloud Security Alliance: Cloud Security Guidance](https://cloudsecurityalliance.org/)

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

**Last Updated**: October 2026  
**Status**: Active Development 🚀
