# Credit Card Fraud Detection (Kaggle Project)
https://www.kaggle.com/mlg-ulb/creditcardfraud 

#  Objective:

Detect fraudulent credit card transactions, which is a crucial task for credit card companies to help their costumers upon the detection of fraudulent transactions.

# Dataset:
This highly unbalanced Kaggle dataset contains:

- Transactions made by credit cards in September 2013 by european cardholders.
- Transactions occurred in two days, where there are 492 frauds out of 284,807 transactions. About 0.172% of all transactions is the positive class (frauds).
- Only numerical input variables which are the result of a PCA transformation.
- Features V1, V2, … V28, which are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. 
- Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

# Summary
-	Implemented an end-to-end Data Science pipeline by considering different steps, namely Exploratory Data Analytics (EDA), model building, and evaluation.
-	Used and compared different techniques such as Undersampling, Oversampling, Hybrid Oversampling and Undersampling using SMOTEENN, and a custom resampling technique to handle class imbalance.
-	Compared perdormance of different classifiers such as LR, RF, Extra Tree, Gradient Bossting, Light GBM, and XGBoost.
-	Obtained ROC-AUC score of 0.93 Percision at Recall Threshold using the prposed pipeline.

•	SKILLS & Tools:  ML, Feature Engineering, Feature Reduction, Data Augmentation, Hyperparameter Tuning, Python, Matplotlib, Seaborn. 

