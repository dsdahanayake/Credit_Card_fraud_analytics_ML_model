# Credit_Card_fraud_analytics_ML_model
Composite Machine Learning Model for Credit Card fraud detection using Decision Tree, Random Forest and Logistic Regression

## Fraud Analytics using Python
- Introduction to fraud detection
    * Reading the data labels
    * Data resampling and plotting
    * Applying SMOTE
    * Logistic regression with SMOTE
- Using ML classification to catch fraud and monitoring the right performance metrics
    * Random forest classifier
    * Performance of RF classifier
    * Plotting precision recall curve
- Performing model adjustments and regression analysis
    * Logistic regression
    * Voting classifier

Problem Statement
Aim: Identify fraudulent credit card transaction.
The dataset contains transactions made via credit cards by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

Data
It contains only numerical input variables which are the result of a PCA transformation. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount’. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount and feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

## Exploratory analysis

![image](https://user-images.githubusercontent.com/85073848/179573543-a3bdabdc-3b48-4454-b76b-355f189b88ef.png)

## Visualizing the data

![image](https://user-images.githubusercontent.com/85073848/179573933-5c3298e2-de4c-4945-904b-35274125b656.png)

![image](https://user-images.githubusercontent.com/85073848/179574196-df4452f0-bb89-4981-bb0b-13fe380c1864.png)

## Techniques used to manage imbalanced data

- Random Under Sampling(RUS): This reduces the majority class and makes the data balanced.
- Random Over Sampling(ROS): This generated duplicates of the minority class. Inefficient because of duplicacy.
- Synthetic Minority Oversampling Technique(SMOTE): Generates fake realistic data to balance out the data.

![image](https://user-images.githubusercontent.com/85073848/179574842-d8d39725-6961-4bd8-9e9e-fe21de7a4d8a.png)

After Synthetic Minority Oversampling Technique(SMOTE)

![image](https://user-images.githubusercontent.com/85073848/179575134-1cc4eb1e-dfe4-4891-ba2b-81954690126b.png)






