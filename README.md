# azure-datafactory-databricks-synapse-powerbi-project
This project demonstrates a complete cloud-based Data Engineering solution using Microsoft Azure.  The pipeline extracts data from REST APIs and CSV files, stores raw data in Azure Data Lake Storage Gen2, transforms it using Azure Databricks, serves curated data through Azure Synapse Analytics, and visualizes business insights using Power BI.

| Service              | Purpose             |
| -------------------- | ------------------- |
| Azure Data Factory   | Data Ingestion      |
| REST API             | Source System       |
| CSV Files            | Source System       |
| Azure Data Lake Gen2 | Storage             |
| Azure Databricks     | Data Processing     |
| PySpark              | Data Transformation |
| Delta Lake           | Optimized Storage   |
| Azure Synapse        | Data Warehouse      |
| Power BI             | Reporting           |
| GitHub               | Version Control     |

**Project Workflow**
  REST API -> Azure Data Factory -> Azure Data Lake (Bronze) -> Azure Databricks -> Bronze → Silver → Gold -> Azure Synapse -> Power BI Dashboard


