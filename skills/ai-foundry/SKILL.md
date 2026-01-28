---
name: ai-foundry
description: Expert knowledge for Ai Foundry development including configuration, architecture & design patterns, integrations & coding patterns, security, limits & quotas, deployment, troubleshooting, comparing x vs. y, and best practices. Use when building, debugging, or optimizing Ai Foundry applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Ai Foundry Skill

This skill provides expert guidance for Ai Foundry development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Design multi-agent systems using connected agents in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/connected-agents?view=foundry-classic |
| Understand Microsoft Foundry resource and infrastructure architecture | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/architecture?view=foundry-classic |
| Plan disaster recovery strategy for Foundry Agent Service | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/agent-service-disaster-recovery?view=foundry-classic |
| Recover Foundry Agent Service from resource and data loss | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/agent-service-operator-disaster-recovery?view=foundry-classic |
| Recover Foundry Agent Service from Azure platform outages | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/agent-service-platform-disaster-recovery?view=foundry-classic |
| Design high availability and resiliency for Foundry projects and Agent Service | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/high-availability-resiliency?view=foundry-classic |
| Design BCDR architecture for Azure OpenAI deployments | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/business-continuity-disaster-recovery?view=foundry-classic |

### Best Practices
| Topic | URL |
|-------|-----|
| Deploy and use DeepSeek-R1 reasoning model in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/tutorials/get-started-deepseek-r1?view=foundry-classic |
| Securely configure Foundry playground chat on your data | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/secure-data-playground?view=foundry-classic |
| Design system messages for safe, consistent Azure OpenAI chats | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/advanced-prompt-engineering?view=foundry-classic |
| Format prompts with document embeddings for Azure guardrails | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/content-filter-document-embedding?view=foundry-classic |
| Apply fine-tuning considerations for Microsoft Foundry models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/fine-tuning-considerations?view=foundry-classic |
| Engineer effective image prompts for vision chat models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/gpt-4-v-prompt-engineering?view=foundry-classic |
| Use vision-enabled chat models with Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/gpt-with-vision?view=foundry-classic |
| Apply prompt engineering techniques for Azure OpenAI chat | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/prompt-engineering?view=foundry-classic |
| Adopt updated Azure OpenAI provisioned throughput model | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/provisioned-migration?view=foundry-classic |
| Plan red teaming and adversarial testing for LLM solutions | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/red-teaming?view=foundry-classic |
| Apply Azure OpenAI safety system message templates | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/safety-system-message-templates?view=foundry-classic |
| Manage Azure OpenAI fine-tuning training and hosting costs | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/fine-tuning-cost-management?view=foundry-classic |
| Optimize Azure OpenAI performance and latency | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/latency?view=foundry-classic |
| Apply best practices for Azure OpenAI On Your Data | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/on-your-data-best-practices?view=foundry-classic |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Choose between GPT-5 and GPT-4.1 in Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/model-choice-guide?view=foundry-classic |
| Calculate and compare costs for provisioned throughput units in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/provisioned-throughput-onboarding?view=foundry-classic |

