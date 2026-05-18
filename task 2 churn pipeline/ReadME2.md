# 🔄 Customer Churn Prediction using ML Pipeline

## 📌 Objective

Develop a production-ready machine learning pipeline to predict customer churn using Scikit-learn.

---

## 📂 Dataset

* Telco Customer Churn Dataset
* Includes customer demographics and service usage

---

## ⚙️ Workflow

### 🔹 Data Preprocessing

* Handled missing values
* Encoded categorical variables (OneHotEncoder)
* Scaled numerical features (StandardScaler)

### 🔹 Pipeline Creation

* Built pipeline using `Pipeline`
* Combined preprocessing + model

### 🔹 Model Training

* Logistic Regression
* Random Forest

### 🔹 Hyperparameter Tuning

* Used `GridSearchCV`
* Tuned parameters for best performance

### 🔹 Evaluation

* Accuracy
* Precision
* Recall
* F1-score

---

## 💾 Model Saving

* Exported pipeline using `joblib`
* Ready for reuse in production

---

## 🛠️ Tech Stack

* Python
* Scikit-learn
* Pandas
* NumPy
* Joblib

---

## 📈 Skills Learned

* ML Pipeline Development
* Hyperparameter Tuning
* Model Optimization
* Production-ready ML

---

## ▶️ How to Run

```bash
pip install scikit-learn pandas numpy joblib
python train_pipeline.py
```

---

## 📌 Output

* Churn prediction (Yes/No)
* Optimized trained pipeline

---
