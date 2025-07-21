# Project-Stock-price-prediction-using-ML-Neural-Network-Web-app-python

This project predicts future stock prices using historical data and a Long Short-Term Memory (LSTM) neural network. Built with Python, Keras, and Streamlit, the app lets users input any stock ticker (from Yahoo Finance) and visualize predicted trends alongside historical prices.

---

## 🔧 Features

- 📉 Predict future stock prices using LSTM model
- 💻 Interactive web app built with Streamlit
- 📊 Data pulled live from Yahoo Finance using `yfinance`
- 📈 Graphs of real vs predicted stock values
- 🧠 Model built with TensorFlow/Keras
- 🔍 Custom input for any stock ticker (e.g., `AAPL`, `TSLA`, `INFY.NS`)

---

## 🚀 Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **ML/DL**: Keras, TensorFlow
- **Data Source**: Yahoo Finance via `yfinance` package
- **Visualization**: Matplotlib, Plotly

---

## 🧠 Model Architecture

The core model is a Sequential LSTM network:
- Input layer reshaped for time-series
- 2 LSTM layers
- Dense output layer predicting the closing stock price
- Trained on normalized closing price data

---

## 📦 Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/your-username/stock-price-predictor.git
cd stock-price-predictor
pip install -r requirements.txt

├── web_stock_price_predictor.py   # Streamlit web app
├── stock_model.ipynb              # Model training and analysis
├── Latest_stock_price_model.keras # Saved LSTM model
├── requirements.txt               # Python dependencies
└── README.md

