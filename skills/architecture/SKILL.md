---
name: architecture
description: Expert knowledge for Architecture development including architecture & design patterns, best practices, comparing x vs. y, security, deployment, and troubleshooting. Use when building, debugging, or optimizing Architecture applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Architecture Skill

This skill provides expert guidance for Architecture development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Design a secure research environment for regulated data on Azure | https://learn.microsoft.com/en-us/azure/architecture/ai-ml/architecture/secure-compute-for-research |
| Compare Microsoft machine learning products and platforms | https://learn.microsoft.com/en-us/azure/architecture/ai-ml/guide/data-science-and-machine-learning |
| Avoid monolithic persistence in Azure architectures | https://learn.microsoft.com/en-us/azure/architecture/antipatterns/monolithic-persistence/ |
| Handle noisy neighbor issues in multitenant systems | https://learn.microsoft.com/en-us/azure/architecture/antipatterns/noisy-neighbor/noisy-neighbor |
| Design and manage AKS node and node pool strategies | https://learn.microsoft.com/en-us/azure/architecture/aws-professional/eks-to-aks/node-pools |
| Select Azure AI services for video and image processing | https://learn.microsoft.com/en-us/azure/architecture/data-guide/ai-services/image-video-processing |
| Choose Azure speech recognition and generation services | https://learn.microsoft.com/en-us/azure/architecture/data-guide/ai-services/speech-recognition-generation |
| Select Azure AI targeted language processing services | https://learn.microsoft.com/en-us/azure/architecture/data-guide/ai-services/targeted-language-processing |
| Design Azure data platform architecture with DR | https://learn.microsoft.com/en-us/azure/architecture/data-guide/disaster-recovery/dr-for-azure-data-platform-architecture |
| Select Azure data transfer technologies and tools | https://learn.microsoft.com/en-us/azure/architecture/data-guide/scenarios/data-transfer |
| Choose Azure AI services for applications and data | https://learn.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/ai-services |
| Select Azure analytics and reporting technologies | https://learn.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/analysis-visualizations-reporting |
| Choose an analytical data store in Azure | https://learn.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/analytical-data-stores |
| Select big data storage technologies in Azure | https://learn.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/data-storage |
| Choose Azure NLP services for text analytics | https://learn.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/natural-language-processing |
| Choose Azure data pipeline orchestration technology | https://learn.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/pipeline-orchestration-data-movement |
| Choose an Azure search data store service | https://learn.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/search-options |
| Compare Azure real-time stream processing options | https://learn.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/stream-processing |
| Compare Azure data store models for workloads | https://learn.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/understand-data-store-models |
| Design an enterprise BI solution with Microsoft Fabric | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/analytics/enterprise-bi-microsoft-fabric |
| Sync MongoDB Atlas changes to Azure Synapse in real time | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/analytics/sync-mongodb-atlas-azure-synapse-analytics |
| Run IBM Maximo Application Suite on Azure | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/apps/deploy-ibm-maximo-application-suite |
| Model and score Azure app sustainability (SCI) | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/apps/measure-azure-app-sustainability-sci-score |
| Design high-availability SAP on Oracle in Azure | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/apps/sap-production |
| Automate certificate lifecycle management with Azure and nonintegrated CAs | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/certificate-lifecycle/ |
| Architect an Azure data warehouse and analytics pipeline | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/data/data-warehouse |
| Build near real-time lakehouse processing with Synapse | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/data/real-time-lakehouse-data-processing |
| Modernize SMB data warehouses with Fabric and Azure SQL | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/data/small-medium-data-warehouse |
| Implement end-to-end analytics with Microsoft Fabric | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/dataplate2e/data-platform-end-to-end |
| Implement resilient Azure NetApp Files shares with disaster recovery | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/file-storage/enterprise-file-shares-disaster-recovery |
| Deploy Moodle on Azure with Azure NetApp Files | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/file-storage/moodle-azure-netapp-files |
| Run Oracle Database on Azure VMs with Azure NetApp Files | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/file-storage/oracle-azure-netapp-files |
| Migrate SQL Server to Azure VMs using Azure NetApp Files | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/file-storage/sql-server-azure-netapp-files |
| Implement chain-of-custody forensics workflows on Azure | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/forensics/ |
| Implement Zero Trust web app protection with Azure Firewall and Application Gateway | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/gateway/application-gateway-before-azure-firewall |
| Design network security with Azure Firewall and Application Gateway | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/gateway/firewall-application-gateway |
| Apply GitOps patterns to manage AKS clusters | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/gitops-aks/gitops-blueprint-aks |
| Baseline AKS architecture for Azure Local deployments | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/hybrid/aks-baseline |
| Secure on-premises access to Azure Files via AD DS | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/hybrid/azure-files-on-premises-authentication |
| Design secure hybrid mobile messaging with MFA | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/hybrid/secure-hybrid-messaging-mobile |
| Design secure hybrid web messaging with MFA | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/hybrid/secure-hybrid-messaging-web |
| Extend on-premises AD DS domain into Azure | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/identity/adds-extend-domain |
| Build HA/DR multi-tier web apps on Azure | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/infrastructure/multi-tier-app-disaster-recovery |
| Design secure API Management landing zone | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/integration/app-gateway-internal-api-management-function |
| Integrate systems using message broker and events | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/integration/queues-events |
| Upload IoT files privately to Azure Storage via IoT Hub | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/iot/iot-private-file-upload |
| Migrate IBM z/OS mainframes to Azure with Avanade AMT | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mainframe/avanade-amt-zos-migration |
| Refactor COBOL mainframe apps to Java with CloudFrame Renovate | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mainframe/cloudframe-renovate-mainframe-refactor |
| Deploy IBM Power workloads on Skytap using Azure NetApp Files | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mainframe/deploy-ibm-power-workloads |
| Expose mainframe workloads via REST APIs on Azure | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mainframe/extend-mainframes-rest-apis |
| Refactor general mainframe applications to Azure | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mainframe/general-mainframe-refactor |
| Lift-and-shift HP-UX workloads to Azure with Charon-PAR | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mainframe/hp-ux-stromasys-charon-par |
| Migrate IBM z/OS OLTP workloads to Azure | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mainframe/ibm-zos-online-transaction-processing-azure |
| Rehost IMS DB and TM workloads to Azure VMs with IMSql | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mainframe/imsql-rehost-ims |
| Design Azure integration for IBM MQ mainframe queues | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mainframe/integrate-ibm-message-queues-azure |
| Back up mainframe file and tape data to Azure with Luminex | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mainframe/luminex-mainframe-file-tape-transfer |
| Modernize mainframe workloads using BMC AMI Cloud and Azure Blob Storage | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mainframe/mainframe-modernization-bmc-ami-cloud |
| Design a general mainframe rehosting architecture on Azure | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mainframe/mainframe-rehost-architecture-azure |
| Architect Micro Focus Enterprise Server HA/DR on Azure VMs | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mainframe/micro-focus-server |
| Migrate IBM AIX LPAR workloads to Skytap on Azure | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mainframe/migrate-aix-workloads-to-azure-with-skytap |
| Migrate IBM i workloads to Skytap on Azure with native backup | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mainframe/migrate-ibm-i-series-to-azure-with-skytap |
| Migrate Unisys Dorado mainframes to Azure with Astadia and Micro Focus | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mainframe/migrate-unisys-dorado-mainframe-apps-with-astadia-micro-focus |
| Move mainframe archive data to Azure storage | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mainframe/move-archive-data-mainframes |
| Implement high-volume batch processing on Azure | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mainframe/process-batch-transactions |
| Modernize Adabas & Natural mainframe systems on Azure | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mainframe/refactor-adabas-aks |
| Rehost Software AG Adabas & Natural systems on Azure | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mainframe/rehost-adabas-software-ag |
| Virtualize Unisys ClearPath MCP mainframes on Azure | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mainframe/unisys-clearpath-forward-mainframe-rehost |
| Architect Siemens Teamcenter PLM on Azure | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/manufacturing/teamcenter-baseline |
| Use Azure NetApp Files for Teamcenter PLM storage | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/manufacturing/teamcenter-plm-netapp-files |
| Build real-time monitoring for media telemetry | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/monitoring/monitoring-observable-systems-media |
| Integrate Azure Quantum with classical applications | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/quantum/quantum-computing-integration-with-classical-apps |
| Replatform Kubernetes microservices to Azure Container Apps | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/serverless/microservices-with-container-apps |
| Build microservices on Container Apps with Dapr and KEDA | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/serverless/microservices-with-container-apps-dapr |
| Migrate IBM AIX workloads to Azure Linux | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/unix-migration/migrate-aix-azure-linux |
| Apply blue-green deployment pattern to AKS | https://learn.microsoft.com/en-us/azure/architecture/guide/aks/blue-green-deployment-for-aks |
| Apply big compute architecture style on Azure | https://learn.microsoft.com/en-us/azure/architecture/guide/architecture-styles/big-compute |
| Design big data architectures with Azure services | https://learn.microsoft.com/en-us/azure/architecture/guide/architecture-styles/big-data |
| Implement event-driven architectures on Azure | https://learn.microsoft.com/en-us/azure/architecture/guide/architecture-styles/event-driven |
| Design microservices architecture patterns on Azure | https://learn.microsoft.com/en-us/azure/architecture/guide/architecture-styles/microservices |
| Choose the right Azure container service | https://learn.microsoft.com/en-us/azure/architecture/guide/choose-azure-container-service |
| Choose Azure services for Kafka migration | https://learn.microsoft.com/en-us/azure/architecture/guide/hadoop/apache-kafka-migration |
| Architect ML inference on Azure IoT Edge devices | https://learn.microsoft.com/en-us/azure/architecture/guide/iot/machine-learning-inference-iot-edge |
| Scale Azure IoT Hub solutions to millions of devices | https://learn.microsoft.com/en-us/azure/architecture/guide/iot/scale-iot-solution-azure |
| Design multitenant architectures with Azure IoT Hub | https://learn.microsoft.com/en-us/azure/architecture/guide/multitenant/approaches/iot |
| Implement mission-critical web apps on App Service | https://learn.microsoft.com/en-us/azure/architecture/guide/networking/global-web-applications/mission-critical-app-service |
| Architect mission-critical global content delivery with Azure CDNs | https://learn.microsoft.com/en-us/azure/architecture/guide/networking/global-web-applications/mission-critical-content-delivery |
| Design resilient global HTTP ingress on Azure | https://learn.microsoft.com/en-us/azure/architecture/guide/networking/global-web-applications/mission-critical-global-http-ingress |
| Design global routing redundancy for mission-critical web apps | https://learn.microsoft.com/en-us/azure/architecture/guide/networking/global-web-applications/overview |
| Run SAP NetWeaver on Windows in Azure | https://learn.microsoft.com/en-us/azure/architecture/guide/sap/sap-netweaver |
| Architect SAP S/4HANA on Linux in Azure | https://learn.microsoft.com/en-us/azure/architecture/guide/sap/sap-s4hana |
| Architect SAS Viya and SAS Grid deployments on Azure | https://learn.microsoft.com/en-us/azure/architecture/guide/sas/sas-overview |
| Select the right Azure compute hosting model | https://learn.microsoft.com/en-us/azure/architecture/guide/technology-choices/compute-decision-tree |
| Prepare to choose Azure data stores for workloads | https://learn.microsoft.com/en-us/azure/architecture/guide/technology-choices/data-stores-getting-started |
| Select Azure hybrid hosting and deployment options | https://learn.microsoft.com/en-us/azure/architecture/guide/technology-choices/hybrid-considerations |
| Choose the appropriate Azure storage service | https://learn.microsoft.com/en-us/azure/architecture/guide/technology-choices/storage-options |
| Select an Azure vector search service | https://learn.microsoft.com/en-us/azure/architecture/guide/technology-choices/vector-search |
| Load test IoT/Event Hubs with custom JMeter plugins | https://learn.microsoft.com/en-us/azure/architecture/guide/testing/load-testing/load-testing-with-custom-plugins |
| Design multi-region load balancing on Azure | https://learn.microsoft.com/en-us/azure/architecture/high-availability/reference-architecture-traffic-manager-application-gateway |
| Architect Azure Arc management for hybrid Kubernetes clusters | https://learn.microsoft.com/en-us/azure/architecture/hybrid/arc-hybrid-kubernetes |
| Design Azure Arc-enabled SQL Managed Instance disaster recovery | https://learn.microsoft.com/en-us/azure/architecture/hybrid/arc-sql-managed-instance-disaster-recovery |
| Architect Azure Arc management for on-premises SQL Server | https://learn.microsoft.com/en-us/azure/architecture/hybrid/azure-arc-sql-server |
| Integrate Azure file shares into hybrid AD DS | https://learn.microsoft.com/en-us/azure/architecture/hybrid/azure-file-share |
| Architect enterprise cloud file shares with Azure Files | https://learn.microsoft.com/en-us/azure/architecture/hybrid/azure-files-private |
| Baseline architecture for Azure Local infrastructure design | https://learn.microsoft.com/en-us/azure/architecture/hybrid/azure-local-baseline |
| Design Azure Local storage switchless architecture | https://learn.microsoft.com/en-us/azure/architecture/hybrid/azure-local-switchless |
| Architect Azure Virtual Desktop workloads on Azure Local | https://learn.microsoft.com/en-us/azure/architecture/hybrid/azure-local-workload-virtual-desktop |
| Design a hybrid DNS architecture with Azure | https://learn.microsoft.com/en-us/azure/architecture/hybrid/hybrid-dns-infra |
| Design hybrid file services with Azure File Sync | https://learn.microsoft.com/en-us/azure/architecture/hybrid/hybrid-file-services |
| Architect hybrid performance and availability monitoring | https://learn.microsoft.com/en-us/azure/architecture/hybrid/hybrid-perf-monitoring |
| Architect analytics for automotive test fleet telemetry | https://learn.microsoft.com/en-us/azure/architecture/industries/automotive/automotive-telemetry-analytics |
| Implement subscription vending architecture in Azure | https://learn.microsoft.com/en-us/azure/architecture/landing-zones/subscription-vending |
| Virtualize Unisys ClearPath OS 2200 Enterprise Server on Azure | https://learn.microsoft.com/en-us/azure/architecture/mainframe/virtualization-of-unisys-clearpath-forward-os-2200-enterprise-server-on-azure |
| Design end-to-end microservices architecture on Azure | https://learn.microsoft.com/en-us/azure/architecture/microservices/design/ |
| Design microservice APIs with REST and RPC trade-offs | https://learn.microsoft.com/en-us/azure/architecture/microservices/design/api-design |
| Select Azure compute options for microservices | https://learn.microsoft.com/en-us/azure/architecture/microservices/design/compute-options |
| Select Azure compute options for microservices | https://learn.microsoft.com/en-us/azure/architecture/microservices/design/compute-options |
| Design interservice communication patterns for microservices | https://learn.microsoft.com/en-us/azure/architecture/microservices/design/interservice-communication |
| Apply microservices design patterns on Azure | https://learn.microsoft.com/en-us/azure/architecture/microservices/design/patterns |
| Use domain analysis to define Azure microservices | https://learn.microsoft.com/en-us/azure/architecture/microservices/model/domain-analysis |
| Determine correct microservice boundaries from domain models | https://learn.microsoft.com/en-us/azure/architecture/microservices/model/microservice-boundaries |
| Apply tactical DDD patterns to Azure microservices | https://learn.microsoft.com/en-us/azure/architecture/microservices/model/tactical-ddd |
| Architect cross-tenant private endpoint access to apps | https://learn.microsoft.com/en-us/azure/architecture/networking/guide/cross-tenant-secure-access-private-endpoints |
| Evaluate Kubernetes edge compute options on Azure | https://learn.microsoft.com/en-us/azure/architecture/operator-guides/aks/choose-kubernetes-edge-compute-option |
| Implement network secure ingress with Azure Front Door | https://learn.microsoft.com/en-us/azure/architecture/pattern-implementations/network-secure-ingress |
| Rehost COBOL mainframe applications to Azure with Raincode | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/app-modernization/raincode-reference-architecture |
| Run GPU-accelerated workloads on AKS clusters | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks-gpu/gpu-aks |
| Implement microservices architecture on AKS | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks-microservices/aks-microservices |
| Design advanced AKS microservices architecture | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks-microservices/aks-microservices-advanced |
| Design resilient mission-critical applications on Azure | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks-mission-critical/mission-critical-app-design |
| Choose application platform for mission-critical AKS | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks-mission-critical/mission-critical-app-platform |
| Design data platform for mission-critical Azure apps | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks-mission-critical/mission-critical-data-platform |
| Design mission-critical architectures on Azure | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks-mission-critical/mission-critical-intro |
| Plan networking for mission-critical Azure workloads | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks-mission-critical/mission-critical-networking |
| Run multiregion AKS clusters for high availability | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks-multi-region/aks-multi-cluster |
| Use baseline architecture for AKS clusters | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/baseline-aks |
| Implement ARO landing zone for financial services | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aro/azure-redhat-openshift-financial-services-workloads |
| Implement stream processing pipeline with Azure Databricks | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/data/stream-processing-databricks |
| Implement stream processing pipeline with Azure Stream Analytics | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/data/stream-processing-stream-analytics |
| Implement a secure DMZ-based hybrid network in Azure | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/dmz/secure-vnet-dmz |
| Implement basic enterprise integration on Azure | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/enterprise-integration/basic-enterprise-integration |
| Design ExpressRoute with VPN failover for hybrid connectivity | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/hybrid-networking/expressroute-vpn-failover |
| Choose Azure virtual network peering vs VPN gateways | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/hybrid-networking/virtual-network-peering |
| Deploy IBM Sterling OMS architecture on Azure | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/ibm/deploy-ibm-sterling-oms |
| Create AD DS resource forest in Azure for hybrid | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/identity/adds-forest |
| Extend AD FS-based federation into Azure | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/identity/adfs |
| Integrate on-premises AD with Microsoft Entra ID | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/identity/azure-ad |
| Migrate Unisys MCP workloads to Azure with Avanade AMT | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/migration/unisys-mainframe-migration |
| Run SAP BW/4HANA application tier on Linux VMs with HA | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/sap/run-sap-bw4hana-with-linux-virtual-machines |
| Architect SAP HANA scale-up Linux VMs on Azure | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/sap/run-sap-hana-for-linux-virtual-machines |
| Architect solutions using Event Hubs with Functions | https://learn.microsoft.com/en-us/azure/architecture/serverless/event-hubs-functions/event-hubs-functions |
| Add real-time analytics to Service Bus with Azure Data Explorer | https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/analytics-service-bus |
| Create a modern analytics architecture using Azure Databricks | https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/azure-databricks-modern-analytics-architecture |
| Design AKS-based real-time data streaming solution | https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/data-streaming-scenario |
| Design a DevSecOps IaC pipeline for Azure landing zones | https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/devsecops-infrastructure-as-code |
| Build batch and streaming ETL with Databricks and Delta Lake | https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/ingest-etl-stream-with-adb |
| Analyze IoT telemetry with Azure Data Explorer | https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/iot-azure-data-explorer |
| Replicate and sync mainframe files to Azure | https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/mainframe-azure-file-replication |
| Design automated incident response with Microsoft Sentinel playbooks | https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/microsoft-sentinel-automated-response |
| Plan cross-tenant Azure workload migration strategy | https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/migrate-cloud-workloads-across-security-tenants |
| Build IoT sustainability solutions with Project 15 | https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/project-15-iot-sustainability |
| Design SAP S/4HANA large-instance HA/DR on Azure | https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/sap-s4-hana-on-hli-with-ha-and-dr |
| Automate SAP infrastructure with SUSE on Azure | https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/sap-workload-automation-suse |
| Design a modern data platform for SMBs with Fabric and Databricks | https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/small-medium-modern-data-platform |
| Run Solaris SPARC workloads on Azure with Charon-SSP | https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/solaris-azure |
| Plan high-performance computing architectures on Azure | https://learn.microsoft.com/en-us/azure/architecture/topics/high-performance-computing |
| Implement baseline architecture for Azure VMs | https://learn.microsoft.com/en-us/azure/architecture/virtual-machines/baseline |
| Adapt VM baseline architecture to Azure landing zones | https://learn.microsoft.com/en-us/azure/architecture/virtual-machines/baseline-landing-zone |

