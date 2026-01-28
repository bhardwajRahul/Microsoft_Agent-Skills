---
name: hdinsight
description: Expert knowledge for Hdinsight development including configuration, integrations & coding patterns, deployment, best practices, troubleshooting, security, architecture & design patterns, comparing x vs. y, and limits & quotas. Use when building, debugging, or optimizing Hdinsight applications.
compatibility: Requires network access. Uses mcp_microsoftdocs:microsoft_docs_fetch or fetch_webpage to retrieve documentation.
---

# Hdinsight Skill

This skill provides expert guidance for Hdinsight development. It combines local quick-reference content with remote documentation fetching capabilities.

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
| Connect Azure HDInsight to on-premises networks via VPN | https://learn.microsoft.com/en-us/azure/hdinsight/connect-on-premises-network |
| Plan HDInsight architecture with Enterprise Security Package | https://learn.microsoft.com/en-us/azure/hdinsight/domain-joined/apache-domain-joined-architecture |
| Design large-scale ETL pipelines with HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-etl-at-scale |
| Design HDInsight architecture for Hadoop migration | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-on-premises-migration-best-practices-architecture |
| Choose and run custom MapReduce approaches on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-run-custom-programs |
| Use Apache Hive as an ETL engine on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-using-apache-hive-as-an-etl-tool |
| Choose backup and replication options for HBase/Phoenix | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/apache-hbase-backup-replication |
| Design HDInsight business continuity architectures | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-business-continuity-architecture |
| Implement highly available HDInsight solution architectures | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-high-availability-case-study |
| Share Azure Data Lake Storage across HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-multiple-clusters-data-lake-store |
| Operationalize HDInsight data pipelines with Oozie | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-operationalize-data-pipeline |
| Plan Azure Virtual Network architecture for HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-plan-virtual-network-deployment |
| Select optimal VM sizes for HDInsight workloads | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-selecting-vm-size |
| Understand Azure HDInsight virtual network architecture and connectivity | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-virtual-network-architecture |
| Apply Kafka MirrorMaker 2.0 patterns on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/kafka/kafka-mirrormaker-2-0-guide |
| Use HDInsight IO Cache to speed Spark workloads | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-improve-performance-iocache |

### Best Practices
| Topic | URL |
|-------|-----|
| Use Azure Monitor logs for HDInsight availability | https://learn.microsoft.com/en-us/azure/hdinsight/cluster-availability-monitor-logs |
| Apply cluster management best practices in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/cluster-management-best-practices |
| Apply general best practices for HDInsight Enterprise Security Package | https://learn.microsoft.com/en-us/azure/hdinsight/domain-joined/general-guidelines |
| Create Java UDFs for Apache Hive on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-hive-java-udf |
| Execute data migration to Azure HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-on-premises-migration-best-practices-data-migration |
| Manage HDInsight infrastructure for Hadoop migration | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-on-premises-migration-best-practices-infrastructure |
| Plan HDInsight storage for Hadoop migration | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-on-premises-migration-best-practices-storage |
| Optimize HBase write performance with Accelerated Writes | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/apache-hbase-accelerated-writes |
| Apply HDInsight HBase performance advisor recommendations | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/apache-hbase-advisor |
| Tune Apache Phoenix performance on Azure HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/apache-hbase-phoenix-performance |
| Tune Apache HBase performance on Azure HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/troubleshoot-hbase-performance-issues |
| Tune HDInsight clusters using Ambari configuration | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-changing-configs-via-ambari |
| Monitor HDInsight cluster availability with Ambari | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-cluster-availability |
| Apply Linux-specific tips for Hadoop on Azure HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-linux-information |
| Optimize Apache Hive query performance on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-optimize-hive-query |
| Monitor and optimize HDInsight cluster performance | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-key-scenarios-to-monitor |
| Configure OS patching and updates for HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-os-patching |
| Apply pre-creation best practices for Azure HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-overview-before-you-start |
| Manually scale HDInsight clusters for workload elasticity | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-scaling-best-practices |
| Migrate Azure HDInsight clusters to newer versions | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-upgrade-cluster |
| Optimize Hive queries through HDInsight gateway best practices | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/gateway-best-practices |
| Size HDInsight Interactive Query (LLAP) clusters effectively | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/hive-llap-sizing-guide |
| Apply schedule-based autoscale best practices for LLAP | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/llap-schedule-based-autoscale-best-practices |
| Configure Kafka partition replicas for high availability | https://learn.microsoft.com/en-us/azure/hdinsight/kafka/apache-kafka-high-availability |
| Tune Kafka on HDInsight for performance | https://learn.microsoft.com/en-us/azure/hdinsight/kafka/apache-kafka-performance-tuning |
| Migrate HDInsight Log Analytics data to new tables | https://learn.microsoft.com/en-us/azure/hdinsight/log-analytics-migration |
| Optimize HDInsight HBase performance via Ambari settings | https://learn.microsoft.com/en-us/azure/hdinsight/optimize-hbase-ambari |
| Optimize HDInsight Hive performance with Ambari configuration | https://learn.microsoft.com/en-us/azure/hdinsight/optimize-hive-ambari |
| Optimize Apache Spark job performance on Azure HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-perf |
| Customize Python environments for HDInsight Jupyter | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-python-package-installation |
| Achieve exactly-once processing in Spark Streaming | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-streaming-exactly-once |
| Configure high availability for Spark Streaming on YARN | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-streaming-high-availability |
| Optimize data processing operations for Spark on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/spark/optimize-data-processing |
| Optimize HDInsight Spark data storage layout | https://learn.microsoft.com/en-us/azure/hdinsight/spark/optimize-data-storage |
| Tune memory usage for Spark on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/spark/optimize-memory-usage |
| Safely manage JAR dependencies on HDInsight Spark | https://learn.microsoft.com/en-us/azure/hdinsight/spark/safely-manage-jar-dependency |
| Apply Apache Spark usage guidelines on Azure HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/spark/spark-best-practices |
| Use SparkCruise to optimize HDInsight Spark queries | https://learn.microsoft.com/en-us/azure/hdinsight/spark/spark-cruise |

