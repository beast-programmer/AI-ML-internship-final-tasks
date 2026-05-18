# 🏠 Multimodal Housing Price Prediction (Image + Tabular)

## 📌 Objective

Predict house prices using both structured data and house images (multimodal machine learning).

---

## 📂 Dataset

* Housing dataset (price, size, location, rooms)
* House images dataset (custom or public)

---

## ⚙️ Workflow

### 🔹 Image Processing

* Used CNN to extract features from images
* Converted images into feature vectors

### 🔹 Tabular Data Processing

* Cleaned dataset
* Selected important features
* Normalized values

### 🔹 Feature Fusion

* Combined image features + tabular features
* Created unified dataset

### 🔹 Model Training

* Regression model (Neural Network / Linear Regression)

### 🔹 Evaluation

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)

---

## 🛠️ Tech Stack

* Python
* TensorFlow / PyTorch
* OpenCV / PIL
* Scikit-learn

---

## 📈 Skills Learned

* Multimodal ML
* CNN Feature Extraction
* Feature Fusion
* Regression Modeling

---

## ▶️ How to Run

```bash
pip install tensorflow torch opencv-python scikit-learn pandas
python train_multimodal.py
```

---

## 📌 Output

* Predicted house prices
* Error metrics (MAE, RMSE)

---
