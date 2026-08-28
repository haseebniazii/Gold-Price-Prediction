<h1 align="center">🥇 Gold Price Prediction 🥇</h1>

<p align="center">
  🚀 Machine Learning Project | 📈 Regression Model | 🌳 Random Forest Regressor
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikit-learn">
  <img src="https://img.shields.io/badge/Model-Random%20Forest-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Problem-Regression-purple?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
</p>

---

## 📌 About The Project

**Gold Price Prediction** is a Machine Learning regression project that predicts the price of gold based on historical market data and related financial features.

The project uses a **Random Forest Regressor** to learn patterns from historical data and predict the estimated gold price.

The complete Machine Learning workflow includes:

- Data Loading
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Selection
- Train-Test Split
- Model Training
- Model Evaluation
- Price Prediction

---

## 🎯 Objective

The main objective of this project is to build a Machine Learning model that can predict gold prices based on historical financial and market-related features.

---

## 📊 Dataset Features

The dataset contains historical gold price information and related market features.

Typical features include:

- 📅 Date
- 💵 Gold Price
- 📈 Market Indicators
- 💲 Currency / Exchange Rate
- 🛢️ Related Financial Features
- 📊 Historical Market Values

> The exact features depend on the dataset used in this project.

### 🎯 Target Variable

**Gold Price**

The model predicts the numerical gold price, making this a **Regression Problem**.

---

## 🤖 Machine Learning Model

### 🌳 Random Forest Regressor

This project uses **Random Forest Regressor**, an ensemble learning algorithm that combines multiple decision trees to make accurate numerical predictions.

Model:

```python
from sklearn.ensemble import RandomForestRegressor

model = RandomForestRegressor(
    n_estimators=100,
    random_state=42
)
