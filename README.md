# Credit Score Prediction

## Overview
This project focuses on predicting credit scores using machine learning techniques. The primary objective is to develop a machine learning model to predict whether a user will pay on time or face issues with their payment.
Metrics used in this project are ROC-AUC, Accuracy and precission. The minimun od good metrics should be achieve is 60 %.

## Table of Contents
- [Project Description](#project-description)
- [Technologies Used](#technologies-used)
- [Dataset Description](#dataset-description)
- [Project Workflow](#project-workflow)
- [Model Evaluation](#model-evaluation)
- [Conclusions](#conclusions)
- [Getting Started](#getting-started)
- [Acknowledgments](#acknowledgments)

## Project Description
The notebook includes an end-to-end pipeline for predicting credit scores. Key steps include:
- Data exploration and visualization
- Data preprocessing (e.g., handling missing values and encoding categorical variables)
- Model training and evaluation using multiple algorithms

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset Description
The dataset contains features relevant to credit scoring, such as:
- **Demographic Information**: Age, income, employment status
- **Financial Data**: Debt-to-income ratio, credit history, loan amounts
- **Target Variable**: Credit score classification (e.g., good, average, poor)

## Project Workflow
1. **Importing Libraries**: Load essential Python libraries.
2. **Loading and Inspecting Data**: Check for missing values, data types, and distributions.
3. **Preprocessing**:
   - Handle missing values
   - Encode categorical variables
   - Normalize numerical features
4. **Exploratory Data Analysis**:
   - Visualize distributions
   - Analyze correlations between features
5. **Feature Selection**: Identify significant features using statistical methods.
6. **Model Building**:
   - Train multiple machine learning models (e.g., Logistic Regression, Random Forest)
   - Use cross-validation for robust performance evaluation
7. **Model Evaluation**: Assess models using metrics such as accuracy, precission, and roc_auc
8. **Hyperparameter tunning** : Using gridSearch to tune the parameter for each Algorithm 
## Evaluation
The models were evaluated based on their ability to classify credit scores accurately. Results for key models:
- Logistic Regression: High interpretability, moderate accuracy, fit accuracy
- Random Forest: High accuracy, overfitting for each metrics

## Conclusions
- Feature engineering significantly improved model accuracy.
- Random Forest emerged as the best-performing model.
- Insights from EDA highlighted key factors influencing credit scores.

## Getting Started
To run this project:
1. Clone the repository and navigate to the project folder.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Open the notebook and follow the workflow outlined above.

## Acknowledgments
Special thanks to open-source contributors and dataset providers for making this project possible.