### Configuration
| Topic | URL |
|-------|-----|
| Configure capability hosts for Foundry Agent Service | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/concepts/capability-hosts?view=foundry-classic |
| Configure Azure Monitor metrics for Foundry Agent Service | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/metrics?view=foundry-classic |
| Configure Foundry Agent Service to use existing Azure resources | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/use-your-own-resources?view=foundry-classic |
| Use Azure Monitor data for Foundry Agent Service | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/reference/monitor-service?view=foundry-classic |
| Configure content filtering for Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/concepts/content-filter?view=foundry-classic |
| Set up and tune Foundry content filters | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/configure-content-filters?view=foundry-classic |
| Configure project connections to Microsoft Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/configure-project-connection?view=foundry-classic |
| Configure Foundry model deployments with CLI and Bicep | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/create-model-deployments?view=foundry-classic |
| Configure AI projects to use Microsoft Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/quickstart-ai-project?view=foundry-classic |
| Create and manage custom blocklists in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/use-blocklists?view=foundry-classic |
| Select SDKs and languages for Foundry model usage | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/supported-languages?view=foundry-classic |
| Configure Foundry managed network to access on-premises resources | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/access-on-premises-resources?view=foundry-classic |
| Configure customer-managed Azure Storage for Microsoft Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/bring-your-own-azure-storage-foundry?view=foundry-classic |
| Configure customer-managed storage for Speech and Language in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/bring-your-own-azure-storage-speech-language-services?view=foundry-classic |
| Configure managed network isolation for Foundry hubs | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/configure-managed-network?view=foundry-classic |
| Configure Private Link endpoints for Microsoft Foundry projects | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/configure-private-link?view=foundry-classic |
| Configure and manage compute instances in Microsoft Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/create-manage-compute?view=foundry-classic |
| Configure cross-project access to serverless APIs | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/deploy-models-serverless-connect?view=foundry-classic |
| Enable OpenTelemetry tracing for Foundry AI agents | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/trace-agents-sdk?view=foundry-classic |
| Enable tracing and feedback collection for prompt flow deployments | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/trace-production-sdk?view=foundry-classic |
| Configure Azure Storage accounts for Foundry evaluations | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/evaluations-storage-account?view=foundry-classic |
| Create and use vector indexes in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/index-add?view=foundry-classic |
| Enable managed virtual network for Microsoft Foundry projects | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/managed-virtual-network?view=foundry-classic |
| Configure monitoring of quality and token usage for deployed prompt flows | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/monitor-quality-safety?view=foundry-classic |
| Configure Azure OpenAI GPT-4 Turbo with Vision tool in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-tools/azure-open-ai-gpt-4v-tool?view=foundry-classic |
| Configure the Content Safety tool in Microsoft Foundry flows | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-tools/content-safety-tool?view=foundry-classic |
| Configure the Embedding tool for vector generation in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-tools/embedding-tool?view=foundry-classic |
| Configure the Index Lookup tool for RAG in Foundry flows | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-tools/index-lookup-tool?view=foundry-classic |
| Configure and use the LLM tool in Microsoft Foundry flows | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-tools/llm-tool?view=foundry-classic |
| Configure and select prompt flow tools in Microsoft Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-tools/prompt-flow-tools-overview?view=foundry-classic |
| Set up and customize the Prompt tool in Foundry flows | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-tools/prompt-tool?view=foundry-classic |
| Configure the Python tool for custom logic in Foundry flows | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-tools/python-tool?view=foundry-classic |
| Configure the Rerank tool to improve RAG search quality | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-tools/rerank-tool?view=foundry-classic |
| Configure the Serp API tool for web search in Foundry flows | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-tools/serp-api-tool?view=foundry-classic |
| Interpret and configure Azure OpenAI guardrail annotations | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/content-filter-annotations?view=foundry-classic |
| Configure Azure OpenAI content filter policies and thresholds | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/content-filter-configurability?view=foundry-classic |
| Enable and configure JSON mode for chat completions | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/json-mode?view=foundry-classic |
| Configure monitoring and logging for Azure OpenAI with Azure Monitor | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/monitor-openai?view=foundry-classic |
| Optimize latency using predicted outputs settings | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/predicted-outputs?view=foundry-classic |
| Configure prompt caching for Azure OpenAI requests | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/prompt-caching?view=foundry-classic |
| Configure and use Azure OpenAI reasoning models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/reasoning?view=foundry-classic |
| Configure reproducible output for Azure OpenAI models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/reproducible-output?view=foundry-classic |
| Use Risks and Safety monitoring for Azure OpenAI filters | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/risks-safety-monitor?view=foundry-classic |
| Configure spillover traffic management for provisioned deployments | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/spillover-traffic-management?view=foundry-classic |
| Reference metrics and logs for monitoring Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/monitor-openai-reference?view=foundry-classic |
| Configure Azure AI Search for Azure OpenAI On Your Data | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/references/azure-search?view=foundry-classic |
| Configure Azure Cosmos DB for Azure OpenAI On Your Data | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/references/cosmos-db?view=foundry-classic |
| Configure Elasticsearch as Azure OpenAI On Your Data source | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/references/elasticsearch?view=foundry-classic |
| Configure MongoDB Atlas for Azure OpenAI On Your Data | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/references/mongo-db?view=foundry-classic |
| Configure Pinecone for Azure OpenAI On Your Data | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/references/pinecone?view=foundry-classic |
| Use Azure OpenAI language SDKs in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/supported-languages?view=foundry-classic |
| Use Azure OpenAI language SDKs in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/supported-languages?view=foundry-classic |

