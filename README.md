# Credit Card Fraud Detection
This repository contains a Python script for credit card fraud detection using machine learning techniques. The code analyzes a dataset of credit card transactions and identifies fraudulent transactions. It includes data preprocessing, visualization, undersampling, model training, and evaluation steps.


# Introduction
Credit card fraud is a significant problem in the banking industry, and detecting fraudulent transactions is crucial for protecting consumers and financial institutions. This Python script uses machine learning to identify potential fraudulent transactions based on historical transaction data.


# Data
The dataset used for this project is called "creditcard.csv." It contains credit card transaction data, including features that have undergone Principal Component Analysis (PCA) transformation, as well as "Time" and "Amount" columns. The dataset has been preprocessed and scaled for analysis.

# Exploratory Data Analysis
Before building the fraud detection model, the code performs exploratory data analysis (EDA) to understand the dataset's characteristics. This includes visualizing class distribution, time, and amount distributions, and identifying outliers.

# Data Preprocessing
Data preprocessing steps involve handling outliers and standardizing features using the StandardScaler. The code also performs undersampling to balance the class distribution between normal and fraudulent transactions.

# Model
A logistic regression model is used for fraud detection. It is trained on the preprocessed data and used to make predictions.

# Evaluation
The model's performance is evaluated using accuracy, precision, recall, and F1-score metrics. These metrics provide insights into how well the model can detect fraudulent transactions.
