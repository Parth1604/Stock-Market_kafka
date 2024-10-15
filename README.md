*Stock Market Real-Time Data Analysis
*Overview
The Stock Market Real-Time Data Analysis project demonstrates how to build a data pipeline that processes and analyzes live stock market data using Apache Kafka and AWS services.

*Technologies Used
-Python
-Apache Kafka
-AWS EC2
-Amazon S3
-AWS Glue
-AWS Athena
*Data Pipeline Architecture
-Python CSV App (Producer)
-Kafka (on EC2)
-Consumer
-Amazon S3 (Storage)
-AWS Crawler (Data Cataloging)
-AWS Glue (Schema Management)
-Amazon Athena (Data Querying)

*How It Works
Simulates stock market data from a CSV file.
Sends data to Kafka running on an AWS EC2 instance.
Stores the data in an Amazon S3 bucket.
Uses AWS Crawler to catalog the data and AWS Glue for schema management.
Query the data using AWS Athena.
Key Learnings
Hands-on experience with Kafka and AWS integration.
Understanding of real-time data processing and storage.
