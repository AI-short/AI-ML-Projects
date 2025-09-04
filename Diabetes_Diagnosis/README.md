# 🩺 Diagnosing Diabetes in Female Patients

## 📌 Project Overview
This project predicts whether a female patient is likely to have diabetes based on key medical features.  
A **Logistic Regression model** is applied after handling missing values to classify patients as **Diabetic (1)** or **Non-Diabetic (0)**.

---

## 🛠️ Tools & Libraries
- **Google Colab / Jupyter Notebook** – for running and sharing notebooks
- **Python** – programming language
- **pandas** – data handling and analysis
- **missingno** – visualization of missing data
- **scikit-learn** – Logistic Regression model, train-test split, and evaluation

---

## 📊 Dataset
**Source:** [Diabetes Missing Data.csv](https://github.com/YBI-Foundation/Dataset/raw/main/Diabetes%20Missing%20Data.csv)  

**Features (min–max values):**
1. Pregnant (0 – 17)  
2. Glucose (44 – 199)  
3. Diastolic_BP (24 – 122)  
4. Skin_Fold (7 – 99)  
5. Serum_Insulin (14 – 846)  
6. BMI (18.2 – 67.1)  
7. Diabetes_Pedigree (0.07 – 2.42)  
8. Age (21 – 81)  

**Target Variable:**  
- `Class` → 0 = No Diabetes, 1 = Diabetes  

---

## 🔄 Steps Implemented
1. Import libraries and dataset  
2. Explore dataset (info, statistics, top rows)  
3. Handle missing values using **Mean/Median imputation**  
4. Define features (**X**) and target (**y**)  
5. Split data into training (40%) and testing (60%) sets  
6. Select model: **Logistic Regression**  
7. Train model on training data  
8. Predict diabetes status on test data  
9. Evaluate model with **Classification Report**  

---

## 📈 Model Performance
- **Accuracy: ~74%**  
- Balanced performance across classes using Logistic Regression  

---

## 📂 How to Use
1. Open `diabetes_prediction.ipynb` in **Google Colab**  
2. Run all cells to see:  
   - Missing value analysis  
   - Data preprocessing  
   - Model training  
   - Predictions  
   - Evaluation results  

---

## 👨‍💻 Author
**Shailendra Singh**
