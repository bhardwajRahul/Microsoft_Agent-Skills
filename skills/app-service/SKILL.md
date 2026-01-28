---
name: app-service
description: Expert knowledge for App Service development including best practices, configuration, limits & quotas, integrations & coding patterns, security, architecture & design patterns, deployment, comparing x vs. y, and troubleshooting. Use when building, debugging, or optimizing App Service applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# App Service Skill

This skill provides expert guidance for App Service development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Use gateway-required VNet integration with App Service | https://learn.microsoft.com/en-us/azure/app-service/configure-gateway-required-vnet-integration |
| Design geo-distributed scale with ASE and Traffic Manager | https://learn.microsoft.com/en-us/azure/app-service/environment/app-service-app-service-environment-geo-distributed-scale |
| Migrate Docker Compose multi-container apps to sidecars | https://learn.microsoft.com/en-us/azure/app-service/migrate-sidecar-multi-container-apps |
| Choose Azure App Service networking features | https://learn.microsoft.com/en-us/azure/app-service/networking-features |
| Use Azure NAT Gateway with App Service outbound traffic | https://learn.microsoft.com/en-us/azure/app-service/overview-nat-gateway-integration |
| Plan and use App Service VNet integration | https://learn.microsoft.com/en-us/azure/app-service/overview-vnet-integration |
| Apply recommended companion services for App Service apps | https://learn.microsoft.com/en-us/azure/app-service/recommended-services |
| Choose secure connectivity patterns for App Service to Azure resources | https://learn.microsoft.com/en-us/azure/app-service/tutorial-connect-overview |

### Best Practices
| Topic | URL |
|-------|-----|
| Apply best practices and troubleshooting for Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/app-service-best-practices |
| Apply deployment best practices for Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/deploy-best-practices |
| Choose authentication options for App Service apps | https://learn.microsoft.com/en-us/azure/app-service/identity-scenarios |
| Apply security best practices to Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/overview-security |
| Apply Traffic Manager best practices for App Service | https://learn.microsoft.com/en-us/azure/app-service/web-sites-traffic-manager |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Compare ASE v3 vs public multitenant App Service | https://learn.microsoft.com/en-us/azure/app-service/environment/ase-multi-tenant-comparison |

