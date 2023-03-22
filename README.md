# Project3 Cloud-based Big Data Systems Project
### Project objectives
1. Use a major Big Data system to perform a Data Engineering related task
2. Example systems could be: (AWS Athena, AWS Spark/EMR, AWS Sagemaker, Databricks, Snowflake)
## Introduction
This project aims to build a cloud-based ETL Data pipeline to support data dashboard analysis.
### Goals
1. Data Ingestion — Build a mechanism to ingest data from different sources
2. Data lake — We will be getting data from multiple sources so we need centralized repo to store them
3. ETL System — We are getting data in raw format, transforming this data into the proper format
4. Scalability — As the size of our data increases, we need to make sure our system scales with it
5. Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS
6. Reporting — Build a dashboard to get answers to the question we asked earlier
### Services we will use
1. Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
2. QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.
3. AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
4. AWS Lambda: Lambda is a computing service that allows programmers to run code without creating or managing servers.
5. AWS Athena: Athena is an interactive query service for S3 that makes it easy to analyze data directly in S3 using standard SQL.
### Data we will use
The dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months.  
Dataset: https://www.kaggle.com/datasets/datasnaek/youtube-new
## Structure Diagrams
![architecture](https://user-images.githubusercontent.com/84234596/226989424-15e8e397-360f-45fd-82c6-2f7a43d4bacd.jpeg)
## Steps

## Usage
## Referennce
1. Perform advanced streaming data transformations with Apache Spark and Kafka in Azure HDInsight-Microsoft Learn<https://learn.microsoft.com/en-us/training/modules/perform-advanced-streaming-data-transformations-with-spark-kafka/>
2. Hadoop Tutorial
3. A very brief introduction to MapReduce<https://hci.stanford.edu/courses/cs448g/a2/files/map_reduce_tutorial.pdf>
