
# 🧠 Logistic Regression Model Development

This project demonstrates a complete end-to-end implementation of Logistic Regression using various scenarios and evaluation techniques. Below are the key highlights:

## ✅ Binary Classification

- Used `make_classification` from `sklearn.datasets` to generate a dataset with **10 features**.
- Implemented **Logistic Regression** from scratch and using `sklearn`.
- Evaluated model performance using metrics like:
  - **Precision**
  - **Recall**
  - **F1 Score**
- Conducted **Hyperparameter Tuning** using:
  - `GridSearchCV`
  - `RandomizedSearchCV`
- Compared performance improvements post tuning.

## 🔢 Multiclass Classification

- Extended Logistic Regression to handle **multiclass classification** problems.
- Evaluated the model using **macro** and **weighted** averages of precision, recall, and F1 scores.

## ⚖️ Imbalanced Dataset

- Addressed class imbalance in the dataset.
- Applied techniques like:
  - Class weight adjustment in `LogisticRegression`

---

Feel free to explore the code, tweak hyperparameters, and experiment with various datasets to understand how logistic regression behaves in different scenarios.
