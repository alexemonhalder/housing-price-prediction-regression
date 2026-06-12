# 🏠 Housing Price Prediction using Regression Models

## 📌 Overview

This project explores how different regression models perform in predicting housing prices using a dataset similar to the Boston Housing dataset. The goal is to compare **Linear Regression, Ridge Regression, and Lasso Regression** and analyze how regularization impacts performance.

---

## 🎯 Objective

* Build multiple regression models
* Evaluate performance using standard metrics
* Compare results to identify the best model for prediction

---

## 📂 Dataset

* Source: https://raw.githubusercontent.com/jbrownlee/Datasets/master/housing.data
* No headers included, so column names were manually assigned
* Target variable: **MEDV (Median House Value)**

---

## 🧠 Models Used

* Linear Regression
* Ridge Regression
* Lasso Regression

---

## 📊 Evaluation Metrics

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* Mean Absolute Error (MAE)
* R² Score

---

## 📈 Results

| Model             | MSE     | RMSE   | R² Score | MAE    |
| ----------------- | ------- | ------ | -------- | ------ |
| Linear Regression | 24.2911 | 4.9286 | 0.6688   | 3.1891 |
| Ridge Regression  | 24.4772 | 4.9474 | 0.6662   | 3.1329 |
| Lasso Regression  | 24.4095 | 4.9406 | 0.6671   | 3.2535 |

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Scikit-learn

---

## 🚀 How to Run

```bash
git clone https://github.com/alexemonhalder/housing-price-prediction-regression
cd housing-price-prediction-regression
pip install -r requirements.txt
jupyter notebook
```

Open:

```
housing_price_prediction_regression.ipynb
```

---

## 📌 Key Insights

* All three models perform very similarly
* Linear Regression slightly outperforms others in R² score
* Regularization (Ridge/Lasso) has minimal impact on this dataset

---

## 🧾 Conclusion

This project shows how regression models behave on real-world data. While Linear Regression performed slightly better, Ridge and Lasso help understand model stability and regularization effects.

---

⭐ If you found this useful, feel free to star the repository!
