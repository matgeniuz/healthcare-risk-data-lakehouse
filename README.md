# healthcare-risk-data-lakehouse
End-to-end PySpark healthcare data pipeline for diabetes risk analytics using a Bronze/Silver/Gold lakehouse architecture.

This project simulates a healthcare data engineering pipeline that ingests member, lab, medication, provider, and claims data into a Databricks lakehouse. The pipeline cleans and transforms the data through Bronze, Silver, and Gold layers to create analytics-ready tables for identifying diabetic members at risk of uncontrolled HbA1c.

# Project Architecture

Raw CSV files
   ↓
Bronze Layer
   Raw ingested tables
   ↓
Silver Layer
   Cleaned and standardized tables
   ↓
Gold Layer
   Analytics-ready tables and ML feature table
   ↓
SQL analysis / dashboard / model-ready output
