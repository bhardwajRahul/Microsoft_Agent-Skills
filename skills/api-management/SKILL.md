---
name: api-management
description: Expert knowledge for Api Management development including integrations & coding patterns, limits & quotas, security, architecture & design patterns, troubleshooting, comparing x vs. y, best practices, configuration, and deployment. Use when building, debugging, or optimizing Api Management applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Api Management Skill

This skill provides expert guidance for Api Management development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Use API Management capacity metrics for scaling decisions | https://learn.microsoft.com/en-us/azure/api-management/api-management-capacity |
| Front API Management with Application Gateway in internal VNets | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-integrate-internal-vnet-appgateway |
| Use API Management with AKS-based microservices | https://learn.microsoft.com/en-us/azure/api-management/api-management-kubernetes |
| Place Azure Front Door in front of API Management | https://learn.microsoft.com/en-us/azure/api-management/front-door-api-management |
| Choose virtual network options for Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/virtual-network-concepts |

### Best Practices
| Topic | URL |
|-------|-----|
| Configure autoscale rules for Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-autoscale |
| Implement flexible throttling in API Management | https://learn.microsoft.com/en-us/azure/api-management/api-management-sample-flexible-throttling |
| Run API Management self-hosted gateway on Kubernetes in production | https://learn.microsoft.com/en-us/azure/api-management/how-to-self-hosted-gateway-on-kubernetes-in-production |
| Mitigate OWASP API Security Top 10 using Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/mitigate-owasp-api-threats |
| Use API Management sustainability features to reduce carbon impact | https://learn.microsoft.com/en-us/azure/api-management/sustainability |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Compare Azure API Management pricing tiers by features | https://learn.microsoft.com/en-us/azure/api-management/api-management-features |
| Migrate from Amazon API Gateway to Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/migrate-amazon-api-gateway-to-api-management |

