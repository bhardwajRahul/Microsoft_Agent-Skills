---
name: lab-services
description: Expert knowledge for Lab Services development including security, configuration, best practices, limits & quotas, architecture & design patterns, comparing x vs. y, integrations & coding patterns, deployment, and troubleshooting. Use when building, debugging, or optimizing Lab Services applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Lab Services Skill

This skill provides expert guidance for Lab Services development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Understand Azure Lab Services architecture fundamentals and components | https://learn.microsoft.com/en-us/azure/lab-services/classroom-labs-fundamentals |
| Select supported networking architectures for Azure Lab Services lab plans | https://learn.microsoft.com/en-us/azure/lab-services/concept-lab-services-supported-networking-scenarios |
| Choose GPU VM sizes for Azure Lab Services | https://learn.microsoft.com/en-us/azure/lab-services/how-to-setup-lab-gpu |

### Best Practices
| Topic | URL |
|-------|-----|
| Recommended approaches for creating Lab Services custom images | https://learn.microsoft.com/en-us/azure/lab-services/approaches-for-custom-image-creation |
| Apply cost-optimized migration practices from physical labs to Azure Lab Services | https://learn.microsoft.com/en-us/azure/lab-services/concept-migrating-physical-labs |
| Configure nested virtualization in Azure Lab Services | https://learn.microsoft.com/en-us/azure/lab-services/concept-nested-virtualization-template-vm |
| Optimize Linux lab remote desktop performance | https://learn.microsoft.com/en-us/azure/lab-services/how-to-enable-remote-desktop-linux |
| Prepare Windows lab templates with recommended settings | https://learn.microsoft.com/en-us/azure/lab-services/how-to-prepare-windows-template |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Compare lab accounts and lab plans in Azure Lab Services | https://learn.microsoft.com/en-us/azure/lab-services/concept-lab-accounts-versus-lab-plans |
| Decide when to move from Lab Services to DevTest Labs | https://learn.microsoft.com/en-us/azure/lab-services/transition-devtest-labs-guidance |

### Configuration
| Topic | URL |
|-------|-----|
| Allow lab creators to choose lab locations in Azure Lab Services | https://learn.microsoft.com/en-us/azure/lab-services/allow-lab-creator-pick-lab-location |
| Configure allowed regions for creating Azure labs | https://learn.microsoft.com/en-us/azure/lab-services/create-and-configure-labs-admin |
| Attach or detach Azure compute galleries from lab plans | https://learn.microsoft.com/en-us/azure/lab-services/how-to-attach-detach-shared-image-gallery |
| Attach or detach Shared Image Gallery to Azure Lab Services lab accounts | https://learn.microsoft.com/en-us/azure/lab-services/how-to-attach-detach-shared-image-gallery-1 |
| Configure auto-shutdown behavior for Azure Lab VMs | https://learn.microsoft.com/en-us/azure/lab-services/how-to-configure-auto-shutdown-lab-plans |
| Configure automatic VM shutdown for Azure Lab Services lab accounts | https://learn.microsoft.com/en-us/azure/lab-services/how-to-configure-lab-accounts |
| Configure advanced networking and VNet injection for lab plans | https://learn.microsoft.com/en-us/azure/lab-services/how-to-connect-vnet-injection |
| Configure automatic start/stop schedules for Lab Services VMs | https://learn.microsoft.com/en-us/azure/lab-services/how-to-create-schedules |
| Enable nested virtualization on Lab Services templates | https://learn.microsoft.com/en-us/azure/lab-services/how-to-enable-nested-virtualization-template-vm-using-script |
| Configure automatic shutdown policies for lab VMs | https://learn.microsoft.com/en-us/azure/lab-services/how-to-enable-shutdown-disconnect |
| Configure and manage Lab Services users and usage hours | https://learn.microsoft.com/en-us/azure/lab-services/how-to-manage-lab-users |
| Set up GPU-based labs in Azure Lab Services using lab accounts | https://learn.microsoft.com/en-us/azure/lab-services/how-to-setup-lab-gpu-1 |
| Configure Windows lab VMs to disable shutdown | https://learn.microsoft.com/en-us/azure/lab-services/how-to-windows-shutdown |
| Configure support contact information for Lab Services accounts | https://learn.microsoft.com/en-us/azure/lab-services/lab-account-owner-support-information |
| Configure allowed Azure Marketplace images for labs | https://learn.microsoft.com/en-us/azure/lab-services/specify-marketplace-images |
| Specify allowed Marketplace images in Azure Lab Services lab accounts | https://learn.microsoft.com/en-us/azure/lab-services/specify-marketplace-images-1 |
| Configure advanced networking for Azure Lab Services lab plans | https://learn.microsoft.com/en-us/azure/lab-services/tutorial-create-lab-with-advanced-networking |

