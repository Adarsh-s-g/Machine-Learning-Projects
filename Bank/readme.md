# Bank loan Prediction using Logistic Regression

This project implements a Logistic Regression model to predict whether a bank customer will churn (leave the bank) or not, based on various customer data. The notebook explores the dataset, performs feature engineering, and trains a machine learning model to classify customers.

## Project Overview

The project is divided into the following sections:

1. **Data Preprocessing**:
   - Data cleaning and handling missing values.
   - Feature encoding for categorical variables.
   - Train-test split.

2. **Model Training**:
   - Logistic Regression is used as the primary model.
   - Evaluation metrics like confusion matrix, precision, recall, and F1-score are used to assess the model's performance.

3. **Model Evaluation**:
   - Confusion matrix for prediction analysis.
   - Classification report for detailed evaluation of precision, recall, and F1-score.

## Dataset

The dataset used contains bank customer information, including various features such as:
- Customer age
- Account balance
- Credit score
- Marital status
- Number of products
- ...and more.

The target variable is whether the customer will churn (leave the bank) or not.

## Project Files

- **`Bank_logistic_regression.ipynb`**: Jupyter notebook containing the full analysis, model training, and evaluation steps.

## Model Performance

The Logistic Regression model achieves the following performance metrics:

- **Accuracy**: 90.6%
- **Precision**: 
  - Class 0 (Non-churners): 0.99
  - Class 1 (Churners): 0.84
- **Recall**:
  - Class 0: 0.82
  - Class 1: 0.99
- **F1-Score**:
  - Class 0: 0.90
  - Class 1: 0.91

## Requirements

To run this notebook, you'll need the following Python packages:

```bash
pip install pandas numpy scikit-learn matplotlib
