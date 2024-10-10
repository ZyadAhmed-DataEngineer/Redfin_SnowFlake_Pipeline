# Redfin_SnowFlake_Data_Pipeline

## Project Overview

This project demonstrates how to build an automated data pipeline using AWS EC2, S3, Apache Airflow, Snowflake, and Power BI to extract, process, and visualize Redfin housing market data. The primary objective is to create an efficient end-to-end ETL (Extract, Transform, Load) process that ensures seamless data flow from Redfin to Power BI for analytics and reporting.

## Pipeline Architecture

The architecture automates the entire ETL workflow, leveraging the power of cloud services and orchestration tools. 

### Here's an overview of the components involved:

Source Data: Redfin housing market data
AWS EC2: Hosts Apache Airflow to orchestrate the ETL pipeline and manage workflow scheduling
AWS S3: Storage solution for both raw and processed data
Snowflake: Cloud-based data warehouse used for storing and querying processed data
Power BI: Visualization and reporting tool for analytics and insights

## Workflow Breakdown

Data Extraction: Extract Redfin housing market data and load it into an AWS S3 bucket.
Data Orchestration: Use Apache Airflow running on an EC2 instance to automate and orchestrate the data pipeline.
Data Storage: Store the raw data in AWS S3 for backup.
Transform the data on EC2 as per business requirements.
Load the transformed data into Snowflake for querying and analysis.
Data Visualization: Visualize and analyze the housing market data in Power BI by connecting to the Snowflake data warehouse.

## Key Benefits

Automation: Apache Airflow automates the entire ETL process, ensuring data is processed consistently.
Scalability: Using AWS and Snowflake allows for scalable storage and computation, handling increasing data volumes seamlessly.
Business Insights: Power BI provides a powerful platform for data visualization, enabling stakeholders to gain actionable insights from the processed data.

## Conclusion

This data pipeline showcases how modern cloud infrastructure and tools like AWS, Apache Airflow, Snowflake, and Power BI can be combined to create an automated, scalable, and efficient solution for processing Redfin housing market data. With this setup, you can ensure that data is always up-to-date, easily accessible, and ready for analysis.