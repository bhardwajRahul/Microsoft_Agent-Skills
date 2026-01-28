---
name: logic-apps
description: Expert knowledge for Logic Apps development including integrations & coding patterns, limits & quotas, security, deployment, comparing x vs. y, best practices, configuration, architecture & design patterns, and troubleshooting. Use when building, debugging, or optimizing Logic Apps applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Logic Apps Skill

This skill provides expert guidance for Logic Apps development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Design autonomous AI agent workflows in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/create-autonomous-agent-workflows |
| Design conversational AI agent workflows in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/create-conversational-agent-workflows |
| Design replication workflows for Azure resources | https://learn.microsoft.com/en-us/azure/logic-apps/create-replication-tasks-azure-resources |
| Design Web and REST API Patterns for Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-create-api-app |
| Plan disaster recovery for Logic Apps integration accounts | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-enterprise-integration-b2b-business-continuity |
| Design multi-region disaster recovery for Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/multi-region-disaster-recovery |
| Implement Sequential Convoy Pattern for Service Bus | https://learn.microsoft.com/en-us/azure/logic-apps/send-related-messages-sequential-convoy |
| Implement handoff pattern between AI agents in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/set-up-handoff-agent-workflow |
| Implement prompt chaining with sequential AI agents | https://learn.microsoft.com/en-us/azure/logic-apps/set-up-prompt-chain-agent-workflow |
| Configure zone redundancy for Azure Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/set-up-zone-redundancy-availability-zones |
| Choose single vs multiple AI agents in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/single-versus-multiple-agents |

### Best Practices
| Topic | URL |
|-------|-----|
| Apply migration best practices from BizTalk to Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/biztalk-server-migration-approaches |
| Author and run inline .NET code in Standard Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/create-run-custom-code-functions |
| Apply Error and Exception Handling Patterns in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/error-exception-handling |
| Optimize Logic Apps rules with control functions | https://learn.microsoft.com/en-us/azure/logic-apps/rules-engine/add-rules-control-functions |
| Optimize Azure Logic Apps Rules Engine execution | https://learn.microsoft.com/en-us/azure/logic-apps/rules-engine/rules-engine-optimization |
| Generate unit tests from Logic Apps Standard workflow definitions | https://learn.microsoft.com/en-us/azure/logic-apps/testing-framework/create-unit-tests-standard-workflow-definitions-visual-studio-code |
| Create unit tests from Logic Apps Standard workflow runs | https://learn.microsoft.com/en-us/azure/logic-apps/testing-framework/create-unit-tests-standard-workflow-runs-visual-studio-code |
| Test Logic Apps workflows using mock outputs and static results | https://learn.microsoft.com/en-us/azure/logic-apps/testing-framework/test-logic-apps-mock-data-static-results |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Choose Azure integration services for enterprise scenarios | https://learn.microsoft.com/en-us/azure/logic-apps/azure-integration-services-choose-capabilities |
| Evaluate migration from BizTalk Server to Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/biztalk-server-migration-overview |
| Understand Logic Apps metering, billing, and pricing models | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-pricing |
| Compare Power Automate flows vs Standard logic apps | https://learn.microsoft.com/en-us/azure/logic-apps/power-automate-migration |
| Choose between Standard and Consumption Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/single-tenant-overview-compare |

