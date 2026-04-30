# Customer Churn Prediction in Telecommunications

This project focuses on predicting customer churn in the telecom industry using machine learning models. The goal is not only to achieve strong predictive performance, but also to make the model decisions interpretable and useful for real-world business applications.

## Project Overview
Customer churn is a major challenge in telecommunications, where retaining existing customers is significantly more cost-effective than acquiring new ones. 

Most existing research focuses heavily on improving accuracy, but often ignores model interpretability. This project addresses that gap by combining:
- Model comparison
- Feature engineering
- Explainability (using SHAP)

within a single unified framework.

---

## Models Implemented
The following machine learning models were used:
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

These models were selected to compare simple interpretable approaches with more complex ensemble methods.

---

## Key Features of the Project
- Feature Engineering (e.g., Charge-to-Tenure Ratio)
- Ablation Study (Raw vs Engineered Features)
- SHAP Explainability (Global + Local explanations)
- Handling Class Imbalance using proper evaluation metrics

---

## Evaluation Metrics
Due to class imbalance, the following metrics were prioritised:
- F1-score
- PR-AUC 
- ROC-AUC
- Precision & Recall

---

## Key Findings
- Logistic Regression performed well on raw features.
- Gradient Boosting performed best after feature engineering.
- The **Charge-to-Tenure Ratio** was identified as the most important feature.
- Feature engineering improved all tree-based models.

---

## Tools & Technologies
- Python
- Google Colab
- Pandas & NumPy
- Scikit-learn
- SHAP
- Matplotlib

---

## Dataset
- IBM Telco Customer Churn Dataset (public and anonymised)

---

## How to Run the Project
1. Open the notebook in Google Colab
2. Run all cells step by step
3. Ensure required libraries are installed


---

## Author
Md Ashraful Islam  
