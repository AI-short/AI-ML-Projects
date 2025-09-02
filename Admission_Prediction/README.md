# **Chance of Admission Prediction**

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![Colab](https://img.shields.io/badge/Open%20in-Colab-orange)](https://colab.research.google.com/github/ybifoundation/Dataset/blob/main/Admission%20Chance.csv)
[![Dataset](https://img.shields.io/badge/Dataset-CSV-green)](https://github.com/ybifoundation/Dataset/raw/main/Admission%20Chance.csv)

---

## **Project Overview**

Predict the probability of a student getting admission into **graduate programs** using their academic scores and test results.
Uses **Linear Regression** to estimate admission chances based on **GRE, TOEFL, CGPA, SOP, LOR, and Research Experience**.

---

## **Tools & Libraries**

* **Google Colab** – run and share notebooks online
* **Python** – programming language
* **pandas** – data handling and analysis
* **scikit-learn** – Linear Regression model & evaluation

---

## **Dataset**

* Source: [Admission Chance Dataset](https://github.com/ybifoundation/Dataset/raw/main/Admission%20Chance.csv)
* Features include:

  * **GRE Score:** 290–340
  * **TOEFL Score:** 92–120
  * **University Rating:** 1–5
  * **Statement of Purpose (SOP):** 1–5
  * **Letter of Recommendation (LOR) Strength:** 1–5
  * **Undergraduate CGPA:** 6.8–9.92
  * **Research Experience:** 0 or 1
  * **Chance of Admit:** 0.34–0.97
* **No missing values**; preprocessing not required

---

## **Steps Implemented**

1. Import libraries and dataset
2. Explore the dataset (info, statistics, top rows)
3. Define features (`X`) and target (`y`)
4. Split data into training (60%) and testing (40%) sets
5. Select model: **Linear Regression**
6. Train model on training data
7. Predict admission chances on test data
8. Evaluate model using **Mean Absolute Percentage Error (MAPE)**

---

## **Model Performance**

* **Mean Absolute Error Percentage (MAPE):** \~7.5%
* Predicts admission chances accurately based on student data

---

## **How to Use**

1. Open `admission_prediction.ipynb` in **Google Colab**
2. Run all cells to see:

   * Data analysis
   * Model training
   * Predictions
   * Evaluation results

---

## **Author**

**Shailendra Singh**
