---
name: azure-monitor
description: Expert knowledge for Azure Monitor development including troubleshooting, configuration, limits & quotas, deployment, best practices, integrations & coding patterns, security, comparing x vs. y, and architecture & design patterns. Use when building, debugging, or optimizing Azure Monitor applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Azure Monitor Skill

This skill provides expert guidance for Azure Monitor development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Apply Azure autoscale patterns for workloads | https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-common-scale-patterns |
| Design an enterprise monitoring architecture with Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/enterprise-monitoring-architecture |
| Design NSP scenarios for Azure Monitor resources | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/network-security-perimeter-scenarios |
| Design Azure Monitor Logs architecture using WAF | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/best-practices-logs |
| Choose Log Analytics table plans by data usage | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/logs-table-plans |
| Design Azure Monitor Private Link architectures | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/private-link-design |
| Design single vs multiple Log Analytics workspaces | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/workspace-design |
| Design and operate replicated Log Analytics workspaces | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/workspace-replication |
| Plan migration from self-hosted Prometheus to Azure Monitor managed service | https://learn.microsoft.com/en-us/azure/azure-monitor/metrics/prometheus-migrate |

### Best Practices
| Topic | URL |
|-------|-----|
| Best practices for migrating from MMA to Azure Monitor Agent | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/azure-monitor-agent-migration |
| Use AMA Migration Helper workbook to plan agent migration | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/azure-monitor-agent-migration-helper-workbook |
| Migrate from WAD/LAD diagnostics extensions to Azure Monitor Agent | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/azure-monitor-agent-migration-wad-lad |
| Apply best practices for Copilot observability agent | https://learn.microsoft.com/en-us/azure/azure-monitor/aiops/observability-agent-best-practices |
| Optimize Azure Monitor log alert queries | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-log-query |
| Apply Azure Monitor alerting best practices | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/best-practices-alerts |
| Implement autoscale best practices across services | https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-best-practices |
| Avoid autoscale flapping with tuned rules | https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-flapping |
| Implement WAF-aligned monitoring for AKS and Arc clusters | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/best-practices-containers |
| Optimize Container Insights monitoring costs in Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-cost |
| Create log-based alerts for AKS container performance | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-log-alerts |
| Design cost-effective alerting for AKS in Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/cost-effective-alerting |
| Apply Kubernetes monitoring best practices in Azure | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/monitor-kubernetes |
| Apply best practices for Azure Monitor data collection rules | https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-rule-best-practices |
| Use sample KQL transformations for Azure Monitor ingestion | https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-transformations-samples |
| Optimize Azure Monitor costs with configuration | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/best-practices-cost |
| Apply Azure Monitor best practices for multicloud monitoring | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/best-practices-multicloud |
| Configure Azure Monitor for operational excellence | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/best-practices-operation |
| Monitor VM performance with Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/best-practices-performance |
| Apply reliability best practices in Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/best-practices-reliability |
| Analyze Log Analytics usage to control Azure Monitor costs | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/analyze-usage |
| Migrate from HTTP Data Collector API to Logs Ingestion API | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/custom-logs-migrate |
| Monitor Log Analytics operational issues using Operation table | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/monitor-workspace |
| Identify and manage personal data in Azure Monitor Logs | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/personal-data-mgmt |
| Optimize Azure Monitor log queries for performance | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/query-optimization |
| Best practices for scaling Azure Monitor Prometheus workspaces | https://learn.microsoft.com/en-us/azure/azure-monitor/metrics/azure-monitor-workspace-scaling-best-practice |
| Optimize metrics usage and cost in Azure Monitor workspaces | https://learn.microsoft.com/en-us/azure/azure-monitor/metrics/metrics-usage-insights |
| Apply PromQL best practices to OpenTelemetry metrics | https://learn.microsoft.com/en-us/azure/azure-monitor/metrics/prometheus-opentelemetry-best-practices |
| Query system and Guest OS metrics with PromQL | https://learn.microsoft.com/en-us/azure/azure-monitor/metrics/prometheus-system-metrics-best-practices |
| Choose and use Azure Monitor visualization tools effectively | https://learn.microsoft.com/en-us/azure/azure-monitor/visualize/best-practices-visualize |
| Apply VM monitoring best practices in Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/best-practices-vm |
| Design alert rules for VM monitoring in Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/monitor-virtual-machine-alerts |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Replace Azure alertsSummary API with Resource Graph queries | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/migrate-from-alerts-summary-api |
| Choose between Azure Monitor metrics data plane and export | https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-plane-versus-metrics-export |
| Choose between SCOM and Azure Monitor for workloads | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/azure-monitor-operations-manager |
| Interpret Azure Monitor billing meter names | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/cost-meters |

