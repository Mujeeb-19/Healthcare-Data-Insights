# Healthcare-Data-Insights-with-Azure-Data-Lake-Databricks-Power-BI
Description:
An end-to-end data engineering project to extract, transform, and visualize healthcare data from a GitHub repository to Azure Data Lake Storage (ADLS). Utilizes Azure Data Factory for secure data ingestion, Azure Databricks for data cleaning and transformation, Synapse Analytics for data analysis, and Power BI for interactive visualizations. This pipeline enhances data quality, scalability, and provides actionable healthcare insights.

Features:

- Data Ingestion:
Ingests healthcare data from GitHub to ADLS using Azure Data Factory with an HTTP linked service.
- Data Cleaning & Transformation:
Utilizes Azure Databricks to drop unnecessary columns, standardize names, add calculated fields, and save data in Parquet format.
- Data Validation and Backup:
Implements metadata checks, debugging breakpoints, and backups of processed files to a backup container.
- Data Loading and Analysis:
Loads transformed data into Synapse Analytics, creates external tables, and performs SQL-based analyses.
- Data Visualization:
Connects Synapse Analytics to Power BI, performs data transformations in Power Query, and creates interactive dashboards with various visualizations.
- Scalability & Optimization:
Ensures the pipeline can handle large datasets and optimizes storage and query performance through partitioning and efficient storage formats.


Technologies Used:

- Azure Data Factory (ADF): Orchestrates data ingestion and pipeline management.
- Azure Databricks: Executes data cleaning and transformation tasks.
- Azure Data Lake Storage (ADLS): Centralized data repository for raw and processed data.
- Azure Synapse Analytics: Facilitates advanced data analysis with SQL queries.
- Power BI: Develops interactive dashboards and visualizations.
- GitHub: Hosts the project repository and version control.
- SQL Server: Source of the on-premises healthcare data.
