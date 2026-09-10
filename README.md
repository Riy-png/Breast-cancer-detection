# Breast Cancer Detection & Diagnostic Classification

A machine learning project focused on classifying breast mass diagnostics as malignant or benign using the Wisconsin Diagnostic Breast Cancer dataset. This repository covers data preprocessing, feature analysis, model training, and performance evaluation.

## 🚀 Key Technical Highlights
* **Model Training:** Implemented a binary classification pipeline using Logistic Regression in Python.
* **Feature Analysis:** Cleaned, scaled, and analyzed diagnostic feature sets using Pandas and NumPy.
* **Metric Optimization:** Evaluated performance using Confusion Matrices, Precision, Recall, and F1-Scores—prioritizing **Recall** to minimize critical False Negatives.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## 📊 Model Evaluation Focus
In diagnostic and high-stakes classification tasks, minimizing False Negatives (missing a malignant case) takes priority over Precision. 

* **Recall Priority:** Ensures hostile or critical targets are identified reliably.
* **Confusion Matrix:** Tracks True Positives, False Positives, True Negatives, and False Negatives across classification decision thresholds.

## 📁 Repository Structure
├── breast_cancer_detection.ipynb  # Data Processing & Model Evaluation
├── README.md                      # Project Documentation
└── requirements.txt               # Dependencies
