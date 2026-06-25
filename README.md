# 💳 Credit Card Fraud Detection using Machine Learning

<p align="center">
  <img src="assets/thumbnail.png" alt="Credit Card Fraud Detection" width="900"/>
</p>

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-orange?style=for-the-badge&logo=scikit-learn)
![XGBoost](https://img.shields.io/badge/XGBoost-green?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-black?style=for-the-badge&logo=pandas)
![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)

**A machine learning pipeline for detecting fraudulent credit card transactions using data preprocessing, class imbalance handling, dimensionality reduction, and ensemble learning techniques.**

</div>

---

# 📌 Overview

Credit card fraud detection is one of the most important applications of machine learning in the financial industry. Since fraudulent transactions account for only a tiny fraction of all transactions, the problem is highly imbalanced and requires specialized preprocessing and evaluation techniques.

This project develops a complete fraud detection pipeline that combines data preprocessing, oversampling, dimensionality reduction, and multiple machine learning algorithms to accurately classify fraudulent transactions.

The final implementation uses **XGBoost**, achieving **99.96% accuracy** while maintaining strong precision and recall on fraud cases.

---

# ⭐ Key Highlights

- 📊 Exploratory Data Analysis (EDA)
- 🧹 Data Cleaning & Preprocessing
- ⚖️ Class Imbalance Handling using **SMOTE**
- 📉 Principal Component Analysis (PCA)
- 🌲 Random Forest Classifier
- 📈 Logistic Regression
- 🎯 Support Vector Machine (SVM)
- 🚀 XGBoost Classifier
- 📊 Confusion Matrix Visualization
- 📈 Performance Evaluation using Accuracy, Precision, Recall, and F1-Score

---

# 🛠️ Tech Stack

| Category | Technology |
|-----------|------------|
| Language | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Oversampling | SMOTE |
| Gradient Boosting | XGBoost |

---

# 📂 Dataset

This project uses the **Credit Card Fraud Detection Dataset**, containing anonymized transactions made by European cardholders.

### Dataset Features

- Highly imbalanced dataset
- PCA-transformed numerical features
- Transaction Amount feature
- Binary target variable:
  - **0 → Legitimate Transaction**
  - **1 → Fraudulent Transaction**

Dataset Source:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

---

# 🔄 Machine Learning Pipeline

```text
Credit Card Dataset
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Data Cleaning
        │
        ▼
Train-Test Split
        │
        ▼
Feature Scaling
        │
        ▼
SMOTE Oversampling
        │
        ▼
Principal Component Analysis
        │
        ▼
Model Training
   ├── Logistic Regression
   ├── Random Forest
   ├── Support Vector Machine
   └── XGBoost
        │
        ▼
Performance Evaluation
```

---

# 📁 Project Structure

```text
Credit-Card-Fraud-Detection/

│
├── Credit card fraud detection.ipynb
├── README.md
│
└── assets/
    ├── thumbnail.png
    └── confusion_matrix.png
```

---

# 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Credit-Card-Fraud-Detection.git

cd Credit-Card-Fraud-Detection
```

### Open the notebook

Open

```text
Credit card fraud detection.ipynb
```

using

- Jupyter Notebook
- Jupyter Lab
- VS Code
- Google Colab

Run all the notebook cells sequentially to reproduce the results.

---

# 🤖 Models Evaluated

The following machine learning algorithms were trained and compared:

- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- XGBoost

The **XGBoost Classifier** achieved the best overall performance and was selected as the final model.

---

# 📊 Results

The final XGBoost model achieved the following performance on the test dataset.

| Metric | Score |
|---------|-------:|
| **Accuracy** | **99.96%** |
| **Recall** | **89.23%** |
| **Precision** | **85.29%** |
| **F1-Score** | **87.22%** |

These results demonstrate that the model effectively detects fraudulent transactions while maintaining a very low false positive rate, making it suitable for highly imbalanced financial datasets.

---

# 📈 Confusion Matrix

<p align="center">
  <img src="assets/confusion_matrix.png" alt="Confusion Matrix" width="600"/>
</p>

---

# 🚀 Future Improvements

- Hyperparameter Optimization
- Deep Learning-based Fraud Detection
- Explainable AI using SHAP/LIME
- Real-Time Fraud Detection API
- Deployment using FastAPI or Flask
- Streaming Fraud Detection for Live Transactions

---

# 👤 Author

**Yuvraj Singh**

M.Sc. Computer Science  
National Institute of Technology, Tiruchirappalli (2024–2026)

📧 **Email:** yuvraj.singh.nitt@gmail.com

🔗 **LinkedIn:**  
https://www.linkedin.com/in/yuvraj-singh-37a70b2a0

💻 **GitHub:**  
https://github.com/YOUR_GITHUB_USERNAME

---

# 📜 License

This project is licensed under the MIT License.
