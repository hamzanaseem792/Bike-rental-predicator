# Bike-rental-predicator
# 🚲 Bike Rental Predictor using Deep Learning

This project uses weather and calendar data to predict the **number of daily bike rentals** using a deep learning model built with Keras.

---

## 🎯 Goal
Predict how many bikes will be rented in a day based on:
- Temperature & humidity
- Season & month
- Weekday, holiday, and working day
- Weather situation

---

## 🔧 Tools Used
- Python, Pandas, NumPy
- TensorFlow/Keras
- Scikit-learn
- Matplotlib, Seaborn

---

## 📈 Project Workflow
1. **Data Cleaning** — Removed unnecessary columns (`instant`, `casual`, `registered`)
2. **Feature Engineering** — Extracted date parts, one-hot encoded season & weather
3. **Model Building** — 2-layer dense neural network trained with early stopping
4. **Evaluation** — MAE: _XX_, R² Score: _XX_  
5. **Visualization** — Predicted vs actual bike rentals

---

## ✅ Results
- The model was able to generalize well to unseen data
- Temperature, season, and humidity had high correlation with rental volume

---

## 🚀 Future Steps
- Deploy the model using **Streamlit** (coming soon)
- Add real-time weather integration
- Improve accuracy with ensemble models

---

## 📂 Dataset
Source: [UCI Bike Sharing Dataset](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset)
