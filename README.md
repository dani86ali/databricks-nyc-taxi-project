# databricks-nyc-taxi-project
Repository for Interviews
# NYC Taxi Data Analysis Using Databricks and PySpark

## Overview
This project demonstrates how to ingest, clean, transform, and analyze NYC Taxi data using Databricks and PySpark.

## Steps
1. **Data Ingestion**: Loaded the NYC Taxi dataset into Databricks.
2. **Data Transformation**: Cleaned and transformed the data using PySpark.
3. **Data Analysis**: Performed aggregations and created visualizations.
4. **Optimization**: Used Delta Lake and Z-ordering to optimize the pipeline.

## Challenges and Solutions
- **Challenge**: Large dataset size caused slow queries.
  **Solution**: Used Delta Lake optimizations like file compaction and Z-ordering.

## Results
- Achieved a 40% improvement in query performance after optimization.

## How to Run
1. Clone this repository.
2. Open the Databricks notebook in your Databricks workspace.
3. Attach the notebook to a cluster and run the cells.
