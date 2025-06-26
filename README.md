# 🌾 Crop Yield Prediction using Machine Learning (SDG 2: Zero Hunger)

## 📌 Project Overview

This project presents an AI-driven solution to support **Sustainable Development Goal 2: Zero Hunger** by predicting crop yield using supervised machine learning techniques. Accurate crop yield forecasting can empower farmers, policymakers, and agri-tech startups to optimize resource use, reduce waste, and make informed agricultural decisions—ultimately contributing to global food security.

The model uses data including **area planted, annual rainfall, fertilizer usage, and pesticide application** to estimate **yield per hectare** for various crops. The solution was built and evaluated using Python and scikit-learn libraries.

---

## 🎯 Problem Statement

Agricultural productivity is sensitive to environmental and resource factors. Predicting yield based on historical data can help mitigate risks like overuse of fertilizers or crop failure due to poor rainfall.

By using AI/ML to forecast yield, this project addresses:
- **Food insecurity and hunger**
- **Poor planning and distribution of resources**
- **Data-driven decision making in agriculture**

---

## 🧠 Machine Learning Approach

We applied a **supervised regression model** using the **Random Forest Regressor** algorithm. This ensemble model is well-suited for complex relationships and handles nonlinearities between features like rainfall and crop yield efficiently.

### Features Used
- `Area` (in hectares)
- `Annual_Rainfall` (in mm)
- `Fertilizer` (kg or cost-based)
- `Pesticide` (kg or cost-based)

### Target Variable
- `Yield` (production per hectare)

---

## 📊 Dataset

The dataset was sourced from an open Kaggle dataset on Indian crop production statistics (1997 onward). It contains:
- Crop name and type
- Year and season
- State-wise agricultural inputs and outcomes

Data preprocessing included:
- Handling missing values
- Feature selection
- Train-test split (80:20 ratio)

---

## ⚙️ Tools & Libraries

- Python
- Pandas
- scikit-learn
- Matplotlib

---

## 📈 Model Training and Results

We trained a Random Forest model on the cleaned dataset. The model was evaluated using **Mean Absolute Error (MAE)**, a common metric in regression tasks that represents the average absolute difference between predicted and actual yields.

### ✅ **Result:**
