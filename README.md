# Portuguese Bank Telemarketing Dataset Classification Project

## Introduction

This repository contains code and analysis for a machine learning project based on the Portuguese Bank Telemarketing Dataset. The goal of this project is to predict whether a client will subscribe to a term deposit, turning this into a binary classification problem.

## Data Preprocessing

The dataset underwent several preprocessing steps:

- **Cleaning and Segregation:** Data was cleaned, segregated into numeric and non-numeric columns.
- **Handling Missing Values:** Missing values were checked and dealt with appropriately.
- **Duplicate Removal:** Duplicate rows were removed from the dataset.
- **Outlier Removal:** Outliers and unknown values were dropped for accurate analysis.

## Exploratory Data Analysis (EDA) and Visualization

Exploratory analysis was performed on the target variable, as well as categorical and continuous variables. Heatmaps were generated to visualize correlations between numerical columns.

## Data Preparation

Data was split into training and testing sets. Categorical variables were transformed into dummy variables, and standardization techniques were applied. Dimensionality reduction methods were employed to prepare the data for training.

## Machine Learning Algorithms

Four machine learning algorithms were utilized and evaluated:

1. **Logistic Regression:**
   - Classification report was generated.
   - Hyperparameters were tuned using GridSearchCV.
   - The model was trained with optimized parameters and evaluated again.

2. **K-Nearest Neighbors (KNN):**
   - Classification report was generated.
   - Optimal neighbor value was determined using the elbow method.
   - Hyperparameters were tuned using GridSearchCV.
   - Regularization techniques were applied.
   - The model was trained with optimized parameters and evaluated again.

3. **Random Forest:**
   - Classification report was generated.
   - Hyperparameters were tuned using RandomizedSearchCV.
   - The model was trained with optimized parameters and evaluated again.

4. **XGBoost:**
   - Classification report was generated.
   - Hyperparameters were tuned using Bayesian Optimization with Hyperopt.
   - The model was trained with optimized parameters and evaluated again.

## Model Evaluation and Selection

Accuracy scores from all models were compared, and the best-performing model was determined. An ROC curve was plotted to visualize the performance of the selected model.

## Feature Importance Analysis

The importance of features was analyzed, and the accuracy changes concerning the top k important features were examined to understand the impact of feature selection on the models.

## Conclusion and Insights

Based on the evaluation metrics and feature importance analysis, insights were drawn regarding the most influential factors in predicting whether a client will subscribe to a term deposit. The best-performing model and its corresponding parameters were identified, providing valuable information for future marketing strategies and client targeting efforts.