### Comparing X vs. Y
| Topic | URL |
|-------|-----|
| Compare Azure storage options for HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-compare-storage-options |

### Configuration
| Topic | URL |
|-------|-----|
| Configure Ambari Web UI auto-logout timeout in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/ambari-web-ui-auto-logout |
| Configure Apache Ambari roles in HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/apache-ambari-usage |
| Retrieve HDInsight cluster node hostnames and FQDNs | https://learn.microsoft.com/en-us/azure/hdinsight/find-host-name |
| Configure HBase cluster replication across Azure VNets | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/apache-hbase-replication |
| Check open-source component versions for Azure HDInsight 4.0 | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-40-component-versioning |
| Check open-source component versions for Azure HDInsight 5.x | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-5x-component-versioning |
| Scale HiveServer2 using HDInsight edge nodes | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-apps-install-hiveserver2 |
| Add and use empty edge nodes in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-apps-use-edge-node |
| Configure HDInsight Autoscale policies and limits | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-autoscale-clusters |
| Review bundled open-source components and versions in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-component-versioning |
| Configure Spark & Hive Tools settings for HDInsight in VS Code | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-config-for-vscode |
| Create and configure VNets, NSGs, and DNS for HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-create-virtual-network |
| Configure custom Ambari database for HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-custom-ambari-db |
| Preload Apache Hive libraries on HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-add-hive-libraries |
| Programmatically configure HDInsight clusters with bootstrap | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-customize-cluster-bootstrap |
| Connect to Azure HDInsight via SSH | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-linux-use-ssh-unix |
| Enable Azure Monitor logs for HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-oms-log-analytics-tutorial |
| Reference of ports for Hadoop services on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-port-settings-for-services |
| Develop script actions to configure HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-script-actions-linux |
| Configure SSH tunneling to access HDInsight web UIs | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-linux-ambari-ssh-tunnel |
| Rotate and update Azure Storage access keys in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-rotate-storage-keys |
| Custom-tune HDInsight Autoscale advanced settings | https://learn.microsoft.com/en-us/azure/hdinsight/how-to-custom-configure-hdinsight-autoscale |
| Configure Apache Hive replication on HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/apache-hive-replication |
| Access and configure Grafana dashboards on HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/hdinsight-grafana |
| Move HDInsight Hive default metastore to external DB | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/hive-default-metastore-export-import |
| Configure Hive LLAP workload management on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/hive-workload-management |
| Use Hive LLAP Workload Management commands in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/workload-management-commands |
| Enable automatic topic creation in Kafka on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/kafka/apache-kafka-auto-create-topics |
| Configure Azure Monitor logs for HDInsight Kafka | https://learn.microsoft.com/en-us/azure/hdinsight/kafka/apache-kafka-log-analytics-operations-management |
| Configure VNet peering for Kafka and VM connectivity | https://learn.microsoft.com/en-us/azure/hdinsight/kafka/connect-kafka-cluster-with-vm-in-different-vnet |
| Reference of monitoring metrics and logs for HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/monitor-hdinsight-reference |
| Tune HDInsight Pig properties via Ambari configuration | https://learn.microsoft.com/en-us/azure/hdinsight/optimize-pig-ambari |
| Configure selective logging for AMA on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/selective-logging-analysis |
| Configure selective logging for HDInsight with script actions | https://learn.microsoft.com/en-us/azure/hdinsight/selective-logging-analysis-azure-logs |
| Set up PySpark interactive environment in VS Code | https://learn.microsoft.com/en-us/azure/hdinsight/set-up-pyspark-interactive-environment |
| Use HDInsight Spark Jupyter kernels effectively | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-jupyter-notebook-kernels |
| Configure Spark dependency management on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-manage-dependencies |
| Tune HDInsight Spark cluster resource settings | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-resource-manager |
| Configure Apache Spark settings on Azure HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-settings |
| Configure HDInsight Spark clusters for throughput | https://learn.microsoft.com/en-us/azure/hdinsight/spark/optimize-cluster-configuration |
| Transfer files to HDInsight using SCP and SSH | https://learn.microsoft.com/en-us/azure/hdinsight/use-scp |

