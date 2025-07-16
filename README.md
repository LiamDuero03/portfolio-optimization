# 📊 Portfolio Optimization & Efficient Frontier
This project demonstrates **Modern Portfolio Theory (MPT)** by optimizing a portfolio of stocks using historical price data. It uses a **Monte Carlo simulation** to generate thousands of random portfolios, calculates their **expected return**, **risk (volatility)**, and **Sharpe ratio**, and visualizes the **Efficient Frontier**. Finally, it identifies the **optimal portfolio allocation** with the highest Sharpe ratio.

## 🚀 Features
✅ Fetches historical stock prices via **yfinance**  
✅ Calculates annualized expected returns & risk (covariance matrix)  
✅ Simulates thousands of random portfolios  
✅ Plots the **Efficient Frontier** (Risk vs Return scatter plot)  
✅ Finds the **optimal Sharpe ratio portfolio**  

## 📂 Project Structure
portfolio-optimization/
├── notebooks/
│ └── portfolio_optimization.ipynb # Main Jupyter Notebook
├── requirements.txt # Dependencies
└── README.md # Project overview

markdown
Copy
Edit

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

Example Efficient Frontier plot:  
![Efficient Frontier Example](https://user-images.githubusercontent.com/placeholder/efficient_frontier.png)  
*(You can replace this with your actual plot image)*

## ▶️ How to Run
1️⃣ **Clone the repo**  
```bash
git clone https://github.com/YOUR_USERNAME/portfolio-optimization.git
cd portfolio-optimization
2️⃣ Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Run the notebook

bash
Copy
Edit
jupyter notebook notebooks/portfolio_optimization.ipynb
✅ Next Steps
Add exact optimization using cvxpy

Include constraints (e.g., max 30% allocation per stock)

Build an interactive Streamlit app

💡 Modern Portfolio Theory (MPT): Introduced by Harry Markowitz, MPT helps investors optimize portfolios by balancing risk vs. return, resulting in an efficient frontier of optimal portfolios.

Author
👤 Your Name
📧 your.email@example.com
🔗 Your Portfolio Website

pgsql
Copy
Edit

✅ **This is ONE file, no gaps.**  

Would you like me to also **generate a downloadable `README.md` file** for you?
