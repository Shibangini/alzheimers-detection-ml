# 🧠 Alzheimer’s Detection using Multi-Omics Integration & Machine Learning

## 📌 Overview

This project focuses on detecting **Alzheimer’s Disease (AD)** by integrating **Gene Expression (GE)** and **DNA Methylation (DM)** data using a multi-omics approach.

We applied **autoencoder-based dimensionality reduction** and a **pairwise integration strategy**, followed by machine learning models for classification.

---

## 🚀 Key Features

* 🔬 Multi-omics data integration (GE + DM)
* 🧠 Autoencoder-based feature extraction
* 🔗 Pairwise integration of biological data
* ⚠️ Data leakage identification and correction
* 📊 Comparative analysis of ML models
* 📈 Visualization using graphs and confusion matrix

---

## 📂 Dataset

* Gene Expression datasets:

  * GSE33000
  * GSE44770
* DNA Methylation dataset:

  * GSE80970

---

## ⚙️ Methodology

### 1️⃣ Preprocessing

* Data cleaning and label extraction
* Conversion to numerical format
* Merging GE datasets

### 2️⃣ Train-Test Split

* 70–30 stratified split
* Avoided data leakage

### 3️⃣ Feature Reduction (Autoencoder)

* GE: **39280 → 64 features**
* DM: **485577 → 16 features**

### 4️⃣ Pairwise Integration

* Combined GE and DM features based on matching class labels
* Final feature vector: **80 features**

### 5️⃣ Leakage Fix

* Ensured train and test pairing were done separately
* Prevented overlap between datasets

---

## 🤖 Models Used

* Logistic Regression
* Random Forest ⭐
* Support Vector Machine (SVM)

---

## 📊 Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 86.35%   |
| Random Forest       | ⭐ 87.17% |
| SVM                 | 80.01%   |

---

## 📈 Visualizations

* 📊 Model comparison bar graph
* 🔲 Confusion matrix (Random Forest)

---

## 🏆 Key Insights

* Random Forest performed best due to its ability to handle **nonlinear high-dimensional data**
* Autoencoder effectively reduced dimensionality while preserving important patterns
* Proper handling of **data leakage** significantly improved reliability of results

---

## 🧠 Conclusion

This project demonstrates that combining **multi-omics data** with **deep learning-based feature extraction** improves Alzheimer’s detection performance.

---

## 🛠️ Tech Stack

* Python
* NumPy, Pandas
* Scikit-learn
* TensorFlow / Keras
* Matplotlib

---

## 📌 Future Work

* Apply advanced deep learning models
* Use larger datasets
* Explore feature selection techniques
* Perform robust cross-validation

---

## 👩‍💻 Author

**Shibangini Kar**
B.Tech CSE | Final Year Project

---
