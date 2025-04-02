# 🏡 California Housing Price Prediction
---
## 📌 Project Overview

This project aims to predict housing prices in California using various machine learning models. The dataset is sourced from the sklearn.datasets.fetch_california_housing dataset and contains features like median income, house age, number of rooms, and more.

---

## 📊 Dataset Information

The California Housing dataset contains 8 features and 1 target variable (Median House Value):

|Feature      | Description|
|-------------|---------------------------|
|MedInc       |Median income in block group|
|HouseAge     |Median house age in block group|
|AveRooms     |Average number of rooms per household|
|AveBedrms    |Average number of bedrooms per household|
|Population   |Population in block group|
|AveOccup     |Average number of household members|
|Latitude     |Latitude coordinate|
|Longitude    |Longitude coordinate|

---

## 🛠️ Machine Learning Models Used

We trained multiple models and evaluated their performance:

| Model                       | Score (R^2) |
|-----------------------------|---------|
| Linear Regression           | 0.8372 |
|Ridge Regression             | 0.8368 |
| Decision Tree Regressor     | 0.9426 |
| Random Forest Regressor     | 0.9655 |
| XGBoost Regressor           | 0.9391 |

---

## 🔧 Data Preprocessing & Feature Engineering

Feature Scaling: Applied StandardScaler to normalize the numerical features.

Feature Engineering: Created new features such as Rooms per Household and Population Density.

Train-Test Split: Split dataset into 80% training and 20% testing.

---

## 🚀 How to Run the Project

Install dependencies:

pip install -r requirements.txt

Run the script to train models:

python model_training.py

View predictions and evaluation results.

---

## 📌 Conclusion

This project demonstrates the application of regression models for predicting housing prices. The best-performing model can be used for real-world applications such as property valuation and investment analysis.

---

## 📜 License

This project is open-source and free to use under the MIT License.

Author: Dhruv Agarwal

Happy Coding! 🚀