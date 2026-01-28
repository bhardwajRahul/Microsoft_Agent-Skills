---
name: azure-resource-manager
description: Expert knowledge for Azure Resource Manager development including deployment, best practices, integrations & coding patterns, configuration, troubleshooting, comparing x vs. y, limits & quotas, security, and architecture & design patterns. Use when building, debugging, or optimizing Azure Resource Manager applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Azure Resource Manager Skill

This skill provides expert guidance for Azure Resource Manager development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Use configuration set pattern in Bicep parameters | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/patterns-configuration-set |
| Apply logical parameter pattern in Bicep templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/patterns-logical-parameter |
| Implement robust name generation patterns in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/patterns-name-generation |
| Use shared variable file pattern in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/patterns-shared-variable-file |
| Select a cloud workload relocation strategy in Azure | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocate-select |

### Best Practices
| Topic | URL |
|-------|-----|
| Apply product-specific best practices for Bicep files | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/best-practices |
| Use and configure Bicep linter for template quality | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter |
| Avoid literal admin usernames in Bicep templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-admin-username-should-not-be-literal |
| Define artifacts parameters correctly in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-artifacts-parameters |
| Clean up decompiler-generated names in Bicep files | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-decompiler-cleanup |
| Use explicit module location parameters in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-explicit-values-for-loc-params |
| Fix nested deployment template scoping in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-nested-deployment-template-scoping |
| Avoid conflicting metadata decorators in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-no-conflicting-metadata |
| Avoid root-level deployment resources in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-no-deployments-resources |
| Discourage explicit any type usage in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-no-explicit-any |
| Avoid hardcoded environment URLs in Bicep templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-no-hardcoded-environment-urls |
| Avoid hardcoded Azure locations in Bicep templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-no-hardcoded-location |
| Restrict location expressions to parameter defaults in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-no-loc-expr-outside-params |
| Apply Bicep linter rule for unnecessary dependsOn | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-no-unnecessary-dependson |
| Use Bicep linter to remove unused existing resources | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-no-unused-existing-resources |
| Detect and clean up unused imports in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-no-unused-imports |
| Identify and remove unused parameters in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-no-unused-parameters |
| Find and eliminate unused variables in Bicep files | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-no-unused-variables |
| Prefer string interpolation over concat in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-prefer-interpolation |
| Use unquoted property names in Bicep objects | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-prefer-unquoted-property-names |
| Simplify unnecessary string interpolation in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-simplify-interpolation |
| Replace json('null') with null in Bicep templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-simplify-json-null |
| Use the parent property for child resources in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-use-parent-property |
| Enforce recent Azure resource API versions in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-use-recent-api-versions |
| Use recent Az PowerShell versions in deployment scripts | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-use-recent-az-powershell-version |
| Keep Bicep public module versions up to date | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-use-recent-module-versions |
| Use resource ID functions and symbolic names in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-use-resource-id-functions |
| Prefer resource symbol references over list/reference in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-use-resource-symbol-reference |
| Apply Bicep linter rule for safe access operator | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-use-safe-access |
| Use stable resource identifiers in Bicep templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-use-stable-resource-identifier |
| Avoid preview VM images with Bicep linter | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-use-stable-vm-image |
| Detect what-if short-circuiting in Bicep modules | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-what-if-short-circuiting |
| Follow recommended workflow to migrate ARM to Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/migrate |
| Implement custom action endpoints for Azure REST API | https://learn.microsoft.com/en-us/azure/azure-resource-manager/custom-providers/custom-providers-action-endpoint-how-to |
| Implement custom resource endpoints for Azure REST API | https://learn.microsoft.com/en-us/azure/azure-resource-manager/custom-providers/custom-providers-resources-endpoint-how-to |
| Delete Azure resource groups and handle ARM responses | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/delete-resource-group |
| Cut over Azure workloads after regional migration | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocate-cutover |
| Manage and delete personal data in Azure Resource Manager | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/resource-manager-personal-data |
| Tag Azure resources to label mission-critical workloads | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/tag-mission-critical-workload |
| Understand ARM template test toolkit all-file rules | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/all-files-test-cases |
| Apply best practices when authoring ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/best-practices |
| createUiDefinition.json test cases for ARM toolkit | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/createuidefinition-test-cases |
| Parameter file test cases for ARM toolkit | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/parameter-file-test-cases |
| ARM template test cases and rule examples | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-test-cases |
| Run ARM template test toolkit for best practices | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/test-toolkit |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Compare ARM JSON template syntax with Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/compare-template-syntax |

