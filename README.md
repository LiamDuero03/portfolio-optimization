# 📊 Portfolio Optimization & Efficient Frontier
This project demonstrates **Modern Portfolio Theory (MPT)** by optimizing a portfolio of stocks using historical price data. It uses a **Monte Carlo simulation** to generate thousands of random portfolios, calculates their **expected return**, **risk (volatility)**, and **Sharpe ratio**, and visualizes the **Efficient Frontier**. Finally, it identifies the **optimal portfolio allocation** with the highest Sharpe ratio.

## 🚀 Features
✅ Fetches historical stock prices via **yfinance**  
✅ Calculates annualized expected returns & risk (covariance matrix)  
✅ Simulates thousands of random portfolios  
✅ Plots the **Efficient Frontier** (Risk vs Return scatter plot)  
✅ Finds the **optimal Sharpe ratio portfolio**  


## 🛠 Tech Stack
- **Python 3.12**
- `pandas` & `numpy` → data analysis  
- `matplotlib` & `seaborn` → visualization  
- `yfinance` → stock data API  

## 📈 Example Output
The notebook generates:  
- A **Risk vs Return scatter plot** of simulated portfolios  
- Color-coded **Sharpe ratios**  
- A printed table of **optimal portfolio weights**

💡 Modern Portfolio Theory (MPT): Introduced by Harry Markowitz, MPT helps investors optimize portfolios by balancing risk vs. return, resulting in an efficient frontier of optimal portfolios.


