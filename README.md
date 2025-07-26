# ETLPipeline
Powering data for the Department of Engergy

⚡ Automated Energy Data Pipeline

This project demonstrates how to build a data pipeline to automate the extraction, transformation, and loading (ETL) of energy data using Python and pandas.

🏢 Project Background
Previously, analysts manually processed energy sales and capability data each quarter—a time-consuming and tedious task. My role is to automate this process so that data is pulled and prepared monthly, enabling faster insights and freeing up time for stakeholders.

📂 Data Sources
The pipeline works with two raw data files:

electricity_sales.csv: Contains state-level sales information across energy types.

electricity_capability_nested.json: Contains nested JSON data describing generation capability.

🔧 Technologies Used
Python

pandas

parquet for efficient data storage

Custom functions to extract, transform, and load datasets

🧱 ETL Pipeline Overview
Extract: Load raw CSV and JSON data into dataframes.

Transform:

Clean and reshape the sales data.

Normalize nested JSON into flat tables.

Handle data types and missing values.

Load: Save the cleaned and transformed data into .parquet format for downstream use.

✅ Outcome
This automated ETL pipeline runs efficiently on a monthly basis, reducing the manual burden on analysts and improving data availability for business decisions.

