---
name: azure-functions
description: Expert knowledge for Azure Functions development including integrations & coding patterns, architecture & design patterns, best practices, configuration, troubleshooting, security, deployment, and comparing x vs. y. Use when building, debugging, or optimizing Azure Functions applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Azure Functions Skill

This skill provides expert guidance for Azure Functions development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Understand Azure Managed Redis internal architecture | https://learn.microsoft.com/en-us/azure/redis/architecture |

### Best Practices
| Topic | URL |
|-------|-----|
| Apply client library best practices for Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/best-practices-client-libraries |
| Design resilient connections to Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/best-practices-connection |
| Implement development best practices for Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/best-practices-development |
| Host Kubernetes client apps using Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/best-practices-kubernetes |
| Optimize Azure Managed Redis memory management | https://learn.microsoft.com/en-us/azure/redis/best-practices-memory-management |
| Run performance testing for Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/best-practices-performance |
| Apply scaling best practices for Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/best-practices-scale |
| Monitor and manage Azure Managed Redis server load | https://learn.microsoft.com/en-us/azure/redis/best-practices-server-load |
| Understand failover and patching behavior in Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/failover |
| Key FAQs and patterns for Azure Redis services | https://learn.microsoft.com/en-us/azure/redis/faq |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Plan and purchase Azure Managed Redis reservations | https://learn.microsoft.com/en-us/azure/redis/reserved-pricing |

### Configuration
| Topic | URL |
|-------|-----|
| Configure Azure Managed Redis instance settings | https://learn.microsoft.com/en-us/azure/redis/configure |
| Set up active geo-replication for Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/how-to-active-geo-replication |
| Manage Azure Redis instances with PowerShell commands | https://learn.microsoft.com/en-us/azure/redis/how-to-manage-redis-cache-powershell |
| Configure data persistence for Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/how-to-persistence |
| Configure monitoring and metrics for Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/monitor-cache |
| Reference metrics and logs for monitoring Azure Cache for Redis | https://learn.microsoft.com/en-us/azure/redis/monitor-cache-reference |
| Configure diagnostic settings for Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/monitor-diagnostic-settings |
| Configure Redis modules for Azure Managed Redis instances | https://learn.microsoft.com/en-us/azure/redis/redis-modules |
| Configure maintenance windows for Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/scheduled-maintenance |
| Create and manage Azure Redis via Azure CLI | https://learn.microsoft.com/en-us/azure/redis/scripts/create-manage-cache |

### Deployment
| Topic | URL |
|-------|-----|
| Import and export data with Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/how-to-import-export-data |
| Upgrade Redis server versions in Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/how-to-upgrade |
| Plan migration from Azure Cache for Redis to Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/migrate/migrate-overview |
| Migrate existing Redis caches to Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/migrate/migration-guide |
| Deploy Azure Cache for Redis with ARM templates | https://learn.microsoft.com/en-us/azure/redis/redis-cache-arm-provision |
| Deploy Azure Cache for Redis using Bicep templates | https://learn.microsoft.com/en-us/azure/redis/redis-cache-bicep-provision |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Use Azure Functions bindings with Azure Redis services | https://learn.microsoft.com/en-us/azure/azure-functions/functions-bindings-cache |
| Configure ASP.NET Core output caching with Azure Redis | https://learn.microsoft.com/en-us/azure/redis/aspnet-core-output-cache-provider |
| Access Azure Cache for Redis from .NET Core | https://learn.microsoft.com/en-us/azure/redis/dotnet-core-quickstart |
| Connect .NET Framework apps to Azure Redis | https://learn.microsoft.com/en-us/azure/redis/dotnet-how-to-use-azure-redis-cache |
| Use Azure Cache for Redis in Java with Jedis | https://learn.microsoft.com/en-us/azure/redis/java-get-started |
| Use Azure Redis cache in ASP.NET Core apps | https://learn.microsoft.com/en-us/azure/redis/web-app-aspnet-core-howto |
| Integrate Azure Redis caching into ASP.NET web apps | https://learn.microsoft.com/en-us/azure/redis/web-app-cache-howto |

### Security
| Topic | URL |
|-------|-----|
| Use Microsoft Entra authentication with Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/entra-for-authentication |
| Connect Go applications securely to Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/go-get-started |
| Configure disk encryption for Azure Managed Redis data | https://learn.microsoft.com/en-us/azure/redis/how-to-encryption |
| Authenticate Node.js TypeScript apps to Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/nodejs-get-started |
| Secure Azure Managed Redis with Private Link | https://learn.microsoft.com/en-us/azure/redis/private-link |
| Secure Python connections to Azure Managed Redis with Entra ID | https://learn.microsoft.com/en-us/azure/redis/python-get-started |
| Apply Azure Policy compliance controls to Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/security-controls-policy |
| Configure TLS settings for Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/tls-configuration |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Resolve common Azure Managed Redis development issues | https://learn.microsoft.com/en-us/azure/redis/development-faq |
| Use redis-cli to debug Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/how-to-redis-cli-tool |
| Common monitoring and error questions for Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/monitor-troubleshoot-faq |
| Troubleshoot Azure Managed Redis client-side issues | https://learn.microsoft.com/en-us/azure/redis/troubleshoot-client |
| Troubleshoot connectivity issues in Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/troubleshoot-connectivity |
| Diagnose and resolve data loss in Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/troubleshoot-data-loss |
| Troubleshoot Azure Managed Redis server-side issues | https://learn.microsoft.com/en-us/azure/redis/troubleshoot-server |
| Troubleshoot latency and timeouts in Azure Managed Redis | https://learn.microsoft.com/en-us/azure/redis/troubleshoot-timeouts |

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
