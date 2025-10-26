# 🚗 Car Price Prediction

## 📘 Project Overview
This project aims to predict the **selling price of cars** based on various features such as the present price, year of manufacture, fuel type, transmission, and more.  
It applies **Machine Learning regression techniques** to model the relationship between these features and the car prices.

The goal of this project was to **learn the complete workflow of a regression problem** — from data preprocessing to model evaluation — and to compare different algorithms on performance and interpretability.

---

## 🧩 Dataset
The dataset was sourced from **Kaggle** and contains information about used cars, including:

- `Car_Name`: Model and brand of the car  
- `Year`: Year of manufacture  
- `Selling_Price`: The target variable (price of the car when sold)  
- `Present_Price`: The current ex-showroom price  
- `Kms_Driven`: Number of kilometers driven  
- `Fuel_Type`: Type of fuel (Petrol, Diesel, CNG)  
- `Seller_Type`: Dealer or Individual  
- `Transmission`: Manual or Automatic  
- `Owner`: Number of previous owners  

**Rows:** ~300  
**Columns:** 8  

---

## ⚙️ Tech Stack
- **Language:** Python  
- **Libraries:**  
  - pandas, numpy  
  - matplotlib, seaborn  
  - scikit-learn (LinearRegression, RandomForestRegressor, XGBRegressor)  

---

## 🧠 Project Workflow
1. **Importing libraries and dataset**  
2. **Data Preprocessing**
   - Handling null and duplicate values  
   - Feature engineering (`Age` = 2025 - Year)  
   - Encoding categorical variables (OneHotEncoder / pandas.get_dummies)  
   - Feature scaling with StandardScaler  
3. **Exploratory Data Analysis (EDA)**
   - Correlation heatmap  
   - Distribution plots of key features  
   - Relationship between `Selling_Price` and independent variables  
4. **Model Training**
   - Linear Regression  
   - Random Forest Regressor  
   - XGBoost Regressor  
5. **Evaluation**
   - R² Score  
   - Comparison of model performance  

---

## 📊 Results
| Model | R² Score |
|-------|-----------|
| Linear Regression | 0.75 |
| Random Forest | 0.54 |
| XGBoost | 0.79 |

✅ **XGBoost performed the best** on this dataset due to its ability to capture non-linear relationships, even with a small number of samples.

---

## 📈 Key Learnings
- Complete end-to-end ML pipeline for regression  
- Impact of feature scaling on linear models  
- Comparison between linear and tree-based models  
- Handling categorical variables effectively  

---


---

## 🚀 Future Improvements
- Hyperparameter tuning for Random Forest and XGBoost  
- Integration of a web app (Flask / Streamlit) for live predictions  
- Expanding dataset with more records and features  

---

## 👤 Author
**Ayman IBNOUENNADRE**  
📧 Contact: ayman.ibnouennadre@gmail.com  
💼 GitHub: https://github.com/AymanIbnouennadre 
🌐 LinkedIn: https://www.linkedin.com/in/ayman-ibnouennadre

