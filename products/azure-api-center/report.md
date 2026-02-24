---
generated_at: '2026-02-24'
category_descriptions:
  security: Configuring API authorization in Azure API Center, including setting auth
    settings, securing access to APIs, and integrating with identity providers.
  configuration: 'Configuring API Center portals and tools: customize portal settings,
    set up managed portals, enable the VS Code portal view, and configure self-managed
    API linting.'
  best-practices: Guidance on enabling and using built-in linting and analysis in
    Azure API Center to automatically validate API definitions, enforce standards,
    and improve API quality.
  integrations: How to integrate API Center with tools like VS Code, GitHub Copilot,
    Copilot Studio, Azure CLI, Logic Apps, Teams, and sync APIs from API Management
    and Amazon API Gateway
  deployment: Automating Azure API Center registration via GitHub Actions CI/CD and
    deploying/self-hosting the API Center developer portal configuration and runtime.
---
# Azure Api Center Crawl Report

## Summary

- **Total Pages**: 35
- **Fetched**: 35
- **Fetch Failed**: 0
- **Classified**: 14
- **Unclassified**: 21

### Incremental Update
- **New Pages**: 0
- **Updated Pages**: 6
- **Unchanged**: 29
- **Deleted Pages**: 0
- **Compared With**: `/home/vsts/work/1/s/Agent-Skills/products/azure-api-center/azure-api-center.csv`

## Classification Statistics

| Type | Count | Percentage |
|------|-------|------------|
| best-practices | 1 | 2.9% |
| configuration | 4 | 11.4% |
| deployment | 2 | 5.7% |
| integrations | 6 | 17.1% |
| security | 1 | 2.9% |
| *(Unclassified)* | 21 | 60.0% |

## Changes

### Updated Pages

