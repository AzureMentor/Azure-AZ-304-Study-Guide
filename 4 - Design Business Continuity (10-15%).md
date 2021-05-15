# AZ-304: Design Business Continuity (10-15%)

## Design a solution for backup and recovery
- Recommend a recovery solution for Azure hybrid and on-premises workloads that meets recovery objectives:
  - Recovery Time Objective (RTO)
  - Recovery Level Objective (RLO)
  - Recovery Point Objective (RPO)
- [Design and Azure Site Recovery solution](https://docs.microsoft.com/en-us/azure/site-recovery/site-recovery-overview)
  - [General questions about Azure Site Recovery](https://docs.microsoft.com/en-us/azure/site-recovery/site-recovery-faq)
  - [SLA for Azure Site Recovery](https://azure.microsoft.com/en-us/support/legal/sla/site-recovery/v1_2/)
- Recommend a solution for recovery in different regions
- [Recommend a solution for **Azure Backup** management](https://docs.microsoft.com/en-us/azure/backup/backup-overview)
  - [Azure Backup architecture and components](https://docs.microsoft.com/en-us/azure/backup/backup-architecture)
- Design a solution for data archiving and retention
  - [Access tiers for Azure Blob Storage - hot, cool, and archive](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-storage-tiers)
  - [Optimize costs by automating Azure Blob Storage access tiers](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-lifecycle-management-concepts)
  - [Azure Storage redundancy](https://docs.microsoft.com/en-us/azure/storage/common/storage-redundancy)

## Design for high availability
- Recommend a solution for application and workload redundancy, including:
  - Compute
    - [Regions and Availability Zones in Azure](https://docs.microsoft.com/en-us/azure/availability-zones/az-overview)
    - [Create and deploy virtual machines in an availability set using Azure PowerShell](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-availability-sets)
  - Database
    - [High availability for Azure SQL Database and SQL Managed Instance](https://docs.microsoft.com/en-us/azure/azure-sql/database/high-availability-sla)
    - [Overview of business continuity with Azure SQL Database](https://docs.microsoft.com/en-us/azure/azure-sql/database/business-continuity-high-availability-disaster-recover-hadr-overview)
  - Storage
    - [Azure Storage redundancy](https://docs.microsoft.com/en-us/azure/storage/common/storage-redundancy)
- [Recommend a solution for autoscaling](https://docs.microsoft.com/en-us/azure/architecture/best-practices/auto-scaling)
  - [Overview of Autoscale in Azure](https://docs.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-overview)
  - [Dynamically scale database resources with minimal downtime](https://docs.microsoft.com/en-us/azure/azure-sql/database/scale-resources)
  - [Scaling out with Azure SQL Database](https://docs.microsoft.com/en-us/azure/azure-sql/database/elastic-scale-introduction)
  - [What are virtual machine scale sets?](https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/overview)
- Identify resources that require high availability
  - [Enabling Data Residency and Data Protection in Microsoft Azure Regions](https://azure.microsoft.com/en-us/resources/achieving-compliant-data-residency-and-security-with-azure/)
  - [Review your data options](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/considerations/data-options)
- Identify storage types for high availability
  - [Disaster recovery and storage account failover](https://docs.microsoft.com/en-us/azure/storage/common/storage-disaster-recovery-guidance)

[Return to Table of Contents](README.md)