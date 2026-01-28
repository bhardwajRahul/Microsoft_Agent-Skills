# SRE Agent Crawl Report

## Summary

- **Duration**: 0m 17s
- **Total Pages**: 25
- **Fetched**: 25
- **Fetch Failed**: 0
- **Classified**: 18
- **Unclassified**: 7

### Incremental Update
- **New Pages**: 0
- **Updated Pages**: 25
- **Unchanged**: 0
- **Deleted Pages**: 0
- **Compared With**: `/home/vsts/work/1/s/Agent-Skills/products/sre-agent/sre-agent.csv`

## Classification Statistics

| Type | Count | Percentage |
|------|-------|------------|
| best-practices | 1 | 4.0% |
| configuration | 5 | 20.0% |
| integrations | 4 | 16.0% |
| security | 5 | 20.0% |
| troubleshooting | 3 | 12.0% |
| *(Unclassified)* | 7 | 28.0% |

## Changes

### Updated Pages

- [Role based access control](https://learn.microsoft.com/en-us/azure/sre-agent/user-access-roles)
  - Updated: 2025-09-15T00:00:00Z → 2025-09-16T17:23:00.000Z
- [Use Managed Identity](https://learn.microsoft.com/en-us/azure/sre-agent/agent-managed-identity)
  - Updated: 2025-09-11T00:00:00Z → 2025-09-16T17:23:00.000Z
- [Frequently asked questions](https://learn.microsoft.com/en-us/azure/sre-agent/faq)
  - Updated: 2025-10-13T00:00:00Z → 2025-10-13T22:14:00.000Z
- [Billing](https://learn.microsoft.com/en-us/azure/sre-agent/billing)
  - Updated: 2025-08-08T00:00:00Z → 2025-09-22T22:32:00.000Z
- [Data residency and privacy](https://learn.microsoft.com/en-us/azure/sre-agent/data-privacy)
  - Updated: 2025-11-05T00:00:00Z → 2025-11-18T17:01:00.000Z
- [About Azure SRE Agent](https://learn.microsoft.com/en-us/azure/sre-agent/overview)
  - Updated: 2025-12-08T00:00:00Z → 2025-12-09T05:48:00.000Z
- [Diagnose your first incident](https://learn.microsoft.com/en-us/azure/sre-agent/usage)
  - Updated: 2025-10-28T00:00:00Z → 2025-11-18T17:01:00.000Z
- [Ask the agent for help](https://learn.microsoft.com/en-us/azure/sre-agent/ask-agent)
  - Updated: 2025-09-02T00:00:00Z → 2025-09-03T17:13:00.000Z
- [Starter prompts](https://learn.microsoft.com/en-us/azure/sre-agent/prompts)
  - Updated: 2025-07-24T00:00:00Z → 2025-08-26T17:10:00.000Z
- [Connect source control](https://learn.microsoft.com/en-us/azure/sre-agent/code-repository-connect)
  - Updated: 2025-09-24T00:00:00Z → 2025-11-20T06:12:00.000Z
- [Multi-cause investigation](https://learn.microsoft.com/en-us/azure/sre-agent/deep-investigation)
  - Updated: 2025-11-04T00:00:00Z → 2025-11-04T23:10:00.000Z
- [Build incident response plans](https://learn.microsoft.com/en-us/azure/sre-agent/incident-response-plan)
  - Updated: 2025-09-24T00:00:00Z → 2025-09-25T17:11:00.000Z
- [Build subagents](https://learn.microsoft.com/en-us/azure/sre-agent/subagent-builder-scenarios)
  - Updated: 2025-11-10T00:00:00Z → 2025-11-18T17:01:00.000Z
- [App Service](https://learn.microsoft.com/en-us/azure/sre-agent/troubleshoot-azure-app-service)
  - Updated: 2025-10-13T00:00:00Z → 2025-11-18T17:01:00.000Z
- [Container Apps](https://learn.microsoft.com/en-us/azure/sre-agent/troubleshoot-azure-container-apps)
  - Updated: 2025-10-13T00:00:00Z → 2025-11-18T17:01:00.000Z
- [Code interpreter](https://learn.microsoft.com/en-us/azure/sre-agent/code-interpreter)
  - Updated: 2026-01-26T00:00:00Z → 2026-01-27T18:10:00.000Z
- [Memory system](https://learn.microsoft.com/en-us/azure/sre-agent/memory-system)
  - Updated: 2026-01-17T00:00:00Z → 2026-01-22T18:12:00.000Z
- [Subagents](https://learn.microsoft.com/en-us/azure/sre-agent/subagent-builder-overview)
  - Updated: 2025-11-10T00:00:00Z → 2025-11-18T17:01:00.000Z
- [Incident management](https://learn.microsoft.com/en-us/azure/sre-agent/incident-management)
  - Updated: 2025-12-09T00:00:00Z → 2025-12-09T23:13:00.000Z
- [Run custom logic](https://learn.microsoft.com/en-us/azure/sre-agent/custom-logic-python)
  - Updated: 2026-01-23T00:00:00Z → 2026-01-27T06:10:00.000Z
- *...and 5 more*

## Classified Pages

| TOC Title | Type | Confidence | Reason |
|-----------|------|------------|--------|
| [Roles and permissions](https://learn.microsoft.com/en-us/azure/sre-agent/roles-permissions-overview) | security | 0.80 | Describes layered permission model built on Azure RBAC; expected to list specific roles, scopes, and security behaviors unique to SRE Agent. |
| [Role based access control](https://learn.microsoft.com/en-us/azure/sre-agent/user-access-roles) | security | 0.78 | RBAC-focused page for SRE Agent likely lists specific built-in roles, their permissions, and allowed actions per role. These are product-specific security configurations (role names and scopes) that qualify as expert knowledge under the security category. |
| [Use Managed Identity](https://learn.microsoft.com/en-us/azure/sre-agent/agent-managed-identity) | security | 0.76 | Describes how agent and user permissions affect SRE Agent behavior, likely including specific Azure RBAC roles, scopes, and permission mappings between the agent’s managed identity and user actions. This is product-specific IAM configuration, fitting the security sub-skill. |
| [Connect to custom MCP server](https://learn.microsoft.com/en-us/azure/sre-agent/custom-mcp-server) | integrations | 0.75 | Details integrating with external MCP servers, including secure connection setup and access to telemetry/tools; expected to list MCP-specific configuration parameters and constraints. |
| [App Service](https://learn.microsoft.com/en-us/azure/sre-agent/troubleshoot-azure-app-service) | troubleshooting | 0.70 | Tutorial focused on identifying and fixing app problems using SRE Agent; likely maps specific symptoms in App Service to SRE Agent–driven diagnosis and remediation steps. |
| [Connect to external services](https://learn.microsoft.com/en-us/azure/sre-agent/connectors) | integrations | 0.70 | Explains connector types and setup for notifications and telemetry ingestion; likely includes connector configuration options and parameter tables. |
| [Container Apps](https://learn.microsoft.com/en-us/azure/sre-agent/troubleshoot-azure-container-apps) | troubleshooting | 0.70 | Tutorial for monitoring and resolving issues in Azure Container Apps via SRE Agent; expected to include symptom-to-solution flows specific to this integration. |
| [Frequently asked questions](https://learn.microsoft.com/en-us/azure/sre-agent/faq) | troubleshooting | 0.70 | FAQ focused on common problems with permissions, regional availability, and admin access likely includes concrete error messages or conditions and their resolutions (symptom → cause → fix), which is product-specific troubleshooting knowledge. |
| [Run custom logic](https://learn.microsoft.com/en-us/azure/sre-agent/custom-logic-python) | integrations | 0.70 | Shows how to create and configure Python tools in a secure sandbox; expected to document tool configuration parameters and integration patterns unique to SRE Agent. |
| [Schedule a task](https://learn.microsoft.com/en-us/azure/sre-agent/scheduled-tasks) | configuration | 0.70 | Describes defining schedules and automation behaviors, including how tasks are created via chat or autonomously; likely includes task configuration fields and allowed values. |
| [Agent run modes](https://learn.microsoft.com/en-us/azure/sre-agent/agent-run-modes) | security | 0.65 | Focuses on consent and security context for write operations; likely documents run modes, elevation behavior, and security-related configuration options. |
| [Code interpreter](https://learn.microsoft.com/en-us/azure/sre-agent/code-interpreter) | configuration | 0.65 | Describes executing Python and shell commands in a sandbox; likely documents interpreter-specific capabilities, constraints, and parameters unique to SRE Agent. |
| [Connect source control](https://learn.microsoft.com/en-us/azure/sre-agent/code-repository-connect) | integrations | 0.65 | Describes connecting monitored resources to a code repository for RCA and ticketing; likely includes repo connection parameters and integration-specific settings beyond generic Git usage. |
| [Data residency and privacy](https://learn.microsoft.com/en-us/azure/sre-agent/data-privacy) | security | 0.65 | Data handling and residency page likely details specific storage locations/regions, processing flows, and privacy controls unique to SRE Agent. These are product-specific security/compliance behaviors that an LLM wouldn’t reliably know from training. |
| [Build subagents](https://learn.microsoft.com/en-us/azure/sre-agent/subagent-builder-scenarios) | configuration | 0.60 | Covers scenarios and configuration patterns for subagent builder, including connecting observability tools, knowledge bases, and triggers/schedules—likely includes product-specific configuration options. |
| [Incident management](https://learn.microsoft.com/en-us/azure/sre-agent/incident-management) | best-practices | 0.60 | Explains how SRE Agent processes incidents and takes actions based on configuration; likely includes product-specific recommendations and edge cases for incident handling. |
| [Memory system](https://learn.microsoft.com/en-us/azure/sre-agent/memory-system) | configuration | 0.60 | Explains how to add runbooks, standards, and context to the memory system; likely includes product-specific fields and behaviors for knowledge retrieval. |
| [Subagents](https://learn.microsoft.com/en-us/azure/sre-agent/subagent-builder-overview) | configuration | 0.60 | Overview of subagent builder focused on creating and customizing subagents; expected to detail configuration options for incident response, schedules, and knowledge sources. |

## Unclassified Pages

| TOC Title | Confidence | Reason |
|-----------|------------|--------|
| [Build incident response plans](https://learn.microsoft.com/en-us/azure/sre-agent/incident-response-plan) | 0.45 | Incident response plans are described conceptually (filtering, autonomy levels, instructions); no explicit parameter tables or numeric thresholds indicated. |
| [Multi-cause investigation](https://learn.microsoft.com/en-us/azure/sre-agent/deep-investigation) | 0.40 | Deep investigation is a feature/workflow description; summary does not indicate concrete config parameters, limits, or error mappings. |
| [Billing](https://learn.microsoft.com/en-us/azure/sre-agent/billing) | 0.30 | Billing description appears conceptual (explaining always-on vs task-based actions) without clear indication of specific rates, numeric billing metrics, or tier matrices; more likely high-level pricing behavior than expert configuration or limits. |
| [Diagnose your first incident](https://learn.microsoft.com/en-us/azure/sre-agent/usage) | 0.30 | How-to style usage/creation of an agent but described at a conceptual/tutorial level; no detailed config tables, limits, or error mappings. |
| [About Azure SRE Agent](https://learn.microsoft.com/en-us/azure/sre-agent/overview) | 0.20 | High-level product overview of Azure SRE Agent; no concrete limits, configs, error codes, or role definitions. |
| [Starter prompts](https://learn.microsoft.com/en-us/azure/sre-agent/prompts) | 0.20 | Starter prompts are usage examples, not configuration, limits, or troubleshooting references. |
| [Ask the agent for help](https://learn.microsoft.com/en-us/azure/sre-agent/ask-agent) | 0.10 | Explains learning via chat and references prompt library; no product-specific parameters, limits, or troubleshooting content. |