- [Create an API center - Visual Studio Code](https://learn.microsoft.com/en-us/azure/api-center/set-up-api-center-vs-code-extension)
  - Updated: 2025-06-26T17:09:00.000Z → 2026-01-28T23:12:00.000Z
- [Build and register APIs - VS Code extension](https://learn.microsoft.com/en-us/azure/api-center/build-register-apis-vscode-extension)
  - Updated: 2025-09-08T22:37:00.000Z → 2026-01-28T23:12:00.000Z
- [Design and develop  APIs - GitHub Copilot for Azure](https://learn.microsoft.com/en-us/azure/api-center/design-api-github-copilot-azure)
  - Updated: 2025-09-26T08:00:00.000Z → 2026-01-28T23:12:00.000Z
- [Register and discover MCP servers](https://learn.microsoft.com/en-us/azure/api-center/register-discover-mcp-server)
  - Updated: 2025-09-09T05:11:00.000Z → 2026-02-11T18:17:00.000Z
- [Govern APIs - VS Code extension](https://learn.microsoft.com/en-us/azure/api-center/govern-apis-vscode-extension)
  - Updated: 2025-03-27T06:08:00.000Z → 2026-02-20T23:21:00.000Z
- [Discover and consume APIs - VS Code extension](https://learn.microsoft.com/en-us/azure/api-center/discover-apis-vscode-extension)
  - Updated: 2025-05-30T22:09:00.000Z → 2026-01-28T23:12:00.000Z

## Classified Pages

| TOC Title | Type | Confidence | Reason |
|-----------|------|------------|--------|
| [Authorize access to APIs](https://learn.microsoft.com/en-us/azure/api-center/authorize-api-access) | security | 0.75 | Covers configuring API access via API keys and OAuth 2.0, and is explicitly about authorization. Likely includes specific auth settings, scopes, and possibly role mappings, which fits the security sub-skill. |
| [Customize API Center portal](https://learn.microsoft.com/en-us/azure/api-center/customize-api-center-portal) | configuration | 0.75 | Explicitly about customizable portal settings; likely lists specific configuration options and allowed values, which is core configuration knowledge. |
| [API analysis - self-managed](https://learn.microsoft.com/en-us/azure/api-center/enable-api-analysis-linting) | configuration | 0.70 | Explains manual setup of a linting engine and triggers. This typically involves specific configuration parameters, trigger settings, and possibly environment values unique to API Center, matching the configuration sub-skill criteria. |
| [Enable API Center portal](https://learn.microsoft.com/en-us/azure/api-center/set-up-api-center-portal) | configuration | 0.70 | Describes setting up the managed portal with Entra ID and RBAC-based access. Likely includes portal configuration options and required settings, fitting configuration (with some overlap with security). |
| [Export API from API Center to Copilot Studio](https://learn.microsoft.com/en-us/azure/api-center/export-to-copilot-studio) | integrations | 0.70 | Describes exporting API definitions from API Center into Microsoft Copilot Studio as connectors; cross-product integration with specific steps and parameters. |
| [Import APIs from API Management](https://learn.microsoft.com/en-us/azure/api-center/import-api-management-apis) | integrations | 0.70 | Describes using Azure CLI (az apim api export and related commands) to import APIs from API Management into API Center; includes product-specific CLI parameters and integration flow. |
| [Self-host Azure API Center portal](https://learn.microsoft.com/en-us/azure/api-center/self-host-api-center-portal) | deployment | 0.70 | Covers deploying a reference implementation of the portal from a starter repository. This is a product-specific deployment pattern, likely including deployment requirements and steps beyond generic hosting. |
| [Synchronize APIs from API Management](https://learn.microsoft.com/en-us/azure/api-center/synchronize-api-management-apis) | integrations | 0.70 | Explains continuous synchronization between API Management and API Center, including configuration steps and product-specific integration behavior; fits integrations & coding patterns. |
| [Synchronize APIs from Amazon API Gateway](https://learn.microsoft.com/en-us/azure/api-center/synchronize-aws-gateway-apis) | integrations | 0.70 | Shows how to integrate Amazon API Gateway with API Center for automatic sync; cross-service integration with product-specific configuration details. |
| [API analysis - Microsoft managed](https://learn.microsoft.com/en-us/azure/api-center/enable-managed-api-analysis-linting) | best-practices | 0.65 | Describes Microsoft-managed linting capabilities, built-in vs self-managed options, and how they affect governance. While partly conceptual, it likely includes product-specific recommendations and edge-case guidance (for example, when to disable custom functions and rely on managed linting), which qualifies as best-practices. |
| [Enable API Center portal view - VS Code extension](https://learn.microsoft.com/en-us/azure/api-center/enable-api-center-portal-vs-code-extension) | configuration | 0.65 | Shows how to enable and control access to the portal view in the VS Code extension, likely involving specific extension settings and access configuration, matching configuration (with some security aspects). |
| [Manage inventory - Azure CLI](https://learn.microsoft.com/en-us/azure/api-center/manage-apis-azure-cli) | integrations | 0.65 | Shows az apic api commands to create and update APIs, versions, and definitions; includes product-specific CLI command names and parameters, which qualify as integration/coding patterns. |
| [Register APIs - GitHub Actions](https://learn.microsoft.com/en-us/azure/api-center/register-apis-github-actions) | deployment | 0.65 | Shows a GitHub Actions workflow to register APIs in API Center as part of CI/CD; includes product-specific deployment workflow configuration and constraints. |
| [Workflow automation to set API status](https://learn.microsoft.com/en-us/azure/api-center/set-up-notification-workflow) | integrations | 0.65 | Shows how to wire API Center events into Logic Apps and Microsoft Teams. This kind of article typically includes connector configuration, trigger/action parameters, and integration-specific patterns, matching the integrations sub-skill. |

## Unclassified Pages

| TOC Title | Confidence | Reason |
|-----------|------------|--------|
| [1 - Define custom metadata](https://learn.microsoft.com/en-us/azure/api-center/tutorials/add-metadata-properties) | 0.50 | Tutorial on defining custom metadata via portal; likely procedural with examples but no configuration parameter tables or numeric constraints. |
| [2 - Add APIs to the inventory](https://learn.microsoft.com/en-us/azure/api-center/tutorials/register-apis) | 0.50 | Tutorial on registering APIs and assigning metadata; step-by-step usage, not a reference of limits, configs, or troubleshooting mappings. |
| [3 - Add environments and deployments](https://learn.microsoft.com/en-us/azure/api-center/tutorials/configure-environments-deployments) | 0.50 | Tutorial on adding environments and deployments; describes how to use portal, not detailed deployment constraints or matrices. |
| [Track API dependencies](https://learn.microsoft.com/en-us/azure/api-center/track-resource-dependencies) | 0.50 | Explains how to track dependencies between APIs and resources using the dependency tracker; appears conceptual/feature-usage without detailed config tables, limits, or troubleshooting mappings. |
| [Create an API center - ARM template](https://learn.microsoft.com/en-us/azure/api-center/set-up-api-center-arm-template) | 0.40 | Quickstart using ARM template to create an API Center; shows basic template usage rather than comprehensive configuration or limits. |
| [Create an API center - Bicep](https://learn.microsoft.com/en-us/azure/api-center/set-up-api-center-bicep) | 0.40 | Quickstart using Bicep to create an API Center; primarily a deployment example, not a full deployment constraints matrix or config reference. |
| [Create an API center - CLI](https://learn.microsoft.com/en-us/azure/api-center/set-up-api-center-azure-cli) | 0.40 | Quickstart for creating an API Center via Azure CLI; focuses on basic creation flow, not on exhaustive config options or expert troubleshooting. |
| [Create an API center - portal](https://learn.microsoft.com/en-us/azure/api-center/set-up-api-center) | 0.40 | Quickstart for creating an API Center via portal; step-by-step tutorial without detailed configuration matrices, limits, or advanced patterns. |
| [Frequently asked questions](https://learn.microsoft.com/en-us/azure/api-center/frequently-asked-questions) | 0.30 | FAQ page likely addresses common questions but summary shows no concrete error codes, config tables, or numeric limits; appears conceptual/clarificatory. |
| [Register and manage agents](https://learn.microsoft.com/en-us/azure/api-center/register-manage-agents) | 0.30 | Task-focused how-to for registering and managing agents, but summary does not indicate detailed configuration parameter tables, limits, or product-specific troubleshooting. |
| [Build and register APIs - VS Code extension](https://learn.microsoft.com/en-us/azure/api-center/build-register-apis-vscode-extension) | 0.20 | Covers how to build and register APIs using the API Center VS Code extension; appears to be a usage/tutorial guide without explicit limits, configuration matrices, or troubleshooting mappings. |
| [Create an API center - Visual Studio Code](https://learn.microsoft.com/en-us/azure/api-center/set-up-api-center-vs-code-extension) | 0.20 | Quickstart for creating an API Center via VS Code; primarily step-by-step UI workflow without detailed configuration tables, limits, or product-specific best practices beyond generic tutorial content. |
| [Design and develop  APIs - GitHub Copilot for Azure](https://learn.microsoft.com/en-us/azure/api-center/design-api-github-copilot-azure) | 0.20 | Describes using the API Center plugin for GitHub Copilot for Azure to design APIs; high-level workflow and AI-assisted generation, not detailed configuration, limits, or decision matrices. |
| [Discover and consume APIs - VS Code extension](https://learn.microsoft.com/en-us/azure/api-center/discover-apis-vscode-extension) | 0.20 | Explains how to discover and consume APIs via the Azure API Center VS Code extension, including SDK generation with Kiota. Summary indicates a feature/tour style description without product-specific limits, configuration matrices, or error-resolution mappings. |
| [Govern APIs - VS Code extension](https://learn.microsoft.com/en-us/azure/api-center/govern-apis-vscode-extension) | 0.20 | Page is about governance capabilities of the Azure API Center VS Code extension and the shift-left governance concept. Summary suggests feature overview and conceptual guidance, not detailed configuration tables, limits, or troubleshooting content. |
| [Key concepts](https://learn.microsoft.com/en-us/azure/api-center/key-concepts) | 0.20 | Key concepts page describing entities and terminology; conceptual only without product-specific numeric limits, configs, or troubleshooting mappings. |
| [Overview](https://learn.microsoft.com/en-us/azure/api-center/agent-to-agent-overview) | 0.20 | High-level overview of agent registry capabilities and concepts; no detailed limits, configuration tables, error codes, or decision matrices. |
| [Register and discover MCP servers](https://learn.microsoft.com/en-us/azure/api-center/register-discover-mcp-server) | 0.20 | Describes concept of using Azure API Center as a registry for MCP servers and mentions integration with Microsoft Foundry tool catalogs, but available summary indicates high-level usage and benefits without concrete configuration parameters, limits, error codes, or decision matrices. |
| [Samples and labs](https://learn.microsoft.com/en-us/azure/api-center/resources) | 0.20 | Resource index linking to samples and templates; navigation/aggregation content without embedded expert configuration, limits, or troubleshooting details. |
| [Use metadata for governance](https://learn.microsoft.com/en-us/azure/api-center/metadata) | 0.20 | Metadata usage and governance concepts; likely policy/organization guidance rather than concrete numeric limits, config tables, or error codes. |
| [What is Azure API Center?](https://learn.microsoft.com/en-us/azure/api-center/overview) | 0.20 | High-level overview of Azure API Center capabilities and scenarios; no detailed limits, configuration parameters, error codes, or decision matrices. |
