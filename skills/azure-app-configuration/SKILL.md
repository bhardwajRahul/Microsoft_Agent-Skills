---
name: azure-app-configuration
description: Expert knowledge for Azure App Configuration development including deployment, configuration, security, architecture & design patterns, limits & quotas, integrations & coding patterns, best practices, and troubleshooting. Use when building, debugging, or optimizing Azure App Configuration applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Azure App Configuration Skill

This skill provides expert guidance for Azure App Configuration development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Design resiliency and disaster recovery for Azure App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/concept-disaster-recovery |

### Best Practices
| Topic | URL |
|-------|-----|
| Apply Azure App Configuration usage best practices | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-best-practices |
| Ensure consistency using synchronization tokens in REST API | https://learn.microsoft.com/en-us/azure/azure-app-configuration/rest-api-consistency |

### Configuration
| Topic | URL |
|-------|-----|
| Use configuration files with Azure App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/concept-config-file |
| Configure and use snapshot references in App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/concept-snapshot-references |
| Enable dynamic configuration in Azure Functions with App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/enable-dynamic-configuration-azure-functions-csharp |
| Configure dynamic configuration in AKS using App Configuration Kubernetes Provider | https://learn.microsoft.com/en-us/azure/azure-app-configuration/enable-dynamic-configuration-azure-kubernetes-service |
| Configure dynamic configuration in Go Gin web apps with App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/enable-dynamic-configuration-gin-web-app |
| Use dynamic configuration in Go console apps with App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/enable-dynamic-configuration-go-console-app |
| Enable dynamic configuration in Spring Boot with App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/enable-dynamic-configuration-java-spring-app |
| Enable dynamic configuration in JavaScript with App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/enable-dynamic-configuration-javascript |
| Configure dynamic configuration refresh in Python with App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/enable-dynamic-configuration-python |
| Configure and interpret Azure App Configuration feature flag telemetry | https://learn.microsoft.com/en-us/azure/azure-app-configuration/feature-flag-telemetry-reference |
| Configure AI agents with Azure App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-ai-agent-config |
| Define chat completion settings in App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-chat-completion-config |
| Upgrade Spring Boot apps to Azure App Configuration library v6 | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-convert-to-the-new-spring-boot |
| Create and manage App Configuration snapshots | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-create-snapshots |
| Configure feature filters for conditional flags | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-feature-filters |
| Configure and manage geo-replication for App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-geo-replication |
| Configure JSON content-type for App Configuration key-values | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-leverage-json-content-type |
| Configure soft delete retention and recovery for App Configuration stores | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-recover-deleted-stores-in-azure-app-configuration |
| Configure targeting filters for staged rollouts | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-targetingfilter |
| Configure telemetry collection for Azure feature flags | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-telemetry |
| Configure time window filters for scheduled features | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-timewindow-filter |
| Configure and manage variant feature flags in App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-variant-feature-flags |
| Reference for Azure App Configuration monitoring data | https://learn.microsoft.com/en-us/azure/azure-app-configuration/monitor-app-configuration-reference |
| Configure Azure App Configuration Kubernetes Provider properties | https://learn.microsoft.com/en-us/azure/azure-app-configuration/reference-kubernetes-provider |
| Use and troubleshoot Azure App Configuration REST API versioning | https://learn.microsoft.com/en-us/azure/azure-app-configuration/rest-api-versioning |

