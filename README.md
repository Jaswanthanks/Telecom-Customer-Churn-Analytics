# Telecom-Customer-Churn-Analytics

# 🚀 Customer Churn Prediction System (End-to-End ML Pipeline)

## 📌 Overview

This project presents an **end-to-end machine learning pipeline** designed to predict customer churn in a telecom dataset. The objective is to identify customers likely to leave the service, enabling proactive retention strategies.

The solution covers the full lifecycle of a machine learning project — from **data preprocessing and exploratory analysis to model training, evaluation, and deployment readiness**.

---

## 🎯 Business Objective

Customer churn directly impacts revenue. This project aims to:

* Predict whether a customer will churn (Yes/No)
* Identify key factors influencing churn
* Enable data-driven retention strategies

---

## 🧠 Tech Stack

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn
* **Model:** Logistic Regression
* **Tools:** Jupyter Notebook

---

## 🔄 Project Pipeline

### 1️⃣ Data Ingestion

* Loaded dataset using Pandas
* Initial inspection (`head`, `info`, `describe`)

### 2️⃣ Data Cleaning

* Handled missing values (`Total Charges`)
* Removed irrelevant columns (e.g., CustomerID, location fields)
* Avoided dropping meaningful nulls (e.g., Churn Reason)

### 3️⃣ Exploratory Data Analysis (EDA)

* Churn distribution visualization
* Correlation heatmap
* Feature relationship analysis

### 4️⃣ Feature Engineering

* Encoded categorical variables
* Removed data leakage columns
* Created feature matrix (`X`) and target (`y`)

### 5️⃣ Model Building

* Train-test split with stratification
* Logistic Regression model training

### 6️⃣ Model Evaluation

* Accuracy Score
* Confusion Matrix
* Classification Report (Precision, Recall, F1-score)

### 7️⃣ Model Persistence

* Saved trained model using `joblib`

---

## 📊 Model Performance

*(Update this section after running your evaluation)*

* **Accuracy:** XX%
* **Precision:** XX%
* **Recall:** XX%
* **F1 Score:** XX%

---

## 🔍 Key Insights

* Customers with **higher monthly charges** are more likely to churn
* **Long-term customers** (higher tenure) show lower churn probability
* Certain service features significantly impact retention

---

## 🚀 Future Enhancements

* Implement advanced models (Random Forest, XGBoost)
* Hyperparameter tuning (GridSearchCV)
* Deploy using Streamlit / Flask
* Add real-time prediction API

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.

---




