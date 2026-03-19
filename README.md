# 📊 Forecasting Inflation Trends and Detecting Price Shocks Using Indian Price Index Data

## 📌 Overview

This project builds an end-to-end machine learning system to analyze, forecast, and monitor inflation trends in India using time series data. It uses CPI (Consumer Price Index) and WPI (Wholesale Price Index) to predict inflation and detect sudden price shocks.

The project follows a complete ML lifecycle:
**Data Collection → Cleaning → Analysis → Modeling → Deployment**

---

## 🎯 Objectives

- Forecast future inflation trends (CPI)
- Analyze relationship between CPI and WPI
- Detect abnormal price spikes (price shocks)
- Build a deployable ML application

---

## 📂 Dataset

- CPI (Consumer Price Index)
- WPI (Wholesale Price Index)

✔ Monthly time series data
✔ Cleaned and merged dataset

---

## ⚙️ Tech Stack

### 📊 Data Processing

- Pandas
- NumPy

### 📈 Visualization

- Matplotlib

### 🤖 Machine Learning

- Scikit-learn (Linear Regression)
- Statsmodels (ARIMA, SARIMA)

### 🧠 Feature Engineering

- Lag Features
- Rolling Mean
- Percentage Change

### 🚨 Anomaly Detection

- Threshold-based shock detection

### 🌐 Deployment

- Streamlit (Dashboard)
- Flask / FastAPI (API - optional)

### 🗂️ Tools

- Jupyter Notebook
- Git & GitHub

---

## 🧱 Project Structure

```id="final_struct_01"
inflation-forecasting-india/
│
├── data/
│   ├── raw/                  # Original data (ignored)
│   ├── processed/
│       └── final_dataset.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_feature_engineering.ipynb
│   ├── 04_model.ipynb
│   ├── 05_shock_detection.ipynb
│
├── app/
│   ├── streamlit_app.py
│
├── models/
│   ├── model.pkl
│
├── outputs/
│   ├── plots/
│   ├── forecasts/
│
├── requirements.txt
├── README.md
```

---

## 🔧 Workflow

1. Data Collection
2. Data Cleaning & Preprocessing
3. Dataset Merging
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Model Building (ML + ARIMA)
7. Price Shock Detection
8. Deployment

---

## 📈 Models Used

- Linear Regression (baseline)
- ARIMA (time series forecasting)

---

## 🚨 Price Shock Detection

Price shocks are detected using percentage change thresholds in CPI.

---

## 🚀 Deployment

- Streamlit dashboard for visualization and predictions
- API support (optional)

---

## 📦 Installation

```bash
pip install -r requirements.txt
```

---

## ▶️ Run App

```bash
streamlit run app/streamlit_app.py
```

---

## 🔮 Future Work

- Add LSTM (Deep Learning)
- Include more economic indicators
- Deploy on cloud platforms

---

## 👨‍💻 Author

Manthru
