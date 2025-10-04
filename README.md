# Custmer Churn Prediction

This is a **Full-Stack Web Application** built for the **BNP Paribas Hackathon** by Team20.  
It focuses on **Customer Churn Prediction** and **Sales Forecasting**, using **Machine Learning models** integrated with a modern frontend and backend architecture.

---

## 🚀 Features

- **User Authentication** with JWT (Login & Register)
- **Churn Prediction Dashboard**  
  - Displays 10 products  
  - Pie charts for High, Medium, and Low Churn risk customers  
  - ML Model: **K-Means Clustering**
- **Sales Forecasting Dashboard**  
  - Shows Top 10 products  
  - Sales trends and visualizations  
  - ML Model: **Facebook Prophet**
- **Interactive Charts** using modern visualization libraries
- **Backend API** with Flask
- **Frontend** with React and TailwindCSS
- **Database Integration** for user data and results

---

## 🖼️ Screenshots

### 🔐 Login & Register  
![Login Page](Customer-Churn-Prediction
/Screenshot 2025-10-05 003205.png)

### 📊 Churn Prediction Dashboard  
![Churn Dashboard](/Screenshot 2025-10-05 003205.png)

### 📈 Sales Forecasting Dashboard  
![Forecast Dashboard](/screenshots/forecast_dashboard.png)

*(Place your screenshots inside a folder named `screenshots` in your project root and rename accordingly.)*  

---

## 🛠️ Tech Stack

### Frontend
- React.js  
- TailwindCSS  
- Chart.js / Recharts  

### Backend
- Flask (Python)  
- REST APIs  
- JWT Authentication  

### Machine Learning
- **K-Means** for Customer Churn Prediction  
- **Prophet** for Sales Forecasting  

### Database
- MongoDB / MySQL (depending on setup)

---

## ⚙️ Installation & Setup

### Clone Repository
```bash
git clone https://github.com/Himanizambare/Customer-Churn-Prediction.git
cd Customer-Churn-Prediction
```


## Backend Setup

```
cd backend
python -m venv venv
venv\Scripts\activate   # On Windows
source venv/bin/activate  # On Mac/Linux

pip install -r requirements.txt
python app.py

```
Backend will start on: http://127.0.0.1:5000/


## Frontend Setup


```
cd frontend
npm install
npm start
```
Frontend will start on: http://localhost:3000/


## System Flow
 -  User Login/Register → JWT Authentication

 -  Dashboard

 -  Churn Section → Displays product churn risk analysis (High/Medium/Low)

 -  Sales Forecast Section → Shows top 10 products with forecasted sales

 -  Visualization & Insights shown via charts

## 📜 License
This project is licensed under the MIT License.

```

---

✨ If you give me a couple of your **real screenshots** (like your login page, churn pie chart, forecast graph), I can insert them in the right format so you just need to push the README to GitHub.  

👉 Do you want me to also make a **nice banner/cover image** for the top of your README (like a hackathon-style project showcase)?

```

