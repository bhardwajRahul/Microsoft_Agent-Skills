---
name: healthcare-apis
description: Expert knowledge for Healthcare Apis development including security, limits & quotas, troubleshooting, deployment, configuration, integrations & coding patterns, best practices, and architecture & design patterns. Use when building, debugging, or optimizing Healthcare Apis applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Healthcare Apis Skill

This skill provides expert guidance for Healthcare Apis development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Architect DICOM service with Azure Data Lake Storage | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/dicom-data-lake |

### Best Practices
| Topic | URL |
|-------|-----|
| Set up disaster recovery for Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/disaster-recovery |
| Apply CMK encryption best practices for DICOM | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/customer-managed-keys |
| Follow CMK best practices for Azure FHIR service | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/customer-managed-keys |
| Run bulk $export operations for FHIR data | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/export-data |
| Apply performance best practices for Azure FHIR service | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/fhir-best-practices |
| Perform safe bulk updates on FHIR resources | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/fhir-bulk-update |
| Run and manage FHIR reindex jobs safely | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/how-to-run-a-reindex |
| Use high-throughput FHIR data import with NDJSON | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/import-data |
| Use FHIR REST API capabilities efficiently in Health Data | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/rest-api-capabilities |

### Configuration
| Topic | URL |
|-------|-----|
| Configure Azure API for FHIR for CARIN Blue Button | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/carin-implementation-guide-blue-button-tutorial |
| Configure database settings for Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/configure-database |
| Configure export settings for Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/configure-export-data |
| Configure Azure API for FHIR for Da Vinci Drug Formulary | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/davinci-drug-formulary-tutorial |
| Set up Azure API for FHIR for Da Vinci PDex | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/davinci-pdex-tutorial |
| Configure Azure API for FHIR for Da Vinci Plan Net | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/davinci-plan-net |
| Configure de-identified data export for Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/de-identified-export |
| Enable and configure diagnostic logging for Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/enable-diagnostic-logging |
| Check FHIR feature support in Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/fhir-features-supported |
| Use Azure API for FHIR REST API capabilities | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/fhir-rest-api-capabilities |
| Configure custom search parameters in Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/how-to-do-custom-search |
| Run and manage reindex jobs in Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/how-to-run-a-reindex |
| Store and manage FHIR profiles in Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/store-profiles-in-fhir |
| Add custom headers to Azure API for FHIR audit logs | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/use-custom-headers |
| Validate FHIR resources against profiles in Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/validation-against-profiles |
| Customize DICOM image location URLs in responses | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/dicom-proxy-url-support |
| Enable and query diagnostic logs for DICOM service | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/enable-diagnostic-logging |
| Export DICOM data to Azure Blob Storage via API | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/export-files |
| Store and query external metadata with DICOM STOW-RS | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/external-metadata |
| Use bulk import API to load DICOM files | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/import-files |
| Perform bulk metadata updates on DICOM files | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/update-files |
| Configure diagnostic settings for Azure Health Data events | https://learn.microsoft.com/en-us/azure/healthcare-apis/events/events-enable-diagnostic-settings |
| Understand and configure Azure Health Data events message schema | https://learn.microsoft.com/en-us/azure/healthcare-apis/events/events-message-structure |
| Configure Azure FHIR service for CARIN Blue Button tests | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/carin-implementation-guide-blue-button-tutorial |
| Configure CORS settings for Azure FHIR service | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/configure-cross-origin-resource-sharing |
| Configure FHIR $export settings and storage targets | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/configure-export-data |
| Configure FHIR import operation settings in Azure | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/configure-import-data |
| Configure $convert-data settings in Azure FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/convert-data-configuration |
| Configure Azure FHIR service for Da Vinci Drug Formulary | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/davinci-drug-formulary-tutorial |
| Set up Azure FHIR service for Da Vinci PDex compliance | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/davinci-pdex-tutorial |
| Configure Azure FHIR service for Da Vinci Plan-Net tests | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/davinci-plan-net |
| Supported FHIR features in Azure FHIR service | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/fhir-features-supported |
| Enable and query diagnostic logs for Azure FHIR service | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/fhir-service-diagnostic-logs |
| Configure FHIR versioning policy and history retention | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/fhir-versioning-policy-and-history-management |
| Define and manage custom FHIR search parameters | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/how-to-do-custom-search |
| Configure selectable FHIR search parameters for performance | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/selectable-search-parameters |
| Add custom header data to Azure FHIR audit logs | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/use-custom-headers-diagnosticlog |
| Configure and view MedTech performance metrics in Azure | https://learn.microsoft.com/en-us/azure/healthcare-apis/iot/configure-metrics |
| Enable MedTech diagnostic settings and log destinations | https://learn.microsoft.com/en-us/azure/healthcare-apis/iot/how-to-enable-diagnostic-settings |
| Configure CalculatedContent templates for MedTech mapping | https://learn.microsoft.com/en-us/azure/healthcare-apis/iot/how-to-use-calculatedcontent-templates |
| Use custom functions in MedTech device mappings | https://learn.microsoft.com/en-us/azure/healthcare-apis/iot/how-to-use-custom-functions |
| Configure IotJsonPathContent templates for MedTech mapping | https://learn.microsoft.com/en-us/azure/healthcare-apis/iot/how-to-use-iotjsonpathcontent-templates |
| Use MedTech monitoring and health check tabs | https://learn.microsoft.com/en-us/azure/healthcare-apis/iot/how-to-use-monitoring-and-health-checks-tabs |
| Configure and interpret AuditLogs and DiagnosticLogs for Health Data | https://learn.microsoft.com/en-us/azure/healthcare-apis/logging |

