#credit-card-fraud-using-SMOTE
#Project Overview
Here we, handle imbalanced dataset by applying SMOTE and remove the extreme outliers
Compare which technique fits best to find feasible and resource efficient patterns in the dataset
Logistic Regression, Decision tree, K-Nearest Neighbor, Naive Bayes, Support Vector Machine, Random Forest Regressors and XGBoost to reach the best model.
Code and Resources Used
Python Version: 3.9
Packages: pandas, matplotlib, seaborn, numpy, sklearn, xgboost, imblearn

Dataset
Source : Kaggle - https://www.kaggle.com/mlg-ulb/creditcardfraud
The datasets contains transactions made by credit cards in September 2013 by european cardholders that occurred in two days.
It contains only numerical input variables which are the result of a PCA transformation. The only features which have not been transformed with PCA are 'Time' and 'Amount'.
Project Detail
Handling Imbalanced Dataset: For this project we use SMOTE (Synthetic Minority Over-sampling Technique) technique to handle imbalanced dataset.

Machine Learning Models: For this project I will implement the data to these models and determine which one fits the best:

Logistic Regression
Decision Tree
Naive Bayes
K-Nearest Neighbor
Support Vector Machine
Random Forest
XGBoost
Model Parameter: To determine which machine learning model fits the dataset the best, I will use this parameter to decide:

Precision-Recall
F1-Score
Accuracy
Step-by-Step Project:
Data Wrangling
Scaling the 'Amount' and 'Time' columns
Use SMOTE to handle imbalanced dataset and see the correlation of each columns
Determine which feature have a negative and positive correlation
Remove extereme outliers from features that have a high correlation with the classes
