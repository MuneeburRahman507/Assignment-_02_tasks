# Customer Segmentation Using Unsupervised Learning

## Overview

This project focuses on customer segmentation using K-Means Clustering. The goal is to group customers based on their demographic characteristics and spending behavior. Customer segmentation helps businesses understand different customer groups and develop targeted marketing strategies.

## Dataset Information

The dataset contains the following features:

- CustomerID: Unique identifier for each customer
- Gender: Male/Female
- Age: Customer age
- Annual Income (k$): Annual income in thousand dollars
- Spending Score (1–100): Score assigned based on customer spending behavior

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- PCA

## Exploratory Data Analysis (EDA)

### Gender Distribution

[Insert<img width="600" height="200" alt="image" src="https://github.com/user-attachments/assets/1b330dd8-3914-4d0e-8a8b-5e861a9162d0" />
 Graph]

### Observation

The dataset contains customers from both genders, providing a balanced representation for analysis.

---

### Age Distribution

[Inser<img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/40e0d126-1839-47bb-8c7d-7b93098b8f76" />
t Graph]

### Observation

Most customers belong to the young and middle-aged groups, indicating an active consumer base.

---

### Annual Income Distribution

[Insert Gra<img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/2707a3f4-59ba-45ba-bd8f-1bd7e902488f" />
ph]

### Observation

Customers have varying income levels, showing a diverse purchasing capacity.

---

### Spending Score Distribution

[Inse<img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/7b6dc102-8dc7-44d8-8ed6-6a888b00c698" />
rt Graph]

### Observation

The spending scores vary significantly, suggesting the presence of multiple customer segments.

---

### Correlation Heatmap

[Insert<img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/f0c3c520-247c-47ee-980a-dee1b52979c0" /> Graph]


### Observation

The heatmap helps identify relationships among age, income, and spending behavior.

## Clustering Analysis

### Elbow Method

[Insert <img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/7be23868-abac-44ec-a3cb-cf3214edc52c" />
Graph]

### Observation

The Elbow Method suggests that 5 clusters provide the optimal balance between cluster compactness and simplicity.

### K-Means Clustering

K-Means Clustering was applied using the selected number of clusters to segment customers into meaningful groups.

## PCA Visualization

[Insert Gr<img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/5b83a2a7-01e3-46b4-8746-44fc71515d14" />
aph]

### Observation

PCA visualization shows clear separation among customer segments, indicating effective clustering performance.

## Key Insights

- Five distinct customer segments were identified.
- High-income and high-spending customers represent premium customers.
- High-income but low-spending customers may require personalized promotions.
- Low-income and high-spending customers are suitable targets for loyalty programs.
- Different customer groups exhibit unique purchasing behaviors.

## Marketing Strategies

### Cluster 1: High Income, High Spending
- Premium memberships
- Exclusive offers

### Cluster 2: High Income, Low Spending
- Personalized promotions
- Product recommendations

### Cluster 3: Low Income, High Spending
- Loyalty rewards
- Discount campaigns

### Cluster 4: Low Income, Low Spending
- Budget-friendly promotions

### Cluster 5: Average Income and Spending
- Regular engagement campaigns

## Conclusion

This project demonstrates how unsupervised learning techniques can be used to identify meaningful customer segments.

The K-Means algorithm successfully grouped customers based on spending patterns and income levels. The findings can help businesses design targeted marketing campaigns, improve customer satisfaction, and increase profitability through data-driven decision-making.

## AUTHOR 
Muneeb ur Rahman