### Best Practices
| Topic | URL |
|-------|-----|
| Avoid busy front-end antipattern in Azure apps | https://learn.microsoft.com/en-us/azure/architecture/antipatterns/busy-front-end/ |
| Mitigate chatty I/O antipattern in cloud workloads | https://learn.microsoft.com/en-us/azure/architecture/antipatterns/chatty-io/ |
| Reduce extraneous data fetching in Azure solutions | https://learn.microsoft.com/en-us/azure/architecture/antipatterns/extraneous-fetching/ |
| Prevent improper object instantiation in cloud apps | https://learn.microsoft.com/en-us/azure/architecture/antipatterns/improper-instantiation/ |
| Mitigate no-caching antipattern in Azure workloads | https://learn.microsoft.com/en-us/azure/architecture/antipatterns/no-caching/ |
| Prevent retry storm antipattern in Azure services | https://learn.microsoft.com/en-us/azure/architecture/antipatterns/retry-storm/ |
| Avoid synchronous I/O antipattern in Azure apps | https://learn.microsoft.com/en-us/azure/architecture/antipatterns/synchronous-io/ |
| Preserve HTTP host names behind Azure reverse proxies | https://learn.microsoft.com/en-us/azure/architecture/best-practices/host-name-preservation |
| Apply DR best practices for Azure data platforms | https://learn.microsoft.com/en-us/azure/architecture/data-guide/disaster-recovery/dr-for-azure-data-platform-recommendations |
| Move Azure IoT Hub solutions to production safely | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/iot/iot-move-to-production |
| Plan WSUS deployment for Azure Windows VMs | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/wsus/ |
| Apply high-availability practices for AKS apps | https://learn.microsoft.com/en-us/azure/architecture/guide/aks/aks-high-availability |
| Apply SAP landscape architecture best practices on Azure | https://learn.microsoft.com/en-us/azure/architecture/guide/sap/sap-whole-landscape |
| Design resilient workloads using Azure Spot VMs | https://learn.microsoft.com/en-us/azure/architecture/guide/spot/spot-eviction |
| Continuously validate deployments with Load Testing and Chaos Studio | https://learn.microsoft.com/en-us/azure/architecture/guide/testing/mission-critical-deployment-testing |
| Implement backup and recovery for AKS clusters | https://learn.microsoft.com/en-us/azure/architecture/operator-guides/aks/aks-backup-and-recovery |
| Plan patching and upgrade strategy for AKS | https://learn.microsoft.com/en-us/azure/architecture/operator-guides/aks/aks-upgrade-practices |
| Apply best practices for Linux VMs on Azure | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/n-tier/linux-vm |
| Apply best practices for Windows VMs on Azure | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/n-tier/windows-vm |
| Monitor Azure Functions and Event Hubs topologies | https://learn.microsoft.com/en-us/azure/architecture/serverless/event-hubs-functions/observability |
| Optimize performance and scale for Event Hubs Functions | https://learn.microsoft.com/en-us/azure/architecture/serverless/event-hubs-functions/performance-scale |
| Design resilient Event Hubs-triggered Azure Functions | https://learn.microsoft.com/en-us/azure/architecture/serverless/event-hubs-functions/resilient-design |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Map AWS services and concepts to Azure equivalents | https://learn.microsoft.com/en-us/azure/architecture/aws-professional/ |
| Compare AWS and Azure account and subscription models | https://learn.microsoft.com/en-us/azure/architecture/aws-professional/accounts |
| Compare AWS and Azure compute service offerings | https://learn.microsoft.com/en-us/azure/architecture/aws-professional/compute |
| Compare Azure and AWS data and AI services | https://learn.microsoft.com/en-us/azure/architecture/aws-professional/data-ai |
| Map AWS database services to Azure database options | https://learn.microsoft.com/en-us/azure/architecture/aws-professional/databases |
| Understand AKS for professionals experienced with Amazon EKS | https://learn.microsoft.com/en-us/azure/architecture/aws-professional/eks-to-aks/ |
| Compare and optimize AKS vs EKS Kubernetes costs | https://learn.microsoft.com/en-us/azure/architecture/aws-professional/eks-to-aks/cost-management |
| Compare AWS and Azure messaging and queueing services | https://learn.microsoft.com/en-us/azure/architecture/aws-professional/messaging |
| Compare AWS and Azure networking capabilities | https://learn.microsoft.com/en-us/azure/architecture/aws-professional/networking |
| Compare AWS and Azure regions, zones, and resiliency options | https://learn.microsoft.com/en-us/azure/architecture/aws-professional/regions-zones |
| Compare AWS and Azure resource management approaches | https://learn.microsoft.com/en-us/azure/architecture/aws-professional/resources |
| Compare AWS and Azure identity and access solutions | https://learn.microsoft.com/en-us/azure/architecture/aws-professional/security-identity |
| Compare AWS and Azure storage services and tiers | https://learn.microsoft.com/en-us/azure/architecture/aws-professional/storage |
| Compare Azure batch processing technologies and capabilities | https://learn.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/batch-processing |
| Select an analytical data store in Microsoft Fabric | https://learn.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/fabric-analytical-data-stores |
| Map Google Cloud services to Azure equivalents | https://learn.microsoft.com/en-us/azure/architecture/gcp-professional/services |
| Compare Azure Java application hosting options | https://learn.microsoft.com/en-us/azure/architecture/guide/technology-choices/service-for-java-comparison |
| Compare options to connect on-premises networks to Azure VNets | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/hybrid-networking/ |

