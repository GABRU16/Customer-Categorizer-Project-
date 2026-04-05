# Customer Categorizer (Customer Segmentation & Prediction)

## Overview
This project builds an end-to-end Machine Learning pipeline to segment customers based on demographic and transaction data, and predict their category for targeted marketing.

---

## Objective
- Segment customers into meaningful groups  
- Predict customer category using ML models  
- Improve targeted marketing and personalization  

---

## Dataset
- Size: 2240 × 29  
- Type: Demographic + Transaction data  
- Features: Income, Spending, Campaign Response, Purchases  

---

## Tech Stack
- Python  
- Pandas, NumPy, Scikit-learn  
- Matplotlib, Seaborn  

---

## Workflow
Data Collection → EDA → Data Preprocessing → Feature Engineering →  
Clustering → Classification → Evaluation → Deployment  

---

## Key Steps

### 1. Data Preprocessing
- Handled missing values using Median Imputation  
- Removed irrelevant columns (ID, constant features)  
- Outlier handling using IQR method  
- Feature scaling using StandardScaler and PowerTransformer  

### 2. Feature Engineering
- Created meaningful features:
  - Age  
  - Total Spending  
  - Days as Customer  

### 3. Clustering (Unsupervised Learning)
Algorithms Used:
- K-Means  
- Agglomerative Clustering  
- Gaussian Mixture  
- DBSCAN  

Best Model:
- K-Means with k = 3 (based on Silhouette Score and Elbow Method)  

### 4. Dimensionality Reduction
- Applied PCA (Principal Component Analysis)  
- Reduced to 2 components  

### 5. Classification
- Converted clusters into labels  
- Tested multiple models  

Best Model:
- Logistic Regression  
- Accuracy: 94.13%  

---

## Results
- Segmented customers into 3 clusters  
- Achieved high prediction accuracy  
- Enabled better customer targeting and marketing strategies  

---

## Model Evaluation
- Accuracy Score  
- Confusion Matrix  
- GridSearchCV for hyperparameter tuning  

---

## Key Insights
- Majority customers fall in mid-income range  
- Spending behavior varies across clusters  
- Segmentation improves business decision-making  

---
