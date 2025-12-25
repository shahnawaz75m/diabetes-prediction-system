# Diabetes Risk Prediction System (Machine Learning) 🏥

An end-to-end Machine Learning project that predicts the risk of diabetes using real-world healthcare data.  
The project covers data preprocessing, exploratory data analysis (EDA), model training and evaluation, and an interactive web application built with Streamlit.

## Project Overview

Diabetes is a chronic disease where early diagnosis and preventive care play a critical role.  
This project aims to build a **machine learning–based diabetes risk assessment system** that predicts whether a person is diabetic based on key medical parameters such as glucose level, BMI, insulin, age, blood pressure, and family history.

The focus of this project is not only model accuracy, but also **clean preprocessing, interpretability, and real-world usability**.

## Technologies Used
- Python  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-learn  
- Streamlit  
- Plotly  
- Joblib  

## Machine Learning Workflow
1. Handling invalid zero values in medical features  
2. Exploratory Data Analysis (EDA)  
3. Feature scaling using **StandardScaler**  
4. Train–test split (80% training / 20% testing with stratification)  
5. Model training and comparison  
   - Support Vector Machine (SVM)  
   - Random Forest Classifier  
6. Model evaluation using:
   - Accuracy  
   - Precision  
   - Recall  
   - F1-score  
   - Confusion Matrix  
7. Model saving and deployment  

## Model Performance
   SVM (Linear Kernel) ~78%
   Random Forest ~70%

The **SVM model** performed slightly better and was selected for deployment.

## 🌐 Web Application (Streamlit)
**The Streamlit application allows users to:**
- Enter patient medical details        
- Get real-time diabetes risk predictions
- View probability-based risk indicators
- Understand key health risk factors
- Receive general health recommendations

⚠️ The app is for **educational purposes only** and does not replace professional medical advice.


## Getting Started

Follow the steps below to run the project locally.

## 1️⃣ Clone the Repository
git clone https://github.com/shahnawaz75m/diabetes-risk-prediction.git
cd diabetes-risk-prediction

## 2️⃣ Create a Virtual Environment

## 2️⃣ Create a Virtual Environment
**On Windows**\
*1. python -m venv venv*\
*2. venv\Scripts\activate*

**On macOS / Linux**\
*1. python3 -m venv venv*\
*2. source venv/bin/activate*

## 3️⃣ Install Dependencies
pip install -r requirements.txt

## 4️⃣ Run the Streamlit App
streamlit run app.py

**After running this command, open the local URL shown in the terminal (usually http://localhost:8501) in your browser.**

## 📌 Key Learnings
- Importance of preprocessing real medical data
- Handling missing and invalid values correctly
- Comparing multiple machine learning models
- Understanding evaluation metrics beyond accuracy
- Deploying ML models using Streamlit
- Presenting ML solutions responsibly in healthcare


## ⚠️ Disclaimer

This project is intended for educational and research purposes only.
It should not be used as a medical diagnostic tool. Always consult qualified healthcare professionals for medical advice.