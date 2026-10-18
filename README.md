# food-industry-data-pipeline

Food Industry Data Pipeline (Open-Source)
A cost-effective, open-source data warehouse solution for a Food & Beverage client. Built using Python (Ingestion), PostgreSQL (Storage), dbt Core (Transformation), and Power BI (Reporting). Runs on an Azure Cloud VM without Docker.

Architecture
Sources: SQL Server, PostgreSQL, OneDrive (CSVs)
Storage: PostgreSQL (Azure VM)
Ingestion: Custom Python Scripts (Pandas, SQLAlchemy)
Transformation: dbt Core
BI: Power BI
Project Structure
/ingestion: Python scripts to extract data from sources and load to Postgres.
/dbt_models: SQL models for transforming raw data into a Star Schema.
/data: Local staging area for CSVs.