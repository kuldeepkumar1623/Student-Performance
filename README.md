# 🎓 Student Performance Prediction using Machine Learning

## 📌 Overview

This project focuses on predicting student academic performance using various machine learning algorithms. The goal is to classify whether a student will pass or fail based on academic, social, and personal attributes.

The project demonstrates the complete machine learning pipeline, including data preprocessing, feature engineering, model training, and performance evaluation.

---

## 🎯 Objectives

* To analyze student performance data
* To apply multiple machine learning algorithms
* To compare model performance and accuracy
* To identify key factors affecting student success

---

## 📂 Dataset

The dataset used is the **Student Performance Dataset** (UCI/Kaggle version), which contains student-related attributes such as:

* Academic records (G1, G2, G3)
* Demographic information (age, gender)
* Social factors (family support, internet access)
* Study habits (study time, failures, absences)

Target variable:

* Final grade (**G3**) converted into a binary classification:

  * Pass (1)
  * Fail (0)

---

## ⚙️ Machine Learning Models Used

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)

---

## 🔧 Project Workflow

1. Data Loading and Exploration
2. Data Preprocessing (handling categorical data using encoding)
3. Feature Engineering (creating pass/fail target)
4. Feature Scaling (StandardScaler)
5. Model Training
6. Model Evaluation and Comparison

---

## 📊 Performance Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 📈 Results

Random Forest achieved the highest accuracy among all models, followed by SVM and Logistic Regression. KNN performance depended heavily on feature scaling, while Decision Tree showed moderate accuracy with risk of overfitting.

---

## 🧠 Key Insights

* Previous grades (G1, G2) strongly influence final performance
* Feature scaling improves distance-based models like KNN and SVM
* Ensemble methods like Random Forest provide better generalization

---

## 🚀 Future Improvements

* Hyperparameter tuning using GridSearchCV
* Cross-validation for better evaluation
* Adding more real-world datasets
* Deployment using Streamlit or Flask

---

## 🛠️ Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib

---

## 📎 Conclusion

This project highlights the effectiveness of machine learning techniques in predicting student performance and provides a comparative analysis of different classification algorithms.

---

## 👨‍💻 Author

Kuldeep Kumar
