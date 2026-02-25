📈 YES Bank Stock Closing Price Prediction
🏦 Domain

Financial Technology (FinTech)

🤖 Project Type

Supervised Machine Learning (Regression)

📌 Project Overview

YES Bank has been one of the most discussed stocks in the Indian financial sector, particularly after the 2018 liquidity crisis and corporate governance issues that triggered extreme volatility.

This project analyzes the historical stock journey of YES Bank (from inception to 2020) and builds a robust regression model to predict monthly closing prices.

The model is designed to handle:

📉 Extreme volatility

🔁 Structural breaks / regime changes

📊 Multicollinearity among stock variables

📈 Skewed financial distributions

🎯 Problem Statement

Can we accurately predict the monthly closing price of YES Bank stock using historical price features (Open, High, Low) while maintaining model stability during high-volatility periods?

🧠 Project Approach
1️⃣ Data Understanding

Monthly stock price dataset

Features used:

Open

High

Low

Close (Target Variable)

2️⃣ Exploratory Data Analysis (EDA)

Followed the UBM Rule:

🔹 Univariate Analysis

Distribution plots

KDE plots

Log transformation analysis

🔹 Bivariate Analysis

Correlation heatmap

Scatter plots

Trend visualization

🔹 Multivariate Analysis

Pair Plot (Log-transformed variables)

Multicollinearity analysis

Relationship strength validation

🔬 Data Preprocessing

✔ Handled missing values
✔ Log transformation applied to reduce skewness
✔ Checked and handled multicollinearity
✔ Feature scaling where necessary
✔ Cleaned and structured time-series format

📊 Key Insights

Strong positive correlation among Open, High, Low, and Close prices

Severe volatility observed post-2018 crisis

Log transformation improved linear relationships

Multicollinearity required careful model selection

Stock price behavior showed regime shifts

🏗 Model Building

Implemented multiple regression models and evaluated performance:

Linear Regression

Regularized Regression (if applied: Ridge/Lasso)

Performance comparison using:

R² Score

RMSE

MAE

Final model selected based on:

Stability

Interpretability

Error minimization

🧪 Model Evaluation

Evaluation Metrics Used:

📌 R² Score

📌 Mean Absolute Error (MAE)

📌 Root Mean Squared Error (RMSE)

The final model demonstrates strong predictive capability despite high volatility in the dataset.

💡 Technical Strengths

🔹 Production-grade modular code
🔹 Strict exception handling
🔹 Clean function-based architecture
🔹 Logical EDA following data science standards
🔹 Applied statistical reasoning (log transform & multicollinearity check)
🔹 Professional documentation

🛠 Tech Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

📈 Business Impact

Helps investors understand price behavior patterns

Assists in volatility-aware forecasting

Demonstrates how ML models behave during financial crises

Practical example of regression modeling in FinTech

🚀 Future Improvements

Add ARIMA / Time-Series models

Use LSTM for deep learning forecasting

Add feature engineering with macroeconomic indicators

Deploy as a web application

Integrate real-time stock API

👨‍💻 Author

Faizaan Bhati
B.Tech Final Year | AI/ML Enthusiast | FinTech Explorer
