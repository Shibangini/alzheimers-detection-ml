🧠 Alzheimer’s Detection using Multi-Omics Data & Ensemble Learning
📌 Overview

This project focuses on the early detection of Alzheimer’s disease using multi-omics data integration, combining Gene Expression (GE) and DNA Methylation (DM) datasets.

The work extends a previous approach by introducing a bagging-based multi-run ensemble technique to improve robustness, stability, and generalization.

🎯 Objectives
Integrate heterogeneous biological datasets (GE + DM)
Reduce dimensionality using Autoencoders
Improve classification performance using Ensemble Learning
Compare proposed method with previous year’s approach
🧬 Dataset Description
Gene Expression (GE): ~39,280 features → reduced to 64
DNA Methylation (DM): ~485,577 features → reduced to 16
Data combined using label-based matching (AD vs Normal)
⚙️ Methodology
🔹 Previous Approach
Pairwise integration of GE and DM
Single-run training
Models used:
Logistic Regression
Random Forest
SVM
Naive Bayes
XGBoost
🔹 Proposed Approach (This Work)
Label-based combination of GE and DM
Feature scaling using StandardScaler
Bagging (Bootstrap Sampling)
Multi-run Ensemble (5 runs)
Soft Voting (probability averaging)
🧠 Models Used
Support Vector Machine (SVM)
Random Forest (Tuned)
XGBoost
Logistic Regression
Naive Bayes
📊 Results
🔹 Proposed Work Performance
Model	Accuracy
Random Forest	⭐ 0.8837
XGBoost	⭐ 0.8837
SVM	0.8605
Logistic Regression	0.8605
Naive Bayes	0.6279
🔹 Comparison with Previous Work
Model	Previous	Proposed	Improvement
SVM	0.8001	0.8605	⬆ Significant
Random Forest	0.8717	0.8837	⬆ Slight
XGBoost	0.8706	0.8837	⬆ Slight
Logistic Regression	0.8635	0.8605	≈ Stable
Naive Bayes	0.4620	0.6279	⬆ Major
🔍 Key Insights
Ensemble learning significantly improves model stability
Multi-run approach reduces dependency on random data pairing
Strong improvement observed in weaker models (SVM, Naive Bayes)
Random Forest and XGBoost achieved best performance (~88%)
🚀 Key Contributions
Introduced Bagging + Multi-run Ensemble for multi-omics integration
Improved Random Forest performance (0.81 → 0.88) through tuning
Reduced randomness and increased prediction consistency
Provided a robust alternative to pairwise integration
📁 Project Structure
Alzheimers-Detection-ML/
│
├── notebooks/                # Jupyter notebooks (pipeline & experiments)
├── results/                  # Results, graphs, comparison files
├── README.md                 # Project documentation
🧠 Technologies Used
Python
NumPy, Pandas
Scikit-learn
XGBoost
Matplotlib
🎯 Conclusion

The proposed ensemble-based approach improves robustness, stability, and generalization compared to the previous pairwise integration method. While accuracy improvements are moderate, the consistency and reliability of predictions are significantly enhanced.

📌 Future Work
Use larger matched datasets
Apply deep learning models (CNN, Transformer-based models)
Explore feature importance and explainability (SHAP, LIME)
👩‍💻 Author

Shibangini Kar
B.Tech CSE | Final Year Project
