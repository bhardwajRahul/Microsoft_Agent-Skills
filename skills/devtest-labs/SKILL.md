---
name: devtest-labs
description: Expert knowledge for Devtest Labs development including integrations & coding patterns, best practices, security, configuration, deployment, comparing x vs. y, architecture & design patterns, limits & quotas, and troubleshooting. Use when building, debugging, or optimizing Devtest Labs applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Devtest Labs Skill

This skill provides expert guidance for Devtest Labs development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Govern Azure DevTest Labs resources across an organization | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-guidance-governance-resources |
| Plan and scale Azure DevTest Labs for enterprise use | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-guidance-scale |
| Enterprise reference architecture for Azure DevTest Labs | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-reference-architecture |

### Best Practices
| Topic | URL |
|-------|-----|
| Best practices for distributed DevTest Labs resource development | https://learn.microsoft.com/en-us/azure/devtest-labs/best-practices-distributive-collaborative-development-environment |
| Report and analyze DevTest Labs usage across subscriptions | https://learn.microsoft.com/en-us/azure/devtest-labs/report-usage-across-multiple-labs-subscriptions |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Choose between custom images and formulas in DevTest Labs | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-comparing-vm-base-image-types |

### Configuration
| Topic | URL |
|-------|-----|
| Attach and configure Azure Compute Gallery for DevTest Labs | https://learn.microsoft.com/en-us/azure/devtest-labs/configure-shared-image-gallery |
| Configure activity log alerts for Azure DevTest Labs | https://learn.microsoft.com/en-us/azure/devtest-labs/create-alerts |
| Create and manage tags for DevTest Labs resources | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-add-tag |
| Author Azure DevTest Labs custom artifact definitions | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-artifact-author |
| Configure VM autoshutdown policies in DevTest Labs | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-auto-shutdown |
| Set up VM autostart policies in DevTest Labs | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-auto-startup-vm |
| Configure allowed Azure Marketplace images for labs | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-configure-marketplace-images |
| Add and configure virtual networks for DevTest Labs | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-configure-vnet |
| Enable and manage licensed images in DevTest Labs | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-enable-licensed-images |
| Add internal support statements to DevTest Labs | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-internal-support-message |
| Configure DevTest Labs policies for VM usage and shutdown | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-set-lab-policy |
| Configure shared public IP addresses for DevTest Labs VMs | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-shared-ip |
| Handle DevTest Labs changes for Basic Load Balancer retirement | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-standard-load-balancer |
| Author ARM templates for DevTest Labs VMs | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-use-resource-manager-template |
| Configure resource groups for DevTest Labs virtual machines | https://learn.microsoft.com/en-us/azure/devtest-labs/resource-group-control |

