# 💳 Credit Card Approval Prediction

This project predicts whether a **credit card application** will be **approved or rejected** using **Machine Learning models**.
It involves **data preprocessing, encoding, model training, hyperparameter tuning, and evaluation**.

---

## 🚀 Project Overview

The notebook performs the following steps:

1. **Importing Libraries** – Loading required Python libraries (pandas, numpy, sklearn, xgboost, matplotlib, seaborn, etc.)
2. **Data Preprocessing** – Handling missing values and categorical features.
3. **Encoding Data** – Using **Label Encoding** to convert categorical variables into numeric form.
4. **Train-Test Split** – Splitting dataset into training and testing sets.
5. **Model Building** – Training machine learning models for credit card approval prediction:

   * **Decision Tree Classifier**
   * **XGBoost Classifier**
6. **Hyperparameter Tuning** – Using **RandomizedSearchCV** to optimize model performance.
7. **Model Evaluation** – Evaluating models with:

   * Accuracy
   * Confusion Matrix
   * Classification Report (Precision, Recall, F1-score)
   * Cross-validation scores

---

## 🛠️ Technologies Used

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn (Decision Tree, model selection, metrics)
* XGBoost
* Jupyter Notebook

---

## 📂 Dataset

The dataset contains applicant information used for predicting credit card approvals.
Features typically include:

* **Gender** – Applicant’s gender
* **Age** – Age of applicant
* **Family Status** – Marital/family information
* **Annual Income** – Applicant’s income
* **Employment Status** – Job details
* **Credit History** – Past credit record
* **Loan/Assets** – Financial details
* **Approval Status (Target Variable)** – 1 = Not Approved, 0 = Approved

---

## 📈 Expected Insights

* Applicants with **higher income** and **good credit history** are more likely to be approved.
* **Decision Tree** gives interpretable results but may overfit.
* **XGBoost** generally outperforms Decision Tree due to its ability to handle non-linearities and boosting.
* **RandomizedSearchCV** improves accuracy by tuning hyperparameters.

---
