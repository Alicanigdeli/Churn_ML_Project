# Churn_ML_Project

# Credit Card Churn Model

This project aims to create a machine learning model for predicting the churn (attrition) rate of credit card customers. Churn rate refers to the likelihood of customers leaving the company. The model includes steps such as data cleaning, feature scaling, and the use of various classification algorithms.

## Data Cleaning and Preprocessing

The data cleaning and preprocessing steps in the project are performed as follows:

- Categorical values in the "Geography," "Gender," and "AgeGroup" columns are converted to numerical values using Label Encoder.
- The dataset is split into training and test sets, with a split ratio of 80% for training and 20% for testing.
- StandardScaler is used for feature scaling.

## Model Building and Performance Evaluation

In this project, models are built using various classification algorithms, and their performance is evaluated. The following classification algorithms are used:

- K-Nearest Neighbors (KNN)
- Random Forest
- Support Vector Machines (SVM)
- Logistic Regression

For each classification algorithm, the following performance metrics are calculated and printed:

- Accuracy
- F1 Score
- Precision
- Recall
- AUC-ROC Score (Area Under the Receiver Operating Characteristic Curve)
- Average Precision Score
- Confusion Matrix

Additionally, feature importances are calculated for the Random Forest classifier, and they are plotted in a graph.