### Configuration
| Topic | URL |
|-------|-----|
| Use Azure App Configuration references in App Service | https://learn.microsoft.com/en-us/azure/app-service/app-service-configuration-references |
| Manage and scale Azure App Service plans | https://learn.microsoft.com/en-us/azure/app-service/app-service-plan-manage |
| Restore deleted Azure App Service apps | https://learn.microsoft.com/en-us/azure/app-service/app-service-undelete |
| Map an existing custom DNS name to App Service | https://learn.microsoft.com/en-us/azure/app-service/app-service-web-tutorial-custom-domain |
| Configure App Service authentication API versions | https://learn.microsoft.com/en-us/azure/app-service/configure-authentication-api-version |
| Use file-based configuration for App Service auth | https://learn.microsoft.com/en-us/azure/app-service/configure-authentication-file-based |
| Configure common settings for Azure App Service apps | https://learn.microsoft.com/en-us/azure/app-service/configure-common |
| Mount Azure Files shares in App Service apps | https://learn.microsoft.com/en-us/azure/app-service/configure-connect-to-azure-storage |
| Configure custom containers on Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/configure-custom-container |
| Configure Traffic Manager with custom domains for App Service | https://learn.microsoft.com/en-us/azure/app-service/configure-domain-traffic-manager |
| Configure gRPC and HTTP/2 for Linux App Service apps | https://learn.microsoft.com/en-us/azure/app-service/configure-grpc |
| Configure ASP.NET apps on Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/configure-language-dotnet-framework |
| Configure ASP.NET Core apps on Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/configure-language-dotnetcore |
| Configure APM for Java apps on Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/configure-language-java-apm |
| Configure Java data sources on Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/configure-language-java-data-sources |
| Configure Java runtimes and logging on Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/configure-language-java-deploy-run |
| Configure Node.js applications on Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/configure-language-nodejs |
| Configure PHP apps on Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/configure-language-php |
| Configure Python apps on Azure App Service for Linux | https://learn.microsoft.com/en-us/azure/app-service/configure-language-python |
| Configure SSH access for App Service containers | https://learn.microsoft.com/en-us/azure/app-service/configure-linux-open-ssh-session |
| Configure Managed Instance for Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/configure-managed-instance |
| Enable and configure sidecars in Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/configure-sidecar |
| Enable VNet integration for Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/configure-vnet-integration-enable |
| Configure routing for App Service VNet integration | https://learn.microsoft.com/en-us/azure/app-service/configure-vnet-integration-routing |
| Configure App Service deployment credentials | https://learn.microsoft.com/en-us/azure/app-service/deploy-configure-credentials |
| Configure Run-From-Package for Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/deploy-run-package |
| Configure ASE-wide custom settings via clusterSettings | https://learn.microsoft.com/en-us/azure/app-service/environment/app-service-app-service-environment-custom-settings |
| Configure network customizations for App Service Environment v3 | https://learn.microsoft.com/en-us/azure/app-service/environment/configure-network-settings |
| Configure custom domain suffix for internal ASE | https://learn.microsoft.com/en-us/azure/app-service/environment/how-to-custom-domain-suffix |
| Configure upgrade preference for ASE planned maintenance | https://learn.microsoft.com/en-us/azure/app-service/environment/how-to-upgrade-preference |
| Configure networking for Azure App Service Environment | https://learn.microsoft.com/en-us/azure/app-service/environment/networking |
| Configure automatic scaling for Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/manage-automatic-scaling |
| Configure and restore Azure App Service backups | https://learn.microsoft.com/en-us/azure/app-service/manage-backup |
| Buy and configure App Service-managed custom domains | https://learn.microsoft.com/en-us/azure/app-service/manage-custom-dns-buy-domain |
| Migrate an active DNS domain to Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/manage-custom-dns-migrate-domain |
| Enable per-app scaling in Azure App Service plans | https://learn.microsoft.com/en-us/azure/app-service/manage-scale-per-app |
| Reference for Azure App Service monitoring data | https://learn.microsoft.com/en-us/azure/app-service/monitor-app-service-reference |
| Configure App Service health check endpoint monitoring | https://learn.microsoft.com/en-us/azure/app-service/monitor-instances-health-check |
| Understand OS-level capabilities for Windows apps on App Service | https://learn.microsoft.com/en-us/azure/app-service/operating-system-functionality |
| Configure Entra agent identity for App Service | https://learn.microsoft.com/en-us/azure/app-service/overview-agent-identity |
| Configure and manage App Service local cache | https://learn.microsoft.com/en-us/azure/app-service/overview-local-cache |
| Configure managed identities for Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/overview-managed-identity |
| Configure DNS and name resolution for Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/overview-name-resolution |
| Configure and override App Service environment variables | https://learn.microsoft.com/en-us/azure/app-service/reference-app-settings |
| Configure and override App Service environment variables | https://learn.microsoft.com/en-us/azure/app-service/reference-app-settings |
| Enable and access App Service diagnostic logs | https://learn.microsoft.com/en-us/azure/app-service/troubleshoot-diagnostic-logs |
| Configure sidecar containers for custom Linux apps | https://learn.microsoft.com/en-us/azure/app-service/tutorial-custom-container-sidecar |
| Configure custom domain and managed certificate in App Service | https://learn.microsoft.com/en-us/azure/app-service/tutorial-secure-domain-certificate |
| Configure and run WebJobs background tasks in App Service | https://learn.microsoft.com/en-us/azure/app-service/webjobs-create |
| Understand and configure WebJobs execution behavior | https://learn.microsoft.com/en-us/azure/app-service/webjobs-execution |

