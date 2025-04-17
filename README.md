# Predicting Bitcoin Price Using Sentiment Analysis and Blockchain Data

This project explores the relationship between sentiment analysis, blockchain activity, and Bitcoin price fluctuations using data science and machine learning techniques. It aims to develop predictive models that estimate Bitcoin's price movement based on hourly on-chain metrics, news sentiment, and price action.

## Project Description

The project combines sentiment analysis on Ethereum-related news (as a proxy for crypto sentiment), on-chain blockchain data, and historical Bitcoin price data to build a predictive model. The primary objective is to investigate how these different data types correlate with Bitcoin’s hourly price changes and to use them to forecast the closing price of Bitcoin.

## Contents

- `notebooks/` – Jupyter Notebooks for:
  - Data preprocessing
  - Exploratory data analysis
  - Feature engineering
  - Model training (ML/DL)
  - Time series forecasting: ARIMA

## ⚙️ Tech Stack

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn, XGBoost
- VADER Sentiment (NLTK)
- Statsmodels (for ARIMA)
- TensorFlow / Keras (for LSTM models)

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/bitcoin-price-prediction-defi.git
   cd bitcoin-price-prediction-defi
