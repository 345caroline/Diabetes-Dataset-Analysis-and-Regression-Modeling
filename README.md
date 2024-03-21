# Diabetes Dataset Analysis and Regression Modeling

## Overview
This project involves a comprehensive analysis and modeling of the diabetes dataset available from sklearn, focusing on exploring data relationships, preprocessing for regression modeling, and evaluating the performance of various regression models.

## Dataset
The dataset comprises 442 samples with 10 feature variables each, representing different medical measurements relevant to diabetes progression.

## Objectives
- Explore the diabetes dataset.
- Determine feature relationships using a scatter matrix.
- Preprocess the data for regression modeling.
- Develop and evaluate regression models:
  - Linear Regression
  - Polynomial Regression
  - Ridge Regression
  - Lasso Regression
  - ElasticNet Regression

## Key Findings
- **Data Shape**: 442 samples, 10 features.
- **Target Range**: 25 to 346.
- **Feature Range**: Approximately -0.15 to 0.15.
- **Correlations**: Strongest correlations found with BMI, S5 (triglycerides levels), and BP (average blood pressure).

## Model Performance
- **Linear Regression** showed consistent performance.
- **Polynomial Regression** indicated high variance initially, stabilizing with more data.
- **Ridge Regression** balanced bias and variance effectively.
- **Lasso Regression** favored sparsity, with a risk of underfitting.
- **ElasticNet Regression** offered a balanced performance, combining L1 and L2 regularization.

## Conclusion
The analysis and modeling provided insights into the diabetes progression and the effectiveness of various regression models. Learning curves for each model helped diagnose potential bias or variance issues, guiding further improvements.

