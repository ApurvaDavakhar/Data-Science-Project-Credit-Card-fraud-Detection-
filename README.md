# Credit-Card-fraud-Detection-Project

link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

About Dataset
Context
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

Content
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.



Overview

This project detects fraudulent credit card transactions using the Kaggle dataset. It applies various anomaly detection techniques to classify transactions as fraudulent or normal.

Dataset

Source: Kaggle (creditcard.csv)

Features:

30 numerical features (V1 to V28, Amount, Time)

Class: Target variable (0 = Normal, 1 = Fraud)

Approach

Data Preprocessing:

Loaded the dataset and checked for missing values.

Performed exploratory data analysis (EDA).

Anomaly Detection Methods:

Isolation Forest

Local Outlier Factor (LOF)

One-Class SVM

Evaluation:

Measured accuracy and classification performance.

Visualized fraudulent transactions.

Dependencies

Install the required Python libraries using:

pip install numpy pandas matplotlib seaborn scikit-learn

Usage

Run the Jupyter Notebook:

jupyter notebook CreditCardFruadDetectionUsingKaggleDataSet.ipynb

Results

Compared different anomaly detection models.

Visualized fraudulent transactions in the dataset.


View less
Usability
8.53

License
Database: Open Database, Contents: Database Contents
