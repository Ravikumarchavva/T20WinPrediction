# T20WinPrediction

**T20WinPrediction** is a student project that uses data science and machine learning to predict the probability of a team winning a T20 cricket match. The goal is to accurately forecast match outcomes using advanced analytics and machine learning models.

## Project Overview

This project covers the entire machine learning lifecycle, from data collection to model deployment, following industry-standard practices. Key steps include:

- **Data Collection**: Match data gathered from multiple sources and stored in Azure Blob Storage.
- **Data Processing & Analysis**: Leveraged services like Azure Data Factory, Databricks, Synapse Analytics, and ML Studio to clean, transform, and analyze the data.
- **Model Development**: Built machine learning models to predict match outcomes, using historical match data.
- **Deployment**: Created a Docker image of the model and deployed it using FastAPI on Google Cloud Run for serverless hosting.
- **Reporting**: Generated reports and visualizations using Power BI to provide insights into the model’s performance and predictions.

## Technologies Used

- **Azure Services**:
  - Azure Blob Storage (for data storage)
  - Azure Data Factory (for data pipelines)
  - Azure Databricks (for data preprocessing and analysis)
  - Azure Synapse Analytics (for data integration)
  - Azure ML Studio (for model training and management)
  
- **Google Cloud**: 
  - Google Cloud Run (for deployment)
  
- **FastAPI**: Used to build the backend API for model serving.
- **Docker**: Containerized the machine learning model for scalable deployment.
- **Power BI**: Created reports for visual analysis of the model’s predictions.
