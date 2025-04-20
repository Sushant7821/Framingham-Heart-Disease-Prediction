# Framingham-Heart-Disease-Prediction
Logistic Regression model to predict heart disease using the Framingham Study dataset
# 🫀 Predicting Heart Disease Risk with Logistic Regression

This project applies logistic regression on the **Framingham Heart Study dataset** to predict the 10-year risk of coronary heart disease (CHD). The goal is to build a predictive model and understand key risk factors using interpretable machine learning techniques.

---

## 📂 Dataset

The dataset used is the **Framingham Heart Study dataset**, which contains medical and demographic information for over 4,000 patients, including:

- Age, gender, education
- Smoking, alcohol intake
- Blood pressure, cholesterol
- Diabetes, heart rate
- Target column: `TenYearCHD` (0 = No CHD, 1 = CHD within 10 years)

---

## 🔍 Project Steps

1. **Import Libraries**
2. **Load and Explore Dataset**
3. **Handle Missing Values**
4. **Feature Selection**
5. **Data Standardization** (using `StandardScaler`)
6. **Train-Test Split**
7. **Model Training** (Logistic Regression with `class_weight='balanced'`)
8. **Model Evaluation**  
    - Confusion Matrix  
    - Accuracy, Precision, Recall  
    - Classification Report
9. **Feature Importance** (Log Odds)

---

## ⚙️ Tools Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 📊 Model Performance

- **Accuracy:** ~66%
- **Recall (CHD):** ~63%
- **Precision (CHD):** ~28%

> ⚠️ In healthcare, recall is often more important than precision, as it's critical to identify as many true CHD cases as possible.

---

## ✅ Future Improvements

- Try advanced models like Random Forest, XGBoost
- Use cross-validation for better generalization
- Feature engineering and VIF analysis to reduce multicollinearity

---

## 📁 Project Notebook

The full notebook is available in `Framingham_Logistic_Regression.ipynb`.

---

## 🤝 Connect with Me

Feel free to connect on [LinkedIn](https://www.linkedin.com) to discuss data science, machine learning, and more!
