---
name: application-gateway
description: Expert knowledge for Application Gateway development including configuration, limits & quotas, troubleshooting, security, deployment, integrations & coding patterns, and best practices. Use when building, debugging, or optimizing Application Gateway applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Application Gateway Skill

This skill provides expert guidance for Application Gateway development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Apply high-traffic configuration best practices for Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/high-traffic-support |

### Configuration
| Topic | URL |
|-------|-----|
| Configure HTTP header rewrite using PowerShell | https://learn.microsoft.com/en-us/azure/application-gateway/add-http-header-rewrite-rule-powershell |
| Configure custom probes for classic Application Gateway via PowerShell | https://learn.microsoft.com/en-us/azure/application-gateway/application-gateway-create-probe-classic-ps |
| Create custom health probes in Application Gateway portal | https://learn.microsoft.com/en-us/azure/application-gateway/application-gateway-create-probe-portal |
| Configure custom probes for Application Gateway using PowerShell | https://learn.microsoft.com/en-us/azure/application-gateway/application-gateway-create-probe-ps |
| Set up Application Gateway with internal load balancer endpoint | https://learn.microsoft.com/en-us/azure/application-gateway/application-gateway-ilb-arm |
| Configure frontend IP addresses for Azure Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/configuration-frontend-ip |
| Configure backend settings for Azure Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/configuration-http-settings |
| Configure infrastructure for Azure Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/configuration-infrastructure |
| Configure listeners and protocols for Azure Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/configuration-listeners |
| Configure core components of Azure Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/configuration-overview |
| Configure request routing rules in Azure Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/configuration-request-routing-rules |
| Configure Azure Monitor alert rules for Application Gateway via templates | https://learn.microsoft.com/en-us/azure/application-gateway/configure-alerts-with-templates |
| Configure Application Gateway v1 with private frontend IP | https://learn.microsoft.com/en-us/azure/application-gateway/configure-application-gateway-with-private-frontend-ip |
| Configure Application Gateway with Azure App Service backends | https://learn.microsoft.com/en-us/azure/application-gateway/configure-web-app |
| Create and configure custom error pages in Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/custom-error |
| Customize AKS pod health probes via Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/ingress-controller-add-health-probes |
| Configure Application Gateway Ingress Controller annotations | https://learn.microsoft.com/en-us/azure/application-gateway/ingress-controller-annotations |
| Configure cookie-based affinity with Application Gateway ingress | https://learn.microsoft.com/en-us/azure/application-gateway/ingress-controller-cookie-affinity |
| Enable multi-namespace support in Application Gateway Ingress Controller | https://learn.microsoft.com/en-us/azure/application-gateway/ingress-controller-multiple-namespace-support |
| Use private IPs for internal ingress with Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/ingress-controller-private-ip |
| Reference monitoring data types for Azure Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/monitor-application-gateway-reference |
| Configure multi-site hosting on Azure Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/multiple-site-overview |
| Configure parameter-based path selection in Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/parameter-based-path-selection-portal |
| Configure Azure Application Gateway Private Link via portal, PowerShell, and CLI | https://learn.microsoft.com/en-us/azure/application-gateway/private-link-configure |
| Configure request and response buffering in Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/proxy-buffers |
| Configure HTTP header rewrite in Application Gateway portal | https://learn.microsoft.com/en-us/azure/application-gateway/rewrite-http-headers-portal |
| Configure URL and query string rewrite in Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/rewrite-url-portal |
| Create Application Gateway and set header rewrite rules | https://learn.microsoft.com/en-us/azure/application-gateway/tutorial-http-header-rewrite-powershell |
| Configure URL path-based routing in Azure Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/url-route-overview |

### Deployment
| Topic | URL |
|-------|-----|
| Configure externally managed scheduled autoscaling for Application Gateway v2 | https://learn.microsoft.com/en-us/azure/application-gateway/application-gateway-externally-managed-scheduled-autoscaling |
| Upgrade Application Gateway Ingress Controller using Helm | https://learn.microsoft.com/en-us/azure/application-gateway/ingress-controller-update-ingress-controller |
| ARM template deployment for IPv6 Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/ipv6-application-gateway-arm-template |
| Deploy Application Gateway with IPv6 frontend via portal | https://learn.microsoft.com/en-us/azure/application-gateway/ipv6-application-gateway-portal |
| Deploy Application Gateway IPv6 frontend using PowerShell | https://learn.microsoft.com/en-us/azure/application-gateway/ipv6-application-gateway-powershell |
| Migrate Azure Application Gateway and WAF from V1 to V2 | https://learn.microsoft.com/en-us/azure/application-gateway/migrate-v1-v2 |
| FAQ for Application Gateway V1 retirement and migration | https://learn.microsoft.com/en-us/azure/application-gateway/retirement-faq |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Configure Application Gateway TLS termination with Key Vault in portal | https://learn.microsoft.com/en-us/azure/application-gateway/configure-key-vault-portal |
| Integrate Application Gateway TLS termination with Key Vault via PowerShell | https://learn.microsoft.com/en-us/azure/application-gateway/configure-keyvault-ps |
| Autoscale AKS pods using Application Gateway metrics | https://learn.microsoft.com/en-us/azure/application-gateway/ingress-controller-autoscale-pods |
| Expose AKS services over HTTP/HTTPS using Application Gateway ingress | https://learn.microsoft.com/en-us/azure/application-gateway/ingress-controller-expose-service-over-http-https |
| Expose WebSocket servers through Application Gateway ingress | https://learn.microsoft.com/en-us/azure/application-gateway/ingress-controller-expose-websocket-server |
| Use Let’s Encrypt certificates with Application Gateway for AKS | https://learn.microsoft.com/en-us/azure/application-gateway/ingress-controller-letsencrypt-certificate-application-gateway |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Configure autoscaling and instance limits for Application Gateway v2 | https://learn.microsoft.com/en-us/azure/application-gateway/application-gateway-autoscaling-zone-redundant |

