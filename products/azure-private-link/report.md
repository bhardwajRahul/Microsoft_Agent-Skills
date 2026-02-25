---
generated_at: '2026-02-24'
category_descriptions:
  configuration: 'Configuring Azure Private Link/endpoint behavior: subnet policies,
    DNS zones, routing, SNAT, security perimeters, and monitoring/diagnostic logs.'
  limits-quotas: Guidance on increasing virtual network scale limits for Azure Private
    Endpoints, including supported maximums and how to request higher quotas.
  security: Configuring Azure RBAC roles and permissions needed to create, manage,
    and secure Private Link resources and Network Security Perimeters.
  best-practices: DNS design and configuration guidance for Azure Private Endpoints,
    including zone setup, name resolution patterns, split-horizon DNS, and integration
    with on-premises DNS systems
  decision-making: Guidance on estimating and optimizing Private Link costs, comparing
    design options (zonal vs regional, hub-spoke vs mesh), and understanding trade-offs
    between security, performance, and spend.
  troubleshooting: Diagnosing and fixing Azure Private Endpoint and Private Link Service
    connectivity issues, including DNS/misconfiguration causes, validation steps,
    and common error resolutions.
---
# Azure Private Link Crawl Report

## Summary

- **Total Pages**: 49
- **Fetched**: 49
- **Fetch Failed**: 0
- **Classified**: 16
- **Unclassified**: 33

### Incremental Update
- **New Pages**: 0
- **Updated Pages**: 6
- **Unchanged**: 43
- **Deleted Pages**: 0
- **Compared With**: `/home/vsts/work/1/s/Agent-Skills/products/azure-private-link/azure-private-link.csv`

## Classification Statistics

| Type | Count | Percentage |
|------|-------|------------|
| best-practices | 1 | 2.0% |
| configuration | 9 | 18.4% |
| decision-making | 1 | 2.0% |
| limits-quotas | 1 | 2.0% |
| security | 2 | 4.1% |
| troubleshooting | 2 | 4.1% |
| *(Unclassified)* | 33 | 67.3% |

## Changes

### Updated Pages

