---
name: container-apps
description: Expert knowledge for Container Apps development including security, deployment, configuration, architecture & design patterns, comparing x vs. y, best practices, integrations & coding patterns, troubleshooting, and limits & quotas. Use when building, debugging, or optimizing Container Apps applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Container Apps Skill

This skill provides expert guidance for Container Apps development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Implement blue-green deployment with Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/blue-green-deployment |
| Design and scope Azure Container Apps environments | https://learn.microsoft.com/en-us/azure/container-apps/environment |
| Architect Azure Functions workloads on Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/functions-overview |
| Design a highly available Eureka Server cluster on Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/java-eureka-server-highly-available |

### Best Practices
| Topic | URL |
|-------|-----|
| Apply cold-start reduction best practices in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/cold-start |
| Optimize Java memory usage with automatic memory fitting in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/java-memory-fit |
| Apply security best practices to Azure Container Apps deployments | https://learn.microsoft.com/en-us/azure/container-apps/secure-deployment |
| Use storage mounts correctly in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/storage-mounts |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Choose code-to-cloud deployment options for Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/code-to-cloud-options |
| Choose between Azure container hosting options | https://learn.microsoft.com/en-us/azure/container-apps/compare-options |
| Compare Nvidia GPU options in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/gpu-types |

### Configuration
| Topic | URL |
|-------|-----|
| Configure Azure Container Apps with ARM and YAML templates | https://learn.microsoft.com/en-us/azure/container-apps/azure-resource-manager-api-spec |
| Configure containers and jobs in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/containers |
| Configure CORS settings for Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/cors |
| Configure virtual network integration for Azure Container Apps environments | https://learn.microsoft.com/en-us/azure/container-apps/custom-virtual-networks |
| Create Dapr components via Azure Container Apps portal | https://learn.microsoft.com/en-us/azure/container-apps/dapr-component-connection |
| Configure Dapr component resiliency in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/dapr-component-resiliency |
| Configure Dapr components in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/dapr-components |
| Configure Dapr settings on Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/enable-dapr |
| Map Azure Functions triggers to KEDA scaling settings | https://learn.microsoft.com/en-us/azure/container-apps/functions-keda-mappings |
| Configure environment-level ingress for Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/ingress-environment-configuration |
| Configure app-level ingress in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/ingress-how-to |
| Configure managed Admin for Spring in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/java-admin |
| Integrate Admin for Spring with Eureka Server in Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/java-admin-eureka-integration |
| Configure APM Java agent with init containers in Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/java-application-performance-management-config |
| Configure Java build environment variables in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/java-build-environment-variables |
| Access logs for managed Java components in Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/java-component-logs |
| Connect Config Server for Spring to Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/java-config-server |
| Configure managed Eureka Server for Spring in Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/java-eureka-server |
| Enable Java-optimized features in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/java-feature-switch |
| Configure Gateway for Spring with Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/java-gateway-for-spring |
| Enable and configure Java metrics in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/java-metrics |
| Scale Azure Container Apps using Java metrics with KEDA | https://learn.microsoft.com/en-us/azure/container-apps/java-metrics-scale-with-keda |
| Build Java metrics dashboards with Azure Managed Grafana | https://learn.microsoft.com/en-us/azure/container-apps/java-metrics-with-grafana |
| Configure Log Analytics monitoring for Azure Container Apps logs | https://learn.microsoft.com/en-us/azure/container-apps/log-monitoring |
| Configure log storage destinations for Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/log-options |
| Configure planned maintenance windows for Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/planned-maintenance |
| Configure premium ingress scaling and settings for Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/premium-ingress |
| Configure and manage revisions in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/revisions |
| Configure rule-based HTTP routing for Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/rule-based-routing |
| Use custom domains with rule-based routing in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/rule-based-routing-custom-domain |
| Configure service discovery resiliency policies in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/service-discovery-resiliency |
| Configure session pools for Azure Container Apps sessions | https://learn.microsoft.com/en-us/azure/container-apps/session-pool |
| Run serverless code interpreter sessions in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/sessions-code-interpreter |
| Run custom container-based dynamic sessions in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/sessions-custom-container |
| Configure and manage dynamic sessions in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/sessions-usage |
| Configure session affinity (sticky sessions) for Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/sticky-sessions |
| Configure traffic splitting between revisions in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/traffic-splitting |
| Create Azure Container Apps environment in an existing virtual network | https://learn.microsoft.com/en-us/azure/container-apps/vnet-custom |
| Manage workload profiles via Azure CLI for Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/workload-profiles-manage-cli |
| Manage workload profiles in Azure portal for Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/workload-profiles-manage-portal |

