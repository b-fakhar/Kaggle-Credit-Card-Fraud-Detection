# Kaggle-Project-Credit-Card-Fraud-Detection

#  Objective:

Detect fraudulent credit card transactions, which is a crucial task for credit card companies to help their costumers upon the detection of fraudulent transactions.

# Dataset:
This highly unbalanced Kaggle dataset contains:

- Transactions made by credit cards in September 2013 by european cardholders.
- Transactions occurred in two days, where there are 492 frauds out of 284,807 transactions. About 0.172% of all transactions is the positive class (frauds).
- Only numerical input variables which are the result of a PCA transformation.
- Features V1, V2, … V28, which are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. 
- Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
