# Loan-Default-Prediction-using-ETL-Machine-Learning
# Loan Default Prediction using ETL + Machine Learning

## 📌 Project Overview
This project predicts whether a loan applicant is likely to default based on historical loan data. It includes a complete ETL pipeline, data preprocessing, and a machine learning model trained on an imbalanced dataset.

---

## 🎯 Problem Statement
To identify high-risk loan applicants using historical financial and credit-related features, helping reduce financial risk for lending institutions.

---

## ⚙️ Workflow

### 1. ETL Process
- Data cleaning (missing values, duplicates)
- Encoding categorical variables
- Feature preparation

### 2. Model Building
- Random Forest Classifier
- Handling imbalance using class weighting

### 3. Optimization
- Threshold tuning to improve recall for default detection

---

## 📊 Results

- Accuracy: 0.82  
- Precision (Default class): 0.32  
- Recall (Default class): 0.56  
- F1-score: 0.41  

---

## 🎯 Key Insight
Lowering classification threshold significantly improved recall, helping better identify potential loan defaulters, which is critical in financial risk systems.

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
