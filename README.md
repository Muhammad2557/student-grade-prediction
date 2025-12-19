# 🎓 Student Grade Prediction Using Machine Learning

This project uses supervised machine learning to predict students’ final grades based on academic, demographic, and behavioral features. The goal is to build a realistic and interpretable model rather than maximizing accuracy alone.

---

## 📊 Dataset
The dataset contains information about students, including:
- Demographic data (age, gender, family background)
- Academic factors (study time, failures, absences)
- Previous grades (G1, G2)

The target variable is the final grade (**G3**).

---

## 🧠 Methodology
- Data preprocessing using **pandas**
- Categorical feature encoding via **one-hot encoding**
- Train–test split (80/20)
- Model: **Random Forest Regressor**
- Evaluation metrics: **Mean Absolute Error (MAE)** and **R² score**

---

## 📈 Results
The model demonstrates reasonable predictive performance:

- **MAE:** ~3  
- **R² score:** ~0.27–0.81 (depending on feature selection)

A scatter plot of predicted vs. actual grades is used for evaluation.

---

## 🔍 Discussion & Limitations
- Including previous grades significantly improves accuracy but may reduce real-world applicability.
- The dataset size is limited and specific to one region.
- The model is intended for educational and exploratory purposes.

---

## 🛠 Tools & Libraries
- Python
- pandas
- scikit-learn
- matplotlib

---

## 🚀 How to Run
1. Clone the repository
2. Install dependencies
3. Run the Jupyter notebook

---

## 👤 Author
**Muhammad**
