# 🩺 Diagnosing Diabetes in Females (KNN Classification)

## 📌 Project Overview

This project predicts whether a **female patient is diabetic (Yes/No)** based on medical test results and health factors.
The model uses **K-Nearest Neighbors (KNN) Classification** to identify patterns in the dataset and classify patients accordingly.

---

## 📊 Dataset

**Source:** Diabetes Dataset with missing values

**Features & Range:**

* **Pregnant:** 0 – 17
* **Glucose:** 44 – 199
* **Diastolic\_BP:** 24 – 122
* **Skin\_Fold:** 7 – 99
* **Serum\_Insulin:** 14 – 846
* **BMI:** 18.2 – 67.1
* **Diabetes\_Pedigree:** 0.07 – 2.42
* **Age:** 21 – 81
* **Class (Target):** 0 = Non-Diabetic, 1 = Diabetic

---

## 🛠 Tools & Libraries

* **Python** – programming language
* **Google Colab / Jupyter Notebook** – execution environment
* **pandas** – data handling and preprocessing
* **missingno** – visualization of missing values
* **scikit-learn** – KNN model, train-test split, evaluation metrics

---

## ⚙️ Data Preprocessing

* Handled missing values using **mean/median imputation**:

  * Glucose → Median
  * Diastolic\_BP → Mean
  * Skin\_Fold → Mean
  * Serum\_Insulin → Median
  * BMI → Mean
* After imputation → **No missing values remained**.

---

## 🚀 Steps Implemented

1. Import required libraries
2. Load dataset from GitHub
3. Explore dataset (info, statistics, head)
4. Visualize missing values (bar, matrix)
5. Handle missing values (mean/median imputation)
6. Define features (X) and target (y)
7. Split dataset (60% train, 40% test)
8. Select **KNN Classifier**
9. Train model on training data
10. Predict outcomes on test data
11. Evaluate using classification report

---

## 📈 Model Performance

* **Accuracy:** \~73%
* **Precision / Recall / F1-Score:**

| Class                | Precision | Recall | F1-Score | Support |
| -------------------- | --------- | ------ | -------- | ------- |
| **0 (Non-Diabetic)** | 0.84      | 0.76   | 0.80     | 322     |
| **1 (Diabetic)**     | 0.54      | 0.66   | 0.60     | 139     |

🔹 **Macro Avg:** 0.70
🔹 **Weighted Avg:** 0.74

---

## 📌 How to Use

1. Open `diabetes_knn.ipynb` in **Google Colab**
2. Run all cells to perform:

   * Data preprocessing
   * Model training
   * Prediction
   * Evaluation results

---

## 🔮 Future Improvements

* Apply **feature scaling (StandardScaler/MinMaxScaler)** to improve KNN performance.
* Experiment with **different values of K** (hyperparameter tuning with GridSearchCV).
* Use **distance-weighted KNN** instead of uniform weighting.
* Compare with other models: Logistic Regression, Random Forest, SVM.
* Perform **cross-validation** for more reliable evaluation.
* Add **ROC-AUC curve and confusion matrix visualization**.

---

## 👨‍💻 Author

**Shailendra Singh**
