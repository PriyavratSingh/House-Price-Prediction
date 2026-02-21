# 🏠 House Price Prediction Web App

🔗 **Live Demo:** https://house-price-prediction-aii9.onrender.com/

A Flask-based web application that predicts house prices using a trained regression model.

This project was developed during a Machine Learning bootcamp as part of hands-on deployment training.

---

## 📌 Project Overview

The application allows users to input housing features such as:

- Crime Rate  
- Zoning Classification  
- Industrial Area Proportion  
- Nitrogen Oxide Concentration  
- Average Rooms per Dwelling  
- Property Tax Rate  
- Pupil-Teacher Ratio  
- Distance to Employment Centers  
- Lower Status Population Percentage  
- And more  

Based on these inputs, the trained model predicts the estimated house price.

---

## 🛠 Tech Stack

- Python  
- Flask  
- HTML  
- CSS  
- Scikit-learn  
- Pickle (Model Serialization)  
- Render (Deployment)  

---

## 🚀 How It Works

1. User enters property details in the web form.
2. Flask backend processes the inputs.
3. The pre-trained regression model (`house_price_prediction.pkl`) generates a prediction.
4. The estimated house price is displayed on the webpage.

---

## 📂 Project Structure

```
House-Price-Prediction/
│
├── templates/
│   └── index.html
│
├── static/
│   └── styles.css
│
├── app.py
├── house_price_prediction.pkl
├── requirements.txt
└── README.md
```

---

## 🌐 Deployment

The application is deployed on **Render**.

---

## 🎓 Learning Context

This project was built during a Machine Learning bootcamp.  
The model training and deployment workflow were demonstrated as part of the program.

My contribution focused on:

- Implementing the Flask web application  
- Integrating the trained model  
- Designing and improving the user interface  
- Deploying the application  

---

## 📈 Future Improvements

- Add prediction confidence score  
- Improve UI/UX further  
- Add input validation  
- Add feature impact visualization  
- Dockerize the application  

---

## 👤 Author

Priyavrat Singh  
B.Tech CSE (AI & ML)
