# 🍎 Apple Stock Analysis & Prediction Dashboard

An interactive dashboard for analyzing historical **Apple (AAPL)** stock data and predicting future prices using **Python**, **Streamlit**, and **Machine Learning** techniques.

---

## 📌 Project Overview

This project aims to:

* Analyze historical stock price movements of Apple (AAPL)
* Visualize data using interactive charts and dashboards
* Train a machine learning model to predict future stock prices
* Help users understand general market trends (educational purposes only)

---

## 🛠️ Tech Stack

* **Python 3**
* **Streamlit** – Interactive web dashboard
* **Yahoo Finance (yfinance)** – Stock data source
* **Pandas & NumPy** – Data processing
* **Matplotlib & Plotly** – Data visualization
* **Scikit-learn** – Machine Learning
* **Random Forest Regressor** – Prediction model

---

## ✨ Features

* 📄 Full historical stock data view
* 📊 Advanced Exploratory Data Analysis (EDA)
* 📈 Interactive charts for price & volume
* 🤖 Future price prediction (7–90 days)
* ⚙️ Adjustable model complexity
* 📥 Export data & predictions as CSV
* 🎨 Clean and modern UI with custom CSS

---

## 🧠 Machine Learning Model

* Algorithm: **Random Forest Regressor**
* Data split: **80% training – 20% testing**
* Evaluation metrics:

  * R² Score
  * RMSE
  * MAPE

> ⚠️ Predictions are based solely on historical data and are **not financial advice**.

---

## ▶️ How to Run the Project

### 1️⃣ Install Dependencies

```bash
pip install streamlit yfinance pandas numpy matplotlib seaborn plotly scikit-learn textblob
```

### 2️⃣ Run the Application

```bash
streamlit run main.py
```

### 3️⃣ Usage Steps

1. Select the desired date range from the sidebar
2. Choose analysis and prediction options
3. Click **🚀 Start Analysis**
4. Explore insights, charts, and predictions

---

## 📂 Project Structure

```text
📁 Apple-Stock-Analysis
│
├── main.py        # Main Streamlit application
├── README.md      # Project documentation
```


