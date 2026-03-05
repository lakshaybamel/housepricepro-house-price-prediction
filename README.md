# 🏠 HousePricePro – House Price Prediction (Regression)

## 📌 Project Overview

Accurate house price prediction is an important task in the real estate industry. Property values depend on many factors such as house size, number of bedrooms, bathrooms, location advantages, and other property characteristics.

In this project, we build a **machine learning regression system** to predict house prices based on property features. The goal is to analyze housing data and develop models that can estimate property prices using historical information.

The project demonstrates the use of **linear regression models and regularization techniques** to improve prediction stability and model interpretability.

---

## 🚨 Problem Statement

Real estate companies, property investors, and home buyers often struggle to determine a fair price for properties.

Manual price estimation can be inconsistent and subjective.

This project aims to solve that problem by using **machine learning models to predict house prices automatically based on property features**.

---

## 📊 Dataset Description

The dataset contains information about residential houses and their characteristics.

Key features include:

* **Area** – size of the house
* **Bedrooms** – number of bedrooms
* **Bathrooms** – number of bathrooms
* **Stories** – number of floors
* **Parking** – parking availability
* **Main road access**
* **Guest room availability**
* **Basement availability**
* **Air conditioning**
* **Preferred area location**
* **Furnishing status**

Target variable:

* **Price** – selling price of the house

---

## ⚙️ Machine Learning Pipeline

The project follows a complete machine learning workflow:

1️⃣ Data Understanding
2️⃣ Exploratory Data Analysis (EDA)
3️⃣ Data Preprocessing
4️⃣ Encoding Categorical Variables
5️⃣ Feature Scaling
6️⃣ Train-Test Split
7️⃣ Model Training
8️⃣ Model Evaluation and Comparison
9️⃣ Business Insights

---

## 🧠 Models Used

Three regression models were implemented:

### Linear Regression

Baseline model used to understand the relationship between house features and price.

### Ridge Regression

Applies **L2 regularization** to reduce model complexity and handle multicollinearity.

### Lasso Regression

Uses **L1 regularization**, which can shrink feature coefficients and perform feature selection.

---

## 📈 Evaluation Metrics

The models were evaluated using:

* **RMSE (Root Mean Squared Error)** – measures prediction error
* **R² Score** – measures how well the model explains price variance

---

## 🏁 Results

| Model             | RMSE      | R² Score |
| ----------------- | --------- | -------- |
| Linear Regression | 1,324,507 | 0.6529   |
| Ridge Regression  | 1,324,677 | 0.6528   |
| Lasso Regression  | 1,324,507 | 0.6529   |

### Key Observations

* All three models produced **very similar performance**.
* The dataset appears well-behaved and does not suffer heavily from multicollinearity.
* Regularization did not significantly improve performance over the baseline model.

The **Linear Regression model performs competitively while remaining simple and interpretable**.

---

## 📊 Key Insights

From the analysis:

* **House area strongly influences price**
* **Number of bathrooms significantly impacts property value**
* Houses with more **bedrooms and stories tend to have higher prices**
* Additional amenities such as **parking, air conditioning, and preferred location** also increase property value

---

## 💼 Business Impact

This model can help:

* **Real estate companies** estimate competitive property prices
* **Property investors** identify valuable investment opportunities
* **Home buyers** understand fair market value
* **Developers** identify which house features increase property value

Using machine learning for pricing enables **data-driven decision making in the real estate market**.

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📁 Project Structure

```
housepricepro-house-price-prediction
│
├── house_price_prediction.ipynb
├── housing_dataset.csv
├── requirements.txt
└── README.md
```

---

## ▶️ How to Run

Clone the repository:

```
git clone https://github.com/lakshaybamel/housepricepro-house-price-prediction.git
cd housepricepro-house-price-prediction
```

Install required dependencies:

```
pip install -r requirements.txt
```

Run the notebook:

```
jupyter notebook house_price_prediction.ipynb
```

---

## 🏁 Conclusion

This project demonstrates how regression models can be used to predict house prices using property data.

Although regularized models such as Ridge and Lasso were tested, **Linear Regression provided comparable performance while maintaining simplicity and interpretability**.

The project highlights how machine learning can assist in **property valuation, pricing strategy, and real estate analytics**.

---

## 👨‍💻 Author

**Lakshay Bamel**
