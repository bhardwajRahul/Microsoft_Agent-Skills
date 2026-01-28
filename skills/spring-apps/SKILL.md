---
name: spring-apps
description: Expert knowledge for Spring Apps development including configuration, best practices, limits & quotas, security, architecture & design patterns, integrations & coding patterns, troubleshooting, deployment, and comparing x vs. y. Use when building, debugging, or optimizing Spring Apps applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Spring Apps Skill

This skill provides expert guidance for Spring Apps development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Design zero-downtime deployments on Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/concept-zero-downtime-deployment |
| Apply blue-green deployment strategies in Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/concepts-blue-green-deployment-strategies |
| Choose Azure load balancer options for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-integrate-azure-load-balancers |

### Best Practices
| Topic | URL |
|-------|-----|
| Optimize observability for production workloads on Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/application-observability |
| Configure JVM diagnostic options on Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-dump-jvm-options |
| Monitor Azure Spring Apps with logs, metrics, and tracing | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/quickstart-logs-metrics-tracing |
| Monitor Azure Spring Apps Enterprise with Application Live View | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/monitor-apps-by-application-live-view |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Compare Azure Spring Apps Basic, Standard, Enterprise plans | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/plan-comparison |

### Configuration
| Topic | URL |
|-------|-----|
| Configure private network access to Azure Spring Apps apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/access-app-virtual-network |
| Handle Azure Spring Apps API breaking changes | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/breaking-changes |
| Configure user-defined routes for Azure Spring Apps egress | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/concept-outbound-type |
| Configure diagnostics logs and metrics for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/diagnostic-services |
| Configure end-to-end TLS with Application Gateway for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/expose-apps-gateway-end-to-end-tls |
| Configure managed Spring Cloud Config Server in Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-config-server |
| Configure health probes and graceful termination in Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-configure-health-probes-graceful-termination |
| Customize ingress settings for Azure Spring Apps applications | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-configure-ingress |
| Configure Palo Alto firewall with Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-configure-palo-alto |
| Configure planned maintenance windows for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-configure-planned-maintenance |
| Control Azure Spring Apps egress with user-defined routes | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-create-user-defined-route-instance |
| Configure custom persistent storage for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-custom-persistent-storage |
| Map DNS names to multiple Azure Spring Apps instances in a VNet | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-map-dns-virtual-network |
| Prepare Steeltoe applications for Azure Spring Apps deployment | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-prepare-app-deployment |
| Register Spring Boot apps with Azure Spring Apps Service Registry | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-service-registration |
| Configure autoscale rules for Azure Spring Apps applications | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-setup-autoscale |
| Flush and update DNS settings for virtual-network-injected Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-use-flush-dns-settings |
| Use TLS/SSL certificates in Azure Spring Apps applications | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-use-tls-certificate |
| Configure Logback to write Azure Spring Apps logs to custom storage | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-write-log-to-custom-persistent-storage |
| Configure lifecycle event monitoring for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/monitor-app-lifecycle-events |
| Configure Spring Cloud Config Server for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/quickstart-setup-config-server |
| Configure Log Analytics workspace for Azure Spring Apps monitoring | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/quickstart-setup-log-analytics |
| Configure structured application logging in Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/structured-app-log |
| Expose Azure Spring Apps via Application Gateway with TLS termination | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/expose-apps-gateway-tls-termination |
| Configure VMware Spring Cloud Gateway on Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-configure-enterprise-spring-cloud-gateway |
| Configure Spring Cloud Gateway route filters on Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-configure-enterprise-spring-cloud-gateway-filters |
| Configure Application Configuration Service for Tanzu on Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-enterprise-application-configuration-service |
| Configure APM integration and CA certificates for Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-enterprise-configure-apm-integration-and-ca-certificates |
| Configure Application Live View for Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-use-application-live-view |
| Configure Tanzu Dev Tools in Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-use-dev-tool-portal |
| Configure request rate limiting with Spring Cloud Gateway on Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/quickstart-set-request-rate-limits-enterprise |