### Configuration
| Topic | URL |
|-------|-----|
| Configure Azure Monitor Agent via data collection rules | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/agent-settings |
| Migrate MMA custom text log tables to AMA DCR custom logs | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/azure-monitor-agent-custom-text-log-migration |
| Map data field differences between MMA and AMA | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/azure-monitor-agent-data-field-differences |
| Configure network settings for Azure Monitor Agent connectivity | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/azure-monitor-agent-network-configuration |
| Use Azure Policy to auto-install Azure Monitor Agent | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/azure-monitor-agent-policy |
| Enable Azure Monitor Agent network isolation with Private Link | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/azure-monitor-agent-private-link |
| Configure Windows Diagnostics extension to send guest OS metrics to Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/collect-custom-metrics-guestos-resource-manager-vm |
| Configure Windows diagnostics extension schema for Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/diagnostics-extension-schema-windows |
| Azure Diagnostics (WAD) schema versions and settings | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/diagnostics-extension-versions |
| Install and configure Azure Diagnostics extension for Windows | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/diagnostics-extension-windows-install |
| Configure Log Analytics gateway for Azure Monitor connectivity | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/gateway |
| Use ARM templates to deploy Azure Monitor agents | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/resource-manager-agent |
| Enable and use Azure Monitor common alert schema | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-common-schema |
| Configure query-based metric alerts with PromQL | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-create-query-based-metric-alerts |
| Define Azure Monitor alert rules via CLI, PowerShell, ARM | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-create-rule-cli-powershell-arm |
| Configure custom email subjects for log alerts | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-customize-email-subject-how-to |
| Use noncommon Azure Monitor alert schema definitions | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-non-common-schema-definitions |
| Upgrade smart detection to alerts in App Insights | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-smart-detections-migration |
| Configure smart detection rules via ARM templates | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/proactive-arm-config |
| Configure smart detection in Application Insights | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/proactive-diagnostics |
| Use smart detection for failure anomalies | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/proactive-failure-diagnostics |
| Monitor trace severity ratio with smart detection | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/proactive-trace-severity |
| Create Azure Monitor action groups via ARM | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/resource-manager-action-groups |
| Configure activity log alerts with ARM templates | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/resource-manager-alerts-activity-log |
| Create metric alerts using ARM templates | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/resource-manager-alerts-metric |
| Configure resource health alerts using ARM | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/resource-manager-alerts-resource-health |
| Configure service health alerts via ARM templates | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/resource-manager-alerts-service-health |
| Use smart detection for performance anomalies | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/smart-detection-performance |
| Configure Application Insights connection strings | https://learn.microsoft.com/en-us/azure/azure-monitor/app/connection-strings |
| Create and configure workspace-based Application Insights | https://learn.microsoft.com/en-us/azure/azure-monitor/app/create-workspace-resource |
| Configure JMX metrics for Application Insights Java | https://learn.microsoft.com/en-us/azure/azure-monitor/app/java-jmx-metrics-configuration |
| Configure Application Insights Java agent settings | https://learn.microsoft.com/en-us/azure/azure-monitor/app/java-standalone-config |
| Configure sampling overrides for Java Application Insights | https://learn.microsoft.com/en-us/azure/azure-monitor/app/java-standalone-sampling-overrides |
| Configure telemetry processors for Java Application Insights | https://learn.microsoft.com/en-us/azure/azure-monitor/app/java-standalone-telemetry-processors |
| Use telemetry processor configuration examples in Java | https://learn.microsoft.com/en-us/azure/azure-monitor/app/java-standalone-telemetry-processors-examples |
| Set up Application Insights JavaScript SDK tracking | https://learn.microsoft.com/en-us/azure/azure-monitor/app/javascript-sdk |
| Configure Application Insights JavaScript SDK options | https://learn.microsoft.com/en-us/azure/azure-monitor/app/javascript-sdk-configuration |
| Configure OpenTelemetry settings in Application Insights | https://learn.microsoft.com/en-us/azure/azure-monitor/app/opentelemetry-configuration |
| Enable OpenTelemetry data collection in Application Insights | https://learn.microsoft.com/en-us/azure/azure-monitor/app/opentelemetry-enable |
| Understand Statsbeat telemetry in Application Insights | https://learn.microsoft.com/en-us/azure/azure-monitor/app/statsbeat |
| Configure autoscale on custom metrics for web apps | https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-custom-metric |
| Enable and route Azure autoscale diagnostics | https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-diagnostics |
| Configure and interpret Azure autoscale settings | https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-understanding-settings |
| Configure VM scale set autoscale via PowerShell | https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-using-powershell |
| Configure autoscale email and webhook notifications | https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-webhook-email |
| Switch Container Insights to Managed Prometheus visualizations | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-experience-v2 |
| Configure GPU monitoring for Kubernetes with Container insights | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-gpu-monitoring |
| View real-time Kubernetes metrics with Container Insights Live Data | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-livedata-metrics |
| Query Container insights logs and metrics in Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-log-query |
| Configure and migrate to ContainerLogV2 schema in Container Insights | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-logs-schema |
| Manage and configure the Container insights agent lifecycle | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-manage-agent |
| Configure multitenant managed logging in Container Insights | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-multitenant |
| Configure AKS network monitoring with Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-network-monitoring |
| Configure persistent volume monitoring in Container insights | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-persistent-volumes |
| Access and configure Syslog collection for AKS nodes | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-syslog |
| Configure log throttling and monitor loss in Container Insights | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-throttling |
| Implement DCR transformations for Kubernetes container logs | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-transformations |
| Configure workspace transformations for AKS control plane logs | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/control-plane-transformations |
| Configure Kubernetes container log collection via ConfigMap | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/kubernetes-data-collection-configmap |
| Customize and filter Kubernetes data collection in Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/kubernetes-data-collection-configure |
| Enable recommended metric alert rules for Kubernetes clusters | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/kubernetes-metric-alerts |
| Disable Prometheus metrics and log collection for Kubernetes | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/kubernetes-monitoring-disable |
| Enable Azure Monitor features on AKS clusters | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/kubernetes-monitoring-enable |
| Configure monitoring for Arc-enabled Kubernetes clusters | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/kubernetes-monitoring-enable-arc |
| Use Kubernetes workbooks to analyze Azure Monitor data | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/kubernetes-workbooks |
| Configure Prometheus metrics to multiple Azure Monitor workspaces | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/prometheus-metrics-multiple-workspaces |
| Create custom Prometheus scrape jobs with ConfigMap | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/prometheus-metrics-scrape-configmap |
| Customize Prometheus metrics scraping via ConfigMap in Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/prometheus-metrics-scrape-configuration |
| Create custom Prometheus scrape jobs using CRDs | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/prometheus-metrics-scrape-crd |
| Default Prometheus metrics targets and rules in Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/prometheus-metrics-scrape-default |
| Configure data collection endpoints for Azure Monitor ingestion | https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-endpoint-overview |
| Manage Azure Monitor data collection rule associations | https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-rule-associations |
| Create and edit Azure Monitor data collection rules | https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-rule-create-edit |
| Use sample Azure Monitor data collection rule definitions | https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-rule-samples |
| Understand JSON structure of Azure Monitor data collection rules | https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-rule-structure |
| Configure transformations in Azure Monitor data collection rules | https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-transformations |
| Create and test Azure Monitor transformation queries in DCRs | https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-transformations-create |
| Use supported KQL features in Azure Monitor transformations | https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-transformations-kql |
| Configure Azure Monitor edge data collection pipeline | https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/edge-pipeline-configure |
| Configure metrics export with Azure Monitor data collection rules | https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/metrics-export-create |
| Understand DCR JSON structure for Azure Monitor metrics export | https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/metrics-export-structure |
| Configure data sources and collection methods in Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/data-sources |
| Configure monitoring coverage recommendations in Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/monitoring-coverage |
| Use ARM templates to configure Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/resource-manager-samples |
| Create and configure Azure Monitor health model resources | https://learn.microsoft.com/en-us/azure/azure-monitor/health-models/create |
| Use the designer to configure Azure Monitor health models | https://learn.microsoft.com/en-us/azure/azure-monitor/health-models/designer |
| Set Prefer header options for Logs Query API | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/prefer-options |
| Configure pricing tier for a Log Analytics workspace | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/change-pricing-tier |
| Create and manage custom tables in Azure Monitor Logs | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/create-custom-table |
| Configure Auxiliary plan custom tables for low-cost logs | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/create-custom-table-auxiliary |
| Configure data retention for Log Analytics tables | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/data-retention-configure |
| Configure health monitoring and alerts for Log Analytics workspaces | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/log-analytics-workspace-health |
| Use standard columns in Azure Monitor log records | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/log-standard-columns |
| Configure continuous data export from Log Analytics workspaces | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/logs-data-export |
| Configure Azure Monitor Logs dedicated clusters | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/logs-dedicated-clusters |
| Configure Log Analytics tables for cost and access | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/manage-logs-tables |
| Configure Azure Monitor Private Link scopes and endpoints | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/private-link-configure |
| Link customer-managed storage accounts to Log Analytics | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/private-storage |
| Understand and use Azure Monitor query audit logs | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/query-audit |
| Configure and share Azure Monitor query packs | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/query-packs |
| Deploy Azure Monitor log queries via ARM | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/resource-manager-log-queries |
| Restore and dismiss hot-cache log data in Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/restore |
| Set up prerequisites for Logs Ingestion API via PowerShell | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/set-up-logs-ingestion-api-prerequisites |
| Configure and manage Log Analytics summary rules | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/summary-rules |
| Add ingestion-time transformations using ARM templates for Azure Monitor Logs | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/tutorial-workspace-transformations-api |
| Add workspace transformations in Azure Monitor via portal | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/tutorial-workspace-transformations-portal |
| Create and manage Azure Monitor workspaces | https://learn.microsoft.com/en-us/azure/azure-monitor/metrics/azure-monitor-workspace-manage |
| Technical configuration details for Azure Monitor Prometheus service | https://learn.microsoft.com/en-us/azure/azure-monitor/metrics/prometheus-metrics-details |
| Configure rule groups in Azure Monitor managed Prometheus | https://learn.microsoft.com/en-us/azure/azure-monitor/metrics/prometheus-rule-groups |
| Configure and route Azure Monitor activity log data | https://learn.microsoft.com/en-us/azure/azure-monitor/platform/activity-log |
| Understand Azure Activity Log event schema by category | https://learn.microsoft.com/en-us/azure/azure-monitor/platform/activity-log-schema |
| Configure diagnostic settings for Azure Monitor metrics and logs | https://learn.microsoft.com/en-us/azure/azure-monitor/platform/diagnostic-settings |
| Configure built-in policies for Azure Monitor diagnostic settings | https://learn.microsoft.com/en-us/azure/azure-monitor/platform/diagnostic-settings-policy-built-in |
| Configure Azure Monitor resource log destinations and settings | https://learn.microsoft.com/en-us/azure/azure-monitor/platform/resource-logs |
| Use Azure resource logs services and event schemas | https://learn.microsoft.com/en-us/azure/azure-monitor/platform/resource-logs-schema |
| Apply diagnostic settings with ARM templates | https://learn.microsoft.com/en-us/azure/azure-monitor/platform/resource-manager-diagnostic-settings |
| Configure Application Insights Profiler for .NET in Azure | https://learn.microsoft.com/en-us/azure/azure-monitor/profiler/profiler-settings |
| Reference Azure Monitor resource log categories and schemas | https://learn.microsoft.com/en-us/azure/azure-monitor/reference/logs-index |
| Reference Azure Monitor metrics by resource type | https://learn.microsoft.com/en-us/azure/azure-monitor/reference/metrics-index |
| Reference field definitions for Azure Monitor log tables | https://learn.microsoft.com/en-us/azure/azure-monitor/reference/tables-index |
| Convert SCOM management packs into Azure Monitor data collection rules | https://learn.microsoft.com/en-us/azure/azure-monitor/scom-manage-instance/convert-management-packs-into-data-collection-rules |
| Configure Snapshot Debugger for .NET exceptions | https://learn.microsoft.com/en-us/azure/azure-monitor/snapshot-debugger/snapshot-debugger |
| Enable Snapshot Debugger for .NET on App Service | https://learn.microsoft.com/en-us/azure/azure-monitor/snapshot-debugger/snapshot-debugger-app-service |
| Enable Snapshot Debugger for .NET in Functions | https://learn.microsoft.com/en-us/azure/azure-monitor/snapshot-debugger/snapshot-debugger-function-app |
| Enable Snapshot Debugger on VMs and Service Fabric | https://learn.microsoft.com/en-us/azure/azure-monitor/snapshot-debugger/snapshot-debugger-vm |
| Deploy Azure Monitor workbooks using ARM | https://learn.microsoft.com/en-us/azure/azure-monitor/visualize/resource-manager-workbooks |
| Manage Azure Monitor workbook resources and settings | https://learn.microsoft.com/en-us/azure/azure-monitor/visualize/workbooks-manage |
| Configure data collection rules for VM monitoring | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/data-collection |
| Configure Windows Firewall log collection with Azure Monitor Agent | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/data-collection-firewall-logs |
| Configure IIS log collection with Azure Monitor Agent | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/data-collection-iis |
| Collect JSON log files with Azure Monitor Agent | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/data-collection-log-json |
| Collect custom text log files with Azure Monitor Agent | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/data-collection-log-text |
| Configure performance counter collection with Azure Monitor Agent | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/data-collection-performance |
| Configure SNMP trap collection with Azure Monitor Agent | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/data-collection-snmp-data |
| Configure Syslog event collection with Azure Monitor Agent | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/data-collection-syslog |
| Configure Windows event collection with Azure Monitor Agent | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/data-collection-windows-events |
| Configure and deploy Azure Monitor agent to VMs | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/monitor-virtual-machine-agent |
| Configure VM data collection rules in Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/monitor-virtual-machine-data-collection |
| Install and run Performance Diagnostics reports on Azure VMs | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/performance-diagnostics-run |
| Configure Azure Monitor Agent DCRs to send VM data to Fabric and ADX | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/send-fabric-destination |
| Manage VM insights Dependency Agent requirements and upgrades | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/vminsights-dependency-agent |
| Uninstall VM insights Dependency Agent from Azure VMs and scale sets | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/vminsights-dependency-agent-uninstall |
| Enable VM insights on Azure VMs and scale sets | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/vminsights-enable |
| Enable VM insights on intermittently connected Windows clients | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/vminsights-enable-client |
| Enable VM insights at scale using Azure Policy | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/vminsights-enable-policy |
| Migrate VM insights from Log Analytics agent to Azure Monitor agent | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/vminsights-migrate-agent |
| Migrate from deprecated VM insights DCR deployment policies | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/vminsights-migrate-deprecated-policies |
| Migrate VM insights monitoring to OpenTelemetry metrics | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/vminsights-opentelemetry |
| Disable VM insights monitoring for Azure virtual machines | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/vminsights-optout |
| Create and customize VM insights workbooks for reporting | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/vminsights-workbooks |

