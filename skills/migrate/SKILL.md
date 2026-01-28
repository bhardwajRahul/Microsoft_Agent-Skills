---
name: migrate
description: Expert knowledge for Migrate development including integrations & coding patterns, configuration, best practices, troubleshooting, limits & quotas, security, deployment, architecture & design patterns, and comparing x vs. y. Use when building, debugging, or optimizing Migrate applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Migrate Skill

This skill provides expert guidance for Migrate development. It combines local quick-reference content with remote documentation fetching capabilities.

## Prerequisites

This skill requires **network access** to fetch remote documentation.

**Option 1: Microsoft Learn MCP Server (Recommended)**
- `mcp_microsoftdocs:microsoft_docs_fetch` - Fetch full page content from URLs

**Option 2: Web Fetch Tool**
- `fetch_webpage` - Fetch content from documentation URLs listed below

If neither option is available, you can still use the URLs in the tables below as references for the user to manually access.

---

## Remote Content Sources (MCP Tools)

When you need the latest official documentation, use `mcp_microsoftdocs:microsoft_docs_fetch` to fetch complete documentation pages:

- **Usage**: `microsoft_docs_fetch({ url: "https://learn.microsoft.com/..." })`

---

## Documentation Links by Category

### Architecture & Design Patterns
| Topic | URL |
|-------|-----|
| Choose Azure Migrate discovery methods and modes | https://learn.microsoft.com/en-us/azure/migrate/discovery-methods-modes?view=migrate |
| Understand Hyper-V migration architecture in Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/hyper-v-migration-architecture?view=migrate |

### Best Practices
| Topic | URL |
|-------|-----|
| Meet Azure Migrate assessment prerequisites for accurate results | https://learn.microsoft.com/en-us/azure/migrate/assessment-prerequisites?view=migrate |
| Apply security best practices to Azure Migrate appliance | https://learn.microsoft.com/en-us/azure/migrate/best-practices-security?view=migrate |
| Test migrate replicated virtual machines in Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/how-to-test-replicating-virtual-machines?view=migrate |
| Prepare on-premises machines for Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/prepare-for-migration?view=migrate |
| Prepare Windows Server 2003 for migration to Azure | https://learn.microsoft.com/en-us/azure/migrate/prepare-windows-server-2003-migration?view=migrate |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Compare agentless vs agent-based Azure Migrate methods | https://learn.microsoft.com/en-us/azure/migrate/server-migrate-overview?view=migrate |

### Configuration
| Topic | URL |
|-------|-----|
| Configure server credentials on Azure Migrate appliance | https://learn.microsoft.com/en-us/azure/migrate/add-server-credentials?view=migrate |
| Configure general assessment properties in Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/assessment-properties?view=migrate |
| Migrate Azure Migrate dependency analysis to Azure Monitor Agent | https://learn.microsoft.com/en-us/azure/migrate/azure-monitor-agent-migration?view=migrate |
| Configure Azure Migrate appliance via PowerShell script | https://learn.microsoft.com/en-us/azure/migrate/deploy-appliance-script?view=migrate |
| Understand metadata collected by Azure Migrate appliance | https://learn.microsoft.com/en-us/azure/migrate/discovered-metadata?view=migrate |
| Enable Azure Arc for servers discovered by Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/how-to-arc-enable-inventory?view=migrate |
| Configure agentless dependency analysis in Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/how-to-create-group-machine-dependencies-agentless?view=migrate |
| Configure agent-based dependency analysis in Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/how-to-create-group-machine-dependencies?view=migrate |
| Configure Azure Migrate appliance for physical servers | https://learn.microsoft.com/en-us/azure/migrate/how-to-set-up-appliance-physical?view=migrate |
| Upgrade Windows Server OS during Azure migration | https://learn.microsoft.com/en-us/azure/migrate/how-to-upgrade-windows?view=migrate |
| Review prerequisites and support for Azure Migrate appliance | https://learn.microsoft.com/en-us/azure/migrate/migrate-appliance?view=migrate |
| Configure Azure Migrate Collector VM extension settings | https://learn.microsoft.com/en-us/azure/migrate/migrate-virtual-machine-extension-reference?view=migrate |
| Configure PostgreSQL assessment properties in Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/postgresql-assessment-properties?view=migrate |
| Create Azure Migrate project via ARM template | https://learn.microsoft.com/en-us/azure/migrate/quickstart-create-migrate-project?view=migrate |
| Configure Azure VM assessment properties in Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/vm-assessment-properties?view=migrate |

