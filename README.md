#  Machine Learning with Scikit-Learn

This repository contains implementations of core supervised learning algorithms using **Scikit-learn**, along with a full machine learning pipeline demonstrated on the **Rossmann Store Sales** dataset. The project follows a well-structured ML workflow — from understanding business requirements to model interpretation.

---
##  Algorithms Implemented

- **Linear Regression** – for continuous target prediction  
- **Logistic Regression** – for binary classification  
- **Decision Tree Classifier** – interpretable tree-based model  
- **Random Forest Classifier & Regressor** – ensemble method for improved performance  

Each algorithm is implemented using **Scikit-learn**, with proper documentation and comments.

---

##  Project: Rossmann Store Sales Forecasting

This project aims to predict daily sales for Rossmann drug stores based on historical sales data and external factors.

###  Steps Followed (as per Jovian’s ML Pipeline):

1. **Business Requirements**  
   - Understand sales patterns and prediction goals for Rossmann stores.

2. **Problem Identification**  
   - Regression problem: Predict continuous values (daily sales).

3. **Data Cleaning**  
   - Handled missing values, removed outliers, formatted dates.

4. **Data Preparation**  
   - Feature engineering, encoding categorical features, splitting data.

5. **Baseline Models**  
   - Implemented Linear Regression and Decision Tree to set baseline.

6. **Model Training & Evaluation**  
   - Applied Random Forest Regressor, optimized with GridSearchCV.  
   - Evaluated using RMSE, MAE, and R² Score.

7. **Regularization & Ensembling**  
   - Tried ensembling (Random Forest), compared models.

8. **Interpretation & Presentation**  
   - Visualized feature importances, actual vs. predicted sales.  
   - Summarized findings and model behavior.

---

## 🛠 Tools & Libraries

- Python  
- Scikit-learn  
- Pandas, NumPy  
- Matplotlib, Seaborn, Plotly
- Jupyter Notebooks
