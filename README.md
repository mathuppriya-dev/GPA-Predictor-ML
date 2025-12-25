# 🎓 GPA / Final Grade Prediction using Machine Learning

This project predicts students’ final exam grades (G3) using academic, behavioral,
and family-related features from the UCI Student Performance Dataset.

---

## 📌 Dataset
- Source: UCI Machine Learning Repository
- Records: 1044 students
- Features: 33

---

## 🔍 Exploratory Data Analysis
- Pairplots
- Correlation heatmap
- Grade distributions

<img src="images/pairplot.png" width="700">

---

## 🤖 Models Used
- Linear Regression
- Random Forest
- XGBoost (Best Model)

---

## 📊 Model Performance

| Model | RMSE | R² |
|------|------|----|
| Linear Regression | 1.78 | 0.79 |
| Random Forest | 1.70 | 0.81 |
| XGBoost ⭐ | 1.68 | 0.816 |

---

## 🔑 Key Insights
- G1 and G2 strongly influence final grades
- Absences and study time impact performance
- XGBoost achieved the best results

---

## 🛠 Tools
Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn

---

## 👤 Author
Mathuppriya Naguleswaran
