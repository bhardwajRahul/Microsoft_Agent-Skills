---
name: bot-service
description: Expert knowledge for Bot Service development including configuration, integrations & coding patterns, security, troubleshooting, best practices, limits & quotas, architecture & design patterns, comparing x vs. y, and deployment. Use when building, debugging, or optimizing Bot Service applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Bot Service Skill

This skill provides expert guidance for Bot Service development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Route across multiple LUIS and QnA projects with Orchestrator | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-tutorial-orchestrator?view=azure-bot-service-4.0 |
| Embed Azure bots inside native and mobile apps | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-design-pattern-embed-app?view=azure-bot-service-4.0 |
| Embed Azure bots into websites with web control | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-design-pattern-embed-web-site?view=azure-bot-service-4.0 |
| Design bot-to-human handoff patterns in Azure Bots | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-design-pattern-handoff-human?view=azure-bot-service-4.0 |
| Choose and design Azure Bot knowledge-bot patterns | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-design-pattern-knowledge-base?view=azure-bot-service-4.0 |

### Best Practices
| Topic | URL |
|-------|-----|
| Expire and restart bot conversations safely | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-howto-expire-conversation?view=azure-bot-service-4.0 |
| Handle user interruptions and errors in bots | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-howto-handle-user-interrupt?view=azure-bot-service-4.0 |
| Apply debugging guidelines for Bot Framework bots | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-testing-debugging?view=azure-bot-service-4.0 |
| Unit test Bot Framework SDK bots effectively | https://learn.microsoft.com/en-us/azure/bot-service/unit-test-bots?view=azure-bot-service-4.0 |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Select the right Microsoft chatbot platform | https://learn.microsoft.com/en-us/azure/bot-service/bot-overview?view=azure-bot-service-4.0 |
| Compare Direct Line channel options for bots | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-directline?view=azure-bot-service-4.0 |