### Deployment
| Topic | URL |
|-------|-----|
| Select deployment options for Microsoft Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/deployments-overview?view=foundry-classic |
| Understand Foundry model deployment types and hosting choices | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/concepts/deployment-types?view=foundry-classic |
| Use partner and community Foundry Models by region | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/concepts/models-from-partners?view=foundry-classic |
| Use Azure-sold Foundry Models by region and deployment type | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/concepts/models-sold-directly-by-azure?view=foundry-classic |
| Use Azure-sold Foundry Models by region and deployment type | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/concepts/models-sold-directly-by-azure?view=foundry-classic |
| Provision Microsoft Foundry hubs using Bicep templates | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/create-azure-ai-hub-template?view=foundry-classic |
| Use Terraform to deploy Microsoft Foundry hubs and projects | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/create-hub-terraform?view=foundry-classic |
| Deploy Microsoft Foundry resources using Bicep templates | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/create-resource-template?view=foundry-classic |
| Automate Microsoft Foundry provisioning with Terraform | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/create-resource-terraform?view=foundry-classic |
| Deploy partner models with pay-as-you-go managed compute | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/deploy-models-managed-pay-go?view=foundry-classic |
| Deploy models with managed compute in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/deploy-models-managed?view=foundry-classic |
| Check regional availability for serverless model deployments | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/deploy-models-serverless-availability?view=foundry-classic |
| Deploy models as serverless API endpoints in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/deploy-models-serverless?view=foundry-classic |
| Create Microsoft Foundry hubs via Azure ML SDK and CLI | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/create-hub-project-sdk?view=foundry-classic |
| Integrate Foundry evaluations into Azure DevOps pipelines | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/evaluation-azure-devops?view=foundry-classic |
| Run Foundry evaluations in GitHub Actions pipelines | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/evaluation-github-action?view=foundry-classic |
| Deploy prompt flows as managed online endpoints for real-time inference | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/flow-deploy?view=foundry-classic |
| Deploy and invoke CXRReportGen healthcare AI model | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/healthcare-ai/deploy-cxrreportgen?view=foundry-classic |
| Deploy MedImageInsight for medical image embeddings | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/healthcare-ai/deploy-medimageinsight?view=foundry-classic |
| Use MedImageParse models for medical image segmentation | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/healthcare-ai/deploy-medimageparse?view=foundry-classic |
| Create hub-based projects in Microsoft Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/hub-create-projects?view=foundry-classic |
| Upgrade Azure OpenAI resources to Microsoft Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/upgrade-azure-openai?view=foundry-classic |
| Follow Azure OpenAI API version lifecycle in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/api-version-lifecycle?view=foundry-classic |
| Understand Azure OpenAI model deprecations and retirements | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/model-retirements?view=foundry-classic |
| Deploy Azure OpenAI On Your Data resources with azd | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/azure-developer-cli?view=foundry-classic |
| Deploy Azure OpenAI provisioned deployments in Microsoft Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/provisioned-get-started?view=foundry-classic |
| Check Microsoft Foundry feature availability by Azure region | https://learn.microsoft.com/en-us/azure/ai-foundry/reference/region-support?view=foundry-classic |
| Deploy an enterprise chat web app in Foundry playground | https://learn.microsoft.com/en-us/azure/ai-foundry/tutorials/deploy-chat-web-app?view=foundry-classic |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Use Azure AI Search to ground Foundry agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/azure-ai-search-samples?view=foundry-classic |
| Configure Azure AI Search tool for Foundry agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/azure-ai-search?view=foundry-classic |
| Connect Foundry agents to Azure Functions via queues | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/azure-functions-samples?view=foundry-classic |
| Integrate Azure Functions as custom tools for agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/azure-functions?view=foundry-classic |
| Bing Search grounding code samples for Agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/bing-code-samples?view=foundry-classic |
| Custom Bing Search grounding code samples | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/bing-custom-search-samples?view=foundry-classic |
| Configure Custom Bing Search grounding for Agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/bing-custom-search?view=foundry-classic |
| Use Bing Search grounding with Azure AI Agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/bing-grounding?view=foundry-classic |
| Run Browser Automation tool samples with Foundry agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/browser-automation-samples?view=foundry-classic |
| Enable and use Code Interpreter in Foundry agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/code-interpreter?view=foundry-classic |
| Use Computer Use tool with Azure AI Projects SDK | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/computer-use-samples?view=foundry-classic |
| Implement deep research tool with Azure AI Agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/deep-research-samples?view=foundry-classic |
| Integrate deep research web tool into Foundry agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/deep-research?view=foundry-classic |
| Use Microsoft Fabric data agents with Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/fabric?view=foundry-classic |
| Upload files using Azure Agents file search | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/file-search-upload-files?view=foundry-classic |
| Integrate Azure AI Agents with file search | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/file-search?view=foundry-classic |
| Implement function calling in Foundry Agent Service | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/function-calling?view=foundry-classic |
| Integrate Logic Apps with Foundry Agent Service | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/logic-apps?view=foundry-classic |
| Model Context Protocol tool code samples for Agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/model-context-protocol-samples?view=foundry-classic |
| Connect Model Context Protocol servers to Foundry Agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/model-context-protocol?view=foundry-classic |
| OpenAPI tool configuration and code samples for Agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/openapi-spec-samples?view=foundry-classic |
| Configure OpenAPI tools with Azure AI Agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/openapi-spec?view=foundry-classic |
| SharePoint grounding tool code samples for Agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/sharepoint-samples?view=foundry-classic |
| Ground Azure AI Agents with SharePoint content | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/sharepoint?view=foundry-classic |
| Trigger Foundry agents from Logic Apps events | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/triggers?view=foundry-classic |
| Use serverless API inference examples for Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/models-inference-examples?view=foundry-classic |
| Call Foundry Responses API for text generation | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/generate-responses?view=foundry-classic |
| Process images and audio with Foundry chat completions | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/use-chat-multi-modal?view=foundry-classic |
| Use reasoning models via Foundry chat APIs | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/use-chat-reasoning?view=foundry-classic |
| Generate text embeddings with Foundry Models APIs | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/use-embeddings?view=foundry-classic |
| Deploy and call Anthropic Claude models in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/use-foundry-models-claude?view=foundry-classic |
| Generate image embeddings using Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/use-image-embeddings?view=foundry-classic |
| Implement structured outputs with Foundry chat models | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/use-structured-outputs?view=foundry-classic |
| Configure and manage Microsoft Foundry project connections | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/connections-add?view=foundry-classic |
| Evaluate AI agents using the Microsoft Foundry SDK | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/agent-evaluate-sdk?view=foundry-classic |
| Configure cloud evaluations with Microsoft Foundry SDK | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/cloud-evaluation?view=foundry-classic |
| Run local evaluations with Azure AI Evaluation SDK | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/evaluate-sdk?view=foundry-classic |
| Integrate LangChain with Microsoft Foundry deployments | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/langchain?view=foundry-classic |
| Integrate LlamaIndex with Microsoft Foundry models | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/llama-index?view=foundry-classic |
| Run AI Red Teaming Agent scans in the cloud | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/run-ai-red-teaming-cloud?view=foundry-classic |
| Run AI Red Teaming Agent locally with Evaluation SDK | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/run-scans-ai-red-teaming-agent?view=foundry-classic |
| Build Semantic Kernel apps with Foundry models | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/semantic-kernel?view=foundry-classic |
| Add MCP server tools to Foundry agents in VS Code | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/vs-code-agents-mcp?view=foundry-classic |
| Create and manage hub-scoped connections in Microsoft Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/hub-connections-add?view=foundry-classic |
| Integrate Microsoft Foundry endpoints with external applications | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/integrate-with-other-apps?view=foundry-classic |
| Migrate from Azure AI Inference SDK to OpenAI SDK | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/model-inference-to-openai-migration?view=foundry-classic |
| Use image-to-text models from the Foundry catalog | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/use-image-models?view=foundry-classic |
| Generate audio with Azure OpenAI audio models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/audio-completions-quickstart?view=foundry-classic |
| Authoring preview REST API for Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/authoring-reference-preview?view=foundry-classic |
| Use Azure OpenAI audio models via APIs | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/audio?view=foundry-classic |
| Generate images with Azure OpenAI DALL·E models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/dall-e-quickstart?view=foundry-classic |
| Use GPT-4 Turbo with Vision in Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/gpt-v-quickstart?view=foundry-classic |
| Implement function calling with Azure OpenAI Assistants | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/assistant-functions?view=foundry-classic |
| Integrate Azure OpenAI Assistants with Logic Apps | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/assistants-logic-apps?view=foundry-classic |
| Configure Azure Blob Storage with Azure OpenAI Batch | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/batch-blob-storage?view=foundry-classic |
| Work with Azure OpenAI chat completion models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/chatgpt?view=foundry-classic |
| Use Azure OpenAI Assistants Code Interpreter | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/code-interpreter?view=foundry-classic |
| Use Codex CLI and VS Code with Azure OpenAI gpt-5-codex | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/codex?view=foundry-classic |
| Implement Computer Use agents with Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/computer-use?view=foundry-classic |
| Call Azure OpenAI image generation models with options | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/dall-e?view=foundry-classic |
| Use o3-deep-research via Responses API with tools | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/deep-research?view=foundry-classic |
| Migrate from Azure.AI.OpenAI .NET 1.0 beta to 2.0 | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/dotnet-migration?view=foundry-classic |
| Generate and use embeddings with Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/embeddings?view=foundry-classic |
| Configure Azure OpenAI Assistants file search | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/file-search?view=foundry-classic |
| Implement function calling with Azure OpenAI models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/function-calling?view=foundry-classic |
| Call vision-enabled chat models with images | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/gpt-with-vision?view=foundry-classic |
| Migrate Azure OpenAI apps to OpenAI JavaScript v4.x | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/migration-javascript?view=foundry-classic |
| Migrate Azure OpenAI apps to OpenAI Python v1.x | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/migration?view=foundry-classic |
| Integrate and configure model router in Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/model-router?view=foundry-classic |
| Use GPT Realtime API via SIP in Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/realtime-audio-sip?view=foundry-classic |
| Use GPT Realtime API via WebRTC in Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/realtime-audio-webrtc?view=foundry-classic |
| Use GPT Realtime API via WebSockets in Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/realtime-audio-websockets?view=foundry-classic |
| Implement GPT Realtime API for speech and audio in Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/realtime-audio?view=foundry-classic |
| Use Azure OpenAI Responses API and computer-use model | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/responses?view=foundry-classic |
| Use stored completions and distillation in Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/stored-completions?view=foundry-classic |
| Use structured outputs with JSON Schema in Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/structured-outputs?view=foundry-classic |
| Switch Python code between OpenAI and Azure OpenAI endpoints | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/switching-endpoints?view=foundry-classic |
| Use the Azure OpenAI standalone web chat app | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/use-web-app?view=foundry-classic |
| Configure web_search_preview tool in Responses API | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/web-search?view=foundry-classic |
| Configure and secure Azure OpenAI webhooks | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/webhooks?view=foundry-classic |
| Integrate Azure OpenAI fine-tuning with Weights & Biases | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/weights-and-biases-integration?view=foundry-classic |
| Call Azure OpenAI v1 REST API in Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/latest?view=foundry-classic |
| Call Azure OpenAI v1 REST API in Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/latest?view=foundry-classic |
| Call Azure OpenAI v1 REST API in Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/latest?view=foundry-classic |
| Call Azure OpenAI v1 REST API in Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/latest?view=foundry-classic |
| Call Azure OpenAI v1 REST API in Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/latest?view=foundry-classic |
| Call Azure OpenAI v1 REST API in Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/latest?view=foundry-classic |
| Call Azure OpenAI v1 REST API in Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/latest?view=foundry-classic |
| Call Azure OpenAI v1 REST API in Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/latest?view=foundry-classic |
| Call Azure OpenAI v1 REST API in Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/latest?view=foundry-classic |
| Use GPT Realtime API for low-latency speech in Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/realtime-audio-quickstart?view=foundry-classic |
| Use Realtime and Voice Live audio events with Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/realtime-audio-reference?view=foundry-classic |
| Use Azure OpenAI Foundry v1 preview REST API | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/reference-preview-latest?view=foundry-classic |
| Preview REST inference API for Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/reference-preview?view=foundry-classic |
| Preview REST inference API for Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/reference-preview?view=foundry-classic |
| Preview REST inference API for Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/reference-preview?view=foundry-classic |
| Preview REST inference API for Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/reference-preview?view=foundry-classic |
| Preview REST inference API for Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/reference-preview?view=foundry-classic |
| Call Azure OpenAI Foundry REST inference APIs | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/reference?view=foundry-classic |
| Integrate Azure OpenAI On Your Data via REST and Python | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/references/on-your-data?view=foundry-classic |
| Use Azure OpenAI text-to-speech with OpenAI voices | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/text-to-speech-quickstart?view=foundry-classic |
| Use your own data with Azure OpenAI in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/use-your-data-quickstart?view=foundry-classic |
| Generate video clips with Sora in Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/video-generation-quickstart?view=foundry-classic |
| Convert speech to text with Azure OpenAI Whisper | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/whisper-quickstart?view=foundry-classic |
| Build a traced chat app with Microsoft Foundry hub projects | https://learn.microsoft.com/en-us/azure/ai-foundry/quickstarts/hub-get-started-code?view=foundry-classic |
| Build a RAG chat app with Microsoft Foundry SDK | https://learn.microsoft.com/en-us/azure/ai-foundry/tutorials/copilot-sdk-build-rag?view=foundry-classic |
| Evaluate and deploy a chat app with Foundry SDK | https://learn.microsoft.com/en-us/azure/ai-foundry/tutorials/copilot-sdk-evaluate?view=foundry-classic |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Review quotas and limits for Foundry Agent Service | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/quotas-limits?view=foundry-classic |
| Reference quotas and limits for Microsoft Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/quotas-limits?view=foundry-classic |
| Manage and request quota increases for Microsoft Foundry hubs | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/hub-quota?view=foundry-classic |
| Manage and request quota increases for Microsoft Foundry resources | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/quota?view=foundry-classic |
| Use Azure OpenAI content streaming modes and constraints | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/content-streaming?view=foundry-classic |
| Review retired Azure OpenAI model availability | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/legacy-models?view=foundry-classic |
| Configure priority processing for Microsoft Foundry model deployments | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/priority-processing?view=foundry-classic |
| Understand provisioned throughput limits for Microsoft Foundry models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/provisioned-throughput?view=foundry-classic |
| Use Azure OpenAI global batch processing quotas and costs | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/batch?view=foundry-classic |
| Use Azure OpenAI dynamic quota for extra capacity | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/dynamic-quota?view=foundry-classic |
| Manage Azure OpenAI quota and rate limits | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/quota?view=foundry-classic |
| Apply reinforcement fine-tuning cost safeguards | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/reinforcement-fine-tuning?view=foundry-classic |
| Azure OpenAI quotas and limits in Microsoft Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/quotas-limits?view=foundry-classic |

