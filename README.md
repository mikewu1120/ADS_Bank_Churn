# Automated Decision System (ADS) for Bank Churn Prediction

## Overview
This project focuses on building an **Automated Decision System (ADS)** for predicting customer churn in the banking sector using machine learning models like **XGBoost** and **Decision Trees**. The system aims to help financial institutions retain customers by identifying those likely to leave. It also incorporates fairness, transparency, and bias mitigation techniques.

## Key Features
- **Data Collection & Preprocessing**: Retrieved and preprocessed the Bank Churn dataset from Kaggle, ensuring clean and structured data for analysis. Employed techniques such as normalization, imputation for missing values, duplicate removal, and over-sampling for class imbalance. The pipeline adhered to **FAIR principles** (Findability, Accessibility, Interoperability, and Reusability), making it adaptable for other datasets.

- **EDA (Exploratory Data Analysis) & Feature Engineering**: Conducted comprehensive **EDA** to uncover patterns in the dataset. Applied feature engineering to optimize model input, using **Pandas**, **Matplotlib**, and **Seaborn** to visualize key insights.

- **Model Training & Optimization**: Selected key features (e.g., CreditScore, Age, Tenure) and excluded irrelevant ones (e.g., customer ID). Implemented **XGBoost** and a **tuned Decision Tree**, optimized using **GridSearchCV**. XGBoost achieved **86.2% accuracy**, outperforming the tuned Decision Tree (85.7%).

- **FAIR Data Principles & Public Sector Deployment**: Ensured that all methodologies were documented to comply with **FAIR principles** for transparency and accountability. Addressed the challenges of bias, fairness, and transparency when considering deployment in the public sector, recognizing that models like XGBoost may lack interpretability, posing risks to public trust.