### Configuration
| Topic | URL |
|-------|-----|
| Configure prebuilt actions in adaptive dialogs | https://learn.microsoft.com/en-us/azure/bot-service/adaptive-dialog/adaptive-dialog-prebuilt-actions?view=azure-bot-service-4.0 |
| Use prebuilt input dialogs in adaptive dialogs | https://learn.microsoft.com/en-us/azure/bot-service/adaptive-dialog/adaptive-dialog-prebuilt-inputs?view=azure-bot-service-4.0 |
| Manage memory scopes in adaptive dialogs | https://learn.microsoft.com/en-us/azure/bot-service/adaptive-dialog/adaptive-dialog-prebuilt-memory-states?view=azure-bot-service-4.0 |
| Configure prebuilt recognizers for adaptive dialogs | https://learn.microsoft.com/en-us/azure/bot-service/adaptive-dialog/adaptive-dialog-prebuilt-recognizers?view=azure-bot-service-4.0 |
| Use prebuilt triggers in adaptive dialogs | https://learn.microsoft.com/en-us/azure/bot-service/adaptive-dialog/adaptive-dialog-prebuilt-triggers?view=azure-bot-service-4.0 |
| Use prebuilt adaptive expression functions | https://learn.microsoft.com/en-us/azure/bot-service/adaptive-expressions/adaptive-expressions-prebuilt-functions?view=azure-bot-service-4.0 |
| Implement custom bot state storage in SDK v4 | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-custom-storage?view=azure-bot-service-4.0 |
| Configure and use state storage in Bot Framework | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-howto-v4-state?view=azure-bot-service-4.0 |
| Write bot data directly to storage providers | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-howto-v4-storage?view=azure-bot-service-4.0 |
| Customize appearance and behavior of Web Chat control | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-webchat-customization?view=azure-bot-service-4.0 |
| Configure and customize Bot Framework Web Chat component | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-webchat-overview?view=azure-bot-service-4.0 |
| Configure Direct Line App Service extension for bots | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-directline-extension?view=azure-bot-service-4.0 |
| Configure channels for Azure AI Bot Service bots | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-manage-channels?view=azure-bot-service-4.0 |
| Configure Azure Bot resource settings in portal | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-manage-settings?view=azure-bot-service-4.0 |
| Register externally hosted bots with Azure Bot Service | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-quickstart-registration?view=azure-bot-service-4.0 |
| Configure Application Insights keys for Bot Framework telemetry | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-resources-app-insights-keys?view=azure-bot-service-4.0 |
| Use and interpret ID fields in Bot Framework protocol | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-resources-identifiers-guide?view=azure-bot-service-4.0 |
| Author .lg language generation files for Bot Framework | https://learn.microsoft.com/en-us/azure/bot-service/file-format/bot-builder-lg-file-format?view=azure-bot-service-4.0 |
| Define .lu language understanding models for bots | https://learn.microsoft.com/en-us/azure/bot-service/file-format/bot-builder-lu-file-format?view=azure-bot-service-4.0 |
| Author .qna files for Azure QnA Maker bots | https://learn.microsoft.com/en-us/azure/bot-service/file-format/bot-builder-qna-file-format?view=azure-bot-service-4.0 |
| Define structured response templates with LG | https://learn.microsoft.com/en-us/azure/bot-service/language-generation/language-generation-structured-response-template?view=azure-bot-service-4.0 |
| Use Azure Bot Service monitoring data and schema | https://learn.microsoft.com/en-us/azure/bot-service/monitor-bot-service-reference?view=azure-bot-service-4.0 |
| Select correct OAuth and redirect URLs for Bot Service | https://learn.microsoft.com/en-us/azure/bot-service/ref-oauth-redirect-urls?view=azure-bot-service-4.0 |
| Use dialogs to implement multi-action skills | https://learn.microsoft.com/en-us/azure/bot-service/skill-actions-in-dialogs?view=azure-bot-service-4.0 |
| Implement a Bot Framework skill consumer bot | https://learn.microsoft.com/en-us/azure/bot-service/skill-implement-consumer?view=azure-bot-service-4.0 |
| Implement a Bot Framework skill bot | https://learn.microsoft.com/en-us/azure/bot-service/skill-implement-skill?view=azure-bot-service-4.0 |
| Convert Bot Framework skills from multitenant to single-tenant | https://learn.microsoft.com/en-us/azure/bot-service/skill-pva-convert-skill-single-tenant?view=azure-bot-service-4.0 |
| Update skills to support both single-tenant and multitenant agents | https://learn.microsoft.com/en-us/azure/bot-service/skill-pva-update-skill-single-tenant?view=azure-bot-service-4.0 |
| Implement Bot Framework skills for Copilot Studio agents | https://learn.microsoft.com/en-us/azure/bot-service/skill-pva?view=azure-bot-service-4.0 |
| Consume a Bot Framework skill using SkillDialog | https://learn.microsoft.com/en-us/azure/bot-service/skill-use-skilldialog?view=azure-bot-service-4.0 |
| Author and configure Bot Framework skill manifests | https://learn.microsoft.com/en-us/azure/bot-service/skills-write-manifest?view=azure-bot-service-4.0 |
| Use trace activities to debug Bot Framework bots | https://learn.microsoft.com/en-us/azure/bot-service/using-trace-activities?view=azure-bot-service-4.0 |

