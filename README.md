# Instacart Customer Basket Analysis

## Project Overview
This project explores customer purchasing behaviour using Instacart transactional, product, and customer data. The analysis was completed in Python using Jupyter Notebook and focuses on data preparation, data quality validation, customer and product-level analysis, feature engineering, aggregation, and visual exploration.

The goal of the project was to transform raw retail data into a structured, analysis-ready dataset and generate business insights that could support customer segmentation, purchasing behaviour analysis, and stakeholder reporting.

## Business Context
Instacart is an online grocery delivery and pickup platform. The project simulates the role of a data analyst working with retail transaction data to answer business questions related to:

- customer ordering patterns
- product purchasing behaviour
- pricing and basket trends
- customer segmentation
- loyalty and activity profiling
- data quality and reporting readiness

## Objectives
The main objectives of this project were to:

- import and structure multiple raw datasets in Python
- assess and improve data quality through consistency checks and cleaning
- combine related datasets into a unified analysis layer
- derive new variables to support segmentation and behavioural analysis
- aggregate customer and order-level metrics
- build visualisations to identify trends, distributions, and outliers
- prepare findings and outputs for stakeholder-friendly reporting

## Tools Used
- Python
- Jupyter Notebook
- pandas
- NumPy
- matplotlib
- seaborn
- Excel

## Project Workflow
The project followed a structured analytical workflow:

1. **Project setup and notebook organisation**  
   Established a clear folder structure, imported required libraries, and prepared the working environment in Jupyter Notebook.

2. **Data import and initial profiling**  
   Loaded raw CSV files into pandas dataframes and reviewed structure, dimensions, data types, and descriptive statistics.

3. **Data wrangling and structuring**  
   Removed unnecessary columns, renamed fields for clarity, adjusted data types, and reorganised data for analysis.

4. **Data quality checks and cleaning**  
   Reviewed missing values, duplicates, mixed data types, and abnormal values to improve consistency and analysis readiness.

5. **Data combining and merging**  
   Merged transactional, product, and customer data into integrated datasets using common key fields.

6. **Feature engineering and segmentation**  
   Created derived variables and flags to support customer profiling, price grouping, and behavioural analysis.

7. **Grouping and aggregation**  
   Applied grouped calculations to create customer-level and department-level summary metrics.

8. **Visual exploration and reporting**  
   Built charts to analyse distributions, trends, and relationships, then prepared final outputs for reporting.

## Key Analysis Areas
This project includes analysis related to:

- order frequency and customer activity
- day-of-week and hour-of-day ordering behaviour
- pricing distributions and outlier checks
- department-level purchasing patterns
- customer segmentation by loyalty, activity, and profile characteristics
- grouped customer and product metrics
- exploratory charting for pattern recognition and insight development

## Repository Structure
```text
[01] Project Brief & Planning
[02] Data
    [1] Original Data
    [2] Data Checks & Cleaning
    [3] Prepared Data
[03] Python Scripts
[04] Analysis & Visualizations
    [1] Reports
    [2] Visualizations
    [3] Test Files
[05] Final Deliverables
