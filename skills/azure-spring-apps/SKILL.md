---
name: azure-spring-apps
description: Expert knowledge for Azure Spring Apps development including configuration, best practices, limits & quotas, security, deployment, integrations & coding patterns, troubleshooting, architecture & design patterns, and decision making. Use when building, debugging, or optimizing Azure Spring Apps applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
metadata:
  generated_at: "2026-02-04"
---
# Azure Spring Apps Skill

This skill provides expert guidance for Azure Spring Apps development. It combines local quick-reference content with remote documentation fetching capabilities.

## How to Use This Skill

> **IMPORTANT for Agent**: This file may be large. Use the **Category Index** below to locate relevant sections, then use `read_file` with specific line ranges (e.g., `L136-L144`) to read the sections needed for the user's question
> **IMPORTANT for Agent**: If `metadata.generated_at` is more than 3 months old, suggest the user pull the latest version from the repository. If `mcp_microsoftdocs` tools are not available, suggest the user install it: [Installation Guide](https://github.com/MicrosoftDocs/mcp/blob/main/README.md)

This skill requires **network access**. Use `mcp_microsoftdocs:microsoft_docs_fetch` or `fetch_webpage` if MCP is unavailable to fetch documentation.

## Category Index

| Category | Lines | Description |
|----------|-------|-------------|
| Troubleshooting | L33-L42 | Diagnosing and fixing Azure Spring Apps issues like OOM restarts, Java memory problems, build failures, and troubleshooting via real-time app, job, and managed component logs, plus Spring Cloud Gateway. |
| Best Practices | L43-L48 | Guidance on production-grade monitoring for Azure Spring Apps, including observability setup, metrics/logs, and using Application Live View for real-time app insights and diagnostics. |
| Decision Making | L49-L54 | Choosing the right Azure Spring Apps plan (Basic/Standard/Enterprise), understanding Enterprise tier features, Marketplace offer details, and licensing/subscription implications |
| Architecture & Design Patterns | L55-L61 | Patterns for exposing Azure Spring Apps with Azure load balancers, Application Gateway (TLS termination), and secure/public internet access configurations. |
| Limits & Quotas | L62-L70 | Version support, storage limits, quotas, and guidance for scaling Azure Spring Apps Enterprise to high instance counts and large CPU/memory workloads. |
| Security | L71-L84 | Security features and patterns for Spring Apps: managed identity to SQL/Key Vault/Functions, Entra ID SSO, custom domains, policy compliance, secrets loading, and end‑to‑end Zero Trust protection. |
| Configuration | L85-L115 | Configuring Azure Spring Apps runtime: networking, scaling, storage, logging/metrics/tracing, health/maintenance, gateways, service registry, and enterprise features (Tanzu, APM, Dev Tools). |
| Integrations & Coding Patterns | L116-L141 | Integrating Azure Spring Apps with APM/monitoring tools, databases, Redis, gRPC, gateways, Entra ID auth, Azure OpenAI, and using Enterprise features like Tanzu services and Maven deployment. |
| Deployment | L142-L155 | Deployment patterns (zero-downtime, blue-green), VNet-integrated provisioning (ARM/Bicep/CLI/Terraform), and CI/CD for polyglot and static apps using buildpacks and GitHub Actions |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Diagnose and fix OOM app restarts in Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-fix-app-restart-issues-caused-by-out-of-memory |
| Use tools to troubleshoot Java memory in Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/tools-to-troubleshoot-memory-issues |
| Stream Azure Spring Apps job logs in real time for troubleshooting | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-job-log-streaming |
| Stream managed component logs in real time on Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-managed-component-log-streaming |
| Troubleshoot VMware Spring Cloud Gateway on Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-troubleshoot-enterprise-spring-cloud-gateway |
| Diagnose and fix Azure Spring Apps build failures | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/troubleshoot-build-exit-code |

### Best Practices
| Topic | URL |
|-------|-----|
| Optimize observability for production Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/application-observability |
| Monitor Azure Spring Apps using Application Live View | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/monitor-apps-by-application-live-view |

### Decision Making
| Topic | URL |
|-------|-----|
| Select the right Azure Spring Apps plan | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/plan-comparison |
| Understand Azure Spring Apps Enterprise Marketplace offer and licensing | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-enterprise-marketplace-offer |

### Architecture & Design Patterns
| Topic | URL |
|-------|-----|
| Integrate Azure Spring Apps with Azure load balancing options | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-integrate-azure-load-balancers |
| Expose Azure Spring Apps via Application Gateway with TLS termination | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/expose-apps-gateway-tls-termination |
| Expose Azure Spring Apps to the internet from public networks | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-access-app-from-internet-virtual-network |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Version support policy for Java and Spring on Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/concept-app-customer-responsibilities |
| Use built-in persistent and temporary storage limits in Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-built-in-persistent-storage |
| Azure Spring Apps plans quotas and limits | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/quotas |
| Scale Azure Spring Apps Enterprise to 500–1000 instances | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-enterprise-deploy-app-at-scale |
| Deploy large CPU and memory workloads on Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-enterprise-large-cpu-memory-applications |

### Security
| Topic | URL |
|-------|-----|
| Understand built-in security controls in Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/concept-security-controls |
| Configure managed identity for Azure Spring Apps to access Azure SQL | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/connect-managed-identity-to-azure-sql |
| Map and secure custom domains for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-custom-domain |
| Azure Policy compliance controls for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/security-controls-policy |
| Use managed identity to call Azure Functions from Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/tutorial-managed-identities-functions |
| Configure managed identity to access Key Vault from Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/tutorial-managed-identities-key-vault |
| Configure Entra ID SSO for Spring Cloud Gateway and API Portal on Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-set-up-sso-with-azure-ad |
| Configure single sign-on for Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/quickstart-configure-single-sign-on-enterprise |
| Load application secrets from Key Vault in Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/quickstart-key-vault-enterprise |
| Secure end-to-end communications for Spring Boot apps on Azure in Zero Trust environments | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/secure-communications-end-to-end |

### Configuration
| Topic | URL |
|-------|-----|
| Access Azure Spring Apps over private endpoints in a VNet | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/access-app-virtual-network |
| Configure custom egress routes for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/concept-outbound-type |
| Configure diagnostics logs and metrics for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/diagnostic-services |
| Configure managed Spring Cloud Config Server in Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-config-server |
| Configure health probes and graceful termination in Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-configure-health-probes-graceful-termination |
| Configure planned maintenance windows for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-configure-planned-maintenance |
| Configure custom persistent storage for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-custom-persistent-storage |
| Enable real-time log streaming for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-log-streaming |
| View and configure outbound public IPs for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-outbound-public-ip |
| Prepare Steeltoe applications for Azure Spring Apps deployment | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-prepare-app-deployment |
| Configure manual scaling for Azure Spring Apps applications | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-scale-manual |
| Register Spring Boot apps with Azure Spring Apps Service Registry | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-service-registration |
| Set up autoscale rules for Azure Spring Apps apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-setup-autoscale |
| Write Azure Spring Apps logs to custom persistent storage with Logback | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-write-log-to-custom-persistent-storage |
| Configure lifecycle event monitoring for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/monitor-app-lifecycle-events |
| Configure logs, metrics, and tracing for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/quickstart-logs-metrics-tracing |
| Configure Spring Cloud Config Server for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/quickstart-setup-config-server |
| Configure Log Analytics workspace for Azure Spring Apps monitoring | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/quickstart-setup-log-analytics |
| Generate and collect structured logs in Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/structured-app-log |
| Configure VMware Spring Cloud Gateway on Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-configure-enterprise-spring-cloud-gateway |
| Configure Spring Cloud Gateway route filters on Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-configure-enterprise-spring-cloud-gateway-filters |
| Configure Application Configuration Service for Tanzu in Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-enterprise-application-configuration-service |
| Use Tanzu Build Service with Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-enterprise-build-service |
| Configure APM integration and CA certificates in Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-enterprise-configure-apm-integration-and-ca-certificates |
| Configure Tanzu Dev Tools for Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-use-dev-tool-portal |
| Configure end-to-end monitoring for Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/quickstart-monitor-end-to-end-enterprise |
| Configure request rate limiting with Spring Cloud Gateway | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/quickstart-set-request-rate-limits-enterprise |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Monitor Azure Spring Apps with AppDynamics Java agent | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-appdynamics-java-agent-monitor |
| Configure Application Insights Java agent for Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-application-insights |
| Bind Azure Cosmos DB to Azure Spring Apps applications | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-bind-cosmos |
| Bind Azure Database for MySQL to Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-bind-mysql |
| Bind Azure Database for PostgreSQL to Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-bind-postgres |
| Connect Azure Cache for Redis to Azure Spring Apps apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-bind-redis |
| Collect Resilience4j circuit breaker metrics with Micrometer | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-circuit-breaker-metrics |
| Monitor Azure Spring Apps with Dynatrace OneAgent | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-dynatrace-one-agent-monitor |
| Monitor Azure Spring Apps with Elastic APM Java agent | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-elastic-apm-java-agent-monitor |
| Analyze Azure Spring Apps logs with Elastic Cloud | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-elastic-diagnostic-settings |
| Configure Azure Spring Apps Maven plugin deployment | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-maven-deploy-apps |
| Monitor Azure Spring Apps with New Relic Java agent | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-new-relic-monitor |
| Implement gRPC services in Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-use-grpc |
| Integrate Azure Spring Apps PetClinic with Azure Database for MySQL | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/quickstart-integrate-azure-database-mysql |
| Configure Tanzu Service Registry on Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-enterprise-service-registry |
| Use Tanzu Application Accelerator with Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-use-accelerator |
| Use Application Live View for monitoring on Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-use-application-live-view |
| Integrate API Portal for Tanzu with Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-use-enterprise-api-portal |
| Use VMware Spring Cloud Gateway to route Azure Spring Apps traffic | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-use-enterprise-spring-cloud-gateway |
| Deploy Entra ID–protected REST API to Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/quickstart-deploy-restful-api-app |
| Integrate Azure OpenAI with Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/quickstart-fitness-store-azure-openai |
| Connect Spring Apps Enterprise to PostgreSQL and Redis | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/quickstart-integrate-azure-database-and-redis-enterprise |

### Deployment
| Topic | URL |
|-------|-----|
| Achieve zero-downtime deployments on Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/concept-zero-downtime-deployment |
| Implement blue-green deployment strategies in Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/concepts-blue-green-deployment-strategies |
| Deploy Azure Spring Apps into a virtual network | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-deploy-in-azure-virtual-network |
| Set up blue-green staging deployments in Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-staging-environment |
| Deploy Azure Spring Apps into VNet using ARM template | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/quickstart-deploy-infrastructure-vnet |
| Provision Azure Spring Apps into VNet using Azure CLI | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/quickstart-deploy-infrastructure-vnet-azure-cli |
| Deploy Azure Spring Apps into VNet using Bicep | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/quickstart-deploy-infrastructure-vnet-bicep |
| Provision Azure Spring Apps into VNet using Terraform | https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/quickstart-deploy-infrastructure-vnet-terraform |
| Deploy polyglot applications with buildpacks on Azure Spring Apps Enterprise | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-enterprise-deploy-polyglot-apps |
| Deploy static web files using Tanzu Web Servers buildpack on Azure Spring Apps | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/how-to-enterprise-deploy-static-file |
| Automate Azure Spring Apps Enterprise deployments with GitHub Actions | https://learn.microsoft.com/en-us/azure/spring-apps/enterprise/quickstart-automate-deployments-github-actions-enterprise |