### Configuration
| Topic | URL |
|-------|-----|
| Configure response caching in Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-cache |
| Configure external Redis-compatible cache for API Management | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-cache-external |
| Configure custom domain for self-hosted API gateway | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-configure-custom-domain-gateway |
| Configure notifications and email templates in APIM | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-configure-notifications |
| Manage API Management developers using groups | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-create-groups |
| Manage developer user accounts in Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-create-or-invite-developers |
| Create and configure subscriptions in Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-create-subscriptions |
| Retrieve and manage API Management IP addresses | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-ip-addresses |
| Set up Azure Monitor logging for LLM APIs in API Management | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-llm-logs |
| Configure Azure API Management policy behaviors | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-policies |
| Configure named values in API Management policies | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-properties |
| Delegate APIM portal user registration and subscriptions | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-setup-delegation |
| Configure and reference Azure API Management policies | https://learn.microsoft.com/en-us/azure/api-management/api-management-policies |
| Use C# policy expressions in API Management | https://learn.microsoft.com/en-us/azure/api-management/api-management-policy-expressions |
| Configure custom key-based caching in API Management | https://learn.microsoft.com/en-us/azure/api-management/api-management-sample-cache-by-key |
| Configure authentication-basic policy in API Management | https://learn.microsoft.com/en-us/azure/api-management/authentication-basic-policy |
| Configure authentication-certificate policy in API Management | https://learn.microsoft.com/en-us/azure/api-management/authentication-certificate-policy |
| Configure authentication-managed-identity policy in API Management | https://learn.microsoft.com/en-us/azure/api-management/authentication-managed-identity-policy |
| Emit Azure OpenAI token metrics via API Management policy | https://learn.microsoft.com/en-us/azure/api-management/azure-openai-emit-token-metric-policy |
| Enable and configure semantic caching for LLM APIs | https://learn.microsoft.com/en-us/azure/api-management/azure-openai-enable-semantic-caching |
| Configure semantic cache lookup for Azure OpenAI in API Management | https://learn.microsoft.com/en-us/azure/api-management/azure-openai-semantic-cache-lookup-policy |
| Configure semantic cache store for Azure OpenAI in API Management | https://learn.microsoft.com/en-us/azure/api-management/azure-openai-semantic-cache-store-policy |
| Update VNet rules for API Management CAPTCHA endpoint change | https://learn.microsoft.com/en-us/azure/api-management/breaking-changes/captcha-endpoint-change-sep-2025 |
| Reconfigure API Management identity providers from ADAL to MSAL | https://learn.microsoft.com/en-us/azure/api-management/breaking-changes/identity-provider-adal-retirement-sep-2025 |
| Update network settings for APIM resource provider IP change (March 2023) | https://learn.microsoft.com/en-us/azure/api-management/breaking-changes/rp-source-ip-address-change-mar-2023 |
| Update network rules for API Management IP change | https://learn.microsoft.com/en-us/azure/api-management/breaking-changes/rp-source-ip-address-change-sep-2023 |
| Replace trusted service connectivity for API Management gateways | https://learn.microsoft.com/en-us/azure/api-management/breaking-changes/trusted-service-connectivity-retirement-march-2026 |
| Adjust Azure API Management workspaces after breaking changes | https://learn.microsoft.com/en-us/azure/api-management/breaking-changes/workspaces-breaking-changes-june-2024 |
| Migrate from preview to GA API Management workspaces | https://learn.microsoft.com/en-us/azure/api-management/breaking-changes/workspaces-breaking-changes-march-2025 |
| Configure cache-lookup policy in Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/cache-lookup-policy |
| Configure cache-lookup-value policy in Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/cache-lookup-value-policy |
| Configure cache-remove-value policy in Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/cache-remove-value-policy |
| Configure cache-store policy in Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/cache-store-policy |
| Configure cache-store-value policy in Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/cache-store-value-policy |
| Enforce HTTP headers with check-header policy in API Management | https://learn.microsoft.com/en-us/azure/api-management/check-header-policy |
| Control policy flow with choose policy in API Management | https://learn.microsoft.com/en-us/azure/api-management/choose-policy |
| Set up multiple credential manager connections in API Management | https://learn.microsoft.com/en-us/azure/api-management/configure-credential-connection |
| Configure custom domains and certificates for API Management | https://learn.microsoft.com/en-us/azure/api-management/configure-custom-domain |
| Configure GraphQL resolvers in Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/configure-graphql-resolver |
| Configure service update groups and maintenance windows in API Management | https://learn.microsoft.com/en-us/azure/api-management/configure-service-update-settings |
| Configure common OAuth providers in API Management credential manager | https://learn.microsoft.com/en-us/azure/api-management/credentials-configure-common-providers |
| Configure user-delegated OAuth connections in API Management | https://learn.microsoft.com/en-us/azure/api-management/credentials-how-to-user-delegated |
| Use Credential Manager to manage backend API connections | https://learn.microsoft.com/en-us/azure/api-management/credentials-overview |
| Configure cross-domain policy for legacy browser clients in API Management | https://learn.microsoft.com/en-us/azure/api-management/cross-domain-policy |
| Extend API Management developer portal with custom functionality | https://learn.microsoft.com/en-us/azure/api-management/developer-portal-extend-custom-functionality |
| Emit custom metrics with emit-metric policy in API Management | https://learn.microsoft.com/en-us/azure/api-management/emit-metric-policy |
| Configure CORS policies for APIM Power Platform connectors | https://learn.microsoft.com/en-us/azure/api-management/enable-cors-power-platform |
| Modify payloads with find-and-replace policy in API Management | https://learn.microsoft.com/en-us/azure/api-management/find-and-replace-policy |
| Configure cloud metrics and logs for self-hosted gateway | https://learn.microsoft.com/en-us/azure/api-management/how-to-configure-cloud-metrics-logs |
| Configure local metrics and logs on Kubernetes self-hosted gateway | https://learn.microsoft.com/en-us/azure/api-management/how-to-configure-local-metrics-logs |
| Create and configure workspaces in Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/how-to-create-workspace |
| Configure Server-Sent Events APIs in Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/how-to-server-sent-events |
| Use include-fragment policy for reusable API policies | https://learn.microsoft.com/en-us/azure/api-management/include-fragment-policy |
| Emit LLM token usage metrics from API Management | https://learn.microsoft.com/en-us/azure/api-management/llm-emit-token-metric-policy |
| Mock backend responses with API Management mock-response policy | https://learn.microsoft.com/en-us/azure/api-management/mock-response-policy |
| Configure monitoring for Azure API Management with Azure Monitor | https://learn.microsoft.com/en-us/azure/api-management/monitor-api-management |
| Reference monitoring metrics and logs for Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/monitor-api-management-reference |
| Create and reuse API Management policy fragments | https://learn.microsoft.com/en-us/azure/api-management/policy-fragments |
| Configure quota-by-key policy in API Management | https://learn.microsoft.com/en-us/azure/api-management/quota-by-key-policy |
| Configure rate-limit-by-key policy in API Management | https://learn.microsoft.com/en-us/azure/api-management/rate-limit-by-key-policy |
| Configure rate-limit policy in Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/rate-limit-policy |
| Configure redirect-content-urls policy for API responses | https://learn.microsoft.com/en-us/azure/api-management/redirect-content-urls-policy |
| Configure retry policy behavior in API Management | https://learn.microsoft.com/en-us/azure/api-management/retry-policy |
| Use return-response policy to short-circuit requests | https://learn.microsoft.com/en-us/azure/api-management/return-response-policy |
| Configure rewrite-uri policy for backend URL mapping | https://learn.microsoft.com/en-us/azure/api-management/rewrite-uri-policy |
| Configure Azure Arc extension settings for API Management self-hosted gateway | https://learn.microsoft.com/en-us/azure/api-management/self-hosted-gateway-arc-reference |
| Configure self-hosted gateway container settings for API Management | https://learn.microsoft.com/en-us/azure/api-management/self-hosted-gateway-settings-reference |
| Configure send-one-way-request policy in API Management | https://learn.microsoft.com/en-us/azure/api-management/send-one-way-request-policy |
| Configure send-request policy with timeouts in API Management | https://learn.microsoft.com/en-us/azure/api-management/send-request-policy |
| Configure set-backend-service policy and backends reuse | https://learn.microsoft.com/en-us/azure/api-management/set-backend-service-policy |
| Configure set-body policy and preserve message bodies | https://learn.microsoft.com/en-us/azure/api-management/set-body-policy |
| Configure set-header policy for requests and responses | https://learn.microsoft.com/en-us/azure/api-management/set-header-policy |
| Configure set-method policy to change HTTP verbs | https://learn.microsoft.com/en-us/azure/api-management/set-method-policy |
| Configure set-query-parameter policy for request parameters | https://learn.microsoft.com/en-us/azure/api-management/set-query-parameter-policy |
| Configure set-status policy to control HTTP status codes | https://learn.microsoft.com/en-us/azure/api-management/set-status-policy |
| Use set-variable policy to define context variables | https://learn.microsoft.com/en-us/azure/api-management/set-variable-policy |
| Configure trace policy for API Management diagnostics | https://learn.microsoft.com/en-us/azure/api-management/trace-policy |
| Configure validate-graphql-request policy in API Management | https://learn.microsoft.com/en-us/azure/api-management/validate-graphql-request-policy |
| Configure validate-odata-request policy in API Management | https://learn.microsoft.com/en-us/azure/api-management/validate-odata-request-policy |
| Meet network resource requirements for API Management VNet injection | https://learn.microsoft.com/en-us/azure/api-management/virtual-network-injection-resources |
| Configure VNet settings for Azure API Management classic tiers | https://learn.microsoft.com/en-us/azure/api-management/virtual-network-reference |
| Use the wait policy for parallel execution in API Management | https://learn.microsoft.com/en-us/azure/api-management/wait-policy |
| Configure xml-to-json transformation policy in API Management | https://learn.microsoft.com/en-us/azure/api-management/xml-to-json-policy |
| Apply XSL transformations with xsl-transform policy in API Management | https://learn.microsoft.com/en-us/azure/api-management/xsl-transform-policy |

