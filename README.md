# 💳 Credit Card Fraud Detection

This project focuses on identifying fraudulent credit card transactions using machine learning. Due to the heavily imbalanced nature of the dataset, the analysis includes techniques like undersampling, SMOTE, and multiple classification models to improve detection accuracy and reduce false negatives.
---
## 📌 Project Overview

- **Dataset**: Credit Card Fraud Detection dataset from Kaggle
- **Objective**: Accurately identify fraudulent transactions while handling class imbalance
- **Techniques Used**:
  - Data preprocessing and scaling
  - Undersampling and SMOTE for class imbalance
  - Classifier comparison: Logistic Regression, K-Nearest Neighbors, Support Vector Machine, Decision Tree
  - Model evaluation using Accuracy, Precision, Recall, F1-Score, ROC-AUC
  - Learning curves and ROC curve visualization
---
## 🗂️ Project Structure
```
credit-card-fraud-detection/
├── credit_card_fraud_detection.ipynb     # Main notebook
├── README.md                             # Project documentation
├── requirements.txt                      # Project dependencies
└── images/                               # Folder for visual outputs
    ├── learning_curves.png
    └── roc_curves.png
```

## 📊 Results Summary

| Model                  | AUC Score (sample) |
|------------------------|--------------------|
| Logistic Regression    | 0.96               |
| K-Nearest Neighbors    | 0.94               |
| Support Vector Machine | 0.93               |
| Decision Tree          | 0.90               |

> Note: Update the table with actual values from your notebook.

## 📷 Visualizations

### ROC Curves  
![ROC Curve](images/roc Curve.png)

### Learning Curves  
![results](images/results.png)

## ⚙️ How to Run

1. **Clone the repo**
   ```bash
   git clone https://github.com/Theepankumargandhi/CreditCard-Fraud-detection cd credit-card-fraud-detection
   cd credit-card-fraud-detection
