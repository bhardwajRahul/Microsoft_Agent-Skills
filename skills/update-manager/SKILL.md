---
name: update-manager
description: Expert knowledge for Update Manager development including configuration, security, comparing x vs. y, best practices, integrations & coding patterns, limits & quotas, and troubleshooting. Use when building, debugging, or optimizing Update Manager applications.
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
| Apply patching best practices for SQL Server on Azure VMs | https://learn.microsoft.com/en-us/azure/update-manager/guidance-patching-sql-server-azure-vm |
| Handle Ubuntu security awareness and Pro support in Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/security-awareness-ubuntu-support |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Map Configuration Manager patching to Azure Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/guidance-migration-azure |

### Configuration
| Topic | URL |
|-------|-----|
| Configure Windows Update client for Azure Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/configure-wu-agent |
| Enroll and manage ESU for Windows Server via Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/extended-security-updates |
| Configure alerts for Azure Update Manager events | https://learn.microsoft.com/en-us/azure/update-manager/manage-alerts |
| Configure and manage dynamic scopes for maintenance | https://learn.microsoft.com/en-us/azure/update-manager/manage-dynamic-scoping |
| Configure hotpatching on Azure Arc-enabled machines | https://learn.microsoft.com/en-us/azure/update-manager/manage-hot-patching-arc-machines |
| Manage pre and post maintenance events for updates | https://learn.microsoft.com/en-us/azure/update-manager/manage-pre-post-events |
| Manage update configuration settings for Azure machines | https://learn.microsoft.com/en-us/azure/update-manager/manage-update-settings |
| Enable periodic update assessment at scale with Policy | https://learn.microsoft.com/en-us/azure/update-manager/periodic-assessment-at-scale |
| Create pre and post maintenance events in Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/pre-post-events-schedule-maintenance-configuration |
| Configure prerequisites and network for Azure Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/prerequisites |
| Configure recurring update schedules in Azure Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/scheduled-patching |
| Configure update sources and types in Azure Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/support-matrix |
| Configure automatic guest patching for Azure VMs | https://learn.microsoft.com/en-us/azure/update-manager/support-matrix-automatic-guest-patching |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Use Update Manager REST API for Arc-enabled servers | https://learn.microsoft.com/en-us/azure/update-manager/manage-arc-enabled-servers-programmatically |
| Use Azure Update Manager REST API for VM updates | https://learn.microsoft.com/en-us/azure/update-manager/manage-vms-programmatically |
| Query Update Manager data via Azure Resource Graph | https://learn.microsoft.com/en-us/azure/update-manager/query-logs |
| Use sample Resource Graph queries for Update Manager logs | https://learn.microsoft.com/en-us/azure/update-manager/sample-query-logs |
| Integrate Update Manager maintenance events with Azure Functions | https://learn.microsoft.com/en-us/azure/update-manager/tutorial-using-functions |
| Integrate Update Manager maintenance events with Automation runbooks | https://learn.microsoft.com/en-us/azure/update-manager/tutorial-webhooks-using-runbooks |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Understand customized image support and limits in Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/manage-updates-customized-images |
| Check OS and update support matrix for Azure Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/support-matrix-updates |
| Understand unsupported workloads in Azure Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/unsupported-workloads |

### Security
| Topic | URL |
|-------|-----|
| Enable secure cross-subscription patching with roles and CLI | https://learn.microsoft.com/en-us/azure/update-manager/enable-cross-subscription-patching |
| Assign roles and permissions for Azure Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/roles-permissions |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot errors and issues in Azure Update Manager | https://learn.microsoft.com/en-us/azure/update-manager/troubleshoot |

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
