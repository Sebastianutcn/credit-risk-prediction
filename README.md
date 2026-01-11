# Credit Risk Prediction

This project focuses on **credit risk prediction** using machine learning techniques.
The notebook includes **exploratory data analysis (EDA)**, **feature engineering**, 
and **training & evaluation of multiple ML models**.

## Dataset
The dataset is automatically downloaded from Kaggle using `kagglehub`:
- Credit Risk Dataset

## Project Structure
- `credit-risk-prediction-training-and-eda.ipynb` – main notebook containing EDA and model training
- `README.md` – project overview
- `requirements.txt` – Python dependencies

## Main Steps
1. Data loading and inspection  
2. Exploratory Data Analysis (EDA)  
3. Handling missing values and feature preprocessing  
4. Model training and comparison using:
   - Scikit-learn models
   - Gradient boosting methods
   - AutoML frameworks (PyCaret, AutoGluon)
5. Model evaluation

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Scikit-learn
- XGBoost, LightGBM, CatBoost
- PyCaret, AutoGluon

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
