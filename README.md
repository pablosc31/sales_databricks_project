# Data Warehouse for sport store using Databricks, PySpark and SQL Server
Data Warehouse and Analytics solution on Databricks, leveraging PySpark and SQL to perform data extraction, transformation, and loading (ETL), while generating actionable insights through comparative analysis of different approaches. Project involves:

  ***1. Data Architecture:*** Designing a data warehouse using a medallion architecture with Bronze, Silver, and Gold layers.
  
  ***2. ETL Pipelines:*** Extracting, transforming, and loading data from different sources.
  
  ***3. Data Modeling:*** Developing fact and dimension tables.
  
  ***4. Reporting:*** Built Databricks dashboards to present valuable insights, leveraging Genie AI.


## Data Architecture

The project adopts a medallion architecture. The **Bronze layer** stores raw data in its original format, with ingestion performed from CSV files using SQL Server or PySpark. **Silver Layer**  performs data cleansing, standardization, and normalization to ensure the data is properly prepared for analysis. The **Gold layer** contains business-ready data structured into a star schema to support reporting and analytics.

## Other Databricks tools

In addition to the ETL processes, automation tools were leveraged to enhance the project’s robustness and realism, including jobs, pipelines, connection to Azure Blob Storage, Power BI, and compute resources.

## Dashboard Example

The next image illustrates dashboard elements such as KPI cards, bar charts, and tables. With Genie AI, users can create new visualizations or cards using natural language.

<img width="1308" height="863" alt="image" src="https://github.com/user-attachments/assets/ba7333cc-8bba-490e-b833-c7dd6ac2692c" />
