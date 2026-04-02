# warehouse-efficiency-fmcg-analytics
Analyzing warehouse operational efficiency in an FMCG supply chain using Python, EDA, and Random Forest Regression — BBA Capstone Project, Jain Online University.
# Analyzing Warehouse Operational Efficiency in an FMCG Supply Chain

## Overview
This project applies data analytics and machine learning to evaluate warehouse 
operational efficiency across a large FMCG distribution network. Using a dataset 
of 25,000 warehouse records, the study identifies performance bottlenecks, computes 
key operational KPIs, and builds a predictive model to forecast warehouse throughput 
(product weight in tons).

## Key Highlights
- Dataset: 25,000 records × 24 features (SupplyFlow FMCG Solutions)
- Best Model: Random Forest Regressor — R² = 0.99, RMSE = 885.88
- Top Predictor: storage_issue_reported_l3m
- Cross-Validation: 5-fold CV R² = 0.99 (±0.00), CV RMSE = 1003.47 (±20.67)

## Tech Stack
Python | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn | Scipy | Jupyter Notebook

## Project Structure
├── SupplyFlow_FMCG_Solutions.xlsx   # Dataset
├── warehouse_analysis.ipynb         # Main Jupyter Notebook
├── Interim_Report.docx              # Interim project report
├── Synopsis_Report.pdf              # Project synopsis
└── README.md

## Methodology
1. Data Cleaning — duplicate removal, missing value imputation, IQR-based outlier treatment
2. Feature Engineering — derived wh_age from wh_est_year
3. EDA — distribution plots, Q-Q plots, categorical analysis
4. Feature Selection — Random Forest importance scores (top 15 features)
5. Model Building — Random Forest Regressor with StandardScaler normalization
6. Model Improvement — ordinal encoding, outlier treatment pipeline, 5-fold cross-validation

## Academic Context
BBA Semester VI | Data Science and Analytics Elective  
Jain Online (Deemed-to-be University), Bangalore | 2025–26  
Guide: Rishab Pandey
