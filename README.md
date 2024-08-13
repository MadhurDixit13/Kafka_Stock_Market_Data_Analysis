# Real-Time Stock Market Data Engineering with Apache Kafka

## Project Overview

This project demonstrates a comprehensive End-to-End Data Engineering pipeline focused on processing and analyzing Real-Time Stock Market Data using a combination of Apache Kafka and Amazon Web Services (AWS). The goal is to efficiently manage and analyze streaming data to gain actionable insights.

## Architecture

![Architecture Overview](Architecture.jpg)

This architecture facilitates the seamless ingestion, processing, and storage of real-time stock data, ensuring scalability, reliability, and speed across the pipeline.

## Technology Stack

- **Programming Language**: Python
- **Amazon Web Services (AWS)**:
  - **S3 (Simple Storage Service)**: For durable and scalable data storage.
  - **Athena**: To query data directly from S3 using SQL.
  - **Glue Crawler**: For automated schema discovery and cataloging.
  - **Glue Catalog**: To maintain and manage metadata for the datasets.
  - **EC2 (Elastic Compute Cloud)**: For running scalable Kafka brokers and other services.
- **Apache Kafka**: For real-time data streaming and message queuing.

## Screenshots

![AWS S3 Bucket](s3_bucket.jpg)

![AWS Athena](athena.jpg)

## Dataset

This project is focused on the operational aspects of Data Engineering, specifically building and managing the data pipeline. You can use any stock market dataset that suits your needs for testing and demonstration purposes.

## Author

Madhur Dixit

## Status 

Completed