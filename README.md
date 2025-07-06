# week_3_Carbon_Emission_Prediction

# 🌍 CO₂ Emissions Forecasting Using Random Forest

This project builds a **Random Forest Regression model** to forecast **CO₂ emissions per capita** for selected countries over the next 20 years based on historical environmental and economic indicators.

---

## 📑 Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Setup & Installation](#setup--installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Outputs](#outputs)
- [Author](#author)

---

## 🎯 Project Overview

**Problem:** Estimating future CO₂ emissions per capita is essential for sustainability planning and policy decisions.

**Solution:** Build a Random Forest model using **Recursive Feature Elimination with Cross Validation (RFECV)** to select important features and predict emissions based on Compound Annual Growth Rate (CAGR) of features for forecasting.

---

## ✨ Features

✅ Loads cleaned historical data  
✅ Removes outliers (e.g. ARE data)  
✅ Selects optimal features using **RFECV**  
✅ Tunes hyperparameters with **RandomizedSearchCV**  
✅ Trains a Random Forest Regressor  
✅ Evaluates model performance with cross-validation  
✅ Saves and loads the model using joblib  
✅ Calculates CAGR for features of selected countries  
✅ Forecasts CO₂ emissions per capita for **20 years ahead**  
✅ Plots predicted vs true values and forecast trends  
✅ Uses **Seaborn & Matplotlib** for data visualization

---

## ⚙️ Setup & Installation

1. **Clone the repository** (if applicable) or download the script files.

2. **Install required Python packages**:

```bash
pip install pandas numpy matplotlib scikit-learn seaborn joblib
