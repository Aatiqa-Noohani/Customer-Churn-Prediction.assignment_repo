# Customer-Churn-Prediction-ML
Machine Learning classification project to predict customer churn using Logistic Regression.

# 📊 Customer Churn Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict whether a customer will churn (leave the service) or not using classification techniques.

Customer churn prediction helps businesses identify customers at risk of leaving, allowing proactive retention strategies.

---
## 📊 Dataset

- Dataset: IBM Telco Customer Churn
- Source: Kaggle
- Target Variable: Churn (Yes/No)

---
## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---
## 🧹 Data Preprocessing

- Removed unnecessary columns (customerID)
- Converted TotalCharges to numeric
- Handled missing values
- Applied One-Hot Encoding to categorical variables
- Split dataset into training and testing sets (80/20)

---
## 🤖 Model Applied

- Logistic Regression

---
## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---
## 🎯 Important Insight

For churn prediction, **Recall** is especially important because failing to identify a customer who is likely to churn can result in revenue loss.  
Higher recall ensures that most churn-prone customers are correctly identified.

---
## 📊 Results

The model successfully classifies customers into churn and non-churn categories with reasonable accuracy.  

Performance can be improved further by:
- Trying Decision Tree or Random Forest
- Hyperparameter tuning
- Feature selection
- Cross-validation

---
## 🚀 Future Improvements

- Compare multiple classification models
- Apply SMOTE for class imbalance
- Deploy as a web application using Streamlit
## 👩‍💻 Author

Developed as part of a Machine Learning classification project.