### Deployment
| Topic | URL |
|-------|-----|
| Export App Configuration settings with Azure Pipelines | https://learn.microsoft.com/en-us/azure/azure-app-configuration/azure-pipeline-export-task |
| Import configuration into App Configuration via Azure Pipelines | https://learn.microsoft.com/en-us/azure/azure-app-configuration/azure-pipeline-import-task |
| Create App Configuration snapshots using Azure Pipelines | https://learn.microsoft.com/en-us/azure/azure-app-configuration/azure-pipeline-snapshot-task |
| Integrate Azure App Configuration into CI/CD pipelines | https://learn.microsoft.com/en-us/azure/azure-app-configuration/integrate-ci-cd-pipeline |
| Deploy App Configuration data to Kubernetes with Helm | https://learn.microsoft.com/en-us/azure/azure-app-configuration/integrate-kubernetes-deployment-helm |
| Sync GitHub configuration files to App Configuration via Actions | https://learn.microsoft.com/en-us/azure/azure-app-configuration/push-kv-github-action |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Enable dynamic configuration in Aspire using App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/enable-dynamic-configuration-aspire |
| Implement dynamic configuration in ASP.NET Core with App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/enable-dynamic-configuration-aspnet-core |
| Use dynamic Azure App Configuration in ASP.NET (.NET Framework) | https://learn.microsoft.com/en-us/azure/azure-app-configuration/enable-dynamic-configuration-aspnet-netfx |
| Implement dynamic configuration in .NET Framework using App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/enable-dynamic-configuration-dotnet |
| Enable dynamic configuration in .NET background services using App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/enable-dynamic-configuration-dotnet-background-service |
| Use dynamic configuration in .NET apps with App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/enable-dynamic-configuration-dotnet-core |
| Implement push-based dynamic configuration in .NET with App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/enable-dynamic-configuration-dotnet-core-push-refresh |
| Implement push-based dynamic configuration in Spring with App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/enable-dynamic-configuration-java-spring-push-refresh |
| Implement feature flags in .NET with Azure App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/feature-management-dotnet-reference |
| Implement feature flags in Go with Azure App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/feature-management-go-reference |
| Implement feature flags in JavaScript with Azure App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/feature-management-javascript-reference |
| Implement feature flags in Python with Azure App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/feature-management-python-reference |
| Load App Configuration via Azure Front Door in clients | https://learn.microsoft.com/en-us/azure/azure-app-configuration/how-to-load-azure-front-door-configuration-provider |
| Apply targeting filter in Python feature flags | https://learn.microsoft.com/en-us/azure/azure-app-configuration/how-to-targeting-filter-python |
| Integrate feature flag telemetry in ASP.NET Core | https://learn.microsoft.com/en-us/azure/azure-app-configuration/how-to-telemetry-aspnet-core |
| Use Agent Framework and App Configuration in Python | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-ai-agent-config-python |
| Configure App Configuration change events with Event Grid | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-app-configuration-event |
| Implement custom feature filters in ASP.NET Core | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-feature-filters-aspnet-core |
| Implement custom feature filters in Go Gin apps | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-feature-filters-go |
| Implement custom feature filters in Node.js | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-feature-filters-javascript |
| Implement custom feature filters in Python | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-feature-filters-python |
| Configure ASP.NET Core to use App Configuration labels | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-labels-aspnet-core |
| Use targeting filters in ASP.NET Core feature flags | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-targetingfilter-aspnet-core |
| Use targeting filter in Go Gin web apps | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-targetingfilter-go |
| Use targeting filter for Node.js feature rollouts | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-targetingfilter-javascript |
| Integrate feature flag telemetry in Node.js apps | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-telemetry-javascript |
| Integrate feature flag telemetry in Python apps | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-telemetry-python |
| Use time window filters in Python apps | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-time-window-filter-python |
| Use time window filters in ASP.NET Core apps | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-timewindow-filter-aspnet-core |
| Use time window filters in Go Gin apps | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-timewindow-filter-go |
| Use time window filters in Node.js apps | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-timewindow-filter-javascript |
| Use variant feature flags in ASP.NET Core apps | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-variant-feature-flags-aspnet-core |
| Use variant feature flags in Go Gin web apps | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-variant-feature-flags-go |
| Use variant feature flags in Node.js applications | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-variant-feature-flags-javascript |
| Use variant feature flags in Python applications | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-variant-feature-flags-python |
| Integrate Azure App Configuration with .NET Aspire solutions | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-aspire |
| Integrate Azure App Configuration with ASP.NET Core | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-aspnet-core-app |
| Integrate Azure App Configuration with Azure Functions in C# | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-azure-functions-csharp |
| Use Azure App Configuration Kubernetes Provider with AKS | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-azure-kubernetes-service |
| Integrate Azure App Configuration with .NET Framework apps | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-dotnet-app |
| Integrate Azure App Configuration with .NET console apps | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-dotnet-core-app |
| Add Azure App Configuration feature flags to Aspire apps | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-feature-flag-aspire |
| Use Azure App Configuration feature flags in ASP.NET Core | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-feature-flag-aspnet-core |
| Use Azure App Configuration feature flags in Azure Functions | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-feature-flag-azure-functions-csharp |
| Implement Azure App Configuration feature flags in .NET apps | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-feature-flag-dotnet |
| Add Azure App Configuration feature flags to .NET background services | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-feature-flag-dotnet-background-service |
| Implement Azure App Configuration feature flags in Go console apps | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-feature-flag-go-console |
| Add Azure App Configuration feature flags to Go Gin web apps | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-feature-flag-go-gin |
| Add Azure App Configuration feature flags to JavaScript apps | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-feature-flag-javascript |
| Implement Azure App Configuration feature flags in Python | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-feature-flag-python |
| Add Azure App Configuration feature flags to Spring Boot | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-feature-flag-spring-boot |
| Integrate Azure App Configuration with Go console apps | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-go-console-app |
| Use Azure App Configuration in Go Gin web apps | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-go-web-app |
| Integrate Azure App Configuration with Java Spring | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-java-spring-app |
| Use Azure App Configuration from JavaScript with SDK | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-javascript |
| Use Azure App Configuration JavaScript provider in Node.js | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-javascript-provider |
| Use Azure App Configuration from Python with SDK | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-python |
| Use Azure App Configuration in Python apps | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-python-provider |
| Integrate Azure App Configuration with .NET configuration provider | https://learn.microsoft.com/en-us/azure/azure-app-configuration/reference-dotnet-provider |
| Integrate Azure App Configuration with Go configuration provider | https://learn.microsoft.com/en-us/azure/azure-app-configuration/reference-go-provider |
| Integrate Azure App Configuration with JavaScript configuration provider | https://learn.microsoft.com/en-us/azure/azure-app-configuration/reference-javascript-provider |
| Integrate Azure App Configuration with Python configuration provider | https://learn.microsoft.com/en-us/azure/azure-app-configuration/reference-python-provider |
| Automatically reload Key Vault secrets via App Configuration in .NET | https://learn.microsoft.com/en-us/azure/azure-app-configuration/reload-key-vault-secrets-dotnet |
| Call Azure App Configuration using REST API | https://learn.microsoft.com/en-us/azure/azure-app-configuration/rest-api |
| Use required HTTP headers with App Configuration REST | https://learn.microsoft.com/en-us/azure/azure-app-configuration/rest-api-headers |
| Work with key-values in App Configuration REST API | https://learn.microsoft.com/en-us/azure/azure-app-configuration/rest-api-key-value |
| Manage Azure App Configuration keys via REST | https://learn.microsoft.com/en-us/azure/azure-app-configuration/rest-api-keys |
| Use label resources in App Configuration REST API | https://learn.microsoft.com/en-us/azure/azure-app-configuration/rest-api-labels |
| Lock and unlock key-values via App Configuration REST | https://learn.microsoft.com/en-us/azure/azure-app-configuration/rest-api-locks |
| Manage App Configuration snapshots via REST API | https://learn.microsoft.com/en-us/azure/azure-app-configuration/rest-api-snapshot |
| Integrate ASP.NET Core with App Configuration Key Vault references | https://learn.microsoft.com/en-us/azure/azure-app-configuration/use-key-vault-references-dotnet-core |
| Use App Configuration Key Vault references in Spring Boot | https://learn.microsoft.com/en-us/azure/azure-app-configuration/use-key-vault-references-spring-boot |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Use point-in-time key-value retrieval with tier limits | https://learn.microsoft.com/en-us/azure/azure-app-configuration/concept-point-time-snapshot |
| Understand lifecycle limits for App Configuration preview APIs | https://learn.microsoft.com/en-us/azure/azure-app-configuration/concept-preview-api-life-cycle |
| Understand soft delete behavior and retention for App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/concept-soft-delete |
| Understand key-value revision retention limits by tier | https://learn.microsoft.com/en-us/azure/azure-app-configuration/rest-api-revisions |
| Handle App Configuration REST throttling and quotas | https://learn.microsoft.com/en-us/azure/azure-app-configuration/rest-api-throttling |

