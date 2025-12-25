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

## 🏗️ Project Structure

Student-Performance-Indicator/
│
├── src/
│ ├── components/
│ │ ├── data_ingestion.py
│ │ ├── data_transformation.py
│ │ └── model_trainer.py
│ │
│ ├── pipeline/
│ │ └── predict_pipeline.py
│ │
│ ├── utils.py
│ ├── logger.py
│ └── exception.py
│
├── templates/
│ ├── index.html
│ └── home.html
│
├── app.py
├── requirements.txt
├── setup.py
└── README.md


---

## 🖥️ Web Application

- Built using **Flask**
- HTML form collects student details
- Predicts **Math score**
- Displays result on UI

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


