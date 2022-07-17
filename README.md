# Credit_Card_fraud_analytics_ML_model
Composite Machine Learning Model for Credit Card fraud detection using Decision Tree, Random Forest and Logistic Regression

Problem Statement
Aim: Identify fraudulent credit card transaction.
The dataset contains transactions made via credit cards by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

Data
It contains only numerical input variables which are the result of a PCA transformation. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount’. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount and feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.