### Deployment
| Topic | URL |
|-------|-----|
| Configure continuous deployment for Azure Bot Service | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-build-continuous-deployment?view=azure-bot-service-4.0 |
| Deploy Azure bots to 21Vianet-operated Azure China | https://learn.microsoft.com/en-us/azure/bot-service/how-to-deploy-china-cloud?view=azure-bot-service-4.0 |
| Deploy Azure bots to US Government and GCC High | https://learn.microsoft.com/en-us/azure/bot-service/how-to-deploy-gov-cloud-high?view=azure-bot-service-4.0 |
| Provision Azure resources and publish Bot Framework bots | https://learn.microsoft.com/en-us/azure/bot-service/provision-and-publish-a-bot?view=azure-bot-service-4.0 |
| Create App Service for bots using Azure CLI and ARM | https://learn.microsoft.com/en-us/azure/bot-service/provision-app-service?view=azure-bot-service-4.0 |
| Provision Azure Bot resources using Azure CLI | https://learn.microsoft.com/en-us/azure/bot-service/provision-azure-bot?view=azure-bot-service-4.0 |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Adaptive expressions API reference for bots | https://learn.microsoft.com/en-us/azure/bot-service/adaptive-expressions/adaptive-expressions-api-reference?view=azure-bot-service-4.0 |
| Use channelData for channel-specific bot features | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-channeldata?view=azure-bot-service-4.0 |
| Manage complex dialogs with Bot Framework components | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-compositcontrol?view=azure-bot-service-4.0 |
| Create advanced branching and looping dialog flows | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-dialog-manage-complex-conversation-flow?view=azure-bot-service-4.0 |
| Implement sequential dialog flows in Bot Framework | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-dialog-manage-conversation-flow?view=azure-bot-service-4.0 |
| Send media attachments using Bot Framework SDK | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-howto-add-media-attachments?view=azure-bot-service-4.0 |
| Use suggested action buttons in Bot Framework | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-howto-add-suggested-actions?view=azure-bot-service-4.0 |
| Use Azure question answering in Bot Framework bots | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-howto-answer-questions?view=azure-bot-service-4.0 |
| Send proactive notifications with Azure bots | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-howto-proactive-message?view=azure-bot-service-4.0 |
| Integrate QnA Maker with Bot Framework bots | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-howto-qna?view=azure-bot-service-4.0 |
| Send and receive text messages with Bot Framework | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-howto-send-messages?view=azure-bot-service-4.0 |
| Integrate LUIS language understanding with bots | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-howto-v4-luis?view=azure-bot-service-4.0 |
| Create custom prompts for user input in bots | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-primitive-prompts?view=azure-bot-service-4.0 |
| Implement welcome messages for Bot Framework bots | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-send-welcome-message?view=azure-bot-service-4.0 |
| Analyze bot telemetry with Kusto queries | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-telemetry-analytics-queries?view=azure-bot-service-4.0 |
| Add Application Insights telemetry to QnA Maker bots | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-telemetry-qnamaker?view=azure-bot-service-4.0 |
| Configure Application Insights telemetry for bots | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-telemetry?view=azure-bot-service-4.0 |
| Connect Azure bots to channels using Azure CLI | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-azure-cli?view=azure-bot-service-4.0 |
| Connect bots to Outlook Actionable Messages with Adaptive Cards | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-actionable-email?view=azure-bot-service-4.0 |
| Connect bots to client apps via Direct Line | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-directline?view=azure-bot-service-4.0 |
| Integrate Azure bots with Microsoft 365 email | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-email?view=azure-bot-service-4.0 |
| Connect Azure Bot Service to Facebook channels | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-facebook?view=azure-bot-service-4.0 |
| Connect Azure bots to GroupMe channel | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-groupme?view=azure-bot-service-4.0 |
| Integrate Azure bots with LINE messaging | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-line?view=azure-bot-service-4.0 |
| Add Azure bots to Microsoft 365 via M365 Extensions | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-m365?view=azure-bot-service-4.0 |
| Integrate Azure bots as custom Microsoft Search providers | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-search?view=azure-bot-service-4.0 |
| Connect Azure Bot Framework bots to Skype | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-skype?view=azure-bot-service-4.0 |
| Connect Azure Bot Framework bots to Slack | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-slack?view=azure-bot-service-4.0 |
| Connect Azure bots to Telegram messaging | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-telegram?view=azure-bot-service-4.0 |
| Integrate Azure bots with Twilio SMS | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-twilio?view=azure-bot-service-4.0 |
| Connect bots to Web Chat and embed in web pages | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-webchat?view=azure-bot-service-4.0 |
| Connect Azure bots to WeChat via custom adapter | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-wechat?view=azure-bot-service-4.0 |
| Configure .NET bots for Direct Line App Service extension | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-directline-extension-net-bot?view=azure-bot-service-4.0 |
| Create .NET WebSocket clients for Direct Line App Service | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-directline-extension-net-client?view=azure-bot-service-4.0 |
| Configure Node.js bots for Direct Line App Service extension | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-directline-extension-node-bot?view=azure-bot-service-4.0 |
| Use Web Chat with Direct Line App Service extension | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-directline-extension-webchat-client?view=azure-bot-service-4.0 |
| Connect Azure bots to Dynamics 365 Omnichannel | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-omnichannel?view=azure-bot-service-4.0 |
| Connect Azure Bot Framework bots to Microsoft Teams | https://learn.microsoft.com/en-us/azure/bot-service/channel-connect-teams?view=azure-bot-service-4.0 |
| Inject LG functions into bot templates | https://learn.microsoft.com/en-us/azure/bot-service/language-generation/functions-injected-from-language-generation?view=azure-bot-service-4.0 |
| Language Generation library API reference | https://learn.microsoft.com/en-us/azure/bot-service/language-generation/language-generation-api-reference?view=azure-bot-service-4.0 |
| Use input hints to control bot user input | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-connector-add-input-hints?view=azure-bot-service-4.0 |
| Attach media files to Bot Framework messages | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-connector-add-media-attachments?view=azure-bot-service-4.0 |
| Create and use rich card attachments in bots | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-connector-add-rich-cards?view=azure-bot-service-4.0 |
| Add suggested action buttons to bot messages | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-connector-add-suggested-actions?view=azure-bot-service-4.0 |
| Use Bot Framework Connector REST API operations | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-connector-api-reference?view=azure-bot-service-4.0 |
| Send channelData for channel-specific bot features | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-connector-channeldata?view=azure-bot-service-4.0 |
| Format and send Bot Framework message activities | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-connector-create-messages?view=azure-bot-service-4.0 |
| Send and receive activities via Bot Connector | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-connector-send-and-receive-messages?view=azure-bot-service-4.0 |
| Add text-to-speech output to bot messages | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-connector-text-to-speech?view=azure-bot-service-4.0 |
| Direct Line 1.1 REST API reference | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-direct-line-1-1-api-reference?view=azure-bot-service-4.0 |
| Receive messages from bots via Direct Line 1.1 | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-direct-line-1-1-receive-messages?view=azure-bot-service-4.0 |
| Send messages to bots via Direct Line 1.1 | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-direct-line-1-1-send-message?view=azure-bot-service-4.0 |
| Start conversations with Direct Line 1.1 | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-direct-line-1-1-start-conversation?view=azure-bot-service-4.0 |
| Direct Line 3.0 REST API reference | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-direct-line-3-0-api-reference?view=azure-bot-service-4.0 |
| End bot conversations using Direct Line 3.0 | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-direct-line-3-0-end-conversation?view=azure-bot-service-4.0 |
| Receive bot activities via Direct Line 3.0 | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-direct-line-3-0-receive-activities?view=azure-bot-service-4.0 |
| Reconnect Direct Line WebSocket conversations | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-direct-line-3-0-reconnect-to-conversation?view=azure-bot-service-4.0 |
| Send activities to bots via Direct Line 3.0 | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-direct-line-3-0-send-activity?view=azure-bot-service-4.0 |
| Start Direct Line 3.0 conversations with bots | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-direct-line-3-0-start-conversation?view=azure-bot-service-4.0 |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Handle long-running operations and bot timeouts | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-howto-long-operations-guidance?view=azure-bot-service-4.0 |
| Channel capabilities and limits for Azure bots | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channels-reference?view=azure-bot-service-4.0 |