### Deployment
| Topic | URL |
|-------|-----|
| Install, update, and manage Azure Monitor Agent on VMs | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/azure-monitor-agent-manage |
| Review Azure Monitor Agent VM and Arc requirements | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/azure-monitor-agent-requirements |
| Check supported operating systems for Azure Monitor Agent | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/azure-monitor-agent-supported-operating-systems |
| Install and manage Azure Monitor Agent on Windows clients | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/azure-monitor-agent-windows-client |
| Migrate log alert rules to ScheduledQueryRules API | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-log-api-switch |
| Manage legacy log search alert rules in portal | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-manage-alerts-previous-version |
| Update alert rules after cross-region resource moves | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-resource-move |
| Deploy Application Insights Agent for IIS web apps | https://learn.microsoft.com/en-us/azure/azure-monitor/app/application-insights-asp-net-agent |
| Enable codeless Application Insights on AKS workloads | https://learn.microsoft.com/en-us/azure/azure-monitor/app/kubernetes-codeless |
| Enable Container insights for hybrid and Azure Stack Kubernetes | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-hybrid-setup |
| Use Container Insights region mappings with Log Analytics | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-region-mapping |
| Migrate from Container Monitoring Solution to Container insights | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-transition-solution |
| Use availability zones for Log Analytics resilience | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/availability-zones |
| Enable Application Insights Profiler for .NET on Azure App Service | https://learn.microsoft.com/en-us/azure/azure-monitor/profiler/profiler |
| Enable .NET Profiler for ASP.NET Core apps on Linux App Service | https://learn.microsoft.com/en-us/azure/azure-monitor/profiler/profiler-aspnetcore-linux |
| Enable Application Insights Profiler for Azure Functions apps | https://learn.microsoft.com/en-us/azure/azure-monitor/profiler/profiler-azure-functions |
| Enable Application Insights Profiler for .NET in Azure containers | https://learn.microsoft.com/en-us/azure/azure-monitor/profiler/profiler-containers |
| Deploy Application Insights Profiler for Azure Service Fabric applications | https://learn.microsoft.com/en-us/azure/azure-monitor/profiler/profiler-servicefabric |
| Run Application Insights Profiler for .NET on Azure virtual machines | https://learn.microsoft.com/en-us/azure/azure-monitor/profiler/profiler-vm |
| Migrate from SCOM Managed Instance to Azure Monitor DCRs | https://learn.microsoft.com/en-us/azure/azure-monitor/scom-manage-instance/migrate-to-azure-monitor |
| Move Azure Workbook templates across regions | https://learn.microsoft.com/en-us/azure/azure-monitor/visualize/workbook-templates-move-region |
| Deploy Azure Monitor workbooks with ARM templates | https://learn.microsoft.com/en-us/azure/azure-monitor/visualize/workbooks-automate |
| Move Azure Monitor workbooks between regions | https://learn.microsoft.com/en-us/azure/azure-monitor/visualize/workbooks-move-region |
| Deploy and manage PerfInsights VM extension on Windows | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/performance-diagnostics-extension |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Generate AMA data collection rules from workspace configuration | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/azure-monitor-agent-migration-data-collection-rule-generator |
| Use MMA Discovery and Removal Utility after AMA migration | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/azure-monitor-agent-mma-removal-tool |
| Configure ARM template to send VMSS guest metrics | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/collect-custom-metrics-guestos-resource-manager-vmss |
| Configure classic Windows VM diagnostics to Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/collect-custom-metrics-guestos-vm-classic |
| Configure classic Cloud Services metrics to Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/collect-custom-metrics-guestos-vm-cloud-service-classic |
| Use Telegraf to send Linux VM metrics to Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/collect-custom-metrics-linux-telegraf |
| Route Azure Diagnostics extension logs to Azure Monitor Logs | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/diagnostics-extension-logs |
| Stream Azure Diagnostics extension data to Event Hubs | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/diagnostics-extension-stream-event-hubs |
| Send Azure Diagnostics extension data to Application Insights | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/diagnostics-extension-to-application-insights |
| Consume Azure activity log alerts via webhook payload | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/activity-log-alerts-webhook |
| Configure webhook payloads for log search alerts | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-log-webhook |
| Integrate Azure Monitor alerts with Logic Apps | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-logic-apps |
| Use Azure Monitor common alert payload schemas | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-payload-samples |
| Migrate ServiceNow ITSM actions to Secure Webhook | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/itsm-convert-servicenow-to-webhook |
| Connect ServiceNow to Azure Monitor ITSM Connector | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/itsmc-connections-servicenow |
| Connect BMC Helix to Azure Monitor via Secure Webhook | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/itsmc-secure-webhook-connections-bmc |
| Configure ServiceNow with Azure Monitor Secure Webhook | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/itsmc-secure-webhook-connections-servicenow |
| Build Grafana dashboards for Application Insights data in Azure | https://learn.microsoft.com/en-us/azure/azure-monitor/app/grafana-dashboards |
| Enable Click Analytics feature for JS Application Insights | https://learn.microsoft.com/en-us/azure/azure-monitor/app/javascript-feature-extensions |
| Integrate JavaScript frameworks with Application Insights | https://learn.microsoft.com/en-us/azure/azure-monitor/app/javascript-framework-extensions |
| Monitor AKS apps via OTLP and Application Insights | https://learn.microsoft.com/en-us/azure/azure-monitor/app/kubernetes-open-protocol |
| Customize OpenTelemetry integration with Application Insights | https://learn.microsoft.com/en-us/azure/azure-monitor/app/opentelemetry-add-modify |
| Filter and protect OpenTelemetry data in Application Insights | https://learn.microsoft.com/en-us/azure/azure-monitor/app/opentelemetry-filter |
| Integrate Application Insights work items with GitHub and Azure DevOps | https://learn.microsoft.com/en-us/azure/azure-monitor/app/work-item-integration |
| Configure Container insights to collect Prometheus metrics | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-prometheus-logs |
| Integrate KEDA with AKS using Azure Monitor Prometheus metrics | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/integrate-keda |
| Configure Argo CD monitoring with Azure Managed Prometheus | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/prometheus-argo-cd-integration |
| Collect NVIDIA GPU metrics via DCGM exporter in Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/prometheus-dcgm-integration |
| Configure Elasticsearch monitoring with Azure Managed Prometheus | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/prometheus-elasticsearch-integration |
| Integrate common workloads with Azure Managed Prometheus | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/prometheus-exporters |
| Collect Istio service mesh metrics with Azure Managed Prometheus | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/prometheus-istio-integration |
| Configure Kafka monitoring with Azure Managed Prometheus | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/prometheus-kafka-integration |
| Navigate Azure Monitor REST API operation groups | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/azure-monitor-rest-api-index |
| Configure OTLP native ingestion to Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/opentelemetry-protocol-ingestion |
| Query Azure resource logs via Logs API | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/azure-resource-queries |
| Format requests for Azure Monitor Logs API | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/request-format |
| Parse Azure Monitor Logs API JSON responses | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/response-format |
| Use Delete Data API to remove Log Analytics records | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/delete-log-data |
| Ingest Azure Event Hubs data into Azure Monitor Logs | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/ingest-logs-event-hub |
| Integrate Azure Monitor Logs with Power BI and Excel | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/log-powerbi |
| Export Azure Monitor Logs to Storage via Logic Apps | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/logs-export-logic-app |
| Integrate notebooks with Azure Monitor Logs data | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/notebooks-azure-monitor-logs |
| Create and query Azure Monitor search jobs | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/search-jobs |
| Configure Logs Ingestion API with ARM templates | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/tutorial-logs-ingestion-api |
| Sample code for Azure Monitor Logs Ingestion API | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/tutorial-logs-ingestion-code |
| Configure Logs Ingestion API via Azure portal tutorial | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/tutorial-logs-ingestion-portal |
| Send custom metrics to Azure Monitor via REST API | https://learn.microsoft.com/en-us/azure/azure-monitor/metrics/metrics-store-custom-rest-api |
| Migrate Azure Monitor metrics API calls to getBatch | https://learn.microsoft.com/en-us/azure/azure-monitor/metrics/migrate-to-batch-api |
| Query Prometheus metrics via Azure Monitor REST API | https://learn.microsoft.com/en-us/azure/azure-monitor/metrics/prometheus-api-promql |
| Configure Grafana with Azure Monitor managed Prometheus | https://learn.microsoft.com/en-us/azure/azure-monitor/metrics/prometheus-grafana |
| Configure Prometheus remote-write to Azure Monitor managed service | https://learn.microsoft.com/en-us/azure/azure-monitor/metrics/prometheus-remote-write |
| Use resource-scoped PromQL queries with Azure Monitor workspace metrics | https://learn.microsoft.com/en-us/azure/azure-monitor/metrics/prometheus-resource-scoped-queries |
| Assign Code Optimizations items to GitHub Copilot | https://learn.microsoft.com/en-us/azure/azure-monitor/optimization-insights/code-optimizations-github-copilot |
| Use Code Optimizations extension in Visual Studio | https://learn.microsoft.com/en-us/azure/azure-monitor/optimization-insights/code-optimizations-vs-extension |
| Use Code Optimizations extension in VS Code | https://learn.microsoft.com/en-us/azure/azure-monitor/optimization-insights/code-optimizations-vscode-extension |
| Retrieve Azure Activity Log via Monitor REST API | https://learn.microsoft.com/en-us/azure/azure-monitor/platform/rest-activity-log |
| Use Azure Monitor REST API for metrics and logs | https://learn.microsoft.com/en-us/azure/azure-monitor/platform/rest-api-walkthrough |
| Stream Azure Monitor data to Event Hubs and partners | https://learn.microsoft.com/en-us/azure/azure-monitor/platform/stream-monitoring-data-event-hubs |
| Instrument custom .NET requests for Profiler | https://learn.microsoft.com/en-us/azure/azure-monitor/profiler/profiler-trackrequests |
| Transform workbook JSON data using JSONPath | https://learn.microsoft.com/en-us/azure/azure-monitor/visualize/workbooks-jsonpath |
| Query VM insights map data with Log Analytics | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/vminsights-log-query |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Review Azure Monitor Agent extension version support | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/azure-monitor-agent-extension-versions |
| Azure Monitor Agent performance and throughput benchmarks | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/azure-monitor-agent-performance |
| Understand retention and behavior of Azure alert instances | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-manage-alert-instances |
| Monitor and interpret log search alert rule health | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/log-alert-rule-health |
| Deploy log search alert rules with ARM templates | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/resource-manager-alerts-log |
| Deploy simple log search alerts via ARM | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/resource-manager-alerts-simple-log-search-alerts |
| Configure and understand Application Insights availability tests | https://learn.microsoft.com/en-us/azure/azure-monitor/app/availability |
| Use predictive autoscale for VM scale sets | https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-predictive |
| Enable high-scale container log collection in Container Insights | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-high-scale |
| Configure autoscaling for Azure Managed Prometheus addon pods | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/prometheus-metrics-scrape-autoscaling |
| Performance and scale guidance for Prometheus scraping in Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/prometheus-metrics-scrape-scale |
| Review Azure Monitor service limits and quotas | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/service-limits |
| Use batched queries with Azure Monitor Logs API | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/batch-queries |
| Understand caching behavior in Logs Query API | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/cache |
| Run cross-workspace queries with resource limits | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/cross-workspace-queries |
| Migrate from batch and beta Logs APIs | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/migrate-batch-and-beta |
| Configure query execution timeouts for Logs API | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/timeouts |
| Identify tables supporting Basic table plan in Logs | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/basic-logs-azure-tables |
| Query Basic and Auxiliary log tables with limitations | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/basic-logs-query |
| Understand Azure Monitor Logs cost and data sizing | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/cost-logs |
| Set and manage daily ingestion caps for Log Analytics | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/daily-cap |
| Understand and manage Azure Monitor log ingestion latency | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/data-ingestion-time |
| Identify tables supporting ingestion-time transformations | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/tables-feature-support |
| Monitor Prometheus metrics ingestion limits in Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/metrics/azure-monitor-workspace-monitor-ingest-limits |
| Review Azure Workbooks data source and parameter limits | https://learn.microsoft.com/en-us/azure/azure-monitor/visualize/workbooks-limits |

