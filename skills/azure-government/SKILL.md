---
name: azure-government
description: Expert knowledge for Azure Government development including security, comparing x vs. y, deployment, best practices, configuration, and integrations & coding patterns. Use when building, debugging, or optimizing Azure Government applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Azure Government Skill

This skill provides expert guidance for Azure Government development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Name Azure resources to avoid sensitive data spillage | https://learn.microsoft.com/en-us/azure/azure-government/documentation-government-concept-naming-resources |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Compare Azure Government vs global Azure capabilities | https://learn.microsoft.com/en-us/azure/azure-government/compare-azure-government-global-azure |

### Configuration
| Topic | URL |
|-------|-----|
| Configure SSMS to connect to Azure Government SQL | https://learn.microsoft.com/en-us/azure/azure-government/documentation-government-connect-ssms |
| Develop and deploy applications on Azure Government | https://learn.microsoft.com/en-us/azure/azure-government/documentation-government-developer-guide |
| List and use virtual machine extensions in Azure Government | https://learn.microsoft.com/en-us/azure/azure-government/documentation-government-extension |
| Use Azure Government Marketplace image gallery and custom VHDs | https://learn.microsoft.com/en-us/azure/azure-government/documentation-government-image-gallery |
| Use Azure Monitor logs in Azure Government environments | https://learn.microsoft.com/en-us/azure/azure-government/documentation-government-manage-oms |

### Deployment
| Topic | URL |
|-------|-----|
| Set up Azure Pipelines CI/CD to Azure Government App Service | https://learn.microsoft.com/en-us/azure/azure-government/connect-with-azure-pipelines |
| Baseline App Service Environment deployment with DISA CAP | https://learn.microsoft.com/en-us/azure/azure-government/documentation-government-ase-disa-cap |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Use Azure Storage APIs in Azure Government | https://learn.microsoft.com/en-us/azure/azure-government/documentation-government-get-started-connect-to-storage |

### Security
| Topic | URL |
|-------|-----|
| Implement secure isolation across Azure compute, network, and storage | https://learn.microsoft.com/en-us/azure/azure-government/azure-secure-isolation-guidance |
| Understand FedRAMP and DoD compliance scope for Microsoft clouds | https://learn.microsoft.com/en-us/azure/azure-government/compliance/azure-services-in-fedramp-auditscope |
| Configure Azure services to align with TIC guidance | https://learn.microsoft.com/en-us/azure/azure-government/compliance/compliance-tic |
| Apply Secure Azure Computing Architecture for DoD compliance | https://learn.microsoft.com/en-us/azure/azure-government/compliance/secure-azure-computing-architecture |
| Configure Microsoft Entra authentication for Azure Government apps | https://learn.microsoft.com/en-us/azure/azure-government/documentation-government-aad-auth-qs |
| Configure Azure Government isolation for DoD IL5 workloads | https://learn.microsoft.com/en-us/azure/azure-government/documentation-government-impact-level-5 |
| Plan identity management for Azure Government tenants | https://learn.microsoft.com/en-us/azure/azure-government/documentation-government-plan-identity |
| Secure Azure Government workloads with built-in controls | https://learn.microsoft.com/en-us/azure/azure-government/documentation-government-plan-security |

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
