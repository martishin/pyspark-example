# PySpark Notebooks
This repository contains a collection of Jupyter Notebooks demonstrating how to use Apache Spark with Python (PySpark). The examples cover a variety of topics including creating Spark contexts and sessions, performing operations with RDDs, DataFrames, and SQL, and reading from various data sources.

## Requirements
* Python 3.x  
* Apache Spark (2.x or 3.x)  
* Jupyter Notebook   
* PySpark  

## How to Run the Notebooks
Create a Virtual Environment
```bash
python3 -m venv venv
```
Activate the Virtual Environment
```bash
source venv/bin/activate
```
Install the required dependencies  
```bash 
pip3 install -r requirements.txt
```
Start Jupyter Lab  
```bash 
jupyter-lab
```
Open the desired notebook from the list and run the cells

## Notebooks
1. [Getting Started with PySpark](https://github.com/martishin/pyspark-examples/blob/main/01_pyspark_get_started.ipynb).
   Introduces the basics of PySpark, including installation, environment setup, and creating a basic Spark session.
2. [Creating Spark Context](https://github.com/martishin/pyspark-examples/blob/main/02_create_spark_context.ipynb).
   Learn how to create and configure a Spark context, the entry point for using Spark's core features.
3. [Creating Spark Session](https://github.com/martishin/pyspark-examples/blob/main/03_create_spark_session.ipynb). Explore the process of creating a SparkSession, the unified entry point for working with DataFrames and SQL in Spark.
4. [RDD Operations](https://github.com/martishin/pyspark-examples/blob/main/04_rdd_operations.ipynb). This notebook covers basic and advanced operations on RDDs (Resilient Distributed Datasets), the fundamental data structure in Spark.
5. [Working with DataFrames](https://github.com/martishin/pyspark-examples/blob/main/05_data_frames_get_started.ipynb). Introduces Spark DataFrames, showing how to create and manipulate them for data analysis.
6. [DataFrames from Different Sources](https://github.com/martishin/pyspark-examples/blob/main/06_data_frames_from_different_sources.ipynb). Demonstrates how to create DataFrames by reading from various sources such as CSV, JSON, Parquet, and others.
7. [DataFrames Operations](https://github.com/martishin/pyspark-examples/blob/main/07_data_frames_operations.ipynb). Dive deeper into DataFrames operations, such as filtering, aggregating, and joining DataFrames.
8. [Working with SQL in Spark](https://github.com/martishin/pyspark-examples/blob/main/08_data_frames_sql.ipynb). Learn how to use SQL within Spark to query and manipulate DataFrames, one of Spark's key features.
