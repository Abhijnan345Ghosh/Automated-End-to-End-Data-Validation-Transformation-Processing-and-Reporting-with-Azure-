
# Automated End to End Data Validation, Transformation, Processing and Reporting with Azure Data Factory,Azure Functions and Databricks, Azure DataLake, Power Bi

## Problem Statement

The objective of the project is to design and implement an automated, event-driven data pipeline using Azure services which will validate and process incoming data. Ensures the integrity and correctness of data files as they are uploaded to Azure Data Lake.
Seamlessly transfer validated data to Azure Data Lake Storage.Utilized Azure Databricks to transform data through multiple stages (bronze, silver, gold) to ensure data quality and readiness for analysis. Integrate the final transformed data with Power BI to create insightful and actionable reports based on business requirements.

## Architecture

![architecture_Azure](https://github.com/user-attachments/assets/79068ee0-e1ea-4610-bbb4-7526283d3d14)

## Technologies Used
  -   Azure DataLake
  -   Azure Functions
  -   Azure Event Based trigger
  -   Azure Databricks
  -   Azure Data Factory
  -   Power BI
##  Programming Language
  -   Python
  -   PySpark

## Step Followed

  - Implemented an **event-based trigger** to detect when the file is loaded to Azure DataLake
  - Developed an **Azure Function** using Python to validate file that is loaded in the **Azure Storage**
  - Seamlessly transfer the validated file to **Azure Data Lake Storage**
  - Utilized **Azure Data Factory**'s ForEach activity to iterate over files for transformation.
  - Employed **Azure Databricks** notebooks to transform data through multiple layers:
     - **Bronze Layer**: Raw data ingestion.
     - **Silver Layer**: Data cleansing and enrichment.
     - **Gold Layer**: Aggregated and refined data for analysis. Also created the Fact and Dimension tables 
  -  Integrated the final transformed data into **Power BI** to create insightful reports based on business requirements  


## Data Model

![data_model](https://github.com/user-attachments/assets/f23d2f7b-d2d0-4767-a8da-222462a1969e)


## Pipeline created in Azure Data Factory

![pipeline](https://github.com/user-attachments/assets/1fe4f5a1-2b59-4a03-98b1-df3bbc191c76)


