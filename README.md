# 🍽️ FoodMood — ML-Powered Nutrition & Alertness Prediction

Predict how a meal may affect your energy, focus, and alertness before you eat it.

## 🚀 Overview

FoodMood is an end-to-end Machine Learning web application that predicts the short-term cognitive impact of meals using nutritional information. By analyzing calories, protein, carbohydrates, fat, sugar, and fiber, the system classifies meals into:

* 🟢 High Alertness
* 🟡 Moderate Alertness
* 🔴 Low Alertness

The project combines nutrition science, feature engineering, and machine learning to help users make smarter food choices for productivity and energy management.

---

## 🎯 Key Features

### 🤖 Machine Learning Prediction

* Predicts post-meal alertness levels
* Powered by a Gradient Boosting Classifier
* 74.7% classification accuracy

### 📊 Interactive Dashboard

* Nutrition breakdown and visualizations
* Meal-wise analytics
* Mood distribution tracking
* Calorie trend monitoring

### 📝 Meal Logging

* Save meal history
* Build a personal food-mood profile
* Track eating patterns over time

### 💡 Personalized Recommendations

* Time-aware nutrition suggestions
* Actionable tips based on prediction results
* Explainable AI insights showing influential features

---

## 🧠 Model Performance

| Model               | Accuracy  |
| ------------------- | --------- |
| Logistic Regression | 61%       |
| Random Forest       | 71%       |
| Gradient Boosting   | **74.7%** |

Gradient Boosting was selected as the final model due to its superior ability to capture complex relationships between nutritional features and alertness outcomes.

---

## ⚙️ Tech Stack

* Python
* Streamlit
* Scikit-Learn
* Pandas
* Plotly
* Joblib

---

## 📂 Project Structure

foodmood/

├── app.py

├── pipeline.py

├── foodmood_model.pkl

├── feature_cols.json

├── requirements.txt

└── README.md

---

## 🔬 Feature Engineering

The model uses 17 engineered nutritional features including:

* Protein Ratio
* Sugar Ratio
* Fat Ratio
* Balance Score
* Meal Heaviness
* High Sugar Flag
* High Protein Flag
* Heavy Meal Indicator

These features help the model better understand how meal composition affects cognitive performance.

---

## 📈 Results

* 74.7% prediction accuracy
* Supports 58+ Indian and international foods
* Provides explainable predictions
* Generates personalized nutrition insights

---

## 🚧 Future Improvements

* USDA FoodData Central API integration
* Real user mood feedback collection
* Sleep and activity-aware predictions
* Continuous glucose monitoring integration
* Support for 200+ food items
* Advanced deep learning models

---

## 📜 License

MIT License

---

## 👨‍💻 Author

Developed as an independent Machine Learning project exploring the relationship between nutrition, energy levels, and cognitive performance.

