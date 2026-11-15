# EdTech Student Performance & Engagement Analytics Dashboard

## Project Overview

The **EdTech Student Performance & Engagement Analytics Dashboard** is a data engineering and analytics project designed to analyse student learning behaviour, engagement with video lectures, and academic performance.

The project uses Microsoft Azure services to process student engagement data through a Medallion Architecture and presents meaningful insights through an interactive Power BI dashboard.

## Objectives

- Analyse student engagement with online video lectures.
- Track student watch time and learning behaviour.
- Identify lecture drop-off patterns.
- Analyse the relationship between engagement and academic performance.
- Identify students who may be at academic risk.
- Present insights through interactive visualisations.

## Technologies Used

| Technology | Purpose |
|---|---|
| Azure Data Lake Storage Gen2 | Data storage |
| Azure Data Factory | Workflow orchestration |
| Azure Databricks | Data processing and transformation |
| Azure SQL | Data querying and storage |
| Power BI | Dashboard and visualisation |
| Python / PySpark | Data processing |

## Project Architecture

The project follows the **Medallion Architecture**:

1. **Bronze Layer:** Raw student engagement data is ingested and stored.
2. **Silver Layer:** Data cleaning and transformation are performed.
3. **Gold Layer:** Processed data is prepared for analytics and dashboard reporting.

Azure Data Factory is used to orchestrate the data processing workflow.

## Key Dashboard Features

- Student engagement analysis
- Watch-time analysis
- Topic-wise performance comparison
- Student risk identification
- Academic performance insights
- Interactive Power BI visualisations

## Project Demonstration

Watch the project demonstration video:

[▶ Watch on YouTube](https://youtu.be/fK9njP3VOtA)

## Project Screenshots

The `screenshots` folder contains visual evidence of the project implementation, including Azure resources, data processing workflows, and the Power BI dashboard.

## Repository Structure

```text
edtech-student-performance-analytics/
│
├── README.md
├── screenshots/
├── notebooks/
├── sql/
└── report/
```

## Conclusion

This project demonstrates how cloud-based data engineering and business intelligence tools can be integrated to analyse student engagement and academic performance. It aims to support data-driven insights into online learning behaviour and student performance.

---

**Project Domain:** Data Engineering & Analytics  
**Project Type:** Academic / Industrial Training Project  
**Technologies:** Microsoft Azure, Databricks, Python, SQL and Power BI
