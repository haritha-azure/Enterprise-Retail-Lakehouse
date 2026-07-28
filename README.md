# Enterprise Retail Lakehouse on Azure

![Azure](https://img.shields.io/badge/Azure-Data%20Engineering-blue)
![Databricks](https://img.shields.io/badge/Databricks-PySpark-red)
![ADF](https://img.shields.io/badge/Azure-Data%20Factory-blueviolet)
![Delta Lake](https://img.shields.io/badge/Delta-Lake-green)
![Power BI](https://img.shields.io/badge/Power-BI-yellow)

## Project Overview

This project demonstrates an end-to-end Azure Data Engineering solution built using Azure Data Factory, Azure Databricks, PySpark, Delta Lake, Azure Data Lake Storage Gen2, Unity Catalog, Azure DevOps, and Power BI.

The solution follows the Medallion Architecture (Bronze, Silver, Gold) to ingest, transform, govern, and serve analytics-ready data for business intelligence.

---

## Business Scenario

A global retail organization receives data from multiple systems including:

- SQL Server
- REST APIs
- CSV Files
- ERP Systems

The objective is to build a centralized Lakehouse platform that supports scalable data ingestion, transformation, governance, and reporting.

---

## Technology Stack

| Category | Technology |
|-----------|------------|
| Cloud | Microsoft Azure |
| Storage | ADLS Gen2 |
| ETL | Azure Data Factory |
| Processing | Azure Databricks |
| Language | PySpark |
| Database | Azure SQL |
| Data Lake | Delta Lake |
| Governance | Unity Catalog |
| CI/CD | Azure DevOps |
| Reporting | Power BI |

---

## Medallion Architecture

- Bronze Layer – Raw Data
- Silver Layer – Cleaned & Validated Data
- Gold Layer – Business Ready Data

---

## Project Structure

```text
Enterprise-Retail-Lakehouse
│
├── architecture
├── datasets
├── adf
├── databricks
├── sql
├── powerbi
├── devops
├── screenshots
└── docs
```

---

## Key Features

- Metadata-driven pipelines
- Incremental loading using Delta MERGE
- Auto Loader
- Unity Catalog
- Azure Key Vault
- Databricks Workflows
- Power BI Reporting
- CI/CD using Azure DevOps
- Performance Optimization
- Monitoring & Logging

---

## Future Enhancements

- Event Hub Streaming
- Microsoft Fabric Integration
- Machine Learning
- Data Quality Dashboard

---

## Author

**Haritha Tenkasala**

Azure Data Engineer
