# 🧠 Retention AI

Retention AI is a full-stack machine learning application that predicts employee attrition and provides explainable AI insights to help organizations identify employees at risk of leaving. The application combines a React frontend, FastAPI backend, and machine learning models to deliver real-time predictions through an interactive dashboard.

---

## 🚀 Features

- 📊 Employee attrition prediction using Machine Learning
- 🤖 Explainable AI (SHAP) for prediction interpretation
- 📈 Interactive analytics dashboard
- ⚡ FastAPI REST API backend
- 🎨 React-based frontend
- 📂 Dataset management and preprocessing
- 📉 Employee retention insights and visualization

---

## 🛠️ Tech Stack

### Frontend
- React
- JavaScript
- HTML5
- CSS3
- Chart.js

### Backend
- FastAPI
- Python
- Uvicorn

### Machine Learning
- Scikit-learn
- XGBoost
- SHAP
- Pandas
- NumPy
- Joblib

### Tools
- Git
- GitHub
- VS Code
- npm
- pip

---

# Project Structure

```
Retention-AI-main
│
├── backend/
│   ├── main.py
│   ├── requirements.txt
│   └── ...
│
├── retention-ai-frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── datasets/
├── models/
├── outputs/
├── requirements.txt
└── README.md
```

---

# Installation

## 1. Clone Repository

```bash
git clone https://github.com/KushalCodes-7/Retention-AI.git
cd Retention-AI
```

---

## 2. Create Virtual Environment

```bash
python -m venv .venv
```

Activate it

### Windows

```bash
.\.venv\Scripts\Activate.ps1
```

---

## 3. Install Backend Dependencies

```bash
pip install -r requirements.txt
```

---

## 4. Install Frontend Dependencies

```bash
cd retention-ai-frontend

npm install
```

---

# Running the Project

## Start Backend

```bash
cd backend

python main.py
```

Backend runs at

```
http://localhost:8000
```

---

## Start Frontend

Open another terminal

```bash
cd retention-ai-frontend

npm start
```

Frontend runs at

```
http://localhost:3000
```

---

# Screenshots

> Add screenshots of the dashboard here.

Example:

```
Home Dashboard

Prediction Result

Analytics Dashboard
```

---

# Machine Learning Pipeline

1. Data Collection
2. Data Preprocessing
3. Feature Engineering
4. Model Training
5. Prediction
6. Explainability using SHAP
7. Dashboard Visualization

---

# Future Improvements

- User Authentication
- Database Integration
- Cloud Deployment
- Email Notifications
- Model Retraining
- Docker Support
- CI/CD Pipeline

---

# Author

**Kushal S J**

GitHub:
https://github.com/KushalCodes-7

LinkedIn:
https://www.linkedin.com/in/kushalsj7/

---

# License

This project is developed for educational and learning purposes.
