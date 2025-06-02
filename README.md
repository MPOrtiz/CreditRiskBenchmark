# Credit Risk Prediction Project

This project aims to predict the probability of serious delinquency within the next two years, based on financial and demographic attributes of loan applicants. The goal is to support better credit risk decisions using interpretable and robust machine learning models.

## 🔍 Problem Statement
The task is to classify borrowers as risky or not, with imbalanced class distribution and regulatory requirements for explainability.

## 📊 Key Findings
- Individuals aged 40–60 tend to have more credit lines and higher income.
- Peak financial exposure often occurs around age 55–65.
- Debt ratio and late payments behave differently by age group.
- CatBoost delivered the best performance, with a test ROC-AUC of 0.86 and F1 score of 0.78.

## ⚙️ Tools & Techniques
- Python, Pandas, NumPy
- Scikit-learn, CatBoost, XGBoost, Random Forest
- SHAP for explainability
- Visualizations with Matplotlib and Seaborn
- Jupyter Notebook

## 📁 Files
- `Project.ipynb`: full modeling workflow
- `outputs/`: ROC-AUC and F1 visualizations
- `data/`: dataset (if permitted to share)

## 📈 Results Summary

| Model              | Test ROC-AUC | Test F1 |
|--------------------|--------------|---------|
| Logistic Regression| 0.7903       | 0.6899  |
| Random Forest      | 0.8519       | 0.7717  |
| CatBoost           | 0.8607       | 0.7801  |
| XGBoost            | 0.8538       | 0.7759  |
| SVM                | 0.8093       | 0.6776  |

## 📎 Demo or Report
You can view the full notebook and visual insights [here](./Project.ipynb).