### Deployment
| Topic | URL |
|-------|-----|
| Deploy Azure API for FHIR with ARM template | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/azure-api-fhir-resource-manager-template |
| Deploy Azure API for FHIR using Azure CLI | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/fhir-paas-cli-quickstart |
| Move Azure API for FHIR between subscriptions | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/move-fhir-service |
| Deploy Azure API for FHIR for web app use | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/tutorial-web-app-fhir-server |
| Deploy Azure Health Data Services with Bicep templates | https://learn.microsoft.com/en-us/azure/healthcare-apis/deploy-healthcare-apis-using-bicep |
| Deploy DICOM service using Azure portal | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/deploy-dicom-services-in-azure |
| Deploy DICOM service with Azure Data Lake Storage | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/deploy-dicom-services-in-azure-data-lake |
| Deploy Azure FHIR service using Bicep templates | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/fhir-service-bicep |
| Deploy Azure FHIR service using ARM templates | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/fhir-service-resource-manager-template |
| Plan and execute migration from Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/migration-strategies |
| Deploy MedTech service with ARM templates | https://learn.microsoft.com/en-us/azure/healthcare-apis/iot/deploy-arm-template |
| Deploy MedTech service using Bicep and CLI | https://learn.microsoft.com/en-us/azure/healthcare-apis/iot/deploy-bicep-powershell-cli |
| Choose MedTech service deployment method in Azure | https://learn.microsoft.com/en-us/azure/healthcare-apis/iot/deploy-choose-method |
| Deploy MedTech service via ARM and CLI/PowerShell | https://learn.microsoft.com/en-us/azure/healthcare-apis/iot/deploy-json-powershell-cli |
| Deploy MedTech service through Azure portal | https://learn.microsoft.com/en-us/azure/healthcare-apis/iot/deploy-manual-portal |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Use $convert-data and templates in Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/convert-data |
| Copy Azure API for FHIR data into Synapse | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/copy-to-synapse |
| Execute FHIR $export operations in Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/export-data |
| Invoke Patient-everything operation in Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/patient-everything |
| Use $purge-history for FHIR resource history management | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/purge-history |
| Use FHIR search examples with Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/search-samples |
| Use the $member-match operation in Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/tutorial-member-match |
| Build a web app that calls Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/tutorial-web-app-write-web-app |
| Use DICOM service v1 API and conformance details | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/dicom-services-conformance-statement |
| Use DICOM service v2 API and conformance details | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/dicom-services-conformance-statement-v2 |
| Call DICOMweb APIs from C# with sample DICOM data | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/dicomweb-standard-apis-c-sharp |
| Use cURL to interact with DICOMweb APIs | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/dicomweb-standard-apis-curl |
| Access DICOMweb APIs using Python scripts | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/dicomweb-standard-apis-python |
| Use DICOMweb and custom APIs to manage DICOM data | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/dicomweb-standard-apis-with-dicom-services |
| Run analytics on DICOM data with Data Factory and Fabric | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/get-started-with-analytics-dicom |
| Consume DICOM Change Feed using C# client SDK | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/pull-dicom-changes-from-change-feed |
| Integrate HL7v2 to FHIR R4 using ADF $convert-data | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/convert-data-azure-data-factory |
| Copy FHIR data into Azure Synapse Analytics | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/copy-to-synapse |
| Call $docref operation in Azure FHIR service | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/fhir-docref |
| Use $expand ValueSet operation in Azure FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/fhir-expand |
| Use Patient-everything to retrieve patient-related FHIR data | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/patient-everything |
| Use $purge-history operation in Azure FHIR service | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/purge-history |
| Store and manage FHIR profiles in Azure FHIR service | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/store-profiles-in-fhir |
| Access Azure Health Data Services APIs with cURL | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/using-curl |
| Access Azure Health Data Services using VS Code REST Client | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/using-rest-client |
| Validate FHIR resources against profiles in Azure | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/validation-against-profiles |
| Route Azure IoT Hub device messages to MedTech | https://learn.microsoft.com/en-us/azure/healthcare-apis/iot/device-messages-through-iot-hub |
| Use MedTech scenario-based device-to-FHIR mappings | https://learn.microsoft.com/en-us/azure/healthcare-apis/iot/overview-of-samples |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Configure autoscale behavior for Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/autoscale-azure-api-fhir |
| Understand autoscale behavior and limits for FHIR service | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/autoscale |

