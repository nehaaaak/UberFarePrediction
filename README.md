# 🚖 Uber Fare Prediction

## 📌 Overview
This project builds a regression-based machine learning model to predict Uber ride fares.  
The goal is to understand what factors affect pricing and provide data-driven insights for better pricing strategies.
This was AIMERZ x MentorMind virtual internship project.

---

## 🛠️ Tech Stack
- Python  
- pandas, numpy, matplotlib, seaborn  
- scikit-learn, xgboost  

---

## 📊 Key Insights
- **Best Model**: Tuned **XGBoost Regressor** (R² ≈ 0.79)  
- **Most Important Features**: Trip length & trip distance  
- **Business Takeaway**: Dynamic pricing works – fares are higher during rush hours & for longer rides.

---

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/nehaaaak/UberFarePrediction.git
   cd UberFarePrediction
   ```

2. Open the notebooks in Jupyter/Colab and run step by step:
   - data_preprocessing.ipynb → Prepare the dataset
   - model.ipynb → Train and tune models
   - model_insights.ipynb → Evaluate and generate insights

---

## ✅ Final Outcome
- Built ML models to predict fares with good accuracy.
- Identified distance and trip length as key factors.
- Provided recommendations for pricing and driver incentives.
