# 🩺 Diabetes Prediction using Age & Blood Pressure (ML Mini Project)

This is a beginner-friendly Machine Learning project to predict whether a patient is likely to have diabetes based on just **Age** and **Blood Pressure**. The prediction is done using two ML models: **Logistic Regression** and **Decision Tree**.

---

## 📌 Project Features

- Takes user input (Age & Blood Pressure)
- Predicts diabetes likelihood using two ML models
- Prints clear output: whether the patient is likely to have diabetes or not
- Trained on real-world data (PIMA Diabetes dataset)

---

## 📊 Dataset

- **Source**: [PIMA Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Used Features**:  
  - `Age`  
  - `BloodPressure`
- **Target Column**:  
  - `Outcome` (1 = Diabetic, 0 = Not Diabetic)

---

## 🧠 Technologies Used

- Python  
- pandas, numpy – Data handling  
- scikit-learn – Model training, prediction, scaling  
- Logistic Regression and Decision Tree algorithms

---

## 🔁 Project Workflow

1. Load and clean the dataset  
2. Select only 2 features: `Age`, `BloodPressure`  
3. Replace missing/zero BP values with column mean  
4. Split data into training and test sets  
5. Apply **StandardScaler** for feature scaling  
6. Train **Logistic Regression** and **Decision Tree** models  
7. Take user input and predict outcome  
8. Show prediction result in friendly language

---

## ▶️ How to Run the Code

1. Clone or download the project folder  
2. Make sure you have the required libraries:
```bash
pip install pandas numpy scikit-learn
python diabetes_predict.py
