# Cricket World Cup 2019 Analysis

![Cricket Icon](https://img.icons8.com/color/48/000000/cricket.png)

This repository contains code and resources for analyzing the ICC Cricket World Cup 2019 dataset. The analysis involves loading data from GitHub, performing transformations using Azure Data Factory and Azure Databricks, and storing the processed data in Azure Synapse Analytics.

## Understanding the Dataset

The dataset for the ICC Cricket World Cup 2019 Analysis can be found on Kaggle. It includes various statistics and metrics related to matches, players, teams, and more.

- [ICC Cricket World Cup 2019 Analysis Dataset](https://www.kaggle.com/code/venky73/icc-cricket-world-cup-2019-analysis)

## Architecture Diagram
![tempsnip](https://github.com/AjabNauman958/CWC-2019-Analysis/assets/114978635/85ae1cb3-7d95-4cb2-85b5-a8c154cd92b5)

## ETL Process

### Extraction

- **Data Extraction from GitHub:**
  Utilized Azure Data Factory to extract the dataset from the GitHub repository and load it into Azure Data Lake Gen 2.

### Transformation

- **Data Transformation with Azure Databricks:**
  Employed Azure Databricks to handle missing values, perform type casting, and other necessary data transformations.

### Load

- **Data Loading to Azure Storage:**
  Loaded the transformed data into Azure Data Lake Gen 2 for further processing.

## Azure Synapse Workspace Setup

1. **Azure Synapse Workspace Creation**
2. **SQL Pool Creation in Azure Synapse Workspace**
3. **Table Creation in SQL Pool**
4. **Data Ingestion Pipeline from Azure Storage into the SQL pool tables**