### Deployment
| Topic | URL |
|-------|-----|
| Deploy API Management across multiple Azure regions | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-deploy-multi-region |
| Backup and restore API Management for disaster recovery | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-disaster-recovery-backup-restore |
| Migrate Azure API Management instances between regions | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-migrate |
| Provision a self-hosted gateway resource in API Management | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-provision-self-hosted-gateway |
| Check regional availability of API Management v2 tiers and workspace gateways | https://learn.microsoft.com/en-us/azure/api-management/api-management-region-availability |
| Deploy API Management in internal virtual network mode | https://learn.microsoft.com/en-us/azure/api-management/api-management-using-with-internal-vnet |
| Deploy Azure API Management to an external virtual network | https://learn.microsoft.com/en-us/azure/api-management/api-management-using-with-vnet |
| Automate deployment of API Management developer portal content | https://learn.microsoft.com/en-us/azure/api-management/automate-portal-deployments |
| Use alternative approaches to self-host APIM portal | https://learn.microsoft.com/en-us/azure/api-management/developer-portal-alternative-processes-self-host |
| Self-host Azure API Management developer portal | https://learn.microsoft.com/en-us/azure/api-management/developer-portal-self-host |
| Adopt DevOps and CI/CD for Azure API Management APIs | https://learn.microsoft.com/en-us/azure/api-management/devops-api-development-templates |
| Enable availability zones for API Management instances | https://learn.microsoft.com/en-us/azure/api-management/enable-availability-zone-support |
| Deploy API Management self-hosted gateway via Azure Arc | https://learn.microsoft.com/en-us/azure/api-management/how-to-deploy-self-hosted-gateway-azure-arc |
| Deploy API Management self-hosted gateway to AKS | https://learn.microsoft.com/en-us/azure/api-management/how-to-deploy-self-hosted-gateway-azure-kubernetes-service |
| Deploy API Management self-hosted gateway to Azure Container Apps | https://learn.microsoft.com/en-us/azure/api-management/how-to-deploy-self-hosted-gateway-container-apps |
| Deploy API Management self-hosted gateway to Docker | https://learn.microsoft.com/en-us/azure/api-management/how-to-deploy-self-hosted-gateway-docker |
| Deploy API Management self-hosted gateway to Kubernetes with YAML | https://learn.microsoft.com/en-us/azure/api-management/how-to-deploy-self-hosted-gateway-kubernetes |
| Deploy API Management self-hosted gateway to Kubernetes with Helm | https://learn.microsoft.com/en-us/azure/api-management/how-to-deploy-self-hosted-gateway-kubernetes-helm |
| Deploy self-hosted gateway with OpenTelemetry on Kubernetes | https://learn.microsoft.com/en-us/azure/api-management/how-to-deploy-self-hosted-gateway-kubernetes-opentelemetry |
| Inject Premium v2 API Management into virtual networks | https://learn.microsoft.com/en-us/azure/api-management/inject-vnet-v2 |
| Configure outbound VNet integration for API Management | https://learn.microsoft.com/en-us/azure/api-management/integrate-vnet-outbound |
| Meet VNet requirements for API Management workspace gateways | https://learn.microsoft.com/en-us/azure/api-management/virtual-network-workspaces-resources |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Import and manage Agent2Agent (A2A) agent APIs in API Management | https://learn.microsoft.com/en-us/azure/api-management/agent-to-agent-api |
| Import Amazon Bedrock LLM APIs as passthrough in API Management | https://learn.microsoft.com/en-us/azure/api-management/amazon-bedrock-passthrough-llm-api |
| Integrate API Management with Application Insights logging | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-app-insights |
| Log API Management events to Azure Event Hubs | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-log-event-hubs |
| Send messages to Azure Service Bus from API Management | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-send-service-bus |
| Log API Management traffic to Event Hubs and Moesif | https://learn.microsoft.com/en-us/azure/api-management/api-management-log-to-eventhub-sample |
| Call external services from API Management policies | https://learn.microsoft.com/en-us/azure/api-management/api-management-sample-send-request |
| Import Microsoft Foundry AI APIs into API Management | https://learn.microsoft.com/en-us/azure/api-management/azure-ai-foundry-api |
| Import Azure OpenAI APIs as REST in API Management | https://learn.microsoft.com/en-us/azure/api-management/azure-openai-api-from-specification |
| Integrate GraphQL APIs with Cosmos DB via cosmosdb-data-source policy | https://learn.microsoft.com/en-us/azure/api-management/cosmosdb-data-source-policy |
| Create managed Microsoft Graph connection in API Management | https://learn.microsoft.com/en-us/azure/api-management/credentials-how-to-azure-ad |
| Connect Azure API Management to GitHub OAuth APIs | https://learn.microsoft.com/en-us/azure/api-management/credentials-how-to-github |
| Integrate Application Insights with API Management developer portal | https://learn.microsoft.com/en-us/azure/api-management/developer-portal-integrate-application-insights |
| Integrate Google Tag Manager with API Management developer portal | https://learn.microsoft.com/en-us/azure/api-management/developer-portal-integrate-google-tag-manager |
| Customize API Management developer portal using WordPress plugin | https://learn.microsoft.com/en-us/azure/api-management/developer-portal-wordpress-plugin |
| Export Azure API Management APIs to Postman collections | https://learn.microsoft.com/en-us/azure/api-management/export-api-postman |
| Export APIM APIs to Power Platform custom connectors | https://learn.microsoft.com/en-us/azure/api-management/export-api-power-platform |
| Expose REST APIs as MCP servers via API Management | https://learn.microsoft.com/en-us/azure/api-management/export-rest-mcp-server |
| Connect and govern existing MCP servers with API Management | https://learn.microsoft.com/en-us/azure/api-management/expose-existing-mcp-server |
| Configure forward-request policy in Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/forward-request-policy |
| Use get-authorization-context policy in API Management | https://learn.microsoft.com/en-us/azure/api-management/get-authorization-context-policy |
| Configure Service Fabric services as API Management backends | https://learn.microsoft.com/en-us/azure/api-management/how-to-configure-service-fabric-backend |
| Send Azure API Management events to Event Grid | https://learn.microsoft.com/en-us/azure/api-management/how-to-event-grid |
| Configure http-data-source policy for GraphQL resolvers | https://learn.microsoft.com/en-us/azure/api-management/http-data-source-policy |
| Import OData-compliant services into API Management | https://learn.microsoft.com/en-us/azure/api-management/import-api-from-odata |
| Import Azure Function Apps into API Management | https://learn.microsoft.com/en-us/azure/api-management/import-function-app-as-api |
| Import Logic Apps (Consumption) into API Management | https://learn.microsoft.com/en-us/azure/api-management/import-logic-app-as-api |
| Invoke Dapr bindings with API Management policy | https://learn.microsoft.com/en-us/azure/api-management/invoke-dapr-binding-policy |
| Convert JSON to XML with API Management policy | https://learn.microsoft.com/en-us/azure/api-management/json-to-xml-policy |
| Enable JSONP support with API Management jsonp policy | https://learn.microsoft.com/en-us/azure/api-management/jsonp-policy |
| Configure LLM semantic cache lookup in API Management | https://learn.microsoft.com/en-us/azure/api-management/llm-semantic-cache-lookup-policy |
| Store LLM responses with semantic cache policy | https://learn.microsoft.com/en-us/azure/api-management/llm-semantic-cache-store-policy |
| Log API Management traffic to Azure Event Hubs | https://learn.microsoft.com/en-us/azure/api-management/log-to-eventhub-policy |
| Import and manage Google Gemini OpenAI-compatible APIs | https://learn.microsoft.com/en-us/azure/api-management/openai-compatible-google-gemini-api |
| Import OpenAI-compatible and custom LLM APIs into API Management | https://learn.microsoft.com/en-us/azure/api-management/openai-compatible-llm-api |
| Publish GraphQL subscription events with API Management policy | https://learn.microsoft.com/en-us/azure/api-management/publish-event-policy |
| Publish messages to Dapr Pub/Sub from API Management | https://learn.microsoft.com/en-us/azure/api-management/publish-to-dapr-policy |
| Import SAP OData metadata into Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/sap-api |
| Enable Dapr integration in API Management self-hosted gateway | https://learn.microsoft.com/en-us/azure/api-management/self-hosted-gateway-enable-dapr |
| Send Service Bus messages via API Management policy | https://learn.microsoft.com/en-us/azure/api-management/send-service-bus-message-policy |
| Use set-backend-service policy for Dapr sidecar integration | https://learn.microsoft.com/en-us/azure/api-management/set-backend-service-dapr-policy |
| Configure sql-data-source policy for GraphQL resolvers | https://learn.microsoft.com/en-us/azure/api-management/sql-data-source-policy |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| API format import restrictions for Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/api-management-api-import-restrictions |
| Limit Azure OpenAI token usage with API Management policy | https://learn.microsoft.com/en-us/azure/api-management/azure-openai-token-limit-policy |
| Plan for managed certificate suspension in API Management | https://learn.microsoft.com/en-us/azure/api-management/breaking-changes/managed-certificates-suspension-august-2025 |
| Migrate from legacy APIM metrics to Requests metric | https://learn.microsoft.com/en-us/azure/api-management/breaking-changes/metrics-retirement-aug-2023 |
| Import and manage gRPC APIs in API Management | https://learn.microsoft.com/en-us/azure/api-management/grpc-api |
| Import OpenAPI specs into Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/import-api-from-oas |
| Import SOAP WSDL APIs into Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/import-soap-api |
| Limit concurrent API executions with limit-concurrency policy | https://learn.microsoft.com/en-us/azure/api-management/limit-concurrency-policy |
| Enforce LLM token rate and quota limits in API Management | https://learn.microsoft.com/en-us/azure/api-management/llm-token-limit-policy |
| Configure call and bandwidth quotas with API Management quota policy | https://learn.microsoft.com/en-us/azure/api-management/quota-policy |
| Convert SOAP WSDL APIs to REST in API Management | https://learn.microsoft.com/en-us/azure/api-management/restify-soap-api |
| Support policies and limitations for API Management self-hosted gateway | https://learn.microsoft.com/en-us/azure/api-management/self-hosted-gateway-support-policies |
| Understand Azure API Management service limits and quotas | https://learn.microsoft.com/en-us/azure/api-management/service-limits |
| Recover deleted Azure API Management instances with soft-delete | https://learn.microsoft.com/en-us/azure/api-management/soft-delete |
| Upgrade and scale Azure API Management units and capacity | https://learn.microsoft.com/en-us/azure/api-management/upgrade-and-scale |
| Validate request and response content in API Management | https://learn.microsoft.com/en-us/azure/api-management/validate-content-policy |
| Validate response headers with API schema in API Management | https://learn.microsoft.com/en-us/azure/api-management/validate-headers-policy |
| Validate request parameters against API schema in API Management | https://learn.microsoft.com/en-us/azure/api-management/validate-parameters-policy |
| Validate HTTP status codes with API schema in API Management | https://learn.microsoft.com/en-us/azure/api-management/validate-status-code-policy |
| Configure and manage WebSocket APIs in API Management | https://learn.microsoft.com/en-us/azure/api-management/websocket-api |

