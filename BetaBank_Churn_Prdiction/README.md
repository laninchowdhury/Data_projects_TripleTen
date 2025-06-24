# Beta Bank Customers: Predicting Customer Churn with Maximum F1 Score

This project focuses on predicting customer churn at Beta Bank using machine learning models. The goal is to maximize the F1 Score to balance precision and recall, ensuring high retention insights.

## 🧩 Problem Statement
Customer churn can significantly impact a bank’s revenue. By predicting churn early, the bank can implement retention strategies. This project aims to create a reliable predictive model.

## 🛠️ Tools & Technologies
- Python, pandas, NumPy
- scikit-learn
- matplotlib, seaborn

## 🔄 Process Overview
- **Data Cleaning:** Missing values handled and features encoded
- **EDA:** Identified trends between tenure, balance, and churn
- **Modeling:** Logistic Regression, Random Forest, XGBoost
- **Evaluation:** Focused on optimizing F1 Score due to class imbalance

## 📈 Visualizations

**Customer Tenure Distribution**
![Churn Distribution](images/churn_distribution.png)

**AUC-ROC Curve**
![AUC Curve](images/auc_curve.png)

## 📁 Files
- `beta_churn_model.ipynb` – Full notebook with EDA, modeling, and evaluation
- `images/` – Charts used for better interpretation

## ✅ Conclusion
The Random Forest model achieved the highest F1 Score, effectively identifying customers likely to churn. Tenure and account balance were among the top predictors. This model can help Beta Bank proactively reduce churn and improve customer retention.
