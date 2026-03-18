# 🚗 Car Price Prediction using Machine Learning

## 📌 Overview

This project focuses on predicting the **selling price of used cars** using Machine Learning techniques. A **Linear Regression model** is trained on historical car data to estimate prices based on key features such as vehicle age, price, usage, and specifications.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook (Anaconda)

---

## 📊 Dataset

**Dataset:** `cardata.csv`

### Features:

* `Year` – Manufacturing year of the car
* `Present_Price` – Current ex-showroom price
* `Kms_Driven` – Distance driven (in km)
* `Fuel_Type` – Petrol/Diesel/CNG
* `Seller_Type` – Dealer or Individual
* `Transmission` – Manual or Automatic
* `Owner` – Number of previous owners

### 🎯 Target:

* `Selling_Price` – Price at which the car is sold

---

## 🔄 Machine Learning Workflow

1. Data Collection & Loading
2. Data Preprocessing
3. Feature Encoding (Categorical → Numerical)
4. Train-Test Split
5. Model Training using Linear Regression
6. Model Evaluation (R² Score)
7. Price Prediction System

---

## 📈 Model Details

**Algorithm Used:** Linear Regression

Linear Regression is effective for predicting continuous values and helps establish a relationship between car features and selling price.

---

## ✅ Model Performance

* **Training Accuracy (R²):** ~0.88
* **Testing Accuracy (R²):** ~0.84

---

## 🔍 Example Prediction

**Input Features:**

```
Year = 2011  
Present_Price = 0.826  
Kms_Driven = 6000  
Fuel_Type = 0  
Seller_Type = 1  
Transmission = 0  
Owner = 0  
```

**Predicted Output:**

```
Selling Price ≈ 4.52 Lakhs
```

---

## 📁 Project Structure

```
Car-Price-Prediction/
│
├── cardata.csv
├── car_price_prediction.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 Future Improvements

* Use advanced models (Random Forest, XGBoost)
* Hyperparameter tuning
* Deploy as a web app using Flask/Streamlit
* Add visualization dashboard

---

## 👨‍💻 Author

**Balamurugan S**
Computer Science Student
Interested in Machine Learning & Data Science
