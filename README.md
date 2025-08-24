# credit-card-fraud-detection
A machine learning project to detect fraudulent credit card transactions
#DATASETS 
Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)  
- Contains **284,807 transactions**, of which only **492 are frauds** (~0.17%).  
- Highly **imbalanced dataset**.
# Project Structure 

credit-card-fraud-detection/
│── data/
│   └── creditcard.csv
│── README.md
│── fraud.ipynb   


# Models Used

Logistic Regression

Random Forest Classifier

XGBoost
# Evaluation Metrics

Since the dataset is imbalanced, accuracy is not reliable.
We use:

Precision

Recall

F1-Score

ROC-AUC

# RESULTS 
| Model               | Precision | Recall | F1-score | ROC-AUC |
| ------------------- | --------- | ------ | -------- | ------- |
| Logistic Regression | 0.89      | 0.62   | 0.73     | 0.95    |
| Random Forest       | 0.97      | 0.76   | 0.85     | 0.99    |
| XGBoost             | 0.96      | 0.80   | 0.87     | 0.99    |
# FUTURE WORK 
Deploy as a Streamlit web app

Use Deep Learning (Autoencoders / LSTMs)

Improve imbalance handling with SMOTE
