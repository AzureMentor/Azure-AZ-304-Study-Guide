# AZ-304: Design Infrastructure (25-30%)

## Design a compute solution
- [Recommend a solution for Compute provisioning](https://docs.microsoft.com/en-us/azure/architecture/guide/technology-choices/compute-decision-tree)
- Determine appropriate compute technologies, including:
  - [Virtual machines](https://docs.microsoft.com/en-us/azure/virtual-machines)
  - [App Services](https://docs.microsoft.com/en-us/azure/app-service)
  - [Azure Service Fabric](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-overview)
  - [Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/functions-overview)
  - [Windows Virtual Desktop](https://docs.microsoft.com/en-us/azure/virtual-desktop/overview)
  - [Azure Batch](https://docs.microsoft.com/en-us/azure/batch/batch-technical-overview)
  - [HPC](https://azure.microsoft.com/en-us/solutions/high-performance-computing/)
  - [Containers](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-overview)
- Recommend a solution for containers
  - [Azure Kubernetes Service](https://docs.microsoft.com/en-us/azure/aks/intro-kubernetes)
  - [Introduction to private Docker container registries in Azure](https://docs.microsoft.com/en-us/azure/container-registry/container-registry-intro)
- Recommend a solution for Automating compute management
  - [An introduction to Azure Automation](https://docs.microsoft.com/en-us/azure/automation/automation-intro)
  - [What is Azure Logic Apps?](https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-overview)

## Design a network solution
- Recommend a network architecture:
  - [Hub and spoke](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/hybrid-networking/hub-spoke?tabs=cli)
  - [Virtual WAN](https://docs.microsoft.com/en-us/azure/virtual-wan/virtual-wan-about)
- Recommend a solution for network addressing and name resolution
  - [Name resolution for resources in Azure virtual networks](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-name-resolution-for-vms-and-role-instances)
  - [Use Azure DNS to provide custom domain settings for an Azure service](https://docs.microsoft.com/en-us/azure/dns/dns-custom-domain)
  - [Tutorial: Host your domain in Azure DNS](https://docs.microsoft.com/en-us/azure/dns/dns-delegate-domain-azure-dns)
  - [Quickstart: Create an Azure private DNS zone using the Azure portal](https://docs.microsoft.com/en-us/azure/dns/private-dns-getstarted-portal)
- Recommend a solution for network provisioning
  - [What is Azure Virtual Network?](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-overview)
  - [Azure Virtual Network FAQ](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-faq)
  - [Virtual network service endpoint policies for Azure Storage](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-service-endpoint-policies-overview)
  - [Virtual Network service endpoints](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-service-endpoints-overview)
- Recommend a solution for network security
  - [Azure Best Practices for Network Security](https://docs.microsoft.com/en-us/azure/security/fundamentals/network-best-practices)
  - [Azure Private Link](https://docs.microsoft.com/en-us/azure/private-link/private-link-overview)
  - [Azure Firewall](https://docs.microsoft.com/en-us/azure/firewall/overview)
  - Gateways
    - [What is VPN Gateway?](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vpngateways)
  - Network segmentation
    - [Perimeter networks](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/perimeter-networks)
    - [DMZs](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/decision-guides/software-defined-network/cloud-dmz)
    - [NVAs](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/dmz/nva-ha)
- Recommend a solution for network connectivity to:
  - The Internet
  - On-premises networks
  - Other Azure virtual networks
  - [What is VPN Gateway?](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vpngateways)
  - [What is Azure ExpressRoute?](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-introduction)
- Recommend a solution for automating network management
  - [What is Azure Virtual Network?](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-overview)
- Recommend a solution for:
  - [Azure Load Balancing](https://docs.microsoft.com/en-us/azure/architecture/guide/technology-choices/load-balancing-overview)
  - Traffic routing
    - [What is Traffic Manager?](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-overview)
  - [What is Azure Front Door?](https://docs.microsoft.com/en-us/azure/frontdoor/front-door-overview)
  - [What is Azure Application Gateway?](https://docs.microsoft.com/en-us/azure/application-gateway/overview)

## Design an application architecture
- Recommend a microservices architecture including:
  - [Event Grid](https://docs.microsoft.com/en-us/azure/event-grid/overview)
  - [Event Hubs](https://docs.microsoft.com/en-us/azure/event-hubs/event-hubs-about)
  - [Service Bus](https://docs.microsoft.com/en-us/azure/service-bus-messaging/service-bus-messaging-overview)
  - [Azure Queue Storage](https://docs.microsoft.com/en-us/azure/storage/queues/storage-queues-introduction)
  - [Logic Apps](https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-overview)
  - [Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/functions-overview)
  - [Service Fabric](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-overview)
    - [Microservices architecture style](https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/microservices)
  - [AKS](https://azure.microsoft.com/en-ca/services/kubernetes-service)
  - [Azure App Configuration]()
  - [Webhooks](https://docs.microsoft.com/en-us/azure/automation/automation-webhooks)
- Recommend an orchestration solution for deployment and maintenance of application including:
  - [ARM templates](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/overview)
    - [Tutorial: Create and deploy your first ARM template](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-tutorial-create-first-template)
  - [Azure Automation]()
  - [Azure Pipelines]()
  - [Logic Apps](https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-overview)
  - [Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/functions-overview)
- Recommend a solution for API integration

## Design migrations
- Assess and interpret on-premises servers, data, and applications for migration
  - [About Azure Migrate](https://docs.microsoft.com/en-us/azure/migrate/migrate-services-overview)
- Recommend a solution for migrating applications and VMs
- Recommend a solution for migration of databases
  - [Assess the readiness of a SQL Server data estate migrating to Azure SQL Database using the Data Migration Assistant](https://docs.microsoft.com/en-us/sql/dma/dma-assess-sql-data-estate-to-sqldb)
- Determine migration scope, including:
  - Redundant
  - Related
  - Trivial
  - Outdated data
- Recommend a solution for Migrating Data:
  - Storage Migration Service
    - [SQL Server Migration Assistant](https://docs.microsoft.com/en-us/sql/ssma/sql-server-migration-assistant)
  - [Azure Data Box](https://docs.microsoft.com/en-us/azure/databox/data-box-overview)
  - Azure File Sync-based migration to hybrid file server
    - [Migrate to Azure file shares](https://docs.microsoft.com/en-us/azure/storage/files/storage-files-migration-overview)

[Return to Table of Contents](README.md)
