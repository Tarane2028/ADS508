# ADS508
# DiabetesInsight Inc. – Distributed Data Science Pipeline Project

## Overview

DiabetesInsight Inc. is dedicated to improving early diabetes detection by identifying key health indicators from a comprehensive dataset. This project builds a robust, cloud-based data pipeline leveraging AWS services such as S3 and SageMaker to ingest, process, and analyze health indicator data. Our aim is to enable proactive healthcare interventions by developing reliable predictive models that can accurately distinguish between individuals at risk and not at risk for diabetes.

This repository contains all code, notebooks, and documentation related to the project. It reflects the steps taken throughout the course—starting with data ingestion and exploration (Assignment 3.1), data preparation (Assignment 4.1), model training (Assignment 5.1), and culminating with future enhancements (Assignment 6.1).

## Table of Contents

- [Project Description](#project-description)
- [Data Sources](#data-sources)
- [Project Structure](#project-structure)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Future Enhancements](#future-enhancements)
- [Team Contributions](#team-contributions)
- [References](#references)
- [License](#license)

## Project Description

DiabetesInsight Inc. addresses the critical public health issue of diabetes by leveraging the Diabetes Health Indicators Dataset from Kaggle. Despite the plethora of health metrics available, clinicians often lack precise tools for early diabetes prediction. Our project builds an end-to-end, cloud-based data science pipeline to:
- Ingest and store data on AWS S3.
- Perform extensive Exploratory Data Analysis (EDA) in SageMaker Studio.
- Prepare and process the data through scrubbing, feature selection, creation, and transformation.
- Train a predictive model using SageMaker’s built-in XGBoost algorithm.
- Evaluate the model using key performance metrics.
- Propose future enhancements for integrating additional data sources, real-time analytics, and improved model explainability.

## Data Sources

- **Diabetes Health Indicators Dataset**  
  Source: [Kaggle](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset?resource=download)  
  Description: A comprehensive dataset with over 20,000 records and 22 variables including demographic, lifestyle, and clinical indicators used to predict diabetes risk.

## Project Structure
## Setup and Installation

1. **AWS Account & SageMaker Studio:**  
   Ensure you have an active AWS account with access to SageMaker Studio. The project uses SageMaker’s built-in capabilities for data ingestion, processing, and model training.

2. **Python Packages:**  
   The required Python libraries include:
   - pandas
   - NumPy
   - matplotlib
   - seaborn
   - boto3
   - scikit-learn
   - imblearn  
   
   You can install these dependencies using pip:
   ```bash
   pip install pandas numpy matplotlib seaborn boto3 scikit-learn imbalanced-learn
