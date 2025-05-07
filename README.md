# 🩺 Disease Prediction & Medical Recommendation System

A smart health assistant that predicts diseases from symptoms and recommends medications, diets, and workouts — all powered by Machine Learning!

---

## 🔍 Overview

This project was developed as part of the **CS 584 - Machine Learning** course. It uses real-world healthcare data and ML algorithms to predict possible diseases and generate personalized health recommendations including:

- 🧪 **Medications**
- 🥗 **Diet plans**
- 🏋️ **Workouts**
- ⚠️ **Precautionary steps**

Built using **Python**, **Flask**, and **Scikit-learn**, the system is easy to deploy and run locally.

---

## 🗂️ Project Structure

```bash
📁 kaggle_dataset
 ┣ 📄 description.csv         → Descriptions of various diseases
 ┣ 📄 diets.csv               → Recommended diets per disease
 ┣ 📄 medications.csv         → Medicines linked to diseases
 ┣ 📄 precautions_df.csv      → Preventive measures per condition
 ┣ 📄 Symptom-severity.csv    → Weightage for each symptom
 ┣ 📄 symptoms_df.csv         → Symptoms and their corresponding disease
 ┣ 📄 Training.csv            → Training dataset for ML model
 ┣ 📄 workout_df.csv          → Exercise plans per disease

📁 model
 ┗ 📄 RandomForest.pkl        → Trained model for prediction

📁 templates
 ┗ 📄 index.html              → Front-end UI for the web app

📁 static
 ┣ 📄 10554240.jpg            → UI asset
 ┗ 📄 img.png                 → UI asset

📄 main.py                    → Flask app (entry point)
📄 disease_prediction_system.ipynb → ML model training and evaluation
