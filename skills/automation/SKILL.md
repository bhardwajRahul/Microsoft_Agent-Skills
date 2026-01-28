---
name: automation
description: Expert knowledge for Automation development including security, best practices, integrations & coding patterns, configuration, deployment, limits & quotas, and troubleshooting. Use when building, debugging, or optimizing Automation applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Automation Skill

This skill provides expert guidance for Automation development. It combines local quick-reference content with remote documentation fetching capabilities.

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

### Best Practices
| Topic | URL |
|-------|-----|
| Design modular parent-child runbooks in Azure Automation | https://learn.microsoft.com/en-us/azure/automation/automation-child-runbooks |
| Implement error handling in graphical Azure Automation runbooks | https://learn.microsoft.com/en-us/azure/automation/automation-runbook-graphical-error-handling |
| Configure output and message streams in Azure Automation runbooks | https://learn.microsoft.com/en-us/azure/automation/automation-runbook-output-and-messages |
| Apply security best practices to Azure Automation | https://learn.microsoft.com/en-us/azure/automation/automation-security-guidelines |
| Avoid Azure Automation runbook issues from context switching | https://learn.microsoft.com/en-us/azure/automation/context-switching |
| Manage Azure Automation runbooks with recommended patterns | https://learn.microsoft.com/en-us/azure/automation/manage-runbooks |

### Configuration
| Topic | URL |
|-------|-----|
| Configure and use connection assets in Azure Automation | https://learn.microsoft.com/en-us/azure/automation/automation-connections |
| Compile DSC configurations in Azure Automation State Configuration | https://learn.microsoft.com/en-us/azure/automation/automation-dsc-compile |
| Scale configuration data for Azure Automation State Configuration | https://learn.microsoft.com/en-us/azure/automation/automation-dsc-config-data-at-scale |
| Generate Automation State Configuration from existing servers | https://learn.microsoft.com/en-us/azure/automation/automation-dsc-config-from-server |
| Convert DSC configurations into composite resources in Automation | https://learn.microsoft.com/en-us/azure/automation/automation-dsc-create-composite |
| Get started configuring Azure Automation State Configuration | https://learn.microsoft.com/en-us/azure/automation/automation-dsc-getting-started |
| Enable and onboard machines to Azure Automation State Configuration | https://learn.microsoft.com/en-us/azure/automation/automation-dsc-onboarding |
| Remediate noncompliant nodes in Azure Automation State Configuration | https://learn.microsoft.com/en-us/azure/automation/automation-dsc-remediate |
| Edit PowerShell runbooks with Azure Automation textual editor | https://learn.microsoft.com/en-us/azure/automation/automation-edit-textual-runbook |
| Author graphical runbooks in Azure Automation | https://learn.microsoft.com/en-us/azure/automation/automation-graphical-authoring-intro |
| Run Azure Automation runbooks on Hybrid Runbook Workers | https://learn.microsoft.com/en-us/azure/automation/automation-hrw-run-runbooks |
| Configure network requirements for Azure Automation features | https://learn.microsoft.com/en-us/azure/automation/automation-network-configuration |
| Update built-in Azure PowerShell modules in Azure Automation | https://learn.microsoft.com/en-us/azure/automation/automation-update-azure-modules |
| Compose DSC configurations using composite resources in Azure Automation | https://learn.microsoft.com/en-us/azure/automation/compose-configurationwithcompositeresources |
| Delete and restore Azure Automation accounts with linked resources | https://learn.microsoft.com/en-us/azure/automation/delete-account |
| Configure DNS records for region-specific Azure Automation access | https://learn.microsoft.com/en-us/azure/automation/how-to/automation-region-dns-records |
| Configure runtime environments and runbooks in Azure Automation | https://learn.microsoft.com/en-us/azure/automation/manage-runtime-environment |
| Use built-in Azure Policy definitions for Automation | https://learn.microsoft.com/en-us/azure/automation/policy-reference |
| Manage Python 3 packages in Azure Automation | https://learn.microsoft.com/en-us/azure/automation/python-3-packages |
| Manage Python 2 packages in Azure Automation | https://learn.microsoft.com/en-us/azure/automation/python-packages |
| Configure input parameters for Azure Automation runbooks | https://learn.microsoft.com/en-us/azure/automation/runbook-input-parameters |
| Store and use certificates securely in Azure Automation | https://learn.microsoft.com/en-us/azure/automation/shared-resources/certificates |
| Create and manage credential assets in Azure Automation | https://learn.microsoft.com/en-us/azure/automation/shared-resources/credentials |
| Manage PowerShell modules and runtime environments in Azure Automation | https://learn.microsoft.com/en-us/azure/automation/shared-resources/modules |
| Create and manage runbook schedules in Azure Automation | https://learn.microsoft.com/en-us/azure/automation/shared-resources/schedules |
| Configure and use Azure Automation variable assets | https://learn.microsoft.com/en-us/azure/automation/shared-resources/variables |
| Start Azure Automation runbooks using different methods | https://learn.microsoft.com/en-us/azure/automation/start-runbooks |
| Remove DSC configurations and unregister nodes from Azure Automation | https://learn.microsoft.com/en-us/azure/automation/state-configuration/remove-node-and-configuration-package |
| Configure machines to desired state with Azure Automation DSC | https://learn.microsoft.com/en-us/azure/automation/tutorial-configure-servers-desired-state |

