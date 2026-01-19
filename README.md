<h1>Gold Price Prediction Using Machine Learning</h1>

👉Summary

A machine learning project that predicts gold prices using historical market data and evaluates performance with robust regression metrics.

👉Overview

This project builds a predictive machine learning model to estimate gold prices based on historical data. The goal is not "guessing" prices magically, but learning statistical patterns from data and measuring how well the model generalizes.

This project follows a proper ML pipeline: data loading → exploration → preprocessing → model training → evaluation → visualization.

👉Problem Statement

Gold price prediction is challenging due to:

Market volatility 📉📈

Dependency on multiple correlated financial indicators

Non‑linear relationships in data

📊 Dataset
📁 Source <a href="https://github.com/rajan-kumar-mu1439/gold-price-prediction-ml/blob/main/Gold_price_dataset.csv">Gold financial market dataaet</a>

Target Variable

GLD (Gold Price)

👉 Tools & Technologies

 Python, NumPy, Pandas, Matplotlib / Seaborn, Scikit‑learn, RandomForestRegressor, Jupyter Notebook

👉 Methods & Workflow

1️⃣ Data Loading & Inspection

2️⃣ Exploratory Data Analysis (EDA)

3️⃣ Data Preprocessing

4️⃣ Model Training

5️⃣ Model Evaluation


💡 Key Insights

Gold prices show strong correlation with certain financial indices

Random Forest captures complex non‑linear patterns better than linear models

High R² score indicates strong predictive performance

👉Dashboard / Model Output

<img width="1536" height="1011" alt="dashboard" src="https://github.com/user-attachments/assets/ba8759b6-3dad-48a9-bffe-dd21be49d009" />

🔹 Visualizations Included

Correlation heatmap

Actual vs Predicted Gold Prices plot

Feature importance chart

🔹 Model Performance

Train Data: 80%

Test Data: 20%

R² Score: 99% (dataset‑dependent)

✅ Results & Conclusion

The model successfully learns relationships between gold prices and market indicators

Random Forest performs significantly better than naive regression

The project demonstrates a correct ML workflow, not just accuracy chasing


👉 Future Work

 Time‑series specific models (ARIMA, LSTM)

 Macroeconomic indicators integration

 Real‑time data via APIs

 Web‑based interactive dashboard (Streamlit)

👤 Author & Contact

Rajan Kumar

📧 Email: rajankumarmu1439@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/rajan-kumar-mu1439
