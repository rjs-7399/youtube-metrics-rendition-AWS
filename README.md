# youtube-metrics-rendition

This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured YouTube videos data based on the video categories and the trending metrics.

# Project Goals

1. Data Ingestion — Build a mechanism to ingest data from different sources
2. ETL System — We are getting data in raw format, transforming this data into the proper format
3. Data lake — We will be getting data from multiple sources so we need centralized repo to store them
4. Scalability — As the size of our data increases, we need to make sure our system scales with it
5. Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS
6. Reporting — Build a dashboard to get answers to the question we asked earlier

# Services used

1. AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
2. AWS Lambda: Lambda is a computing service that allows programmers to run code without creating or managing servers.
3. AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.
4. Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
5. AWS IAM: This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.
6. QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.

# Dataset used

This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new

# Project architecture

![architecture](https://github.com/rjs-7399/youtube-metrics-rendition/assets/38734146/ec188046-129f-4235-98fe-98dbbf2299f4)

# Results after analyzing data on different parameters

<img width="868" alt="Screenshot 2023-09-30 at 2 11 19 PM" src="https://github.com/rjs-7399/youtube-metrics-rendition/assets/38734146/fef9b3de-ae79-449e-a8c1-cedc99834d76">


