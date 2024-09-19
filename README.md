### Tokyo Olympic Azure Data Engineering Project ###

## Project Overview ##
This project demonstrates a complete data engineering pipeline using various Azure tools. The goal is to ingest, store, transform, and analyze data related to the Tokyo Olympics. The final output is visualized using Power BI.

## Project Architecutre ##
![image](https://github.com/user-attachments/assets/a3a6bcff-88e8-4c8c-b8b2-bc3349ecba42)

## Data Set ##
The data set consists of five tables containing information about athletes, coaches, entries by gender, medals, and teams. The data is available in CSV formats.

## Tools Used ##

*The project leverages the following Azure services:*
1. *Azure Data Factory:* Used for data ingestion and orchestration.
2. *Azure Data Lake Storage Gen2:* Used for storing raw and transformed data.
3. *Azure Databricks:* Used for data transformation and processing.
4. *Azure Synapse Analytics:* Used for data analysis and querying.
5. *Power BI:* Used for data visualization and creating dashboards.

## Project Workflow ##
1. *Data Ingestion:*

          Data is ingested from the data source using Azure Data Factory.
          The ingested data is stored in Azure Data Lake Storage Gen2 as raw data.

2. *Data Transformation:*

          Raw data is transformed using Azure Databricks.
          The transformed data is then stored back in Azure Data Lake Storage Gen2.

3. *Data Analysis:*

           Transformed data is analyzed using Azure Synapse Analytics.
           Basic charts and analyses are performed in Azure Synapse Analytics.
4. *Data Visualization:*

           The analyzed data is visualized using Power BI to create interactive dashboards.
