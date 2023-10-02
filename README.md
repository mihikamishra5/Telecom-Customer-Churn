# Telecom-Customer-Churn
# Customer Churn Prediction in Telecommunication Industry

## Overview
This repository contains Python scripts and Jupyter Notebooks for building machine learning models to predict customer churn in the telecommunication industry. The project is divided into two stages, where we analyze the data and build predictive models using various algorithms.

### Dataset
- The dataset (telco-customer-churn.csv) contains customer information and churn labels.
- It consists of 7043 rows and 21 columns, with both categorical and numerical features.

## Project Stages
### Stage 1: Original Dataset
1. **Explanatory Data Analysis (EDA):** The initial exploratory data analysis has been performed to understand the data's characteristics.

2. **Data Visualization:** Visualizations have been created to gain insights into the data.

3. **Data Preprocessing:** This includes data imputation, feature selection & scaling, and encoding categorical features.

4. **Addressing Data Imbalance:** The Synthetic Minority Over-sampling Technique (SMOTE) has been applied to balance the data.

5. **Splitting the Dataset:** The data has been divided into training and test sets in an 80/20% ratio.

6. **Model Building:** Four machine learning models - Naïve Bayes, Logistic Regression, Random Forests, and XGBoost - have been built using default parameters.

7. **Model Evaluation:** Model performance metrics such as accuracy, precision, recall, and F1-score have been calculated.

8. **Model Tuning (Hyperparameter Tuning):** Hyperparameter tuning has been applied to Random Forest and XGBoost models.

### Stage 2: Modified Dataset (After SMOTE)
1. Repeat the same steps as in Stage 1 but on the modified dataset, which includes the SMOTE technique to address data imbalance.

## Results and Conclusions
- Model performance metrics (accuracy, precision, recall, and F1-score) for each algorithm will be presented.
- The best model in terms of the 'recall' metric will be identified for both stages.
- Hyperparameter tuning results will be presented, and the best model in terms of 'recall' will be identified for Random Forest and XGBoost.
- A comparison of results between the two stages will be made to determine which stage produces better results.
- The overall best model for predicting customer churn will be identified.


