# Fabric-Data-Factory-Contest
This project presents an end-to-end data pipeline built for the Data Factory Challenge using Microsoft Fabric. The objective was to transform raw job salary data into a structured, analytics-ready format for insights.


--------------- Architecture Overview--------
Step1-
##Bronze Layer:--
Raw data is ingested into a Lakehouse from a SharePoint source without transformations, ensuring data is preserved in its original format.

Step 2--
##Silver Layer:--
Data is processed using Data Factory pipelines and stored in a Data Warehouse schema. Transformations include data cleaning, handling null values, and standardizing fields. SQL scripts and Copilot were used to assist in transformations.

Step--3
##Metadata Pipeline:---
metadata-driven pipeline is implemented to manage and monitor data flow across layers. It enables dynamic execution, parameter handling, and improves pipeline scalability and maintainability within Microsoft Fabric.



Step--4
##Gold Layer:
Data is modeled using dbt to create fact and dimension tables. A star schema is built for efficient querying, with reusable transformations such as converting coded fields into readable formats.

Step--5
##Semantic Model & Reporting:--

An AI-ready semantic model is created and used in Power BI. The model is optimized by selecting relevant columns and defining structure for better performance and accurate insights.

Interactive reports are built on top of this model, enabling natural language queries using Copilot and delivering reliable business insights.


##Outcome------>
This project showcases the implementation of an end-to-end data pipeline, from ingestion to reporting, highlighting practical use of Microsoft Fabric, dbt, and Power BI in a unified environment.


Video Walkthrough----->
(https://raw.githubusercontent.com/trivedisunita/Fabric-Data-Factory-Contest/main/Fabric%20Short%20Video2.mp4)
