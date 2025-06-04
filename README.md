# Analysis-of-factors-affecting-heart-disease-with-Python
# 🫀 Analysis of Factors Affecting Heart Disease with Python

This project performs an Exploratory Data Analysis (EDA) on a heart disease dataset obtained from OpenML.  
The main objective is to analyze various clinical features and visualize their distribution and patterns, which may help in understanding key indicators related to heart disease.

---

## 📁 Project Overview

- Dataset Source: [Heart Disease Dataset (OpenML ID: 43672)](https://www.openml.org/d/43672)
- Programming Language: Python 3.x
- Libraries Used:
  - pandas
  - numpy
  - matplotlib
  - sklearn.datasets (for data fetching)

---

## 📊 Features Analyzed

The following clinical features were analyzed:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure (resting_bp_s)
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Induced Angina
- ST Depression (oldpeak)
- ST Slope

---

## 🧪 Techniques Used

- Descriptive Statistics:
  - Mean, Minimum, Maximum
- Visualizations:
  - Boxplots (for detecting outliers)
  - Violin plots (for distribution shapes)
  - Histograms (for frequency)
  - Pie charts (for categorical feature proportions)

---

## 📌 Summary of Findings

- Age:
  - Mean age is around mid-50s.
  - Most patients are aged between 40 and 60.
  - Graphs showed a relatively symmetric distribution.

- Sex:
  - Majority of patients are male (~65%).
  - Pie chart clearly illustrates this gender imbalance.

- Chest Pain Type:
  - The most frequent type was Asymptomatic, followed by Non-anginal Pain.
  - Typical and Atypical Angina types were less common.

- Resting Blood Pressure:
  - Ranged from very low (~90) to high values (over 200).
  - Boxplot showed presence of high-value outliers.

- Cholesterol:
  - Some patients had very high cholesterol (>500).
  - Distribution was right-skewed (long tail to the right).

- Fasting Blood Sugar:
  - Most people had blood sugar <120 mg/dL.
  - Only a small percentage had elevated fasting blood sugar.

- Resting ECG Results:
  - Majority had normal ECG.
  - A smaller group showed signs of left ventricular hypertrophy.

- Maximum Heart Rate:
  - Mean around 150 bpm.
  - Wide spread from low (70) to high (200+).
  - Right-skewed distribution with few outliers.

- Exercise Induced Angina:
  - Most patients did not experience angina during exercise.

- ST Depression (Oldpeak):
  - Most values were near zero.
  - A few high values caused positive skew.

- ST Slope:
  - Flat slope was most common.
  - Fewer patients had upsloping or downsloping ST segments.

---

## ▶️ How to Run

1. Make sure Python 3 and the required libraries are installed:
`bash
pip install numpy pandas matplotlib scikit-learn
