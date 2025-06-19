# 💳 Credit Card Fraud Detection 🔍

This project aims to detect fraudulent credit card transactions using machine learning techniques.  
The goal is to build a model that can **accurately identify suspicious activity** to reduce fraud losses and ensure financial safety. 🛡️

---

## 📁 Files Included

- `creditcard.ipynb` — Jupyter Notebook with data preprocessing, model building, and evaluation
- `README.md` — You're reading it 😊

---

## 📌 Project Overview

🔐 **Problem Statement:**  
Credit card fraud detection is a major concern for the financial industry.  
This project uses **linear regression** (although other classifiers are better suited) to analyze the model performance and understand basic predictive modeling.

📊 **Dataset:**  
- Publicly available anonymized dataset with features such as transaction amount, time, and anonymized principal components (V1, V2, ... V28).
- The dataset is highly imbalanced.

---

## 🧠 ML Approach

### ✅ Steps Performed:

1. **Data Cleaning & Exploration**  
   - Null checks  
   - Outlier detection  
   - Visualizations (histograms, class balance)

2. **Feature Scaling**  
   - Applied `StandardScaler` for normalization

3. **Model Building**  
   - Used **Linear Regression** (primarily for academic understanding)  
   - Compared accuracy with real vs predicted frauds

4. **Evaluation Metrics**  
   - Confusion Matrix  
   - Accuracy Score  
   - Precision, Recall, F1-Score

---

## 🚀 Getting Started

### ✅ Prerequisites
- Python 3.x  
- Jupyter Notebook  
- Required Libraries: `pandas`, `numpy`, `matplotlib`, `sklearn`

### 💻 Run It Locally:
```bash
git clone https://github.com/HARSHITHA-G-M/Credit-card-fraud-detection.git
cd Credit-card-fraud-detection
jupyter notebook