### Security
| Topic | URL |
|-------|-----|
| Configure authentication and authorization for Azure Health Data Services | https://learn.microsoft.com/en-us/azure/healthcare-apis/authentication-authorization |
| Configure Microsoft Entra identity for Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/azure-active-directory-identity-configuration |
| Bulk delete FHIR resources with required roles and headers | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/bulk-delete-operation |
| Configure Azure RBAC for Azure API for FHIR data plane | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/configure-azure-rbac |
| Configure CORS for Azure API for FHIR securely | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/configure-cross-origin-resource-sharing |
| Configure local RBAC with secondary Entra tenant for Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/configure-local-rbac |
| Configure Private Link for Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/configure-private-link |
| Configure customer-managed keys for Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/customer-managed-key |
| Register Entra applications for Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/fhir-app-registration |
| Find identity object IDs for Azure API for FHIR auth | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/find-identity-object-ids |
| Get Azure API for FHIR access token via CLI | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/get-healthcare-apis-access-token-cli |
| Use built-in Azure Policy for Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/policy-reference |
| Register confidential client app for Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/register-confidential-azure-ad-client-app |
| Register public client app for Azure API for FHIR deployment | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/register-public-azure-ad-client-app |
| Register resource (API) app for Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/register-resource-azure-ad-client-app |
| Register service client app for Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/register-service-azure-ad-client-app |
| Apply regulatory compliance policies to Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/security-controls-policy |
| Enable SMART on FHIR apps with Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/smart-on-fhir |
| Register public client app for Azure API for FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/tutorial-web-app-public-app-reg |
| Use built-in Azure Policies for Health Data compliance | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-health-data-services-policy-reference |
| Configure Azure RBAC roles for FHIR service data access | https://learn.microsoft.com/en-us/azure/healthcare-apis/configure-azure-rbac |
| Assign Azure RBAC roles via CLI and REST for Health Data | https://learn.microsoft.com/en-us/azure/healthcare-apis/configure-azure-rbac-using-scripts |
| Configure Private Link endpoints for Health Data Services | https://learn.microsoft.com/en-us/azure/healthcare-apis/configure-private-link |
| Configure CORS settings for DICOM service APIs | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/configure-cross-origin-resource-sharing |
| Configure customer-managed keys for DICOM encryption | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/configure-customer-managed-keys |
| Set up Azure RBAC for DICOM service access | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/dicom-configure-azure-rbac |
| Register client applications for Azure DICOM service | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/dicom-register-application |
| Get and use access tokens for Azure DICOM service | https://learn.microsoft.com/en-us/azure/healthcare-apis/dicom/get-access-token |
| Use Azure AD B2C to secure Azure FHIR service | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/azure-ad-b2c-setup |
| Configure Entra External ID access for Azure FHIR service | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/azure-entra-external-id-setup |
| Configure customer-managed keys for Azure FHIR encryption | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/configure-customer-managed-keys |
| Configure multiple identity providers for Azure FHIR service | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/configure-identity-providers |
| Configure de-identified FHIR data export for privacy | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/deidentified-export |
| Use bulk delete operations securely in FHIR service | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/fhir-bulk-delete |
| Enable SMART on FHIR security for FHIR service apps | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/smart-on-fhir |
| Obtain access tokens for FHIR and DICOM services | https://learn.microsoft.com/en-us/azure/healthcare-apis/get-access-token |
| Configure network access security for Azure Health Data Services | https://learn.microsoft.com/en-us/azure/healthcare-apis/network-access-security |
| Register client applications for Azure Health Data Services in Entra ID | https://learn.microsoft.com/en-us/azure/healthcare-apis/register-application |
| Automate Entra ID app registration for Health Data Services via CLI and REST | https://learn.microsoft.com/en-us/azure/healthcare-apis/register-application-cli-rest |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Validate and troubleshoot Azure API for FHIR access tokens | https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/azure-api-fhir-access-token-validation |
| Troubleshoot Azure Health Data events issues | https://learn.microsoft.com/en-us/azure/healthcare-apis/events/events-troubleshooting-guide |
| Troubleshoot $convert-data issues in Azure FHIR | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/convert-data-troubleshoot |
| Troubleshoot identity provider issues in Azure FHIR service | https://learn.microsoft.com/en-us/azure/healthcare-apis/fhir/troubleshoot-identity-provider-configuration |
| Debug MedTech device mappings with Mapping debugger | https://learn.microsoft.com/en-us/azure/healthcare-apis/iot/how-to-use-mapping-debugger |
| Diagnose and fix MedTech service deployment errors | https://learn.microsoft.com/en-us/azure/healthcare-apis/iot/troubleshoot-errors-deployment |
| Troubleshoot MedTech service errors using service logs | https://learn.microsoft.com/en-us/azure/healthcare-apis/iot/troubleshoot-errors-logs |
| Resolve known issues in Azure Health Data Services | https://learn.microsoft.com/en-us/azure/healthcare-apis/known-issues |

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
