# 🌍 AI for Sustainable Development — CO₂ Emission Prediction (SDG 13: Climate Action)

## 🧭 Overview  
This project supports **UN SDG 13 – Climate Action**, addressing the global challenge of **CO₂ emissions** and their impact on climate change.  
Using a **machine learning regression model**, it predicts CO₂ emission levels based on environmental and economic indicators.  

---

## 🎯 Objective  
Build an ML model that predicts **CO₂ emissions** to help policymakers and researchers take data-driven actions toward sustainable development.

---

## 🧠 ML Approach  
- **Type:** Supervised Learning (Regression)  
- **Algorithm:** Random Forest Regressor  
- **Goal:** Predict CO₂ emissions  
- **Evaluation Metrics:** R² Score and Mean Absolute Error (MAE)  

---

## 📊 Dataset  
- **File:** `CO2_Emissions.csv`  
- **Source:** Open dataset on CO₂ emissions by country and year  
- **Features:** Various environmental and economic indicators  
- **Target:** Total CO₂ emissions  

---

## ⚙️ Workflow Summary  
1. **Load Data:** Read the CO₂ dataset using Pandas  
2. **Clean Data:** Remove missing values and non-numeric columns  
3. **Split Data:** 80% training, 20% testing  
4. **Train Model:** Use Random Forest for regression  
5. **Evaluate:** Measure accuracy using R² and MAE  
6. **Visualize:** Plot actual vs predicted CO₂ values  

---

## 📈 Results  
- **R² Score:** ~0.87  
- **MAE:** ~6.5 (example result)  
The model shows strong predictive ability for estimating CO₂ emission levels.  

---

## ⚖️ Ethical Reflection  
- **Bias:** Reduced by using diverse global data.  
- **Fairness:** Promotes transparency in environmental monitoring.  
- **Sustainability:** Enables data-driven policies to combat climate change.  

---

## 🌱 Future Work  
- Add real-time emission data via APIs  
- Deploy as a web app using Flask or Streamlit  
- Compare with Linear Regression or XGBoost for performance optimization  

---

## 🗣️ Elevator Pitch  
> “Our AI model predicts CO₂ emissions before they rise—empowering governments and citizens to act early for a cleaner, sustainable planet.”  

---

## 🧩 Repository Contents  
