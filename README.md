# Insurance Linear Regression Project

This project implements a linear regression model to predict insurance charges based on various features such as BMI, salary, consultations, hospital expenditure, and number of past hospitalizations.

## Project Overview

- **Goal**: Predict insurance charges using linear regression.
- **Techniques Used**: 
  - Data preprocessing (handling outliers and encoding categorical features)
  - Train-test split
  - Model evaluation with R² score
  
## Dataset

- The dataset contains information about individuals' health-related features and insurance charges.
- **Preprocessing Steps**:
  - Handled missing and duplicate data.
  - Removed outliers using IQR (Interquartile Range) method.
  - Applied **Label Encoding** for categorical features.

## Model Performance

- **Algorithm Used**: Linear Regression
- **Performance**: Achieved an R² score of **95.81%**.
- The dataset size was small, leading to a high score. Hyperparameter tuning was avoided to prevent overfitting.
