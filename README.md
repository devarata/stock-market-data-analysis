# Stock Market Kafka Real-Time Data Engineering Project

## Introduction

In this comprehensive project, we dive deep into an End-To-End Data Engineering process focused on Real-Time Stock Market Data, harnessing the power of Apache Kafka.

To seamlessly integrate and process this data, we employ a diverse tech stack ranging from Python to various services from Amazon Web Services (AWS) and, of course, the real-time event streaming platform, Apache Kafka.

## Technologies Used

### Programming Language

- **Python**: Chosen for its versatility and extensive libraries which aid in data engineering tasks.

### Amazon Web Service (AWS) 

Several AWS services play pivotal roles in the ingestion, storage, processing, and querying of our data.

- **S3 (Simple Storage Service)**: Used as a data lake, providing scalable object storage for our stock market data.
  
- **Athena**: An interactive query service that allows us to analyze data in Amazon S3 using standard SQL.
  
- **Glue Crawler**: This service is used to populate the AWS Glue Data Catalog with tables. It's particularly useful for extracting metadata and creating table definitions.
  
- **Glue Catalog**: A centralized metadata repository, Glue Catalog makes data discoverable and manageable.
  
- **EC2 (Elastic Compute Cloud)**: Provides virtual servers in the cloud, ensuring the scalable computation capacity.

### Other Technologies

- **Apache Kafka**: A distributed event streaming platform that can handle real-time data efficiently. Perfect for our stock market data processing needs.



