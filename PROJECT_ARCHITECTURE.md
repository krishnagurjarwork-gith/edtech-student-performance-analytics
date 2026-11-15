# Project Architecture

## EdTech Student Performance & Engagement Analytics

### Data Processing Workflow

The project follows a Medallion Architecture to organise and process student engagement data.

### 1. Bronze Layer
Raw student engagement data is ingested and stored in Azure Data Lake Storage Gen2.

### 2. Silver Layer
The raw data is cleaned and transformed using Azure Databricks.

### 3. Gold Layer
Processed data is prepared for analytical reporting and dashboard development.

### 4. Workflow Orchestration
Azure Data Factory orchestrates the notebook execution workflow.

### 5. Data Visualisation
Power BI presents student engagement, topic-wise comparisons, performance indicators and risk analysis.

### Technologies
- Azure Data Lake Storage Gen2
- Azure Data Factory
- Azure Databricks
- Python / PySpark
- SQL
- Power BI

### Project Demonstration
https://youtu.be/fK9njP3VOtA
