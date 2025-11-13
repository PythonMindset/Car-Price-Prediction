# 🚗 Car Price Prediction Web App

A beginner-friendly **Machine Learning + Flask Web Application** that predicts the price of a used car using **three ML models**:

- Linear Regression  
- Random Forest Regressor  
- Support Vector Regressor (SVR)

Users enter car details in a clean frontend, and the app displays predictions from all three models.

---

## 📸 Screenshots

<img width="508" height="909" alt="image" src="https://github.com/user-attachments/assets/5fc54087-57d9-46d2-9326-5e14eedafc82" />


---

## ⭐ Features

- Flask backend for handling requests  
- Predictions from **3 different ML models**  
- User-friendly HTML/CSS frontend  
- Real-time predictions  
- Easy to customize and extend  

---

## 🧠 How It Works

1. User enters car details  
2. App converts input into model-ready format  
3. Linear Regression, Random Forest, and SVR each generate predictions  
4. All three predicted prices are shown on the results page  

---

## 📁 Project Structure
├── app.py
├── linear_model.pkl
├── rf_model.pkl
├── svr_model.pkl
├── templates/
│ ├── index.html
│ └── result.html
└── static/
└── (CSS, images, uploads)
