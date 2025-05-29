# House-Pricing-Prediction-
Predicting Oulu housing prices using Python regression models
## 📊 Project Overview

**Objective:**  
Predict housing prices based on real-world data from the Oulu housing market. This project involves data cleaning, preprocessing, feature engineering, and developing regression models to achieve accurate price predictions.

---

## Tools & Techniques

- Python (Pandas, NumPy, Scikit-learn)
- Jupyter Notebook
- Data visualization (Matplotlib, Seaborn)
- Regression models (Linear Regression, Random Forest, etc.)

---

## Key Steps

Performed exploratory data analysis (EDA) to understand variable relationships  
Engineered features to improve model performance  
Built and tested multiple regression models  
Evaluated model accuracy using R² score, RMSE  
Visualized results to highlight insights

---

## Key Insights from Model
Model Performance:
Achieved R² = 0.81 on training data and R² = 0.61 on test data, showing the model explains 61% of price variance on unseen data — a solid performance, with room for improvement through regularization or additional features.

Feature Impact:
Area, year of construction, and number of rooms were the strongest predictors. Apartments with elevators or in good condition showed measurable price premiums.

Market Trend Insight:
Small apartments (under 40 m²) tend to have a higher price per square meter, reflecting strong demand in compact urban zones.

Visual Takeaways:
The correlation heatmap highlighted a strong relationship between area and rooms (r = 0.92), while actual vs. predicted plots confirmed the model’s solid mid-range performance but revealed some spread at higher price levels.

---

## 📁 Project Files

- `real_estate_model.ipynb` → Main Jupyter notebook with full analysis and modeling steps  
- `oulu_apartment_data_for_analysis/` → Folder for dataset files 
- `plots/` → Key visualizations and output charts

## 📊 Actual vs. Predicted Housing Prices
![Actual vs Predicted](Actual_Predicted_House_Price.png)
Shows how well predicted prices align with actual market prices.

## 🔥 Correlation Matrix Heatmap
![Correlation Matrix](Correlation_Matrix_Heatmap.png)
Highlights key correlations between variables, e.g., area and rooms, price and year.

## 📈 True vs. Predicted Prices Over Apartments
![Prediction Plot](Prediction_Plot.png)
Line plot comparing true vs. predicted prices across individual apartments.

## 📉 Training Loss Curve
![Training Loss](Training_Loss_Curve.png)
Displays model convergence over iterations; zoomed section highlights stabilization.

---

## 🏆 Outcome

Successfully developed a machine learning pipeline for predicting housing prices, strengthening skills in data preprocessing, regression modeling, and business-relevant insights.

