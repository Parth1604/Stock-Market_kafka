Here’s a simpler version of the GitHub text with bullet points:

---

# Stock Market Real-Time Data Analysis

## Overview
This project builds a data pipeline to process and analyze live stock market data using **Apache Kafka** and **AWS** services.

## Technologies Used
- Python
- Apache Kafka
- AWS EC2
- Amazon S3
- AWS Glue
- Amazon Athena

## Data Pipeline Architecture
- **Python CSV App** (Producer)  
  Simulates stock market data.
- **Kafka** (on EC2)  
  Sends data in real-time.
- **Consumer**  
  Receives and processes the data.
- **Amazon S3**  
  Stores the data.
- **AWS Crawler**  
  Catalogs the data in S3.
- **AWS Glue**  
  Manages the data schema.
- **Amazon Athena**  
  Allows SQL queries on the data.

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

This version is more concise and direct while keeping the key information intact.
