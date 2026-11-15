
# Regression Models Comparison
**Name:** Sabrin Alam  
**Date:** November 15, 2026

## Overview

This project focuses on comparing six different regression models for predicting real estate property prices using Python and Scikit-learn.

The objective is to evaluate model performance, compare prediction errors, and understand the impact of regularization and overfitting.

## Regression Models Implemented

1. Ordinary Least Squares (OLS) Linear Regression
2. Polynomial Regression (Degree 2)
3. Ridge Regression (L2 Regularization)
4. Lasso Regression (L1 Regularization)
5. ElasticNet Regression (L1 + L2 Regularization)
6. K-Nearest Neighbors (KNN) Regressor

## Workflow

- Dataset loading and inspection
- Missing value verification
- Feature selection
- 80/20 Train-Test Split
- Feature Standardization
- Training six regression models
- Model performance evaluation
- Comparative analysis using evaluation metrics
- Data visualization

## Evaluation Metrics

- Training R² Score
- Test R² Score
- Generalization Gap
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## Key Findings

- Lasso Regression achieved the highest Test R² score of approximately 0.98303.
- OLS, Ridge, and Lasso showed almost identical performance.
- KNN demonstrated signs of overfitting.
- Regularization helped control model complexity and feature importance.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Repository Contents

- Assignment-7_Solution_Sabrin_Alam.ipynb
- README.md

## Learning Outcomes

Through this assignment, I gained practical experience in regression modeling, feature standardization, model evaluation, regularization techniques, overfitting analysis, and performance visualization.