### Deployment
| Topic | URL |
|-------|-----|
| Deploy DevTest Labs environments with nested ARM templates | https://learn.microsoft.com/en-us/azure/devtest-labs/deploy-nested-template-environments |
| Integrate DevTest Labs with enterprise CI/CD pipelines | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-dev-ops |
| Move Azure DevTest Labs and schedules to another region | https://learn.microsoft.com/en-us/azure/devtest-labs/how-to-move-labs |
| Use DevTest Labs in Azure Pipelines build and release | https://learn.microsoft.com/en-us/azure/devtest-labs/use-devtest-labs-build-release-pipelines |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Add and configure DevTest Labs artifacts on VMs | https://learn.microsoft.com/en-us/azure/devtest-labs/add-artifact-vm |
| Automate adding DevTest Labs users via ARM, PowerShell, CLI | https://learn.microsoft.com/en-us/azure/devtest-labs/automate-add-lab-user |
| Connect DevTest Labs environments to lab virtual networks | https://learn.microsoft.com/en-us/azure/devtest-labs/connect-environment-lab-virtual-network |
| Provision DevTest Labs and VMs using Bicep | https://learn.microsoft.com/en-us/azure/devtest-labs/create-lab-windows-vm-bicep |
| Create DevTest Labs and VMs with ARM templates | https://learn.microsoft.com/en-us/azure/devtest-labs/create-lab-windows-vm-template |
| Create DevTest Labs custom images from VHD using PowerShell | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-create-custom-image-from-vhd-using-powershell |
| Upload VHDs to DevTest Labs with AzCopy | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-upload-vhd-using-azcopy |
| Upload VHDs to DevTest Labs using PowerShell | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-upload-vhd-using-powershell |
| Upload VHDs to DevTest Labs via Azure Storage Explorer | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-upload-vhd-using-storage-explorer |
| Use ARM templates to provision DevTest Labs resources | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-use-arm-and-powershell-for-lab-resources |
| Create DevTest Labs VMs using PowerShell | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-vm-powershell |
| Manage DevTest Labs VMs with Azure CLI | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-vmcli |
| Extend Azure DevTest Labs using Azure Functions | https://learn.microsoft.com/en-us/azure/devtest-labs/extend-devtest-labs-azure-functions |
| Import DevTest Labs VMs via REST and PowerShell | https://learn.microsoft.com/en-us/azure/devtest-labs/import-virtual-machines-from-another-lab |
| Manage DevTest Labs via Azure REST API | https://learn.microsoft.com/en-us/azure/devtest-labs/quickstarts/create-lab-rest |
| Automate DevTest Labs creation with Terraform | https://learn.microsoft.com/en-us/azure/devtest-labs/quickstarts/create-lab-windows-vm-terraform |
| Use Azure CLI scripts to manage DevTest Labs VMs | https://learn.microsoft.com/en-us/azure/devtest-labs/samples-cli |
| Automate DevTest Labs tasks with PowerShell scripts | https://learn.microsoft.com/en-us/azure/devtest-labs/samples-powershell |
| Automate DevTest Labs VM start order with runbooks | https://learn.microsoft.com/en-us/azure/devtest-labs/start-machines-use-automation-runbooks |
| Publish Visual Studio apps to Azure DevTest Labs VMs | https://learn.microsoft.com/en-us/azure/devtest-labs/test-app-azure |
| Automate DevTest Labs VM start/stop via CLI/PowerShell | https://learn.microsoft.com/en-us/azure/devtest-labs/use-command-line-start-stop-virtual-machines |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| View and increase Azure quotas affecting DevTest Labs | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-scale-lab |

### Security
| Topic | URL |
|-------|-----|
| Configure managed identity and Key Vault for DevTest Labs | https://learn.microsoft.com/en-us/azure/devtest-labs/configure-lab-identity |
| Secure DevTest Labs access with Remote Desktop Gateway | https://learn.microsoft.com/en-us/azure/devtest-labs/configure-lab-remote-desktop-gateway |
| Connect DevTest Labs VMs via Azure Bastion | https://learn.microsoft.com/en-us/azure/devtest-labs/connect-virtual-machine-through-browser |
| Assign DevTest Labs RBAC roles and permissions | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-add-devtest-user |
| Configure DevTest Labs lab secrets securely | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-configure-lab-secrets |
| Grant permissions to specific DevTest Labs policies | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-grant-user-permissions-to-specific-lab-policies |
| Use Azure Key Vault secrets in DevTest Labs | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-store-secrets-in-key-vault |
| Enable Trusted Launch for DevTest Labs Gen2 VMs | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-trusted-launch |
| Enable secure browser-based VM access with Bastion | https://learn.microsoft.com/en-us/azure/devtest-labs/enable-browser-connection-lab-virtual-machines |
| Enable user-assigned managed identities on DevTest Labs VMs | https://learn.microsoft.com/en-us/azure/devtest-labs/enable-managed-identities-lab-vms |
| Configure customer-managed key disk encryption in DevTest Labs | https://learn.microsoft.com/en-us/azure/devtest-labs/encrypt-disks-customer-managed-keys |
| Manage DevTest Labs storage accounts and encryption | https://learn.microsoft.com/en-us/azure/devtest-labs/encrypt-storage |
| View and handle Defender security alerts in DevTest Labs environments | https://learn.microsoft.com/en-us/azure/devtest-labs/environment-security-alerts |
| Configure network isolation for Azure DevTest Labs | https://learn.microsoft.com/en-us/azure/devtest-labs/network-isolation |
| Use managed identities to deploy DevTest Labs environments | https://learn.microsoft.com/en-us/azure/devtest-labs/use-managed-identities-environments |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot Azure DevTest Labs artifact failures | https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-troubleshoot-apply-artifacts |
| Troubleshoot Azure DevTest Labs VM deployment failures | https://learn.microsoft.com/en-us/azure/devtest-labs/troubleshoot-vm-deployment-failures |
| Troubleshoot DevTest Labs VM and environment creation failures | https://learn.microsoft.com/en-us/azure/devtest-labs/troubleshoot-vm-environment-creation-failures |

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