### Deployment
| Topic | URL |
|-------|-----|
| Automate Azure Spring Apps deployments with Azure Pipelines | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-cicd |
| Deploy Azure Spring Apps instances into a virtual network | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-deploy-in-azure-virtual-network |
| Build CI/CD workflows for Azure Spring Apps with GitHub Actions | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-github-actions |
| Migrate Azure Spring Apps Basic/Standard to Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-migrate-standard-tier-to-enterprise-tier |
| Implement blue-green staging deployments in Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-staging-environment |
| Deploy Azure Spring Apps into a VNet using ARM templates | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/quickstart-deploy-infrastructure-vnet |
| Provision Azure Spring Apps in a VNet using Azure CLI | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/quickstart-deploy-infrastructure-vnet-azure-cli |
| Deploy Azure Spring Apps into a VNet using Bicep | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/quickstart-deploy-infrastructure-vnet-bicep |
| Provision Azure Spring Apps in a VNet using Terraform | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/quickstart-deploy-infrastructure-vnet-terraform |
| Expose Azure Spring Apps to the internet from a public network | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-access-app-from-internet-virtual-network |
| Deploy polyglot applications using buildpacks on Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-enterprise-deploy-polyglot-apps |
| Deploy static web files with Tanzu Web Servers buildpack on Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-enterprise-deploy-static-file |
| Automate Azure Spring Apps Enterprise deployments with GitHub Actions and Terraform | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/quickstart-automate-deployments-github-actions-enterprise |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Monitor Azure Spring Apps with AppDynamics Java agent | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-appdynamics-java-agent-monitor |
| Integrate Application Insights Java agent with Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-application-insights |
| Bind Azure Cosmos DB to Azure Spring Apps applications | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-bind-cosmos |
| Bind Azure Database for MySQL to Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-bind-mysql |
| Bind Azure Database for PostgreSQL to Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-bind-postgres |
| Integrate Azure Cache for Redis with Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-bind-redis |
| Collect Resilience4j circuit breaker metrics via Micrometer | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-circuit-breaker-metrics |
| Monitor Azure Spring Apps with Dynatrace OneAgent | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-dynatrace-one-agent-monitor |
| Monitor Azure Spring Apps with Elastic APM Java agent | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-elastic-apm-java-agent-monitor |
| Send Azure Spring Apps diagnostics logs to Elastic Cloud | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-elastic-diagnostic-settings |
| Configure Azure Spring Apps Maven plugin deployment | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-maven-deploy-apps |
| Monitor Azure Spring Apps using New Relic Java agent | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-new-relic-monitor |
| Implement gRPC services in Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-use-grpc |
| Integrate Azure Spring Apps PetClinic with Azure Database for MySQL | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/quickstart-integrate-azure-database-mysql |
| Use Tanzu Build Service with Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-enterprise-build-service |
| Integrate Tanzu Service Registry with Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-enterprise-service-registry |
| Use Tanzu Application Accelerator with Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-use-accelerator |
| Configure API Portal for Tanzu on Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-use-enterprise-api-portal |
| Route requests using Spring Cloud Gateway on Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-use-enterprise-spring-cloud-gateway |
| Integrate PostgreSQL and Redis with Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/quickstart-integrate-azure-database-and-redis-enterprise |
| Monitor Azure Spring Apps Enterprise with Application Insights and Log Analytics | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/quickstart-monitor-end-to-end-enterprise |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Version support policy for Java and Spring on Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/concept-app-customer-responsibilities |
| Use Azure Spring Apps built-in persistent storage limits | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-built-in-persistent-storage |
| Review Azure Spring Apps plan quotas and limits | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/quotas |
| Understand virtual network requirements for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/vnet-customer-responsibilities |
| Scale Azure Spring Apps Enterprise to 500–1000 instances and understand preview limits | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-enterprise-deploy-app-at-scale |
| Deploy large CPU and memory workloads on Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-enterprise-large-cpu-memory-applications |

### Security
| Topic | URL |
|-------|-----|
| Understand built-in security controls in Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/concept-security-controls |
| Configure managed identity for Azure Spring Apps to access Azure SQL | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/connect-managed-identity-to-azure-sql |
| Authenticate Azure Spring Apps GitHub Actions with Azure Key Vault | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/github-actions-key-vault |
| Access Config Server and Service Registry with Entra RBAC in Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-access-data-plane-azure-ad-rbac |
| Map and secure custom domains for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-custom-domain |
| Enable ingress-to-app TLS for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-enable-ingress-to-app-tls |
| Enable system-assigned managed identity for Azure Spring Apps applications | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-enable-system-assigned-managed-identity |
| Manage user-assigned managed identities for Azure Spring Apps applications | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-manage-user-assigned-managed-identities |
| Create custom RBAC roles and permissions for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-permissions |
| Use managed identities for applications in Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-use-managed-identities |
| Use built-in Azure Policy definitions for Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/policy-reference |
| Apply Azure Policy compliance controls to Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/security-controls-policy |
| Invoke Azure Functions from Spring Apps using managed identity | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/tutorial-managed-identities-functions |
| Use managed identities from Azure Spring Apps to access Key Vault | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/tutorial-managed-identities-key-vault |
| Configure Entra ID SSO for Spring Cloud Gateway and API Portal on Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-set-up-sso-with-azure-ad |
| Configure SSO for Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/quickstart-configure-single-sign-on-enterprise |
| Load application secrets from Key Vault in Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/quickstart-key-vault-enterprise |
| Secure end-to-end communications for Spring Boot apps on Azure in zero trust environments | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/secure-communications-end-to-end |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Capture JVM dumps and JFR in Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-capture-dumps |
| Access Azure Spring Apps instances for shell debugging | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-connect-to-app-instance-for-troubleshooting |
| Diagnose and fix Azure Spring Apps OOM restarts | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-fix-app-restart-issues-caused-by-out-of-memory |
| Stream Azure Spring Apps logs for live troubleshooting | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-log-streaming |
| Enable and use remote debugging in Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-remote-debugging-app-instance |
| Diagnose Azure Spring Apps issues in VNets | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-self-diagnose-running-in-vnet |
| Self-diagnose and solve Azure Spring Apps problems with diagnostics | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-self-diagnose-solve |
| Troubleshoot common Azure Spring Apps problems | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/troubleshoot |
| Resolve Azure Spring Apps application exit codes | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/troubleshoot-exit-code |
| Troubleshoot Azure Spring Apps in virtual networks | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/troubleshooting-vnet |
| Stream Azure Spring Apps job logs in real time for troubleshooting | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-job-log-streaming |
| Stream Azure Spring Apps managed component logs in real time | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-managed-component-log-streaming |
| Troubleshoot VMware Spring Cloud Gateway on Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-troubleshoot-enterprise-spring-cloud-gateway |
| Diagnose and fix Azure Spring Apps build failures | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/troubleshoot-build-exit-code |

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
