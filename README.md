# 🎯 Sonar Rock vs Mine Prediction using Logistic Regression

This project builds a binary classification model using **Logistic Regression** to identify whether sonar signal reflections correspond to a **rock** or a **mine**.

---

## 📘 Overview

Sonar signals reflect differently when they hit metallic mines versus ordinary rocks. Using the **UCI Sonar Dataset**, we train a machine learning model to distinguish between the two based on 60 numerical frequency-based features.

---

## 🧾 Dataset Information

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks))
- **Samples**: 208
- **Features**: 60 numerical (signal strength at different frequencies)
- **Target**:  
  - `M` → Mine  
  - `R` → Rock

---

## 📌 Technologies Used

- Python 3
- Pandas, NumPy
- Scikit-learn (Logistic Regression, train-test split, accuracy score)
- Google Colab (based on the file path used)

---

## 🔍 Model Used

- **Logistic Regression**
  - Trained on 70% of the data, tested on 30%
  - Accuracy measured using `accuracy_score`

---



