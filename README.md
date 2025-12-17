# Azure Tool List

A curated list of free and open-source tools for working with Microsoft Azure. This includes official Microsoft tools, community-built tools, and third-party utilities.

## Table of Contents

- [Command Line Tools](#command-line-tools)
- [Infrastructure as Code (IaC)](#infrastructure-as-code-iac)
- [Kubernetes & Container Tools](#kubernetes--container-tools)
- [Monitoring & Observability](#monitoring--observability)
- [Security & Compliance](#security--compliance)
- [Development Tools](#development-tools)
- [Data & Analytics](#data--analytics)
- [DevOps & CI/CD](#devops--cicd)
- [Storage & Backup](#storage--backup)
- [Networking](#networking)
- [Cost Management](#cost-management)
- [Migration & Assessment](#migration--assessment)
- [Community Tools & Extensions](#community-tools--extensions)

---

## Command Line Tools

### Azure CLI
- **Description**: Official cross-platform command-line tool for managing Azure resources
- **Repository**: https://github.com/Azure/azure-cli
- **License**: MIT
- **Language**: Python
- **Features**: Comprehensive Azure resource management, scripting support, interactive mode

### Azure PowerShell
- **Description**: PowerShell modules for managing Azure resources
- **Repository**: https://github.com/Azure/azure-powershell
- **License**: Apache 2.0
- **Language**: PowerShell/C#
- **Features**: PowerShell integration, pipeline support, automation-friendly

### AzCopy
- **Description**: Command-line utility for copying data to/from Azure Storage
- **Repository**: https://github.com/Azure/azure-storage-azcopy
- **License**: MIT
- **Language**: Go
- **Features**: High-performance transfers, resumable uploads, blob/file/table storage support

---

## Infrastructure as Code (IaC)

### Terraform Azure Provider
- **Description**: Terraform provider for managing Azure resources
- **Repository**: https://github.com/hashicorp/terraform-provider-azurerm
- **License**: MPL 2.0
- **Language**: Go
- **Features**: Declarative infrastructure, state management, extensive resource coverage

### Bicep
- **Description**: Domain-specific language for deploying Azure resources (ARM template successor)
- **Repository**: https://github.com/Azure/bicep
- **License**: MIT
- **Language**: C#
- **Features**: Simplified ARM syntax, IDE support, type safety

### Pulumi Azure Providers
- **Description**: Infrastructure as Code using programming languages
- **Repository**: https://github.com/pulumi/pulumi-azure
- **License**: Apache 2.0
- **Language**: Go (with Python, TypeScript, C#, Go SDKs)
- **Features**: Use real programming languages, test infrastructure code, component model

### Azure Resource Manager (ARM) Templates
- **Description**: Native Azure deployment templates
- **Repository**: https://github.com/Azure/azure-quickstart-templates
- **License**: MIT
- **Language**: JSON
- **Features**: 1000+ quickstart templates, official Microsoft support

### Farmer
- **Description**: F# DSL for generating ARM templates
- **Repository**: https://github.com/CompositionalIT/farmer
- **License**: MIT
- **Language**: F#
- **Features**: Type-safe infrastructure, functional programming approach, ARM template generation

---

## Kubernetes & Container Tools

### Azure Kubernetes Service (AKS) Engine
- **Description**: Tool for provisioning Kubernetes clusters on Azure
- **Repository**: https://github.com/Azure/aks-engine
- **License**: Apache 2.0
- **Language**: Go
- **Features**: Custom cluster configurations, ARM template generation

### Kubectl Azure Authentication Plugin
- **Description**: kubectl credential plugin for Azure
- **Repository**: https://github.com/Azure/kubelogin
- **License**: MIT
- **Language**: Go
- **Features**: Azure AD authentication for Kubernetes

### Draft
- **Description**: Tool for building Kubernetes applications
- **Repository**: https://github.com/Azure/draft
- **License**: MIT
- **Language**: Go
- **Features**: Streamlined Kubernetes development, Dockerfile generation, Helm chart creation

### Brigade
- **Description**: Event-driven scripting for Kubernetes
- **Repository**: https://github.com/brigadecore/brigade
- **License**: Apache 2.0
- **Language**: Go
- **Features**: Event-driven workflows, JavaScript scripting, pipeline automation

### Virtual Kubelet
- **Description**: Kubelet implementation that connects Kubernetes to other APIs (e.g., Azure Container Instances)
- **Repository**: https://github.com/virtual-kubelet/virtual-kubelet
- **License**: Apache 2.0
- **Language**: Go
- **Features**: Serverless container support, ACI integration, bursting capabilities

---

## Monitoring & Observability

### Azure Monitor OpenTelemetry
- **Description**: OpenTelemetry integration for Azure Monitor
- **Repository**: https://github.com/Azure/azure-sdk-for-python/tree/main/sdk/monitor
- **License**: MIT
- **Language**: Multiple
- **Features**: Distributed tracing, metrics collection, log aggregation

### Application Insights SDK
- **Description**: SDKs for integrating Application Insights monitoring
- **Repository**: https://github.com/microsoft/ApplicationInsights-dotnet
- **License**: MIT
- **Language**: .NET, Java, JavaScript, Python
- **Features**: APM, telemetry, performance monitoring

### Grafana Azure Monitor Data Source
- **Description**: Grafana plugin for Azure Monitor
- **Repository**: https://github.com/grafana/azure-monitor-datasource
- **License**: Apache 2.0
- **Language**: TypeScript
- **Features**: Visualize Azure metrics, query Azure Monitor, dashboard integration

### Prometheus Azure Exporter
- **Description**: Prometheus exporter for Azure metrics
- **Repository**: https://github.com/RobustPerception/azure_metrics_exporter
- **License**: Apache 2.0
- **Language**: Python
- **Features**: Export Azure metrics to Prometheus, monitoring integration

---

## Security & Compliance

### ScubaGear (Azure Secure Configuration Baseline Assessment)
- **Description**: Tool for assessing Azure AD and Microsoft 365 security configurations
- **Repository**: https://github.com/cisagov/ScubaGear
- **License**: CC0 1.0
- **Language**: PowerShell
- **Features**: Security baseline assessment, compliance checking, CISA recommendations

### Azure Security Center Automation
- **Description**: Automate Azure Security Center operations
- **Repository**: https://github.com/Azure/Azure-Security-Center
- **License**: MIT
- **Language**: PowerShell/ARM Templates
- **Features**: Security automation, compliance monitoring, threat detection

### CloudGuard
- **Description**: Cloud-native security platform (Check Point)
- **Repository**: https://github.com/CheckPointSW/CloudGuard-ShiftLeft
- **License**: Apache 2.0
- **Language**: Python
- **Features**: IaC security scanning, policy enforcement

### Checkov
- **Description**: Static code analysis for infrastructure as code
- **Repository**: https://github.com/bridgecrewio/checkov
- **License**: Apache 2.0
- **Language**: Python
- **Features**: ARM/Bicep scanning, policy as code, CI/CD integration

### Terrascan
- **Description**: Security scanner for IaC with Azure support
- **Repository**: https://github.com/tenable/terrascan
- **License**: Apache 2.0
- **Language**: Go
- **Features**: Terraform/ARM scanning, compliance policies, vulnerability detection

### tfsec
- **Description**: Security scanner for Terraform with Azure provider support
- **Repository**: https://github.com/aquasecurity/tfsec
- **License**: MIT
- **Language**: Go
- **Features**: Static analysis, security best practices, custom checks

---

## Development Tools

### Azure Functions Core Tools
- **Description**: Local development tools for Azure Functions
- **Repository**: https://github.com/Azure/azure-functions-core-tools
- **License**: MIT
- **Language**: C#
- **Features**: Local debugging, function templates, deployment tools

### Azure SDK for Python
- **Description**: Azure libraries for Python developers
- **Repository**: https://github.com/Azure/azure-sdk-for-python
- **License**: MIT
- **Language**: Python
- **Features**: Comprehensive Azure service coverage, async support, management libraries

### Azure SDK for .NET
- **Description**: Azure libraries for .NET developers
- **Repository**: https://github.com/Azure/azure-sdk-for-net
- **License**: MIT
- **Language**: C#
- **Features**: .NET Core/Framework support, management and data plane operations

### Azure SDK for Java
- **Description**: Azure libraries for Java developers
- **Repository**: https://github.com/Azure/azure-sdk-for-java
- **License**: MIT
- **Language**: Java
- **Features**: Spring integration, async operations, Azure services support

### Azure SDK for JavaScript
- **Description**: Azure libraries for JavaScript/TypeScript developers
- **Repository**: https://github.com/Azure/azure-sdk-for-js
- **License**: MIT
- **Language**: TypeScript
- **Features**: Node.js and browser support, modern JavaScript, promise-based APIs

### Azure SDK for Go
- **Description**: Azure libraries for Go developers
- **Repository**: https://github.com/Azure/azure-sdk-for-go
- **License**: Apache 2.0
- **Language**: Go
- **Features**: Management and data plane SDKs, Go idioms

### Azurite
- **Description**: Azure Storage emulator for local development
- **Repository**: https://github.com/Azure/Azurite
- **License**: MIT
- **Language**: TypeScript
- **Features**: Blob, Queue, and Table storage emulation, cross-platform, VS Code integration

### Azure Storage Explorer
- **Description**: Cross-platform GUI for managing Azure Storage
- **Repository**: https://github.com/microsoft/AzureStorageExplorer
- **License**: Custom (free to use)
- **Language**: TypeScript/Electron
- **Features**: Visual storage management, file uploads/downloads, SAS token management

---

## Data & Analytics

### Azure Data Studio
- **Description**: Cross-platform database tool for SQL Server and Azure SQL
- **Repository**: https://github.com/microsoft/azuredatastudio
- **License**: MIT (with some proprietary components)
- **Language**: TypeScript
- **Features**: Query editing, notebooks, extensions, charting

### Azure Databricks CLI
- **Description**: Command-line interface for Azure Databricks
- **Repository**: https://github.com/databricks/databricks-cli
- **License**: Apache 2.0
- **Language**: Python
- **Features**: Job management, workspace operations, DBFS access

### Azure Synapse Analytics Artifacts
- **Description**: Sample artifacts for Azure Synapse Analytics
- **Repository**: https://github.com/Azure-Samples/Synapse
- **License**: MIT
- **Language**: Various
- **Features**: SQL scripts, notebooks, pipelines, best practices

---

## DevOps & CI/CD

### Azure DevOps CLI Extension
- **Description**: Azure CLI extension for Azure DevOps
- **Repository**: https://github.com/Azure/azure-devops-cli-extension
- **License**: MIT
- **Language**: Python
- **Features**: Pipeline management, work item tracking, repository operations

### Azure Pipelines Tasks
- **Description**: Collection of tasks for Azure Pipelines
- **Repository**: https://github.com/microsoft/azure-pipelines-tasks
- **License**: MIT
- **Language**: TypeScript
- **Features**: Build and release tasks, cross-platform, extensible

### Azure Pipelines Agent
- **Description**: Agent for running Azure Pipelines jobs
- **Repository**: https://github.com/microsoft/azure-pipelines-agent
- **License**: MIT
- **Language**: C#
- **Features**: Self-hosted agents, container support, cross-platform

### GitHub Actions for Azure
- **Description**: GitHub Actions for deploying to Azure
- **Repository**: https://github.com/Azure/actions
- **License**: MIT
- **Language**: TypeScript
- **Features**: Login, app deployment, Kubernetes, function apps

---

## Storage & Backup

### Blobporter
- **Description**: High-performance data transfer tool for Azure Blob Storage
- **Repository**: https://github.com/Azure/blobporter
- **License**: MIT
- **Language**: Go
- **Features**: Parallel uploads, large file optimization, resume support

### Azure Backup Scripts
- **Description**: Community scripts for Azure Backup automation
- **Repository**: https://github.com/Azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.recoveryservices
- **License**: MIT
- **Language**: PowerShell/ARM
- **Features**: Backup automation, recovery scenarios

---

## Networking

### Azure Network Security Group Flow Logs Parser
- **Description**: Tools for parsing and analyzing NSG flow logs
- **Repository**: https://github.com/Azure/Azure-Network-Security
- **License**: MIT
- **Language**: Various
- **Features**: Log analysis, traffic patterns, security insights

### Azure VPN Client
- **Description**: OpenVPN configuration for Azure
- **Repository**: https://github.com/Azure/azure-vpn-client
- **License**: MIT
- **Language**: Various
- **Features**: VPN setup, client configuration

---

## Cost Management

### Azure Cost CLI
- **Description**: Command-line tool for Azure cost analysis
- **Repository**: https://github.com/mivano/azure-cost-cli
- **License**: MIT
- **Language**: C#
- **Features**: Cost reporting, budget tracking, spending analysis

### Azure Optimization Engine
- **Description**: Extensible solution for cost optimization recommendations
- **Repository**: https://github.com/helderpinto/AzureOptimizationEngine
- **License**: MIT
- **Language**: PowerShell
- **Features**: Cost optimization, resource recommendations, automation

### Infracost
- **Description**: Cloud cost estimates for Terraform (Azure support)
- **Repository**: https://github.com/infracost/infracost
- **License**: Apache 2.0
- **Language**: Go
- **Features**: Cost estimates, PR comments, policy enforcement

---

## Migration & Assessment

### Azure Migrate
- **Description**: Tools and resources for Azure migration
- **Repository**: https://github.com/Azure/azure-migrate
- **License**: MIT
- **Language**: Various
- **Features**: Assessment tools, migration planning

### Service Map
- **Description**: Application dependency mapping
- **Repository**: https://github.com/Azure/service-map
- **License**: MIT
- **Language**: Various
- **Features**: Dependency discovery, migration planning

---

## Community Tools & Extensions

### Azure Resource Inventory
- **Description**: PowerShell script for documenting Azure resources
- **Repository**: https://github.com/azureinventory/ARI
- **License**: MIT
- **Language**: PowerShell
- **Features**: Inventory generation, Excel reports, resource documentation

### Azure Naming Tool
- **Description**: Web application for generating Azure resource names
- **Repository**: https://github.com/microsoft/CloudAdoptionFramework/tree/master/ready/AzNamingTool
- **License**: MIT
- **Language**: C#
- **Features**: Naming convention enforcement, custom templates

### PSRule for Azure
- **Description**: Rules and documentation for validating Azure resources
- **Repository**: https://github.com/Azure/PSRule.Rules.Azure
- **License**: MIT
- **Language**: PowerShell
- **Features**: Well-Architected Framework checks, CI/CD integration, custom rules

### Azure Quick Review
- **Description**: Script to review Azure subscriptions for best practices
- **Repository**: https://github.com/Azure/azqr
- **License**: MIT
- **Language**: Go
- **Features**: Best practice checks, recommendation engine, multiple output formats

### Steampipe Azure Plugin
- **Description**: Use SQL to query Azure resources
- **Repository**: https://github.com/turbot/steampipe-plugin-azure
- **License**: Apache 2.0
- **Language**: Go
- **Features**: SQL queries for Azure, compliance checks, resource discovery

### Azure Terrafy
- **Description**: Tool to import existing Azure infrastructure to Terraform
- **Repository**: https://github.com/Azure/aztfy
- **License**: MIT
- **Language**: Go
- **Features**: Import Azure resources, generate Terraform code, state management

### Azure Graph Explorer
- **Description**: Tool for exploring Microsoft Graph API
- **Repository**: https://github.com/microsoftgraph/microsoft-graph-explorer-v4
- **License**: MIT
- **Language**: TypeScript
- **Features**: API exploration, query building, Azure AD integration

### K9s
- **Description**: Terminal UI for managing Kubernetes clusters (AKS compatible)
- **Repository**: https://github.com/derailed/k9s
- **License**: Apache 2.0
- **Language**: Go
- **Features**: Cluster monitoring, resource management, real-time updates

### Lens (OpenLens)
- **Description**: Kubernetes IDE (works with AKS)
- **Repository**: https://github.com/MuhammedKalkan/OpenLens
- **License**: MIT
- **Language**: TypeScript
- **Features**: Visual cluster management, monitoring, extensions

---

## Contributing

Found a tool that should be listed here? Please submit a pull request or open an issue!

### Criteria for inclusion:
- Tool must be free or open-source
- Tool must be actively maintained
- Tool must be relevant to Azure development, operations, or management
- Preference for community-driven projects

## License

This list is provided under the MIT License. Individual tools have their own licenses.
# azure-tool-list
Tools for Azure.

- [Bicep Linter](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/linter)
- [Azure Region Span](https://github.com/vmisson/azure-region-span)
