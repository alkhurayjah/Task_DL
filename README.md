# 💳 Fraud Detection System using Deep Learning

## 👨‍💻 Team Members

* Abdullah
* Ahmed
* Saad
* Mansour ⭐ *(Best performance in training phase)*

---

## 📌 Project Overview

This project aims to build a **fraud detection system** using machine learning and deep learning techniques to classify transactions as **fraudulent or legitimate**.

The system follows a **complete pipeline**, including preprocessing, feature engineering, model training, tuning, and evaluation.

---

## 📊 Dataset

We used the **Credit Card Fraud Detection dataset**:

🔗 https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

* Highly imbalanced dataset
* Majority class: Normal transactions
* Minority class: Fraud transactions

---

## ⚙️ Project Pipeline

### 1. Data Preprocessing

* Data cleaning
* Feature scaling using `StandardScaler`
* Train / Test split
* Preventing **data leakage**
* Handling imbalance using class weights

---

### 2. Feature Engineering 🔥

* Log transformation for skewed features
* Ratio-based features
* Time-based features
* Creation of additional informative variables

---

### 3. Model Design

We experimented with multiple models:

* Logistic Regression
* Random Forest
* Gradient Boosting / XGBoost
* Artificial Neural Network (ANN)

---

### 4. Training & Hyperparameter Tuning

* Used **GridSearchCV** for optimization
* Tuned key parameters such as:

  * Learning rate
  * Number of estimators
  * Model depth

---

### 5. Evaluation Metrics

Models were evaluated using:

* Precision
* Recall
* F1-score
* ROC-AUC
* Precision-Recall Curve
* Confusion Matrix

---

## 📈 Final Results ⭐

The best-performing model achieved:

* **Precision: 0.91 🔥**
* **Recall: 0.80**
* **F1-score: 0.85 🔥🔥**
* **PR-AUC: 0.74**

### 🏆 Performance Summary

The model demonstrates:

* Very high precision → minimal false alarms
* Strong recall → detects most fraud cases
* Excellent balance → suitable for real-world fraud detection

---

## 🚀 Conclusion

The final model provides strong performance by:

* Effectively handling imbalanced data
* Using feature engineering to improve detection
* Achieving a strong balance between precision and recall

---

## 📌 Future Work

* Explore ensemble methods
* Improve feature engineering
* Experiment with advanced deep learning architectures

---
