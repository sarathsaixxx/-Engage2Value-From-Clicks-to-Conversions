# Engage2Value: From Clicks to Conversions  
**Predicting Purchase Value from Multi-Session Digital Behavior using Machine Learning**

---

## 🔍 Short Summary (Resume / Internship Ready)
**Engage2Value** is an end-to-end machine learning project that predicts **session-level purchase value** from user digital behavior. It leverages behavioral, traffic, device, and geographic features to understand how engagement translates into revenue. The project covers data preprocessing, EDA, feature engineering, regression modeling, and performance evaluation using industry-standard metrics.

---

## 📌 Project Overview
Digital commerce platforms generate vast amounts of user interaction data, yet translating this data into actionable revenue insights remains challenging.

**Engage2Value** addresses this challenge by building a regression-based machine learning model to predict the **purchaseValue** generated during a user session based on engagement and contextual signals.

This project demonstrates a **complete data science workflow** using Python and popular machine learning libraries.

---

## 🧠 Problem Statement
User engagement does not always directly translate into revenue. Understanding *which behaviors drive value* is essential for optimizing marketing spend and improving user experience.

### 🎯 Objective
Predict the **total purchase value (`purchaseValue`)** of a user session using:
- Behavioral engagement metrics  
- Traffic acquisition channels  
- Device and browser information  
- Geographic attributes  

---

## 📊 Dataset Description
- Each row represents a **unique user session**
- Session-level data collected from a large-scale digital commerce platform

### 🔑 Feature Categories
- **User Behavior:** page views, interactions, session depth  
- **Traffic Source:** organic, paid, referral, direct  
- **Device Information:** mobile, desktop, browser type  
- **Geography:** country, region  

### 🎯 Target Variable
- **purchaseValue** — total amount spent during a session

---

## 🛠️ Technologies Used
- **Programming Language:** Python  
- **Libraries:**  
  - NumPy  
  - Pandas  
  - Matplotlib  
  - Seaborn  
  - Scikit-learn  
- **Environment:** Jupyter Notebook  

---

## 📂 Project Structure
 

├── main_notebook.ipynb # Data analysis, modeling, evaluation

├── README.md # Project documentation 

├── test_data.csv # its too long to upload, https://www.kaggle.com/competitions/engage-2-value-from-clicks-to-conversions/data?select=train_data.csv

├── train_data.csv

├── sample_submission.csv

---

## ⚙️ Methodology
### 1️⃣ Data Preprocessing
- Handling missing values  
- Encoding categorical variables  
- Feature scaling and normalization  

### 2️⃣ Exploratory Data Analysis (EDA)
- Purchase value distribution analysis  
- Correlation heatmaps  
- Engagement vs revenue insights  

### 3️⃣ Feature Engineering
- Session-level feature extraction  
- Traffic source and device encoding  
- Behavioral aggregation  

### 4️⃣ Model Building
- Regression-based machine learning models  
- Model comparison and selection  

### 5️⃣ Model Evaluation
Performance evaluated using:
- **Mean Absolute Error (MAE)**  
- **Root Mean Squared Error (RMSE)**  
- **R² Score**
---
## Used Models 
- 'Linear Regression': LinearRegression(),
- 'Ridge': Ridge(),
- 'Lasso': Lasso(),
- 'Random Forest': RandomForestRegressor(n_estimators=100, random_state=42),
- 'Gradient Boosting': GradientBoostingRegressor(),
- 'XGBoost': xgb.XGBRegressor(n_estimators=100, random_state=42),
- 'LightGBM': lgb.LGBMRegressor(n_estimators=100, random_state=42)



 
