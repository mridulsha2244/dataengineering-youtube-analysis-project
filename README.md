#🎥 YouTube Data Engineering Project

##📌 Overview

This end-to-end Data Engineering project focuses on ingesting, transforming, storing, and analyzing structured and semi-structured YouTube trending data. I designed the pipeline to handle growing data volume while ensuring secure, scalable, and efficient data processing in the cloud.

##🎯 Objectives

Data Ingestion – Ingest raw YouTube data from multiple sources
ETL Pipeline – Transform raw data into clean, structured formats using AWS Glue
Data Lake – Store and organize data in Amazon S3 as a centralized, scalable repository
Scalability – Ensure the architecture supports increasing data volume
Cloud-Based Processing – Utilize AWS cloud services to manage and process large datasets
Data Visualization – Build a dashboard using Amazon QuickSight to derive key insights

##☁️ AWS Services Used

Amazon S3 – For storing raw and processed data securely
AWS IAM – To manage user and service permissions securely
AWS Glue – For ETL jobs to clean and prepare data
AWS Lambda – For serverless triggers and lightweight processing
AWS Athena – For running SQL queries directly on data stored in S3
Amazon QuickSight – To visualize metrics and trends with interactive dashboards

##📊 Dataset

The project uses the YouTube Trending Videos Dataset from Kaggle. This dataset contains daily stats for trending videos across multiple countries, including:

Video title, channel, publish time, tags, views, likes, dislikes, comments
Regional category ID (mapped from JSON metadata)

##✅ Key Outcomes

Built a cloud-native pipeline for real-time and batch processing
Centralized YouTube data in a structured data lake
Generated analytical insights by video category, region, and performance metrics
