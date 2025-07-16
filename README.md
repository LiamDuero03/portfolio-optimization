# 📊 Portfolio Optimization & Stock Prediction ML Pipeline

This project combines **Modern Portfolio Theory (MPT)** with **Machine Learning** to create an enhanced portfolio analysis workflow.  

It includes:  
✅ **Traditional Portfolio Optimization** using historical returns & Monte Carlo simulations  
✅ **Machine Learning-based Stock Movement Prediction** with multiple models  
✅ A **multi-stock pipeline** that benchmarks model performance across different tickers  
✅ **ML-informed portfolio insights** for smarter allocation strategies  

---

## 🚀 Features

- **Portfolio Optimization**
  - Fetches historical stock prices via **yfinance**
  - Calculates annualized expected returns & risk (covariance matrix)
  - Simulates thousands of random portfolios
  - Plots the **Efficient Frontier** (Risk vs Return scatter plot)
  - Finds the **optimal Sharpe ratio portfolio**

- **Stock Movement ML Prediction**
  - Feature engineering with **returns, moving averages, volatility**
  - Binary classification of **next-day stock movement (Up/Down)**
  - Trains & compares **6 models**:
    - Logistic Regression  
    - Random Forest  
    - Support Vector Machine (SVM)  
    - XGBoost  
    - K-Nearest Neighbors (KNN)  
    - Naive Bayes  
  - Evaluates using **Accuracy, ROC-AUC, Confusion Matrix, ROC Curves**
  - Visualizes **feature importance & coefficients** for interpretable models

- **Multi-Stock Pipeline**
  - Runs the ML pipeline on **multiple tickers** (e.g., PLTR, SHOP, ARKK)
  - Summarizes the **best model per stock**
  - Visualizes **predictability across stocks** using ROC-AUC

---

## 🛠 Tech Stack

- **Python 3.12**
- `pandas`, `numpy` → data wrangling & analysis  
- `matplotlib`, `seaborn` → visualization  
- `yfinance` → stock data API  
- `scikit-learn` → ML models (Logistic Regression, RF, SVM, KNN, NB)  
- `xgboost` → Gradient Boosting model for tabular data  



