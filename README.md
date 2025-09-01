# 🏦 Customer Churn Prediction – Credit Card Attrition

This repository documents a project focused on predicting **customer churn in credit card services** using machine learning. The work was carried out as part of an academic course and culminated in a full research paper analyzing customer attrition patterns and building predictive models to identify at-risk clients.

Customer churn is a critical challenge in the banking industry. Retaining customers is significantly more cost-effective than acquiring new ones, and early identification of at-risk customers allows banks to take targeted retention actions. In this project, we used the **BankChurners dataset** to explore behavioral and demographic factors driving attrition and applied predictive models to classify customers into *retained* vs *attrited* groups.

---

## 📌 Project Overview

- **Goal**: Build predictive models to identify credit card customers at risk of attrition.  
- **Dataset**: BankChurners (10,000+ customers with demographic, transactional, and account data).  
- **Approach**:  
  - Data cleaning and preprocessing (feature encoding, normalization, outlier handling).  
  - Feature engineering (e.g., Transactions per Month).  
  - Exploratory Data Analysis (EDA) to uncover churn drivers.  
  - Model development (Logistic Regression, KNN, Decision Tree, Random Forest, Gradient Boosting, LightGBM, XGBoost).  
  - Addressed class imbalance using SMOTE oversampling.  
  - Feature selection using Recursive Feature Elimination (RFE) for interpretability.  

---

## 📊 Key Findings

- **Behavioral factors** (transaction count, transaction amount, utilization ratio) were stronger predictors of churn than demographics.  
- Customers with **low transaction activity**, **fewer product relationships**, and **high utilization ratios** were more likely to leave.  
- **XGBoost with Recursive Feature Elimination (RFE)** achieved the best results:  
  - Precision: **0.92**  
  - Recall: **0.91**  
  - F1-Score: **0.91**  
  - Overall Accuracy: **97%**:contentReference[oaicite:0]{index=0}  

---

## 🛠️ Tools & Techniques

- **Python** (pandas, numpy, matplotlib, seaborn)  
- **scikit-learn** (Logistic Regression, Decision Tree, Random Forest, Gradient Boosting)  
- **imbalanced-learn** (SMOTE for class balancing)  
- **XGBoost & LightGBM** (boosting algorithms)  

---

## 📄 Research Paper

The complete research paper (with methodology, code snippets, and analysis) is available in this repository:  
👉 [Identifying At-Risk Customers – Understanding Customer Churn (PDF)](./Identifying_At_Risk_Customer_-_Understanding_Customer_Churn-Final.pdf)

---

## ✨ Impact

This project demonstrates how **machine learning and feature engineering** can be applied in the financial services sector to:  
- Proactively flag customers likely to churn.  
- Inform retention strategies such as loyalty programs or personalized offers.  
- Highlight key business drivers like **engagement** and **credit utilization**.  

---

## 📌 Next Steps

Future extensions of this project could include:  
- Deploying the model via a web application for real-time churn prediction.  
- Incorporating time-series analysis to track behavioral changes.  
- Testing deep learning models for comparison with ensemble methods.  

---
