# 🩺 Health Budyy

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
 ┗ 📄 Model.pkl        → Trained model for prediction

📁 templates
 ┗ 📄 index.html              → Front-end UI for the web app

📁 static
 ┣ 📄 10554240.jpg            → UI asset
 ┗ 📄 img.png                 → UI asset

📄 main.py                    → Flask app (entry point)
📄 Health_buddy.ipynb → ML model training and evaluation



## 🚀 How to Run the Project Locally

Follow the steps below to set up and run the application on your local machine:

1. **Clone the repository**

   ```bash
   git clone https://github.com/rohitkushwahasingh001/Health_Buddy.git
   cd disease-predictor
   ```

2. **Create and activate a virtual environment (recommended)**

   ```bash
   python -m venv venv
   # For Windows
   venv\Scripts\activate
   # For macOS/Linux
   source venv/bin/activate
   ```

3. **Install dependencies**

   ```bash
   pip install pandas scikit-learn flask numpy fuzzywuzzy pickle5
   ```

4. **Run the Flask application**

   ```bash
   python main.py
   ```

5. **Access the app in your browser**

   ```
   http://localhost:5000
   ```

---

## ✨ Features

- ✅ Predicts disease based on user-input symptoms
- 💊 Recommends medications and safety tips
- 🥦 Provides diet suggestions
- 🏃 Suggests workouts for better recovery
- 📊 Uses a trained Random Forest ML model
- 🌐 Intuitive web-based interface using Flask
- 🧠 Integrates symptom severity and precaution data
- 🧾 Documentation and logical directory structure for clarity

---

## 👨‍💻 Developed By

**Rohit Kushwaha**  
[GitHub](https://github.com/rohitkushwaha001) | [LinkedIn](https://linkedin.com/in/rohit-kushwaha)

---

