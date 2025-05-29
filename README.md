# AI-DOCTOR

# 🧠 Disease Prediction System using Machine Learning & AI

A smart, AI-driven system that predicts diseases based on user-input symptoms and recommends relevant medicines, precautions, diets, and workouts. Developed using supervised machine learning models and rule-based AI techniques.

---

## 🔬 Project Overview

This project was created as part of the **"Introduction to AI"** and **"Machine Learning"** courses to demonstrate the integration of AI reasoning and ML classification. It aims to provide users with quick, preliminary medical insights based on symptoms.

---

## 📂 Features

- 🔍 Predict diseases from over 130+ symptoms using ML models.
- 💊 Recommend medications and precautions.
- 🥗 Suggest diet and workout plans.
- 📄 Provide disease descriptions for better understanding.
- 🌐 Flask-powered frontend for user interaction (future extension).

---

## 🧰 Technologies Used

- Python
- Scikit-learn
- Pandas / NumPy
- Flask (for frontend)
- SVM (Support Vector Machine)
- Joblib & Pickle (Model Persistence)

---

## 🧠 Machine Learning Pipeline

- **Data:** `Training.csv`, `Symptom-severity.csv`, `description.csv`, etc.
- **Preprocessing:** Binary encoding of symptoms, data cleaning.
- **Models Tested:** SVM (final), Random Forest, Naive Bayes, Gradient Boosting, KNN.
- **Final Model:** Support Vector Machine (`svc.pkl`), due to its superior performance on symptom data.

---

## 🤖 AI Techniques

- **Rule-Based Inference:** Symptom severity weighted reasoning.
- **Knowledge Representation:** CSV-based disease metadata.
- **Decision Support:** Merges statistical learning with expert rules.

---

## 🩺 Example Prediction

Input Symptoms: itching, skin rash, nodal skin eruptions

Predicted Disease: Fungal Infection

Description: Common skin condition caused by fungal growth.

Medications: Antifungal cream, Ketoconazole

Precautions:

Keep the area dry
Avoid shared towels
...
_________________________________________


4. Enter your symptoms (comma separated) and get predictions + recommendations.

---

## 📈 Future Work

- Expand the dataset with real clinical data.
- Incorporate time-based symptom progression.

---

## 👨‍💻 Authors

- Muhammad Ubaid Ur Rehman – 231157  
- Muhammad Aqdus Siddique – 231151  

---

## 📜 License

This project is for educational purposes only and not intended for actual medical diagnosis. Always consult a healthcare professional for medical advice.

---

