# Hostel Mess Food Wastage Prediction Using Machine Learning
<p align="center">
  <img src=""Hostel%20Mess%20Food%20Wastage%20Prediction.png"" width="100%">
</p>

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-Enabled-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

Machine Learning-based hostel mess food wastage prediction system using attendance, menu patterns, and contextual features to optimize food preparation and reduce waste.

## Overview

This project predicts hostel mess food wastage using Machine Learning techniques. The system analyzes attendance patterns, menu characteristics, exam periods, and historical food waste data to optimize food preparation and reduce wastage.

---
## Key Highlights

- 📊 Analyzed 45,000+ food demand records
- 🤖 Implemented 5 Machine Learning algorithms
- 📈 Achieved R² Score of 0.958 using Gradient Boosting
- 🧠 Applied feature engineering using attendance, weather, and exam schedules
- ♻️ Designed to reduce hostel food wastage and improve operational efficiency

---

## Problem Statement

Hostel messes frequently face challenges in estimating food demand accurately. Variations in attendance, special meals, and academic schedules often result in excess food preparation and increased wastage.

This project develops a predictive system that forecasts food wastage before meal preparation.

---

## Dataset

Food Demand Forecasting Dataset (45,000+ records)

Files Used:

- train.csv
- meal_info.csv
- fulfilment_center_info.csv

---

## Feature Engineering

Features used:

- Attendance
- Food Category
- Cuisine
- Exam Period
- Weekend Indicator
- Weather Conditions
- Previous Day Waste
- Rolling Average Waste

---

## Algorithms Implemented

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor

---

## Performance Comparison

| Model | MAE | RMSE | R² |
|--------|--------|--------|--------|
| Linear Regression | 6.60 | 12.53 | 0.903 |
| Decision Tree | 5.55 | 11.12 | 0.923 |
| Random Forest | 4.48 | 8.31 | 0.957 |
| Gradient Boosting | 4.46 | 8.21 | 0.958 |
| XGBoost | 4.32 | 9.67 | 0.942 |

### Best Model

**Gradient Boosting Regressor**

R² Score = **0.958**

---

## Results

### Model Comparison

![Model Comparison](images/model%20graph.png)

### Feature Importance

![Feature Importance](images/feature%20importance.png)

### Actual vs Predicted

![Actual vs Predicted](images/actual%20predicted.png)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Matplotlib

---

## Future Scope

- QR-based Attendance System
- IoT Weight Sensors
- Real-time Dashboard
- Computer Vision Based Waste Detection

---

## Author

**Vansh Juneja**
