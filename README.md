# 💎 Diamond Price Predictor

This project analyzes a Kaggle dataset about diamonds to explore data patterns and build machine learning models (Random Forest & Decision Tree) that predict diamond prices based on their features. The project also includes a **Streamlit web app** for interactive predictions.

---

## 📊 Overview

- Performed **Exploratory Data Analysis (EDA)** to understand trends and correlations.
- Built and evaluated **Random Forest** and **Decision Tree** regression models.
- Created an **interactive frontend with Streamlit** where users can input diamond features and get price predictions.

---

## 🗂️ Dataset

- Source: [Kaggle - Diamonds Dataset](https://www.kaggle.com/datasets/shivam2503/diamonds)
- Features include:
  - Carat
  - Cut
  - Color
  - Clarity
  - Depth
  - Table
  - Dimensions (x, y, z)
  - Price (target)

---

## 🔍 EDA Highlights

- Checked missing values and data types.
- Visualized distribution of diamond prices and other features.
- Explored correlations between features (e.g., carat vs price).

---

## 🧠 ML Models

- **RandomForestRegressor** and **DecisionTreeRegressor**
- Evaluated using metrics like **RMSE** and **R²**
- Feature importance analysis to determine top predictors

---

## 🌐 Streamlit App

The app allows users to:
- Select diamond features (e.g., carat, cut, clarity)
- Get a real-time price prediction
- View underlying model performance

To run the app:
```bash
streamlit run app.py
