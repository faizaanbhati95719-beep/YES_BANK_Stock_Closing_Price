
---

# 🚀 YES Bank Stock Closing Price Prediction

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge\&logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Regression-orange?style=for-the-badge\&logo=scikitlearn)
![Domain](https://img.shields.io/badge/Domain-FinTech-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)
![EDA](https://img.shields.io/badge/EDA-UBM%20Rule-purple?style=for-the-badge)

</p>

---

## 🏦 About The Project

YES Bank became one of the most volatile stocks in the Indian financial sector after the **2018 liquidity crisis**.
This project analyzes its historical monthly stock data (from inception to 2020) and builds a **robust regression model** to predict closing prices while handling:

* 📉 Extreme volatility
* 🔁 Regime shifts
* 📊 Multicollinearity
* 📈 Positive skewness

This is a **production-grade ML project** built using data science best practices.

---

## 🎯 Objective

To predict the **monthly closing price** of YES Bank stock using historical price features (Open, High, Low) while ensuring model stability and interpretability.

---

## 🧠 Data Science Workflow

### 🔎 1. Exploratory Data Analysis (UBM Rule)

✔ **Univariate Analysis** – Distribution, KDE plots, skewness detection
✔ **Bivariate Analysis** – Correlation heatmaps, scatter relationships
✔ **Multivariate Analysis** – Pair plots, interaction validation

---

### 🧹 2. Data Preprocessing

* Log Transformation (handled skewness)
* Multicollinearity check
* Feature scaling
* Clean modular pipeline
* Exception handling

---

### 📊 3. Key Insights

* Strong positive correlation among Open, High, Low, Close
* Severe volatility post-2018 crisis
* Log transformation improved linear structure
* High multicollinearity required careful modeling
* Clear structural regime shifts in stock behavior

---

## 🏗 Model Development

Implemented and compared multiple regression models:

* 🔹 Linear Regression
* 🔹 Regularized Regression (Ridge / Lasso if applied)

### 📏 Evaluation Metrics

* R² Score
* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)

✔ Final model selected based on performance stability and interpretability.

---

## 📈 Sample Visualization

Pair Plot of Log-Transformed Variables:
(Open, High, Low, Close showed strong linear relationships)

*(You can insert your image here later using:)*

```markdown
![Pair Plot]
images/pairplot.png
```

---

## 🛠 Tech Stack

| Tool            | Purpose                |
| --------------- | ---------------------- |
| 🐍 Python       | Core Programming       |
| 📊 Pandas       | Data Handling          |
| 🔢 NumPy        | Numerical Operations   |
| 📈 Matplotlib   | Visualization          |
| 🎨 Seaborn      | Advanced Visualization |
| 🤖 Scikit-Learn | Machine Learning       |

---

## 📂 Project Structure

```
YES-Bank-Stock-Prediction/
│
├── data/
│
├── EDA/
│   ├── EDA_Submission.ipyb 
├──ML/
│   ├── ML_Submission.ipyb
│
├── models/
└── README.md
```

---

## 💡 What Makes This Project Strong?

✔ Production-style modular code
✔ Strict exception handling
✔ Financial crisis-aware modeling
✔ Statistical reasoning applied (log transform + multicollinearity handling)
✔ Clean documentation
✔ Recruiter-ready presentation

---

## 🚀 Future Improvements

* 📈 ARIMA Time-Series Modeling
* 🧠 LSTM Deep Learning Forecasting
* 🌍 Real-time stock API integration
* 💻 Deploy as Web App (Streamlit / Flask)
* 📊 Add macroeconomic indicators

---

## 👨‍💻 Author

**Faizaan Bhati**
🎓 B.Tech Final Year
🤖 AI/ML Enthusiast
📊 FinTech Explorer

---