### Deployment
| Topic | URL |
|-------|-----|
| Select App Service deployment authentication types | https://learn.microsoft.com/en-us/azure/app-service/deploy-authentication-types |
| Set up CI/CD to custom containers in App Service | https://learn.microsoft.com/en-us/azure/app-service/deploy-ci-cd-custom-container |
| Deploy Windows containers to App Service with Azure Pipelines | https://learn.microsoft.com/en-us/azure/app-service/deploy-container-azure-pipelines |
| Deploy custom Linux containers via GitHub Actions | https://learn.microsoft.com/en-us/azure/app-service/deploy-container-github-action |
| Use App Service deployment slots for staging | https://learn.microsoft.com/en-us/azure/app-service/deploy-staging-slots |
| Configure zone redundancy for ASE and Isolated v2 plans | https://learn.microsoft.com/en-us/azure/app-service/environment/configure-zone-redundancy-environment |
| Deploy App Service Environment v3 using ARM templates | https://learn.microsoft.com/en-us/azure/app-service/environment/how-to-create-from-template |
| Set up App Service, Functions, and Logic Apps on Azure Arc | https://learn.microsoft.com/en-us/azure/app-service/manage-create-arc-environment |
| Migrate App Service on Arc to Container Apps on Arc | https://learn.microsoft.com/en-us/azure/app-service/migrate-app-service-arc |
| Migrate App Service from gateway to regional VNet integration | https://learn.microsoft.com/en-us/azure/app-service/migrate-gateway-based-vnet-integration |
| Deploy Managed Instance on Azure App Service (preview constraints) | https://learn.microsoft.com/en-us/azure/app-service/quickstart-managed-instance |
| Use Kudu engine features for App Service deployments | https://learn.microsoft.com/en-us/azure/app-service/resources-kudu |
| Develop and deploy Azure WebJobs with Visual Studio | https://learn.microsoft.com/en-us/azure/app-service/webjobs-dotnet-deploy-vs |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Use Hybrid Connections from App Service to private resources | https://learn.microsoft.com/en-us/azure/app-service/app-service-hybrid-connections |
| Integrate ILB App Service Environment with Application Gateway | https://learn.microsoft.com/en-us/azure/app-service/environment/integrate-with-application-gateway |
| Integrate Azure OpenAI with .NET Blazor on App Service | https://learn.microsoft.com/en-us/azure/app-service/tutorial-ai-openai-chatbot-dotnet |
| Access Azure databases from App Service with MSI | https://learn.microsoft.com/en-us/azure/app-service/tutorial-connect-msi-azure-database |
| Use Key Vault and managed identity from .NET App Service apps | https://learn.microsoft.com/en-us/azure/app-service/tutorial-connect-msi-key-vault |
| Use Key Vault from App Service JavaScript with MSI | https://learn.microsoft.com/en-us/azure/app-service/tutorial-connect-msi-key-vault-javascript |
| Use Key Vault from App Service PHP with MSI | https://learn.microsoft.com/en-us/azure/app-service/tutorial-connect-msi-key-vault-php |
| Use Key Vault from App Service Python with MSI | https://learn.microsoft.com/en-us/azure/app-service/tutorial-connect-msi-key-vault-python |
| Integrate App Service apps with Logic Apps to send email | https://learn.microsoft.com/en-us/azure/app-service/tutorial-send-email |
| Build and deploy Azure WebJobs SDK queue processor | https://learn.microsoft.com/en-us/azure/app-service/webjobs-sdk-get-started |
| Author Azure WebJobs SDK functions and bindings | https://learn.microsoft.com/en-us/azure/app-service/webjobs-sdk-how-to |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Configure and use App Service Premium v3 tier | https://learn.microsoft.com/en-us/azure/app-service/app-service-configure-premium-v3-tier |
| Configure and use App Service Premium v4 tier | https://learn.microsoft.com/en-us/azure/app-service/app-service-configure-premium-v4-tier |
| Understand Azure App Service plan capabilities and limits | https://learn.microsoft.com/en-us/azure/app-service/overview-hosting-plans |
| Manage inbound and outbound IPs for App Service | https://learn.microsoft.com/en-us/azure/app-service/overview-inbound-outbound-ips |
| View and understand App Service quotas and metrics | https://learn.microsoft.com/en-us/azure/app-service/web-sites-monitor |