### Security
| Topic | URL |
|-------|-----|
| Implement authentication flows in Bot Framework SDK | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-authentication-basics?view=azure-bot-service-4.0 |
| Use federated identity credentials for bot auth | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-authentication-federated-credential?view=azure-bot-service-4.0 |
| Configure single sign-on between root and skill bots | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-authentication-sso?view=azure-bot-service-4.0 |
| Add Azure-based user authentication to bots | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-authentication?view=azure-bot-service-4.0 |
| Use bot and user authentication types in Bot Service | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-concept-authentication-types?view=azure-bot-service-4.0 |
| Configure user OAuth authentication for Azure bots | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-concept-authentication?view=azure-bot-service-4.0 |
| Create OAuth2 proxy for custom bot identity providers | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-concept-identity-providers-proxy?view=azure-bot-service-4.0 |
| Use identity providers with Bot Framework SDK | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-concept-identity-providers?view=azure-bot-service-4.0 |
| Implement single sign-on for Bot Framework bots | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-concept-sso?view=azure-bot-service-4.0 |
| Secure Direct Line connections with enhanced authentication | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-security-enhanced?view=azure-bot-service-4.0 |
| Apply security guidelines to Bot Framework solutions | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-security-guidelines?view=azure-bot-service-4.0 |
| Implement single sign-on for Web Chat bots with Entra ID | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-webchat-sso?view=azure-bot-service-4.0 |
| Use Direct Line App Service extension inside a VNet | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-channel-directline-extension-vnet?view=azure-bot-service-4.0 |
| Understand compliance certifications for Azure AI Bot Service | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-compliance?view=azure-bot-service-4.0 |
| Understand Azure Bot Service data-at-rest encryption | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-encryption?view=azure-bot-service-4.0 |
| Address security and privacy concerns in Bot Framework | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-resources-faq-security?view=azure-bot-service-4.0 |
| Network isolation options for Azure AI Bot Service | https://learn.microsoft.com/en-us/azure/bot-service/dl-network-isolation-concept?view=azure-bot-service-4.0 |
| Configure network isolation for Azure Bot Service | https://learn.microsoft.com/en-us/azure/bot-service/dl-network-isolation-how-to?view=azure-bot-service-4.0 |
| Configure authentication for Bot Connector and state APIs | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-connector-authentication?view=azure-bot-service-4.0 |
| Authenticate Direct Line 1.1 with secrets and tokens | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-direct-line-1-1-authentication?view=azure-bot-service-4.0 |
| Authenticate Direct Line 3.0 clients with secrets and tokens | https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-direct-line-3-0-authentication?view=azure-bot-service-4.0 |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Debug Bot Framework bots with transcript files | https://learn.microsoft.com/en-us/azure/bot-service/bot-builder-debug-transcript?view=azure-bot-service-4.0 |
| Debug Bot Framework bots with IDE and Emulator | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-debug-bot?view=azure-bot-service-4.0 |
| Debug bot channels using Dev Tunnels | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-debug-channel-devtunnel?view=azure-bot-service-4.0 |
| Test and debug bots using Bot Framework Emulator | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-debug-emulator?view=azure-bot-service-4.0 |
| Debug bots using inspection middleware and Emulator | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-debug-inspection-middleware?view=azure-bot-service-4.0 |
| Handle and stop Bot Framework User-Agent webhook requests | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-resources-user-agent?view=azure-bot-service-4.0 |
| Resolve HTTP 500 errors in Azure AI Bot Service | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-troubleshoot-500-errors?view=azure-bot-service-4.0 |
| Troubleshoot authentication failures in Bot Framework bots | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-troubleshoot-authentication-problems?view=azure-bot-service-4.0 |
| Troubleshoot Azure bot configuration and channel issues | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-troubleshoot-bot-configuration?view=azure-bot-service-4.0 |
| Diagnose common Azure AI Bot Service issues | https://learn.microsoft.com/en-us/azure/bot-service/bot-service-troubleshoot-general-problems?view=azure-bot-service-4.0 |
| Debug Bot Framework skills and consumers with Dev Tunnels | https://learn.microsoft.com/en-us/azure/bot-service/skills-debug-skill-or-consumer?view=azure-bot-service-4.0 |

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
