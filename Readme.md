# Car Price Prediction using Machine Learning

## Overview
This project predicts the **selling price of used cars** using Machine Learning.  
A **Linear Regression model** is trained on historical car data to estimate the selling price based on various features.

The model analyzes attributes such as car age, present price, kilometers driven, fuel type, seller type, transmission, and number of previous owners.

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Linear Regression  
- Jupyter Notebook (Anaconda)

---

## Dataset
**Dataset used:** cardata.csv

Main features include:  
- Year  
- Present_Price  
- Kms_Driven  
- Fuel_Type  
- Seller_Type  
- Transmission  
- Owner

**Target variable:** Selling_Price

---

## Machine Learning Workflow
1. Import required libraries  
2. Load dataset  
3. Data preprocessing  
4. Feature encoding  
5. Train-test split  
6. Train Linear Regression model  
7. Evaluate model using R² score  
8. Build a predictive system

---

## Model Used
**Linear Regression**

Linear Regression is used to predict **continuous values**, making it suitable for estimating car prices.

---

## Model Evaluation
Model performance is evaluated using **R² Score**.

Example output:  
Training Accuracy: ~0.88  
Testing Accuracy: ~0.84

---

## Example Prediction

Input:  
`(2011, 0.826, 6000, 0, 1, 0, 0)`

Output:  
Predicted Selling Price: 4.52

---

## Project Structure

```

Car-Price-Prediction/
│
├── cardata.csv
├── car_price_prediction.ipynb
├── README.md
└── requirements.txt

```

---

## Author
Balamurugan S  
Computer Science Student  
Interested in Machine Learning and Data Science
