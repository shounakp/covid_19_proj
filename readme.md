# 🦠 COVID-19 Data Analysis Using Azure Data Engineering
This project demonstrates the design and implementation of a scalable data pipeline to process and analyze COVID-19 data using Azure’s modern data stack. The architecture integrates Azure Data Factory, Azure Storage, SQL datasets, and Azure Databricks with Delta Lake to enable efficient data ingestion, transformation, and reporting.

# 📌 Project Overview
The goal of this project is to automate the collection, processing, and analysis of COVID-19 data using cloud-based tools to support accurate reporting and data-driven decision making. The pipeline is built for performance, reliability, and modularity using Azure Data Engineering services.

# 🧱 Technologies Used
Azure Data Factory (ADF)
Orchestrated end-to-end data pipelines to ingest and process COVID-19 datasets.

Azure Data Lake Storage
Used for scalable, secure storage of raw and processed data.

Azure SQL and Datasets
Integrated structured data sources for analysis-ready input.

Azure Databricks
Performed large-scale data transformations and analytics using PySpark.

Delta Lake
Enabled ACID-compliant storage, efficient updates, and schema evolution on big data.

# 🔄 Data Pipeline Flow
Data Ingestion: COVID-19 data ingested using ADF pipelines from public and SQL sources.

Storage: Data stored in Azure Data Lake in both raw and curated zones.

Transformation: Azure Databricks processes and cleans the data using PySpark.

Delta Lake Integration: Transformed data written to Delta tables for efficient querying.

Analytics: Cleaned data used to generate insights and visualizations for decision making.

# 🎯 Key Features
Parameterized and modular ADF pipelines

Integration with Delta Lake for scalable and efficient data management

PySpark transformations for data cleaning and enrichment

End-to-end orchestration using Azure-native tools

Reusable and extensible pipeline for future datasets
# 📈 Outcomes
Automated and scalable pipeline for COVID-19 data ingestion and processing.

Reliable and efficient data handling using Delta Lake.

Actionable insights generated to support reporting and decision-making processes.
# Data architecture digram
# ![image](https://github.com/user-attachments/assets/58f121ab-af84-4654-b9c0-9087b8be01c6)