### Configuration
| Topic | URL |
|-------|-----|
| Configure Bicep environment with bicepconfig.json | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/bicep-config |
| Customize Bicep linter settings in bicepconfig.json | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/bicep-config-linter |
| Configure Bicep module aliases and credentials | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/bicep-config-modules |
| Use and configure data types in Azure Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/data-types |
| Configure dev environments for Bicep deployment scripts | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/deployment-script-bicep-configure-dev |
| Manage Azure deployment stacks using Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/deployment-stacks |
| Author and configure Azure Bicep file syntax | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/file |
| Install and configure Bicep development tools | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/install |
| Convert Bicep files to JSON with MSBuild | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/msbuild-bicep-file |
| Configure private Azure Container Registry for Bicep modules | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/private-module-registry |
| Provision Azure monitoring resources using Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/scenarios-monitoring |
| Create and manage template specs with Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/template-specs |
| Define and use user-defined types in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/user-defined-data-types |
| Create and use user-defined functions in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/user-defined-functions |
| Configure cache custom resources for Azure Custom Providers | https://learn.microsoft.com/en-us/azure/azure-resource-manager/custom-providers/proxy-cache-resource-endpoint-reference |
| Configure proxy custom resources for Azure Custom Providers | https://learn.microsoft.com/en-us/azure/azure-resource-manager/custom-providers/proxy-resource-endpoint-reference |
| Configure _artifactsLocation parameters for managed app templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/artifacts-location |
| Use collection functions in createUiDefinition.json | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/create-ui-definition-collection-functions |
| Use conversion functions in createUiDefinition.json | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/create-ui-definition-conversion-functions |
| Use date functions in createUiDefinition.json | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/create-ui-definition-date-functions |
| Use logical functions in createUiDefinition.json | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/create-ui-definition-logical-functions |
| Use math functions in createUiDefinition.json | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/create-ui-definition-math-functions |
| Use referencing functions in createUiDefinition.json | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/create-ui-definition-referencing-functions |
| Use string functions in createUiDefinition.json | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/create-ui-definition-string-functions |
| Configure elements schema in createUiDefinition.json | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/create-uidefinition-elements |
| Use createUiDefinition functions in managed apps | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/create-uidefinition-functions |
| Define createUiDefinition.json for managed app portal UX | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/create-uidefinition-overview |
| Configure Microsoft.Common.CheckBox UI element | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-common-checkbox |
| Configure Microsoft.Common.DropDown UI element | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-common-dropdown |
| Configure Microsoft.Common.EditableGrid UI element | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-common-editablegrid |
| Configure Microsoft.Common.FileUpload UI element in ARM | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-common-fileupload |
| Configure Microsoft.Common.InfoBox UI element in ARM | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-common-infobox |
| Configure Microsoft.Common.OptionsGroup UI element in ARM | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-common-optionsgroup |
| Configure Microsoft.Common.PasswordBox UI element in ARM | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-common-passwordbox |
| Configure Microsoft.Common.Section UI element in ARM | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-common-section |
| Configure ServicePrincipalSelector UI element in ARM | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-common-serviceprincipalselector |
| Configure Microsoft.Common.Slider UI element in ARM | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-common-slider |
| Configure TagsByResource UI element for ARM deployments | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-common-tagsbyresource |
| Configure Microsoft.Common.TextBlock UI element in ARM | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-common-textblock |
| Configure Microsoft.Common.TextBox UI element in ARM | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-common-textbox |
| Configure Microsoft.Compute.CredentialsCombo UI element | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-compute-credentialscombo |
| Configure Microsoft.Compute.SizeSelector UI element for VMs | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-compute-sizeselector |
| Configure Microsoft.Compute.UserNameTextBox UI element | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-compute-usernametextbox |
| Configure KeyVaultCertificateSelector UI element in ARM | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-keyvault-keyvaultcertificateselector |
| Configure IdentitySelector UI element for managed identities | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-managedidentity-identityselector |
| Configure PublicIpAddressCombo UI element in ARM | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-network-publicipaddresscombo |
| Configure VirtualNetworkCombo UI element in ARM | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-network-virtualnetworkcombo |
| Configure ArmApiControl UI element for ARM API calls | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-solutions-armapicontrol |
| Configure ResourceSelector UI element for existing resources | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-solutions-resourceselector |
| Configure MultiStorageAccountCombo UI element in ARM | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-storage-multistorageaccountcombo |
| Configure webhook notifications for Azure Managed Applications | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/publish-notifications |
| Author createUiDefinition.json for managed applications | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/reference-createuidefinition-artifact |
| Define mainTemplate.json for Azure Managed Applications | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/reference-main-template-artifact |
| Configure viewDefinition.json for managed application views | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/reference-view-definition-artifact |
| Configure Azure Resource Manager for EU data boundary | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/manage-data-boundary |
| Configure monitoring and metrics for Azure Resource Manager | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/monitor-resource-manager |
| Reference for Azure Resource Manager monitoring data | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/monitor-resource-manager-reference |
| Apply built-in Azure Policy definitions for ARM | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/policy-reference |
| Configure and manage Azure preview features per subscription | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/preview-features |
| Use Resource Group insights to monitor Azure workloads | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/resource-group-insights |
| Enforce Azure tag compliance with policy definitions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/tag-policies |
| Configure Azure tags using Bicep templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/tag-resources-bicep |
| Configure Azure tags using ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/tag-resources-templates |
| Configure child resource names and types in ARM | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/child-resource-name-type |
| Use conditional deployment in ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/conditional-resource-deployment |
| Return multiple output values with ARM copy | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/copy-outputs |
| Use copy loops for resource properties in ARM | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/copy-properties |
| Deploy multiple resource instances with ARM copy | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/copy-resources |
| Define multiple variable values with ARM copy | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/copy-variables |
| Define reusable type definitions in ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/definitions |
| Use deploymentScripts resources in ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deployment-script-template |
| Set up dev environment for ARM deployment scripts | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deployment-script-template-configure-dev |
| Export ARM or Bicep templates using Azure CLI | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/export-template-cli |
| Export ARM or Bicep templates from Azure portal | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/export-template-portal |
| Export ARM or Bicep templates with PowerShell | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/export-template-powershell |
| Configure linked and nested ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/linked-templates |
| Create and use ARM template parameter files | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/parameter-files |
| Configure parameters and constraints in ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/parameters |
| Declare Azure resources in ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/resource-declaration |
| Configure resource dependencies in ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/resource-dependency |
| Configure post-deployment extensions in ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/resource-extensions |
| Set resource locations in ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/resource-location |
| Configure scope property for ARM extension resources | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/scope-extension-resources |
| Use template functions in scoped ARM deployments | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/scope-functions |
| Author Azure Resource Manager template JSON structure | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/syntax |
| Author ARM templates reusable across Azure clouds | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-cloud-consistency |
| Use built-in functions in ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-functions |
| Work with array functions in ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-functions-array |
| Use CIDR functions in ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-functions-cidr |
| Apply comparison functions in ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-functions-comparison |
| Use date functions in ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-functions-date |
| Get deployment info with ARM template functions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-functions-deployment |
| Use lambda expressions in ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-functions-lambda |
| Use logical functions in ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-functions-logical |
| Use numeric functions in ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-functions-numeric |
| Manipulate objects with ARM template functions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-functions-object |
| Retrieve resource values with ARM functions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-functions-resource |
| Use scope functions in ARM template deployments | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-functions-scope |
| Work with string functions in ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-functions-string |
| Update Visual Studio ARM deployment scripts to Az | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/update-visual-studio-deployment-script |
| Create and reuse user-defined functions in ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/user-defined-functions |
| Use variables to simplify ARM template configuration | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/variables |

