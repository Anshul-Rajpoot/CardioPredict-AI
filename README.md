# ❤️ CardioPredict AI

> **An Intelligent Heart Disease Risk Prediction System built using Machine Learning and Streamlit**

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn)
![Streamlit](https://img.shields.io/badge/Streamlit-WebApp-red?logo=streamlit)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Project Overview

CardioPredict AI is a Machine Learning-based web application that predicts the likelihood of heart disease using patient health information.

The application allows users to enter patient details such as age, blood pressure, cholesterol level, glucose level, lifestyle habits, and other medical parameters to estimate heart disease risk in real time.

The project combines **Machine Learning**, **Data Preprocessing**, and **Streamlit** to provide an interactive healthcare prediction dashboard.

---

## ✨ Features

- ❤️ Heart Disease Risk Prediction
- 📊 Interactive Streamlit Dashboard
- 📈 Prediction Probability
- 📋 Patient Health Summary
- 🩺 Personalized Health Recommendations
- ⚖ BMI Calculator
- 📥 Download Prediction Report
- 💻 Responsive User Interface

---

## 🖥 Demo

### Home Page

<img width="1508" height="723" alt="image" src="https://github.com/user-attachments/assets/5760d9fd-c6c0-4efb-8fe6-3d9b4ba0576f" />


```
screenshots/home.png
```

---

### Prediction Result

<img width="1524" height="708" alt="image" src="https://github.com/user-attachments/assets/e96d1f0b-107e-4114-8370-059cc47ce78c" />


```
screenshots/result.png
```

---

## 📂 Project Structure

```text
CardioPredict-AI/
│
├── app.py
├── train.py
├── predict.py
│
├── models/
│   └── disease_model.pkl
│
├── data/
│   └── heart_disease.csv
│
├── requirements.txt
├── README.md
```

---

## ⚙ Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Scikit-Learn
- Joblib
- Streamlit

### Machine Learning

- Logistic Regression
- StandardScaler
- One-Hot Encoding
- Pipeline
- ColumnTransformer

---

## 📊 Dataset

The dataset contains patient health records with features such as:

- Country
- Age
- Gender
- Height
- Weight
- Blood Pressure
- Cholesterol Level
- Glucose Level
- Smoking Habit
- Alcohol Consumption
- Physical Activity
- Occupation

Target Variable

- Heart Disease (0 = No, 1 = Yes)

---

## 🔄 Machine Learning Workflow

```
Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Data Preprocessing
      │
      ▼
Train-Test Split
      │
      ▼
Logistic Regression Model
      │
      ▼
Prediction
      │
      ▼
Streamlit Web Application
```

---

## 📈 Model Evaluation

Evaluation Metrics Used

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/CardioPredict-AI.git

cd CardioPredict-AI
```

---

### Create Virtual Environment

Windows

```bash
python -m venv .venv

.venv\Scripts\activate
```

Linux / macOS

```bash
python3 -m venv .venv

source .venv/bin/activate
```

---

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

### Train the Model

```bash
python train.py
```

---

### Run Streamlit App

```bash
streamlit run app.py
```

---

## 📷 Application Preview

### Dashboard

Add Screenshot

---

### Prediction

Add Screenshot

---

## 💡 Future Improvements

- Deploy on Streamlit Community Cloud
- Add Random Forest & XGBoost Models
- Improve Prediction Accuracy
- User Authentication
- Database Integration
- Patient History Tracking
- PDF Report Generation
- Doctor Recommendation System

---

## 👨‍💻 Developer

**Anshul Rajpoot**

Electronics & Communication Engineering  
Maulana Azad National Institute of Technology (MANIT), Bhopal

GitHub

https://github.com/Anshul-Rajpoot

LinkedIn

https://www.linkedin.com/in/anshul-rajpoot-39327328b

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

## 📄 License

This project is licensed under the MIT License.

Feel free to use and modify it for educational purposes.

---

# ❤️ Thank You

*"Predicting Heart Disease with Machine Learning for Better Healthcare Decisions."*
