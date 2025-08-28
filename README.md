# 💳 Credit Risk Scoring with Explainable AI

This project builds a machine learning model to predict whether a borrower will default on a loan. It also uses SHAP values for interpretability.

---

## 📌 Dataset

German Credit Dataset (binary classification: Good vs Bad credit)

📁 [Dataset Source](https://github.com/selva86/datasets/blob/master/GermanCredit.csv)

---

##  Model

- GradientBoostingClassifier (sklearn)
- Input: encoded features like `Age`, `CreditAmount`, `Job`, `Housing`, etc.
- Target: Creditworthiness (Good / Bad)

----

## ⚙️ Requirements

```bash
pip install pandas scikit-learn shap matplotlib
----
