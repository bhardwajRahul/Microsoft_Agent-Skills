---
name: static-web-apps
description: Expert knowledge for Static Web Apps development including security, integrations & coding patterns, configuration, deployment, troubleshooting, limits & quotas, architecture & design patterns, and comparing x vs. y. Use when building, debugging, or optimizing Static Web Apps applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Static Web Apps Skill

This skill provides expert guidance for Static Web Apps development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Choose Next.js deployment model on Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/nextjs |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Compare Azure Static Web Apps Free vs Standard plans | https://learn.microsoft.com/en-us/azure/static-web-apps/plans |

### Configuration
| Topic | URL |
|-------|-----|
| Configure apex domains via Azure DNS for Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/apex-domain-azure-dns |
| Configure apex/root domains for Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/apex-domain-external |
| Configure Azure Functions APIs in Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/apis-functions |
| Set backend application settings in Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/application-settings |
| Configure CI/CD build YAML for Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/build-configuration |
| Define staticwebapp.config.json for Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/configuration |
| Configure custom domains for Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/custom-domain |
| Use Azure DNS custom domains with Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/custom-domain-azure-dns |
| Manage default domain routing in Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/custom-domain-default |
| Set custom domains with external DNS for Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/custom-domain-external |
| Configure database connections for Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/database-configuration |
| Configure front-end framework build settings for Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/front-end-frameworks |
| Link existing Azure Functions apps to Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/functions-bring-your-own |
| Configure local development environment for Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/local-development |
| Configure Application Insights monitoring for Azure Static Web Apps APIs | https://learn.microsoft.com/en-us/azure/static-web-apps/monitor |
| Reference for Azure Static Web Apps CLI commands and options | https://learn.microsoft.com/en-us/azure/static-web-apps/static-web-apps-cli |
| Run and debug APIs locally with SWA CLI API server | https://learn.microsoft.com/en-us/azure/static-web-apps/static-web-apps-cli-api-server |
| Configure Azure Static Web Apps CLI with swa-cli.config.json | https://learn.microsoft.com/en-us/azure/static-web-apps/static-web-apps-cli-configuration |
| Use the Azure Static Web Apps CLI emulator | https://learn.microsoft.com/en-us/azure/static-web-apps/static-web-apps-cli-emulator |
| Install Azure Static Web Apps CLI with supported runtimes | https://learn.microsoft.com/en-us/azure/static-web-apps/static-web-apps-cli-install |
| Understand and use the Azure Static Web Apps CLI | https://learn.microsoft.com/en-us/azure/static-web-apps/static-web-apps-cli-overview |

### Deployment
| Topic | URL |
|-------|-----|
| Deploy Bitbucket repositories to Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/bitbucket |
| Create branch-based preview environments in Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/branch-environments |
| Use external CI/CD providers with Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/external-providers |
| Manually configure Azure Front Door CDN for Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/front-door-manual |
| Deploy GitLab repositories to Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/gitlab |
| Create named preview environments in Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/named-environments |
| Use preview environments for Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/preview-environments |
| Deploy Azure Static Web Apps using ARM templates | https://learn.microsoft.com/en-us/azure/static-web-apps/publish-azure-resource-manager |
| Deploy Azure Static Web Apps using Bicep templates | https://learn.microsoft.com/en-us/azure/static-web-apps/publish-bicep |
| Review pull requests in Static Web Apps pre-production environments | https://learn.microsoft.com/en-us/azure/static-web-apps/review-publish-pull-requests |
| Deploy Static Web Apps using the SWA CLI deploy command | https://learn.microsoft.com/en-us/azure/static-web-apps/static-web-apps-cli-deploy |
| Configure traffic splitting for Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/traffic-splitting |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Use Mongoose with Azure Cosmos DB in Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/add-mongoose |
| Integrate Azure API Management with Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/apis-api-management |
| Integrate Azure App Service APIs with Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/apis-app-service |
| Integrate Azure Container Apps with Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/apis-container-apps |
| Connect Azure Static Web Apps to Azure Cosmos DB | https://learn.microsoft.com/en-us/azure/static-web-apps/database-azure-cosmos-db |
| Connect Azure Static Web Apps to Azure SQL | https://learn.microsoft.com/en-us/azure/static-web-apps/database-azure-sql |
| Connect Azure Static Web Apps to MySQL Flexible Server | https://learn.microsoft.com/en-us/azure/static-web-apps/database-mysql |
| Connect Azure Static Web Apps to PostgreSQL | https://learn.microsoft.com/en-us/azure/static-web-apps/database-postgresql |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Supported languages and runtimes for Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/languages-runtimes |
| Understand metrics for managed Functions in Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/metrics |
| Quotas and limits for Azure Static Web Apps plans | https://learn.microsoft.com/en-us/azure/static-web-apps/quotas |

### Security
| Topic | URL |
|-------|-----|
| Configure authentication for Azure Static Web Apps sites | https://learn.microsoft.com/en-us/azure/static-web-apps/add-authentication |
| Assign Static Web Apps roles using Microsoft Graph and Entra groups | https://learn.microsoft.com/en-us/azure/static-web-apps/assign-roles-microsoft-graph |
| Configure authentication and authorization for Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/authentication-authorization |
| Configure custom authentication providers for Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/authentication-custom |
| Manage and reset deployment tokens for Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/deployment-token-management |
| Use Key Vault and managed identity for Static Web Apps auth secrets | https://learn.microsoft.com/en-us/azure/static-web-apps/key-vault-secrets |
| Enable password protection for Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/password-protection |
| Restrict Static Web Apps access with private endpoints | https://learn.microsoft.com/en-us/azure/static-web-apps/private-endpoint |
| Access authenticated user information in Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/user-information |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Azure Static Web Apps FAQ for behavior and limitations | https://learn.microsoft.com/en-us/azure/static-web-apps/faq |
| Troubleshoot deployment and runtime issues in Azure Static Web Apps | https://learn.microsoft.com/en-us/azure/static-web-apps/troubleshooting |

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