### Deployment
| Topic | URL |
|-------|-----|
| Set up Azure Pipelines to publish Container Apps revisions | https://learn.microsoft.com/en-us/azure/container-apps/azure-pipelines |
| Scale Dapr apps with KEDA in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/dapr-keda-scaling |
| Use GitHub Actions to publish Container Apps revisions | https://learn.microsoft.com/en-us/azure/container-apps/github-actions |
| Generate Container Apps GitHub Actions workflows with Azure CLI | https://learn.microsoft.com/en-us/azure/container-apps/github-actions-cli |
| Create zone-redundant Azure Container Apps in a virtual network | https://learn.microsoft.com/en-us/azure/container-apps/how-to-zone-redundancy |
| Compare Azure Container Apps plan types for deployment | https://learn.microsoft.com/en-us/azure/container-apps/plans |
| Run self-hosted CI/CD runners using Container Apps jobs | https://learn.microsoft.com/en-us/azure/container-apps/tutorial-ci-cd-runners-jobs |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Implement microservice-to-microservice calls in Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/communicate-between-microservices |
| Deploy Docker Compose agents to Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/compose-agent |
| Configure inter-app communication in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/connect-apps |
| Use Dapr extension with Azure Functions in Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/dapr-functions-extension |
| Deploy Azure Functions in custom containers on Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/functions-container-apps |
| Integrate Azure Front Door with Azure Container Apps via private link | https://learn.microsoft.com/en-us/azure/container-apps/how-to-integrate-with-azure-front-door |
| Integrate OpenTelemetry agents with Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/opentelemetry-agents |
| Connect Container Apps to Azure services with Service Connector | https://learn.microsoft.com/en-us/azure/container-apps/service-connector |
| Integrate AutoGen code interpreter sessions with Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/sessions-tutorial-autogen |
| Use Azure Container Apps sessions with LangChain code interpreter | https://learn.microsoft.com/en-us/azure/container-apps/sessions-tutorial-langchain |
| Integrate LlamaIndex with Azure Container Apps code interpreter sessions | https://learn.microsoft.com/en-us/azure/container-apps/sessions-tutorial-llamaindex |
| Execute JavaScript via Azure Container Apps dynamic sessions API | https://learn.microsoft.com/en-us/azure/container-apps/sessions-tutorial-nodejs |
| Use MCP server with Python code interpreter sessions in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/sessions-tutorial-python-mcp |
| Connect Semantic Kernel to Azure Container Apps code interpreter sessions | https://learn.microsoft.com/en-us/azure/container-apps/sessions-tutorial-semantic-kernel |
| Run shell commands using Azure Container Apps session pools | https://learn.microsoft.com/en-us/azure/container-apps/sessions-tutorial-shell |
| Use MCP server with shell sessions in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/sessions-tutorial-shell-mcp |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Review Azure Container Apps quota values and scopes | https://learn.microsoft.com/en-us/azure/container-apps/quotas |

### Security
| Topic | URL |
|-------|-----|
| Configure built-in authentication for Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/authentication |
| Enable Microsoft Entra authentication in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/authentication-entra |
| Configure Facebook authentication for Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/authentication-facebook |
| Configure GitHub authentication for Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/authentication-github |
| Configure Google authentication for Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/authentication-google |
| Use custom OpenID Connect providers with Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/authentication-openid |
| Configure X (Twitter) authentication for Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/authentication-twitter |
| Set up client certificate authentication for Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/client-certificate-authorization |
| Manage custom domains and TLS certificates in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/custom-domains-certificates |
| Configure custom domains and managed certificates for Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/custom-domains-managed-certificates |
| Enable Dapr token authentication in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/dapr-authentication-token |
| Secure Dapr component connections to Azure and third-party services | https://learn.microsoft.com/en-us/azure/container-apps/dapr-component-connect-services |
| Configure custom environment DNS suffix and TLS for Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/environment-custom-dns-suffix |
| Harden Azure Container Apps VNets with NSGs and firewall rules | https://learn.microsoft.com/en-us/azure/container-apps/firewall-integration |
| Securely access Azure Container Apps with private endpoints | https://learn.microsoft.com/en-us/azure/container-apps/how-to-use-private-endpoint |
| Configure IP ingress restrictions for Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/ip-restrictions |
| Import and manage TLS certificates from Key Vault for Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/key-vault-certificates-manage |
| Manage and use secrets in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/manage-secrets |
| Use managed identities with Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/managed-identity |
| Pull images from ACR using managed identity in Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/managed-identity-image-pull |
| Configure mutual TLS (mTLS) for Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/mtls |
| Apply built-in Azure Policy definitions to Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/policy-reference |
| Configure private endpoints and DNS for Azure Container Apps environments | https://learn.microsoft.com/en-us/azure/container-apps/private-endpoints-with-dns |
| Enable and configure token store for Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/token-store |
| Use managed identity from Container Apps to access PostgreSQL | https://learn.microsoft.com/en-us/azure/container-apps/tutorial-java-quarkus-connect-managed-identity-postgresql-database |
| Secure Azure Container Apps outbound traffic with Azure Firewall | https://learn.microsoft.com/en-us/azure/container-apps/use-azure-firewall |
| Control Azure Container Apps outbound traffic using user-defined routes and Azure Firewall | https://learn.microsoft.com/en-us/azure/container-apps/user-defined-routes |
| Protect Azure Container Apps with Application Gateway WAF | https://learn.microsoft.com/en-us/azure/container-apps/waf-app-gateway |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Use container debug console to troubleshoot Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/container-debug-console |
| Use dynamic log levels to troubleshoot Java apps in Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/java-dynamic-log-level |
| Diagnose container create and exit failures in Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/troubleshoot-container-create-failures |
| Diagnose container start failures in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/troubleshoot-container-start-failures |
| Fix health probe failures in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/troubleshoot-health-probe-failures |
| Troubleshoot image pull failures in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/troubleshoot-image-pull-failures |
| Resolve OCI runtime errors in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/troubleshoot-open-container-initiative-errors |
| Resolve storage mount failures in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/troubleshoot-storage-mount-failures |
| Fix target port misconfigurations in Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/troubleshoot-target-port-settings |
| Troubleshoot Azure Container Apps using logs and config | https://learn.microsoft.com/en-us/azure/container-apps/troubleshooting |

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
