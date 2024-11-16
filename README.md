# Pizza-Company-Performance-Analysis-on-Azure

This project demonstrates an end-to-end data engineering solution for analyzing a pizza company's performance using Microsoft Azure services. The solution encompasses data ingestion, transformation, and visualization to derive actionable business insights.

## Project Overview

The primary objective is to build a scalable data pipeline that processes sales data and provides comprehensive performance reports. The project utilizes the following Azure services:

- **Azure Data Factory**: Orchestrates data movement and workflow scheduling.
- **Azure Databricks**: Performs data transformation and analysis.
- **Azure Data Lake Storage**: Serves as the storage repository for raw and processed data.
- **Power BI**: Visualizes data through interactive dashboards.



![Azure Data Engineering Pipeline (1)](https://github.com/user-attachments/assets/2532e022-8146-4587-90dd-e1e86a6a846f)


## Repository Contents

- `Azure_Data_Engineer_Project.ipynb`: Jupyter Notebook detailing the data engineering workflow, including data ingestion, transformation, and loading processes.
- `Pizza_Sales_Reporting.pbit`: Power BI template file for generating interactive sales performance reports.
- `pizza_sales.csv`: Sample dataset containing pizza sales records used for analysis.
- `README.md`: Project documentation and overview.

## Getting Started

To replicate or extend this project, follow these steps:

1. **Clone the Repository**: Download the project files to your local machine.
   ```bash
   git clone https://github.com/cyber-prags/Pizza-Company-Performance-Analysis-on-Azure.git
   
![image](https://github.com/user-attachments/assets/69ff12bb-314a-4118-b842-b4a0247757c6)

## Set Up Azure Services

- **Azure Data Factory**: Create a Data Factory instance to manage data workflows.
- **Azure Databricks**: Set up a Databricks workspace for data processing tasks.
- **Azure Data Lake Storage**: Establish a storage account to hold raw and processed data.

## Configure Data Ingestion

- Use Azure Data Factory to create pipelines that ingest data from various sources into Azure Data Lake Storage.

## Data Transformation

- Utilize Azure Databricks to process and transform the ingested data as outlined in the `Azure_Data_Engineer_Project.ipynb` notebook.

## Data Visualization

- Open the `Pizza_Sales_Reporting.pbit` file in Power BI Desktop to visualize the processed data through interactive dashboards.

## Prerequisites

- **Azure Subscription**: Required to access Azure services.
- **Power BI Desktop**: Needed to open and edit the Power BI template file.
- **Jupyter Notebook Environment**: To run and modify the provided notebook.

## Usage

This project serves as a template for building data engineering solutions on Azure. It can be customized to fit specific business requirements by modifying the data processing logic, integrating additional data sources, or enhancing the visualization components.


![image](https://github.com/user-attachments/assets/74fb9cfa-ddb4-4c12-b5aa-7a33da6d5df1)



![image](https://github.com/user-attachments/assets/d38e7402-4f71-4383-ba63-4be2ee2d72b2)
