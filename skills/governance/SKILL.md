---
name: governance
description: Expert knowledge for Governance development including security, deployment, integrations & coding patterns, configuration, architecture & design patterns, troubleshooting, best practices, limits & quotas, and comparing x vs. y. Use when building, debugging, or optimizing Governance applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Governance Skill

This skill provides expert guidance for Governance development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Architecture of Azure Security Benchmark blueprint foundation | https://learn.microsoft.com/en-us/azure/governance/blueprints/samples/azure-security-benchmark-foundation/ |
| Understand CAF Foundation blueprint architecture | https://learn.microsoft.com/en-us/azure/governance/blueprints/samples/caf-foundation/ |
| Review CAF Migration landing zone architecture | https://learn.microsoft.com/en-us/azure/governance/blueprints/samples/caf-migrate-landing-zone/ |
| Architecture for ISO 27001 ASE/SQL workload blueprint | https://learn.microsoft.com/en-us/azure/governance/blueprints/samples/iso27001-ase-sql-workload/ |
| ISO 27001 shared services blueprint architecture patterns | https://learn.microsoft.com/en-us/azure/governance/blueprints/samples/iso27001-shared/ |
| Design and group Azure Policy definitions into initiatives | https://learn.microsoft.com/en-us/azure/governance/policy/samples/pattern-group-with-initiative |

### Best Practices
| Topic | URL |
|-------|-----|
| Evaluate impact before deploying new Azure policies | https://learn.microsoft.com/en-us/azure/governance/policy/concepts/evaluate-impact |
| Author Azure Policy rules for array resource properties | https://learn.microsoft.com/en-us/azure/governance/policy/how-to/author-policies-for-arrays |
| Apply the count operator in Azure Policy rules | https://learn.microsoft.com/en-us/azure/governance/policy/samples/pattern-count-operator |
| Deploy resources using Azure Policy deployIfNotExists | https://learn.microsoft.com/en-us/azure/governance/policy/samples/pattern-deploy-resources |
| Implement Azure Policy patterns for resource tags | https://learn.microsoft.com/en-us/azure/governance/policy/samples/pattern-tags |
| Use the value operator in Azure Policy definitions | https://learn.microsoft.com/en-us/azure/governance/policy/samples/pattern-value-operator |
| Avoid throttling in Azure Resource Graph queries | https://learn.microsoft.com/en-us/azure/governance/resource-graph/concepts/guidance-for-throttled-requests |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Compare ARG GET/LIST API with ARG Query service | https://learn.microsoft.com/en-us/azure/governance/resource-graph/concepts/get-list-query-service-differences |

