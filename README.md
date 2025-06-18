# 🩺 Diabetes Prediction using Machine Learning

This project uses the **PIMA Indian Diabetes Dataset** to build predictive models that classify whether a patient is diabetic or not using **Logistic Regression** and **Support Vector Machine (SVM)**.

---

## 📊 Features Used
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

---

## 🔧 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 📌 Key Highlights
- Data preprocessing (feature scaling, train-test split)
- Exploratory Data Analysis (EDA)
- Trained two models: Logistic Regression & SVM
- Model evaluation using Accuracy, Confusion Matrix, Classification Report
- Comparison plot of both models
- Prediction demo for new input values

---

## 📁 Files Included
- `Diabetes_merged.py`: Main code
- `Dia_merged.ipynb`: Notebook version
- `diabetes.csv`: Dataset (from Kaggle)

---

## 📈 Sample Output
After training the models on the PIMA Indian Diabetes dataset, here are the evaluation metrics and prediction results:

### Logistic Regression
Accuracy: 0.77
Confusion Matrix:
[[89 11]
[26 28]]
Classification Report:
precision recall f1-score support
0 0.77 0.89 0.83 100
1 0.72 0.52 0.60 54

yaml
Copy
Edit

---

### SVM (Support Vector Machine)
Accuracy: 0.78
Confusion Matrix:
[[91 9]
[26 28]]
Classification Report:
precision recall f1-score support
0 0.78 0.91 0.84 100
1 0.76 0.52 0.62 54

yaml
Copy
Edit

---

### 🔍 Prediction for New Input
Input: `(5, 166, 72, 19, 175, 25.8, 0.587, 51)`
Logistic Regression ➤ Prediction: Diabetic, Risk: 83.57%
SVM ➤ Prediction: Diabetic, Risk: 87.93%

less
Copy
Edit

---

## 🔗 Dataset Source
[Kaggle: PIMA Indian Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
