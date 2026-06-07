# 🚀 Data-Driven Career Path Recommendation Analysis using Machine Learning and Explainable AI

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-green)
![Explainable AI](https://img.shields.io/badge/XAI-SHAP-orange)
![Streamlit](https://img.shields.io/badge/Frontend-Streamlit-red)
![License](https://img.shields.io/badge/License-Educational-lightgrey)

---

## 📌 Project Overview

**Data-Driven Career Path Recommendation Analysis** is an intelligent career guidance system that helps students and job seekers discover suitable career paths based on academic performance, educational background, technical skills, certifications, career interests, and RIASEC personality traits.

The system evaluates multiple Machine Learning algorithms including Random Forest, Logistic Regression, and Decision Tree classifiers. The best-performing model is optimized and integrated with SHAP (SHapley Additive Explanations) to provide transparent and explainable career recommendations.

---

## 🌐 Live Demo

https://career-recommendation-system-hcl.streamlit.app/

---

## 📊 Datasets Used

- [Student Career Prediction (RIASEC Dataset)](https://www.kaggle.com/datasets/svenkateshkumar/student-career-prediction-using-riasec-dataset)
- [Career Path Recommendations Dataset](https://www.kaggle.com/datasets/ahsanneural/career-path-recommendations-dataset)

---

## ⚙️ Features

- ML-based career prediction (Random Forest)
- RIASEC personality integration
- Education + skills-based recommendation system
- Explainable AI using SHAP
- Interactive Streamlit web app

---

## 🧠 Tech Stack

- **Language:** Python  
- **Data Processing:** Pandas, NumPy  
- **Machine Learning & XAI:** Scikit-learn, SHAP, Joblib  
- **Frontend & Visualization:** Streamlit, Matplotlib  

---

## 📈 Model Performance

- **Algorithm:** Random Forest Classifier  
- **Accuracy:** 95.42%  
- **Task:** Multi-class classification across 6+ career domains  

---

## 🏗️ System Architecture
````markdown
User Input
   ↓
Data Collection
   ↓
Data Preprocessing
   ↓
Feature Engineering
   ↓
Machine Learning Models
   ↓
Model Selection & Tuning
   ↓
SHAP Explainability
   ↓
Career Recommendation
   ↓
Streamlit Dashboard
   ↓
Final Output (Recommended Career Path + Explanation)
````


## 📁 Project Structure
````markdow
Career-recommendation-System/
├── Dataset/               # Raw and processed datasets
├── saved_models/          # Trained models (.pkl files)
├── Career_Re.ipynb        # EDA, training, evaluation notebook
├── app.py                 # Streamlit application
├── requirements.txt       # Dependencies
└── README.md              # Documentation
````

## ▶️ How to Run

```bash
git clone https://github.com/DivyanshuSingh-12/Career-recommendation-System.git

cd Career-recommendation-System

pip install -r requirements.txt

streamlit run app.py
```

## 👨‍💻 Team Members
- Divyanshu Singh – ML Engineer (Model Development, SHAP, EDA)
- Dhruv Paliwal – Frontend & Deployment (Streamlit App)
- Surbhi Singh – Data & Research Analyst

