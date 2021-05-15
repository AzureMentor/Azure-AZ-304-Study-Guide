# AZ-304: Design Data Storage (15-20%)

## Design a solution for databases
- Select an appropriate data platform based on requirements
  - [What is Azure SQL Database?](https://docs.microsoft.com/en-us/azure/azure-sql/database/sql-database-paas-overview)
  - [What is Azure SQL?](https://docs.microsoft.com/en-us/azure/azure-sql/azure-sql-iaas-vs-paas-what-is-overview)
  - [Understand data store models](https://docs.microsoft.com/en-us/azure/architecture/guide/technology-choices/data-store-overview)
- Recommend database service tier sizing
  - [Azure SQL Database and Azure SQL Managed Instance service tiers](https://docs.microsoft.com/en-us/azure/azure-sql/database/service-tiers-general-purpose-business-critical)
  - [General Purpose service tier - Azure SQL Database and Azure SQL Managed Instance](https://docs.microsoft.com/en-us/azure/azure-sql/database/service-tier-general-purpose)
- [Recommend a solution for database scalability](https://docs.microsoft.com/en-us/azure/azure-sql/database/scale-resources)
- Recommend a solution for:
  - [Azure Data Encryption at rest](https://docs.microsoft.com/en-us/azure/security/fundamentals/encryption-atrest)
  - [Encryption of data in transit](https://docs.microsoft.com/en-us/azure/security/fundamentals/encryption-overview#encryption-of-data-in-transit)
  - Data in use
    - [Transparent data encryption for SQL Database, SQL Managed Instance, and Azure Synapse Analytics](https://docs.microsoft.com/en-us/azure/azure-sql/database/transparent-data-encryption-tde-overview)

## Design data integration
- Recommend a data flow to meet business requirements
  - [Create Azure Data Factory Data Flow](https://docs.microsoft.com/en-us/azure/data-factory/data-flow-create)
  - [Source transformation in mapping data flow](https://docs.microsoft.com/en-us/azure/data-factory/data-flow-source)
- Recommend a solution for data integration, including:
  - [Azure Data Factory](https://docs.microsoft.com/en-us/azure/data-factory/introduction)
  - [Azure Databricks](https://docs.microsoft.com/en-us/azure/databricks/scenarios/what-is-azure-databricks)
  - [Azure Data Lake](https://docs.microsoft.com/en-us/azure/data-lake-store/data-lake-store-overview)
    - [Introduction to Azure Data Lake Storage Gen2](https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-introduction)
  - [Azure Synapse Analytics](https://docs.microsoft.com/en-us/azure/synapse-analytics/overview-what-is)
    - [What is dedicated SQL pool (formerly SQL DW) in Azure Synapse Analytics?](https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-overview-what-is)

## Select an appropriate storage account
- Choose between storage tiers
  - [Access tiers for Azure Blob Storage - hot, cool, and archive](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-storage-tiers)
- Recommend a storage access solution
  - [Introduction to the core Azure Storage services](https://docs.microsoft.com/en-us/azure/storage/common/storage-introduction)
  - [Authorize access to blobs and queues using Azure Active Directory](https://docs.microsoft.com/en-us/azure/storage/common/storage-auth-aad)
  - [Manage storage account access keys](https://docs.microsoft.com/en-us/azure/storage/common/storage-account-keys-manage)
- Recommend storage management tools
  - [Microsoft client tools for working with Azure Storage](https://docs.microsoft.com/en-us/azure/storage/common/storage-explorers)
  - [Get started with AzCopy](https://docs.microsoft.com/en-us/azure/storage/common/storage-use-azcopy-v10)

[Return to Table of Contents](README.md)