### Deployment
| Topic | URL |
|-------|-----|
| Migrate workloads from EKS to AKS clusters | https://learn.microsoft.com/en-us/azure/architecture/aws-professional/eks-to-aks/migrate |
| Automate Microsoft 365 tenant config with Azure DevOps | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/devops/manage-microsoft-365-tenant-configuration-microsoft365dsc-devops |
| Build GitOps deployment pipelines for AKS on Azure Local | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/hybrid/aks-hybrid-azure-local |
| Create AKS CI/CD pipelines with Azure Pipelines | https://learn.microsoft.com/en-us/azure/architecture/guide/aks/aks-cicd-azure-pipelines |
| Deploy and manage Azure Sandbox environments with Terraform | https://learn.microsoft.com/en-us/azure/architecture/guide/azure-sandbox/azure-sandbox |
| Pause Azure deployments with Bicep deployment scripts | https://learn.microsoft.com/en-us/azure/architecture/guide/devops/deployment-scripts-property-check |
| Deploy and automate Azure Governance Visualizer | https://learn.microsoft.com/en-us/azure/architecture/landing-zones/azure-governance-visualizer-accelerator |
| Select and apply Azure landing zone deployment options | https://learn.microsoft.com/en-us/azure/architecture/landing-zones/landing-zone-deploy |
| Design CI/CD pipelines for Azure microservices | https://learn.microsoft.com/en-us/azure/architecture/microservices/ci-cd |
| Build microservices CI/CD to AKS with Azure DevOps | https://learn.microsoft.com/en-us/azure/architecture/microservices/ci-cd-kubernetes |
| Deploy and test mission-critical workloads on Azure | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks-mission-critical/mission-critical-deploy-test |

