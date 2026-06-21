# Assignment-_02_tasks

# Task 1: Term Deposit Subscription Prediction (Bank Marketing)

## Overview

This project focuses on predicting whether a bank customer will subscribe to a term deposit based on customer demographics, financial information, and previous marketing campaign interactions.

The project applies machine learning classification techniques and Explainable AI (XAI) methods to understand customer behavior and improve marketing decision-making.

---

## Objective

The primary objective of this project is to build a predictive model that can determine whether a customer will subscribe to a term deposit offered by a bank.

This helps financial institutions:

* Improve marketing campaign efficiency
* Reduce customer acquisition costs
* Identify high-potential customers
* Support data-driven business decisions

---

## Dataset

**Dataset:** Bank Marketing Dataset

The dataset contains information related to:

* Customer demographics
* Employment details
* Marital status
* Education level
* Account balance
* Housing and personal loans
* Marketing campaign interactions
* Previous campaign outcomes

**Target Variable**

| Variable | Description                                  |
| -------- | -------------------------------------------- |
| y        | Customer subscribed to term deposit (Yes/No) |

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* SHAP (Explainable AI)

---

## Project Workflow

### 1. Data Loading and Exploration

* Imported required libraries
* Loaded the Bank Marketing dataset
* Examined dataset structure
* Checked dimensions and data types

### 2. Data Cleaning and Preprocessing

* Checked for missing values
* Encoded categorical features using Label Encoding
* Prepared data for machine learning models

### 3. Exploratory Data Analysis (EDA)

Performed:

* Target variable distribution analysis
* Statistical summary analysis
* Correlation heatmap visualization

These analyses helped understand feature relationships and customer subscription trends.

### 4. Feature Engineering

* Separated features and target variable
* Prepared training and testing datasets

### 5. Train-Test Split

The dataset was divided into:

* 80% Training Data
* 20% Testing Data

This ensures unbiased model evaluation.

---

## Machine Learning Models

### Logistic Regression

A baseline classification model used to predict customer subscription behavior.

### Random Forest Classifier

An ensemble learning model that combines multiple decision trees to improve predictive performance.

---

## Model Evaluation

The following evaluation metrics were used:

### Confusion Matrix

Measures:

* True Positives
* True Negatives
* False Positives
* False Negatives

### F1-Score

Provides a balance between:

* Precision
* Recall

### ROC Curve

Evaluates the model's ability to distinguish between classes.

### AUC Score

Measures overall classification performance.

---

## Explainable AI (XAI)

SHAP (SHapley Additive Explanations) was used to explain model predictions.

### SHAP Analysis Included

* Global feature importance
* SHAP summary plots
* Individual prediction explanations
* Analysis of 5 customer predictions

This improves transparency and trust in model decisions.

---

## Visualizations

The project includes:

* Target Variable Distribution Plot
* Correlation Heatmap
* Logistic Regression Confusion Matrix
* Random Forest Confusion Matrix
* ROC Curve
* SHAP Summary Plot
* SHAP Force Plots

---

## Results

* Successfully trained Logistic Regression and Random Forest models.
* Compared model performance using F1-Score and ROC metrics.
* Random Forest demonstrated stronger predictive capability.
* SHAP explanations identified the most influential customer features.
* The model can assist banks in targeting customers more effectively.

---

## Skills Demonstrated

* Data Cleaning
* Feature Encoding
* Exploratory Data Analysis (EDA)
* Classification Modeling
* Model Evaluation
* Explainable AI (XAI)
* Customer Behavior Analysis
* Data Visualization

---

## Repository Structure

```text
Task-1-Term-Deposit-Subscription-Prediction/
│
├── Task 1 Term Deposit Subscription Prediction (Bank Marketing).ipynb
├── README.md
└── dataset/
```

---

## Conclusion

This project demonstrates the complete machine learning workflow for customer subscription prediction. By combining classification algorithms with Explainable AI techniques, the solution not only predicts customer behavior but also explains why predictions are made. Such insights can help banks optimize marketing campaigns and improve customer targeting strategies.

---



