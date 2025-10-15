# Telco Customer Churn Classification  

This project analyzes and predicts customer churn in a telecommunications dataset using exploratory data analysis (EDA) and multiple machine learning models.  
The goal is to identify key factors influencing customer decisions to leave and to build a robust predictive model for churn detection.

---

## Objectives  
- Explore the Telco Customer Churn dataset to understand customer behavior.  
- Identify patterns related to churned vs. loyal customers.  
- Handle imbalanced classes using **SMOTE**.  
- Train and compare multiple ML models:  
  - Decision Tree  
  - Random Forest  
  - XGBoost  
- Evaluate model performance using precision, recall, F1-score, and confusion matrix.

---

## Project Workflow  

1. **Data Preprocessing**  
   - Handle missing values and inconsistent data types.  
   - Encode categorical variables using Label Encoding and One-Hot Encoding.  
   - Normalize and balance data with **SMOTE**.

2. **Exploratory Data Analysis (EDA)**  
   - Analyze customer demographics and contract details.  
   - Visualize churn distribution by payment method, tenure, and service type.  
   - Correlation heatmaps and distribution plots for key insights.

3. **Modeling & Evaluation**  
   - Train multiple classifiers: Decision Tree, Random Forest, and XGBoost.  
   - Evaluate with accuracy, precision, recall, F1-score, and confusion matrix.  
   - Compare model performance and interpret feature importance.

---

## Key Libraries  
- `pandas`, `numpy` – data handling  
- `matplotlib`, `seaborn` – visualization  
- `scikit-learn`, `xgboost`, `imblearn` – modeling and evaluation  

---


