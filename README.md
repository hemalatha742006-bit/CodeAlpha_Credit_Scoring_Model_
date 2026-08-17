# CodeAlpha_Credit_Scoring_Model_
# CodeAlpha Internship - Task 1: Credit Scoring Model

## Overview
This repository contains a Machine Learning workflow designed to assess an individual's creditworthiness using past financial data.

## Dataset
* **Dataset Used:** Statlog (German Credit Data) from UCI ML Repository
* **Instances:** 1,000 financial records
* **Target Variable:** Credit Risk (0 = Good Credit / Low Risk, 1 = Bad Credit / High Risk)

## Workflow & Approach
1. **Data Preprocessing:** Handled missing values and mapped target variables.
2. **Feature Engineering:** One-Hot Encoding for categorical financial attributes.
3. **Feature Scaling:** Applied `StandardScaler` to numerical inputs.
4. **Model Training:** Trained Logistic Regression and Random Forest models.
5. **Evaluation Metrics:** Precision, Recall, F1-Score, and ROC-AUC Curves.

## How to Run
1. Open Google Colab.
2. Upload `credit_Scoring_model (2).ipynb`.
3. Upload the `statlog+german+credit+data (1).zip` dataset when prompted by the script.
4. Run all cells sequentially.
