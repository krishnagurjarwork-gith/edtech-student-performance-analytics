
# EdTech Student Performance & Engagement Analytics Dashboard

## Project Overview

The **EdTech Student Performance & Engagement Analytics Dashboard** is a data engineering and analytics project designed to analyse student learning behaviour, engagement with video lectures, and academic performance.

The project uses Microsoft Azure services to process student engagement data through a Medallion Architecture and presents meaningful insights through an interactive Power BI dashboard.

## Project Objectives

- Analyse student engagement with online video lectures.
- Track student watch time and learning behaviour.
- Identify lecture drop-off patterns.
- Analyse the relationship between student engagement and academic performance.
- Identify students who may be at academic risk.
- Present meaningful insights through interactive visualisations.

## Technologies Used

| Technology | Purpose |
|---|---|
| Azure Data Lake Storage Gen2 | Data storage |
| Azure Data Factory | Workflow orchestration |
| Azure Databricks | Data processing and transformation |
| Python | Data processing |
| PySpark | Large-scale data transformation |
| SQL | Data querying and analysis |
| Power BI | Dashboard creation and visualisation |

## Project Architecture

The project follows the **Medallion Architecture**, which organises data processing into three layers:

### 1. Bronze Layer
- Stores raw student engagement data.
- Maintains the original ingested data.

### 2. Silver Layer
- Performs data cleaning and transformation.
- Prepares structured data for further analysis.

### 3. Gold Layer
- Stores processed data prepared for analytics.
- Supports dashboard reporting and visualisation.

Azure Data Factory is used to orchestrate the data processing workflow, while Azure Databricks handles data transformation.

For a detailed explanation, see [Project Architecture](PROJECT_ARCHITECTURE.md).

## Key Dashboard Features

- Student engagement analysis
- Video lecture watch-time analysis
- Topic-wise performance comparison
- Student risk identification
- Academic performance insights
- Interactive Power BI visualisations

## Project Demonstration

Watch the project demonstration video:

[▶ Watch Project Demo on YouTube](https://youtu.be/fK9njP3VOtA)

## Project Screenshots

The `screenshots` folder contains visual evidence of the project, including Azure resources, data processing workflows, and Power BI dashboard views.

[View Project Screenshots](screenshots/)

## Repository Structure

```text
edtech-student-performance-analytics/
│
├── README.md
├── PROJECT_ARCHITECTURE.md
│
├── screenshots/
│   └── README.md
│
├── notebooks/
│   └── README.md
│
└── sql/
    └── README.md
```

**Note:** The repository currently includes project documentation and screenshots. Original notebook source files and SQL scripts are not included at this stage.

## Conclusion

This project demonstrates the use of cloud-based data engineering and business intelligence technologies to analyse student engagement and academic performance.

It aims to generate meaningful, data-driven insights into online learning behaviour and help identify students who may require additional academic support.

---

**Project Domain:** Data Engineering & Analytics  
**Project Type:** Academic / Industrial Training Project  
**Technologies:** Microsoft Azure, Databricks, Python, PySpark, SQL and Power BI

**Developed by:** Krishna Gurjar
