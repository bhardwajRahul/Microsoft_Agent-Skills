---
name: managed-grafana
description: Expert knowledge for Managed Grafana development including configuration, integrations & coding patterns, security, limits & quotas, deployment, and troubleshooting. Use when building, debugging, or optimizing Managed Grafana applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Managed Grafana Skill

This skill provides expert guidance for Managed Grafana development. It combines local quick-reference content with remote documentation fetching capabilities.

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

### Configuration
| Topic | URL |
|-------|-----|
| Configure Agent Framework monitoring dashboard in Grafana | https://learn.microsoft.com/en-us/azure/managed-grafana/agent-framework-dashboard |
| Configure workflow monitoring dashboard for Agent Framework | https://learn.microsoft.com/en-us/azure/managed-grafana/agent-framework-workflow-dashboard |
| Configure Azure Managed Grafana instance settings | https://learn.microsoft.com/en-us/azure/managed-grafana/grafana-settings |
| Manage Grafana plugins from Azure Managed Grafana workspace | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-manage-plugins |
| Monitor Managed Grafana with Azure Monitor metrics | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-monitor-managed-grafana-metrics |
| Configure diagnostic settings for Managed Grafana workspaces | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-monitor-managed-grafana-workspace |
| Configure SMTP email alerts in Azure Managed Grafana | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-smtp-settings |

### Deployment
| Topic | URL |
|-------|-----|
| Enable zone-redundant Azure Managed Grafana workspaces | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-enable-zone-redundancy |
| Migrate existing Grafana instances to Azure Managed Grafana | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-migrate |
| Migrate from Managed Grafana Essential to Standard or Azure Monitor | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-migrate-essential-service-tier |
| Upgrade Azure Managed Grafana workspaces to Grafana 11 | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-upgrade-grafana-11 |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Build an Azure AI Foundry metrics dashboard in Grafana | https://learn.microsoft.com/en-us/azure/managed-grafana/azure-ai-foundry-dashboard |
| Configure bundled Prometheus integration in Azure Managed Grafana | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-bundled-prometheus |
| Add and authenticate Azure Data Explorer as a Grafana data source | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-connect-azure-data-explorer |
| Connect Azure Monitor workspace Prometheus metrics to Grafana | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-connect-azure-monitor-workspace |
| Manage Azure Managed Grafana data sources and authentication | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-data-source-plugins-managed-identity |
| Connect AKS Prometheus to Grafana via managed private endpoint | https://learn.microsoft.com/en-us/azure/managed-grafana/tutorial-mpe-oss-prometheus |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Understand reliability and availability for Managed Grafana | https://learn.microsoft.com/en-us/azure/managed-grafana/high-availability |
| Use Azure Monitor alerts with Managed Grafana | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-use-azure-monitor-alerts |
| Use reporting and image rendering in Azure Managed Grafana | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-use-reporting-and-image-rendering |
| Review Azure Managed Grafana service limits and constraints | https://learn.microsoft.com/en-us/azure/managed-grafana/known-limitations |

### Security
| Topic | URL |
|-------|-----|
| Understand data encryption in Azure Managed Grafana | https://learn.microsoft.com/en-us/azure/managed-grafana/encryption |
| Configure authentication and data access for Azure Managed Grafana | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-authentication-permissions |
| Connect Managed Grafana to data sources privately | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-connect-to-data-source-privately |
| Enable deterministic outbound IPs for Managed Grafana | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-deterministic-ip |
| Assign Grafana roles to users and identities in Azure | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-manage-access-permissions-users-identities |
| Manage Azure Monitor access permissions for Grafana workspaces | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-permissions |
| Use service accounts and tokens in Managed Grafana | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-service-accounts |
| Configure private access for Azure Managed Grafana | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-set-up-private-access |
| Configure Grafana Team Sync with Microsoft Entra groups | https://learn.microsoft.com/en-us/azure/managed-grafana/how-to-sync-teams-with-entra-groups |
| Apply security best practices to Azure Managed Grafana | https://learn.microsoft.com/en-us/azure/managed-grafana/secure-azure-managed-grafana |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot common Azure Managed Grafana issues | https://learn.microsoft.com/en-us/azure/managed-grafana/troubleshoot-managed-grafana |
| Fix Managed Grafana managed private endpoint connection issues | https://learn.microsoft.com/en-us/azure/managed-grafana/troubleshoot-mpe-connection |

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
