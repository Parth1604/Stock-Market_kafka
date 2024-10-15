Here’s a simpler version of the text without bullet points for **Technologies Used** and **Data Pipeline Architecture**:

---

# Stock Market Real-Time Data Analysis

## Overview
This project builds a data pipeline to process and analyze live stock market data using **Apache Kafka** and **AWS** services.

## Technologies Used
The project makes use of the following technologies: **Python**, **Apache Kafka**, **AWS EC2**, **Amazon S3**, **AWS Glue**, and **Amazon Athena**.

## Data Pipeline Architecture
The pipeline starts with a Python CSV app that simulates stock market data. The data is sent to Kafka, running on an EC2 instance, which handles real-time streaming. A consumer reads this data and stores it in Amazon S3. AWS Crawler catalogs the data, and AWS Glue manages its schema. Finally, you can query the data using Amazon Athena.

## How It Works
1. Data is simulated from a CSV file using Python.
2. The data is sent to Kafka on EC2.
3. The consumer reads the data and stores it in Amazon S3.
4. AWS Crawler and Glue organize the data and schema.
5. Data can be queried in Athena using SQL.

## Key Learnings
- Learned how to integrate Kafka with AWS.
- Gained experience with real-time data processing and storage.

---

This keeps the explanation simple while grouping the sections into clear paragraphs without bullet points.
