# PySpark Transaction Analytics – Mini Project

## Overview
This mini project demonstrates the use of PySpark for scalable transaction analytics
on a large synthetic dataset.

The objective is to compute distributed behavioral metrics and identify high-activity
patterns using Spark DataFrames and aggregations. While the data is synthetic, the
analytical workflow mirrors common use cases in fintech and AML environments, such as
transaction monitoring and risk segmentation.



## What This Project Demonstrates
- Use of PySpark for distributed data processing
- Generation of large-scale synthetic transactional data
- Aggregation and segmentation at user and group level
- Identification of high-activity behavioral patterns
- Writing aggregated outputs to Parquet format


## Use Case Context
The techniques demonstrated in this project are applicable to:
- Transaction monitoring systems
- Behavioral analysis in financial services
- Risk-aware analytics pipelines
- Large-scale data processing environments


## Repository Structure
- `/notebooks/` – PySpark analysis notebook
- `/data/` – Data availability notes

- [Analysis Notebook](notebooks/pyspark_transaction_analytics.ipynb)



## Reproducibility
The notebook is provided without stored outputs to keep the repository lightweight.
All results can be reproduced by executing the notebook locally or in a Spark-enabled
environment.



## Tools
PySpark, Spark DataFrames, Parquet
