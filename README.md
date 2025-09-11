# Bank Churn Prediction Using Binary Classification Models

## Project Overview

This project focuses on predicting **bank customer churn** using three supervised machine learning algorithms:

- **Logistic Regression**  
- **K-Nearest Neighbors (KNN)**  
- **Support Vector Machines (SVM)**  

The dataset contains **simulated records** for **10,000 customers**, each described by **11 features** such as credit score, age, tenure, balance, and activity status. The target variable is `churn`, where:
- `1` indicates the customer has churned
- `0` indicates the customer has remained with the bank

## Objectives

- Develop and evaluate **binary classification models** to predict customer churn
- Identify which features have the **strongest influence** on the likelihood of churn

For analysis, explanations, and discussion of the results, please refer to the [report](report.pdf).

**Note:** The **Logistic Regression** and **KNN** algorithms were implemented manually **without using the scikit-learn library**, to strengthen understanding of how the algorithms work internally.
