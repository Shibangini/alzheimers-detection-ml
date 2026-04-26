# 🧠 Alzheimer’s Detection using Multi-Omics & Ensemble Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange?logo=scikitlearn)
![XGBoost](https://img.shields.io/badge/XGBoost-Enabled-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

> 🚀 Improved Alzheimer’s detection using Bagging + Multi-run Ensemble Learning

---

## 📌 Overview
This project detects Alzheimer’s disease using **Gene Expression (GE)** and **DNA Methylation (DM)** data.  
The proposed method improves performance using **bagging and multi-run ensemble learning**.

---

## ⚙️ Methodology

### 🔹 Previous Work
- Pairwise GE + DM integration  
- Single-run training  

### 🔹 Proposed Work
- Label-based GE + DM combination  
- StandardScaler  
- Bagging (10 bootstrap samples)  
- Multi-run ensemble (5 runs)  
- Soft voting  

---

## 🧠 Models Used
- SVM  
- Random Forest (tuned)  
- XGBoost  
- Logistic Regression  
- Naive Bayes  

---

## 📊 Results

### 🔹 Proposed Work

| Model | Accuracy |
|------|--------|
| Random Forest | ⭐ 0.8837 |
| XGBoost | ⭐ 0.8837 |
| SVM | 0.8605 |
| Logistic Regression | 0.8605 |
| Naive Bayes | 0.6279 |

---

### 🔹 Comparison

| Model | Previous | Proposed |
|------|---------|----------|
| SVM | 0.80 | 0.86 |
| Random Forest | 0.87 | 0.88 |
| XGBoost | 0.87 | 0.88 |
| Logistic Regression | 0.86 | 0.86 |
| Naive Bayes | 0.46 | 0.63 |

---

## 🔍 Key Improvements
- Reduced randomness using ensemble learning  
- Improved SVM and Naive Bayes significantly  
- Tuned Random Forest (0.81 → 0.88)  
- More stable and reliable predictions  

---

## 📁 Project Structure
Alzheimers-Detection-ML/
│
├── notebooks/
├── results/
├── README.md

---

## 🧠 Tech Stack
Python • NumPy • Pandas • Scikit-learn • XGBoost • Matplotlib  

---

## 🎯 Conclusion
The proposed approach improves **stability and generalization** compared to the previous method, while achieving strong performance across models.

---

## 👩‍💻 Author
**Shibangini Kar**
