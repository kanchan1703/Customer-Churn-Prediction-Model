# Customer Churn Prediction: Model Comparison & Evaluation

## Introduction
Customer churn refers to the loss of customers over time, which impacts business revenue and growth. Predicting churn helps companies take proactive measures to retain customers. This project implements machine learning models to analyze and predict customer churn based on various customer behavior and service usage patterns.

## Dataset
The dataset consists of customer records with multiple attributes, including demographic information, account details, and usage metrics. The target variable is a binary label indicating whether a customer has churned (1) or not (0).

## Project Workflow
- **Data Preprocessing:** Handling missing values, encoding categorical features, and normalizing numerical data.
- **Exploratory Data Analysis (EDA):** Identifying key factors contributing to churn.
- **Feature Selection:** Selecting relevant features to improve model efficiency.
- **Model Training & Hyperparameter Tuning:** Implementing and optimizing multiple classification models using GridSearchCV.
- **Model Evaluation:** Comparing models based on accuracy, precision, recall, F1-score, and AUC-ROC.

## Models Used & Selection Criteria
- **Logistic Regression:** Baseline model for interpretability.
- **Decision Tree:** Captures non-linear relationships and feature importance.
- **Random Forest:** Reduces overfitting by aggregating multiple decision trees.
- **XGBoost:** Boosting-based model for improved performance and handling class imbalance.

These models were selected based on their ability to balance interpretability, performance, and generalization across different scenarios.

## Results & Conclusion
The models were evaluated using multiple metrics, with **Random Forest and XGBoost** demonstrating the best trade-off between accuracy and robustness. The final selection was based on a balanced evaluation of precision, recall, and AUC-ROC scores.


