# Task 1: Term Deposit Subscription Prediction (Bank Marketing)

##  Objective

The objective of this project is to predict whether a bank customer will subscribe to a term deposit based on demographic information and previous marketing campaign interactions. This classification problem helps banks identify potential customers and improve the effectiveness of marketing campaigns.

---

##  Dataset

**Dataset:** Bank Marketing Dataset

The dataset contains customer information such as:

* Age
* Job
* Marital Status
* Education
* Balance
* Housing Loan
* Personal Loan
* Contact Type
* Campaign Information
* Previous Marketing Outcomes

**Target Variable:**

* `y` → Whether the customer subscribed to a term deposit (`Yes` or `No`)

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* SHAP
* Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Loading and Exploration

* Loaded the Bank Marketing dataset.
* Examined dataset structure, dimensions, and feature types.
* Checked for missing values.

### 2. Data Preprocessing

* Encoded categorical variables using Label Encoding.
* Prepared features and target variables.
* Split data into training and testing sets.

### 3. Exploratory Data Analysis (EDA)

* Analyzed target variable distribution.
* Generated statistical summaries.
* Created correlation heatmaps.
* Visualized important data patterns.

### 4. Model Building

The following classification models were trained:

#### Logistic Regression

* Simple and interpretable classification algorithm.

#### Random Forest Classifier

* Ensemble learning algorithm using multiple decision trees.

### 5. Model Evaluation

Models were evaluated using:

* Confusion Matrix
* F1 Score
* ROC Curve
* AUC Score

### 6. Explainable AI (XAI)

SHAP (SHapley Additive Explanations) was used to:

* Identify important features.
* Explain model decisions.
* Interpret at least five individual predictions.

---

##  Results

* Successfully trained and evaluated multiple classification models.
* Compared model performance using F1 Score and ROC-AUC.
* Random Forest achieved better predictive performance than Logistic Regression.
* SHAP explanations provided transparency into model predictions.

---

## Visualizations Included

* Target Variable Distribution
* Correlation Heatmap
* Confusion Matrix
* ROC Curve
* SHAP Summary Plot
* SHAP Individual Prediction Explanations

---

##  Skills Gained

* Classification Modeling
* Data Preprocessing
* Feature Encoding
* Exploratory Data Analysis (EDA)
* Model Evaluation
* Explainable AI (XAI)
* Customer Behavior Analysis

---

##  Conclusion

This project demonstrates how machine learning can be used to predict customer subscription behavior in banking marketing campaigns. By identifying customers who are more likely to subscribe to a term deposit, banks can optimize marketing strategies, reduce operational costs, and improve campaign effectiveness.

---

## Author

**Muneeb ur rahman**