### Security
| Topic | URL |
|-------|-----|
| Configure authentication and authorization to LLM APIs in API Management | https://learn.microsoft.com/en-us/azure/api-management/api-management-authenticate-authorize-ai-apis |
| Enable Microsoft Entra ID sign-in for APIM portal | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-aad |
| Configure Azure AD B2C authentication for APIM portal | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-aad-b2c |
| Manage custom CA certificates in Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-ca-certificates |
| Authorize external users via Entra External ID in APIM portal | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-entra-external-id |
| Configure TLS protocols and cipher suites in API Management | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-manage-protocols-ciphers |
| Secure API Management backends with client certificate authentication | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-mutual-certificates |
| Secure APIs with client certificate and mutual TLS in API Management | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-mutual-certificates-for-clients |
| Configure OAuth 2.0 authorization for API Management developer portal console | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-oauth2 |
| Protect APIs with OAuth2 and Microsoft Entra in API Management | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-protect-backend-with-aad |
| Configure and use managed identities with Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/api-management-howto-use-managed-service-identity |
| Use Azure RBAC roles for API Management access control | https://learn.microsoft.com/en-us/azure/api-management/api-management-role-based-access-control |
| Configure OAuth2 product access with Microsoft Entra applications | https://learn.microsoft.com/en-us/azure/api-management/applications |
| Configure CORS policy for Azure API Management APIs | https://learn.microsoft.com/en-us/azure/api-management/cors-policy |
| Configure basic authentication for APIM developer portal | https://learn.microsoft.com/en-us/azure/api-management/developer-portal-basic-authentication |
| Configure CORS for Azure API Management developer portal test console | https://learn.microsoft.com/en-us/azure/api-management/enable-cors-developer-portal |
| Secure APIs with Azure AD B2C, API Management, and Easy Auth | https://learn.microsoft.com/en-us/azure/api-management/howto-protect-backend-frontend-azure-ad-b2c |
| Restrict client IPs with ip-filter policy in API Management | https://learn.microsoft.com/en-us/azure/api-management/ip-filter-policy |
| Enforce LLM content safety with API Management policy | https://learn.microsoft.com/en-us/azure/api-management/llm-content-safety-policy |
| Secure API Management with inbound private endpoints | https://learn.microsoft.com/en-us/azure/api-management/private-endpoint |
| Protect API Management from DDoS attacks | https://learn.microsoft.com/en-us/azure/api-management/protect-with-ddos-protection |
| Enable Defender for APIs protection in API Management | https://learn.microsoft.com/en-us/azure/api-management/protect-with-defender-for-apis |
| Route API Management traffic through HTTP proxy | https://learn.microsoft.com/en-us/azure/api-management/proxy-policy |
| Secure Azure API Management developer portal access | https://learn.microsoft.com/en-us/azure/api-management/secure-developer-portal-access |
| Secure inbound and outbound access to MCP servers in API Management | https://learn.microsoft.com/en-us/azure/api-management/secure-mcp-servers |
| Apply Azure Policy regulatory controls to API Management | https://learn.microsoft.com/en-us/azure/api-management/security-controls-policy |
| Configure Microsoft Entra authentication for self-hosted gateway | https://learn.microsoft.com/en-us/azure/api-management/self-hosted-gateway-enable-azure-ad |
| Configure validate-azure-ad-token policy in API Management | https://learn.microsoft.com/en-us/azure/api-management/validate-azure-ad-token-policy |
| Use validate-client-certificate policy in API Management | https://learn.microsoft.com/en-us/azure/api-management/validate-client-certificate-policy |
| Configure validate-jwt policy in Azure API Management | https://learn.microsoft.com/en-us/azure/api-management/validate-jwt-policy |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Handle errors with Azure API Management policies | https://learn.microsoft.com/en-us/azure/api-management/api-management-error-handling-policies |
| Fix APIM custom domain errors with Key Vault certificates | https://learn.microsoft.com/en-us/azure/api-management/api-management-troubleshoot-cannot-add-custom-domain |
| Troubleshoot common Azure API Management developer portal issues | https://learn.microsoft.com/en-us/azure/api-management/developer-portal-faq |
| Use Diagnose and Solve to troubleshoot APIM APIs | https://learn.microsoft.com/en-us/azure/api-management/diagnose-solve-problems |
| Troubleshoot APIM client timeouts and SNAT port exhaustion | https://learn.microsoft.com/en-us/azure/api-management/troubleshoot-response-timeout-and-errors |

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
