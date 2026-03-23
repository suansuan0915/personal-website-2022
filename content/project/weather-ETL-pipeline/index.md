---
title: Weather ETL Pipeline & Data Mart
summary: End-to-end batch pipeline for historical weather data using Python, Postgres, dbt, and Airflow, with ongoing migration toward GCS-backed storage and Databricks orchestration.
date: '2025-01-15T00:00:00Z'
tags:
- data engineering
- data modeling
- postgres
- dbt
- Airflow
- Databricks
- Google Cloud Storage (GCS)

# Optional external URL for project (replaces project detail page).
external_link: 'https://github.com/suansuan0915/weather-dbt-project/tree/databricks-gcs-migration'

image:
  caption: ''
  focal_point: Smart
  filename: weather-tools.png

---

This project builds a historical weather analytics pipeline from ingestion through transformation and reporting.

- Batch ingestion and transformation are built with Python, Postgres, dbt, and Airflow.
- The current migration work is moving storage toward Google Cloud Storage and orchestration toward Databricks workflows.
