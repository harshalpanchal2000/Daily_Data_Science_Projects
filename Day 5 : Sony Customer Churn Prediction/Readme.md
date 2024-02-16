# Sony Customer Churn Prediction Project Documentation

## Introduction
This project aims to predict customer churn for a telecom company using machine learning techniques. The dataset provided contains information about customers, including features such as state, phone number, international plan, voice mail plan, and various usage metrics.

### Tasks
The project involves the following tasks:
1. Exploratory Data Analysis (EDA) to gain insights from the dataset.
2. Data preprocessing, including handling missing values, encoding categorical variables, and feature engineering.
3. Splitting the dataset into train and test sets for model evaluation.
4. Building predictive models to identify customers likely to churn.
5. Establishing metrics to evaluate model performance.
6. Discussing potential deployment issues with the model.

## Dataset Overview
- The dataset contains information about telecom customers, including features such as state, phone number, international plan, voice mail plan, and usage metrics.
- It includes a target variable indicating whether a customer churned or not.

## Exploratory Data Analysis (EDA)
- Checked basic structure and statistics of the dataset.
- Examined missing values and duplicate rows (none found).
- Explored data types and identified non-numeric columns.
- Visualized distributions and class ratios to understand the data better.
- Conducted correlation analysis to identify relationships between features and the target variable.

## Data Preprocessing
- Encoded categorical features such as international plan and voice mail plan into numeric values (0 and 1).
- Dropped irrelevant features such as phone number and state.
- Performed feature scaling and split the dataset into train and test sets.

## Model Building and Evaluation
- Explored various classifiers, including K-Nearest Neighbors, Support Vector Machines, Decision Trees, Random Forests, and others.
- Evaluated model performance using accuracy and F1-score.
- Compared the performance of traditional machine learning models with a deep learning model (Artificial Neural Network).
- Chose XGBoost as the final model due to its high accuracy and F1-score.

## Deployment Issues
- Discussed potential deployment issues such as data drift and concept drift.
- Emphasized the importance of monitoring model performance in production and updating models periodically.

## Conclusion
This project demonstrated the process of predicting customer churn for a telecom company using machine learning techniques. By exploring the dataset, preprocessing the data, building predictive models, and evaluating their performance, we identified important features and developed a reliable model for predicting churn. Additionally, we discussed potential deployment issues and strategies for maintaining model performance in production.

Thank you for reading this project documentation!
