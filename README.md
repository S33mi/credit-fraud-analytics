# Credit Fraud Analytics

Personal project analyzing credit card transaction data for fraud detection using anomaly detection techniques.  
Focus: Handling highly imbalanced datasets (fraud is rare ~0.17%), evaluating unsupervised methods like Isolation Forest.

## Why this project?
- Builds on my background in anomaly/outlier detection.
- Demonstrates practical data analysis skills: preprocessing, imbalance handling, model evaluation (PR-AUC, confusion matrix, etc.).
- Relevant to risk/fraud analytics in finance (e.g., banking roles).

## Dataset
- Primary: [Credit Card Fraud Detection (Kaggle/ULB)](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
  - 284,807 transactions over 2 days (2013 European cardholders)  
  - 492 frauds (~0.172%)  
  - Features: 28 PCA-transformed variables (V1–V28) + Time + Amount + Class (0=legit, 1=fraud)  
  - Anonymized for privacy.

Alternative datasets (if you want variety):  
- [Credit Card Transactions Fraud Detection (2020 simulated)](https://www.kaggle.com/datasets/kartik2112/fraud-detection)  
- [Credit Card Fraud 2023](https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023)

## Current Notebook
- `credit_fraud_anomaly_detection.ipynb` → Isolation Forest baseline + evaluation.

More to come: Compare with Local Outlier Factor, Autoencoders, or supervised models (e.g., XGBoost with SMOTE).

## Setup (Colab/Local)
```bash
pip install -r requirements.txt
jupyter notebook
```
Or open directly in Colab: ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)

## Skills Demonstrated

· Python · Pandas · Scikit-learn · Anomaly Detection · Imbalanced Data · Visualization (Matplotlib/Seaborn)

Questions/collabs? Feel free to open an issue or reach out!

Main profile: github.com/S33mi | Casual X: [@Seemi_Rauf](x.com/Seemi_Rauf)
