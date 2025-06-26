# 📈 Stock Price Forecasting using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-LSTM/GRU-orange?logo=tensorflow)
![scikit-learn](https://img.shields.io/badge/sklearn-Regression%20Models-green?logo=scikitlearn)
![YahooFinance](https://img.shields.io/badge/DataSource-YahooFinance-lightgrey)

This project uses multiple machine learning models to predict and visualize future stock prices for top-performing companies including **Apple (AAPL)**, **Tesla (TSLA)**, **Amazon (AMZN)**, **Microsoft (MSFT)**, and **Meta (META)**. It compares performance across traditional and deep learning models with RMSE as the evaluation metric.

---

## 🚀 Models Implemented

- 🔁 **Linear Regression** – Baseline model for comparison
- 📈 **ARIMA** – Time-series specific modeling
- 🧠 **LSTM** – Deep learning model for sequential prediction
- 🧠 **GRU** – Gated Recurrent Unit, another RNN variant

Each model is developed and tested on real-time stock data fetched using Yahoo Finance.

---

## 📊 Performance Metric

All models were evaluated using **Root Mean Square Error (RMSE)**. The lower the RMSE, the better the model performance.

Results showed that **LSTM and GRU significantly outperform** the classical models in capturing long-term dependencies in stock price movement.

---

## 📂 Folder Structure

```
Stock-Price-Forecasting-ML/
├── notebooks/
│   ├── Jay_LinearRegression.ipynb
│   ├── Jay_ARIMA.ipynb
│   ├── Jay_LSTM.ipynb
│   ├── Jay_GRU.ipynb
│   └── Jay_ExecuteGRU.ipynb
├── report/
│   └── Final_Project_Report.docx
├── presentation/
│   └── Final-Presentation.pptx
├── README.md
```

---

## 🛠️ Tech Stack

- Python 3.8+
- pandas, numpy, matplotlib, seaborn
- scikit-learn, statsmodels
- tensorflow / keras
- yfinance (for data collection)
- Jupyter Notebooks

---

## 📌 Key Highlights

- ✔️ Applied **Principal Component Analysis (PCA)** for dimensionality reduction
- ✔️ Compared **5 companies** across **4 models**
- ✔️ Built end-to-end pipelines for preprocessing → modeling → visualization
- ✔️ Made interactive forecast comparisons

---

## 👨‍💻 Author

**Jaya Chandra Kadiveti**  
📧 [jkadiveti@clarku.edu](mailto:jkadiveti@clarku.edu)

---

> Project submitted for academic evaluation under Time Series Forecasting and Deep Learning coursework.