
# Loan Default Prediction using Machine Learning

This is an acadamic project which aims to predict loan defaults using various machine learning models. The objective is to identify potential defaulters early, which can help financial institutions manage risk and make informed lending decisions. Extensive experimentation has been conducted to explore various aspects of machine learning for a deeper understanding.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Description](#data-description)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Conclusion](#conclusion)

## Project Overview

This project involves building a machine learning model to predict whether a borrower will default on a loan. The process includes data preprocessing, feature engineering, model selection, hyperparameter tuning, and model evaluation.

## Data Description

The dataset used for this project includes various features related to borrower information and loan details. Key features include:

- **Loan Amount**: The amount of money borrowed.
- **Term**: The loan repayment term.
- **Interest Rate**: The interest rate of the loan.
- **Employment Length**: The number of years the borrower has been employed.
- **Credit Score**: The credit score of the borrower.
- **Annual Income**: The annual income of the borrower.
- **Loan Purpose**: The purpose of the loan.

## Feature Engineering

Several feature engineering techniques were applied to improve model performance, including:

- Handling missing values.
- Encoding categorical variables.
- Scaling numerical features.
- Creating new features from existing ones to capture more information.

## Modeling

Multiple machine learning models were trained and evaluated:

- **Logistic Regression with Polynomial Features**: This model was enhanced with ridge regularization.
- **Voting Classifier**: An ensemble model that combines predictions from multiple base models.
- **Random Forest Classifier**: A tree-based ensemble model.
- **XGBoost Classifier**: An advanced gradient boosting model.

## Evaluation

The models were evaluated using various metrics, including ROC-AUC used to compare the four best models. Here are the results:

- **Logistic Regression with Polynomial Features**: ROC-AUC Score: 0.78
- **Voting Classifier**: ROC-AUC Score: 0.85
- **Random Forest Classifier**: ROC-AUC Score: 0.86
- **XGBoost Classifier**: ROC-AUC Score: 0.96

Based on the ROC-AUC scores, the **XGBoost Classifier** performed the best among all models.

## Conclusion

The XGBoost Classifier was identified as the best-performing model for predicting loan defaults, followed closely by the Random Forest Classifier and Voting Classifier. Future work could involve further tuning of these models and exploring additional features or different modeling techniques.
