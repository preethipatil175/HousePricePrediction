# 🏠 House Price Prediction (Machine Learning + Streamlit)

Welcome! This project predicts **California house prices** using a **Linear Regression model** built with `scikit-learn`, and features a simple web app frontend built using **Streamlit**.

---

## 📌 Project Overview

This repository contains:
- A **trained Linear Regression model** to predict house prices based on housing features.
- A **Streamlit app** (`app.py`) that allows users to enter feature values and get a predicted house price.
- Supporting files like a saved **model**, **scaler**, and **requirements.txt**.

This project demonstrates a complete workflow for a machine learning project — from data preprocessing and model training to deployment as a web app.

---

## 🧠 Features Used

The model was trained on the California Housing dataset using these features:

| Feature | Description |
|---------|-------------|
| MedInc | Median income |
| HouseAge | Median house age |
| AveRooms | Average number of rooms |
| AveBedrms | Average number of bedrooms |
| Population | Population in block |
| AveOccup | Average occupancy |
| Latitude | Geographic latitude |
| Longitude | Geographic longitude |

The model predicts the **house price** based on these inputs.

---
🚀 How to Run the Project Locally

``` 
1️⃣ Clone the repository
    git clone https://github.com/preethipatil175/HousePricePrediction.git

2️⃣ Navigate to the project directory
    cd HousePricePrediction

3️⃣ Install the required dependencies
    pip install -r requirements.txt

4️⃣ Run the Streamlit application
    streamlit run app.py

5️⃣ View the app
    After running the command, Streamlit will open the app automatically in your browser.
```
---

File Structure
```
HousePricePrediction/
├── app.py              # Streamlit app code
├── model.pkl           # Saved trained model
├── scaler.pkl          # Saved scaler for normalization
├── requirements.txt    # Project dependencies
└── README.md
```
---
