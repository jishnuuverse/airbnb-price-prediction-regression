# 🏠 Airbnb Price Prediction using Machine Learning

## 📌 Overview

This project aims to predict Airbnb listing prices using machine learning models based on features like location, room type, availability, and reviews.

---

## 📊 Dataset

* Contains Airbnb listings from multiple cities
* ~290,000 entries with features such as:

  * Latitude & Longitude
  * Room Type
  * Number of Reviews
  * Availability (days/year)
  * Minimum Nights
  * Price (target variable)

---

## 🧹 Data Preprocessing

* Removed irrelevant columns (ID, names, etc.)
* Handled missing values
* Converted categorical variables using one-hot encoding
* Removed outliers in price
* Feature selection and basic feature engineering

---

## 🤖 Models Used

* Linear Regression
* Random Forest Regressor
* Gradient Boosting Regressor

---

## 📈 Evaluation Metrics

* Mean Squared Error (MSE)
* R² Score

---

## 🏆 Results

| Model             | R² Score | MSE       |
| ----------------- | -------- | --------- |
| Linear Regression | 0.72     | 24429     |
| Random Forest     | **0.78** | **18637** |
| Gradient Boosting | 0.77     | 20991     |

👉 **Random Forest performed the best** with highest R² and lowest error.

---

## 📊 Visualizations

* Actual vs Predicted plot
* Residual plot
* Feature importance
* Model comparison chart

---

## 🚀 Conclusion

Random Forest outperformed other models by effectively capturing non-linear relationships in the data, making it the most suitable model for Airbnb price prediction.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## 📌 How to Run

1. Clone the repository
2. Install required libraries
3. Run the Python script or notebook

---

## 🔮 Future Improvements

* Hyperparameter tuning
* Use advanced models like XGBoost
* Deploy as a web application using Flask

---