### Security
| Topic | URL |
|-------|-----|
| Secure webhook configuration for Azure Monitor ITSM | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/it-service-management-connector-secure-webhook-connections |
| Azure configuration for Secure Webhook ITSM integration | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/itsm-connector-secure-webhook-connections-azure-configuration |
| Enable Microsoft Entra authentication for Application Insights | https://learn.microsoft.com/en-us/azure/azure-monitor/app/azure-ad-authentication |
| Understand IP handling and geolocation in Application Insights | https://learn.microsoft.com/en-us/azure/azure-monitor/app/ip-collection |
| Migrate Container insights to managed identity authentication | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-authentication |
| Configure secure access to Live Data in Container insights | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-livedata-setup |
| Configure firewall and proxy for AKS monitoring with Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/kubernetes-monitoring-firewall |
| Secure AKS monitoring traffic with Private Link and AMPLS | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/kubernetes-monitoring-private-link |
| Configure Prometheus remote write with Entra authentication | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/prometheus-remote-write-active-directory |
| Use Entra Workload ID for Prometheus remote write | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/prometheus-remote-write-azure-workload-identity |
| Configure Prometheus remote write with managed identity | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/prometheus-remote-write-managed-identity |
| Configure network and firewall access for Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/azure-monitor-network-access |
| Securely deploy and configure Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/best-practices-security |
| Configure Network Security Perimeter for Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/network-security-perimeter |
| Apply Azure Monitor built-in policy definitions | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/policy-reference |
| Configure RBAC roles and permissions for Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/roles-permissions-security |
| Configure RBAC roles and permissions for Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/roles-permissions-security |
| Apply Azure Policy compliance controls to Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/security-controls-policy |
| Apply Azure Policy compliance controls to Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/security-controls-policy |
| Configure authentication for Azure Monitor Logs API | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/access-api |
| Register Azure app for Log Analytics API access | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/register-app-for-token |
| Configure customer-managed keys for Azure Monitor Logs | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/customer-managed-keys |
| Implement granular RBAC for Log Analytics data access | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/granular-rbac-log-analytics |
| Configure row-level granular RBAC in Log Analytics | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/granular-rbac-use-case |
| Use KQL for Azure Monitor log queries securely | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/log-query-overview |
| Configure access control for Log Analytics workspaces | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/manage-access |
| Configure table-level RBAC for Log Analytics workspaces | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/manage-table-access |
| Secure Azure Monitor access with Private Link | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/private-link-security |
| Configure access control for Azure Monitor workspaces | https://learn.microsoft.com/en-us/azure/azure-monitor/metrics/azure-monitor-workspace-manage-access |
| Configure BYOS storage for Profiler and Snapshot Debugger with Private Link | https://learn.microsoft.com/en-us/azure/azure-monitor/profiler/profiler-bring-your-own-storage |
| Call Azure Managed Grafana APIs with Entra ID and service principals | https://learn.microsoft.com/en-us/azure/azure-monitor/visualize/visualize-call-grafana-api |
| Secure workbook content with customer-managed storage | https://learn.microsoft.com/en-us/azure/azure-monitor/visualize/workbooks-bring-your-own-storage |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot Log Analytics agent for Linux | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/agent-linux-troubleshoot |
| Troubleshoot Log Analytics agent for Windows | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/agent-windows-troubleshoot |
| Troubleshoot Azure Monitor Agent on Linux VMs and scale sets | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/azure-monitor-agent-troubleshoot-linux-vm |
| Troubleshoot rsyslog integration with Azure Monitor Agent on Linux | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/azure-monitor-agent-troubleshoot-linux-vm-rsyslog |
| Troubleshoot Azure Monitor Agent on Windows Arc-enabled servers | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/azure-monitor-agent-troubleshoot-windows-arc |
| Troubleshoot Azure Monitor Agent on Windows VMs and scale sets | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/azure-monitor-agent-troubleshoot-windows-vm |
| Troubleshoot Azure Diagnostics extension issues | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/diagnostics-extension-troubleshooting |
| Run Linux Azure Monitor Agent Troubleshooter for diagnostics | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/troubleshooter-ama-linux |
| Run Windows Azure Monitor Agent Troubleshooter for diagnostics | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/troubleshooter-ama-windows |
| Troubleshoot Azure Log Analytics VM extension problems | https://learn.microsoft.com/en-us/azure/azure-monitor/agents/vmext-troubleshoot |
| Troubleshoot Azure Copilot observability investigations | https://learn.microsoft.com/en-us/azure/azure-monitor/aiops/observability-agent-troubleshooting |
| Create and troubleshoot tenant-level service health alerts | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-create-tenant-level-service-heath-alerts |
| Troubleshoot common Azure Monitor alert issues | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-troubleshoot |
| Resolve issues with Azure log alert rules | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-troubleshoot-log |
| Diagnose and fix Azure metric alert problems | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-troubleshoot-metric |
| Use ITSMC dashboard to investigate connector errors | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/itsmc-dashboard |
| Resolve common ITSMC dashboard connector status errors | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/itsmc-dashboard-errors |
| Fix ServiceNow sync problems for Azure Monitor ITSM | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/itsmc-resync-servicenow |
| Troubleshoot Azure Monitor ITSM Connector issues | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/itsmc-troubleshoot-overview |
| Troubleshoot test action group notification errors | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/test-action-group-errors |
| Troubleshoot OpenTelemetry issues in Application Insights | https://learn.microsoft.com/en-us/azure/azure-monitor/app/opentelemetry-help-support-feedback |
| Troubleshoot telemetry issues using Application Insights SDK stats | https://learn.microsoft.com/en-us/azure/azure-monitor/app/sdk-stats |
| Troubleshoot Azure Monitor autoscale issues | https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-troubleshoot |
| Use Live Data in Container insights for real-time troubleshooting | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-livedata-overview |
| Troubleshoot Container Insights log collection issues | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-troubleshoot |
| Troubleshoot Prometheus metric collection in Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/containers/prometheus-metrics-troubleshoot |
| Monitor and troubleshoot Azure Monitor DCR-based data collection | https://learn.microsoft.com/en-us/azure/azure-monitor/data-collection/data-collection-monitor |
| Troubleshoot Azure Monitor Logs API errors | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/api/errors |
| Troubleshoot stopped data collection in Azure Monitor Logs | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/data-collection-troubleshoot |
| Monitor and troubleshoot ingestion and query issues in Azure Monitor workspaces | https://learn.microsoft.com/en-us/azure/azure-monitor/metrics/azure-monitor-workspace-monitor-health |
| Troubleshoot Azure Monitor metric chart issues | https://learn.microsoft.com/en-us/azure/azure-monitor/metrics/metrics-troubleshoot |
| Troubleshoot Application Insights Code Optimizations | https://learn.microsoft.com/en-us/azure/azure-monitor/optimization-insights/code-optimizations-troubleshoot |
| Troubleshoot Application Insights Profiler for .NET | https://learn.microsoft.com/en-us/azure/azure-monitor/profiler/profiler-troubleshooting |
| FAQ for migrating from Azure Monitor SCOM Managed Instance | https://learn.microsoft.com/en-us/azure/azure-monitor/scom-manage-instance/migration-faq-scom-manage-instance |
| Troubleshoot Application Insights Snapshot Debugger | https://learn.microsoft.com/en-us/azure/azure-monitor/snapshot-debugger/snapshot-debugger-troubleshoot |
| Troubleshoot Azure Monitor workbook-based insights issues | https://learn.microsoft.com/en-us/azure/azure-monitor/visualize/troubleshoot-workbooks |
| Use Performance Diagnostics to troubleshoot Azure VM performance | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/performance-diagnostics |
| Interpret PerfInsights performance reports for Azure VMs | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/performance-diagnostics-analyze |
| Troubleshoot VM insights agent installation and usage issues | https://learn.microsoft.com/en-us/azure/azure-monitor/vm/vminsights-troubleshoot |

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