- [Connect to a SQL server - PowerShell](https://learn.microsoft.com/en-us/azure/private-link/tutorial-private-endpoint-sql-powershell)
  - Updated: 2025-01-07T23:03:00.000Z → 2026-02-20T08:00:00.000Z
- [Deploy a private endpoint with a private resolver](https://learn.microsoft.com/en-us/azure/private-link/tutorial-dns-on-premises-private-resolver)
  - Updated: 2025-02-18T08:00:00.000Z → 2026-02-24T06:10:00.000Z
- [Connect to a storage account](https://learn.microsoft.com/en-us/azure/private-link/tutorial-private-endpoint-storage-portal)
  - Updated: 2025-03-25T08:00:00.000Z → 2026-02-24T06:10:00.000Z
- [Inspect private endpoint traffic with Azure Firewall](https://learn.microsoft.com/en-us/azure/private-link/tutorial-inspect-traffic-azure-firewall)
  - Updated: 2025-02-18T08:00:00.000Z → 2026-02-24T06:10:00.000Z
- [Create a private endpoint - Azure portal](https://learn.microsoft.com/en-us/azure/private-link/create-private-endpoint-portal)
  - Updated: 2025-03-25T08:00:00.000Z → 2026-02-24T12:29:00.000Z
- [Create a private endpoint - Azure CLI](https://learn.microsoft.com/en-us/azure/private-link/create-private-endpoint-cli)
  - Updated: 2025-03-25T08:00:00.000Z → 2026-02-20T08:00:00.000Z

## Classified Pages

| TOC Title | Type | Confidence | Reason |
|-----------|------|------------|--------|
| [Increase Private Endpoint virtual network limits](https://learn.microsoft.com/en-us/azure/private-link/increase-private-endpoint-vnet-limits) | limits-quotas | 0.95 | Explicitly discusses current hard limits (1,000 private endpoints per VNet, 4,000 across peered VNets) and how to increase them via High Scale Private Endpoints; these are precise quota values not inferable from general training. |
| [RBAC permissions](https://learn.microsoft.com/en-us/azure/private-link/rbac-permissions) | security | 0.90 | Explicitly described as listing specific permissions required to create Private Endpoints and Private Link services, including built-in roles and custom role permission actions; this is product-specific RBAC configuration detail. |
| [Role-based access control permissions](https://learn.microsoft.com/en-us/azure/private-link/network-security-perimeter-role-based-access-control-requirements) | security | 0.85 | Described as detailing Azure RBAC permissions required for using Network Security Perimeter capabilities, including actions for profiles, access rules, diagnostic settings, and associations; this is specific security configuration knowledge. |
| [Troubleshoot Private Link service connectivity problems](https://learn.microsoft.com/en-us/azure/private-link/troubleshoot-private-link-connectivity) | troubleshooting | 0.85 | Provides structured guidance to validate and diagnose Private Link connectivity, implying symptom-to-cause-to-solution flows specific to Azure Private Link Service, fitting the troubleshooting category. |
| [Troubleshoot private endpoint connectivity problems](https://learn.microsoft.com/en-us/azure/private-link/troubleshoot-private-endpoint-connectivity) | troubleshooting | 0.85 | Step-by-step connectivity validation and diagnosis for Private Endpoints; such articles typically map specific connectivity symptoms and checks to causes and resolutions, which is product-specific troubleshooting knowledge. |
| [Private DNS zone values](https://learn.microsoft.com/en-us/azure/private-link/private-endpoint-dns) | configuration | 0.80 | This page is a reference of private DNS zone values per Azure service that supports private endpoints; it contains service-specific FQDN patterns and zone names that function as configuration parameters not derivable from general knowledge. |
| [Cost optimization](https://learn.microsoft.com/en-us/azure/private-link/private-link-cost-optimization) | decision-making | 0.70 | Cost optimization guidance for Private Link architectures; focuses on balancing security and cost. This is decision-making content with product-specific trade-offs and scenario-based recommendations, beyond generic theory. |
| [Disable SNAT for traffic through NVA](https://learn.microsoft.com/en-us/azure/private-link/private-link-disable-snat) | configuration | 0.70 | Explains configuring a special tag on NVA VMs to bypass SNAT for private endpoint traffic; this is product-specific configuration with concrete setting names and behavior, matching configuration expert knowledge. |
| [Disable network policies for a Private Link service](https://learn.microsoft.com/en-us/azure/private-link/disable-private-link-service-network-policy) | configuration | 0.70 | Describes the privateLinkServiceNetworkPolicies setting that must be disabled on the subnet for Azure Private Link service, including its scope and portal behavior. This is a concrete, product-specific configuration parameter. |
| [Manage network policies for private endpoints](https://learn.microsoft.com/en-us/azure/private-link/disable-private-endpoint-network-policy) | configuration | 0.70 | Explains enabling network policies for private endpoints on a subnet, including specific setting behavior and scope (applies only to private endpoints vs other resources). This is product-specific configuration guidance rather than generic networking advice. |
| [Manage private endpoints](https://learn.microsoft.com/en-us/azure/private-link/manage-private-endpoint) | configuration | 0.70 | Covers specific configuration aspects such as GroupId and MemberName retrieval and use, and custom properties (static IP, NIC name) that must be set at creation. These are product-specific configuration details. |
| [Monitoring data reference](https://learn.microsoft.com/en-us/azure/private-link/monitor-private-link-reference) | configuration | 0.70 | A monitoring data reference typically lists specific metric names, dimensions, and log categories for Azure Private Link. These are product-specific configuration/telemetry details beyond generic monitoring concepts. |
| [Private endpoint DNS integration](https://learn.microsoft.com/en-us/azure/private-link/private-endpoint-dns-integration) | best-practices | 0.70 | Described as covering common DNS scenarios and best practices for Private Endpoint name resolution across VNets, peered networks, and on-premises; likely includes product-specific recommendations and patterns for DNS setup unique to Azure Private Endpoint. |
| [Configure Private Link service Direct Connect](https://learn.microsoft.com/en-us/azure/private-link/configure-private-link-service-direct-connect) | configuration | 0.65 | Describes how to configure Private Link service Direct Connect to arbitrary private IPs. Likely includes specific configuration properties and constraints unique to this feature, fitting configuration-focused expert knowledge. |
| [Diagnostic logs](https://learn.microsoft.com/en-us/azure/private-link/network-security-perimeter-diagnostic-logs) | configuration | 0.65 | Describes diagnostic log categories and options for storing logs, plus how to enable them in the portal for Network Security Perimeter. This is product-specific logging configuration, not just conceptual logging guidance. |
| [Azure CLI](https://learn.microsoft.com/en-us/azure/private-link/create-network-security-perimeter-cli) | configuration | 0.60 | Quickstart shows concrete Azure CLI commands and parameters to create and manage a Network Security Perimeter, including associations and access rules. These are specific configuration commands and options for this feature. |

## Unclassified Pages

| TOC Title | Confidence | Reason |
|-----------|------------|--------|
| [Approve private link connections across subscriptions](https://learn.microsoft.com/en-us/azure/private-link/how-to-approve-private-link-cross-subscription) | 0.45 | Article on approving Private Endpoint connections across subscriptions; summary suggests procedural guidance rather than detailed RBAC role lists or configuration tables. |
| [Configure an application security group](https://learn.microsoft.com/en-us/azure/private-link/configure-asg-private-endpoint) | 0.45 | Shows how to associate Private Endpoints with Application Security Groups; appears to be a how-to without extensive configuration parameter reference or security role matrices. |
| [Export private endpoint DNS records](https://learn.microsoft.com/en-us/azure/private-link/private-endpoint-export-dns) | 0.40 | Tutorial on exporting DNS records via portal; procedural and narrow, without broad configuration tables, limits, or error-code-based troubleshooting. |
| [Transition to a network security perimeter](https://learn.microsoft.com/en-us/azure/private-link/network-security-perimeter-transition) | 0.40 | Conceptual guidance on access modes and transitioning to network security perimeter; no clear evidence of numeric thresholds, decision matrices, or detailed RBAC/limits tables in the summary. |
| [Availability](https://learn.microsoft.com/en-us/azure/private-link/availability) | 0.30 | Availability/GA announcement and supported-services overview; does not describe limits, configuration parameters, or decision criteria in the summary. |
| [Connect to a SQL server - PowerShell](https://learn.microsoft.com/en-us/azure/private-link/tutorial-private-endpoint-sql-powershell) | 0.30 | Tutorial-style walkthrough for creating a private endpoint to Azure SQL via PowerShell. It focuses on step-by-step creation, not on limits, configuration matrices, error-code troubleshooting, or product-specific best-practice guidance with quantified impact. |
| [Connect to a storage account](https://learn.microsoft.com/en-us/azure/private-link/tutorial-private-endpoint-storage-portal) | 0.30 | Tutorial for connecting to a storage account using a private endpoint via the portal. It is a basic how-to guide without expert-level limits, quotas, decision matrices, or detailed configuration option tables. |
| [Create a Private Link service - ARM template](https://learn.microsoft.com/en-us/azure/private-link/create-private-link-service-template) | 0.30 | ARM template quickstart for Private Link service; focuses on one template, not on enumerating all configuration options or limits. |
| [Create a Private Link service - Bicep](https://learn.microsoft.com/en-us/azure/private-link/create-private-link-service-bicep) | 0.30 | Bicep quickstart for Private Link service; single deployment example, not a full configuration reference with parameter ranges or constraints. |
| [Create a network security perimeter - ARM template](https://learn.microsoft.com/en-us/azure/private-link/create-network-security-perimeter-template) | 0.30 | ARM template quickstart; shows one deployment example rather than enumerating configuration options, limits, or RBAC details. |
| [Create a network security perimeter - Azure CLI](https://learn.microsoft.com/en-us/azure/private-link/create-network-security-perimeter-cli) | 0.30 | CLI quickstart for creating a network security perimeter; mainly a how-to guide without expert-level limits, RBAC matrices, or configuration catalogs. |
| [Create a network security perimeter - Azure portal](https://learn.microsoft.com/en-us/azure/private-link/create-network-security-perimeter-portal) | 0.30 | Quickstart for creating a network security perimeter via portal; primarily step-by-step tutorial without detailed RBAC tables, limits, or product-specific configuration matrices. |
| [Create a network security perimeter - Bicep](https://learn.microsoft.com/en-us/azure/private-link/create-network-security-perimeter-bicep) | 0.30 | Bicep quickstart for creating a network security perimeter; template-focused tutorial, not a comprehensive configuration reference or limits document. |
| [Create a network security perimeter - PowerShell](https://learn.microsoft.com/en-us/azure/private-link/create-network-security-perimeter-powershell) | 0.30 | PowerShell quickstart for creating a network security perimeter; focuses on procedural steps, not detailed configuration parameter tables or limits. |
| [Create a private endpoint - ARM template](https://learn.microsoft.com/en-us/azure/private-link/create-private-endpoint-template) | 0.30 | ARM template quickstart; defines one deployment scenario rather than enumerating all configuration options, limits, or decision criteria. |
| [Create a private endpoint - Bicep](https://learn.microsoft.com/en-us/azure/private-link/create-private-endpoint-bicep) | 0.30 | Bicep quickstart for a single private endpoint deployment; example-focused, not a full configuration reference with parameter ranges or limits. |
| [Create a private endpoint - Terraform](https://learn.microsoft.com/en-us/azure/private-link/create-private-endpoint-terraform) | 0.30 | Terraform quickstart for a specific scenario (SQL Database + private DNS); primarily a sample, not a comprehensive configuration or limits reference. |
| [Deploy a private endpoint with a private resolver](https://learn.microsoft.com/en-us/azure/private-link/tutorial-dns-on-premises-private-resolver) | 0.30 | Tutorial for setting up DNS infrastructure with Azure Private Resolver for on-premises workloads. Content is procedural (create VNet, resolver, endpoints) without detailed configuration parameter tables, limits, or troubleshooting mappings. |
| [FAQ](https://learn.microsoft.com/en-us/azure/private-link/private-link-faq) | 0.30 | FAQ page likely mixes conceptual and minor specifics, but description does not indicate structured limits, config tables, or troubleshooting mappings required for expert classification. |
| [Inspect private endpoint traffic with Azure Firewall](https://learn.microsoft.com/en-us/azure/private-link/tutorial-inspect-traffic-azure-firewall) | 0.30 | Tutorial for inspecting private endpoint traffic with Azure Firewall. It describes how to set up inspection but does not provide error-code-based troubleshooting, quantified best practices, or configuration matrices. |
| [Monitor Private Link](https://learn.microsoft.com/en-us/azure/private-link/monitor-private-link) | 0.30 | Monitoring overview for Azure Private Link; describes what data can be collected and general use of Azure Monitor without detailed metric tables, configuration parameters, or product-specific limits, codes, or settings. |
| [Connect to a SQL server - Azure CLI](https://learn.microsoft.com/en-us/azure/private-link/tutorial-private-endpoint-sql-cli) | 0.20 | CLI tutorial for creating SQL Private Endpoint; similar to other tutorials, focused on commands rather than expert configuration or limits. |
| [Connect to a SQL server - Azure portal](https://learn.microsoft.com/en-us/azure/private-link/tutorial-private-endpoint-sql-portal) | 0.20 | Portal tutorial for connecting to Azure SQL via Private Endpoint; standard step-by-step content without expert-level limits, RBAC matrices, or config catalogs. |
| [Create a Private Link service - Azure CLI](https://learn.microsoft.com/en-us/azure/private-link/create-private-link-service-cli) | 0.20 | CLI quickstart for Private Link service; example commands only, no structured limits, quotas, or decision matrices. |
| [Create a Private Link service - Azure portal](https://learn.microsoft.com/en-us/azure/private-link/create-private-link-service-portal) | 0.20 | Portal quickstart for creating a Private Link service; procedural guidance without detailed expert-level configuration matrices. |
| [Create a Private Link service - PowerShell](https://learn.microsoft.com/en-us/azure/private-link/create-private-link-service-powershell) | 0.20 | PowerShell quickstart for Private Link service; focuses on basic creation steps, not on exhaustive configuration options or limits. |
| [Create a private endpoint - Azure CLI](https://learn.microsoft.com/en-us/azure/private-link/create-private-endpoint-cli) | 0.20 | Quickstart tutorial for creating a private endpoint via Azure CLI; focuses on basic creation flow and example commands, not on limits, quotas, best-practices, troubleshooting mappings, or configuration reference tables. |
| [Create a private endpoint - Azure portal](https://learn.microsoft.com/en-us/azure/private-link/create-private-endpoint-portal) | 0.20 | Quickstart tutorial for creating a private endpoint via Azure portal; primarily step-by-step instructions without limits, quotas, decision matrices, or product-specific troubleshooting/config tables. |
| [Create a private endpoint - PowerShell](https://learn.microsoft.com/en-us/azure/private-link/create-private-endpoint-powershell) | 0.20 | Quickstart using PowerShell to create a private endpoint; primarily procedural, not a reference of config parameters, limits, or troubleshooting. |
| [Private Link service](https://learn.microsoft.com/en-us/azure/private-link/private-link-service-overview) | 0.20 | Overview of Azure Private Link service from provider side; no specific quotas, config matrices, or error-resolution content. |
| [What is Azure Private Link?](https://learn.microsoft.com/en-us/azure/private-link/private-link-overview) | 0.20 | High-level overview of Azure Private Link features and architecture; no detailed limits, configuration tables, error codes, or decision matrices. |
| [What is a network security perimeter?](https://learn.microsoft.com/en-us/azure/private-link/network-security-perimeter-concepts) | 0.20 | Conceptual description of Network Security Perimeter; summary indicates no concrete RBAC role lists, parameter tables, or numeric thresholds. |
| [What is a private endpoint?](https://learn.microsoft.com/en-us/azure/private-link/private-endpoint-overview) | 0.20 | Conceptual explanation of private endpoints; lacks numeric limits, configuration parameter tables, or troubleshooting mappings. |
