## 🎓 Student Performance Indicator

An end-to-end **Machine Learning + Flask** web application that predicts a student's **Math score** based on demographic and academic features.  
The project follows **industry-level ML pipeline practices** and is **deployable on AWS Elastic Beanstalk**.

---

## 🚀 Project Overview

This project demonstrates:
- End-to-end ML workflow (data ingestion → transformation → training → prediction)
- Modular, production-ready code structure
- Custom exception handling & logging
- Flask-based web interface
- Cloud deployment using **AWS Elastic Beanstalk**

---

## 🧠 Machine Learning Workflow

1. **Data Ingestion**
   - Reads raw student performance dataset
   - Splits data into train/test
   - Stores artifacts

2. **Data Transformation**
   - Numerical & categorical preprocessing
   - Pipelines using `ColumnTransformer`
   - Saves preprocessing object

3. **Model Training**
   - Trains multiple regression models
   - Performs hyperparameter tuning
   - Selects best model based on R² score
   - Saves trained model

4. **Prediction Pipeline**
   - Loads trained model & preprocessor
   - Generates predictions from user input

---

## 🖥️ Web Application

- Built using **Flask**
- HTML form collects student details
- Predicts **Math score**
- Displays result on UI

---
## App Workflow

- Enter Student details (Gender, Race Ethnicity, Parental Level of Education, Lunch Type, Test Preparation Course, Writing Score, Reading Score).

- Click Predict Your Math Score.

- The app displays the predicted Math Score.

  <img width="461" height="772" alt="Screenshot 2025-12-25 143323" src="https://github.com/user-attachments/assets/6808929c-6216-4e3d-b040-790e1be3444d" />


---

## ⚙️ Technologies Used

- **Python**
- **Pandas, NumPy**
- **Scikit-learn**
- **CatBoost, XGBoost**
- **Flask**
- **AWS Elastic Beanstalk**
- **GitHub**

---


