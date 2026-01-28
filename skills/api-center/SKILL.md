---
name: api-center
description: Expert knowledge for Api Center development including security, integrations & coding patterns, configuration, and deployment. Use when building, debugging, or optimizing Api Center applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Api Center Skill

This skill provides expert guidance for Api Center development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Customize settings in the Azure API Center portal | https://learn.microsoft.com/en-us/azure/api-center/customize-api-center-portal |

### Deployment
| Topic | URL |
|-------|-----|
| Automate API Center registration with GitHub Actions CI/CD | https://learn.microsoft.com/en-us/azure/api-center/register-apis-github-actions |
| Deploy and self-host the Azure API Center portal | https://learn.microsoft.com/en-us/azure/api-center/self-host-api-center-portal |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Build and register APIs via API Center VS Code extension | https://learn.microsoft.com/en-us/azure/api-center/build-register-apis-vscode-extension |
| Design compliant APIs with API Center GitHub Copilot plugin | https://learn.microsoft.com/en-us/azure/api-center/design-api-github-copilot-azure |
| Export API Center APIs as Copilot Studio connectors | https://learn.microsoft.com/en-us/azure/api-center/export-to-copilot-studio |
| Import Azure API Management APIs into API Center | https://learn.microsoft.com/en-us/azure/api-center/import-api-management-apis |
| Manage Azure API Center inventory with Azure CLI | https://learn.microsoft.com/en-us/azure/api-center/manage-apis-azure-cli |
| Automate API Center notifications with Logic Apps and Teams | https://learn.microsoft.com/en-us/azure/api-center/set-up-notification-workflow |
| Synchronize Azure API Management with API Center | https://learn.microsoft.com/en-us/azure/api-center/synchronize-api-management-apis |
| Synchronize Amazon API Gateway APIs to Azure API Center | https://learn.microsoft.com/en-us/azure/api-center/synchronize-aws-gateway-apis |

### Security
| Topic | URL |
|-------|-----|
| Configure API access security in Azure API Center | https://learn.microsoft.com/en-us/azure/api-center/authorize-api-access |
| Enable secure API Center portal view in VS Code | https://learn.microsoft.com/en-us/azure/api-center/enable-api-center-portal-vs-code-extension |
| Set up secure Azure API Center portal access | https://learn.microsoft.com/en-us/azure/api-center/set-up-api-center-portal |

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
