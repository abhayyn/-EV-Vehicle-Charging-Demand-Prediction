# -EV-Vehicle-Charging-Demand-Prediction

This project aims to forecast Electric Vehicle (EV) adoption trends across 311 counties in Washington State using real-world registration data. The insights from this model help in identifying high-demand areas for EV charging infrastructure planning.

---

## Project Overview

With the rapid rise of EVs in the U.S., especially in Washington, predicting where charging stations are most needed is crucial. Using historical EV registration data, this project builds a machine learning model to estimate future EV demand on a county level.

---

##  Objectives

- Analyze regional EV adoption using actual registration data.
- Engineer features like EV counts by type and adoption year.
- Train a **Random Forest Regressor** to forecast future EV usage.
- Evaluate model accuracy using metrics like **R²** and **MAE**.
- Visualize trends and feature importance.
- Deploy a **Streamlit** app for real-time forecasting.

---

##  Tech Stack

- **Language**: Python 3.12.10  
- **Environment**: Jupyter Notebook  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Joblib  
- **Web Framework**: Streamlit  
- **Version Control**: Git & GitHub  
- **Dataset Format**: CSV  

---

## Workflow

1. **Data Collection**  
   Collected EV registration data for 311 counties in CSV format.

2. **Data Preprocessing**  
   Cleaned missing values, encoded categorical columns, created lag-based and trend-based features.

3. **Exploratory Data Analysis (EDA)**  
   Used Matplotlib and Seaborn to visualize adoption patterns and outliers.

4. **Model Building**  
   Trained and evaluated multiple models:  
   - Decision Tree  
   - SVR  
   - **Random Forest Regressor** (Selected, R² = 0.94, MAE ≈ 98.5)

5. **Deployment**  
   - Model saved with `joblib`  
   - Web app created using Streamlit  
   - Hosted for public use

---

##  Results

- Achieved **94% R² Score** with Random Forest.
- Accurate 36-month predictions for EV growth per county.
- Fully functional **interactive dashboard** for insights and comparison.

---

##  Future Enhancements

- Add advanced models like **XGBoost**, **LSTM** for better temporal modeling.
- Include external factors (e.g., **charging station density**, **government incentives**) for improved prediction accuracy.
- Enable user-uploaded data in Streamlit for dynamic forecasting.

---

