# Telco Customer Churn Prediction

Predicting customer churn for a telecommunications company using machine learning.

## Project Overview
This project aims to predict which customers are likely to churn (cancel their service) based on various customer attributes and usage patterns.

## Dataset
- Source: [Kaggle Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Size: 7,043 customers
- Features: 21 columns including customer demographics, account information, and services

## Technologies Used
- Python 3.10
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

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

## Setup

### Using Conda (Recommended)
```bash
# Create environment
conda env create -f environment.yml

# Activate environment
conda activate churn-prediction

# Launch Jupyter
jupyter notebook
```

### Data Setup
1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
2. Place `WA_Fn-UseC_-Telco-Customer-Churn.csv` in `data/raw/`

## Status
🚧 Work in Progress

## Author
Julio Cesar Benavides Jimenez