### Deployment
| Topic | URL |
|-------|-----|
| Set up continuous deployment with Azure Automation DSC and Chocolatey | https://learn.microsoft.com/en-us/azure/automation/automation-dsc-cd-chocolatey |
| Deploy agent-based Linux Hybrid Runbook Workers in Azure Automation | https://learn.microsoft.com/en-us/azure/automation/automation-linux-hrw-install |
| Deploy agent-based Windows Hybrid Runbook Workers in Azure Automation | https://learn.microsoft.com/en-us/azure/automation/automation-windows-hrw-install |
| Deploy extension-based Hybrid Runbook Workers on Windows and Linux | https://learn.microsoft.com/en-us/azure/automation/extension-based-hybrid-runbook-worker-install |
| Move Azure Automation accounts across subscriptions safely | https://learn.microsoft.com/en-us/azure/automation/how-to/move-account |
| Migrate agent-based Hybrid Runbook Workers to extension-based workers | https://learn.microsoft.com/en-us/azure/automation/migrate-existing-agent-based-hybrid-worker-to-extension-based-workers |
| Deploy Azure Automation accounts using ARM templates | https://learn.microsoft.com/en-us/azure/automation/quickstart-create-automation-account-template |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Configure Azure Automation runbooks to authenticate with AWS | https://learn.microsoft.com/en-us/azure/automation/automation-config-aws-account |
| Deploy ARM templates from Automation PowerShell runbooks | https://learn.microsoft.com/en-us/azure/automation/automation-deploy-template-runbook |
| Integrate Azure Automation State Configuration with Azure Monitor Logs | https://learn.microsoft.com/en-us/azure/automation/automation-dsc-diagnostics |
| Forward Azure Automation job logs to Azure Monitor | https://learn.microsoft.com/en-us/azure/automation/automation-manage-send-joblogs-log-analytics |
| Provision AWS virtual machines using Azure Automation | https://learn.microsoft.com/en-us/azure/automation/automation-scenario-aws-deployment |
| Send email from Automation runbooks using SendGrid | https://learn.microsoft.com/en-us/azure/automation/automation-send-email |
| Trigger Azure Automation runbooks via webhooks | https://learn.microsoft.com/en-us/azure/automation/automation-webhooks |
| Use the Azure Automation graphical runbook SDK | https://learn.microsoft.com/en-us/azure/automation/graphical-runbook-sdk |
| Automate Office 365 management with Azure Automation | https://learn.microsoft.com/en-us/azure/automation/manage-office-365 |
| Manage Azure SQL databases using Automation managed identity | https://learn.microsoft.com/en-us/azure/automation/manage-sql-server-in-automation |
| Configure source control integration for Azure Automation runbooks | https://learn.microsoft.com/en-us/azure/automation/source-control-integration |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Review Azure DSC extension version history details | https://learn.microsoft.com/en-us/azure/automation/automation-dsc-extension-history |
| View and manage Azure Automation limits and quotas | https://learn.microsoft.com/en-us/azure/automation/automation-limits-quotas |
| Review Azure Automation subscription limits and quotas | https://learn.microsoft.com/en-us/azure/automation/automation-subscription-limits-faq |
| Check support matrix and limits for Change Tracking | https://learn.microsoft.com/en-us/azure/azure-change-tracking-inventory/change-tracking-inventory-support-matrix |