### Deployment
| Topic | URL |
|-------|-----|
| Migrate HDInsight monitoring to Azure Monitor Agent | https://learn.microsoft.com/en-us/azure/hdinsight/azure-monitor-agent |
| Migrate HBase cluster to HDInsight 5.1 | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/apache-hbase-migrate-hdinsight-5-1 |
| Migrate HBase to HDInsight 5.1 with new storage | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/apache-hbase-migrate-hdinsight-5-1-new-storage-account |
| Upgrade HBase cluster to newer HDInsight version | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/apache-hbase-migrate-new-version |
| Upgrade HBase to new version and storage account | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/apache-hbase-migrate-new-version-new-storage-account |
| Deploy HDInsight clusters using ARM templates | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-create-linux-clusters-arm-templates |
| Create HDInsight clusters using Azure CLI commands | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-create-linux-clusters-azure-cli |
| Provision HDInsight clusters with Azure PowerShell | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-create-linux-clusters-azure-powershell |
| Create HDInsight clusters via Azure REST API templates | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-create-linux-clusters-curl-rest |
| Deploy Azure HDInsight clusters using Availability Zones | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-use-availability-zones |
| Migrate Kafka workloads from HDInsight 4.0 to 5.1 | https://learn.microsoft.com/en-us/azure/hdinsight/kafka/migrate-5-1-versions |
| Migrate Kafka workloads from HDInsight 3.6 to 4.0 | https://learn.microsoft.com/en-us/azure/hdinsight/kafka/migrate-versions |
| Transition HDInsight clusters to Standard Load Balancer | https://learn.microsoft.com/en-us/azure/hdinsight/load-balancer-migration-guidelines |
| Provision and delete HDInsight clusters with Automation runbooks | https://learn.microsoft.com/en-us/azure/hdinsight/manage-clusters-runbooks |

