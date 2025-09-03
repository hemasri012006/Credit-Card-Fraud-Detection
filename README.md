# 💳 Credit Card Fraud Detection

## 📌 Project Overview
This project aims to detect fraudulent credit card transactions using Machine Learning.  
By analyzing anonymized transaction data, we trained a Random Forest Classifier to classify transactions as **fraudulent (1)** or **genuine (0)**.

## 📂 Dataset
- Source: [Kaggle – Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- Contains **284,807 transactions** with 492 fraud cases (highly imbalanced).
- Features: 30 numerical variables (V1–V28, Time, Amount)
- Target: `Class` (0 = genuine, 1 = fraud)

## ⚙️ Steps Involved
1. Load dataset and check missing values  
2. Scale features using `StandardScaler`  
3. Handle class imbalance with train-test split  
4. Train a **Random Forest Classifier**  
5. Evaluate using Accuracy, Precision, Recall, and F1-Score  

## 📊 Model Performance
- ✅ Accuracy: ~99.95%  
- ✅ High precision in fraud detection  
- ✅ Model generalized well on test data  

## 📁 Files in Repository
- `FraudDetection.ipynb` → Notebook with full code  
- `fraud_model.pkl` → Trained model  
- `fraud_scaler.pkl` → Scaler used for preprocessing  
- `README.md` → Project documentation  

## 🚀 Future Improvements
- Try **SMOTE** for handling imbalance  
- Test **Logistic Regression, XGBoost**  
- Deploy as a **Flask/Streamlit app**  

---
👨‍💻 Developed as part of a **Data Science Internship Task**  

