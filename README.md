# Auto-Insurance-Fraud-Detection

## Project Overview
This project presents a comprehensive machine learning framework for identifying potentially fraudulent auto insurance claims. Insurance fraud is a significant issue leading to substantial financial losses for insurance companies, which in turn increases premiums for all customers. By leveraging a real-world dataset of US insurance claims, this analysis involves rigorous data cleaning, in-depth exploratory data analysis (EDA), and strategic feature engineering to uncover patterns indicative of fraud. The core of the project is the implementation and comparative evaluation of multiple classification models to build a robust system capable of accurately flagging suspicious claims for further investigation.

## Key Features
- **Data Cleaning & Preprocessing:** Handles missing values, corrects data types, and removes irrelevant or redundant columns to prepare a clean dataset for analysis.
- **Exploratory Data Analysis (EDA):** Utilizes extensive visualizations to explore the relationships between various claim attributes and the likelihood of fraud, identifying key trends and correlations.
- **Feature Engineering:** Creates new, insightful features from existing data, such as days_since_policy, sum_claims, and vehicle_age_at_incident, to enhance model performance.
- **Multi-Model Implementation:** Implements a wide range of classification algorithms to find the best-performing model, including:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - SVM
  - Decision Tree
  - Random Forest
  - XGBoost
- **Model Evaluation:** Employs comprehensive evaluation metrics to assess model performance, including Confusion Matrices, Classification Reports (Precision, Recall, F1-Score), and ROC-AUC scores.
- **Feature Importance & Selection:** Uses techniques like Random Forest feature importance and ANOVA F-tests to identify the most predictive features, leading to a more efficient and interpretable final model.
- **Dimensionality Reduction:** Applies Principal Component Analysis (PCA) as an alternative feature selection strategy to reduce complexity and improve model training.
