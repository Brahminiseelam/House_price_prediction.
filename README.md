Project Overview
This project focuses on predicting residential property prices using supervised machine learning techniques. The objective was to build a robust regression pipeline capable of capturing complex patterns in structured housing data while ensuring strong generalization performance through cross-validation.
The project follows an end-to-end ML workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and model comparison.

Dataset Information
Total Records: 20,640 rows
Total Features: 10 numerical features
Target Variable: Median House Value
Data Type: Structured tabular dataset

Problem Statement
The goal is to accurately predict house prices based on given features and determine which regression model performs best. The project emphasizes:
Model comparison
Handling non-linear relationships
Cross-validation for robustness
Performance improvement over baseline models

Exploratory Data Analysis (EDA)
Analyzed feature distributions and correlations
Identified skewness in income-related features
Checked for multicollinearity
Visualized relationships between features and target variable
Examined outliers and data spread

Data Preprocessing
Checked and handled missing values
Applied feature scaling where necessary
Split dataset into training and test sets
Used cross-validation for model evaluation

Models Implemented
The following regression models were trained and compared:
Linear Regression (Baseline Model)
Ridge Regression
Lasso Regression
Random Forest Regressor
Histogram Gradient Boosting Regressor

Model Performance
Baseline Model – Linear Regression
R² Score: 0.625
RMSE: 70,059
The baseline model showed moderate predictive power but struggled to capture complex relationships.

Best Model – Histogram Gradient Boosting (HistGB)
✅ Cross-Validation RMSE: 48,190.81
✅ Cross-Validation R² Score: 0.826
