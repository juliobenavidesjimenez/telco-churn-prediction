## Project Summary

This project focuses on predicting customer churn for a telecommunications company using machine learning. Several models were evaluated to identify customers at risk of churning, with a Random Forest model selected as the final approach. Beyond model performance, the project emphasizes business decision-making by optimizing the classification threshold based on real-world cost considerations. By aligning predictions with business priorities, the final solution reduces estimated churn-related costs by approximately 39%.


# Telco Customer Churn Prediction

## Overview
Customer churn is a major challenge for telecommunications companies. This project applies machine learning techniques to identify customers who are likely to churn and translates model predictions into actionable business decisions.

The project goes beyond traditional model evaluation by incorporating business costs into the decision process, optimizing the churn prediction threshold to minimize overall business impact.

---

## Dataset
- Source: Kaggle – Telco Customer Churn Dataset  
- Observations: 7,043 customers  
- Target variable: `Churn` (Yes / No)

The dataset includes customer demographics, service information, contract details, and billing data.

---

## Project Structure
```
telco-churn-prediction/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── src/
├── models/
├── reports/
├── environment.yml
└── README.md
```


---

## Methodology

### 1. Exploratory Data Analysis (EDA)
- Analysis of churn distribution
- Identification of key variables such as tenure, monthly charges, and contract type
- Initial insights into customer behavior

### 2. Baseline Model
- Feature selection based on EDA
- Baseline classification model to establish reference performance

### 3. Model Comparison
- Evaluation of multiple models:
  - Logistic Regression (with and without class weighting)
  - Decision Tree
  - Random Forest
- Model selection based on recall and F1-score for churn

### 4. Business Insights
- Interpretation of feature importance
- Identification of high-risk customers
- Translation of model outputs into actionable business insights

### 5. Threshold Optimization and Business Cost
- Separation of probability estimation and decision-making
- Definition of business costs:
  - False Negative (missed churner) = high cost
  - False Positive (unnecessary contact) = low cost
- Optimization of the decision threshold
- Reduction of estimated business cost by approximately 39% by adjusting the threshold from 0.5 to 0.25

---

## Key Results
- Random Forest selected as the final model
- Churn probability used to prioritize customers by risk
- Optimized decision threshold aligned with business priorities
- Significant reduction in churn-related business cost without changing the model

---

## Business Impact
The final solution enables the company to:
- Identify high-risk customers proactively
- Prioritize retention efforts
- Reduce customer attrition and revenue loss
- Make data-driven decisions aligned with real business costs

---

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## Conclusion
This project demonstrates how machine learning can be effectively applied to customer churn prediction while emphasizing the importance of business-driven decision-making. Optimizing the decision threshold based on cost considerations proved to be more impactful than modifying the model itself, highlighting the value of aligning machine learning solutions with business objectives.
