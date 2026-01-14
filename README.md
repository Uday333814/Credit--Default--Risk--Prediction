# Credit Default Risk Prediction Using Machine Learning

## Project Overview
This project focuses on building an end-to-end machine learning system to predict whether a customer is likely to default on a loan. The model uses demographic, financial, and credit-related features to support data-driven loan approval decisions and reduce financial risk.

## Problem Statement
Loan defaults pose a major financial risk for banks and lending institutions. Traditional credit evaluation methods often rely on manual rules and limited indicators, which fail to capture complex patterns in customer behavior. This project aims to address this problem using machine learning techniques.

## Objective
The main objective of this project is to predict whether a customer is likely to default on a loan.

This system helps financial institutions to:
- Reduce credit risk
- Identify high-risk customers early
- Make accurate and data-driven loan approval decisions

## Dataset Description
The dataset contains customer demographic and financial information such as:
- Income
- Savings
- Monthly expenses
- Loan amount
- Credit score
- Employment details
- Loan history

Target Variable:
- 0 → No Default
- 1 → Default

## Methodology
The project follows a complete end-to-end machine learning workflow:
- Data loading and inspection
- Exploratory Data Analysis (EDA)
- Handling missing values using imputation
- Outlier detection using IQR method
- Feature scaling and encoding
- Train-test split
- Model training
- Model evaluation and comparison

## Models Implemented
The following classification models were implemented and compared:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- XGBoost

## Model Evaluation
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

### Model Performance Summary
- Logistic Regression → ~93%
- Decision Tree → ~94%
- Random Forest → ~93%
- SVM → ~89–90%
- XGBoost → ~95–96% (Best Model)

## Conclusion
An end-to-end Credit Default Risk Prediction system was successfully developed using machine learning techniques. Among all models, XGBoost achieved the best performance with high accuracy and balanced precision and recall. This demonstrates the effectiveness of machine learning in predicting credit default risk and improving lending decisions.

## Business Impact
This model can help financial institutions to:
- Identify high-risk customers in advance
- Reduce loan default rates
- Improve credit approval decisions
- Minimize financial losses
- Ensure fair and consistent lending

## Future Improvements
Although the current model achieved strong performance, it can be further improved:
- Extensive hyperparameter tuning using GridSearchCV with higher computational resources
- Handling class imbalance using SMOTE
- Adding model explainability using SHAP values
- Evaluating performance using ROC-AUC and Precision-Recall curves
- Deploying the model as a web application using Flask or FastAPI

## Final Note
This project demonstrates the ability to:
- Handle real-world
