---
title: "Bank Customer Churn Prediction"
excerpt: "Machine Learning project analyzing 10,000 bank customer records to predict churn with MLP, boosting models, and interpretable feature engineering.<br/><img src='/images/churn-overview.png'>"
collection: portfolio
---

## Motivation
- Customer churn is a critical issue in banking: retaining customers is more cost-effective than acquiring new ones.  
- Goal: Build predictive models to identify **at-risk customers early** and guide **targeted retention strategies**.  
- Dataset: 10,000 customer records (Kaggle), with both numerical and categorical features, 20% churn rate.  

---

## Contribution
- Conducted **EDA** (distribution of age, balance, salary, geography, activity) to identify churn drivers.  
- Engineered features (e.g., interaction terms like Age × Balance, standardized scaling, one-hot encoding).  
- Compared multiple ML models: Logistic Regression, Random Forest, Gradient Boosting, MLP, XGBoost, LightGBM, CatBoost.  
- Optimized thresholds and hyperparameters for business-aligned recall vs. precision trade-offs.  

---

## Method
- **Data Preprocessing**: handled imbalance (20% churn vs 80% retained) by oversampling and threshold tuning.  
- **Baseline Models**: Logistic Regression (ROC-AUC 0.79) and Random Forest (Accuracy 73%, ROC-AUC 0.80).  
- **Boosting Models**: Gradient Boosting, XGBoost, LightGBM, CatBoost — CatBoost achieved Recall up to **82%** after threshold tuning.  
- **Neural Model**: Multi-Layer Perceptron (MLP) with dropout, batch size tuning → balanced performance across metrics.  

---

## Results
- **Best Model**: **MLP (Multi-Layer Perceptron)**  
  - Accuracy: 76%  
  - Recall (Churners): 73%  
  - Precision: 76%  
  - F1 Score: 76%  
  - ROC-AUC: 0.83  
- CatBoost also performed well, achieving Recall 82% after threshold optimization.  

📈 **Business Impact**: Higher recall ensures more churners are identified, enabling proactive retention.  

---

## Recommendations
- **Threshold tuning** based on business goals (recall vs precision trade-offs).  
- **Hyperparameter optimization** (dropout, learning rate) and ensemble methods (MLP + boosting).  
- **Continuous retraining** with updated data to adapt to market/customer behavior.  

---

## Screenshots
<img src="/images/ML1.jpg" width="650">
