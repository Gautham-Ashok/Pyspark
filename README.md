PySpark Sales Data Analysis Project
This repository contains a Databricks notebook showcasing a complete ETL (Extract, Transform, Load) and data analysis pipeline using PySpark. The project focuses on cleaning a raw sales dataset, performing feature engineering, and deriving analytical insights through various DataFrame transformations and actions.

🚀 Key Skills Demonstrated
This project highlights proficiency in the following PySpark concepts and operations:

Data Ingestion & Schema Definition: Reading raw CSV data and applying custom schemas for performance and data integrity.

Data Cleaning & Preparation: Handling null values, standardizing inconsistent data, and preparing the dataset for analysis.

Feature Engineering: Creating new, meaningful columns from existing data using withColumn and conditional logic with when().otherwise().

DataFrame Transformations: Applying various transformations like select, filter, dropDuplicates, and orderBy.

Data Aggregation: Using groupBy() with aggregate functions (sum, avg, count) to summarize data.

Window Functions: Applying advanced analytical functions like rank(), dense_rank(), and row_number() over window specifications.

Joins: Combining multiple datasets using different join strategies (e.g., inner, left).

Spark SQL Integration: Leveraging the power of SQL to query DataFrames directly within the Spark environment.

Data Loading: Saving processed data as managed Delta tables for reliability and performance, following modern data warehousing best practices.

🛠️ Technologies Used
Language: Python

Core Framework: Apache Spark (PySpark API)

Platform: Databricks

Data Format: Delta Lake

notebook Overview
The primary file in this repository is the .ipynb notebook which contains all the code and step-by-step analysis. The notebook is structured to follow a logical ETL flow:

Extraction: Loading the raw sales data.

Transformation: Applying all the cleaning, feature engineering, and aggregation logic.

Loading: Saving the final, cleaned data and analytical summaries into Delta tables.
