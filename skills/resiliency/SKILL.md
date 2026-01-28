---
name: resiliency
description: Expert knowledge for Resiliency development including configuration, limits & quotas, and security. Use when building, debugging, or optimizing Resiliency applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Resiliency Skill

This skill provides expert guidance for Resiliency development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Create backup and replication protection policies | https://learn.microsoft.com/en-us/azure/resiliency/backup-protection-policy |
| Configure Recovery Services and Backup vaults | https://learn.microsoft.com/en-us/azure/resiliency/backup-vaults |
| View and manage Resiliency protection policies | https://learn.microsoft.com/en-us/azure/resiliency/manage-protection-policy |
| Manage lifecycle of Azure Resiliency vaults | https://learn.microsoft.com/en-us/azure/resiliency/manage-vault |
| Configure and monitor Resiliency compliance state | https://learn.microsoft.com/en-us/azure/resiliency/tutorial-govern-monitor-compliance |
| Configure alerts and metrics in Resiliency | https://learn.microsoft.com/en-us/azure/resiliency/tutorial-monitor-alerts-metrics |
| Set up backup and DR reports in Resiliency | https://learn.microsoft.com/en-us/azure/resiliency/tutorial-reporting-for-data-insights |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Resiliency support matrix and feature limitations | https://learn.microsoft.com/en-us/azure/resiliency/resiliency-support-matrix |

### Security
| Topic | URL |
|-------|-----|
| Understand security levels in Azure Resiliency | https://learn.microsoft.com/en-us/azure/resiliency/security-levels-concept |
| Review and adjust Resiliency security posture | https://learn.microsoft.com/en-us/azure/resiliency/tutorial-review-security-posture |

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
