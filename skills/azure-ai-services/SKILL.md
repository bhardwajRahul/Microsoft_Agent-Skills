---
name: azure-ai-services
description: Expert knowledge for Azure Ai Services development including troubleshooting, best practices, decision making, architecture & design patterns, limits & quotas, security, configuration, integrations & coding patterns, and deployment. Use when building, debugging, or optimizing Azure Ai Services applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
metadata:
  generated_at: "2026-02-24"
  generator: "docs2skills/1.0.0"
---
# Azure Ai Services Skill

This skill provides expert guidance for Azure Ai Services. Covers troubleshooting, best practices, decision making, architecture & design patterns, limits & quotas, security, configuration, integrations & coding patterns, and deployment. It combines local quick-reference content with remote documentation fetching capabilities.

## How to Use This Skill

> **IMPORTANT for Agent**: This file may be large. Use the **Category Index** below to locate relevant sections, then use `read_file` with specific line ranges (e.g., `L136-L144`) to read the sections needed for the user's question

> **IMPORTANT for Agent**: If `metadata.generated_at` is more than 3 months old, suggest the user pull the latest version from the repository. If `mcp_microsoftdocs` tools are not available, suggest the user install it: [Installation Guide](https://github.com/MicrosoftDocs/mcp/blob/main/README.md)

This skill requires **network access**. Use `mcp_microsoftdocs:microsoft_docs_fetch` or `fetch_webpage` if MCP is unavailable to fetch documentation.

## Category Index

| Category | Lines | Description |
|----------|-------|-------------|
| Troubleshooting | L35-L46 | Diagnosing and fixing Foundry issues: deployments, monitors, private endpoints, Marketplace/model access, fine-tuning, webhooks, prompt flow/compute, and classic portal known problems. |
| Best Practices | L47-L63 | Best practices for Azure OpenAI and Foundry: prompt design, safety and shields, embeddings, fine-tuning (incl. vision/tools), reasoning models, latency/throughput, and HA/DR for agents. |
| Decision Making | L64-L93 | Guidance for choosing Foundry/Azure OpenAI models, regions, hubs, deployments, costs, DR/HA, and migration/upgrade paths between OpenAI, GitHub Models, and Foundry. |
| Architecture & Design Patterns | L94-L99 | Architectural guidance for Azure OpenAI: standard multi-environment/isolated setups, resource design, and business continuity/disaster recovery patterns. |
| Limits & Quotas | L100-L117 | Quotas, rate limits, timeouts, and capacity for Foundry and Azure OpenAI: how to check, manage, increase, batch jobs, prompt caching, dynamic TPM, deployments, and cost safeguards. |
| Security | L118-L162 | Securing Foundry and Azure OpenAI: auth/RBAC, networking (VNets, Private Link, perimeters), encryption/CMK, guardrails/safety, policy-based governance, and data privacy/handling. |
| Configuration | L163-L213 | Configuring and monitoring Foundry agents, models, storage, networking, evaluators, content filters, and Azure OpenAI integrations, including logging, tracing, and evaluation workflows. |
| Integrations & Coding Patterns | L214-L317 | Patterns and code to integrate Azure AI/Foundry/OpenAI models and agents with tools, data sources, REST APIs, RAG, embeddings, function calling, realtime audio, and external frameworks. |
| Deployment | L318-L339 | Deploying Foundry hubs, models, and prompt flows using Bicep, Terraform, CLI/SDK, serverless APIs, CI/CD, and managed compute, including regional availability and enterprise app deployment. |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Monitor Foundry Agent Service metrics with Azure Monitor | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/metrics?view=foundry-classic |
| Resolve Azure Marketplace access issues for Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/configure-marketplace?view=foundry-classic |
| Troubleshoot common issues in prompt flow and compute sessions | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-troubleshoot?view=foundry-classic |
| Troubleshoot deployments and monitors in Microsoft Foundry portal | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/troubleshoot-deploy-and-monitor?view=foundry-classic |
| Diagnose private endpoint access issues in Foundry projects | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/troubleshoot-secure-connection-project?view=foundry-classic |
| Troubleshoot Azure OpenAI fine-tuning issues in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/fine-tuning-troubleshoot?view=foundry-classic |
| Configure and troubleshoot Azure OpenAI webhooks | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/webhooks?view=foundry-classic |
| Resolve known issues in Microsoft Foundry classic | https://learn.microsoft.com/en-us/azure/ai-foundry/reference/foundry-known-issues?view=foundry-classic |

### Best Practices
| Topic | URL |
|-------|-----|
| Recover Foundry Agent Service from regional outages | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/agent-service-platform-disaster-recovery?view=foundry-classic |
| Plan high availability for Foundry projects and agents | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/high-availability-resiliency?view=foundry-classic |
| Design effective system messages for Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/advanced-prompt-engineering?view=foundry-classic |
| Format prompts with document embeddings in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/content-filter-document-embedding?view=foundry-classic |
| Configure and interpret Prompt Shields in Microsoft Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/content-filter-prompt-shields?view=foundry-classic |
| Apply prompt engineering patterns for Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/prompt-engineering?view=foundry-classic |
| Apply safety system message templates in Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/safety-system-message-templates?view=foundry-classic |
| Fine-tune Azure OpenAI for reliable tool calls | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/fine-tuning-functions?view=foundry-classic |
| Fine-tune GPT-4 vision models with images | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/fine-tuning-vision?view=foundry-classic |
| Optimize Azure OpenAI latency and throughput | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/latency?view=foundry-classic |
| Implement best practices for Azure OpenAI On Your Data | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/on-your-data-best-practices?view=foundry-classic |
| Optimize latency with predicted outputs in Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/predicted-outputs?view=foundry-classic |
| Apply Azure OpenAI reasoning models for complex tasks | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/reasoning?view=foundry-classic |

### Decision Making
| Topic | URL |
|-------|-----|
| Choose Azure OpenAI models and regions for Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/concepts/model-region-support?view=foundry-classic |
| Understand and decide on Foundry AI hubs | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/ai-resources?view=foundry-classic |
| Decide when and how to fine-tune models in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/fine-tuning-overview?view=foundry-classic |
| Plan and manage Microsoft Foundry cost usage | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/manage-costs?view=foundry-classic |
| Use Foundry model benchmarks and leaderboards for selection | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/model-benchmarks?view=foundry-classic |
| Plan for Foundry model deprecation and migration | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/model-lifecycle-retirement?view=foundry-classic |
| Plan Microsoft Foundry rollout and environments | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/planning?view=foundry-classic |
| Choose Azure resource types for Foundry projects | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/resource-types?view=foundry-classic |
| Choose Microsoft Foundry model deployment types | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/concepts/deployment-types?view=foundry-classic |
| Choose partner and community Foundry Models by capabilities | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/concepts/models-from-partners?view=foundry-classic |
| Select Azure-sold Foundry Models by capabilities and regions | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/concepts/models-sold-directly-by-azure?view=foundry-classic |
| Choose between GPT-5 and GPT-4.1 in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/model-choice-guide?view=foundry-classic |
| Decide when to upgrade from GitHub Models to Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/quickstart-github-models?view=foundry-classic |
| Plan disaster recovery for Foundry Agent Service outages | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/agent-service-disaster-recovery?view=foundry-classic |
| Recover Foundry Agent Service resources and data loss incidents | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/agent-service-operator-disaster-recovery?view=foundry-classic |
| Compare Foundry models using leaderboard and side-by-side views | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/benchmark-model-in-catalog?view=foundry-classic |
| Plan and manage Microsoft Foundry hub costs | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/costs-plan-manage?view=foundry-classic |
| Plan high availability and disaster recovery for Foundry hubs | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/hub-disaster-recovery?view=foundry-classic |
| Migrate hub-based projects to new Foundry projects | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/migrate-project?view=foundry-classic |
| Migrate from Azure AI Inference SDK to OpenAI SDK for Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/model-inference-to-openai-migration?view=foundry-classic |
| Decide when and how to upgrade Azure OpenAI to Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/upgrade-azure-openai?view=foundry-classic |
| Choose content streaming and filtering modes in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/content-streaming?view=foundry-classic |
| Evaluate Azure OpenAI model deprecations and retirements | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/model-retirements?view=foundry-classic |
| Plan migration to updated Azure OpenAI provisioned throughput | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/provisioned-migration?view=foundry-classic |
| Migrate .NET apps from Azure.AI.OpenAI 1.x to 2.x | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/dotnet-migration?view=foundry-classic |
| Plan costs and capacity for Foundry PTU billing | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/provisioned-throughput-onboarding?view=foundry-classic |

### Architecture & Design Patterns
| Topic | URL |
|-------|-----|
| Design standard agent setup with isolated Azure resources | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/concepts/standard-agent-setup?view=foundry-classic |
| Design BCDR architecture for Azure OpenAI deployments | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/business-continuity-disaster-recovery?view=foundry-classic |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Review quotas and limits for Foundry Agent Service | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/quotas-limits?view=foundry-classic |
| Check evaluation rate limits and region support in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/evaluation-regions-limits-virtual-network?view=foundry-classic |
| Understand quotas, rate limits, and timeouts for Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/quotas-limits?view=foundry-classic |
| Manage and increase quotas for Foundry hub resources | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/hub-quota?view=foundry-classic |
| Manage Microsoft Foundry model deployment quotas | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/quota?view=foundry-classic |
| Azure OpenAI FAQ with model and usage limits | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/faq?view=foundry-classic |
| Run large-scale jobs with Azure OpenAI Batch API | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/batch?view=foundry-classic |
| Configure Azure OpenAI dynamic quota and TPM behavior | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/dynamic-quota?view=foundry-classic |
| Use prompt caching for long Azure OpenAI prompts | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/prompt-caching?view=foundry-classic |
| Configure and benchmark Foundry provisioned throughput deployments | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/provisioned-get-started?view=foundry-classic |
| Manage Azure OpenAI quota and rate limits | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/quota?view=foundry-classic |
| Use reinforcement fine-tuning with cost safeguards | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/reinforcement-fine-tuning?view=foundry-classic |
| Reference Azure OpenAI quotas and limits in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/quotas-limits?view=foundry-classic |
| Check Azure OpenAI language and SDK support in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/supported-languages?view=foundry-classic |

### Security
| Topic | URL |
|-------|-----|
| Securely configure Browser Automation in Foundry agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/browser-automation?view=foundry-classic |
| Configure and govern Computer Use tool in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/computer-use?view=foundry-classic |
| Set up private networking for Foundry Agent Service | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/virtual-networks?view=foundry-classic |
| Configure authentication and authorization for Microsoft Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/authentication-authorization-foundry?view=foundry-classic |
| Disable Foundry preview features using custom RBAC roles | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/disable-preview-features-with-rbac?view=foundry-classic |
| Configure customer-managed keys for Microsoft Foundry encryption | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/encryption-keys-portal?view=foundry-classic |
| Use risk and safety evaluators for generative AI | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/evaluation-evaluators/risk-safety-evaluators?view=foundry-classic |
| Use customer-managed keys for Foundry hub encryption | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/hub-encryption-keys-portal?view=foundry-classic |
| Configure RBAC for Microsoft Foundry hubs and projects | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/hub-rbac-foundry?view=foundry-classic |
| Configure guardrails and content safety for Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/model-catalog-content-safety?view=foundry-classic |
| Manage Microsoft Foundry access with RBAC roles | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/rbac-foundry?view=foundry-classic |
| Understand vulnerability management responsibilities in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/vulnerability-management?view=foundry-classic |
| Apply default safety and guardrail policies in Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/concepts/default-safety-policies?view=foundry-classic |
| Create custom deployment policies for Foundry and Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/configure-deployment-policies?view=foundry-classic |
| Set up keyless Microsoft Entra ID auth for Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/configure-entra-id?view=foundry-classic |
| Add Microsoft Foundry resources to a network security perimeter | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/add-foundry-to-network-security-perimeter?view=foundry-classic |
| Apply Azure Policy to secure Foundry hubs and projects | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/azure-policy?view=foundry-classic |
| Control Foundry AI model deployment with Azure Policy | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/built-in-policy-model-deployment?view=foundry-classic |
| Understand data handling and privacy for Foundry model catalog | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/concept-data-privacy?view=foundry-classic |
| Configure managed network isolation for Foundry hubs | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/configure-managed-network?view=foundry-classic |
| Configure Private Link for Microsoft Foundry projects | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/configure-private-link?view=foundry-classic |
| Create and secure a Microsoft Foundry hub | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/create-azure-ai-resource?view=foundry-classic |
| Secure a Foundry hub with managed virtual network | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/create-secure-ai-hub?view=foundry-classic |
| Create custom Azure Policies for Microsoft Foundry resources | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/custom-policy-definition?view=foundry-classic |
| Disable shared key access for Foundry hub storage | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/disable-local-auth?view=foundry-classic |
| Configure Private Link for Microsoft Foundry hubs | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/hub-configure-private-link?view=foundry-classic |
| Enable managed virtual network for Microsoft Foundry projects | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/managed-virtual-network?view=foundry-classic |
| Govern Foundry model deployment with built-in Azure Policy | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/model-deployment-policy?view=foundry-classic |
| Configure the Content Safety tool in prompt flow | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-tools/content-safety-tool?view=foundry-classic |
| Securely configure Foundry playground chat on your data | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/secure-data-playground?view=foundry-classic |
| Understand Azure Direct Models abuse monitoring | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/abuse-monitoring?view=foundry-classic |
| Understand Azure OpenAI default Guardrail policies | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/default-safety-policies?view=foundry-classic |
| Apply safety evaluation for fine-tuned models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/fine-tuning-safety-evaluation?view=foundry-classic |
| Configure Entra ID and managed identity for Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/managed-identity?view=foundry-classic |
| Add Azure OpenAI to a network security perimeter | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/network-security-perimeter?view=foundry-classic |
| Secure Azure OpenAI with VNets and private endpoints | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/network?view=foundry-classic |
| Configure Azure RBAC for Azure OpenAI access | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/role-based-access-control?view=foundry-classic |
| Configure custom block lists for Azure OpenAI content | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/use-blocklists?view=foundry-classic |
| Configure data privacy and security for Azure AI Agent Service | https://learn.microsoft.com/en-us/azure/ai-foundry/responsible-ai/agents/data-privacy-security?view=foundry-classic |
| Understand data handling and privacy for Claude in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/responsible-ai/claude-models/data-privacy?view=foundry-classic |
| Implement required mitigations for Azure OpenAI copyright protection | https://learn.microsoft.com/en-us/azure/ai-foundry/responsible-ai/openai/customer-copyright-commitment?view=foundry-classic |

### Configuration
| Topic | URL |
|-------|-----|
| Configure and manage capability hosts in Foundry Agent Service | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/concepts/capability-hosts?view=foundry-classic |
| Configure and use Code Interpreter in Foundry agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/code-interpreter?view=foundry-classic |
| Configure Foundry agents to use your own Azure resources | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/use-your-own-resources?view=foundry-classic |
| Reference metrics and logs for Foundry Agent Service monitoring | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/reference/monitor-service?view=foundry-classic |
| Use built-in evaluators in Microsoft Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/built-in-evaluators?view=foundry-classic |
| Configure agent evaluators for Azure AI agents | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/evaluation-evaluators/agent-evaluators?view=foundry-classic |
| Use Azure OpenAI graders for model evaluation | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/evaluation-evaluators/azure-openai-graders?view=foundry-classic |
| Create and configure custom evaluators in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/evaluation-evaluators/custom-evaluators?view=foundry-classic |
| Configure general-purpose evaluators for generative AI | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/evaluation-evaluators/general-purpose-evaluators?view=foundry-classic |
| Configure RAG evaluators for Azure AI applications | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/evaluation-evaluators/rag-evaluators?view=foundry-classic |
| Apply textual similarity evaluators in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/evaluation-evaluators/textual-similarity-evaluators?view=foundry-classic |
| Configure and customize content filters in Microsoft Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/configure-content-filters?view=foundry-classic |
| Configure project connections to Microsoft Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/configure-project-connection?view=foundry-classic |
| Configure monitoring and logging for Foundry models | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/monitor-models?view=foundry-classic |
| Configure AI projects to use Microsoft Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/quickstart-ai-project?view=foundry-classic |
| Configure Foundry managed network to reach on-premises | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/access-on-premises-resources?view=foundry-classic |
| Configure bring-your-own storage for Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/bring-your-own-azure-storage-foundry?view=foundry-classic |
| Configure customer-managed storage for Speech and Language | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/bring-your-own-azure-storage-speech-language-services?view=foundry-classic |
| Configure continuous evaluation for Microsoft Foundry agents | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/continuous-evaluation-agents?view=foundry-classic |
| Configure and manage prompt flow compute sessions | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/create-manage-compute-session?view=foundry-classic |
| Create and manage compute instances in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/create-manage-compute?view=foundry-classic |
| Configure cross-project access to serverless API deployments | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/deploy-models-serverless-connect?view=foundry-classic |
| Run cloud evaluations with the Foundry SDK | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/cloud-evaluation?view=foundry-classic |
| Configure tracing and feedback for Foundry flow deployments | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/trace-production-sdk?view=foundry-classic |
| Configure Azure Storage accounts for Foundry evaluations | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/evaluations-storage-account?view=foundry-classic |
| Configure batch runs and evaluation for prompt flows | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/flow-bulk-test-evaluation?view=foundry-classic |
| Create custom evaluation flows in prompt flow | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/flow-develop-evaluation?view=foundry-classic |
| Configure and use vector indexes in Microsoft Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/index-add?view=foundry-classic |
| Monitor quality and token usage for prompt flow apps | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/monitor-quality-safety?view=foundry-classic |
| Reference of prompt flow tools in Foundry portal | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-tools/prompt-flow-tools-overview?view=foundry-classic |
| Use the Prompt tool in Microsoft Foundry flows | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-tools/prompt-tool?view=foundry-classic |
| Configure Azure Key Vault connections in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/set-up-key-vault-connection?view=foundry-classic |
| Interpret and configure Foundry guardrail annotations | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/content-filter-annotations?view=foundry-classic |
| Configure Azure Blob Storage for OpenAI Batch I/O | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/batch-blob-storage?view=foundry-classic |
| Configure Azure OpenAI content filters and gated options | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/content-filters?view=foundry-classic |
| Configure and run Azure OpenAI model evaluations | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/evaluations?view=foundry-classic |
| Test fine-tuned Azure OpenAI models in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/fine-tune-test?view=foundry-classic |
| Configure and run fine-tuning for Foundry models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/fine-tuning?view=foundry-classic |
| Configure monitoring and logging for Azure OpenAI with Azure Monitor | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/monitor-openai?view=foundry-classic |
| Configure network and access for Azure OpenAI On Your Data | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/on-your-data-configuration?view=foundry-classic |
| Migrate from beta to GA GPT Realtime protocol | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/realtime-audio-preview-api-migration-guide?view=foundry-classic |
| Configure reproducible output in Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/reproducible-output?view=foundry-classic |
| Configure spillover traffic management for provisioned deployments | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/spillover-traffic-management?view=foundry-classic |
| Configure and manage block lists in Microsoft Foundry models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/use-blocklists?view=foundry-classic |
| Manage Azure OpenAI model lifecycle and updates | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/working-with-models?view=foundry-classic |
| Reference Azure OpenAI monitoring metrics and logs | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/monitor-openai-reference?view=foundry-classic |
| Check Azure OpenAI supported programming languages in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/supported-languages?view=foundry-classic |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Use Azure AI Search tool with Foundry agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/azure-ai-search-samples?view=foundry-classic |
| Integrate Azure AI Search index with Foundry agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/azure-ai-search?view=foundry-classic |
| Connect Foundry agents to Azure Functions via queues | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/azure-functions-samples?view=foundry-classic |
| Build custom Foundry tools with Azure Functions | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/azure-functions?view=foundry-classic |
| Ground Azure AI Agents with Bing Search results | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/bing-code-samples?view=foundry-classic |
| Integrate Custom Bing Search with Foundry Agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/bing-custom-search-samples?view=foundry-classic |
| Use Computer Use tool with Azure AI Projects SDK | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/computer-use-samples?view=foundry-classic |
| Implement Deep Research tool via Azure AI SDK | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/deep-research-samples?view=foundry-classic |
| Use Microsoft Fabric data agents with Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/fabric?view=foundry-classic |
| Upload files to Agents using file search | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/file-search-upload-files?view=foundry-classic |
| Integrate Azure AI Agents with file search tool | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/file-search?view=foundry-classic |
| Implement function calling with Foundry Agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/function-calling?view=foundry-classic |
| Connect Logic Apps workflows to Foundry Agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/logic-apps?view=foundry-classic |
| MCP tool code samples for Foundry Agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/model-context-protocol-samples?view=foundry-classic |
| Integrate MCP servers with Foundry Agent tools | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/model-context-protocol?view=foundry-classic |
| Use OpenAPI-based tools with Foundry Agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/openapi-spec-samples?view=foundry-classic |
| Configure OpenAPI tools with Foundry Agent Service | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/openapi-spec?view=foundry-classic |
| Use SharePoint tool to ground Azure AI Agents | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/sharepoint-samples?view=foundry-classic |
| Ground Foundry Agents with SharePoint content | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/how-to/tools-classic/sharepoint?view=foundry-classic |
| Use serverless API inference examples for Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/models-inference-examples?view=foundry-classic |
| Call Foundry Responses API to generate text | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/generate-responses?view=foundry-classic |
| Process images and audio with Foundry chat completions | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/use-chat-multi-modal?view=foundry-classic |
| Use reasoning models with Microsoft Foundry chat APIs | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/use-chat-reasoning?view=foundry-classic |
| Generate text embeddings using Microsoft Foundry Models APIs | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/use-embeddings?view=foundry-classic |
| Deploy and invoke Anthropic Claude models in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/use-foundry-models-claude?view=foundry-classic |
| Generate image embeddings with Microsoft Foundry Models APIs | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/use-image-embeddings?view=foundry-classic |
| Implement structured outputs with Foundry chat models | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/use-structured-outputs?view=foundry-classic |
| Evaluate AI agents using Microsoft Foundry SDK | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/agent-evaluate-sdk?view=foundry-classic |
| Integrate LangChain with Microsoft Foundry model deployments | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/langchain?view=foundry-classic |
| Integrate LlamaIndex with Microsoft Foundry model deployments | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/llama-index?view=foundry-classic |
| Run AI Red Teaming Agent in cloud with SDK | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/run-ai-red-teaming-cloud?view=foundry-classic |
| Run AI Red Teaming Agent locally with SDK | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/run-scans-ai-red-teaming-agent?view=foundry-classic |
| Integrate Semantic Kernel with Microsoft Foundry models | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/semantic-kernel?view=foundry-classic |
| Instrument and trace AI agents with OpenTelemetry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/trace-agents-sdk?view=foundry-classic |
| Trace AI applications with OpenAI SDK and OpenTelemetry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/trace-application?view=foundry-classic |
| Integrate MCP server tools with Foundry Classic agents in VS Code | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/vs-code-agents-mcp?view=foundry-classic |
| Use images as inputs in Azure prompt flow | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/flow-process-image?view=foundry-classic |
| Deploy and invoke CXRReportGen healthcare AI model | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/healthcare-ai/deploy-cxrreportgen?view=foundry-classic |
| Deploy and call MedImageInsight for medical image embeddings | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/healthcare-ai/deploy-medimageinsight?view=foundry-classic |
| Use MedImageParse models for medical image segmentation | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/healthcare-ai/deploy-medimageparse?view=foundry-classic |
| Create and manage hub connections in Microsoft Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/hub-connections-add?view=foundry-classic |
| Use Microsoft Foundry endpoints in external applications | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/integrate-with-other-apps?view=foundry-classic |
| Use Azure OpenAI GPT-4V tool in prompt flow | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-tools/azure-open-ai-gpt-4v-tool?view=foundry-classic |
| Use the Embedding tool in Microsoft Foundry flows | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-tools/embedding-tool?view=foundry-classic |
| Configure the Index Lookup tool for RAG flows | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-tools/index-lookup-tool?view=foundry-classic |
| Configure the LLM tool in prompt flow | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-tools/llm-tool?view=foundry-classic |
| Configure and use the Python tool in prompt flow | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-tools/python-tool?view=foundry-classic |
| Use the Rerank tool to improve RAG search | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-tools/rerank-tool?view=foundry-classic |
| Integrate Serp API search in prompt flow | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/prompt-flow-tools/serp-api-tool?view=foundry-classic |
| Use image-to-text models from the Foundry catalog | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/use-image-models?view=foundry-classic |
| Authoring operations in Azure OpenAI REST API | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/authoring-reference-preview?view=foundry-classic |
| Configure function calling for Azure OpenAI Assistants | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/assistant-functions?view=foundry-classic |
| Implement Azure OpenAI Assistants in Foundry classic | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/assistant?view=foundry-classic |
| Use Azure OpenAI chat completion models via API | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/chatgpt?view=foundry-classic |
| Use Azure OpenAI Assistants Code Interpreter | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/code-interpreter?view=foundry-classic |
| Use Codex CLI and VS Code with Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/codex?view=foundry-classic |
| Use Computer Use tool with Azure OpenAI agents | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/computer-use?view=foundry-classic |
| Use Azure OpenAI image generation models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/dall-e?view=foundry-classic |
| Generate embeddings with Azure OpenAI API | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/embeddings?view=foundry-classic |
| Enable and use Assistants file search in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/file-search?view=foundry-classic |
| Implement function calling with Azure OpenAI models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/function-calling?view=foundry-classic |
| Call Azure OpenAI vision-enabled chat models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/gpt-with-vision?view=foundry-classic |
| Use JSON mode with Azure OpenAI chat completions | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/json-mode?view=foundry-classic |
| Migrate Azure OpenAI apps to OpenAI JavaScript v4.x | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/migration-javascript?view=foundry-classic |
| Migrate Azure OpenAI apps to OpenAI Python v1.x | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/migration?view=foundry-classic |
| Connect GPT Realtime audio via SIP | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/realtime-audio-sip?view=foundry-classic |
| Use GPT Realtime audio via WebRTC | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/realtime-audio-webrtc?view=foundry-classic |
| Stream GPT Realtime audio via WebSockets | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/realtime-audio-websockets?view=foundry-classic |
| Implement GPT Realtime API for low-latency audio | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/realtime-audio?view=foundry-classic |
| Call Azure OpenAI Responses API with Python and REST | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/responses?view=foundry-classic |
| Use stored completions and distillation in Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/stored-completions?view=foundry-classic |
| Use structured outputs with Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/structured-outputs?view=foundry-classic |
| Switch Python code between OpenAI and Azure OpenAI endpoints | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/switching-endpoints?view=foundry-classic |
| Enable web_search_preview tool in Responses API | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/web-search?view=foundry-classic |
| Integrate Azure OpenAI fine-tuning with Weights & Biases | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/weights-and-biases-integration?view=foundry-classic |
| Use Azure OpenAI v1 REST API in Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/latest?view=foundry-classic |
| Use Azure OpenAI v1 REST API in Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/latest?view=foundry-classic |
| Use Azure OpenAI v1 REST API in Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/latest?view=foundry-classic |
| Use Azure OpenAI v1 REST API in Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/latest?view=foundry-classic |
| Use Azure OpenAI v1 REST API in Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/latest?view=foundry-classic |
| Use Azure OpenAI v1 REST API in Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/latest?view=foundry-classic |
| Use Azure OpenAI v1 REST API in Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/latest?view=foundry-classic |
| Call Azure OpenAI v1 REST endpoints | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/latest?view=foundry-classic |
| Use Azure OpenAI v1 REST API in Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/latest?view=foundry-classic |
| Use realtime audio events with Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/realtime-audio-reference?view=foundry-classic |
| Use Azure OpenAI v1 preview REST API | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/reference-preview-latest?view=foundry-classic |
| Use Azure OpenAI preview REST endpoints | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/reference-preview?view=foundry-classic |
| Use Azure OpenAI preview REST endpoints | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/reference-preview?view=foundry-classic |
| Use Azure OpenAI preview REST endpoints | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/reference-preview?view=foundry-classic |
| Use Azure OpenAI preview REST endpoints | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/reference-preview?view=foundry-classic |
| Use Azure OpenAI preview REST endpoints | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/reference-preview?view=foundry-classic |
| Use Azure OpenAI REST inference API | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/reference?view=foundry-classic |
| Use Azure OpenAI with Azure Search data via API | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/references/azure-search?view=foundry-classic |
| Use Azure OpenAI with Azure Cosmos DB via API | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/references/cosmos-db?view=foundry-classic |
| Use Azure OpenAI with Elasticsearch data via API | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/references/elasticsearch?view=foundry-classic |
| Use Azure OpenAI with MongoDB Atlas data via API | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/references/mongo-db?view=foundry-classic |
| Call Azure OpenAI On Your Data via Python and REST | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/references/on-your-data?view=foundry-classic |
| Use Azure OpenAI with Pinecone data via API | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/references/pinecone?view=foundry-classic |
| Fine-tune gpt-4o-mini models in Azure OpenAI | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/tutorials/fine-tune?view=foundry-classic |
| Call Microsoft Foundry projects via REST API | https://learn.microsoft.com/en-us/azure/ai-foundry/reference/foundry-project?view=foundry-classic |

### Deployment
| Topic | URL |
|-------|-----|
| Deploy infrastructure for Microsoft Foundry Agent Service | https://learn.microsoft.com/en-us/azure/ai-foundry/agents/environment-setup?view=foundry-classic |
| Choose deployment options for Microsoft Foundry Models | https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/deployments-overview?view=foundry-classic |
| Deploy Microsoft Foundry models via CLI and Bicep | https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/create-model-deployments?view=foundry-classic |
| Deploy a Microsoft Foundry hub via Bicep template | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/create-azure-ai-hub-template?view=foundry-classic |
| Provision Foundry hub and project with Terraform | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/create-hub-terraform?view=foundry-classic |
| Deploy Microsoft Foundry resource using Bicep | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/create-resource-template?view=foundry-classic |
| Provision Microsoft Foundry with Terraform templates | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/create-resource-terraform?view=foundry-classic |
| Deploy partner Foundry Models with pay-as-you-go billing | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/deploy-models-managed-pay-go?view=foundry-classic |
| Check regional availability for serverless model deployments | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/deploy-models-serverless-availability?view=foundry-classic |
| Deploy models as serverless APIs in Microsoft Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/deploy-models-serverless?view=foundry-classic |
| Create a Foundry hub using SDK and Azure CLI | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/create-hub-project-sdk?view=foundry-classic |
| Run Foundry evaluations in Azure DevOps pipelines | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/evaluation-azure-devops?view=foundry-classic |
| Integrate Foundry evaluations into GitHub Actions CI | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/evaluation-github-action?view=foundry-classic |
| Deploy fine-tuned models on Foundry managed compute | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/fine-tune-managed-compute?view=foundry-classic |
| Deploy fine-tuned models via Foundry serverless API | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/fine-tune-serverless?view=foundry-classic |
| Deploy prompt flows as managed online endpoints | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/flow-deploy?view=foundry-classic |
| Create a hub-based project in Microsoft Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/hub-create-projects?view=foundry-classic |
| Deploy fine-tuned Azure OpenAI models in Foundry | https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/fine-tuning-deploy?view=foundry-classic |
| Deploy an enterprise chat web app in Microsoft Foundry playground | https://learn.microsoft.com/en-us/azure/ai-foundry/tutorials/deploy-chat-web-app?view=foundry-classic |