### Security
| Topic | URL |
|-------|-----|
| Use customer-managed keys to encrypt App Configuration data | https://learn.microsoft.com/en-us/azure/azure-app-configuration/concept-customer-managed-keys |
| Configure Entra ID and RBAC for Azure App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/concept-enable-rbac |
| Secure Azure App Configuration with private endpoints | https://learn.microsoft.com/en-us/azure/azure-app-configuration/concept-private-endpoint |
| Securely connect App Configuration to Azure Front Door | https://learn.microsoft.com/en-us/azure/azure-app-configuration/how-to-connect-azure-front-door |
| Manage access key authentication for Azure App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-disable-access-key-authentication |
| Disable public network access for Azure App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-disable-public-access |
| Use managed identities to access Azure App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-integrate-azure-managed-service-identity |
| Set up private access to an Azure App Configuration store | https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-set-up-private-access |
| Configure managed identities for Azure App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/overview-managed-identity |
| Apply built-in Azure Policy definitions for App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/policy-reference |
| Configure roles and permissions for App Configuration deployments | https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-deployment-overview |
| Use Microsoft Entra ID to secure App Configuration REST | https://learn.microsoft.com/en-us/azure/azure-app-configuration/rest-api-authentication-azure-ad |
| Configure HMAC-SHA256 authentication for App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/rest-api-authentication-hmac |
| Authenticate Azure App Configuration REST requests | https://learn.microsoft.com/en-us/azure/azure-app-configuration/rest-api-authentication-index |
| Use RBAC with Entra ID for App Configuration REST | https://learn.microsoft.com/en-us/azure/azure-app-configuration/rest-api-authorization-azure-ad |
| Authorize App Configuration REST access with HMAC keys | https://learn.microsoft.com/en-us/azure/azure-app-configuration/rest-api-authorization-hmac |
| Understand authorization models for App Configuration REST | https://learn.microsoft.com/en-us/azure/azure-app-configuration/rest-api-authorization-index |
| Azure Policy compliance controls for Azure App Configuration | https://learn.microsoft.com/en-us/azure/azure-app-configuration/security-controls-policy |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot Azure App Configuration network access errors | https://learn.microsoft.com/en-us/azure/azure-app-configuration/network-access-errors |

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
