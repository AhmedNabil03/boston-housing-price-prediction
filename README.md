# Boston Housing Price Prediction

## Project Overview

This project focuses on predicting housing prices in Boston using machine learning techniques. The objective is to develop an accurate model that leverages various regression techniques based on the dataset's features. Through this work, I enhanced my skills in data preprocessing, model selection, and ensemble learning, culminating in a model that effectively highlights key factors influencing housing prices.

## Dataset Overview
The dataset consists of various features related to housing in Boston, such as average number of rooms, property age, crime rate, proximity to employment centers, and more. This data provides a comprehensive view of factors that impact housing prices in the region.

## Key Highlights

### Exploratory Data Analysis (EDA)
- Conducted thorough data exploration to identify the most impactful features influencing housing prices, visualizing the dataset with various plots to observe feature distributions, outliers, and correlations.

### Data Preprocessing
- Implemented data cleaning to handle missing values and outliers, applied feature scaling for normalization, and conducted feature selection to identify the most relevant predictors.

### Modeling & Evaluation

- **Modeling Steps**:  
  Tested various machine learning algorithms for predicting housing prices:

  - **Regression Models**: Linear Regression, Ridge, Lasso, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), Decision Tree, Random Forest, ExtraTrees, AdaBoost, Gradient Boosting, XGBoost, and Multilayer Perceptron (MLP).
  - **Hyperparameter Tuning**:  
    Used **GridSearchCV** for systematic hyperparameter tuning to optimize performance.
  - **Ensemble Learning**:  
    Applied **Voting Regressor** and **Stacking Regressor** to combine the best models for improved accuracy.
- **Model Evaluation**:  
  Evaluated models using **R² Score** and **Mean Absolute Error (MAE)**.

### Results
- The **Stacking Regressor** emerged as the most effective model:
  - **R² Score**: 0.973
  - **Mean Absolute Error (MAE)**: 1.38, indicating precise price predictions and effective variance explanation.
- The high performance of this model demonstrates its potential for real-world applications in housing price prediction.

## Tools
- Python