### Configuration
| Topic | URL |
|-------|-----|
| Configure Logic Apps to access on-premises data | https://learn.microsoft.com/en-us/azure/logic-apps/connect-on-premises-data-sources |
| Configure app and host settings for Standard Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/edit-app-settings-host-settings |
| Enable enhanced telemetry for Standard Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/enable-enhanced-telemetry-standard-workflows |
| Configure and manage integration accounts for B2B Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/enterprise-integration/create-integration-account |
| Configure and manage integration accounts for B2B Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/enterprise-integration/create-integration-account |
| Use Workflow Definition Language expression functions | https://learn.microsoft.com/en-us/azure/logic-apps/expression-functions-reference |
| Install on-premises data gateway for Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/install-on-premises-data-gateway-workflows |
| Configure B2B agreements between partners in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-enterprise-integration-agreements |
| Handle AS2 MDN acknowledgments in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-enterprise-integration-as2-mdn-acknowledgment |
| Configure AS2 message settings in Logic Apps agreements | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-enterprise-integration-as2-message-settings |
| Configure EDIFACT message settings in Logic Apps agreements | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-enterprise-integration-edifact-message-settings |
| Configure maps for data transforms in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-enterprise-integration-maps |
| Add metadata to B2B artifacts in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-enterprise-integration-metadata |
| Define B2B trading partners in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-enterprise-integration-partners |
| Add and manage schemas for Logic Apps workflows | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-enterprise-integration-schemas |
| Configure X12 message handling in Logic Apps agreements | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-enterprise-integration-x12-message-settings |
| Configure Logic Apps trigger and action schema types | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-workflow-actions-triggers |
| Set up Health Check for Standard Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/monitor-health-standard-workflows |
| Reference monitoring data for Azure Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/monitor-logic-apps-reference |
| Configure B2B message monitoring for Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/monitor-track-b2b-messages-consumption |
| Monitor and track B2B transactions in Standard Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/monitor-track-b2b-transactions-standard |
| Configure Logic Apps diagnostics with Azure Monitor | https://learn.microsoft.com/en-us/azure/logic-apps/monitor-workflows-collect-diagnostic-data |
| Use Parse document and Chunk text actions in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/parse-document-chunk-text |
| Manage Logic Apps with Azure CLI az logic commands | https://learn.microsoft.com/en-us/azure/logic-apps/quickstart-logic-apps-azure-cli |
| Manage Logic Apps workflows using Azure PowerShell | https://learn.microsoft.com/en-us/azure/logic-apps/quickstart-logic-apps-azure-powershell |
| Add arithmetic and logical operators to Logic Apps rules | https://learn.microsoft.com/en-us/azure/logic-apps/rules-engine/add-rules-operators |
| Create and manage vocabularies for Logic Apps rulesets | https://learn.microsoft.com/en-us/azure/logic-apps/rules-engine/create-manage-vocabularies |
| Create business rules with Microsoft Rules Composer | https://learn.microsoft.com/en-us/azure/logic-apps/rules-engine/create-rules |
| Perform advanced operations on Logic Apps rulesets | https://learn.microsoft.com/en-us/azure/logic-apps/rules-engine/perform-advanced-ruleset-tasks |
| Create Logic Apps using Azure CLI script sample | https://learn.microsoft.com/en-us/azure/logic-apps/sample-logic-apps-cli-script |
| Configure Standard Logic Apps as remote MCP servers | https://learn.microsoft.com/en-us/azure/logic-apps/set-up-model-context-protocol-server-standard |
| Configure SQL database storage for Standard Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/set-up-sql-database-storage-standard |
| Use tracking schemas for B2B Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/tracking-schemas-consumption |
| Understand B2B tracking schemas for Standard Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/tracking-schemas-standard |
| Author Logic Apps workflow JSON using WDL schema | https://learn.microsoft.com/en-us/azure/logic-apps/workflow-definition-language-schema |