### Integrations & Coding Patterns
| Topic | URL |
|-------|-----|
| Configure Ambari email alerts in HDInsight using SendGrid | https://learn.microsoft.com/en-us/azure/hdinsight/apache-ambari-email |
| Stream from Kafka to Azure Cosmos DB with Spark | https://learn.microsoft.com/en-us/azure/hdinsight/apache-kafka-spark-structured-streaming-cosmosdb |
| Use Azure CLI script samples for common HDInsight tasks | https://learn.microsoft.com/en-us/azure/hdinsight/azure-cli-samples |
| Query HDInsight Hive from Excel using ODBC | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-connect-excel-hive-odbc-driver |
| Connect Excel to HDInsight data with Power Query | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-connect-excel-power-query |
| Run Hive queries on HDInsight via JDBC | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-connect-hive-jdbc-driver |
| Connect Power BI to HDInsight Hive via ODBC | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-connect-hive-power-bi |
| Develop and deploy Java MapReduce on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-develop-deploy-java-mapreduce-linux |
| Implement C# MapReduce jobs on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-dotnet-csharp-mapreduce-streaming |
| Use C# UDFs with Hive and Pig on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-hive-pig-udf-dotnet-csharp |
| Build Mahout recommendation engine on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-mahout-linux-mac |
| Run Hive queries using Ambari Hive View in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-use-hive-ambari-view |
| Execute Hive queries via Beeline over SSH in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-use-hive-beeline |
| Submit Hive queries via WebHCat REST API using Curl | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-use-hive-curl |
| Submit Hive jobs with the HDInsight .NET SDK | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-use-hive-dotnet-sdk |
| Run Hive queries on HDInsight using Azure PowerShell | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-use-hive-powershell |
| Use Visual Studio Data Lake tools to run Hive on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-use-hive-visual-studio |
| Submit Sqoop jobs to HDInsight using Curl and WebHCat | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-use-sqoop-curl |
| Run Sqoop jobs with HDInsight .NET SDK | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-use-sqoop-dotnet-sdk |
| Use Sqoop on HDInsight via SSH for SQL integration | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-use-sqoop-mac-linux |
| Run Sqoop jobs on HDInsight using PowerShell | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-use-sqoop-powershell |
| Use Visual Studio Data Lake Tools with HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-visual-studio-tools-get-started |
| Connect to HiveServer2 with Beeline on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/connect-install-beeline |
| Run Sqoop jobs between HDInsight and Azure SQL | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/hdinsight-use-sqoop |
| Implement Python UDFs for Hive and Pig on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/python-udf-hdinsight |
| Process JSON data with Apache Hive on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/using-json-in-hive |
| Build and run a Java HBase client on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/apache-hbase-build-java-maven-linux |
| Bulk load data into Phoenix using psql on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/apache-hbase-phoenix-psql |
| Run Apache Phoenix SQL via Zeppelin on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/apache-hbase-phoenix-zeppelin |
| Use Apache Phoenix and SQLLine with HDInsight HBase | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/apache-hbase-query-with-phoenix |
| Use the .NET REST SDK with HDInsight HBase | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/apache-hbase-rest-sdk |
| Use Phoenix Query Server REST SDK on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/apache-hbase-using-phoenix-query-server-rest-sdk |
| Repair HBase clusters using the HBCK2 tool | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/how-to-use-hbck2-tool |
| Manage Azure HDInsight clusters using Azure CLI commands | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-administer-use-command-line |
| Administer Azure HDInsight clusters with .NET SDK | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-administer-use-dotnet-sdk |
| Automate Azure HDInsight cluster management with PowerShell | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-administer-use-powershell |
| Process X (Twitter) data with Hive on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-analyze-twitter-data-linux |
| Stream data between Kafka and Spark on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-apache-spark-with-kafka |
| Install custom Hadoop applications on Azure HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-apps-install-custom-applications |
| Use Spark & Hive Tools for VS Code with HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-for-vscode |
| Use the Azure HDInsight Go SDK with Hadoop clusters | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-go-sdk-overview |
| Attach additional Azure Storage accounts to existing HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-add-storage |
| Install and access Hue on HDInsight Hadoop clusters | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-hue-linux |
| Manage HDInsight Hadoop clusters using Ambari REST API | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-manage-ambari-rest-api |
| Leverage HDInsight .NET SDK sample code for common tasks | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-sdk-dotnet-samples |
| Use HDInsight Java SDK sample code for cluster operations | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-sdk-java-samples |
| Apply HDInsight Python SDK samples for managing clusters | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-sdk-python-samples |
| Upload and access HDInsight job data in Azure storage | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-upload-data |
| Define and run Oozie workflows on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-use-oozie-linux-mac |
| Use Spark HBase Connector on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-using-spark-query-hbase |
| Manage Entra ID HDInsight clusters via Azure REST API | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-with-entra-authentication/manage-entra-id-enabled-cluster-with-rest-api |
| Manage Entra-enabled HDInsight Hadoop clusters with .NET SDK | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-with-entra-authentication/manage-hadoop-cluster-dot-net-sdk |
| Execute Hive queries on Entra HDInsight with PowerShell | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-with-entra-authentication/run-apache-hive-queries-using-powershell-on-entra-enabled-hdinsight-cluster |
| Run Hive queries on HDInsight using the REST API | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-with-entra-authentication/run-apache-hive-queries-using-rest-api |
| Execute Hive queries on Entra HDInsight with .NET SDK | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-with-entra-authentication/run-hive-queries-using-dot-net-sdk |
| Run MapReduce jobs on Entra HDInsight using .NET SDK | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-with-entra-authentication/run-map-reduce-jobs-dot-net-sdk |
| Run MapReduce jobs on Entra HDInsight using PowerShell | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-with-entra-authentication/run-map-reduce-jobs-entra-id-enabled-using-powershell |
| Submit MapReduce jobs to Entra HDInsight via REST API | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-with-entra-authentication/run-map-reduce-rest-jobs |
| Submit Spark jobs to Entra HDInsight via Livy REST API | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-with-entra-authentication/run-spark-jobs-using-rest-api |
| Visualize HDInsight Interactive Query data with Power BI | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/apache-hadoop-connect-hive-power-bi-directquery |
| Query HDInsight Hive using Microsoft ODBC driver and PowerShell | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/apache-hive-query-odbc-driver-powershell |
| Integrate Spark and Hive using Hive Warehouse Connector | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/apache-hive-warehouse-connector |
| Use Spark operations supported by Hive Warehouse Connector | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/apache-hive-warehouse-connector-operations |
| Access Hive tables from Zeppelin via HWC and Livy | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/apache-hive-warehouse-connector-zeppelin |
| Migrate HDInsight Hive tables across storage accounts | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/hive-migration-across-storage-accounts |
| Use Hive Warehouse Connector APIs with Spark | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/hive-warehouse-connector-apis |
| Use Hive Warehouse Connector 2.x APIs on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/hive-warehouse-connector-v2-apis |
| Configure VPN and VNet connectivity for HDInsight Kafka | https://learn.microsoft.com/en-us/azure/hdinsight/kafka/apache-kafka-connect-vpn-gateway |
| Integrate Kafka on HDInsight with Azure IoT Hub | https://learn.microsoft.com/en-us/azure/hdinsight/kafka/apache-kafka-connector-iot-hub |
| Connect HDInsight Kafka to client VM in different VNet | https://learn.microsoft.com/en-us/azure/hdinsight/kafka/connect-kafka-with-vnet |
| Use Kafka REST proxy on HDInsight with HTTPS clients | https://learn.microsoft.com/en-us/azure/hdinsight/kafka/rest-proxy |
| Use MSI-based OAuth access to Azure services from HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/msi-support-to-access-azure-services |
| Connect Synapse Spark to HDInsight external Hive Metastore | https://learn.microsoft.com/en-us/azure/hdinsight/share-hive-metastore-with-synapse |
| Analyze Application Insights telemetry with HDInsight Spark | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-analyze-application-insight-logs |
| Connect HDInsight Spark to Azure SQL Database | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-connect-to-sql-database |
| Build HDInsight Spark Scala apps with Eclipse | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-eclipse-tool-plugin |
| Develop and submit Spark apps via IntelliJ toolkit | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-intellij-tool-plugin |
| Remotely debug HDInsight Spark apps with IntelliJ | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-intellij-tool-plugin-debug-jobs-remotely |
| Install Jupyter locally and connect to HDInsight Spark | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-jupyter-notebook-install-locally |
| Configure Jupyter on HDInsight to use Maven packages | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-jupyter-notebook-use-external-packages |
| Submit Spark jobs to HDInsight via Livy REST | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-livy-rest-interface |
| Integrate Microsoft Cognitive Toolkit with HDInsight Spark | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-microsoft-cognitive-toolkit |
| Run Azure AutoML workloads on HDInsight Spark | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-run-machine-learning-automl |
| Run interactive Spark shells on HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-shell |
| Run Spark jobs with Zeppelin on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-zeppelin-notebook |