### Configuration
| Topic | URL |
|-------|-----|
| Import and export Azure blueprints via PowerShell | https://learn.microsoft.com/en-us/azure/governance/blueprints/how-to/import-export-ps |
| Manage blueprint assignments with PowerShell | https://learn.microsoft.com/en-us/azure/governance/blueprints/how-to/manage-assignments-ps |
| Use Azure Blueprints functions in definitions | https://learn.microsoft.com/en-us/azure/governance/blueprints/reference/blueprint-functions |
| Configure and deploy Azure Security Benchmark blueprint sample | https://learn.microsoft.com/en-us/azure/governance/blueprints/samples/azure-security-benchmark-foundation/deploy |
| Deploy and parameterize ISM PROTECTED blueprint sample | https://learn.microsoft.com/en-us/azure/governance/blueprints/samples/ism-protected/deploy |
| Deploy ISO 27001 shared services blueprint with parameters | https://learn.microsoft.com/en-us/azure/governance/blueprints/samples/iso27001-shared/deploy |
| Create Azure Policy assignment using Bicep | https://learn.microsoft.com/en-us/azure/governance/policy/assign-policy-bicep |
| Create Azure Policy assignment with ARM template | https://learn.microsoft.com/en-us/azure/governance/policy/assign-policy-template |
| Create Azure Policy assignment with Terraform | https://learn.microsoft.com/en-us/azure/governance/policy/assign-policy-terraform |
| Understand and configure Azure Policy attestation JSON | https://learn.microsoft.com/en-us/azure/governance/policy/concepts/attestation-structure |
| Configure Azure Policy remediation task definitions | https://learn.microsoft.com/en-us/azure/governance/policy/concepts/remediation-structure |
| Retrieve and interpret Azure Policy compliance data | https://learn.microsoft.com/en-us/azure/governance/policy/how-to/get-compliance-data |
| Create and run Azure Policy remediation tasks | https://learn.microsoft.com/en-us/azure/governance/policy/how-to/remediate-resources |
| Map Azure Policy guest configuration packages and modules | https://learn.microsoft.com/en-us/azure/governance/policy/samples/built-in-packages |
| Create and manage Azure Policy definitions and assignments | https://learn.microsoft.com/en-us/azure/governance/policy/tutorials/create-and-manage |
| Author custom Azure Policy definitions | https://learn.microsoft.com/en-us/azure/governance/policy/tutorials/create-custom-policy-definition |
| Disallow specific Azure resource types with Policy | https://learn.microsoft.com/en-us/azure/governance/policy/tutorials/disallowed-resources |
| Enforce tag governance using Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/tutorials/govern-tags |
| Add user-assigned identities via Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/tutorials/modify-virtual-machine-identity |
| Use keyboard shortcuts in Azure Resource Graph Explorer | https://learn.microsoft.com/en-us/azure/governance/resource-graph/reference/keyboard-shortcuts |
| Reference of Azure Resource Graph supported resource types | https://learn.microsoft.com/en-us/azure/governance/resource-graph/reference/supported-tables-resources |
| Define Resource Graph shared queries using Bicep | https://learn.microsoft.com/en-us/azure/governance/resource-graph/shared-query-bicep |
| Deploy Resource Graph shared queries with ARM templates | https://learn.microsoft.com/en-us/azure/governance/resource-graph/shared-query-template |
| Manage and share Resource Graph queries in Azure portal | https://learn.microsoft.com/en-us/azure/governance/resource-graph/tutorials/create-share-query |

