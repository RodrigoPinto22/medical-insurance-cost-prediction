# Medical Insurance Cost Prediction

## Overview

This project investigates the factors associated with medical insurance charges and develops predictive models using linear regression techniques.

The analysis combines exploratory data analysis, statistical inference, regression diagnostics, and predictive evaluation to understand how demographic and lifestyle factors relate to insurance costs.

## Objectives

- Explore relationships between predictors and insurance charges.
- Fit and interpret simple and multiple linear regression models.
- Perform hypothesis testing and construct confidence intervals.
- Assess regression assumptions through diagnostic analysis.
- Evaluate predictive performance on unseen data.

## Dataset

The dataset contains information on:

- Age
- Sex
- BMI
- Number of children
- Smoking status
- Region
- Insurance charges

## Key Findings

- Smoking status was the strongest predictor of insurance charges.
- Age and BMI were positively associated with insurance costs.
- A significant interaction was identified between BMI and smoking status.
- The final model explained a large proportion of the variability in insurance charges and achieved strong predictive performance on the test set.

## Methods

- Exploratory Data Analysis (EDA)
- Simple Linear Regression
- Multiple Linear Regression
- Confidence Intervals and Hypothesis Testing
- Regression Diagnostics
- Interaction Effects
- Train-Test Evaluation
- RMSE, MAE, and R²

## Results

Final model performance on the test set:

| Metric | Value |
|----------|----------|
| R² | 0.886 |
| MAE | 2828.97 |
| RMSE | 4572.81 |

## Repository Structure

├── notebook.ipynb  
├── medical_insurance.csv  
└── README.md

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-Learn
