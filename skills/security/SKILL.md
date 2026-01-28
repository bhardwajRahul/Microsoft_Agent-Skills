---
name: security
description: Expert knowledge for Security development including security, integrations & coding patterns, configuration, best practices, troubleshooting, deployment, and architecture & design patterns. Use when building, debugging, or optimizing Security applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Security Skill

This skill provides expert guidance for Security development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Choose the right Azure key management service | https://learn.microsoft.com/en-us/azure/security/fundamentals/key-management-choose |

### Best Practices
| Topic | URL |
|-------|-----|
| Design Azure backup and restore plans for ransomware | https://learn.microsoft.com/en-us/azure/security/fundamentals/backup-plan-to-protect-against-ransomware |
| Implement Azure data security and encryption best practices | https://learn.microsoft.com/en-us/azure/security/fundamentals/data-encryption-best-practices |
| Apply Azure SQL database security checklist controls | https://learn.microsoft.com/en-us/azure/security/fundamentals/database-security-checklist |
| Apply security best practices to Azure IaaS VMs | https://learn.microsoft.com/en-us/azure/security/fundamentals/iaas |
| Apply Azure identity and access security best practices | https://learn.microsoft.com/en-us/azure/security/fundamentals/identity-management-best-practices |
| Apply Azure network security best practices | https://learn.microsoft.com/en-us/azure/security/fundamentals/network-best-practices |
| Design and operate secure Azure PaaS applications | https://learn.microsoft.com/en-us/azure/security/fundamentals/paas-deployments |
| Apply Azure best practices to prepare for ransomware | https://learn.microsoft.com/en-us/azure/security/fundamentals/ransomware-prepare |
| Use Azure Firewall Premium to mitigate ransomware | https://learn.microsoft.com/en-us/azure/security/fundamentals/ransomware-protection-with-azure-firewall |
| Implement key steps to secure Entra ID tenants | https://learn.microsoft.com/en-us/azure/security/fundamentals/steps-secure-identity |

### Configuration
| Topic | URL |
|-------|-----|
| Reference Azure service domains and API endpoints | https://learn.microsoft.com/en-us/azure/security/fundamentals/azure-domains |
| Identify Azure services supporting customer-managed keys | https://learn.microsoft.com/en-us/azure/security/fundamentals/encryption-customer-managed-keys-support |
| Configure Azure-native features against ransomware attacks | https://learn.microsoft.com/en-us/azure/security/fundamentals/ransomware-features-resources |

### Deployment
| Topic | URL |
|-------|-----|
| Check Azure security feature availability across commercial and US Gov clouds | https://learn.microsoft.com/en-us/azure/security/fundamentals/feature-availability |
| Adapt to upcoming Azure managed TLS changes | https://learn.microsoft.com/en-us/azure/security/fundamentals/managed-tls-changes |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Configure Microsoft Antimalware in Azure with PowerShell | https://learn.microsoft.com/en-us/azure/security/fundamentals/antimalware-code-samples |

### Security
| Topic | URL |
|-------|-----|
| Deploy and operate secure Azure applications using SDL | https://learn.microsoft.com/en-us/azure/security/develop/secure-deploy |
| Design secure Azure applications using SDL guidance | https://learn.microsoft.com/en-us/azure/security/develop/secure-design |
| Apply secure development lifecycle practices on Azure | https://learn.microsoft.com/en-us/azure/security/develop/secure-dev-overview |
| Develop secure Azure applications with implementation controls | https://learn.microsoft.com/en-us/azure/security/develop/secure-develop |
| Implement auditing and logging mitigations from threat models | https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool-auditing-and-logging |
| Implement authentication mitigations from threat models | https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool-authentication |
| Mitigate authorization threats identified in threat models | https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool-authorization |
| Mitigate communication security threats from threat models | https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool-communication-security |
| Apply configuration management mitigations from threat models | https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool-configuration-management |
| Implement cryptography mitigations for modeled threats | https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool-cryptography |
| Mitigate exception management threats in applications | https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool-exception-management |
| Implement input validation mitigations from threat models | https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool-input-validation |
| Apply threat mitigations using Microsoft Threat Modeling Tool | https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool-mitigations |
| Protect sensitive data using threat model mitigations | https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool-sensitive-data |
| Apply session management mitigations from threat models | https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool-session-management |
| Use Azure service certificate authority details securely | https://learn.microsoft.com/en-us/azure/security/fundamentals/azure-certificate-authority-details |
| Harden Azure Marketplace images before publishing | https://learn.microsoft.com/en-us/azure/security/fundamentals/azure-marketplace-images |
| Configure alternate email notifications for Customer Lockbox | https://learn.microsoft.com/en-us/azure/security/fundamentals/customer-lockbox-alternative-email |
| Control Microsoft support access with Customer Lockbox | https://learn.microsoft.com/en-us/azure/security/fundamentals/customer-lockbox-overview |
| Learn how Microsoft secures the Azure production network | https://learn.microsoft.com/en-us/azure/security/fundamentals/infrastructure-operations |
| Use Azure SQL Database security capabilities to protect data | https://learn.microsoft.com/en-us/azure/security/fundamentals/infrastructure-sql |
| Configure Azure security logging and auditing for workloads | https://learn.microsoft.com/en-us/azure/security/fundamentals/log-audit |
| Apply operational security best practices to Azure assets | https://learn.microsoft.com/en-us/azure/security/fundamentals/operational-best-practices |
| Use Azure operational security checklist before deployment | https://learn.microsoft.com/en-us/azure/security/fundamentals/operational-checklist |
| Apply security best practices to Azure App Service PaaS apps | https://learn.microsoft.com/en-us/azure/security/fundamentals/paas-applications-using-app-services |
| Harden Azure SQL Database and Synapse for PaaS workloads | https://learn.microsoft.com/en-us/azure/security/fundamentals/paas-applications-using-sql |
| Secure PaaS applications using Azure Storage features | https://learn.microsoft.com/en-us/azure/security/fundamentals/paas-applications-using-storage |
| Understand secure access to the Azure production network | https://learn.microsoft.com/en-us/azure/security/fundamentals/production-network |
| Understand Azure operational access to customer data | https://learn.microsoft.com/en-us/azure/security/fundamentals/protection-customer-data |
| Implement secure Azure Service Fabric clusters and apps | https://learn.microsoft.com/en-us/azure/security/fundamentals/service-fabric-best-practices |
| Mitigate Azure subdomain takeover risks with DNS and App Service | https://learn.microsoft.com/en-us/azure/security/fundamentals/subdomain-takeover |
| Understand Trusted Hardware Identity Management in Azure | https://learn.microsoft.com/en-us/azure/security/fundamentals/trusted-hardware-identity-management |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Resolve common Customer Lockbox for Azure issues | https://learn.microsoft.com/en-us/azure/security/fundamentals/customer-lockbox-faq |
| Diagnose and respond to ransomware incidents in Azure | https://learn.microsoft.com/en-us/azure/security/fundamentals/ransomware-detect-respond |

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