### Deployment
| Topic | URL |
|-------|-----|
| Control blueprint artifact deployment sequence | https://learn.microsoft.com/en-us/azure/governance/blueprints/concepts/sequencing-order |
| Update existing blueprint assignments in portal | https://learn.microsoft.com/en-us/azure/governance/blueprints/how-to/update-existing-assignments |
| Deploy CAF Foundation blueprint sample | https://learn.microsoft.com/en-us/azure/governance/blueprints/samples/caf-foundation/deploy |
| Deploy CAF Migration landing zone blueprint | https://learn.microsoft.com/en-us/azure/governance/blueprints/samples/caf-migrate-landing-zone/deploy |
| Deploy ISO 27001 ASE/SQL blueprint sample | https://learn.microsoft.com/en-us/azure/governance/blueprints/samples/iso27001-ase-sql-workload/deploy |
| Deploy SWIFT CSP-CSCF v2020 blueprint sample | https://learn.microsoft.com/en-us/azure/governance/blueprints/samples/swift-2020/deploy |
| Design Azure Policy as Code deployment workflows | https://learn.microsoft.com/en-us/azure/governance/policy/concepts/policy-as-code |
| Plan migration from Automanage Best Practices to Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/how-to/migrate-from-automanage-best-practices |
| Apply safe deployment practices to Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/how-to/policy-safe-deployment-practices |
| Enforce Azure Policy in Azure DevOps pipelines | https://learn.microsoft.com/en-us/azure/governance/policy/tutorials/policy-devops-pipelines |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Manage Azure Blueprints with Azure CLI commands | https://learn.microsoft.com/en-us/azure/governance/blueprints/create-blueprint-azurecli |
| Create and assign Azure Blueprints using PowerShell | https://learn.microsoft.com/en-us/azure/governance/blueprints/create-blueprint-powershell |
| Use Azure Blueprints through the REST API | https://learn.microsoft.com/en-us/azure/governance/blueprints/create-blueprint-rest-api |
| Run Azure Resource Graph queries for management groups | https://learn.microsoft.com/en-us/azure/governance/management-groups/resource-graph-samples |
| Integrate Azure Policy state changes with Event Grid | https://learn.microsoft.com/en-us/azure/governance/policy/concepts/event-overview |
| Govern Kubernetes clusters with Azure Policy and Gatekeeper | https://learn.microsoft.com/en-us/azure/governance/policy/concepts/policy-for-kubernetes |
| Export Azure Policy resources to GitHub and scripts | https://learn.microsoft.com/en-us/azure/governance/policy/how-to/export-resources |
| Use Azure Policy VS Code extension for aliases and exports | https://learn.microsoft.com/en-us/azure/governance/policy/how-to/extension-for-vscode |
| Programmatically manage Azure policies via CLI, PowerShell, REST | https://learn.microsoft.com/en-us/azure/governance/policy/how-to/programmatically-create |
| Configure effects in Azure Policy definitions | https://learn.microsoft.com/en-us/azure/governance/policy/samples/pattern-effect-details |
| Use field properties in Azure Policy conditions | https://learn.microsoft.com/en-us/azure/governance/policy/samples/pattern-fields |
| Use logical operators in Azure Policy definitions | https://learn.microsoft.com/en-us/azure/governance/policy/samples/pattern-logical-operators |
| Define and use parameters in Azure Policy definitions | https://learn.microsoft.com/en-us/azure/governance/policy/samples/pattern-parameters |
| Query Azure Policy resources with Azure Resource Graph | https://learn.microsoft.com/en-us/azure/governance/policy/samples/resource-graph-samples |
| Query Azure Policy guest configuration with Resource Graph | https://learn.microsoft.com/en-us/azure/governance/policy/samples/resource-graph-samples-guest-configuration |
| Route Azure Policy state changes to Event Grid | https://learn.microsoft.com/en-us/azure/governance/policy/tutorials/route-state-change-events |
| Create monitoring alerts from Resource Graph queries | https://learn.microsoft.com/en-us/azure/governance/resource-graph/alerts-query-quickstart |
| Query Azure resource changes at scale with Resource Graph | https://learn.microsoft.com/en-us/azure/governance/resource-graph/changes/get-resource-changes |
| Query Azure Resource Graph using Azure CLI | https://learn.microsoft.com/en-us/azure/governance/resource-graph/first-query-azurecli |
| Run Azure Resource Graph queries in Azure portal | https://learn.microsoft.com/en-us/azure/governance/resource-graph/first-query-portal |
| Query Azure Resource Graph with PowerShell cmdlets | https://learn.microsoft.com/en-us/azure/governance/resource-graph/first-query-powershell |
| Call Azure Resource Graph via REST API | https://learn.microsoft.com/en-us/azure/governance/resource-graph/first-query-rest-api |
| Create Azure Resource Graph shared queries with CLI | https://learn.microsoft.com/en-us/azure/governance/resource-graph/shared-query-azure-cli |
| Create Azure Resource Graph shared queries in PowerShell | https://learn.microsoft.com/en-us/azure/governance/resource-graph/shared-query-azure-powershell |
| Automate Azure Resource Graph queries with Logic Apps | https://learn.microsoft.com/en-us/azure/governance/resource-graph/tutorials/logic-app-calling-arg |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Use ARG GET/LIST API to reduce throttling | https://learn.microsoft.com/en-us/azure/governance/resource-graph/concepts/azure-resource-graph-get-list-api |
| Handle large Azure Resource Graph query result sets | https://learn.microsoft.com/en-us/azure/governance/resource-graph/concepts/work-with-data |
| Paginate Azure Resource Graph query results in PowerShell | https://learn.microsoft.com/en-us/azure/governance/resource-graph/paginate-powershell |
| Use Power BI connector for Azure Resource Graph queries | https://learn.microsoft.com/en-us/azure/governance/resource-graph/power-bi-connector-quickstart |

