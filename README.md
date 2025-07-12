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

#### 1. **Business Requirements**
- Understood the business goal: forecast sales for each store to help with inventory and staffing.
- Analyzed the dataset context: store attributes, promotions, holidays, and time-based features.

#### 2. **Problem Identification**
- Defined it as a **supervised regression** problem.
- Target variable: `Sales` (a continuous numeric value).

#### 3. **Data Cleaning**
- Merged `train.csv` and `store.csv` on the `Store` column.
- Converted the `Date` column to `datetime` format.
- Removed rows where `Open == 0` since they had zero sales.
- Verified and handled missing values (imputation when necessary).

#### 4. **Data Preparation**
- Created new features from the `Date` column (`Day`, `Month`, `Year`).
- Encoded categorical variables using `OneHotEncoder`.
- Scaled numerical features using `MinMaxScaler`.
- Split the data into training and validation sets.
- Used `ColumnTransformer` and `Pipeline` to bundle preprocessing.

#### 5. **Baseline Models**
- Implemented a naive baseline model that predicted the mean sales.
- Implemented **Linear Regression** and **Decision Tree Regressor** as initial models.
- Compared their RMSE scores with the baseline.

#### 6. **Model Training & Evaluation**
- Trained a **Random Forest Regressor**.
- Evaluated model performance using **RMSE** on both training and validation sets.

#### 7. **Regularization & Ensembling**
- Focused on ensembling via **Random Forest** only.

#### 8. **Interpretation & Presentation**
- Extracted and visualized **feature importances** from the Random Forest model.
- Plotted top features and compared actual vs predicted sales visually using graphs.

---

## 🛠 Tools & Libraries

- Python  
- Scikit-learn  
- Pandas
- Numpy  
- Matplotlib, Seaborn, Plotly
- Jupyter Notebooks
