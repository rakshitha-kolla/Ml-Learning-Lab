# 🧠 Customer Churn Prediction

This project builds a supervised machine learning pipeline to predict customer churn, helping businesses proactively retain high-risk customers. It demonstrates end-to-end workflow from data preprocessing to model evaluation, with a strong focus on feature engineering and interpretability.

---

## 📊 Project Overview

- **Goal**: Predict whether a customer will churn based on behavioral and demographic features.
- **Dataset**: [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Tech Stack**: Python, scikit-learn, pandas, matplotlib, seaborn

---

## 🔍 Workflow Summary

1. **EDA & Cleaning**
   - Handled missing values, outliers, and categorical inconsistencies
   - Visualized churn distribution and feature correlations

2. **Feature Engineering**
   - Scaled numerical features using `StandardScaler`
   - Encoded categorical variables (`OneHotEncoding`, `LabelEncoding`)
   - Created derived features (e.g., tenure buckets, contract type flags)

3. **Dimensionality Reduction**
   - Applied PCA to reduce feature space while retaining 95% variance
   - Visualized PCA components and explained variance

4. **Modeling**
   - Trained multiple classifiers: Logistic Regression, Random Forest, SVM
   - Tuned hyperparameters using GridSearchCV
   - Evaluated using accuracy, precision, recall, F1-score, ROC-AUC
5. **Interpretability**
   - Used Random Forest feature importance
   - Compared model performance across metrics
---

## 📈 Results

- **Top Features**: MonthlyCharges, ContractType, Tenure, InternetService
- **Business Insight**: Customers with month-to-month contracts and high charges are more likely to churn
- **Next Steps**:
  - Apply clustering on PCA-reduced data for segmentation
  - Deploy model using Streamlit or Flask
  - Write blog post summarizing business impact and technical workflow

---

## 📞 Contact

KOLLA RAKSHITHA - [krakshitha0987@gmail.com](krakshitha0987@gmail.com)
Linkdin - https://www.linkedin.com/in/rakshitha-kolla-127637229/

Project Link: [https://github.com/rakshitha-kolla/ML-Learning-Lab](https://github.com/rakshitha-kolla/Ml-Learning-Lab/new/main/customer_churn)

---

