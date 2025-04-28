
# London Housing Price Prediction

This project builds and evaluates multiple regression models to predict housing prices in London based on various features.

## 📂 Project Structure
- **Data:** `London.csv` (housing dataset)
- **Notebook:** Main Jupyter Notebook containing EDA, preprocessing, modeling, and evaluation.

## 🚀 Technologies Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- XGBoost

## 🔍 Project Overview

The project covers the following steps:
- **Exploratory Data Analysis (EDA):**  
  Initial data inspection, visualizations, and statistical analysis.
- **Data Preprocessing:**  
  Handling missing values, categorical encoding (OneHotEncoder), and feature scaling (StandardScaler).
- **Model Building:**  
  - Linear Regression
  - Ridge Regression
  - Lasso Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - XGBoost Regressor
- **Hyperparameter Tuning:**  
  Applied `RandomizedSearchCV` for optimizing model performance.
- **Model Evaluation:**  
  Evaluated using MAE, RMSE, and R² Score.

## 📈 Results
Multiple regression models were compared to find the best performer based on predictive accuracy.

## 📋 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Navigate to the project directory.
3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook and run all cells.

## 📦 Requirements
You can create a `requirements.txt` containing:
```
pandas
numpy
scikit-learn
seaborn
matplotlib
xgboost
```

## ✨ Acknowledgments
- Dataset: [Your Source] (if public, otherwise remove this)
- Inspiration for model selection and pipeline design from best practices in machine learning.
