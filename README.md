# Fraud-transaction-detection-ml

## 📌 Project Overview
This project focuses on detecting fraudulent financial transactions using machine learning techniques. 
The dataset contains over 6.3 million transaction records and is highly imbalanced.

## 📊 Dataset Description
- Transactions: ~6.3 million
- Features: Transaction type, amount, sender & receiver balances
- Target Variable: `isFraud`

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## 🧠 Methodology
1. Data Understanding & Cleaning
2. Feature Engineering
3. Handling Class Imbalance
4. Model Building using Random Forest
5. Model Evaluation (Precision, Recall, ROC-AUC)
6. Feature Importance Analysis

## 📈 Model Performance
- High recall achieved to minimize missed fraud cases
- ROC-AUC score used for robust evaluation

## 🔑 Key Fraud Indicators
- High transaction amount
- TRANSFER and CASH_OUT transaction types
- Sudden balance drops in sender account

## 🛡️ Fraud Prevention Strategy
- Real-time transaction monitoring
- High-value transaction alerts
- Velocity-based checks
- Periodic model retraining

## 🚀 How to Run
1. Clone the repository
2. Install dependencies using `requirements.txt`
3. Open and run the Jupyter Notebook

## 📎 Note
Due to large file size, the dataset is not uploaded. 
You can use the standard financial fraud dataset available publicly.

---
**Author:** Shakshi  
**Internship Project – Fraud Detection**