### Deployment
| Topic | URL |
|-------|-----|
| Integrate Bicep deployments with Azure Pipelines | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/add-template-to-azure-pipelines |
| Deploy Bicep files with Azure CLI commands | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/deploy-cli |
| Deploy local Bicep files from Azure Cloud Shell | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/deploy-cloud-shell |
| Deploy Bicep templates using GitHub Actions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/deploy-github-actions |
| Deploy Bicep templates using Azure PowerShell | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/deploy-powershell |
| Deploy Bicep templates using Visual Studio Code | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/deploy-vscode |
| Migrate Azure Blueprints to deployment stacks | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/migrate-blueprint |
| Move Azure App Service resources across groups or subscriptions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/move-limitations/app-service-move-limitations |
| Move Azure classic deployment resources with ARM | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/move-limitations/classic-model-move-limitations |
| Move Azure Cloud Services (extended support) deployments | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/move-limitations/cloud-services-extended-support |
| Move Azure networking resources to new groups or subscriptions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/move-limitations/networking-move-limitations |
| Handle special cases when moving Azure virtual machines | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/move-limitations/virtual-machines-move-limitations |
| Move Azure resources between resource groups or subscriptions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/move-resource-group-and-subscription |
| Check Azure resource type support and rules for move operations | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/move-support-resources |
| Relocate Azure Application Gateway and WAF between regions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-app-gateway |
| Redeploy Azure App Service to a new region | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-app-service |
| Relocate Azure Automation accounts across regions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-automation |
| Relocate Azure Backup protection to another region | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-backup |
| Relocate Azure Container Registry to another region | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-container-registry |
| Relocate Azure Cosmos DB NoSQL accounts across regions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-cosmos-db |
| Relocate Azure Event Grid custom topics between regions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-event-grid-custom-topics |
| Relocate Azure Event Grid domains to another region | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-event-grid-domains |
| Relocate Azure Event Grid system topics to new regions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-event-grid-system-topics |
| Relocate Azure Event Hubs namespaces to another region | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-event-hub |
| Relocate Azure Event Hubs dedicated clusters across regions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-event-hub-cluster |
| Relocate Azure Firewall protecting a virtual network | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-firewall |
| Redeploy Azure Functions apps across regions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-functions |
| Relocate Azure HDInsight clusters to a new region | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-hdinsight |
| Redeploy Azure Kubernetes Service clusters to new regions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-kubernetes-service |
| Relocate Log Analytics workspaces to new regions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-log-analytics |
| Relocate Azure Database for PostgreSQL across regions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-postgresql-flexible-server |
| Relocate Azure Private Link Service to another region | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-private-link |
| Relocate Recovery Services vault and Site Recovery | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-site-recovery |
| Relocate Azure Static Web Apps between regions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-static-web-apps |
| Relocate Azure Virtual Machine Scale Sets to new regions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-virtual-machine-scale-sets |
| Relocate Azure Virtual Networks across regions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-virtual-network |
| Relocate Azure Network Security Groups to new regions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-virtual-network-nsg |
| Configure Azure Pipelines CI/CD for ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/add-template-to-azure-pipelines |
| Create and deploy ARM resources with Visual Studio | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/create-visual-studio-deployment-project |
| Deploy ARM templates with Azure CLI | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-cli |
| Deploy ARM templates from Azure Cloud Shell | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-cloud-shell |
| Deploy ARM templates using GitHub Actions workflows | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-github-actions |
| Deploy ARM templates using the Azure portal | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-portal |
| Deploy ARM templates with Azure PowerShell | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-powershell |
| Deploy ARM templates using Python SDK | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-python |
| Deploy ARM templates via Azure REST API | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-rest |
| Use Deploy to Azure button for remote ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-to-azure-button |
| Deploy ARM templates at management group scope | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-to-management-group |
| Deploy ARM templates to Azure resource groups | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-to-resource-group |
| Deploy ARM templates at tenant scope | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-to-tenant |
| Preview ARM template changes with what-if | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-what-if |
| Handle resource deletion in ARM complete mode deployments | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deployment-complete-mode-deletion |
| Configure rollback on ARM deployment errors | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/rollback-on-error |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Use Bicep CLI commands via Azure CLI or directly | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/bicep-cli |
| Use Bicep CIDR functions for IP range calculations | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/bicep-functions-cidr |
| Work with date functions in Bicep templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/bicep-functions-date |
| Retrieve deployment information with Bicep functions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/bicep-functions-deployment |
| Load external file content using Bicep file functions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/bicep-functions-files |
| Control Bicep execution flow with the fail function | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/bicep-functions-flow-control |
| Use lambda expressions and functions in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/bicep-functions-lambda |
| Apply logical functions and bool conversion in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/bicep-functions-logical |
| Use numeric functions for calculations in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/bicep-functions-numeric |
| Manipulate objects with Bicep object functions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/bicep-functions-object |
| Use functions in Bicep parameters (.bicepparam) files | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/bicep-functions-parameters-file |
| Get Azure resource values with Bicep resource functions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/bicep-functions-resource |
| Access deployment scope values using Bicep scope functions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/bicep-functions-scope |
| Work with strings using Bicep string functions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/bicep-functions-string |
| Deploy Kubernetes resources using the Bicep extension | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/bicep-kubernetes-extension |
| Decompile ARM JSON templates into Bicep files | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/decompile |
| Develop Bicep deployment scripts with external script files | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/deployment-script-develop |
| Use the Bicep null-forgiving operator to suppress null warnings | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/operator-null-forgiving |
| Safely access properties with the Bicep safe-dereference operator | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/operator-safe-dereference |
| Use core Bicep operators for template expressions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/operators |
| Access resources and properties with Bicep accessor operators | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/operators-access |
| Compare values using Bicep comparison operators | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/operators-comparison |
| Evaluate conditions with Bicep logical operators | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/operators-logical |
| Perform integer math with Bicep numeric operators | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/operators-numeric |
| Build C# RESTful endpoints for Azure Custom Providers | https://learn.microsoft.com/en-us/azure/azure-resource-manager/custom-providers/reference-custom-providers-csharp-endpoint |
| Integrate managed applications with existing virtual networks | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/existing-vnet-integration |
| Track Azure asynchronous operations via ARM responses | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/async-operations |
| Use Python SDK to manage Azure resource groups | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resource-groups-python |
| Manage Azure resources with Azure CLI commands | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resources-cli |
| Manage Azure resources using PowerShell cmdlets | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resources-powershell |
| Manage Azure resources with Python and ARM | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resources-python |
| Call Azure Resource Manager REST to manage resources | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resources-rest |
| Deploy Azure VM extensions via ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-tutorial-deploy-vm-extensions |
| Use ARM deploymentScripts to run custom automation | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-tutorial-deployment-script |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Deploy Bicep templates at subscription scope | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/deploy-to-subscription |
| Enforce maximum predeployment asserts in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-max-asserts |
| Respect ARM template output limits in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-max-outputs |
| Respect ARM template parameter limits in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-max-parameters |
| Respect ARM template resource count limits in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-max-resources |
| Respect ARM template variable limits in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-max-variables |
| Use Bicep outputs and understand output limits | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/outputs |
| Define and use parameters in Bicep templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/parameters |
| Declare resources in Bicep with resource limits | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/resource-declaration |
| Use StorageAccountSelector with storage name constraints | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/microsoft-storage-storageaccountselector |
| Use custom storage to bypass managed app size limits | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/publish-service-catalog-bring-your-own-storage |
| Review Azure subscription and service limits and quotas | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/azure-subscription-service-limits |
| ARM request throttling limits and how to handle them | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/request-limits-and-throttling |
| Apply Azure resource naming rules and restrictions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/resource-name-rules |
| Understand Azure resource group 800-instance limit exceptions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/resources-without-resource-group-limit |
| Understand Azure resource tag limits and behavior | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/tag-resources |
| Check tag support and cost reporting by resource type | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/tag-support |
| Deploy ARM templates at subscription scope | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-to-subscription |
| View ARM deployment history and limits | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deployment-history |
| Understand ARM deployment history limits and cleanup | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deployment-history-deletions |
| Define and use outputs in ARM templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/outputs |
| Use ARM template expressions and syntax rules | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-expressions |
| Resolve deployment quota exceeded in resource groups | https://learn.microsoft.com/en-us/azure/azure-resource-manager/troubleshooting/deployment-quota-exceeded |
| Resolve Azure resource quota errors in deployments | https://learn.microsoft.com/en-us/azure/azure-resource-manager/troubleshooting/error-resource-quota |

