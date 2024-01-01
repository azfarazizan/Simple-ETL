
# Weather Data ETL Pipeline

# Overview

This project encapsulates an ETL (Extract, Transform, Load) pipeline designed for weather data manipulation, integrating a combination of methodologies learned from diverse YouTube tutorials. It harnesses Python, API integration, AWS services (EC2, S3), and Apache Airflow for orchestration.

# Learning Approach

The development of this ETL pipeline was primarily inspired by multiple YouTube tutorials on:

- API Integration: Learning to extract data from weather APIs by meticulously following tutorials and referring to API documentation.
  
- Data Transformation: Understanding data manipulation techniques through Python, adopting strategies demonstrated in various tutorials.

- AWS Integration: Setup and utilization of AWS services (EC2, S3) by combining insights from different sources.
  
- Apache Airflow: Grasping the concepts of DAGs and workflow orchestration through tutorials on Apache Airflow.

# Components

# Data Extraction

  - Source: Weather data obtained via API (weathermap API)

    Extraction Process:

    - Understand API documentation (include links/references)

    - Set up connections and obtain necessary API keys

# Data Transformation

  Process:

   - Python scripts for cleaning, structuring, and formatting the data

# Data Loading

  - Destination: Storage on AWS S3 bucket

    Loading Process:

     - Connection setup with S3

     - Python scripts (load.py) to transfer processed data to S3

# Orchestration

  - Tool Used: Apache Airflow

    Setup:

    - Creation of an EC2 instance

    - Connecting the instance to VSCode for development

    - Integration with Apache Airflow to orchestrate the ETL process

# Pre-requisites

  - Python 

  - Access to API service and credentials

  - AWS account with permissions for S3

  - Apache Airflow installation




