# credit-card-fraud-detection
A machine learning project for fraud detection.
# 🛡️ Credit Card Fraud Detection

## 🚀 Project Overview
This project detects fraudulent credit card transactions using **machine learning models**. We compare **Logistic Regression, Random Forest, and XGBoost** to determine the best fraud detection strategy.

## 📊 Dataset Information
- **Transactions:** 568,630
- **Features:** 28 PCA-transformed columns + `Amount`
- **Target Variable (`Class`):**  
  - 0 = Legitimate Transaction  
  - 1 = Fraudulent Transaction  

## 🛠️ Methodology
1. **Data Cleaning & Feature Scaling**  
2. **Model Selection & Training**
   - **Logistic Regression**
   - **Random Forest**
   - **XGBoost**
3. **Evaluation Using:**
   - Accuracy, Precision, Recall, F1-score
   - ROC-AUC Score
   - Confusion Matrix

## 📈 Results Summary
| Model               | Accuracy | ROC-AUC Score | Precision (Fraud) | Recall (Fraud) | F1-Score (Fraud) |
|---------------------|----------|--------------|------------------|---------------|----------------|
| **Logistic Regression** | 96%      | 0.9935        | 0.98             | 0.95          | 0.96           |
| **Random Forest**      | 100%     | 0.9999        | 1.00             | 1.00          | 1.00           |
| **XGBoost**           | 100%     | 0.9999        | 1.00             | 1.00          | 1.00           |

## 🔍 Business Insights
- **Fraud detection is highly effective with ML models (96-100% accuracy).**
- **XGBoost & Random Forest outperform Logistic Regression, but may be overfitting.**
- **Logistic Regression is best for real-time detection; XGBoost is better for high-value transactions.**
