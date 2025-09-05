# 🎓 Chance of Admission Prediction (KNN Regression)

## 📌 Project Overview

Predict the probability of a student getting admission into graduate programs using their academic scores and test results.
This project uses **K-Nearest Neighbors (KNN) Regression** to estimate admission chances based on features like GRE, TOEFL, CGPA, SOP, LOR, and Research Experience.

---

## 🛠️ Tools & Libraries

* **Google Colab** – run and share notebooks online
* **Python** – programming language
* **pandas** – data handling and analysis
* **scikit-learn** – KNN Regression model & evaluation

---

## 📊 Dataset

* **Source**: Admission Chance Dataset
* **Features include**:

  * GRE Score: 290–340
  * TOEFL Score: 92–120
  * University Rating: 1–5
  * Statement of Purpose (SOP): 1–5
  * Letter of Recommendation (LOR): 1–5
  * Undergraduate CGPA: 6.8–9.92
  * Research Experience: 0 or 1
* **Target Variable**: Chance of Admit (0.34–0.97)
* **Note**: No missing values; preprocessing not required

---

## ⚙️ Steps Implemented

1. Import libraries and dataset
2. Explore dataset (info, statistics, top rows)
3. Define features (X) and target (y)
4. Split data into training (60%) and testing (40%) sets
5. Select model: **K-Nearest Neighbors Regressor**
6. Train model on training data
7. Predict admission chances on test data
8. Evaluate model using **Mean Absolute Percentage Error (MAPE)**

---

## 📈 Model Performance

* **Mean Absolute Percentage Error (MAPE): \~9.5%**
* The model predicts admission chances with good accuracy based on student data

---

## 🚀 How to Use

1. Open **admission\_prediction\_knn.ipynb** in **Google Colab**
2. Run all cells to see:

   * Data analysis
   * Model training
   * Predictions
   * Evaluation results

---

## 👨‍💻 Author

**Shailendra Singh**
