# YouTube Data Engineering Project

## Overview

This end-to-end Data Engineering project focuses on ingesting, transforming, storing, and analyzing structured and semi-structured YouTube trending data. I designed the pipeline to handle growing data volume while ensuring secure, scalable, and efficient data processing in the cloud.

## Objectives

1. Data Ingestion – Ingest raw YouTube data from multiple sources
2. ETL Pipeline – Transform raw data into clean, structured formats using AWS Glue
3. Data Lake – Store and organize data in Amazon S3 as a centralized, scalable repository
4. Scalability – Ensure the architecture supports increasing data volume
5. Cloud-Based Processing – Utilize AWS cloud services to manage and process large datasets
6. Data Visualization – Build a dashboard using Amazon QuickSight to derive key insights

## AWS Services Used

1. Amazon S3 – For storing raw and processed data securely
2. AWS IAM – To manage user and service permissions securely
3. AWS Glue – For ETL jobs to clean and prepare data
4. AWS Lambda – For serverless triggers and lightweight processing
5. AWS Athena – For running SQL queries directly on data stored in S3
6. Amazon QuickSight – To visualize metrics and trends with interactive dashboards

## Dataset

This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new

## Key Outcomes

Built a cloud-native pipeline for real-time and batch processing
Centralized YouTube data in a structured data lake
Generated analytical insights by video category, region, and performance metrics
