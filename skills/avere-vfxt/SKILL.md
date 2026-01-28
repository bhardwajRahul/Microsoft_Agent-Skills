---
name: avere-vfxt
description: Expert knowledge for Avere Vfxt development including configuration, best practices, deployment, security, and limits & quotas. Use when building, debugging, or optimizing Avere Vfxt applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Avere Vfxt Skill

This skill provides expert guidance for Avere Vfxt development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Optimize data ingestion performance for Avere vFXT | https://learn.microsoft.com/en-us/azure/avere-vfxt/avere-vfxt-data-ingest |
| Plan and size an Avere vFXT cluster in Azure | https://learn.microsoft.com/en-us/azure/avere-vfxt/avere-vfxt-deploy-plan |
| Tune Avere vFXT cluster performance settings | https://learn.microsoft.com/en-us/azure/avere-vfxt/avere-vfxt-tuning |
| Implement disaster recovery for Avere vFXT workflows | https://learn.microsoft.com/en-us/azure/avere-vfxt/disaster-recovery |

### Configuration
| Topic | URL |
|-------|-----|
| Configure back-end storage for Avere vFXT clusters | https://learn.microsoft.com/en-us/azure/avere-vfxt/avere-vfxt-add-storage |
| Access and configure Avere vFXT via control panel | https://learn.microsoft.com/en-us/azure/avere-vfxt/avere-vfxt-cluster-gui |
| Configure DNS load balancing for Avere vFXT clusters | https://learn.microsoft.com/en-us/azure/avere-vfxt/avere-vfxt-configure-dns |
| Enable automatic support data upload for Avere vFXT | https://learn.microsoft.com/en-us/azure/avere-vfxt/avere-vfxt-enable-support |
| Manage Avere vFXT cluster lifecycle and nodes | https://learn.microsoft.com/en-us/azure/avere-vfxt/avere-vfxt-manage-cluster |
| Mount clients and load-balance Avere vFXT access | https://learn.microsoft.com/en-us/azure/avere-vfxt/avere-vfxt-mount-clients |

### Deployment
| Topic | URL |
|-------|-----|
| Deploy an Avere vFXT cluster from Azure Marketplace | https://learn.microsoft.com/en-us/azure/avere-vfxt/avere-vfxt-deploy |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Meet Avere vFXT Azure prerequisites and quotas | https://learn.microsoft.com/en-us/azure/avere-vfxt/avere-vfxt-prereqs |

### Security
| Topic | URL |
|-------|-----|
| Create custom Azure roles to deploy Avere vFXT | https://learn.microsoft.com/en-us/azure/avere-vfxt/avere-vfxt-non-owner |

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
