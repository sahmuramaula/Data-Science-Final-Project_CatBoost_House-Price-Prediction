# House Price Prediction with CatBoost

This project builds a predictive model for house prices using the CatBoost algorithm, applying manual hyperparameter tuning to improve performance. The dataset used is the King County house sales dataset from Kaggle, containing 21,613 entries with detailed features about house properties in King County, Washington.  

## 📊 Project Overview

- **Goal:** Predict house prices accurately by leveraging CatBoost and comparing it with other machine learning models (XGBoost, LightGBM, Gradient Boosting, Random Forest, Decision Tree, Linear Regression).  
- **Dataset:** King County house sales data (May 2014 – May 2015).  
- **Main algorithm:** CatBoost with manual hyperparameter tuning and early stopping.  
- **Evaluation metrics:** MAE, MSE, RMSE, R², and MAPE.  

## 📝 Features Used

- Numerical: `sqft_living`, `sqft_lot`, `bedrooms`, `bathrooms`, `floors`, `sqft_above`, `sqft_basement`, etc.  
- Engineered: `total_rooms`, `was_renovated`, `renovation_age`, `has_basement`.  

## ⚙️ Dependencies

Install required libraries with:
pip install -r requirements.txt
Or manually install main packages:
pip install numpy pandas scikit-learn catboost xgboost lightgbm matplotlib seaborn

## 🚀 How to Run

1. Clone this repository or download the notebook.
2. Open `House_Price_Prediction.ipynb` in Jupyter Notebook or JupyterLab.
3. Run all cells to see data cleaning, EDA, feature engineering, modeling, hyperparameter tuning, and evaluation results.

## 📈 Results

The best model achieved:
- MAE ≈ \$58,779.75  
- R² ≈ 0.9081  
indicating a highly accurate predictive performance on the test dataset.

## 📂 Files

- `House_Price_Prediction.ipynb` — Complete notebook containing data preparation, modeling, and evaluation.
- `requirements.txt` — List of Python packages needed to run the notebook.

## 📄 License

This project is for academic and research purposes only.

## 🙌 Acknowledgments

Dataset sourced from [Kaggle - House Sales in King County, USA](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction).
