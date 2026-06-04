# 🚀 Data-Driven Career Path Recommendation Analysis using Machine Learning and Explainable AI

### A Hybrid Workforce Analytics and Explainable AI Based Career Recommendation System

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-green)
![Explainable AI](https://img.shields.io/badge/XAI-SHAP-orange)
![Streamlit](https://img.shields.io/badge/Frontend-Streamlit-red)
![License](https://img.shields.io/badge/License-Educational-lightgrey)

---

## 📌 Project Overview

**Data-Driven Career Path Recommendation Analysis** is an intelligent career guidance system that helps students and job seekers discover suitable career paths based on academic performance, educational background, technical skills, certifications, career interests, and RIASEC personality traits.

The system evaluates multiple Machine Learning algorithms, including Random Forest, Logistic Regression, and Decision Tree classifiers. The best-performing model is further optimized and integrated with SHAP (SHapley Additive Explanations) to provide transparent and explainable career recommendations.

---

## 🎯 Objectives

* Analyze academic, skill-based, and personality-related data.
* Predict suitable career paths using Machine Learning.
* Provide explainable recommendations using SHAP.
* Assist students and professionals in career planning.
* Build an interactive dashboard using Streamlit.
* Deploy the system on Streamlit Cloud.

---

## 🏗️ System Architecture

```text
User Input
     │
     ▼
Data Collection
     │
     ▼
Data Preprocessing
     │
     ▼
Feature Engineering
     │
     ▼
Machine Learning Models
     │
     ▼
Model Selection & Tuning
     │
     ▼
SHAP Explainability
     │
     ▼
Career Recommendation
     │
     ▼
Streamlit Dashboard
```

---

## 🧠 Machine Learning Models

### 📊 Model Comparison

| Model                    | Accuracy |
| ------------------------ | -------- |
| Random Forest Classifier | 95.21%   |
| Logistic Regression      | 95.21%   |
| Decision Tree Classifier | 94.38%   |

### 🚀 Hyperparameter Tuning

| Model                    | Accuracy |
| ------------------------ | -------- |
| Random Forest (Baseline) | 95.21%   |
| Random Forest (Tuned)    | 95.42%   |

### 🏆 Final Model

| Metric          | Value                          |
| --------------- | ------------------------------ |
| Final Algorithm | Tuned Random Forest Classifier |
| Accuracy        | 95.42%                         |
| Explainability  | SHAP                           |
| Deployment      | Streamlit Cloud                |

The optimized Random Forest model was selected for deployment due to its strong predictive performance, robustness, and interpretability.

---

## 🤖 Explainable AI (XAI)

This project integrates **SHAP (SHapley Additive Explanations)** to improve transparency and trust.

### SHAP Helps Users Understand

* Why a career was recommended
* Which factors influenced the prediction
* Feature importance rankings
* Model decision-making process

---

## 📊 Features Used

### Academic Features

* Mathematics Score
* Science Score
* Education Level
* CGPA / Percentage

### Personality Features (RIASEC)

* Realistic (R)
* Investigative (I)
* Artistic (A)
* Social (S)
* Enterprising (E)
* Conventional (C)

### Skill Features

* Technical Skills
* Certifications
* Specialization
* Career Interests

---

## 🛠️ Technology Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* SHAP
* Matplotlib
* Seaborn
* Streamlit
* Git & GitHub

---

## 🌐 Live Demo

https://career-recommendation-system-hcl.streamlit.app/

---

## 📄 License

This project is developed for academic and educational purposes.