### Deployment
| Topic | URL |
|-------|-----|
| Import a Linux custom image from an Azure VM into Lab Services | https://learn.microsoft.com/en-us/azure/lab-services/how-to-bring-custom-linux-image-azure-vm |
| Import a Linux custom image from a physical lab into Lab Services | https://learn.microsoft.com/en-us/azure/lab-services/how-to-bring-custom-linux-image-vhd |
| Create a Lab Services lab from an existing Windows VM image | https://learn.microsoft.com/en-us/azure/lab-services/how-to-bring-custom-windows-image-azure-vm |
| Import a Windows custom image from a physical lab into Lab Services | https://learn.microsoft.com/en-us/azure/lab-services/upload-custom-image-shared-image-gallery |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Connect Linux lab VMs using X2Go client | https://learn.microsoft.com/en-us/azure/lab-services/connect-virtual-machine-linux-x2go |
| Configure Canvas LMS integration with Azure Lab Services | https://learn.microsoft.com/en-us/azure/lab-services/how-to-configure-canvas-for-lab-plans |
| Configure Microsoft Teams integration with Azure Lab Services | https://learn.microsoft.com/en-us/azure/lab-services/how-to-configure-teams-for-lab-plans |
| Connect Azure Lab Services labs to peer virtual networks | https://learn.microsoft.com/en-us/azure/lab-services/how-to-connect-peer-virtual-network |
| Provision an Azure Lab Services lab using Bicep templates | https://learn.microsoft.com/en-us/azure/lab-services/how-to-create-lab-bicep |
| Provision Azure Lab Services lab plans with Bicep or ARM | https://learn.microsoft.com/en-us/azure/lab-services/how-to-create-lab-plan-bicep |
| Create Azure Lab Services lab plans with PowerShell | https://learn.microsoft.com/en-us/azure/lab-services/how-to-create-lab-plan-powershell |
| Create Azure Lab Services lab plans using Python SDK | https://learn.microsoft.com/en-us/azure/lab-services/how-to-create-lab-plan-python |
| Create an Azure Lab Services lab using PowerShell and Az modules | https://learn.microsoft.com/en-us/azure/lab-services/how-to-create-lab-powershell |
| Create an Azure Lab Services lab using the Python SDK | https://learn.microsoft.com/en-us/azure/lab-services/how-to-create-lab-python |
| Use the Az.LabServices PowerShell module for Azure Lab Services | https://learn.microsoft.com/en-us/azure/lab-services/reference-powershell-module |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Understand Azure Lab Services VM capacity limits | https://learn.microsoft.com/en-us/azure/lab-services/capacity-limits |
| Determine Azure Lab Services core quota usage | https://learn.microsoft.com/en-us/azure/lab-services/how-to-determine-your-quota-usage |
| Request Azure Lab Services core quota increases | https://learn.microsoft.com/en-us/azure/lab-services/how-to-request-capacity-increase |
| Understand VM inactivity deletion policy in Azure Lab Services | https://learn.microsoft.com/en-us/azure/lab-services/vm-deletion-policy |

### Security
| Topic | URL |
|-------|-----|
| Assign Lab Creator role in Azure Lab Services | https://learn.microsoft.com/en-us/azure/lab-services/add-lab-creator |
| Enforce Azure Lab Services settings with Azure Policy | https://learn.microsoft.com/en-us/azure/lab-services/azure-polices-for-lab-services |
| Configure Azure RBAC roles for Azure Lab Services | https://learn.microsoft.com/en-us/azure/lab-services/concept-lab-services-role-based-access-control |
| Map lab account roles to lab plan RBAC in Azure Lab Services | https://learn.microsoft.com/en-us/azure/lab-services/concept-migrate-from-lab-accounts-roles |
| Assign Lab Creator role for Azure Lab Services lab accounts | https://learn.microsoft.com/en-us/azure/lab-services/how-to-add-lab-creator |
| Add additional lab owners in Azure Lab Services | https://learn.microsoft.com/en-us/azure/lab-services/how-to-add-user-lab-owner |
| Use Lab Services public IPs to configure firewall rules | https://learn.microsoft.com/en-us/azure/lab-services/how-to-configure-firewall-settings |
| Configure firewall access for Azure Lab Services lab VMs | https://learn.microsoft.com/en-us/azure/lab-services/how-to-configure-firewall-settings-1 |
| Restrict Lab Services VM sizes using Azure Policy | https://learn.microsoft.com/en-us/azure/lab-services/how-to-use-restrict-allowed-virtual-machine-sku-sizes-policy |
| Use built-in Azure Policy definitions for Lab Services | https://learn.microsoft.com/en-us/azure/lab-services/policy-reference |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot Azure Lab Services VM connectivity issues | https://learn.microsoft.com/en-us/azure/lab-services/how-to-reset-and-redeploy-vm |
| Diagnose and fix Azure Lab Services VM access issues | https://learn.microsoft.com/en-us/azure/lab-services/troubleshoot-access-lab-vm |
| Troubleshoot connectivity problems in Azure Lab Services | https://learn.microsoft.com/en-us/azure/lab-services/troubleshoot-connect-lab-vm |
| Troubleshoot lab creation issues in Azure Lab Services | https://learn.microsoft.com/en-us/azure/lab-services/troubleshoot-lab-creation |

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