### Deployment
| Topic | URL |
|-------|-----|
| Deploy Azure Migrate appliance in Azure Government | https://learn.microsoft.com/en-us/azure/migrate/deploy-appliance-script-government?view=migrate |
| Redeploy servers to Azure using IaC with Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/server-redeploy?view=migrate |
| Set up Azure DevOps CI/CD for containerized apps | https://learn.microsoft.com/en-us/azure/migrate/tutorial-app-containerization-azure-pipeline?view=migrate |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Integrate GitHub Copilot code scans with Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/add-copilot-code-insights?view=migrate |
| Integrate CAST Highlight code scan reports with Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/cast-highlights-integration?view=migrate |
| Automate agentless VMware migrations with Azure Migrate PowerShell | https://learn.microsoft.com/en-us/azure/migrate/how-to-automate-migration?view=migrate |
| Automate large-scale migrations using Azure Site Recovery scripts | https://learn.microsoft.com/en-us/azure/migrate/how-to-migrate-at-scale?view=migrate |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Use Azure Migrate from unsupported Azure regions | https://learn.microsoft.com/en-us/azure/migrate/azure-migrate-unsupported-regions?view=migrate |
| Interpret Azure Migrate performance coverage star ratings | https://learn.microsoft.com/en-us/azure/migrate/confidence-ratings?view=migrate |
| Use Azure Migrate scale-out appliance for VMware migration | https://learn.microsoft.com/en-us/azure/migrate/how-to-scale-out-for-migration?view=migrate |
| Review Hyper-V to Azure migration support matrix | https://learn.microsoft.com/en-us/azure/migrate/migrate-support-matrix-hyper-v-migration?view=migrate |
| Hyper-V assessment support matrix for Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/migrate-support-matrix-hyper-v?view=migrate |
| Physical server discovery support matrix for Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/migrate-support-matrix-physical?view=migrate |
| Check VMware to Azure migration support matrix | https://learn.microsoft.com/en-us/azure/migrate/migrate-support-matrix-vmware-migration?view=migrate |
| VMware discovery support matrix for Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/migrate-support-matrix-vmware?view=migrate |
| Review Azure Migrate support matrix and limitations | https://learn.microsoft.com/en-us/azure/migrate/migrate-support-matrix?view=migrate |
| Assess large physical server estates with Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/scale-physical-assessment?view=migrate |
| Assess large VMware estates with Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/scale-vmware-assessment?view=migrate |
| Check Azure Migrate supported regions and metadata locations | https://learn.microsoft.com/en-us/azure/migrate/supported-geographies?view=migrate |

