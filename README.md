# DATA 100: Principles & Techniques of Data Science Projects
### Cook County Housing Prices & Spam Email Classifier

This repo showcases two projects focused on predictive modeling: a housing price regression analyzing tax inequality and a spam email classifier using TF-IDF and logistic regression. Both projects demonstrate end-to-end workflows from data cleaning to model evaluation.

**Tech used:** Python, pandas, NumPy, scikit-learn, in Jupyter Notebooks.

---

## Project A: Housing Price Regression (Oct 2024)

### Overview
This project models housing prices in Cook County, IL, with a focus on property tax inequality. The goal is to evaluate predictive accuracy and identify systematic misestimation of homeowner tax burdens.

### Methods
- Data preprocessing (cleaning, one-hot encoding, log transformations)
- Linear regression with scikit-learn
- Evaluation with RMSE, residual analysis, and stratified error metrics

### Results
- Achieved strong predictive performance with RMSE-based evaluation
- Residual plots showed systematic differences by property value tiers  
- Highlighted cases of potential tax misestimation  

### How to Run
1. Clone repo and install dependencies:  
```bash
   pip install -r requirements.txt
```
2. Open projA1.ipynb or projA2.ipynb in Jupyter Notebook
3. Run all cells to reproduce preprocessing, modeling, and evaluation
   
---

## Project B: Spam/Ham Email Classification (Nov 2024)

### Overview

This project uses logistic regression with TF-IDF features to detect spam messages and evaluate classification performance. Achieved ~90% test accuracy (top 7% of class).

### Methods
- Text preprocessing (tokenization, lowercasing, keyword features)
- Logistic regression with scikit-learn
- Evaluation with ROC/AUC, confusion matrix, and GridSearchCV for tuning

### Results
- Achieved ~90% test accuracy
- Strong ROC/AUC performance
- Improved precision–recall tradeoff through hyperparameter tuning

### How to Run
1. Clone repo and install dependencies:
  ```
   pip install -r requirements.txt
  ```
2. Open projB1.ipynb or projB2.ipynb in Jupyter Notebook
3. Run all cells to reproduce preprocessing, modeling, and evaluation
