# 💳 Machine Learning-Based Anomaly Detection for Fraud Prevention

This project aims to detect fraudulent financial transactions using **machine learning techniques**, serving as an effective cybersecurity measure to prevent financial fraud.  
Currently, around **30% of the project is complete**. A **Logistic Regression** model has been trained on a Kaggle dataset and is achieving **94% accuracy**.  
In the upcoming phases, the system will be deployed as a **Streamlit web app** for real-time fraud prediction.

---

## 📌 Project Overview

- Detect fraudulent vs. legitimate transactions
- Trained Logistic Regression baseline model
- Achieved 94% accuracy with high recall
- Evaluated using confusion matrix, ROC-AUC, and classification metrics
- Plan to integrate prediction model with a user-friendly Streamlit interface
- Future work includes testing and comparing other ML algorithms

This project demonstrates how **machine learning can be applied as a cybersecurity technique** to detect anomaly-based cyberattacks (fraud) in real-time financial systems.

---

## 📊 Dataset

- Source: [Fraud Detection Dataset – Aman Ali Siddiqui (Kaggle)](https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset)
- ~150,000 transaction records
- Features: transaction type, amount, account balances, sender/receiver IDs
- Target column: `isFraud` (1 = fraud, 0 = legitimate)
- Highly imbalanced — only a small fraction are fraud cases

---

## ✅ Progress So Far

- Collected and explored dataset from Kaggle  
- Preprocessed and trained Logistic Regression model  
- Achieved 94% accuracy and high recall  
- Evaluated with confusion matrix, ROC-AUC, and F1-score  
- Planned Streamlit web app for real-time prediction

---

## 🚀 Next Steps

- Analyse and compare different machine learning algorithms (Random Forest, XGBoost)
- Complete data preprocessing pipeline (encoding, scaling, SMOTE)
- Build Streamlit UI for real-time user input and predictions
- Deploy trained model using `joblib`
- Add alert mechanism and feedback-based model retraining

---

## ⚙️ Tech Stack

- **Language:** Python  
- **Libraries:** pandas, scikit-learn, imbalanced-learn, matplotlib, seaborn  
- **Development:** Google Colab  
- **Planned Deployment:** Streamlit

---

## 📁 Repository Structure