### Security
| Topic | URL |
|-------|-----|
| Set least-privilege VMware roles for Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/best-practices-least-privileged-account?view=migrate |
| Secure Azure Migrate discovery using Private Link | https://learn.microsoft.com/en-us/azure/migrate/discover-and-assess-using-private-endpoints?view=migrate |
| Secure Azure Migrate discovery using Private Link | https://learn.microsoft.com/en-us/azure/migrate/discover-and-assess-using-private-endpoints?view=migrate |
| Migrate VMware VMs with SSE and CMK using Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/how-to-migrate-vmware-vms-with-cmk-disks?view=migrate |
| Register Azure Migrate appliance with Entra ID app | https://learn.microsoft.com/en-us/azure/migrate/how-to-register-appliance-using-entra-app?view=migrate |
| Use Azure Migrate over Private Link and private endpoints | https://learn.microsoft.com/en-us/azure/migrate/how-to-use-azure-migrate-with-private-endpoints?view=migrate |
| Use Azure Migrate Insights for security risk assessment | https://learn.microsoft.com/en-us/azure/migrate/insights-overview?view=migrate |
| Create least-privilege SQL accounts for Azure Migrate discovery | https://learn.microsoft.com/en-us/azure/migrate/least-privilege-credentials?view=migrate |
| Migrate Hyper-V servers over Private Link securely | https://learn.microsoft.com/en-us/azure/migrate/migrate-hyper-v-servers-to-azure-using-private-link?view=migrate |
| Use Azure Policy definitions for Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/policy-reference?view=migrate |
| Configure least-privilege PostgreSQL accounts for Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/postgresql-least-privilege-configuration?view=migrate |
| Configure Azure Migrate RBAC roles and access | https://learn.microsoft.com/en-us/azure/migrate/prepare-azure-accounts?view=migrate |
| Set vCenter permissions to scope Azure Migrate discovery | https://learn.microsoft.com/en-us/azure/migrate/set-discovery-scope?view=migrate |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Use PostgreSQL assessment rules for Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/assessment-rules-for-postgresql?view=migrate |
| Resolve common Azure Migrate assessment issues | https://learn.microsoft.com/en-us/azure/migrate/common-questions-discovery-assessment?view=migrate |
| Troubleshoot Azure Migrate server migration tool | https://learn.microsoft.com/en-us/azure/migrate/common-questions-server-migration?view=migrate |
| Diagnose and fix Azure Migrate appliance issues | https://learn.microsoft.com/en-us/azure/migrate/troubleshoot-appliance-diagnostic?view=migrate |
| Troubleshoot Azure Migrate appliance deployment and discovery | https://learn.microsoft.com/en-us/azure/migrate/troubleshoot-appliance?view=migrate |
| Handle supported scenarios in Azure Migrate assessments | https://learn.microsoft.com/en-us/azure/migrate/troubleshoot-assessment-supported-scenarios?view=migrate |
| Troubleshoot Azure Migrate assessment issues | https://learn.microsoft.com/en-us/azure/migrate/troubleshoot-assessment?view=migrate |
| Troubleshoot agentless VMware replication failures in Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/troubleshoot-changed-block-tracking-replication?view=migrate |
| Fix Azure Migrate dependency analysis problems | https://learn.microsoft.com/en-us/azure/migrate/troubleshoot-dependencies?view=migrate |
| Resolve Azure Migrate discovery and inventory issues | https://learn.microsoft.com/en-us/azure/migrate/troubleshoot-discovery?view=migrate |
| Troubleshoot Azure Migrate private endpoint connectivity | https://learn.microsoft.com/en-us/azure/migrate/troubleshoot-network-connectivity?view=migrate |
| Diagnose and fix Azure Migrate project issues | https://learn.microsoft.com/en-us/azure/migrate/troubleshoot-project?view=migrate |
| Resolve slow or stuck VMware replication in Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/troubleshoot-replication-vmware?view=migrate |
| Troubleshoot Windows OS upgrade via Azure Migrate | https://learn.microsoft.com/en-us/azure/migrate/troubleshoot-upgrade?view=migrate |
| Troubleshoot Azure Migrate web app migration errors | https://learn.microsoft.com/en-us/azure/migrate/troubleshoot-webapps-migration?view=migrate |

---

## How to Use This Skill

### Option 1: Using MCP Tool (Recommended)

Use `mcp_microsoftdocs:microsoft_docs_fetch` to retrieve full documentation:
```
microsoft_docs_fetch({ url: "https://learn.microsoft.com/en-us/azure/azure-functions/functions-deployment-technologies" })
```

### Option 2: Using fetch_webpage Tool

If MCP tools are not available, use `fetch_webpage` to retrieve documentation:
```
fetch_webpage({ 
  urls: ["https://learn.microsoft.com/en-us/azure/azure-functions/functions-deployment-technologies"],
  query: "deployment options"
})
```

### Option 3: Manual Reference

If no network tools are available, provide the URLs from the tables above for the user to access directly.
