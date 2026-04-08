# 🧠 AI Student Burnout Risk Predictor

## 📌 Project Overview

This project aims to predict high burnout risk among students using machine learning techniques and mental health indicators.

The system analyzes student behavior patterns such as sleep, study time, stress levels, and lifestyle factors to identify students at risk of burnout.

---

## 📊 Dataset Details

- Dataset: Student Mental Health Dataset  
- Total Records: 150,000+  
- Features: 25+  
- Target Variable: Burnout Level  

Key features include:

- Daily Study Hours  
- Sleep Hours  
- Screen Time  
- Anxiety Score  
- Depression Score  
- Academic Pressure  
- Attendance Percentage  
- CGPA  

---

## 🛠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Imbalanced-learn (SMOTE)  
- Joblib  

---

## ⚙️ Machine Learning Workflow

The following steps were performed:

1. Data Cleaning  
2. Feature Engineering  
3. Handling Class Imbalance using SMOTE  
4. Model Training using:
   - Logistic Regression  
   - Random Forest  
   - Gradient Boosting  
5. Threshold Optimization  
6. Model Evaluation  

---

## 📈 Model Performance

Key evaluation results:

- Accuracy: ~66%  
- ROC-AUC Score: ~0.50  
- Precision & Recall Analysis performed  
- Confusion Matrix generated  

---

## 🔍 Key Insights

During development, several challenges were identified:

- Class imbalance affected prediction quality  
- Feature engineering significantly improved model learning  
- Multiple algorithms were tested to compare performance  
- Threshold tuning improved recall performance  

---

## 💾 Saved Model Files

The trained model is saved using:

- `burnout_final_model.pkl`
- `model_features.pkl`

These files allow future prediction without retraining.

---

## 🚀 Future Improvements

Planned upgrades:

- Use more advanced feature engineering  
- Add real-time prediction interface  
- Build web application using Streamlit  
- Improve prediction accuracy using deep learning  

---

## 👨‍💻 Author

**Kalyan Reddy**  
Aspiring AI & Data Science Engineer  
Passionate about solving real-world problems using AI.
