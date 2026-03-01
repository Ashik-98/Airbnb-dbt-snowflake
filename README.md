# Airbnb End-to-End Data Engineering Pipeline (Snowflake + dbt)

## Overview
This project demonstrates an end-to-end analytics engineering pipeline built using **Snowflake** and **dbt**, following a **medallion architecture (Bronze → Silver → Gold)**.  
The goal of the project is to transform raw Airbnb data into analytics-ready tables using industry-standard data engineering practices.

## Project Flow
Raw Airbnb data is loaded into Snowflake staging tables. dbt is used as the transformation layer to process data through bronze models (raw ingestion), silver models (cleaning and standardization), and gold models (business-ready datasets such as fact tables and a denormalized One Big Table).

The project also demonstrates incremental models for efficient processing, snapshots for tracking historical changes (SCD Type 2), reusable macros, and data quality tests to ensure reliable analytics outputs.

## Tech Stack
- Snowflake
- dbt (Data Build Tool)
- AWS S3 (for source data storage)
- Python
- Git & GitHub

## Author
**Ashik Sikkander Kani**
