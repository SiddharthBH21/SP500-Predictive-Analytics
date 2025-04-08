# 📊 S&P 500 Predictive Analytics

# A data-driven approach to identifying high-potential stocks by combining technical indicators, time series forecasting, and sentiment analysis.


🚀 Overview

This project aims to automate the process of analyzing and forecasting S&P 500 stock performance using Python. Traditional stock screening is time-consuming and often based on manual observation of charts and news—this tool bridges that gap by integrating technical indicators, statistical modeling, and natural language processing into one streamlined pipeline.

The model pulls and processes more than a decade of historical data to evaluate price momentum and trends, then overlays financial news sentiment to offer a comprehensive stock selection framework. This enables faster, more confident, and more informed investment decisions.


📌 Objectives

● Reduce manual stock screening time through automation

● Analyze price momentum using technical indicators

● Forecast future stock trends using time series modeling (ARIMA)

● Use NLP to analyze financial news and understand market sentiment

● Combine quantitative and qualitative signals to shortlist high-opportunity stocks


🛠️ Tools & Technologies

● Python – Core language for data wrangling and modeling

● yfinance – API to pull historical S&P 500 stock data

● Pandas, NumPy – For technical indicators: RSI, MACD, ADX, Moving Averages

● Statsmodels – ARIMA time series forecasting

● VADER – For financial news sentiment analysis

● Matplotlib, Seaborn, Plotly – For data visualization


🔍 Key Features

● Automated Data Pulling
Pulls historical stock data for S&P 500 tickers from Yahoo Finance using the yfinance API.

● Technical Analysis Engine
Calculates key momentum indicators like Relative Strength Index (RSI), Moving Average Convergence Divergence (MACD), Average Directional Index (ADX), and moving averages to gauge price action.

● Time Series Forecasting
Applies the ARIMA model to forecast weekly price trends based on 10 years of historical data.

● Sentiment Analysis with NLP
Scrapes financial news for the relevant stocks and applies sentiment scoring to evaluate public and media perception.

● Stock Shortlisting Framework
Merges technical trends and sentiment insights to rank and identify stocks with upward momentum and positive sentiment.


📈 Results

The system successfully identified 3 high-potential stocks showing both strong technical indicators and positive media sentiment. These results demonstrate that blending time-tested financial indicators with real-time sentiment scoring offers a powerful approach to investment screening and decision-making.


📚 Future Work

● Add a dashboard interface using Streamlit or Power BI

● Expand analysis beyond the S&P 500 to global equities or ETFs

● Implement reinforcement learning for dynamic portfolio rebalancing


🤝 Contributions

Pull requests are welcome. If you'd like to improve this project, feel free to fork and contribute!


📬 Contact
For questions, collaborations, or feedback, feel free to connect:

📧 Email: sidbh@bu.edu
