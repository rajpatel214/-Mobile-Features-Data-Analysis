# Mobile-Features-Data-Analysis
## Project Overview
Predicting the price of a mobile phone based on historical data and its features is a valuable use case for mobile companies. By analyzing available data, we can determine which features significantly impact mobile pricing and optimize model parameters for improved prediction accuracy. This project focuses on feature selection, model tuning, and evaluating different regression models.

## Problem Statement
Given various features of mobile phones, the goal is to build a regression model that predicts the approximate price of a mobile phone. Additionally, we analyze feature importance and optimize model parameters to improve performance.

## Dataset
The dataset contains various mobile features, including:
- Brand, Model, Network Technology, Bands (2G/3G/4G), OS, CPU, Chipset, GPU
- Internal Memory, RAM, Camera Specifications, Battery Capacity, Sensors
- Approximate Price (Target Variable)

## Key Steps in the Project

### 1. Data Preprocessing
- Load the dataset and inspect missing values
- Handle missing values using appropriate imputation techniques
- Convert categorical features into a structured format
- Normalize and scale numerical features

### 2. Feature Engineering
- Extract useful information from categorical and text-based columns
- Encode SIM and Network Technology features
- Select important features using Recursive Feature Elimination (RFE) and Random Forest feature importance

### 3. Model Training and Tuning
- Split data into training and testing sets
- Apply feature scaling using StandardScaler
- Train different regression models:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - Gradient Boosting Regressor
  - AdaBoost Regressor
- Perform hyperparameter tuning using GridSearchCV

### 4. Model Evaluation
- Evaluate models using R-squared score and Mean Squared Error (MSE)
- Compare feature importance from different models
- Visualize model predictions vs actual values
- Analyze residual plots

## Results and Findings
- Feature importance ranking using RFE and Random Forest
- Best model selection based on performance metrics
- Optimized hyperparameters for improved predictions
- Graphical analysis of actual vs predicted prices


