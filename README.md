# Early Churn Detection and Segmentation of Telecom Customers Using Machine Learning

A research-based machine learning study focused on predicting early customer churn and segmenting telecom customers to improve retention strategies.

---

## Project Overview

This repository contains the research paper, dataset, and machine learning model developed to analyze and predict **early customer churn** in the telecom industry.

The study focuses on identifying customers who leave within the **first 3 months of service**, which is critical for reducing revenue loss and improving customer retention.

The project combines predictive modeling with customer segmentation to generate actionable business insights.

### Key Highlights:
- Early churn prediction using supervised machine learning  
- Comparison of multiple models (Logistic Regression, Random Forest, XGBoost, LightGBM)  
- Feature importance analysis using SHAP  
- Customer segmentation using K-Means clustering  
- Business cost optimization through threshold tuning  

---

## Folder Structure
```
Early_Churn_Telecom_ML/
│
├── Dataset/
│ └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
│
├── Model/
│ └── model_ML.html
│
├── Research Paper/
│ └── Research_Paper.pdf
│
└── README.md
```


---

## Dataset

This study uses a publicly available telecom dataset:

**WA_Fn-UseC_-Telco-Customer-Churn.csv**

- Total records: 7043 customers  
- Includes:
  - Demographic data  
  - Service subscription details  
  - Billing information  

The dataset is preprocessed using:
- Missing value handling  
- Encoding categorical variables  
- Feature scaling  
- SMOTE for class imbalance  

---

## Model Description

The following machine learning models were implemented:

- Logistic Regression  
- Random Forest  
- XGBoost  
- LightGBM  

**LightGBM** achieved the best performance and was selected as the final model.

---

## Methodology

- Data preprocessing and feature engineering  
- Creation of Early Churn variable (tenure ≤ 3 months)  
- Model training and evaluation  
- Performance evaluation using:
  - Precision  
  - Recall  
  - F1-score  
  - ROC-AUC  
- Threshold optimization based on business cost  
- Feature importance analysis using SHAP  
- Customer segmentation using K-Means clustering  

---

## Key Findings

- Early churn rate: **8.48%**  
- Best Model: **LightGBM**  
- F1-score: **0.97**  
- ROC-AUC: **0.995**  

Key churn drivers:
- Tenure  
- Monthly Charges  
- Total Charges  
- Contract Type  

Customer segmentation identified:
- Price-Sensitive  
- Low-Engagement  
- Onboarding Failure (highest revenue risk)  

---

## Business Impact

- Enables early detection of high-risk customers  
- Supports targeted retention strategies  
- Reduces potential revenue loss  
- Improves data-driven decision making  

---

## Limitations and Future Work

- Model trained on a single dataset  
- Concept drift not addressed  
- No deep learning models included  

Future improvements:
- Use multiple datasets  
- Implement real-time prediction  
- Include customer feedback data  
- Explore deep learning models  

---

## Authors / Team Members

Rajintha Lakshnai 
BSc in Applied Data Science Communication  

Team Members / Contributors:

WACI Abeysekara  
MZM Hussein  
MN Mohamed