### Deployment
| Topic | URL |
|-------|-----|
| Automate build and release for Standard logic apps | https://learn.microsoft.com/en-us/azure/logic-apps/automate-build-deployment-standard |
| Clone Consumption workflows to Standard logic apps | https://learn.microsoft.com/en-us/azure/logic-apps/clone-consumption-logic-app-to-standard-workflow |
| Create Standard logic apps for hybrid deployment | https://learn.microsoft.com/en-us/azure/logic-apps/create-standard-workflows-hybrid-deployment |
| Develop and deploy Standard Logic Apps with VS Code | https://learn.microsoft.com/en-us/azure/logic-apps/create-standard-workflows-visual-studio-code |
| Develop and deploy Standard Logic Apps with VS Code | https://learn.microsoft.com/en-us/azure/logic-apps/create-standard-workflows-visual-studio-code |
| Plan DevOps CI/CD for Standard logic apps | https://learn.microsoft.com/en-us/azure/logic-apps/devops-deployment-single-tenant-azure-logic-apps |
| Export Consumption workflows to Standard logic apps | https://learn.microsoft.com/en-us/azure/logic-apps/export-from-consumption-to-standard-logic-app |
| Use ARM templates to deploy Logic Apps Consumption workflows | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-azure-resource-manager-templates-overview |
| Create ARM templates for deploying Logic Apps Consumption | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-create-azure-resource-manager-templates |
| Deploy Logic Apps ARM templates across environments | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-deploy-azure-resource-manager-templates |
| Move Logic Apps and integration accounts across Azure scopes | https://learn.microsoft.com/en-us/azure/logic-apps/move-logic-app-resources |
| Deploy Consumption Logic Apps with ARM templates | https://learn.microsoft.com/en-us/azure/logic-apps/quickstart-create-deploy-azure-resource-manager-template |
| Deploy Consumption Logic Apps with Bicep templates | https://learn.microsoft.com/en-us/azure/logic-apps/quickstart-create-deploy-bicep |
| Configure Deployment Center CD for Standard logic apps | https://learn.microsoft.com/en-us/azure/logic-apps/set-up-cd-deployment-center-standard |
| Configure deployment slots for Standard logic apps | https://learn.microsoft.com/en-us/azure/logic-apps/set-up-deployment-slots |
| Set up DevOps deployment for Standard logic apps | https://learn.microsoft.com/en-us/azure/logic-apps/set-up-devops-deployment-single-tenant-azure-logic-apps |
| Prepare infrastructure for hybrid Standard logic apps | https://learn.microsoft.com/en-us/azure/logic-apps/set-up-standard-workflows-hybrid-deployment-requirements |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Run Logic Apps workflows as Azure AI agent actions | https://learn.microsoft.com/en-us/azure/logic-apps/add-agent-action-create-run-workflow |
| Add Logic Apps connector tools to AI agents | https://learn.microsoft.com/en-us/azure/logic-apps/add-agent-tools-connector-actions |
| Execute C# scripts inline in Standard Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/add-run-csharp-scripts |
| Execute PowerShell scripts inline in Standard Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/add-run-powershell-scripts |
| Reference for Logic Apps Standard built-in connectors | https://learn.microsoft.com/en-us/azure/logic-apps/connectors/built-in/reference/ |
| Run Python code with Code Interpreter in agent workflows | https://learn.microsoft.com/en-us/azure/logic-apps/connectors/code-interpreter-python-container-apps-session |
| Create chat completions with Azure OpenAI prompt templates | https://learn.microsoft.com/en-us/azure/logic-apps/connectors/create-chat-completions-prompt-template |
| Use Microsoft Dataverse connector operations in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/connectors/dataverse |
| Configure IBM Informix connector settings for Logic Apps workflows | https://learn.microsoft.com/en-us/azure/logic-apps/connectors/informix |
| Set up SAP connector access and limitations in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/connectors/sap |
| Generate SAP IDoc and BAPI schemas via Logic Apps workflows | https://learn.microsoft.com/en-us/azure/logic-apps/connectors/sap-generate-schemas-for-artifacts |
| Build custom built-in connectors for Standard Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/create-custom-built-in-connector-standard |
| Create Logic Apps–driven MCP servers via API Center | https://learn.microsoft.com/en-us/azure/logic-apps/create-mcp-server-api-center |
| Create Azure Monitor log queries for Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/create-monitoring-tracking-queries |
| Host and Call Web APIs from Logic Apps via App Service | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-custom-api-host-deploy-call |
| Use Logic Apps data operations with code samples | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-data-operations-code-samples |
| Send and receive AS2 messages in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-enterprise-integration-as2 |
| Automate B2B messaging with Logic Apps protocols | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-enterprise-integration-b2b |
| Exchange EDIFACT messages in Logic Apps workflows | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-enterprise-integration-edifact |
| Send and receive RosettaNet messages in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-enterprise-integration-rosettanet |
| Exchange X12 messages in Azure Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-enterprise-integration-x12 |
| Build fact creators and retrievers for Logic Apps rules | https://learn.microsoft.com/en-us/azure/logic-apps/rules-engine/build-fact-creators-retrievers |
| Handle non-Unicode encodings in Azure Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/support-non-unicode-character-encoding |
| Mock Logic Apps actions with ActionMock class | https://learn.microsoft.com/en-us/azure/logic-apps/testing-framework/action-mock-class-definition |
| Use Azure Logic Apps Automated Test SDK | https://learn.microsoft.com/en-us/azure/logic-apps/testing-framework/automated-test-sdk |
| Run Logic Apps data map tests with DataMapTestExecutor | https://learn.microsoft.com/en-us/azure/logic-apps/testing-framework/data-map-test-executor-class-definition |
| Access unit test action context in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/testing-framework/test-action-execution-context-class-definition |
| Manage Logic Apps unit test execution context | https://learn.microsoft.com/en-us/azure/logic-apps/testing-framework/test-execution-context-class-definition |
| Work with loop iteration items in Logic Apps tests | https://learn.microsoft.com/en-us/azure/logic-apps/testing-framework/test-iteration-item-class-definition |
| Inspect workflow output parameters in Logic Apps tests | https://learn.microsoft.com/en-us/azure/logic-apps/testing-framework/test-workflow-output-parameter-class-definition |
| Handle loop action repetition results in Logic Apps tests | https://learn.microsoft.com/en-us/azure/logic-apps/testing-framework/test-workflow-run-action-repetition-result-class-definition |
| Analyze action results in Logic Apps workflow tests | https://learn.microsoft.com/en-us/azure/logic-apps/testing-framework/test-workflow-run-action-result-class-definition |
| Inspect Logic Apps workflow run data in tests | https://learn.microsoft.com/en-us/azure/logic-apps/testing-framework/test-workflow-run-class-definition |
| Review trigger execution results in Logic Apps tests | https://learn.microsoft.com/en-us/azure/logic-apps/testing-framework/test-workflow-run-trigger-result-class-definition |
| Use TestWorkflowStatus enum for Logic Apps tests | https://learn.microsoft.com/en-us/azure/logic-apps/testing-framework/test-workflow-status-enum-definition |
| Mock Logic Apps triggers with TriggerMock class | https://learn.microsoft.com/en-us/azure/logic-apps/testing-framework/trigger-mock-class-definition |
| Execute Logic Apps unit tests with UnitTestExecutor | https://learn.microsoft.com/en-us/azure/logic-apps/testing-framework/unit-test-executor-class-definition |
| Integrate Logic Apps with Functions and Storage | https://learn.microsoft.com/en-us/azure/logic-apps/tutorial-process-email-attachments-workflow |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Use Inline JavaScript with Logic Apps Limits | https://learn.microsoft.com/en-us/azure/logic-apps/add-run-javascript |
| Estimate Azure Storage costs for Standard Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/estimate-storage-costs |
| Control SQL Result Size and Timeouts in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/handle-long-running-stored-procedures-sql-connector |
| Configure loop behavior and limits in Logic Apps workflows | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-control-flow-loops |
| Configure Pagination to Exceed Connector Page Limits | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-exceed-default-page-size-with-pagination |
| Handle Large Messages and Chunking Limits in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-handle-large-messages |
| Logic Apps limits and configuration reference | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-limits-and-config |