### Security
| Topic | URL |
|-------|-----|
| Apply governance and policy controls to AKS clusters | https://learn.microsoft.com/en-us/azure/architecture/aws-professional/eks-to-aks/governance |
| Secure AKS API server access and private clusters | https://learn.microsoft.com/en-us/azure/architecture/aws-professional/eks-to-aks/private-clusters |
| Configure workload identity and access for AKS pods | https://learn.microsoft.com/en-us/azure/architecture/aws-professional/eks-to-aks/workload-identity |
| Protect multitenant AKS with Application Gateway WAF | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/aks-agic/aks-agic |
| Securely expose AKS workloads via Azure Front Door | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/aks-front-door/aks-front-door |
| Implement MFA for secure hybrid Exchange client access | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/hybrid/secure-hybrid-messaging-client |
| Manage Azure VM image compliance with DevOps | https://learn.microsoft.com/en-us/azure/architecture/example-scenario/security/virtual-machine-compliance |
| Secure AKS with Azure Firewall in hub-spoke | https://learn.microsoft.com/en-us/azure/architecture/guide/aks/aks-firewall |
| Secure AWS environments using Microsoft security services | https://learn.microsoft.com/en-us/azure/architecture/guide/aws/aws-azure-security-solutions |
| Use IDaaS platforms for Azure application identity | https://learn.microsoft.com/en-us/azure/architecture/guide/design-principles/identity |
| Implement DevSecOps practices for AKS workloads | https://learn.microsoft.com/en-us/azure/architecture/guide/devsecops/devsecops-on-aks |
| Secure inbound and outbound internet connectivity for SAP on Azure | https://learn.microsoft.com/en-us/azure/architecture/guide/sap/sap-internet-inbound-outbound |
| Securely access AKS API server endpoints | https://learn.microsoft.com/en-us/azure/architecture/guide/security/access-azure-kubernetes-service-cluster-api-server |
| Secure AWS accounts using Microsoft Entra identity solutions | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/aws/aws-azure-ad-security |
| Apply security controls to mission-critical AKS workloads | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks-mission-critical/mission-critical-security |
| Secure Azure Functions integrated with Event Hubs | https://learn.microsoft.com/en-us/azure/architecture/serverless/event-hubs-functions/security |
| Build a first security layer with Azure security services | https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/azure-security-build-first-layer-defense |
| Add a second defense layer with Microsoft Defender XDR | https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/microsoft-365-defender-build-second-layer-defense |
| Integrate Azure and Microsoft Defender XDR security services | https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/microsoft-365-defender-security-integrate-azure |
| Apply multilayered security to Azure virtual machines | https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/multilayered-protection-azure-vm |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Assess DR impact for Azure data platform components | https://learn.microsoft.com/en-us/azure/architecture/data-guide/disaster-recovery/dr-for-azure-data-platform-scenario-details |
| Triage and verify AKS cluster health status | https://learn.microsoft.com/en-us/azure/architecture/operator-guides/aks/aks-triage-cluster-health |
| Verify AKS connectivity to container registries | https://learn.microsoft.com/en-us/azure/architecture/operator-guides/aks/aks-triage-container-registry |
| Validate and troubleshoot AKS admission controllers | https://learn.microsoft.com/en-us/azure/architecture/operator-guides/aks/aks-triage-controllers |
| Triage AKS workload deployments and DaemonSets | https://learn.microsoft.com/en-us/azure/architecture/operator-guides/aks/aks-triage-deployment |
| Diagnose and fix AKS node and pod health issues | https://learn.microsoft.com/en-us/azure/architecture/operator-guides/aks/aks-triage-node-health |
| Use top-down triage for AKS cluster issues | https://learn.microsoft.com/en-us/azure/architecture/operator-guides/aks/aks-triage-practices |
| Plan AKS day-2 operations and troubleshooting | https://learn.microsoft.com/en-us/azure/architecture/operator-guides/aks/day-2-operations-guide |
| Troubleshoot networking issues in AKS clusters | https://learn.microsoft.com/en-us/azure/architecture/operator-guides/aks/troubleshoot-network-aks |
| Troubleshoot Azure hybrid VPN gateway connections | https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/hybrid-networking/troubleshoot-vpn |

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
