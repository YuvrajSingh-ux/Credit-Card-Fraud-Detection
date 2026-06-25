# 💳 Credit Card Fraud Detection using Machine Learning

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-orange?style=for-the-badge&logo=scikit-learn)
![XGBoost](https://img.shields.io/badge/XGBoost-green?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-black?style=for-the-badge&logo=pandas)
![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)

**A machine learning pipeline for detecting fraudulent credit card transactions using data preprocessing, imbalance handling, dimensionality reduction, and ensemble learning techniques.**

</div>

---

# 🖼️ Project Thumbnail

<p align="center">
<img src="assets/thumbnail.png" width="900">
</p>

---

# 📌 Overview

Credit card fraud is one of the most challenging problems in the financial industry due to the highly imbalanced nature of transaction data.

This project develops a fraud detection pipeline that combines:

- Data preprocessing
- Outlier treatment
- SMOTE oversampling
- Principal Component Analysis (PCA)
- Multiple machine learning models
- Performance evaluation using classification metrics

The final implementation uses **XGBoost** to classify transactions as **Fraudulent** or **Legitimate**.

---

# ✨ Features

- 📊 Exploratory Data Analysis
- 📈 Data Visualization
- 🧹 Data Cleaning
- ⚖️ Class Imbalance Handling using SMOTE
- 📉 Dimensionality Reduction using PCA
- 🌲 Random Forest
- 📉 Logistic Regression
- 🎯 Support Vector Machine
- 🚀 XGBoost Classifier
- 📊 Confusion Matrix
- 📈 Accuracy, Precision, Recall and F1-score Evaluation

---

# 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| Language | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Oversampling | SMOTE |
| Gradient Boosting | XGBoost |

---

# 📂 Dataset

This project uses the **Credit Card Fraud Detection Dataset**, containing anonymized transactions made by European cardholders.

Dataset characteristics:

- Highly imbalanced dataset
- Fraudulent transactions represent only a small fraction of all transactions
- PCA-transformed features
- Transaction Amount
- Binary target variable (`Class`)
  - 0 → Legitimate
  - 1 → Fraudulent

---

# 🔄 Workflow

```

Credit Card Dataset
│
▼
Exploratory Data Analysis
│
▼
Data Cleaning
│
▼
Outlier Treatment
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
├── SVM
└── XGBoost
│
▼
Performance Evaluation

```

---

# 📁 Project Structure

```

Credit-Card-Fraud-Detection/

│
├── Credit card fraud detection.ipynb
├── requirements.txt
├── README.md
│
├── assets/
│ ├── thumbnail.png
│ └── screenshots/
│
└── dataset/
└── creditcard.csv

```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/Credit-Card-Fraud-Detection.git

cd Credit-Card-Fraud-Detection
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Notebook

```bash
jupyter notebook
```

Open:

```

Credit card fraud detection.ipynb

```

---

# 📊 Machine Learning Pipeline

### Data Preprocessing

- Missing value check
- Outlier clipping
- Feature scaling

### Imbalance Handling

- SMOTE Oversampling

### Dimensionality Reduction

- Principal Component Analysis (PCA)

### Models Evaluated

- Logistic Regression
- Random Forest
- Support Vector Machine
- XGBoost

---

# 📈 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

# 🚀 Future Improvements

- Hyperparameter Optimization
- Deep Learning Models
- Explainable AI (SHAP/LIME)
- Real-Time Fraud Detection API
- Deployment using Flask/FastAPI

---

# 👤 Author

**Yuvraj Singh**

M.Sc. Computer Science  
National Institute of Technology, Tiruchirappalli

📧 Email: yuvraj.singh.nitt@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/yuvraj-singh-37a70b2a0

💻 GitHub: https://github.com/YOUR_GITHUB_USERNAME

---

# 📜 License

This project is licensed under the MIT License.
