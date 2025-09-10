# Data Science Projects: Cook County Housing Prices & Spam Email Classifier

This repository contains two applied data science projects completed in Jupyter notebooks.  
Project A focuses on **regression modeling for housing prices and tax inequality**, while Project B builds a **spam email classifier using logistic regression**.  

---

## Project A: Housing Price Regression

### Overview
This project models housing prices in Cook County with a focus on property tax inequality. Using regression and feature engineering, the goal is to evaluate predictive accuracy and quantify misestimation of homeowner tax burdens.  

### Methods
- Data preprocessing (cleaning, one-hot encoding, log transformations)  
- Linear regression with scikit-learn  
- Evaluation with RMSE, residual analysis, and stratified error metrics  

### Results
- Achieved reasonable RMSE for overall model fit  
- Residual plots showed systematic differences by property value tiers  
- Highlighted cases of potential tax misestimation  

### How to Run
1. Clone repo and install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
2. Open projA1.ipynb or projA2.ipynb in Jupyter/Colab
3. Run all cells to reproduce preprocessing, modeling, and evaluation
   
---

## Project B: Spam/Ham Email Classification

### Overview

This project builds a spam email classifier using logistic regression. The objective is to detect spam messages and evaluate classification performance with standard metrics.

### Methods
- Text preprocessing (tokenization, lowercasing, keyword features)
- Logistic regression with scikit-learn pipelines
- Evaluation with ROC/AUC, confusion matrix, and GridSearchCV for tuning

### Results
- Achieved ~90% test accuracy (top 7%)
- ROC curve validated classifier performance
- Hyperparameter tuning improved precision–recall balance

### How to Run
1. Clone repo and install dependencies:
  ```
   pip install -r requirements.txt
  ```
2. Open projB1.ipynb or projB2.ipynb in Jupyter/Colab
3. Run all cells to reproduce preprocessing, modeling, and evaluation
