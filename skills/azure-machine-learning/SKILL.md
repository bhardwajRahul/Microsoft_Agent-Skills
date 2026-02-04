---
name: azure-machine-learning
description: Expert knowledge for Azure Machine Learning development including decision making, security, configuration, best practices, limits & quotas, integrations & coding patterns, troubleshooting, and deployment. Use when building, debugging, or optimizing Azure Machine Learning applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
metadata:
  generated_at: "2026-02-04"
---
# Azure Machine Learning Skill

This skill provides expert guidance for Azure Machine Learning development. It combines local quick-reference content with remote documentation fetching capabilities.

## How to Use This Skill

> **IMPORTANT for Agent**: This file may be large. Use the **Category Index** below to locate relevant sections, then use `read_file` with specific line ranges (e.g., `L136-L144`) to read the sections needed for the user's question
> **IMPORTANT for Agent**: If `metadata.generated_at` is more than 3 months old, suggest the user pull the latest version from the repository. If `mcp_microsoftdocs` tools are not available, suggest the user install it: [Installation Guide](https://github.com/MicrosoftDocs/mcp/blob/main/README.md)

This skill requires **network access**. Use `mcp_microsoftdocs:microsoft_docs_fetch` or `fetch_webpage` if MCP is unavailable to fetch documentation.

## Category Index

| Category | Lines | Description |
|----------|-------|-------------|
| Troubleshooting | L32-L43 | Diagnosing and fixing Azure ML issues in AutoML (forecasting/experiments), data labeling, managed VNets, workspace health, prompt flow, and managed feature store errors. |
| Best Practices | L44-L55 | Best practices for AutoML tuning, data collection, feature design, distributed GPU training, generative AI monitoring/safety, and large-model checkpoint optimization in Azure ML |
| Decision Making | L56-L78 | Guidance on Azure ML design decisions: algorithm and data patterns, DR/failover, and detailed v1→v2 migration/upgrade paths for workspaces, data, models, jobs, endpoints, and logging. |
| Limits & Quotas | L79-L86 | Managing Azure ML workspace data retention, storage limits, serverless training capacity, and service quotas to plan, avoid limits, and configure soft delete/retention. |
| Security | L87-L119 | Securing Azure ML workspaces, data, and networking: VNets/Private Link, RBAC and auth, CMK, data exfiltration controls, policies, and secure access for training, inferencing, RAG, and feature store. |
| Configuration | L120-L249 | Configuring Azure ML resources, jobs, AutoML, prompt flow, data, compute, environments, connections, and YAML/CLI settings for training, deployment, monitoring, and Responsible AI. |
| Integrations & Coding Patterns | L250-L286 | Integrating Azure ML with storage, Spark/Kubernetes/Databricks/Synapse, MLflow, prompt flow, and frameworks (PyTorch, TF, Keras, scikit-learn, HF, ONNX) for training, logging, and deployment. |
| Deployment | L287-L302 | Deploying ML and prompt flow apps to Azure ML (online/batch), using ARM/Bicep/Terraform, MLflow, SDK/CLI, and setting up DevOps/GenAIOps rollout pipelines. |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Resolve common Azure AutoML forecasting issues | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-automl-forecasting-faq?view=azureml-api-2 |
| Diagnose and fix Azure AutoML experiment failures | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-troubleshoot-auto-ml?view=azureml-api-2 |
| Troubleshoot AzureML data labeling project creation errors | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-troubleshoot-data-labeling?view=azureml-api-2 |
| Diagnose Azure ML managed virtual network issues | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-troubleshoot-managed-network?view=azureml-api-2 |
| Run workspace diagnostics for Azure Machine Learning | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-workspace-diagnostic-api?view=azureml-api-2 |
| Troubleshoot common Azure ML prompt flow issues | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/troubleshoot-guidance?view=azureml-api-2 |
| Troubleshoot common Azure ML prompt flow issues | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/troubleshoot-guidance?view=azureml-api-2 |
| Troubleshoot Azure ML managed feature store errors | https://learn.microsoft.com/en-us/azure/machine-learning/troubleshooting-managed-feature-store?view=azureml-api-2 |

### Best Practices
| Topic | URL |
|-------|-----|
| Mitigate overfitting and imbalance in Azure AutoML | https://learn.microsoft.com/en-us/azure/machine-learning/concept-manage-ml-pitfalls?view=azureml-api-2 |
| Apply responsible data collection practices for human data in Azure ML | https://learn.microsoft.com/en-us/azure/machine-learning/concept-sourcing-human-data?view=azureml-api-2 |
| Design feature set specifications and transformations in Azure ML | https://learn.microsoft.com/en-us/azure/machine-learning/feature-set-specification-transformation-concepts?view=azureml-api-2 |
| Best practices for distributed GPU training on Azure ML | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-train-distributed-gpu?view=azureml-api-2 |
| Optimize AutoML for small object detection in images | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-use-automl-small-object-detect?view=azureml-api-2 |
| Apply generative AI monitoring metrics in Azure ML | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/concept-model-monitoring-generative-ai-evaluation-metrics?view=azureml-api-2 |
| Monitor safety and quality of Azure ML generative apps | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/how-to-monitor-generative-ai-applications?view=azureml-api-2 |
| Optimize checkpoint performance for large Azure ML models with Nebula | https://learn.microsoft.com/en-us/azure/machine-learning/reference-checkpoint-performance-for-large-models?view=azureml-api-2 |

### Decision Making
| Topic | URL |
|-------|-----|
| Choose ML algorithms with Azure designer cheat sheet | https://learn.microsoft.com/en-us/azure/machine-learning/algorithm-cheat-sheet?view=azureml-api-1 |
| Choose Azure Data Factory patterns for AzureML ingestion | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-data-ingest-adf?view=azureml-api-1 |
| Plan Azure ML failover and disaster recovery strategy | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-high-availability-machine-learning?view=azureml-api-2 |
| Decide when and how to upgrade Azure ML from v1 to v2 | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-migrate-from-v1?view=azureml-api-2 |
| Move Azure ML workspaces between subscriptions | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-move-workspace?view=azureml-api-2 |
| Map and upgrade Azure ML data assets from v1 datasets to v2 | https://learn.microsoft.com/en-us/azure/machine-learning/migrate-to-v2-assets-data?view=azureml-api-2 |
| Upgrade Azure ML model management workflows from SDK v1 to v2 | https://learn.microsoft.com/en-us/azure/machine-learning/migrate-to-v2-assets-model?view=azureml-api-2 |
| Migrate Azure ML script run submissions from SDK v1 to v2 jobs | https://learn.microsoft.com/en-us/azure/machine-learning/migrate-to-v2-command-job?view=azureml-api-2 |
| Choose and upgrade Azure ML deployment endpoints to v2 | https://learn.microsoft.com/en-us/azure/machine-learning/migrate-to-v2-deploy-endpoints?view=azureml-api-2 |
| Upgrade Azure ML AutoML configurations from SDK v1 to v2 jobs | https://learn.microsoft.com/en-us/azure/machine-learning/migrate-to-v2-execution-automl?view=azureml-api-2 |
| Upgrade Azure ML hyperparameter tuning from HyperDrive v1 to v2 sweep jobs | https://learn.microsoft.com/en-us/azure/machine-learning/migrate-to-v2-execution-hyperdrive?view=azureml-api-2 |
| Compare local run workflows between Azure ML SDK v1 and v2 | https://learn.microsoft.com/en-us/azure/machine-learning/migrate-to-v2-local-runs?view=azureml-api-2 |
| Upgrade ACI web services to managed online endpoints | https://learn.microsoft.com/en-us/azure/machine-learning/migrate-to-v2-managed-online-endpoints?view=azureml-api-2 |
| Compare and upgrade Azure ML compute management from v1 to v2 | https://learn.microsoft.com/en-us/azure/machine-learning/migrate-to-v2-resource-compute?view=azureml-api-2 |
| Plan datastore migration from Azure ML SDK v1 to v2 | https://learn.microsoft.com/en-us/azure/machine-learning/migrate-to-v2-resource-datastore?view=azureml-api-2 |
| Compare and upgrade Azure ML workspace management from SDK v1 to v2 | https://learn.microsoft.com/en-us/azure/machine-learning/migrate-to-v2-resource-workspace?view=azureml-api-2 |
| Assess and advance your organization’s GenAIOps maturity | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/concept-llmops-maturity?view=azureml-api-2 |
| Check Azure ML feature availability across sovereign clouds | https://learn.microsoft.com/en-us/azure/machine-learning/reference-machine-learning-cloud-parity?view=azureml-api-2 |
| Map SDK v1 logging APIs to MLflow tracking | https://learn.microsoft.com/en-us/azure/machine-learning/reference-migrate-sdk-v1-mlflow-tracking?view=azureml-api-2 |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Use soft delete and retention for Azure ML workspaces | https://learn.microsoft.com/en-us/azure/machine-learning/concept-soft-delete?view=azureml-api-2 |
| Avoid storage limits when saving AML experiment files | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-save-write-experiment-files?view=azureml-api-1 |
| Train models on Azure ML serverless compute | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-use-serverless-compute?view=azureml-api-2 |
| Plan capacity using Azure Machine Learning service limits | https://learn.microsoft.com/en-us/azure/machine-learning/resource-limits-capacity?view=azureml-api-2 |

### Security
| Topic | URL |
|-------|-----|
| Understand data handling for Model Catalog deployments | https://learn.microsoft.com/en-us/azure/machine-learning/concept-data-privacy?view=azureml-api-2 |
| Configure Azure ML inbound and outbound network traffic | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-access-azureml-behind-firewall?view=azureml-api-2 |
| Enable Azure ML managed network access to on-premises | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-access-on-premises-resources?view=azureml-api-2 |
| Grant limited workspace access for AzureML labeling users | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-add-users?view=azureml-api-2 |
| Administer data access and authentication in Azure ML | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-administrate-data-authentication?view=azureml-api-2 |
| Configure data access authentication for AzureML | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-administrate-data-authentication?view=azureml-api-2 |
| Use built-in Azure Policy to govern AI model deployment | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-built-in-policy-model-deployment?view=azureml-api-2 |
| Maintain network isolation with Azure ML v2 ARM APIs | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-configure-network-isolation-with-v2?view=azureml-api-2 |
| Configure private endpoints for Azure ML workspaces | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-configure-private-link?view=azureml-api-2 |
| Create custom Azure Policies for AI model deployment control | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-custom-policy-model-deployment?view=azureml-api-2 |
| Configure Azure ML workspace storage without shared keys | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-disable-local-auth-storage?view=azureml-api-2 |
| Enable Azure ML studio access inside virtual networks | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-enable-studio-virtual-network?view=azureml-api-2 |
| Configure Model Catalog access with workspace managed VNet | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-network-isolation-model-catalog?view=azureml-api-2 |
| Prevent data exfiltration in Azure ML network setups | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-prevent-data-loss-exfiltration?view=azureml-api-2 |
| Secure Azure Synapse–Azure ML integration with VNets | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-private-endpoint-integration-synapse?view=azureml-api-2 |
| Isolate Azure ML registries with VNets and Private Link | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-registry-network-isolation?view=azureml-api-2 |
| Secure Azure ML online inferencing with VNets | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-secure-inferencing-vnet?view=azureml-api-2 |
| Secure Azure ML RAG workflows with private networking | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-secure-rag-workflows?view=azureml-api-2 |
| Secure Azure ML training compute with virtual networks | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-secure-training-vnet?view=azureml-api-2 |
| Secure Azure ML workspaces with VNets and endpoints | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-secure-workspace-vnet?view=azureml-api-2 |
| Attach Azure Databricks securely to Azure ML via Private Link | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-securely-attach-databricks?view=azureml-api-2 |
| Configure RBAC access to Azure ML managed feature store | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-setup-access-control-feature-store?view=azureml-api-2 |
| Configure customer-managed keys for Azure ML | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-setup-customer-managed-keys?view=azureml-api-2 |
| Securely use private Python packages in Azure ML | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-use-private-python-packages?view=azureml-api-1 |
| Securely access Key Vault secrets in Azure ML jobs | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-use-secrets-in-runs?view=azureml-api-2 |
| Apply built-in Azure Policy definitions for Azure Machine Learning | https://learn.microsoft.com/en-us/azure/machine-learning/policy-reference?view=azureml-api-2 |
| Manage credentials with prompt flow connections | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/concept-connections?view=azureml-api-2 |
| Secure prompt flow with private network isolation | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/how-to-secure-prompt-flow?view=azureml-api-2 |
| Configure network isolation for Azure ML feature store | https://learn.microsoft.com/en-us/azure/machine-learning/tutorial-network-isolation-for-feature-store?view=azureml-api-2 |

### Configuration
| Topic | URL |
|-------|-----|
| Use Azure ML SDK/CLI v2 expressions in jobs | https://learn.microsoft.com/en-us/azure/machine-learning/concept-expressions?view=azureml-api-2 |
| Create Azure ML datastores from OneLake tables via UI | https://learn.microsoft.com/en-us/azure/machine-learning/create-datastore-with-user-interface?view=azureml-api-2 |
| Use keyboard shortcuts and accessibility in Azure ML designer | https://learn.microsoft.com/en-us/azure/machine-learning/designer-accessibility?view=azureml-api-2 |
| Configure Azure AutoML for time-series forecasting | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-auto-train-forecast?view=azureml-api-2 |
| Configure Azure AutoML for custom NLP models | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-auto-train-nlp-models?view=azureml-api-2 |
| Customize data featurization settings in Azure AutoML | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-configure-auto-features?view=azureml-api-1 |
| Configure Azure AutoML tabular training with SDK v2 | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-configure-auto-train?view=azureml-api-2 |
| Install and configure Azure ML CLI v2 extension | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-configure-cli?view=azureml-api-2 |
| Install and configure Azure ML CLI v2 extension | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-configure-cli?view=azureml-api-2 |
| Configure data splits and cross-validation in Azure AutoML | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-configure-cross-validation-data-splits?view=azureml-api-1 |
| Configure Python environments for Azure Machine Learning | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-configure-environment?view=azureml-api-2 |
| Create datastores and datasets in AzureML studio | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-connect-data-ui?view=azureml-api-1 |
| Configure Azure ML connections to external data and services | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-connection?view=azureml-api-2 |
| Create and configure Azure ML compute clusters | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-create-attach-compute-cluster?view=azureml-api-2 |
| Manage training and deployment computes in Azure ML studio | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-create-attach-compute-studio?view=azureml-api-2 |
| Create Azure ML compute instances for development | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-create-compute-instance?view=azureml-api-2 |
| Create Azure ML compute instances for development | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-create-compute-instance?view=azureml-api-2 |
| Create and manage Azure ML data assets | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-create-data-assets?view=azureml-api-2 |
| Create and manage AzureML data assets | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-create-data-assets?view=azureml-api-2 |
| Configure image labeling projects in AzureML | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-create-image-labeling-projects?view=azureml-api-2 |
| Configure text labeling projects in AzureML | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-create-text-labeling-projects?view=azureml-api-2 |
| Configure and use vector indexes in Azure ML prompt flow | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-create-vector-index?view=azureml-api-2 |
| Configure custom DNS for Azure ML private endpoints | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-custom-dns?view=azureml-api-2 |
| Customize Azure ML compute instances with startup scripts | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-customize-compute-instance?view=azureml-api-2 |
| Configure Azure ML datastores for storage access | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-datastore?view=azureml-api-2 |
| Export or delete Azure ML workspace data via portal and SDK | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-export-delete-data?view=azureml-api-2 |
| Import external data into Azure ML as data assets | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-import-data-assets?view=azureml-api-2 |
| Label images and text in AzureML projects | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-label-data?view=azureml-api-2 |
| Configure Azure ML distributed logs to Application Insights | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-log-search?view=azureml-api-2 |
| Manage lifecycle and settings of Azure ML compute instances | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-manage-compute-instance?view=azureml-api-2 |
| Create and manage Azure ML environments in Studio | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-manage-environments-in-studio?view=azureml-api-2 |
| Configure Azure ML environments with CLI and SDK v2 | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-manage-environments-v2?view=azureml-api-2 |
| Manage Azure ML hub workspaces in the portal | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-manage-hub-workspace-portal?view=azureml-api-2 |
| Manage lifecycle and auto-delete for imported data assets | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-manage-imported-data-assets?view=azureml-api-2 |
| Administer and export labels from AzureML projects | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-manage-labeling-projects?view=azureml-api-2 |
| Create and manage Azure ML registries across regions | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-manage-registries?view=azureml-api-2 |
| Configure and manage Azure ML resources via VS Code | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-manage-resources-vscode?view=azureml-api-2 |
| Manage Azure ML workspaces with PowerShell cmdlets | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-manage-workspace-powershell?view=azureml-api-2 |
| Configure dataset data drift monitoring in AzureML | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-monitor-datasets?view=azureml-api-1 |
| Use R interactively on Azure ML compute instances | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-r-interactive-development?view=azureml-api-2 |
| Use and configure Azure ML Responsible AI dashboard tools | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-responsible-ai-dashboard?view=azureml-api-2 |
| Configure Responsible AI dashboards with YAML and Python | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-responsible-ai-insights-sdk-cli?view=azureml-api-2 |
| Generate and customize Azure ML Responsible AI scorecards | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-responsible-ai-scorecard?view=azureml-api-2 |
| Schedule automated data imports in Azure ML | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-schedule-data-import?view=azureml-api-2 |
| Configure Azure ML training compute targets (SDK v1) | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-set-up-training-targets?view=azureml-api-1 |
| Set up VS Code with Azure Machine Learning extension | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-setup-vs-code?view=azureml-api-2 |
| Use custom Docker images for Azure ML training (SDK v1) | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-train-with-custom-image?view=azureml-api-1 |
| Configure hyperparameter sweep jobs in Azure ML v2 | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-tune-hyperparameters?view=azureml-api-2 |
| Configure MLflow tracking with Azure Machine Learning | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-use-mlflow-configure-tracking?view=azureml-api-2 |
| Configure dataset versioning in AzureML pipelines | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-version-track-datasets?view=azureml-api-1 |
| Configure serverless Spark compute for Azure ML notebooks | https://learn.microsoft.com/en-us/azure/machine-learning/interactive-data-wrangling-with-apache-spark-azure-ml?view=azureml-api-2 |
| Reference Azure Machine Learning monitoring metrics and logs | https://learn.microsoft.com/en-us/azure/machine-learning/monitor-azure-machine-learning-reference?view=azureml-api-2 |
| Create and register custom tool packages in prompt flow | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/how-to-custom-tool-package-creation-and-usage?view=azureml-api-2 |
| Customize base Docker image for prompt flow sessions | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/how-to-customize-session-base-image?view=azureml-api-2 |
| Configure and consume streaming endpoints from prompt flow | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/how-to-enable-streaming-mode?view=azureml-api-2 |
| Enable tracing and feedback for prompt flow deployments | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/how-to-enable-trace-feedback-for-deployment?view=azureml-api-2 |
| Configure and manage prompt flow compute sessions | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/how-to-manage-compute-session?view=azureml-api-2 |
| Configure Azure OpenAI GPT-4 Turbo with Vision tool in prompt flow | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/tools-reference/azure-open-ai-gpt-4v-tool?view=azureml-api-2 |
| Use Content Safety text tool for moderation in prompt flow | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/tools-reference/content-safety-text-tool?view=azureml-api-2 |
| Configure the embedding tool for OpenAI models in prompt flow | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/tools-reference/embedding-tool?view=azureml-api-2 |
| Configure Index Lookup tool for RAG in Azure ML prompt flow | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/tools-reference/index-lookup-tool?view=azureml-api-2 |
| Configure and use the LLM tool in Azure ML prompt flow | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/tools-reference/llm-tool?view=azureml-api-2 |
| Use Open Model LLM tool with open-source models in prompt flow | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/tools-reference/open-model-llm-tool?view=azureml-api-2 |
| Configure OpenAI GPT-4V vision tool in Azure ML prompt flow | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/tools-reference/openai-gpt-4v-tool?view=azureml-api-2 |
| Configure prompt templates with the prompt tool in prompt flow | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/tools-reference/prompt-tool?view=azureml-api-2 |
| Create and configure Python tools as nodes in prompt flow | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/tools-reference/python-tool?view=azureml-api-2 |
| Configure Rerank tool to improve RAG search relevance | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/tools-reference/rerank-tool?view=azureml-api-2 |
| Configure SerpAPI search tool in Azure ML prompt flow | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/tools-reference/serp-api-tool?view=azureml-api-2 |
| Configure AutoML forecasting jobs with Azure ML YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-automated-ml-forecasting?view=azureml-api-2 |
| Author AutoML image classification jobs via YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-automl-images-cli-classification?view=azureml-api-2 |
| Configure AutoML image instance segmentation jobs in YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-automl-images-cli-instance-segmentation?view=azureml-api-2 |
| Define AutoML image multilabel classification jobs with YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-automl-images-cli-multilabel-classification?view=azureml-api-2 |
| Configure AutoML image object detection jobs via YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-automl-images-cli-object-detection?view=azureml-api-2 |
| Use AutoML computer vision hyperparameters effectively | https://learn.microsoft.com/en-us/azure/machine-learning/reference-automl-images-hyperparameters?view=azureml-api-2 |
| Format JSONL datasets for AutoML computer vision tasks | https://learn.microsoft.com/en-us/azure/machine-learning/reference-automl-images-schema?view=azureml-api-2 |
| Configure AutoML multilabel text classification jobs in YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-automl-nlp-cli-multilabel-classification?view=azureml-api-2 |
| Define AutoML NLP NER jobs with Azure ML YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-automl-nlp-cli-ner?view=azureml-api-2 |
| Author AutoML text classification jobs using YAML schema | https://learn.microsoft.com/en-us/azure/machine-learning/reference-automl-nlp-cli-text-classification?view=azureml-api-2 |
| Define command components with AzureML YAML schema | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-component-command?view=azureml-api-2 |
| Author pipeline components in AzureML using YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-component-pipeline?view=azureml-api-2 |
| Configure Spark components in AzureML via YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-component-spark?view=azureml-api-2 |
| Configure AmlCompute clusters via Azure ML YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-compute-aml?view=azureml-api-2 |
| Define Azure ML compute instances with YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-compute-instance?view=azureml-api-2 |
| Configure attached Kubernetes clusters with Azure ML YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-compute-kubernetes?view=azureml-api-2 |
| Configure attached virtual machines in Azure ML YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-compute-vm?view=azureml-api-2 |
| Define AI Content Safety connections with CLI v2 YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-connection-ai-content-safety?view=azureml-api-2 |
| Author AI Search connection YAML for Azure ML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-connection-ai-search?view=azureml-api-2 |
| Configure Foundry Tools connections via AzureML YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-connection-ai-services?view=azureml-api-2 |
| Create API key connections with Azure ML YAML schema | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-connection-api-key?view=azureml-api-2 |
| Define Azure OpenAI connections with AzureML YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-connection-azure-openai?view=azureml-api-2 |
| Specify blob store connections using YAML schema | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-connection-blob?view=azureml-api-2 |
| Configure Azure Container Registry connections via YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-connection-container-registry?view=azureml-api-2 |
| Define custom key connections using CLI v2 YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-connection-custom-key?view=azureml-api-2 |
| Create Data Lake Gen2 connections with YAML schema | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-connection-data-lake?view=azureml-api-2 |
| Set up Git connections using Azure ML YAML schema | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-connection-git?view=azureml-api-2 |
| Define OneLake connections in Azure ML YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-connection-onelake?view=azureml-api-2 |
| Configure OpenAI service connections in Azure ML YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-connection-openai?view=azureml-api-2 |
| Define Python feed connections using CLI v2 YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-connection-python-feed?view=azureml-api-2 |
| Author Serp connections with Azure ML YAML schema | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-connection-serp?view=azureml-api-2 |
| Configure serverless connections via Azure ML YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-connection-serverless?view=azureml-api-2 |
| Configure AI Speech Services connections via YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-connection-speech?view=azureml-api-2 |
| Define Azure Blob datastores with CLI v2 YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-datastore-blob?view=azureml-api-2 |
| Author Azure Data Lake Gen1 datastore YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-datastore-data-lake-gen1?view=azureml-api-2 |
| Author Azure Data Lake Gen2 datastore YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-datastore-data-lake-gen2?view=azureml-api-2 |
| Configure Azure Files datastores via CLI v2 YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-datastore-files?view=azureml-api-2 |
| Define batch deployments in AzureML using YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-deployment-batch?view=azureml-api-2 |
| Author Kubernetes online deployment YAML for AzureML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-deployment-kubernetes-online?view=azureml-api-2 |
| Configure managed online deployments with YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-deployment-managed-online?view=azureml-api-2 |
| Use deployment template YAML schema in AzureML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-deployment-template?view=azureml-api-2 |
| Define batch endpoints in AzureML via YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-endpoint-batch?view=azureml-api-2 |
| Configure AzureML online endpoints with YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-endpoint-online?view=azureml-api-2 |
| Define feature entities in AzureML via YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-feature-entity?view=azureml-api-2 |
| Author feature retrieval specs using AzureML YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-feature-retrieval-spec?view=azureml-api-2 |
| Configure AzureML feature sets with YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-feature-set?view=azureml-api-2 |
| Define AzureML feature stores using YAML schema | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-feature-store?view=azureml-api-2 |
| Specify feature set behavior with AzureML YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-featureset-spec?view=azureml-api-2 |
| Author Azure ML command jobs using YAML schema | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-job-command?view=azureml-api-2 |
| Create Azure ML parallel jobs within pipelines using YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-job-parallel?view=azureml-api-2 |
| Author Azure ML CLI v2 pipeline job YAML configurations | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-job-pipeline?view=azureml-api-2 |
| Configure Azure ML pipeline jobs via YAML schema | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-job-pipeline?view=azureml-api-2 |
| Configure Azure ML Spark jobs via YAML schema | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-job-spark?view=azureml-api-2 |
| Define Azure ML sweep jobs with YAML schema | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-job-sweep?view=azureml-api-2 |
| Author model monitoring schedules with Azure ML YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-monitor?view=azureml-api-2 |
| Author Azure ML registry resources with YAML schema | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-registry?view=azureml-api-2 |
| Configure data import schedules in Azure ML YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-schedule-data-import?view=azureml-api-2 |
| Define Azure ML job schedules with CLI v2 YAML | https://learn.microsoft.com/en-us/azure/machine-learning/reference-yaml-schedule?view=azureml-api-2 |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Access Azure cloud storage during interactive ML development | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-access-data-interactive?view=azureml-api-2 |
| Use Kubernetes clusters as Azure ML compute targets | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-attach-kubernetes-anywhere?view=azureml-api-2 |
| Configure AutoML computer vision with CLI and SDK v2 | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-auto-train-image-models?view=azureml-api-2 |
| Set up Azure Databricks with Azure ML AutoML | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-configure-databricks-automl-environment?view=azureml-api-1 |
| Wrangle data using Synapse Spark pools with AzureML | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-data-prep-synapse-spark-pool?view=azureml-api-1 |
| Configure Azure ML datastores for Azure storage | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-datastore?view=azureml-api-2 |
| Configure Azure ML datastores for Azure storage | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-datastore?view=azureml-api-2 |
| Run MLflow models in Azure ML Spark jobs | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-deploy-mlflow-model-spark-jobs?view=azureml-api-2 |
| Deploy Hugging Face models to Azure ML endpoints | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-deploy-models-from-huggingface?view=azureml-api-2 |
| Import data into AzureML designer using datasets | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-designer-import-data?view=azureml-api-1 |
| Run local ONNX inference for AutoML image models | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-inference-onnx-automl-image-models?view=azureml-api-2 |
| Manage Azure ML model registry using MLflow | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-manage-models-mlflow?view=azureml-api-2 |
| Manage Azure ML resources using REST APIs | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-manage-rest?view=azureml-api-2 |
| Define and load AzureML mltable data as DataFrames | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-mltable?view=azureml-api-2 |
| Read and write data in Azure ML training jobs | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-read-write-data-v2?view=azureml-api-2 |
| Read and write data in AzureML jobs | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-read-write-data-v2?view=azureml-api-2 |
| Submit standalone and pipeline Spark jobs in Azure ML | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-submit-spark-jobs?view=azureml-api-2 |
| Log metrics in AzureML designer pipelines | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-track-designer-experiments?view=azureml-api-1 |
| Query and compare Azure ML experiments with MLflow | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-track-experiments-mlflow?view=azureml-api-2 |
| Train and deploy Keras deep learning models on Azure ML | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-train-keras?view=azureml-api-2 |
| Run MLflow Projects using Azure Machine Learning compute | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-train-mlflow-projects?view=azureml-api-2 |
| Train, tune, and deploy PyTorch models with Azure ML v2 | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-train-pytorch?view=azureml-api-2 |
| Run and scale scikit-learn training with Azure ML v2 | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-train-scikit-learn?view=azureml-api-2 |
| Train and deploy TensorFlow models on Azure ML v2 | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-train-tensorflow?view=azureml-api-2 |
| Use AutoML ONNX models for prediction in .NET | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-use-automl-onnx-model-dotnet?view=azureml-api-2 |
| Consume Azure ML batch endpoints from Microsoft Fabric | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-use-batch-fabric?view=azureml-api-2 |
| Use labeled datasets from AzureML labeling projects | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-use-labeled-dataset?view=azureml-api-1 |
| Integrate Azure Databricks ML experiments with MLflow and Azure ML | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-use-mlflow-azure-databricks?view=azureml-api-2 |
| Connect Azure Synapse ML experiments to MLflow and Azure ML | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-use-mlflow-azure-synapse?view=azureml-api-2 |
| Use prompt flow tools to integrate APIs and packages | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/concept-tools?view=azureml-api-2 |
| Evaluate Semantic Kernel plugins using prompt flow | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/how-to-evaluate-semantic-kernel?view=azureml-api-2 |
| Integrate LangChain workflows into Azure prompt flow | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/how-to-integrate-with-langchain?view=azureml-api-2 |
| Submit Apache Spark jobs with Azure ML integration | https://learn.microsoft.com/en-us/azure/machine-learning/quickstart-spark-jobs?view=azureml-api-2 |

### Deployment
| Topic | URL |
|-------|-----|
| Deploy Azure ML workspaces using ARM templates | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-create-workspace-template?view=azureml-api-2 |
| Deploy MLflow models to Azure ML online endpoints | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-deploy-mlflow-models-online-endpoints?view=azureml-api-2 |
| Progressive rollout of MLflow models on Azure ML | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-deploy-mlflow-models-online-progressive?view=azureml-api-2 |
| Deploy MLflow models to Azure ML targets | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-deploy-mlflow-models?view=azureml-api-2 |
| Create Azure ML hub workspaces with Bicep templates | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-manage-hub-workspace-template?view=azureml-api-2 |
| Provision Azure ML workspaces with Terraform | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-manage-workspace-terraform?view=azureml-api-2 |
| Batch deploy MLflow models with Azure ML endpoints | https://learn.microsoft.com/en-us/azure/machine-learning/how-to-mlflow-batch?view=azureml-api-2 |
| Deploy prompt flow as managed online endpoint | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/how-to-deploy-for-real-time-inference?view=azureml-api-2 |
| Deploy prompt flow to online endpoints using Azure CLI | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/how-to-deploy-to-code?view=azureml-api-2 |
| Set up GenAIOps pipelines with prompt flow and Azure DevOps | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/how-to-end-to-end-azure-devops-with-prompt-flow?view=azureml-api-2 |
| Set up GenAIOps pipelines with prompt flow and GitHub | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/how-to-end-to-end-llmops-with-prompt-flow?view=azureml-api-2 |
| Integrate prompt flow with DevOps pipelines for LLM apps | https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/how-to-integrate-with-llm-app-devops?view=azureml-api-2 |
| Deploy models to Azure ML online endpoints with SDK v2 | https://learn.microsoft.com/en-us/azure/machine-learning/tutorial-deploy-model?view=azureml-api-2 |