# BitPredict 💰📈  
### Bitcoin Price Forecasting with TensorFlow

Welcome to the **BitPredict** project!  
This repository contains a comprehensive exploration of **time series forecasting using TensorFlow** to predict **Bitcoin prices**.  
The goal is to experiment with various deep learning models and highlight the **challenges of forecasting in open systems** like the cryptocurrency market.

> ⚠️ **Disclaimer**: This project is for **educational purposes only** and not financial advice.  
> Forecasting Bitcoin is **extremely challenging and often unreliable** due to the volatile nature of open markets.

---

## 📖 Project Overview

This project is a milestone in learning time series forecasting with TensorFlow. It covers:

### 🔧 Data Preparation
- Historical Bitcoin price data (2013-10-01 to 2021-05-18) sourced from **CoinDesk**
- Preprocessing and formatting for time series models

### 🧠 Time Series Concepts
- Handling **univariate** and **multivariate** time series
- Windowing data for supervised learning
- Creating **train/test splits** tailored to time-dependent data

### 📈 Modeling Experiments
A variety of models were built and tested:

- 🟡 **Naïve Forecast** (baseline)
- 🟢 **Dense Neural Networks**
- 🔵 **1D Convolutional Neural Networks (Conv1D)**
- 🟣 **LSTM (Long Short-Term Memory) Networks**
- 🟠 **Multivariate Models**  
  (e.g., including Bitcoin block reward size as an additional feature)
- 🔴 **N-BEATS Algorithm**
- 🟤 **Ensemble Models** using different loss functions

### 🔮 Future Forecasting
- Predicting Bitcoin prices into the future
- Visualizing the predicted trends

### 🧩 Uncertainty & Limitations
- Exploring **prediction intervals**
- Understanding **aleatoric and epistemic uncertainty**
- Discussing the **“Turkey Problem”** (Black Swan events)
- Emphasizing the **difficulty of forecasting in open systems** and the risks of **overfitting**

---

## 🚀 Getting Started

### 🔧 Prerequisites

- Python 3.7+
- TensorFlow 2.x
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook or Google Colab (recommended)

---