### Security
| Topic | URL |
|-------|-----|
| Securely run Bicep deployment scripts in private VNets | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/deployment-script-vnet |
| Run Bicep deployment scripts via private endpoints | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/deployment-script-vnet-private-endpoint |
| Securely pass Key Vault secrets into Bicep deployments | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/key-vault-parameter |
| Prevent exposing secrets in Bicep template outputs | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-outputs-should-not-contain-secrets |
| Protect commandToExecute secrets with protectedSettings | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-protect-commandtoexecute-secrets |
| Avoid hard-coded defaults for secure Bicep parameters | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-secure-parameter-default |
| Secure nested deployments using Bicep secure params | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-secure-params-in-nested-deploy |
| Enforce secure decorator for secret-like Bicep parameters | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-secure-secrets-in-parameters |
| Enforce secure adminPassword values in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter-rule-use-secure-value-for-secure-inputs |
| Define Azure RBAC roles and assignments with Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/scenarios-rbac |
| Manage secrets with Bicep and Azure Key Vault | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/scenarios-secrets |
| Approve just-in-time access for managed applications | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/approve-just-in-time-access |
| Use Azure Policy to deploy managed app associations | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/concepts-built-in-policy |
| Configure delegatedManagedIdentityResourceId for cross-tenant managed apps | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/concepts-delegated-managed-identity-resource-id |
| Deploy managed app with storage encrypted by customer key | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/create-storage-customer-managed-key |
| Comply with hardcoded credential restrictions in Azure applications | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/hardcoded-credentials-restrictions |
| Grant Key Vault access for Azure Managed Application deployments | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/key-vault-access |
| Configure managed identity for Azure Managed Applications | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/publish-managed-identity |
| Configure just-in-time access for Azure Managed Applications | https://learn.microsoft.com/en-us/azure/azure-resource-manager/managed-applications/request-just-in-time-access |
| Authenticate Azure Resource Manager requests across tenants | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/authenticate-multi-tenant |
| Configure ARM management access through Private Link | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/create-private-link-access-commands |
| Secure Azure management with Private Link via portal | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/create-private-link-access-portal |
| Configure management locks to protect Azure resources | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/lock-resources |
| Manage existing Azure Resource Manager Private Links via API | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/manage-private-link-access-commands |
| Use Azure Policy regulatory controls for ARM compliance | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/security-controls-policy |
| Configure TLS version support for Azure Resource Manager | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/tls-support |
| Use Key Vault secrets as ARM template parameters | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/key-vault-parameter |
| Securely deploy ARM templates using SAS tokens | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/secure-template-with-sas-token |
| Secure ARM template parameters with Azure Key Vault | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-tutorial-use-key-vault |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Interpret Bicep warnings and error diagnostic codes | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/bicep-core-diagnostics |
| Use and troubleshoot deployment scripts in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/deployment-script-bicep |
| Resolve BCP007 unrecognized declaration type in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp007 |
| Fix BCP009 incomplete declaration errors in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp009 |
| Resolve BCP018 missing character syntax errors | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp018 |
| Fix BCP029 invalid resource type format in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp029 |
| Resolve BCP033 type mismatch assignment errors | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp033 |
| Fix BCP034 array item type mismatch in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp034 |
| Resolve BCP035 missing required resource properties | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp035 |
| Fix BCP036 property value type mismatch in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp036 |
| Resolve BCP037 disallowed property on resource type | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp037 |
| Fix BCP040 unsupported string interpolation for keys | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp040 |
| Resolve BCP048 cannot resolve function overload | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp048 |
| Fix BCP052 missing property on data type in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp052 |
| Resolve BCP053 invalid property on resource or type | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp053 |
| Fix BCP055 cannot access properties of non-object type | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp055 |
| Resolve BCP057 name does not exist in context | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp057 |
| Fix BCP062 invalid referenced declaration in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp062 |
| Resolve BCP063 name is not a valid symbol type | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp063 |
| Fix BCP070 function argument type mismatch | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp070 |
| Resolve BCP071 incorrect number of function arguments | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp071 |
| Fix BCP072 invalid symbol in parameter default values | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp072 |
| Resolve BCP073 read-only property assignment in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp073 |
| Fix BCP076 invalid index target type in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp076 |
| Resolve BCP077 write-only property access in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp077 |
| Fix BCP078 missing value for tagged union in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp078 |
| Handle BCP081 missing resource type metadata in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp081 |
| Resolve BCP082 unknown name with suggestion in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp082 |
| Fix BCP083 invalid property name with suggestion in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp083 |
| Resolve BCP088 incorrect property value type in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp088 |
| Fix BCP089 disallowed property on Bicep object type | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp089 |
| Resolve BCP091 file path not found in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp091 |
| Fix BCP124 invalid decorator target type in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp124 |
| Resolve BCP125 invalid parameter decorator function in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp125 |
| Fix BCP126 invalid variable decorator function in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp126 |
| Resolve BCP127 invalid resource decorator function in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp127 |
| Fix BCP128 invalid module decorator function in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp128 |
| Resolve BCP129 invalid output decorator function in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp129 |
| Fix BCP130 disallowed decorators in Bicep parameter files | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp130 |
| Resolve BCP132 missing declaration after decorator in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp132 |
| Fix BCP135 invalid deployment scope for Bicep resource | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp135 |
| Resolve BCP138 unsupported for-expression context in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp138 |
| Resolve BCP139 scope mismatch errors in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp139 |
| Fix BCP144 collection reference errors in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp144 |
| Resolve BCP147 decorator parameter declaration errors | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp147 |
| Fix BCP152 invalid decorator function usage in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp152 |
| Resolve BCP153 missing resource or module after decorator | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp153 |
| Fix BCP166 duplicate decorator issues in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp166 |
| Resolve BCP170 invalid child resource names in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp170 |
| Troubleshoot BCP192 module artifact restore failures | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp192 |
| Fix BCP201 invalid Bicep extension specification strings | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp201 |
| Resolve BCP226 invalid #disable-next-line usage in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp226 |
| Fix BCP238 unexpected newline after comma in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp238 |
| Resolve BCP266 missing metadata identifier errors | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp266 |
| Fix BCP288 type used as value errors in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp288 |
| Resolve BCP290 decorator parameter or type declaration issues | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp290 |
| Fix BCP292 decorator parameter, output, or type errors | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp292 |
| Resolve BCP293 invalid union type member definitions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp293 |
| Fix BCP294 non-reducible type unions in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp294 |
| Resolve BCP302 invalid type name usage in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp302 |
| Fix BCP311 invalid array index range errors in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp311 |
| Resolve BCP318 nullability access issues in Bicep deployments | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp318 |
| Resolve BCP327 value-too-large errors in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp327 |
| Resolve BCP328 value-too-small errors in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp328 |
| Fix BCP332 length-too-long errors in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp332 |
| Fix BCP333 length-too-short errors in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp333 |
| Handle BCP335 potential max-length issues in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp335 |
| Resolve BCP337 invalid declarations in Bicep parameters | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp337 |
| Troubleshoot BCP338 parameter evaluation failures | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp338 |
| Fix BCP401 spread operator usage errors in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp401 |
| Resolve BCP414 reverse index operator type errors | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp414 |
| Fix BCP416 string pattern mismatch errors in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp416 |
| Resolve BCP420 ambiguous scope expressions in Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp420 |
| Handle BCP422 resource-existence function call issues | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/diagnostics/bcp422 |
| Troubleshoot common Bicep installation errors | https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/installation-troubleshoot |
| Troubleshoot common ARM template deployment issues | https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/frequently-asked-questions |
| Resolve common Azure ARM/Bicep deployment errors | https://learn.microsoft.com/en-us/azure/azure-resource-manager/troubleshooting/common-deployment-errors |
| Create ARM/Bicep troubleshooting templates | https://learn.microsoft.com/en-us/azure/azure-resource-manager/troubleshooting/create-troubleshooting-template |
| Enable debug logging for ARM/Bicep deployments | https://learn.microsoft.com/en-us/azure/azure-resource-manager/troubleshooting/enable-debug-logging |
| Fix invalid resource name and type segment errors | https://learn.microsoft.com/en-us/azure/azure-resource-manager/troubleshooting/error-invalid-name-segments |
| Resolve invalid ARM/Bicep template errors | https://learn.microsoft.com/en-us/azure/azure-resource-manager/troubleshooting/error-invalid-template |
| Fix ARM/Bicep job size exceeded deployment errors | https://learn.microsoft.com/en-us/azure/azure-resource-manager/troubleshooting/error-job-size-exceeded |
| Fix resource not found errors in ARM operations | https://learn.microsoft.com/en-us/azure/azure-resource-manager/troubleshooting/error-not-found |
| Resolve ParentResourceNotFound errors in deployments | https://learn.microsoft.com/en-us/azure/azure-resource-manager/troubleshooting/error-parent-resource |
| Fix RequestDisallowedByPolicy errors for ARM/Bicep | https://learn.microsoft.com/en-us/azure/azure-resource-manager/troubleshooting/error-policy-requestdisallowedbypolicy |
| Fix location ineligible errors for Azure regions | https://learn.microsoft.com/en-us/azure/azure-resource-manager/troubleshooting/error-region-access-policy |
| Resolve Azure resource provider registration errors | https://learn.microsoft.com/en-us/azure/azure-resource-manager/troubleshooting/error-register-resource-provider |
| Resolve reserved resource name deployment errors | https://learn.microsoft.com/en-us/azure/azure-resource-manager/troubleshooting/error-reserved-resource-name |
| Diagnose and fix Azure SKU not available errors | https://learn.microsoft.com/en-us/azure/azure-resource-manager/troubleshooting/error-sku-not-available |
| Fix Azure storage account name deployment errors | https://learn.microsoft.com/en-us/azure/azure-resource-manager/troubleshooting/error-storage-account-name |
| Find ARM/Bicep deployment error codes | https://learn.microsoft.com/en-us/azure/azure-resource-manager/troubleshooting/find-error-code |
| Use ARM/Bicep deployment troubleshooting tools | https://learn.microsoft.com/en-us/azure/azure-resource-manager/troubleshooting/overview |
| Troubleshoot ARM template JSON deployment issues | https://learn.microsoft.com/en-us/azure/azure-resource-manager/troubleshooting/quickstart-troubleshoot-arm-deployment |
| Troubleshoot Azure Bicep deployment errors | https://learn.microsoft.com/en-us/azure/azure-resource-manager/troubleshooting/quickstart-troubleshoot-bicep-deployment |

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
