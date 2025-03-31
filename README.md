# Tokyo Olympic Azure Data Engineering Project

## Overview
This project is inspired by Darshil Parmar's data engineering workflow for the Tokyo Olympics dataset. It leverages Microsoft Azure services to build a data pipeline for efficient data processing and analytics. The key Azure services used include:

- **Azure Data Factory**: Orchestrates data movement and transformation.
- **Azure Databricks**: Performs data processing using Apache Spark.
- **Azure Storage Account**: Stores raw and processed data.
- **App Registration**: Manages authentication and authorization.

## Technologies Used
- **Azure Data Factory**
- **Azure Databricks**
- **Apache Spark**
- **Azure Storage Account**
- **Azure Active Directory (App Registration)**
- **Python (PySpark)**

## Project Workflow
1. **Data Ingestion**:
   - The Tokyo Olympics dataset is fetched and stored in Azure Storage Account.
   - Data Factory pipelines automate the ingestion process.

2. **Data Processing**:
   - Databricks and Spark are used for ETL (Extract, Transform, Load) operations.
   - Data cleansing, transformation, and aggregation are performed.

3. **Data Storage**:
   - Processed data is stored back in Azure Storage Account for further analysis.

4. **Security & Authentication**:
   - App Registration ensures secure access control to Azure resources.

## Setup Instructions
1. Clone this repository.
2. Set up an **Azure Storage Account** and create a container for data storage.
3. Configure **Azure Data Factory** with necessary pipelines for data ingestion.
4. Set up **Databricks Workspace** and link it to the storage account.
5. Register an application in **Azure Active Directory** for authentication.
6. Use **PySpark in Databricks** to process and analyze the data.

## Link to Project
[Databricks Notebook](https://adb-1133437905082428.8.azuredatabricks.net/editor/notebooks/2384745928248331?o=1133437905082428)

## Future Enhancements
- Implement real-time streaming with **Azure Event Hubs**.
- Automate the entire workflow using **Azure Logic Apps**.
- Integrate Power BI for interactive visualizations.

## Author
Barkha Jha

---