### Security
| Topic | URL |
|-------|-----|
| Securely configure Browser Automation in Foundry agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/browser-automation?view=foundry-classic |
| Configure and govern the Computer Use tool for agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/computer-use?view=foundry-classic |
| Use private virtual networks with Foundry Agent Service | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/virtual-networks?view=foundry-classic |
| Configure authentication, authorization, and RBAC in Microsoft Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/authentication-authorization-foundry?view=foundry-classic |
| Block Foundry preview features using custom RBAC roles | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/disable-preview-features-with-rbac?view=foundry-classic |
| Configure customer-managed keys for Microsoft Foundry encryption | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/encryption-keys-portal?view=foundry-classic |
| Use customer-managed keys for Microsoft Foundry hub encryption | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/hub-encryption-keys-portal?view=foundry-classic |
| Configure RBAC for Microsoft Foundry hubs and projects | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/hub-rbac-foundry?view=foundry-classic |
| Configure guardrails and content safety for Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/model-catalog-content-safety?view=foundry-classic |
| Configure RBAC roles and permissions in Microsoft Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/rbac-foundry?view=foundry-classic |
| Understand vulnerability management for Microsoft Foundry hubs | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/vulnerability-management?view=foundry-classic |
| Apply default safety and guardrail policies in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/concepts/default-safety-policies?view=foundry-classic |
| Create custom deployment policies for Foundry and Azure OpenAI models | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/configure-deployment-policies?view=foundry-classic |
| Set up keyless Entra ID authentication for Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/configure-entra-id?view=foundry-classic |
| Associate Microsoft Foundry with a network security perimeter | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/add-foundry-to-network-security-perimeter?view=foundry-classic |
| Apply Azure Policy to secure Foundry hubs and projects | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/azure-policy?view=foundry-classic |
| Control AI model deployment in Foundry with built-in policies | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/built-in-policy-model-deployment?view=foundry-classic |
| Understand data handling and privacy for Foundry model catalog | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/concept-data-privacy?view=foundry-classic |
| Create and secure Microsoft Foundry hubs in Azure | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/create-azure-ai-resource?view=foundry-classic |
| Secure Microsoft Foundry hubs with managed virtual networks | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/create-secure-ai-hub?view=foundry-classic |
| Create custom Azure Policies to control Foundry resources | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/custom-policy-definition?view=foundry-classic |
| Disable shared key access for Foundry hub storage accounts | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/disable-local-auth?view=foundry-classic |
| Configure private link networking for Microsoft Foundry hubs | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/hub-configure-private-link?view=foundry-classic |
| Use built-in Azure Policies to govern Foundry model deployment | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/model-deployment-policy?view=foundry-classic |
| Securely connect Azure Key Vault to Microsoft Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/set-up-key-vault-connection?view=foundry-classic |
| Use Azure OpenAI in Azure Government cloud | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/azure-government?view=foundry-classic |
| Understand Azure Direct Models abuse monitoring behavior | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/abuse-monitoring?view=foundry-classic |
| Use Azure OpenAI content credentials for image provenance | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/content-credentials?view=foundry-classic |
| Apply Azure OpenAI content filtering to prompts and outputs | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/content-filter?view=foundry-classic |
| Apply Azure OpenAI default safety and control policies | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/default-safety-policies?view=foundry-classic |
| Understand DALL-E 3 prompt transformation safety behavior | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/prompt-transformation?view=foundry-classic |
| Configure Microsoft Foundry content filters and approvals | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/content-filters?view=foundry-classic |
| Configure Entra ID and managed identity for Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/managed-identity?view=foundry-classic |
| Add Azure OpenAI to a network security perimeter | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/network-security-perimeter?view=foundry-classic |
| Secure Azure OpenAI with VNets and private endpoints | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/network?view=foundry-classic |
| Configure network and access for Azure OpenAI On Your Data | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/on-your-data-configuration?view=foundry-classic |
| Apply Azure RBAC roles to Azure OpenAI resources | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/role-based-access-control?view=foundry-classic |
| Configure custom block lists in Microsoft Foundry models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/use-blocklists?view=foundry-classic |
| Configure data privacy and security for Azure AI Agent Service | https://learn.microsoft.com/en-us/azure/ai-foundry/responsible-ai/agents/data-privacy-security?view=foundry-classic |
| Understand data handling and privacy for Claude in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/responsible-ai/claude-models/data-privacy?view=foundry-classic |
| Implement copyright mitigations for Azure OpenAI safety systems | https://learn.microsoft.com/en-us/azure/ai-foundry/responsible-ai/openai/customer-copyright-commitment?view=foundry-classic |
| Understand data privacy and security for Azure Direct Models | https://learn.microsoft.com/en-us/azure/ai-foundry/responsible-ai/openai/data-privacy?view=foundry-classic |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Resolve Azure Marketplace access issues for Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/configure-marketplace?view=foundry-classic |
| Troubleshoot common prompt flow issues and compute session failures | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-troubleshoot?view=foundry-classic |
| Troubleshoot Foundry model deployments and monitors | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/troubleshoot-deploy-and-monitor?view=foundry-classic |
| Diagnose private endpoint connectivity for Foundry projects | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/troubleshoot-secure-connection-project?view=foundry-classic |
| Troubleshoot Azure OpenAI fine-tuning issues in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/fine-tuning-troubleshoot?view=foundry-classic |
| Resolve common Microsoft Foundry issues and workarounds | https://learn.microsoft.com/en-us/azure/ai-foundry/reference/foundry-known-issues?view=foundry-classic |

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