### Security
| Topic | URL |
|-------|-----|
| Configure user-assigned managed identity for Azure Automation | https://learn.microsoft.com/en-us/azure/automation/add-user-assigned-identity |
| Apply DoD STIG-based configuration with Automation State Configuration | https://learn.microsoft.com/en-us/azure/automation/automation-dsc-configuration-based-on-stig |
| Understand data protection and privacy in Azure Automation | https://learn.microsoft.com/en-us/azure/automation/automation-managing-data |
| Configure Azure RBAC roles and permissions for Automation accounts | https://learn.microsoft.com/en-us/azure/automation/automation-role-based-access-control |
| Configure encryption for secure assets in Azure Automation | https://learn.microsoft.com/en-us/azure/automation/automation-secure-asset-encryption |
| Use Microsoft Entra ID to secure Azure Automation authentication | https://learn.microsoft.com/en-us/azure/automation/automation-use-azure-ad |
| Disable local authentication for Azure Automation accounts | https://learn.microsoft.com/en-us/azure/automation/disable-local-authentication |
| Disable system-assigned managed identity in Azure Automation | https://learn.microsoft.com/en-us/azure/automation/disable-managed-identity-for-automation |
| Enable system-assigned managed identity for Azure Automation | https://learn.microsoft.com/en-us/azure/automation/enable-managed-identity-for-automation |
| Enforce Hybrid Runbook Worker job execution with Azure Policy | https://learn.microsoft.com/en-us/azure/automation/enforce-job-execution-hybrid-worker |
| Secure Azure Automation with Private Link and private endpoints | https://learn.microsoft.com/en-us/azure/automation/how-to/private-link-security |
| Use managed identity in Azure Automation PowerShell runbooks | https://learn.microsoft.com/en-us/azure/automation/learn/powershell-runbook-managed-identity |
| Provision Automation account and Reader role via Terraform | https://learn.microsoft.com/en-us/azure/automation/quickstarts/create-azure-automation-account-terraform |
| Enable managed identities on Azure Automation accounts | https://learn.microsoft.com/en-us/azure/automation/quickstarts/enable-managed-identity |
| Apply Azure Policy compliance controls to Automation | https://learn.microsoft.com/en-us/azure/automation/security-controls-policy |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Collect diagnostic data for Azure Automation support cases | https://learn.microsoft.com/en-us/azure/automation/troubleshoot/collect-data-microsoft-azure-automation-case |
| Troubleshoot Azure Automation State Configuration issues | https://learn.microsoft.com/en-us/azure/automation/troubleshoot/desired-state-configuration |
| Troubleshoot extension-based Hybrid Runbook Worker issues | https://learn.microsoft.com/en-us/azure/automation/troubleshoot/extension-based-hybrid-runbook-worker |
| Troubleshoot agent-based Hybrid Runbook Worker issues | https://learn.microsoft.com/en-us/azure/automation/troubleshoot/hybrid-runbook-worker |
| Diagnose and fix Azure Automation managed identity issues | https://learn.microsoft.com/en-us/azure/automation/troubleshoot/managed-identity |
| Troubleshoot Azure Automation runbook execution issues | https://learn.microsoft.com/en-us/azure/automation/troubleshoot/runbooks |
| Troubleshoot Azure Automation shared resource problems | https://learn.microsoft.com/en-us/azure/automation/troubleshoot/shared-resources |

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
