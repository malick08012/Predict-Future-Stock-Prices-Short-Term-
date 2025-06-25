# Predict-Future-Stock-Prices-Short-Term-
A machine learning project to predict the next day's stock closing price using historical stock market data.The project utilizes real-time data from Yahoo Finance  and includes model evaluation and visualizations.

🔮 Predict Future Stock Prices (Short-Term):

This project uses machine learning to predict the **next day's closing stock price** based on historical stock data. It focuses on short-term forecasting using real stock prices from **Apple (AAPL)**, leveraging the "yfinance" API for data retrieval and Linear Regression for prediction.

📌 Task Objective:

- Use historical stock data to **predict the next day's closing price**
- Use features: Open, High, Low, Volume
- Train a **Linear Regression model**
- Evaluate using **RMSE** and **R² Score**
- Plot and compare **actual vs predicted** prices

📁 Dataset Used:

**Retrieved Using**: "yfinance" Python library

🤖 Models Applied:

  - **Linear Regression** (from sklearn.linear_model)
  - Trained on features: Open, High, Low, Volume
  - Target variable: Close


📊 Key Results & Findings:

| Stock  | RMSE  | R² Score | Next Day Predicted Price |
|--------|-------|----------|---------------------------|

| AAPL   | 1.16  | 1.00     | $225.34   |



- **Low RMSE** indicates strong predictive accuracy.
- **R² = 1.00** shows that the model captures almost all variation in the stock's price movement.
- Linear Regression performed exceptionally well, especially on smoother stock data like AAPL.

🛠️ Tools & Libraries:

- Python
- pandas, numpy, matplotlib
- sklearn (for modeling and evaluation)
- yfinance (for stock data fetching)


