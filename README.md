# 🏠 House Price Prediction using Machine Learning

This project focuses on building an end-to-end *House Price Prediction system* using Machine Learning techniques.  
The objective is to predict house prices based on multiple features after performing data preprocessing, exploratory data analysis (EDA), and model evaluation.


## 📌 Project Overview

The workflow includes:
- Data cleaning and handling missing values
- Exploratory Data Analysis (EDA)
- Feature scaling
- Training and comparing multiple regression models
- Model evaluation using *cross-validation (R² score)*
- Hyperparameter tuning using *GridSearchCV*
- Visualizing model performance using prediction plots

After comparing different models, *Gradient Boosting Regressor* was selected as the final model and achieved an *R² score of ~89%*.


## 🧠 Machine Learning Models Used

The following regression models were trained and evaluated:
- Support Vector Regression
- Linear Regression  
- Stochastic Regressor
- Gaussian Process Regressor
- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- XGBoost Regressor  

Cross-validation was used to fairly compare model performance.


## ⚙️ Hyperparameter Tuning

Hyperparameter tuning was performed on the best-performing model (*Gradient Boosting Regressor) using **GridSearchCV* to further improve performance.

Parameters tuned include:
- n_estimators
- max_depth
- learning_rate



## 📊 Model Performance Visualization

The plot below shows the relationship between *Actual vs Predicted House Prices* on validation data.

<img width="1800" height="1800" alt="Actual vs Predicted House Prices" src="https://github.com/user-attachments/assets/030e3d10-2a23-40d6-b913-8f223ba0eb69" />


The closer the points are to the diagonal line, the better the model’s predictions.

---

## 🛠 Tech Stack

- *Programming Language:* Python  
- *Libraries:*  
  - Pandas, NumPy  
  - Matplotlib, Seaborn  
  - Scikit-learn  


## 🚀 Results

- Best Model: *Gradient Boosting Regressor*
- Evaluation Metric: *R² Score*
- Final Performance: *~89% R²*

---

## 📌 Key Learnings

- Importance of data preprocessing and feature scaling
- Model selection using cross-validation
- Identifying and tuning the right hyperparameters
- Interpreting regression performance visually

---

## 🙌 Acknowledgements

This project was built as a learning exercise using publicly available datasets and online resources.
