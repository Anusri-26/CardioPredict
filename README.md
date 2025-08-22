
# 🫀 CardioPredict – Heart Disease Risk Prediction with Health Assistant

## 📌 Overview
CardioPredict is a Machine Learning–powered web application that predicts the risk of heart disease based on user health parameters.  
It integrates a simple **health assistant interface** to guide users, making medical insights more accessible.  

## ✨ Features
- ✅ Predicts heart disease risk using health data such as age, cholesterol, blood pressure, etc.  
- ✅ Trained ML model (Random Forest Classifier) with high accuracy.  
- ✅ Web application built with **Flask** and interactive UI.  
- ✅ Real-time predictions with user input form.  
- ✅ Health Assistant module that provides personalized recommendations.  
- ✅ Deployed model (`heart_disease_model.pkl`) for quick inference.  

## 🛠️ Tech Stack
- **Programming Language**: Python  
- **Libraries**: Scikit-learn, Pandas, Numpy, Matplotlib  
- **Framework**: Flask  
- **Frontend**: HTML, CSS (templates)  
- **Dataset**: UCI Heart Disease Dataset  
- **Deployment**: Flask app (can be deployed on Heroku/Render/Streamlit Cloud)  

## 📂 Project Structure


├── app.py                         # Flask app
├── heart.csv                      # Dataset
├── heart\_disease\_model.pkl        # Trained ML model
├── CARDIO_PREDICT_...ipynb  # Training & evaluation notebook
├── templates/                     # HTML templates for UI
├── screenshorts/                  # Screenshots of app



## 🚀 How to Run Locally
1. Clone the repository  

   git clone https://github.com/Anusri-26/CardioPredict.git
   cd CardioPredict


2. Install dependencies

   
   pip install -r requirements.txt
   

3. Run the application

   
   python app.py


4. Open in browser

   http://127.0.0.1:5000/
   


## 📊 Model Performance

* Algorithm: **Random Forest Classifier**
* Accuracy: \~**90–92%** (on test dataset)
* Balanced evaluation using Precision, Recall, and F1-score.

## 🎯 Future Enhancements

* Deploy on cloud (Heroku / Render / AWS).
* Add Explainable AI (SHAP/Feature Importance) for medical trustworthiness.
* Enhance Health Assistant with chatbot functionality.

## 👤 Author

Developed by **[Anusri Chundru](https://github.com/Anusri-26)**

