---
name: update-manager
description: Expert knowledge for Update Manager development including configuration, security, comparing x vs. y, best practices, integrations & coding patterns, limits & quotas, deployment, and troubleshooting. Use when building, debugging, or optimizing Update Manager applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Update Manager Skill

This skill provides expert guidance for Update Manager development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Patching best practices for SQL Server on Azure VMs | https://learn.microsoft.com/en-us/azure/update-manager/guidance-patching-sql-server-azure-vm |
| Configure automatic guest patching for Azure VMs | https://learn.microsoft.com/en-us/azure/update-manager/support-matrix-automatic-guest-patching |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Map Configuration Manager patching to Azure services | https://learn.microsoft.com/en-us/azure/update-manager/guidance-migration-azure |

### Configuration
| Topic | URL |
|-------|-----|
| Configure Windows Update client for Azure Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/configure-wu-agent |
| Enroll Windows Server ESU with Azure Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/extended-security-updates |
| Configure alerts for Azure Update Manager events | https://learn.microsoft.com/en-us/azure/update-manager/manage-alerts |
| Configure and manage dynamic scopes in Azure Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/manage-dynamic-scoping |
| Configure hotpatching on Azure Arc-enabled Windows machines | https://learn.microsoft.com/en-us/azure/update-manager/manage-hot-patching-arc-machines |
| Manage existing pre and post maintenance events in Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/manage-pre-post-events |
| Manage Azure Update Manager configuration settings for machines | https://learn.microsoft.com/en-us/azure/update-manager/manage-update-settings |
| Enable periodic update assessment at scale with Policy | https://learn.microsoft.com/en-us/azure/update-manager/periodic-assessment-at-scale |
| Create pre and post maintenance events in Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/pre-post-events-schedule-maintenance-configuration |
| Review Azure Update Manager prerequisites and network setup | https://learn.microsoft.com/en-us/azure/update-manager/prerequisites |

### Deployment
| Topic | URL |
|-------|-----|
| Select update sources and types in Azure Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/support-matrix |
| Use Azure Update Manager OS and update support matrix | https://learn.microsoft.com/en-us/azure/update-manager/support-matrix-updates |
| Check Azure Update Manager supported regions and clouds | https://learn.microsoft.com/en-us/azure/update-manager/supported-regions |
| Identify workloads unsupported by Azure Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/unsupported-workloads |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Use Update Manager REST API for Arc-enabled servers | https://learn.microsoft.com/en-us/azure/update-manager/manage-arc-enabled-servers-programmatically |
| Use Azure Update Manager REST API for VM updates | https://learn.microsoft.com/en-us/azure/update-manager/manage-vms-programmatically |
| Access Update Manager data via Azure Resource Graph | https://learn.microsoft.com/en-us/azure/update-manager/query-logs |
| Use sample Resource Graph queries for Update Manager logs | https://learn.microsoft.com/en-us/azure/update-manager/sample-query-logs |
| Trigger Update Manager maintenance events using Azure Functions | https://learn.microsoft.com/en-us/azure/update-manager/tutorial-using-functions |
| Integrate Update Manager maintenance events with Automation runbooks | https://learn.microsoft.com/en-us/azure/update-manager/tutorial-webhooks-using-runbooks |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Customized image support and limits in Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/manage-updates-customized-images |

### Security
| Topic | URL |
|-------|-----|
| Enable secure cross-subscription patching with roles and CLI | https://learn.microsoft.com/en-us/azure/update-manager/enable-cross-subscription-patching |
| Assign Azure Update Manager roles and permissions | https://learn.microsoft.com/en-us/azure/update-manager/roles-permissions |
| Handle security vulnerabilities and Ubuntu Pro in Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/security-awareness-ubuntu-support |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot common Azure Update Manager issues | https://learn.microsoft.com/en-us/azure/update-manager/troubleshoot |

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