### Security
| Topic | URL |
|-------|-----|
| Use managed identities to authenticate Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/authenticate-with-managed-identity |
| Block cross-tenant Logic Apps connections with Entra | https://learn.microsoft.com/en-us/azure/logic-apps/block-connections-across-tenants |
| Block specific connector usage in Logic Apps with policy | https://learn.microsoft.com/en-us/azure/logic-apps/block-connections-connectors |
| Deploy Standard logic apps with private storage accounts | https://learn.microsoft.com/en-us/azure/logic-apps/deploy-single-tenant-logic-apps-private-storage-account |
| Configure Security Center logging for Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/healthy-unhealthy-resource |
| Configure Microsoft Entra Auth for Custom APIs | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-custom-api-authentication |
| Use certificates to secure Logic Apps B2B messages | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-enterprise-integration-certificates |
| Configure secure access and data protection in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-securing-a-logic-app |
| Apply Azure Policy built-ins to Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/policy-reference |
| Secure Standard Logic Apps with private endpoints and VNets | https://learn.microsoft.com/en-us/azure/logic-apps/secure-single-tenant-workflow-virtual-network-private-endpoint |
| Apply Azure Policy compliance controls to Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/security-controls-policy |
| Protect Logic Apps agent workflows with Easy Auth | https://learn.microsoft.com/en-us/azure/logic-apps/set-up-authentication-agent-workflows |
| Configure OAuth OBO delegated access for Logic Apps agents | https://learn.microsoft.com/en-us/azure/logic-apps/set-up-on-behalf-of-user-flow |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Troubleshoot Throttling and HTTP 429 in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/handle-throttling-problems-429-errors |
| Diagnose and troubleshoot Azure Logic Apps workflow failures | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-diagnosing-failures |
| Troubleshoot common B2B Logic Apps errors and resolutions | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-enterprise-integration-b2b-list-errors-solutions |
| Use EDIFACT CONTRL acknowledgments and error codes in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-enterprise-integration-edifact-contrl-acknowledgment |
| Handle X12 997 acknowledgments and error codes in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-enterprise-integration-x12-997-acknowledgment |
| Interpret X12 TA1 acknowledgments and error codes in Logic Apps | https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-enterprise-integration-x12-ta1-acknowledgment |
| Test and validate Logic Apps rulesets with Rules Composer | https://learn.microsoft.com/en-us/azure/logic-apps/rules-engine/test-rulesets |
| Interpret extended error info in Logic Apps tests | https://learn.microsoft.com/en-us/azure/logic-apps/testing-framework/test-error-info-class-definition |
| Use additional error response info in Logic Apps tests | https://learn.microsoft.com/en-us/azure/logic-apps/testing-framework/test-error-response-additional-info-class-definition |
| Inspect Logic Apps run history and alerts | https://learn.microsoft.com/en-us/azure/logic-apps/view-workflow-status-run-history |

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