### Security
| Topic | URL |
|-------|-----|
| Configure App Service IP access restrictions | https://learn.microsoft.com/en-us/azure/app-service/app-service-ip-restrictions |
| Use Azure Key Vault references in App Service app settings | https://learn.microsoft.com/en-us/azure/app-service/app-service-key-vault-references |
| Handle 2025 changes to App Service managed certificates | https://learn.microsoft.com/en-us/azure/app-service/app-service-managed-certificate-changes-july-2025 |
| Configure TLS mutual authentication for Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/app-service-web-configure-tls-mutual-auth |
| Secure Foundry OpenAPI tools with App Service auth | https://learn.microsoft.com/en-us/azure/app-service/configure-authentication-ai-foundry-openapi-tool |
| Customize App Service authentication sign-in and sign-out | https://learn.microsoft.com/en-us/azure/app-service/configure-authentication-customize-sign-in-out |
| Configure MCP server authorization in App Service | https://learn.microsoft.com/en-us/azure/app-service/configure-authentication-mcp |
| Secure MCP servers for VS Code with Entra auth | https://learn.microsoft.com/en-us/azure/app-service/configure-authentication-mcp-server-vscode |
| Manage OAuth tokens with App Service authentication | https://learn.microsoft.com/en-us/azure/app-service/configure-authentication-oauth-tokens |
| Configure Microsoft Entra authentication for App Service | https://learn.microsoft.com/en-us/azure/app-service/configure-authentication-provider-aad |
| Set up Sign in with Apple for App Service | https://learn.microsoft.com/en-us/azure/app-service/configure-authentication-provider-apple |
| Configure Facebook authentication for App Service apps | https://learn.microsoft.com/en-us/azure/app-service/configure-authentication-provider-facebook |
| Configure GitHub authentication for App Service apps | https://learn.microsoft.com/en-us/azure/app-service/configure-authentication-provider-github |
| Configure Google authentication for App Service apps | https://learn.microsoft.com/en-us/azure/app-service/configure-authentication-provider-google |
| Configure custom OpenID Connect auth for App Service | https://learn.microsoft.com/en-us/azure/app-service/configure-authentication-provider-openid-connect |
| Configure X (Twitter) authentication for App Service apps | https://learn.microsoft.com/en-us/azure/app-service/configure-authentication-provider-twitter |
| Access and use user identities in App Service auth | https://learn.microsoft.com/en-us/azure/app-service/configure-authentication-user-identities |
| Disable basic auth for App Service deployments | https://learn.microsoft.com/en-us/azure/app-service/configure-basic-auth-disable |
| Encrypt App Service app source at rest with CMK | https://learn.microsoft.com/en-us/azure/app-service/configure-encrypt-at-rest-using-cmk |
| Configure security for Java apps on Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/configure-language-java-security |
| Purchase and manage Azure App Service certificates | https://learn.microsoft.com/en-us/azure/app-service/configure-ssl-app-service-certificate |
| Bind TLS/SSL certificates to secure App Service custom domains | https://learn.microsoft.com/en-us/azure/app-service/configure-ssl-bindings |
| Add and manage TLS/SSL certificates in Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/configure-ssl-certificate |
| Access and use TLS/SSL certificates in App Service code | https://learn.microsoft.com/en-us/azure/app-service/configure-ssl-certificate-in-code |
| Manage certificates and bindings in App Service Environment | https://learn.microsoft.com/en-us/azure/app-service/environment/overview-certificates |
| Control App Service outbound traffic with Azure Firewall | https://learn.microsoft.com/en-us/azure/app-service/network-secure-outbound-traffic-azure-firewall |
| Secure App Service with access restrictions | https://learn.microsoft.com/en-us/azure/app-service/overview-access-restrictions |
| Integrate Application Gateway securely with App Service | https://learn.microsoft.com/en-us/azure/app-service/overview-app-gateway-integration |
| Secure App Service apps with private endpoints | https://learn.microsoft.com/en-us/azure/app-service/overview-private-endpoint |
| Understand TLS/SSL support and configuration in App Service | https://learn.microsoft.com/en-us/azure/app-service/overview-tls |
| Apply built-in Azure Policy definitions for App Service | https://learn.microsoft.com/en-us/azure/app-service/policy-reference |
| Prevent dangling subdomain takeovers in App Service | https://learn.microsoft.com/en-us/azure/app-service/reference-dangling-subdomain-prevention |
| Configure App Service managed identity to call Microsoft Graph | https://learn.microsoft.com/en-us/azure/app-service/scenario-secure-app-access-microsoft-graph-as-app |
| Access Microsoft Graph as user from App Service | https://learn.microsoft.com/en-us/azure/app-service/scenario-secure-app-access-microsoft-graph-as-user |
| Access Azure Storage from App Service using managed identity | https://learn.microsoft.com/en-us/azure/app-service/scenario-secure-app-access-storage |
| Enable app authentication for an App Service web app | https://learn.microsoft.com/en-us/azure/app-service/scenario-secure-app-authentication-app-service |
| Use Azure Policy compliance controls for App Service | https://learn.microsoft.com/en-us/azure/app-service/security-controls-policy |
| Secure App Service apps with built-in authentication | https://learn.microsoft.com/en-us/azure/app-service/tutorial-auth-aad |
| Secure JavaScript web app access to Microsoft Graph with managed identity | https://learn.microsoft.com/en-us/azure/app-service/tutorial-connect-app-access-microsoft-graph-as-app-javascript |
| Configure JavaScript web app to access Microsoft Graph as user | https://learn.microsoft.com/en-us/azure/app-service/tutorial-connect-app-access-microsoft-graph-as-user-javascript |
| Connect App Service to Azure SQL on behalf of user | https://learn.microsoft.com/en-us/azure/app-service/tutorial-connect-app-access-sql-database-as-user-dotnet |
| Access Azure Storage from JavaScript web app using managed identity | https://learn.microsoft.com/en-us/azure/app-service/tutorial-connect-app-access-storage-javascript |
| Propagate user auth from App Service to Azure APIs | https://learn.microsoft.com/en-us/azure/app-service/tutorial-connect-app-app-graph-javascript |
| Use managed identity to access Azure SQL from App Service | https://learn.microsoft.com/en-us/azure/app-service/tutorial-connect-msi-sql-database |
| Secure Java data access with managed identity on App Service | https://learn.microsoft.com/en-us/azure/app-service/tutorial-java-tomcat-connect-managed-identity-postgresql-database |
| Isolate App Service back-end traffic with VNet integration | https://learn.microsoft.com/en-us/azure/app-service/tutorial-networking-isolate-vnet |
| Deploy a secure N-tier web app on App Service | https://learn.microsoft.com/en-us/azure/app-service/tutorial-secure-ntier-app |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Use App Service diagnostics to troubleshoot apps | https://learn.microsoft.com/en-us/azure/app-service/overview-diagnostics |
| Troubleshoot App Service issues with Azure Monitor | https://learn.microsoft.com/en-us/azure/app-service/tutorial-troubleshoot-monitor |

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
