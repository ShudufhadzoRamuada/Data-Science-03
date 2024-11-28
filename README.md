
# Predicting Client Subscription to Term Deposits Using XGBoost

## Overview
This project aims to predict whether a client will subscribe to a term deposit based on various demographic and behavioral features from a bank's marketing campaign. We use the **XGBoost** algorithm, a powerful machine learning technique, to build a classification model that predicts the target variable ("yes" or "no").

## Features
The dataset includes attributes such as:
- Age
- Job
- Marital status
- Education
- Balance
- Campaign-related features

## Methodology
1. **Data Preprocessing**:
   - Encoding categorical variables
   - Normalizing numerical features
2. **Model**:
   - XGBoost classifier
3. **Evaluation**:
   - Accuracy: **90.64%**
   - ROC-AUC: **0.9290**
   - Precision, recall, and F1-score metrics for both classes

## Results
The model demonstrates high performance, with an accuracy of 90.64% and a ROC-AUC score of 0.9290, indicating strong predictive ability. Although precision and recall for the "yes" class were slightly lower, the overall model shows excellent classification performance.

## Installation
To run the project, ensure you have the following libraries installed:
pip install xgboost pandas scikit-learn matplotlib

## Usage
1. Load the dataset and preprocess the data.
2. Train the **XGBoost** model.
3. Evaluate the model using accuracy, ROC-AUC, and other classification metrics.
4. Visualize results such as confusion matrix and ROC curve.

## Conclusion
This project demonstrates the effective application of **XGBoost** in a real-world classification problem, achieving strong results even with class imbalance.