### Limits & Quotas
| Topic | URL |
|-------|-----|
| Configure HDInsight log types, sizes, and retention policies | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-log-management |
| Allowlist Azure HDInsight management IP address ranges | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-management-ip-addresses |
| Use supported node configurations for HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-supported-node-configuration |
| Use external metastores and understand HDInsight default metastore limits | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-use-external-metadata-stores |
| Scale Kafka on HDInsight with managed disk limits | https://learn.microsoft.com/en-us/azure/hdinsight/kafka/apache-kafka-scalability |
| Request and manage HDInsight CPU core quota increases | https://learn.microsoft.com/en-us/azure/hdinsight/quota-increase-request |

### Security
| Topic | URL |
|-------|-----|
| Configure managed identity access to Blob storage for HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/configure-azure-blob-storage |
| Control inbound and outbound traffic for HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/control-network-traffic |
| Configure double encryption at rest for HDInsight disks | https://learn.microsoft.com/en-us/azure/hdinsight/disk-encryption |
| Configure HDInsight clusters with Microsoft Entra Domain Services | https://learn.microsoft.com/en-us/azure/hdinsight/domain-joined/apache-domain-joined-configure-using-azure-adds |
| Create and configure HDInsight Enterprise Security Package clusters | https://learn.microsoft.com/en-us/azure/hdinsight/domain-joined/apache-domain-joined-create-configure-enterprise-security-cluster |
| Manage users, roles, and security for HDInsight ESP clusters | https://learn.microsoft.com/en-us/azure/hdinsight/domain-joined/apache-domain-joined-manage |
| Configure Apache Ranger policies for HBase in HDInsight ESP | https://learn.microsoft.com/en-us/azure/hdinsight/domain-joined/apache-domain-joined-run-hbase |
| Configure Apache Ranger Hive policies in HDInsight ESP | https://learn.microsoft.com/en-us/azure/hdinsight/domain-joined/apache-domain-joined-run-hive |
| Configure Apache Ranger policies for Kafka in HDInsight ESP | https://learn.microsoft.com/en-us/azure/hdinsight/domain-joined/apache-domain-joined-run-kafka |
| Implement encryption in transit for Azure HDInsight nodes | https://learn.microsoft.com/en-us/azure/hdinsight/domain-joined/encryption-in-transit |
| Secure Apache Oozie workflows with HDInsight Enterprise Security Package | https://learn.microsoft.com/en-us/azure/hdinsight/domain-joined/hdinsight-use-oozie-domain-joined-clusters |
| Set up Azure HDInsight ID Broker for modern auth | https://learn.microsoft.com/en-us/azure/hdinsight/domain-joined/identity-broker |
| Configure LDAP sync for Ranger and Ambari in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/domain-joined/ldap-sync |
| Manage SSH access for Microsoft Entra domain accounts in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/domain-joined/ssh-domain-accounts |
| Enable Private Link for HDInsight Kafka REST Proxy | https://learn.microsoft.com/en-us/azure/hdinsight/enable-private-link-on-kafka-rest-proxy-hdi-cluster |
| Configure Enterprise Security Package and AD integration for HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/enterprise-security-package |
| Apply security and DevOps practices to HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-hadoop-on-premises-migration-best-practices-security-devops |
| Configure Ambari Views authorization in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-authorize-users-to-ambari |
| Implement non-interactive .NET auth for HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-create-non-interactive-authentication-dotnet-applications |
| Create HDInsight clusters with secure transfer–enabled storage | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-create-linux-clusters-with-secure-transfer-storage |
| Configure managed identities for Azure HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-managed-identities |
| Migrate HDInsight cluster configs to granular RBAC | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-migrate-granular-access-cluster-configurations |
| Configure Azure HDInsight Private Link connectivity | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-private-link |
| Upgrade Apache Ranger on Azure HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-ranger-5-1-migration |
| Restrict outbound network traffic from Azure HDInsight via Azure Firewall | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-restrict-outbound-traffic |
| Restrict public connectivity and secure HDInsight network access | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-restrict-public-connectivity |
| Use HDInsight NSG service tags for cluster access | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-service-tags |
| Restrict HDInsight storage access with SAS | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-storage-sharedaccesssignature-permissions |
| Synchronize Microsoft Entra users to Azure HDInsight ESP clusters | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-sync-aad-users-to-cluster |
| Create Entra ID authenticated Azure HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-with-entra-authentication/create-clusters-with-entra |
| Configure Entra ID HDInsight clusters with ARM templates | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-with-entra-authentication/manage-entra-id-enabled-azure-hdinsight-clusters-with-arm-templates |
| Configure security options for Hive in HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/hdinsight-security-options-for-hive |
| Set up TLS and client auth for ESP HDInsight Kafka | https://learn.microsoft.com/en-us/azure/hdinsight/kafka/apache-esp-kafka-ssl-encryption-authentication |
| Configure TLS encryption and client auth for HDInsight Kafka | https://learn.microsoft.com/en-us/azure/hdinsight/kafka/apache-kafka-ssl-encryption-authentication |
| Secure Spark–Kafka streaming across HDInsight VNets | https://learn.microsoft.com/en-us/azure/hdinsight/kafka/secure-spark-kafka-streaming-integration-scenario |
| Configure network virtual appliances with HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/network-virtual-appliance |
| Use Data Lake Storage Gen2 securely with HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/overview-data-lake-storage-gen2 |
| Apply built-in Azure Policy definitions for HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/policy-reference |
| Configure HDInsight service endpoint policies for VNets | https://learn.microsoft.com/en-us/azure/hdinsight/service-endpoint-policies |
| Configure Apache Ranger policies for Spark SQL in HDInsight ESP | https://learn.microsoft.com/en-us/azure/hdinsight/spark/ranger-policies-for-spark |
| Configure TLS versions for Azure HDInsight gateways | https://learn.microsoft.com/en-us/azure/hdinsight/transport-layer-security |
| Configure managed identity auth to SQL from HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/use-managed-identity-for-sql-database-authentication-in-azure-hdinsight |

