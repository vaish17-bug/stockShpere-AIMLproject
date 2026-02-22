# 📈 StockSphere – AI Stock Price Predictor

## 🚀 Overview
StockSphere is an AI-powered stock analysis and prediction web application built using LSTM (Long Short-Term Memory) neural networks and Streamlit.

It provides stock insights, visualizations, price forecasting, and risk simulation.

---

## 🛠 Tech Stack
- Python
- TensorFlow / Keras
- LSTM Neural Network
- Streamlit
- yFinance API
- Pandas, NumPy
- Matplotlib, Seaborn

---

## 📊 Features
- 📥 Live stock data download
- 📈 Moving average analysis (MA100, MA200)
- 🤖 LSTM-based stock prediction
- 🔮 30-day future forecasting
- 🎮 Stock price simulator
- ⚠ Risk assessment using MAPE

---

## 🧠 Model Details
- 2-layer LSTM architecture
- 100-day time window
- MinMax scaling
- Trained on historical stock data

---

## ▶️ How to Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py