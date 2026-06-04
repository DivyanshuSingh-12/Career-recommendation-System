Data Driven Career Path Recommendation Analysis

🚀 A Hybrid Workforce Analytics and Explainable AI Based Career Recommendation System

📌 Project Overview

The Data Driven Career Path Recommendation Analysis project is an intelligent career guidance system that helps students and job seekers identify suitable career paths based on their academic performance, educational background, skills, and RIASEC personality traits.

The system uses Machine Learning (Random Forest Classifier) to predict the most appropriate career path and Explainable Artificial Intelligence (SHAP) to explain why a particular recommendation was generated.

This project aims to support informed career decision-making through a data-driven and transparent recommendation approach.

🎯 Objectives
Analyze educational, skill-based, and personality-related data.
Predict suitable career paths using Machine Learning.
Provide explainable recommendations using SHAP.
Assist students and professionals in career planning.
Develop an interactive web application using Streamlit.
Deploy the recommendation system on Streamlit Cloud.
🏗️ System Architecture
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
Random Forest Model
     │
     ▼
SHAP Explainability
     │
     ▼
Career Recommendation
     │
     ▼
Streamlit Dashboard
🔄 Workflow
Define career recommendation objectives.
Collect historical career datasets.
Analyze career transitions and skill hierarchies.
Perform data cleaning and preprocessing.
Conduct Exploratory Data Analysis (EDA).
Identify important career progression factors.
Engineer relevant features.
Split data into training and testing datasets.
Train Random Forest Classifier.
Evaluate model performance.
Interpret patterns using Explainable AI.
Generate personalized recommendations.
Save trained model files.
Develop Streamlit user interface.
Test using multiple career profiles.
Deploy on Streamlit Cloud.
Document ethical considerations and limitations.
🧠 Machine Learning Model
Random Forest Classifier

The Random Forest Classifier was selected because:

High prediction accuracy
Handles complex relationships effectively
Reduces overfitting
Suitable for multi-class classification problems
Model Performance
Metric	Value
Accuracy	90%
Algorithm	Random Forest
Explainability	SHAP
Deployment	Streamlit Cloud
🤖 Explainable AI (XAI)

The project incorporates SHAP (SHapley Additive Explanations) to improve transparency and trust.

SHAP helps users understand:

Why a career was recommended
Which factors influenced the prediction
Feature importance rankings
Decision-making process of the model
📊 Features Used
Academic Features
Math Score
Science Score
Education Level
CGPA / Percentage
Personality Features (RIASEC)
Realistic (R)
Investigative (I)
Artistic (A)
Social (S)
Enterprising (E)
Conventional (C)
Skill Features
Technical Skills
Certifications
Specialization
Career Interests
🛠️ Technologies Used
Programming Language
Python
Libraries
Pandas
NumPy
Scikit-learn
SHAP
Matplotlib
Seaborn
Machine Learning
Random Forest Classifier
Dashboard
Streamlit
Deployment
Streamlit Cloud
Version Control
GitHub
📂 Project Structure
Career-recommendation-System/
│
├── app.py
├── requirements.txt
├── career_recommendation_model.pkl
├── scaler.pkl
├── label_encoder.pkl
├── Career-prediction-System.ipynb
├── README.md
└── datasets/
🚀 Installation

Clone the repository:

git clone https://github.com/DivyanshuSingh-12/Career-recommendation-System.git

Move into the project directory:

cd Career-recommendation-System

Install dependencies:

pip install -r requirements.txt

Run the Streamlit application:

streamlit run app.py
🌐 Live Application

Career Recommendation System:

Live Demo

📸 Key Functionalities

✅ User Profile Input

✅ Career Prediction

✅ Explainable AI (SHAP)

✅ Interactive Dashboard

✅ Workforce Analytics

✅ Streamlit Deployment

⚠️ Limitations
Recommendations depend on historical datasets.
Career interests may change over time.
Dataset bias can affect prediction quality.
Recommendations should complement, not replace, professional career counseling.
🔮 Future Scope
Deep Learning-based recommendation systems
Real-time job market integration
Skill-gap analysis
Personalized learning path suggestions
Resume-based career recommendations
Multi-language support
👨‍💻 Team Members
Surbhi Singh
[Team Member 2]
[Team Member 3]
👨‍🏫 Project Guide

[Guide Name]

📚 References
Holland, J. L. – RIASEC Career Theory
Random Forest Classifier Research Paper
SHAP Documentation
Scikit-learn Documentation
Streamlit Documentation
Workforce Analytics Research Articles
📄 License

This project is developed for academic and educational purposes. All rights reserved by the project team.
