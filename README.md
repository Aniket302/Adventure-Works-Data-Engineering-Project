# Adventure-Works-Data-Engineering-Project

This repository includes data engineering project made using Azure tools - Azure Data Factory, Azure Databricks, and Azure Snyapse Analytics. It utilizes the [AdventureWorks Dataset](https://www.kaggle.com/datasets/ukveteran/adventure-works) which includes product sales and customer information over a period of 3 years.

<img width="1528" height="355" alt="aaaaaaaaaaaaa" src="https://github.com/user-attachments/assets/98284557-1aef-497c-9da0-4315525fabfe" />


### Bronze Layer - Raw Data Ingestion using Azure Data Factory

Creating a resource group with the following resources:

<img width="1920" height="628" alt="image" src="https://github.com/user-attachments/assets/2e60caae-b7a6-4bd7-b87f-ad07b30aa840" />

Creating a datapipeline in ADF to run a for each loop to fetch file (total 10 files) from github (HTTP source) to Azure Data lake inside bronze container

<img width="1908" height="790" alt="image" src="https://github.com/user-attachments/assets/6ecbd101-5dcc-4960-9c10-4724d23a6656" />

<img width="1920" height="802" alt="image" src="https://github.com/user-attachments/assets/6956f1cd-7e49-40c4-9661-3aa027fe01e3" />

### Silver Layer - Performing data cleaning, transformations

<img width="1914" height="914" alt="image" src="https://github.com/user-attachments/assets/d39816dd-ba6a-4efd-9ab2-2ad882074b3a" />

### Gold Layer 

<img width="1917" height="391" alt="image" src="https://github.com/user-attachments/assets/ca9d40db-db1a-4b61-b6c1-98c1aac598d5" />

<img width="1920" height="998" alt="image" src="https://github.com/user-attachments/assets/44be5cd7-e142-490b-9a64-b827d62d5c70" />


