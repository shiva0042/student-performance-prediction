# 🧠 Student Performance Analysis and Prediction

This project is a Data Science case study using the UCI Student Performance dataset. It focuses on understanding what factors influence student performance and building a machine learning model to predict whether a student will pass or fail.

---

## 📊 Features of the Project

- Exploratory Data Analysis (EDA)
- Grade distribution visualization
- Feature Engineering (e.g., combining grades, encoding gender)
- Pass/Fail classification based on final grade
- Model building using Logistic Regression
- Accuracy, classification report, and confusion matrix
- Streamlit-based interactive web app (optional)

---

## 📁 Dataset

Dataset used:
- `student-mat.csv` (from UCI Machine Learning Repository)

Download from [UCI Student Dataset](https://archive.ics.uci.edu/ml/datasets/Student+Performance)

---

## 🔧 How to Run
pandas
numpy
matplotlib
seaborn
scikit-learn

pip install pandas numpy matplotlib seaborn scikit-learn

### 1. Clone the repo:

```bash
git clone https://github.com/YOUR_USERNAME/student-performance-prediction.git
cd student-performance-prediction
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

pip install -r requirements.txt
jupyter notebook student_performance_analysis.ipynb
