LEVEL 3 - TASK 1: PREDICTIVE MODELING

Codveda Technologies - Data Analysis Intern
Muhammad Sabbar Mustapha | ID: CV/A1/60608

Project Overview

This project focuses on predicting customer churn using a telecom dataset. The goal is to identify which customers are likely to leave the service so that appropriate retention strategies can be applied.

The project implements a step-by-step predictive modeling workflow using Python and popular data science libraries.

Objectives:
Data Preprocessing
Handle categorical variables (binary and multi-class)
Feature scaling of numeric variables
Handle missing values if any
Model Training and Evaluation

Train multiple classification models:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier

Evaluate models using:
Accuracy
Precision
Recall
F1-score

Hyperparameter Tuning
Perform Grid Search on Random Forest to improve performance
Use cross-validation to avoid overfitting
Prediction
Generate predictions for unseen test data
Compare predicted vs actual churn

Tools and Libraries
Python
pandas
scikit-learn
matplotlib & seaborn

Workflow Summary:
Load and Inspect Data – Understand the dataset and target variable.
Data Preprocessing – Encode categorical variables, scale numeric features.
Feature and Target Split – Separate features (X) from target (y).
Model Training – Train Logistic Regression, Decision Tree, and Random Forest.
Model Evaluation – Evaluate using accuracy, precision, recall, F1-score, and confusion matrix.
Hyperparameter Tuning – Optimize Random Forest parameters using Grid Search.
Predictions – Generate and visualize predictions on test data.

Results:
Random Forest (after tuning) achieved the best performance on test data with high F1-score.
Confusion matrices show the model’s ability to correctly classify churn and non-churn customers.