### Security
| Topic | URL |
|-------|-----|
| Understand security stages of blueprint deployment | https://learn.microsoft.com/en-us/azure/governance/blueprints/concepts/deployment-stages |
| Configure resource locking in Azure Blueprints | https://learn.microsoft.com/en-us/azure/governance/blueprints/concepts/resource-locking |
| Set up environment for Blueprint Operator role | https://learn.microsoft.com/en-us/azure/governance/blueprints/how-to/configure-for-blueprint-operator |
| Apply Canada Federal PBMM controls with Azure blueprint | https://learn.microsoft.com/en-us/azure/governance/blueprints/samples/canada-federal-pbmm |
| Use ISM PROTECTED blueprint for Australian compliance | https://learn.microsoft.com/en-us/azure/governance/blueprints/samples/ism-protected/ |
| Control mapping for ISM PROTECTED Azure blueprint | https://learn.microsoft.com/en-us/azure/governance/blueprints/samples/ism-protected/control-mapping |
| Assess ISO 27001 controls with Azure blueprint | https://learn.microsoft.com/en-us/azure/governance/blueprints/samples/iso-27001-2013 |
| Security control mapping for ISO 27001 ASE/SQL blueprint | https://learn.microsoft.com/en-us/azure/governance/blueprints/samples/iso27001-ase-sql-workload/control-mapping |
| Control mapping for ISO 27001 shared services blueprint | https://learn.microsoft.com/en-us/azure/governance/blueprints/samples/iso27001-shared/control-mapping |
| Map SWIFT CSP-CSCF controls to Azure Policy | https://learn.microsoft.com/en-us/azure/governance/blueprints/samples/swift-2020/control-mapping |
| Protect Azure Blueprint-deployed resources with locks | https://learn.microsoft.com/en-us/azure/governance/blueprints/tutorials/protect-new-resources |
| Configure hierarchy settings to protect Azure resource tree | https://learn.microsoft.com/en-us/azure/governance/management-groups/how-to/protect-resource-hierarchy |
| Azure Policy mappings for Australian ISM PROTECTED | https://learn.microsoft.com/en-us/azure/governance/policy/samples/australia-ism |
| Use Microsoft cloud security benchmark in Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/samples/azure-security-benchmark |
| Azure Policy mappings for Canada Federal PBMM | https://learn.microsoft.com/en-us/azure/governance/policy/samples/canada-federal-pbmm |
| Azure Policy mappings for CIS Azure Benchmark 1.1.0 | https://learn.microsoft.com/en-us/azure/governance/policy/samples/cis-azure-1-1-0 |
| Azure Policy mappings for CIS Azure Benchmark 1.3.0 | https://learn.microsoft.com/en-us/azure/governance/policy/samples/cis-azure-1-3-0 |
| Azure Policy mappings for CIS Azure Benchmark 1.4.0 | https://learn.microsoft.com/en-us/azure/governance/policy/samples/cis-azure-1-4-0 |
| Azure Policy mappings for CIS Azure Benchmark 2.0.0 | https://learn.microsoft.com/en-us/azure/governance/policy/samples/cis-azure-2-0-0 |
| Apply CIS benchmarks to AlmaLinux with Azure Machine Configuration | https://learn.microsoft.com/en-us/azure/governance/policy/samples/cis-linux/alma-ado |
| Apply CIS benchmarks to Debian Linux with Azure Machine Configuration | https://learn.microsoft.com/en-us/azure/governance/policy/samples/cis-linux/debian-ado |
| Apply CIS benchmarks to Oracle Linux with Azure Machine Configuration | https://learn.microsoft.com/en-us/azure/governance/policy/samples/cis-linux/oracle-ado |
| Apply CIS benchmarks to RHEL with Azure Machine Configuration | https://learn.microsoft.com/en-us/azure/governance/policy/samples/cis-linux/rhel-ado |
| Apply CIS benchmarks to Rocky Linux with Azure Machine Configuration | https://learn.microsoft.com/en-us/azure/governance/policy/samples/cis-linux/rocky-ado |
| Apply CIS benchmarks to SUSE Linux Enterprise with Azure Machine Configuration | https://learn.microsoft.com/en-us/azure/governance/policy/samples/cis-linux/suse-ado |
| Apply CIS benchmarks to Ubuntu with Azure Machine Configuration | https://learn.microsoft.com/en-us/azure/governance/policy/samples/cis-linux/ubuntu-ado |
| Map CMMC Level 3 controls to Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/samples/cmmc-l3 |
| Align Azure Policy with FedRAMP High controls | https://learn.microsoft.com/en-us/azure/governance/policy/samples/fedramp-high |
| Align Azure Policy with FedRAMP Moderate controls | https://learn.microsoft.com/en-us/azure/governance/policy/samples/fedramp-moderate |
| Use Microsoft cloud security benchmark with Azure Policy (Gov) | https://learn.microsoft.com/en-us/azure/governance/policy/samples/gov-azure-security-benchmark |
| Map CIS Azure Foundations 1.1.0 to Azure Policy (Gov) | https://learn.microsoft.com/en-us/azure/governance/policy/samples/gov-cis-azure-1-1-0 |
| Map CIS Azure Foundations 1.3.0 to Azure Policy (Gov) | https://learn.microsoft.com/en-us/azure/governance/policy/samples/gov-cis-azure-1-3-0 |
| Implement CMMC Level 3 controls with Azure Policy (Gov) | https://learn.microsoft.com/en-us/azure/governance/policy/samples/gov-cmmc-l3 |
| Implement FedRAMP High controls using Azure Policy (Gov) | https://learn.microsoft.com/en-us/azure/governance/policy/samples/gov-fedramp-high |
| Implement FedRAMP Moderate controls using Azure Policy (Gov) | https://learn.microsoft.com/en-us/azure/governance/policy/samples/gov-fedramp-moderate |
| Map IRS 1075 Sept 2016 controls to Azure Policy (Gov) | https://learn.microsoft.com/en-us/azure/governance/policy/samples/gov-irs-1075-sept2016 |
| Implement ISO 27001:2013 controls with Azure Policy (Gov) | https://learn.microsoft.com/en-us/azure/governance/policy/samples/gov-iso-27001 |
| Implement NIST SP 800-171 R2 controls with Azure Policy (Gov) | https://learn.microsoft.com/en-us/azure/governance/policy/samples/gov-nist-sp-800-171-r2 |
| Map NIST SP 800-53 Rev. 4 controls to Azure Policy (Gov) | https://learn.microsoft.com/en-us/azure/governance/policy/samples/gov-nist-sp-800-53-r4 |
| Map NIST SP 800-53 Rev. 5 controls to Azure Policy (Gov) | https://learn.microsoft.com/en-us/azure/governance/policy/samples/gov-nist-sp-800-53-r5 |
| Align SOC 2 controls with Azure Policy (Gov) | https://learn.microsoft.com/en-us/azure/governance/policy/samples/gov-soc-2 |
| Use CIS security benchmarks for Linux via Azure Machine Configuration | https://learn.microsoft.com/en-us/azure/governance/policy/samples/guest-configuration-baseline-cis-linux |
| Use Azure Policy guest configuration baseline for Docker hosts | https://learn.microsoft.com/en-us/azure/governance/policy/samples/guest-configuration-baseline-docker |
| Use Azure Policy guest configuration baseline for Linux | https://learn.microsoft.com/en-us/azure/governance/policy/samples/guest-configuration-baseline-linux |
| Apply Azure Security Baseline via guest configuration for Windows Server | https://learn.microsoft.com/en-us/azure/governance/policy/samples/guest-configuration-baseline-windows |
| Apply Azure Security Baseline via guest configuration for Windows Server 2025 | https://learn.microsoft.com/en-us/azure/governance/policy/samples/guest-configuration-baseline-windows-server-2025 |
| Map HIPAA HITRUST controls to Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/samples/hipaa-hitrust |
| Implement IRS 1075 controls with Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/samples/irs-1075-sept2016 |
| Map ISO 27001:2013 controls to Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/samples/iso-27001 |
| Apply Sovereignty Baseline Confidential policies via Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/samples/mcfs-baseline-confidential |
| Apply Sovereignty Baseline Global policies via Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/samples/mcfs-baseline-global |
| Align NIST SP 800-171 R2 controls with Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/samples/nist-sp-800-171-r2 |
| Map NIST SP 800-53 Rev. 4 controls to Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/samples/nist-sp-800-53-r4 |
| Map NIST SP 800-53 Rev. 5 controls to Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/samples/nist-sp-800-53-r5 |
| Implement NL BIO Cloud Theme controls with Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/samples/nl-bio-cloud-theme |
| Map PCI DSS 3.2.1 controls to Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/samples/pci-dss-3-2-1 |
| Map PCI DSS v4.0 controls to Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/samples/pci-dss-4-0 |
| Implement RBI IT Framework for Banks via Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/samples/rbi-itf-banks-2016 |
| Implement RBI IT Framework for NBFC via Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/samples/rbi-itf-nbfc-2017 |
| Align RMIT Malaysia controls with Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/samples/rmit-malaysia |
| Map SOC 2 controls to Azure Policy initiatives | https://learn.microsoft.com/en-us/azure/governance/policy/samples/soc-2 |
| Map Spain ENS controls to Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/samples/spain-ens |
| Map SWIFT CSP-CSCF 2021 controls to Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/samples/swift-csp-cscf-2021 |
| Map SWIFT CSP-CSCF 2022 controls to Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/samples/swift-csp-cscf-2022 |
| Align UK OFFICIAL and UK NHS controls with Azure Policy | https://learn.microsoft.com/en-us/azure/governance/policy/samples/ukofficial-uknhs |
| Self-enforce MFA using Azure Policy assignments | https://learn.microsoft.com/en-us/azure/governance/policy/tutorials/mfa-enforcement |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot common Azure Blueprints errors | https://learn.microsoft.com/en-us/azure/governance/blueprints/troubleshoot/general |
| Troubleshoot Azure management group SDK errors | https://learn.microsoft.com/en-us/azure/governance/management-groups/troubleshoot/general |
| Diagnose causes of Azure Policy non-compliance | https://learn.microsoft.com/en-us/azure/governance/policy/how-to/determine-non-compliance |
| Troubleshoot common Azure Policy and Kubernetes add-on errors | https://learn.microsoft.com/en-us/azure/governance/policy/troubleshoot/general |
| Use Change Analysis to diagnose Azure resource issues | https://learn.microsoft.com/en-us/azure/governance/resource-graph/changes/resource-graph-changes |
| Inspect Azure resource changes in portal Change Analysis | https://learn.microsoft.com/en-us/azure/governance/resource-graph/changes/view-resource-changes |
| Troubleshoot Azure Resource Graph alert queries | https://learn.microsoft.com/en-us/azure/governance/resource-graph/troubleshoot/alerts |
| Resolve common Azure Resource Graph query errors | https://learn.microsoft.com/en-us/azure/governance/resource-graph/troubleshoot/general |
| Fix issues with Azure Resource Graph Power BI connector | https://learn.microsoft.com/en-us/azure/governance/resource-graph/troubleshoot/power-bi-connector |

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
