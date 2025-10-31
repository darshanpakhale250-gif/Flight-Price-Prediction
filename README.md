# ✈️ Flight Price Prediction

This project predicts **flight ticket prices** based on various features such as airline, class, cities, and days left for departure.  
It uses **data visualization**, **feature encoding**, and **machine learning regression models** to understand and predict flight pricing patterns.

---

## 📊 Features
- Exploratory Data Analysis (EDA) using Seaborn and Matplotlib  
- Visualization of flight trends and price distribution  
- One-Hot Encoding and Label Encoding of categorical features  
- Feature selection using **VIF (Variance Inflation Factor)**  
- Model training and comparison:
  - Linear Regression  
  - Decision Tree Regressor  
  - Random Forest Regressor  
- Evaluation using R², MAE, MSE, RMSE, and MAPE  

---

## 🧠 Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, Statsmodels  

---

## 📂 Dataset
The dataset `Flight_Booking.csv` contains flight-related information such as:
- Airline  
- Source and Destination City  
- Price  
- Number of Stops  
- Class  
- Days Left for Departure  

📘 *Note:* The dataset was shared as part of a course and is not publicly distributed.  
You can use a similar public dataset from Kaggle:
🔗 [Flight Price Prediction Dataset on Kaggle](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction)

---

## ⚙️ Installation
```bash
git clone https://github.com/yourusername/Flight-Price-Prediction.git
cd Flight-Price-Prediction
pip install -r requirements.txt