### Troubleshooting
| Topic | URL |
|-------|-----|
| Resolve reliability issues on older HDInsight images | https://learn.microsoft.com/en-us/azure/hdinsight/cluster-reliability-issues |
| Fix HDInsight ARM template component version validation errors | https://learn.microsoft.com/en-us/azure/hdinsight/component-version-validation-error-arm-templates |
| Resolve Azure HDInsight cluster creation errors | https://learn.microsoft.com/en-us/azure/hdinsight/create-cluster-error-dictionary |
| Troubleshoot authentication issues in HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/domain-joined/domain-joined-authentication-issues |
| Run sample script to resolve HDInsight DomainNotFound | https://learn.microsoft.com/en-us/azure/hdinsight/domain-joined/sample-script |
| Fix DomainNotFound errors during HDInsight cluster creation | https://learn.microsoft.com/en-us/azure/hdinsight/domain-joined/troubleshoot-domainnotfound |
| Fix Apache Ambari directory alerts in Azure HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-ambari-troubleshoot-directory-alerts |
| Fix down hosts and services shown in Ambari on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-ambari-troubleshoot-down-hosts-services |
| Resolve Apache Ambari UI 502 errors in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-ambari-troubleshoot-fivezerotwo-error |
| Diagnose Apache Ambari heartbeat issues in Azure HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-ambari-troubleshoot-heartbeat-issues |
| Troubleshoot Ambari Metrics Collector issues in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-ambari-troubleshoot-metricservice-issues |
| Resolve Apache Ambari stale alerts in Azure HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/apache-ambari-troubleshoot-stale-alerts |
| Fix local HDFS safe mode issues on HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/hdinsight-hdfs-troubleshoot-safe-mode |
| Fix HDInsight cluster creation failures | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/hdinsight-troubleshoot-cluster-creation-fails |
| Convert service principal certificates to base-64 for HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/hdinsight-troubleshoot-converting-service-principal-certificate |
| Resolve Data Lake Storage file access issues in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/hdinsight-troubleshoot-data-lake-files |
| Resolve InvalidNetworkSecurityGroupSecurityRules for HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/hdinsight-troubleshoot-invalidnetworksecuritygroupsecurityrules-cluster-creation-fails |
| Resolve HDInsight node disk space issues | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/hdinsight-troubleshoot-out-disk-space |
| Diagnose Watchdog BUG soft lockup CPU in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/hdinsight-troubleshoot-soft-lockup-cpu |
| Resolve node addition failures in Azure HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/hdinsight-troubleshoot-unable-add-nodes |
| Troubleshoot login failures to Azure HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/hdinsight-troubleshoot-unable-log-in-cluster |
| Troubleshoot and resolve HDInsight disk space issues | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/troubleshoot-disk-space |
| Fix InvalidNetworkConfigurationErrorCode during HDInsight cluster creation | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/troubleshoot-invalidnetworkconfigurationerrorcode-cluster-creation-fails |
| Fix Key Vault access loss on disk-encrypted HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/troubleshoot-lost-key-vault-access |
| Resolve port conflicts when starting services in Azure HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/troubleshoot-port-conflict |
| Fix 'account does not support http' storage errors in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/troubleshoot-wasbs-storage-exception |
| Fix invalid BCFile errors when reading YARN logs in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hadoop/troubleshoot-yarn-log-invalid-bcfile |
| Resolve BindException 'Address already in use' on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/hbase-troubleshoot-bindexception-address-use |
| Fix HBase hbck inconsistency issues on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/hbase-troubleshoot-hbase-hbck-inconsistencies |
| Troubleshoot pegged CPU on HBase region servers | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/hbase-troubleshoot-pegged-cpu-region-server |
| Resolve Apache Phoenix connectivity issues on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/hbase-troubleshoot-phoenix-connectivity |
| Fix missing data in Phoenix views after HDP upgrade | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/hbase-troubleshoot-phoenix-no-data |
| Fix HBase REST service not responding on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/hbase-troubleshoot-rest-not-spending |
| Troubleshoot HBase Master startup failures on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/hbase-troubleshoot-start-fails |
| Resolve storage exceptions after connection reset in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/hbase-troubleshoot-storage-exception-reset |
| Resolve 'hbase hbck' timeout issues on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/hbase-troubleshoot-timeouts-hbase-hbck |
| Fix unassigned regions and region server issues in HBase | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/hbase-troubleshoot-unassigned-regions |
| Fix HBase TTL data retention issues on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/troubleshoot-data-retention-issues-expired-data |
| Troubleshoot HBase REST API issues on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hbase/troubleshoot-rest-api |
| Access and interpret YARN application logs on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-access-yarn-app-logs-linux |
| Enable and collect Hadoop heap dumps on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-collect-debug-heap-dump-linux |
| Resolve Hive out-of-memory errors on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-hive-out-of-memory-error-oom |
| Resolve Hadoop stack trace errors on Azure HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-stack-trace-error-messages |
| Diagnose and fix common WebHCat errors on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-templeton-webhcat-debug-errors |
| Known issues and troubleshooting for Azure HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-known-issues |
| Resolve Ambari access failures after certificate rotation | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-known-issues-ambari-access-certificate-issue |
| Work around Ambari user switch issue in HDInsight 5.1 | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-known-issues-ambari-users-cache |
| Fix HDInsight headnode unresponsive state from /tmp leak | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-known-issues-cluster-head-node-unresponsive |
| Mitigate conda version regression in HDInsight 5.1 | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-known-issues-conda-version-regression |
| Resolve Ranger-based ESP cluster creation failures in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-known-issues-ranger-cluster-create-failure |
| Troubleshoot slow or failing jobs on Azure HDInsight clusters | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-troubleshoot-failed-cluster |
| Navigate HDInsight troubleshooting guides by service | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-troubleshoot-guide |
| Troubleshoot HDFS issues in Azure HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-troubleshoot-hdfs |
| Troubleshoot common Apache Hive issues on Azure HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-troubleshoot-hive |
| Troubleshoot Apache Hadoop YARN issues in Azure HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-troubleshoot-yarn |
| Diagnose missing Hive error messages in Ambari Hive View | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/interactive-query-troubleshoot-error-message-hive-view |
| Resolve Hive log disk space issues on HDInsight head nodes | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/interactive-query-troubleshoot-hive-logs-diskspace-full-headnodes |
| Resolve Hive View inaccessibility from Zookeeper issues in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/interactive-query-troubleshoot-inaccessible-hive-view |
| Resolve Hive join OutOfMemory GC overhead errors in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/interactive-query-troubleshoot-outofmemory-overhead-exceeded |
| Fix permission denied errors when creating Hive tables on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/interactive-query-troubleshoot-permission-error-create-table |
| Fix poor performance in Hive LLAP queries on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/interactive-query-troubleshoot-query-performance |
| Diagnose and resolve slow reducers in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/interactive-query-troubleshoot-slow-reducer |
| Troubleshoot Apache Tez application hangs on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/interactive-query-troubleshoot-tez-hangs |
| Fix slow or failing Ambari Tez View in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/interactive-query-troubleshoot-tez-view-slow |
| Resolve Hive View query result timeouts on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/interactive-query-troubleshoot-view-time-out |
| Fix Zeppelin Hive JDBC interpreter URL errors in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/interactive-query-troubleshoot-zookeeperhiveclientexception-hiveserver-configs |
| Fix exceptions when running Hive queries via Ambari Hive View | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/troubleshoot-gateway-timeout |
| Troubleshoot Hive LLAP Workload Management issues in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/interactive-query/troubleshoot-workload-management-issues |
| Resolve HDInsight Kafka broker startup failures from full disks | https://learn.microsoft.com/en-us/azure/hdinsight/kafka/kafka-troubleshoot-full-disk |
| Fix HDInsight Kafka fault domain region errors | https://learn.microsoft.com/en-us/azure/hdinsight/kafka/kafka-troubleshoot-insufficient-domains |
| Debug Spark jobs using HDInsight History Server | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-azure-spark-history-server |
| Debug Spark job failures with IntelliJ HDInsight tools | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-intellij-tool-failure-debug |
| Known issues and workarounds for HDInsight Spark clusters | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-known-issues |
| Address Spark Streaming apps stopping after 24 days on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-troubleshoot-application-stops |
| Fix Jupyter 404 Blocking Cross Origin in HDInsight Spark | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-troubleshoot-blocking-cross-origin |
| Troubleshoot RequestBodyTooLarge in HDInsight Spark streaming | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-troubleshoot-event-log-requestbodytoolarge |
| Fix IllegalArgumentException in HDInsight Spark activities | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-troubleshoot-illegalargumentexception |
| Resolve InvalidClassException version mismatch in HDInsight Spark | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-troubleshoot-job-fails-invalidclassexception |
| Fix NoClassDefFoundError in HDInsight Spark-Kafka jobs | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-troubleshoot-job-fails-noclassdeffounderror |
| Improve HDInsight Spark performance with many storage files | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-troubleshoot-job-slowness-container |
| Resolve OutOfMemoryError in HDInsight Spark jobs | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-troubleshoot-outofmemory |
| Resolve RpcTimeoutException and 502 errors in HDInsight Spark Thrift | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-troubleshoot-rpctimeoutexception |
| Resolve large JDBC/ODBC downloads with Thrift on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-troubleshoot-sparkexception-kryo-serialization-failed |
| Common Apache Spark issues and fixes on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/spark/apache-troubleshoot-spark |
| Debug WASB file operations and logging in HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/spark/troubleshoot-debug-wasb |
| Fix issues creating Jupyter notebooks on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/spark/troubleshoot-jupyter-notebook-convert |
| Troubleshoot Apache Oozie workflows on HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/troubleshoot-oozie |
| Troubleshoot HDInsight resource creation and capacity failures | https://learn.microsoft.com/en-us/azure/hdinsight/troubleshoot-resource-creation-fails |
| Troubleshoot script action failures in Azure HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/troubleshoot-script-action |
| Work around Sqoop import/export failures on ESP HDInsight | https://learn.microsoft.com/en-us/azure/hdinsight/troubleshoot-sqoop |

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