### Security
| Topic | URL |
|-------|-----|
| Set listener-specific SSL policies on Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/application-gateway-configure-listener-specific-ssl-policy |
| Configure Application Gateway TLS policy with PowerShell | https://learn.microsoft.com/en-us/azure/application-gateway/application-gateway-configure-ssl-policy-powershell |
| Set up end-to-end TLS on Application Gateway using PowerShell | https://learn.microsoft.com/en-us/azure/application-gateway/application-gateway-end-to-end-ssl-powershell |
| Restrict access for private Application Gateway deployments | https://learn.microsoft.com/en-us/azure/application-gateway/application-gateway-private-deployment |
| Secure Application Gateway session affinity cookie flags | https://learn.microsoft.com/en-us/azure/application-gateway/application-gateway-secure-flag-session-affinity |
| Define and manage TLS policies on Azure Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/application-gateway-ssl-policy-overview |
| Plan for TLS 1.0/1.1 retirement on Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/application-gateway-tls-version-retirement |
| Prepare backend TLS certificates for Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/certificates-for-backend-authentication |
| Configure end-to-end TLS encryption on Application Gateway v1 | https://learn.microsoft.com/en-us/azure/application-gateway/end-to-end-ssl-portal |
| Enable and use FIPS 140 mode on Application Gateway v2 | https://learn.microsoft.com/en-us/azure/application-gateway/fips |
| Add HSTS security headers with Application Gateway rewrite | https://learn.microsoft.com/en-us/azure/application-gateway/hsts-http-headers-portal |
| Configure JWT validation and access policies in Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/json-web-token-overview |
| Use Azure Key Vault certificates for Application Gateway TLS termination | https://learn.microsoft.com/en-us/azure/application-gateway/key-vault-certs |
| Deploy Application Gateway with mutual TLS passthrough via ARM template | https://learn.microsoft.com/en-us/azure/application-gateway/mutual-authentication-arm-template |
| Export trusted client CA chains for mutual TLS on Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/mutual-authentication-certificate-management |
| Implement mutual TLS authentication on Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/mutual-authentication-overview |
| Configure mutual TLS authentication on Application Gateway via portal | https://learn.microsoft.com/en-us/azure/application-gateway/mutual-authentication-portal |
| Configure mutual TLS authentication on Application Gateway with PowerShell | https://learn.microsoft.com/en-us/azure/application-gateway/mutual-authentication-powershell |
| Secure Application Gateway access using Private Link | https://learn.microsoft.com/en-us/azure/application-gateway/private-link |
| Generate self-signed certificates for Application Gateway v2 | https://learn.microsoft.com/en-us/azure/application-gateway/self-signed-certificates |
| Manage listener TLS certificates in Azure Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/ssl-certificate-management |
| Configure end-to-end TLS for Azure Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/ssl-overview |
| Protect Application Gateway with Azure DDoS Network Protection | https://learn.microsoft.com/en-us/azure/application-gateway/tutorial-protect-application-gateway-ddos |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Interpret and troubleshoot Application Gateway backend health status | https://learn.microsoft.com/en-us/azure/application-gateway/application-gateway-backend-health |
| Troubleshoot backend health problems in Azure Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/application-gateway-backend-health-troubleshooting |
| Use Application Gateway diagnostic logs for troubleshooting | https://learn.microsoft.com/en-us/azure/application-gateway/application-gateway-diagnostics |
| Resolve Azure Key Vault certificate errors in Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/application-gateway-key-vault-common-errors |
| Troubleshoot 502 Bad Gateway errors in Azure Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/application-gateway-troubleshooting-502 |
| Fix ILB ASE certificate allowlist issues in Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/create-gateway-internal-load-balancer-app-service-environment |
| Understand and fix disabled listeners in Azure Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/disabled-listeners |
| Diagnose and fix Application Gateway session affinity problems | https://learn.microsoft.com/en-us/azure/application-gateway/how-to-troubleshoot-application-gateway-session-affinity-issues |
| Interpret and troubleshoot Application Gateway HTTP response codes | https://learn.microsoft.com/en-us/azure/application-gateway/http-response-codes |
| Troubleshoot Application Gateway Ingress Controller on AKS | https://learn.microsoft.com/en-us/azure/application-gateway/ingress-controller-troubleshoot |
| Analyze Application Gateway WAF logs with Log Analytics | https://learn.microsoft.com/en-us/azure/application-gateway/log-analytics |
| Troubleshoot mutual TLS authentication on Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/mutual-authentication-troubleshooting |
| Resolve unwanted redirection to App Service URL via Application Gateway | https://learn.microsoft.com/en-us/azure/application-gateway/troubleshoot-app-service-redirection-app-service-url |

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
