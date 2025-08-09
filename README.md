# ML-Based-Stroke-Risk-Prediction
A machine learning project that predicts the presence of heart disease using the UCI Heart Disease Dataset. Built with Python, Pandas, NumPy, and Scikit-learn, featuring Logistic Regression for accurate early diagnosis support.

# 🫀 Heart Disease Prediction Model

## 📌 Overview
This project develops a **predictive machine learning model** to determine the presence of heart disease in patients based on various medical attributes.  
Using the **UCI Heart Disease Dataset**, the model helps in **early diagnosis** and can support healthcare professionals in making timely intervention decisions.

---

## 📂 Dataset
- **Source:** [UCI Machine Learning Repository - Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)  
- **Attributes:**  
  - Age, Sex, Chest Pain Type, Resting Blood Pressure, Serum Cholesterol, Fasting Blood Sugar, Resting ECG Results, Maximum Heart Rate, Exercise-Induced Angina, ST Depression, Slope, Number of Major Vessels, Thalassemia.
- **Target:**  
  - `0` → No Heart Disease  
  - `1` → Presence of Heart Disease  

---

## 🛠️ Technologies Used
- **Python**
- **Libraries:**
  - `NumPy` → Numerical operations
  - `Pandas` → Data manipulation
  - `Matplotlib` & `Seaborn` → Data visualization
  - `scikit-learn` → Model building & evaluation
- **Environment:** Jupyter Notebook

---

## ⚙️ Project Workflow
1. **Data Loading & Exploration**
   - Load dataset from UCI Repository
   - Check missing values and data distributions
2. **Data Preprocessing**
   - Handle missing values
   - Encode categorical features
   - Normalize numerical features
3. **Model Building**
   - Implemented **Logistic Regression** for classification
4. **Model Evaluation**
   - Train-Test Split (80%-20%)
   - Accuracy, Precision, Recall, and F1-score used as metrics
5. **Prediction**
   - Predicts heart disease presence for given patient data

---

## 📊 Results
- **Algorithm:** Logistic Regression  
- **Accuracy:** ~85%  
- **Findings:** Model provides balanced precision and recall, making it suitable for early screening.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/heart-disease-prediction.git
   cd heart-disease-prediction
