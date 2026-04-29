# 📊 Customer Churn Prediction (Telco Dataset)

**Author:** Jake Albohn  
**Course:** Data Mining / Machine Learning  
**Date:** April 29, 2026  

---

## 📌 Project Overview
This project builds a machine learning model to predict customer churn for a telecommunications company.  

Customer churn prediction is important because retaining existing customers is far more cost-effective than acquiring new ones.  

This project follows a complete data science workflow:
- Problem Framing & Data Acquisition  
- Exploratory Data Analysis (EDA) & Data Preparation  
- Model Development, Evaluation & Interpretation  

The final deliverable is a fully documented notebook with visualizations, a tuned model, and business insights.

---

## 📊 Dataset
- **Name:** Telco Customer Churn Dataset  
- **Source:** Kaggle  
- **Size:** ~7,000 customers  
- **Features:**  
  - Demographics  
  - Service subscriptions  
  - Billing information  
- **Target Variable:** `Churn` (Yes/No → encoded to 1/0)

---

## 🛠 Tools & Technologies
- **Python**
  - Pandas, NumPy  
  - Matplotlib, Seaborn  
- **Scikit-learn**
  - Pipelines  
  - Preprocessing  
  - Random Forest  
  - GridSearchCV  
- **AutoViz** (EDA automation)  
- **Google Colab**  
- **GitHub**

---

## 🔍 Project Workflow

### 1. Data Preparation
- Dropped non-predictive `customerID`
- Converted `Churn` to numeric (1/0)
- Identified categorical vs. numerical features
- Handled missing values
- Applied one-hot encoding
- Performed stratified train/test split

---

### 2. Modeling
- Built baseline Random Forest model  
- Tuned hyperparameters using GridSearchCV  
- Evaluated using:
  - Accuracy  
  - Precision  
  - Recall  
  - F1 Score  
  - Cohen’s Kappa  
- Visualized confusion matrix  
- Analyzed feature importance  

---

### 3. Interpretation
- Identified key churn drivers  
- Analyzed model errors  
- Developed business recommendations  

---

## 📈 Results Summary
The tuned Random Forest model achieved strong performance across evaluation metrics.

### Key Churn Indicators:
- Month-to-month contracts  
- High monthly charges  
- Short customer tenure  

The model performed better at predicting non-churners than churners due to class imbalance.

---

## 🏢 Business Impact
This model can help telecom companies:
- Identify at-risk customers  
- Target retention campaigns  
- Improve customer satisfaction  
- Reduce revenue loss  
- Support data-driven decision-making  

---

## 📁 Repository Contents
- DataMining_Project_Template_Spring_2026.ipynb # Main notebook
- telco_customer_churn.csv # Dataset
- README.md # Project documentation

Note: AI models were used in this work. This work is meant as an academic exercise, not as an original project.
