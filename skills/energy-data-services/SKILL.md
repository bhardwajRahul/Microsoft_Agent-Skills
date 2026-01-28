---
name: energy-data-services
description: Expert knowledge for Energy Data Services development including security, limits & quotas, configuration, deployment, integrations & coding patterns, and troubleshooting. Use when building, debugging, or optimizing Energy Data Services applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Energy Data Services Skill

This skill provides expert guidance for Energy Data Services development. It combines local quick-reference content with remote documentation fetching capabilities.

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

### Configuration
| Topic | URL |
|-------|-----|
| Configure and manage data partitions in Azure Data Manager for Energy | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-add-more-data-partitions |
| Enable External Data Sources for Azure Data Manager for Energy | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-enable-external-data-sources |
| Enable Reservoir DDMS on Azure Data Manager for Energy | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-enable-reservoir-ddms |
| Register External Data Sources with Azure Data Manager for Energy | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-register-external-data-sources |

### Deployment
| Topic | URL |
|-------|-----|
| Deploy Geospatial Consumption Zone on Azure Data Manager for Energy | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-deploy-gcz |
| Deploy OSDU Admin UI on Azure Data Manager for Energy | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-deploy-osdu-admin-ui |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Integrate Airflow task logs with Azure Monitor for Azure Data Manager for Energy | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-integrate-airflow-logs-with-azure-monitor |
| Integrate Elasticsearch logs with Azure Monitor for Azure Data Manager for Energy | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-integrate-elastic-logs-with-azure-monitor |
| Export OSDU service logs from Azure Data Manager for Energy to Azure Monitor | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-integrate-osdu-service-logs-with-azure-monitor |
| Upload large files via Azure Data Manager for Energy File service API | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-upload-large-files-using-file-service |
| Work with Petrel data via Petrel DDMS APIs | https://learn.microsoft.com/en-us/azure/energy-data-services/tutorial-petrel-ddms |
| Access reservoir data using Reservoir DDMS REST APIs | https://learn.microsoft.com/en-us/azure/energy-data-services/tutorial-reservoir-ddms-apis |
| Use Reservoir DDMS websocket endpoints in PowerShell | https://learn.microsoft.com/en-us/azure/energy-data-services/tutorial-reservoir-ddms-websocket |
| Integrate with Rock and Fluid Samples (RAFS) DDMS APIs | https://learn.microsoft.com/en-us/azure/energy-data-services/tutorial-rock-and-fluid-samples-ddms |
| Call Seismic DDMS REST APIs with cURL | https://learn.microsoft.com/en-us/azure/energy-data-services/tutorial-seismic-ddms |
| Use sdutil CLI to integrate with Seismic Store | https://learn.microsoft.com/en-us/azure/energy-data-services/tutorial-seismic-ddms-sdutil |
| Manage well records with Well Delivery DDMS APIs | https://learn.microsoft.com/en-us/azure/energy-data-services/tutorial-well-delivery-ddms |
| Use Wellbore DDMS APIs for well data | https://learn.microsoft.com/en-us/azure/energy-data-services/tutorial-wellbore-ddms |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Review Developer vs Standard tier capabilities in Azure Data Manager for Energy | https://learn.microsoft.com/en-us/azure/energy-data-services/concepts-tier-details |

### Security
| Topic | URL |
|-------|-----|
| Understand authentication and tokens in Azure Data Manager for Energy | https://learn.microsoft.com/en-us/azure/energy-data-services/concepts-authentication |
| Understand entitlement and access concepts in Azure Data Manager for Energy | https://learn.microsoft.com/en-us/azure/energy-data-services/concepts-entitlements |
| Use Customer Lockbox with Azure Data Manager for Energy support access | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-create-lockbox |
| Configure CORS policies for Azure Data Manager for Energy | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-enable-cors |
| Enable legal tags for restricted country-of-origin data in Azure Data Manager for Energy | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-enable-legal-tags-restricted-country-of-origin |
| Generate service principal and user auth tokens for Azure Data Manager for Energy | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-generate-auth-token |
| Manage ACLs on data records in Azure Data Manager for Energy | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-manage-acls |
| Configure and use audit logs in Azure Data Manager for Energy | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-manage-audit-logs |
| Configure data security and encryption, including customer-managed keys, in Azure Data Manager for Energy | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-manage-data-security-and-encryption |
| Configure and manage legal tags in Azure Data Manager for Energy | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-manage-legal-tags |
| Manage users and OSDU groups in Azure Data Manager for Energy | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-manage-users |
| Secure Azure Data Manager for Energy APIs with API Management | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-secure-apis |
| Create private endpoints for Azure Data Manager for Energy using Private Link | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-set-up-private-links |
| Use managed identities to access Azure Data Manager for Energy APIs | https://learn.microsoft.com/en-us/azure/energy-data-services/how-to-use-managed-identity |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot manifest ingestion in Azure Data Manager for Energy using Airflow logs | https://learn.microsoft.com/en-us/azure/energy-data-services/troubleshoot-manifest-ingestion |

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
