# **Stock Price Sentiment Prediction**

This project explores the relationship between financial sentiment and stock price movements by integrating machine learning and natural language processing (NLP). Using historical stock price data from the Yahoo Finance API and financial news headlines from NewsAPI, I aim to assess whether sentiment trends can enhance traditional stock price forecasting. So far, I have collected and cleaned stock price data, retrieved financial news, and implemented basic sentiment analysis using VADER. The next steps include improving sentiment classification with FinBERT, merging sentiment data with stock prices, and applying machine learning models such as LSTM, ARIMA, or Prophet for time-series forecasting. This project is actively being developed, with planned enhancements in deep learning-based sentiment analysis, stock-sentiment correlation analysis, and predictive modeling.


🎯 ## **Objectives**

- Collect and preprocess **stock price data** (Yahoo Finance).
- Fetch and analyze **financial sentiment data** (NewsAPI, Twitter, Reddit).
- Apply **sentiment classification models** (VADER, FinBERT).
- Use **time-series forecasting models** (ARIMA, LSTM, Prophet).
- Compare **sentiment-based vs. technical indicator-based predictions**.
- Build an **interactive dashboard** for visualization (optional).
- Incorporate Monte Carlo Simulations using a Sentiment Index

## **🔗 Data Sources & APIs**

- **Stock Price Data:** Yahoo Finance API (yfinance)
- **Sentiment Data:** NewsAPI (financial news)
- **(Optional) Social Media Sentiment:** Twitter API, Reddit API

## **🛠️ Tech Stack & Tools**

- **Python** (Pandas, NumPy, Scikit-learn, TensorFlow/PyTorch)
- **Natural Language Processing (NLP)**: VADER, FinBERT
- **Machine Learning Models**: ARIMA, LSTM, Prophet
- **Data Visualization**: Matplotlib, Seaborn, Plotly
- **Deployment**: Docker, Streamlit
