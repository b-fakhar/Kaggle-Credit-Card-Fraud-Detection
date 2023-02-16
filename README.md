# Credit Card Fraud Detection (Kaggle Project)
https://www.kaggle.com/mlg-ulb/creditcardfraud 

#  Objective:

Detect fraudulent credit card transactions, which is a crucial task for credit card companies to help their costumers upon the detection of fraudulent transactions.

# Dataset:
This highly unbalanced Kaggle dataset contains:

- Made by European cardholders in September 2013 using credit cards.
- Transactions occurred in two days, where there are 492 frauds out of 284,807 transactions. About 0.172% of all transactions constitutes the positive class (frauds).
- The dataset includes only numerical input variables resulting from a PCA transformation..
- Features V1, V2, … V28, which are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependent cost-senstive learning. 
- Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

# Summary
- Built an end-to-end data science pipeline that includes Exploratory Data Analysis (EDA), model building, and evaluation.
- Explored and compared different techniques, such as undersampling, oversampling, hybrid oversampling and undersampling using SMOTEENN, and a custom resampling technique, to handle class imbalance.
- Evaluated the performance of various classifiers, including LR, RF, Extra Tree, Gradient Boosting, Light GBM, and XGBoost.
- Achieved an ROC-AUC score of 0.96 and precision at the recall threshold of  0.93 using the proposed pipeline

•	SKILLS & Tools:  ML, Feature Engineering, Feature Reduction, Data Augmentation, Hyperparameter Tuning, Python, Matplotlib, Seaborn. 

