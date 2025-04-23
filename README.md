# Diabetes-Prediction-and-Risk-Factor-Analysis-using-Python

This project focuses on predicting diabetes and analyzing key health, lifestyle, and genetic factors contributing to the disease. Using a real-world dataset, it combines data preprocessing, exploratory analysis, machine learning classification, clustering, and regression techniques to derive actionable healthcare insights.

---

## 📌 Objectives

1. **Predict Diabetes Outcome** using supervised learning models.
2. **Analyze Feature Importance** to identify major contributing health indicators.
3. **Segment Patients** using clustering to discover similar risk profiles.
4. **Study Lifestyle & Genetic Risk Factors** (e.g., smoking, physical activity, family history).
5. **Predict HbA1c Levels** using regression to model glucose control.

---

## 📂 Dataset Overview

The dataset includes:
- Clinical indicators: `HbA1c`, `Fasting_Blood_Glucose`, `BMI`, `Age`
- Demographics: `Sex`, `Ethnicity`
- Lifestyle data: `Smoking_Status`, `Physical_Activity_Level`
- Genetic info: `Family_History_of_Diabetes`

Target variable `Diabetes_Outcome` is engineered based on clinical thresholds.

---

## 🧰 Technologies Used

- **Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Models**: Random Forest, Logistic Regression, KMeans, Linear Regression  

---

## 📊 Key Results

- ✅ **Classification Accuracy**: 89%, Precision: 0.87, Recall: 0.91  
- 📉 **Regression R² Score**: 0.81 (for HbA1c prediction)  
- 📌 **Top Features**: `HbA1c`, `Fasting Glucose`, `BMI`, `Age`, `Family History`  
- 🧬 **Lifestyle Insights**: Smoking and low physical activity linked with higher risk  
- 🧠 **Clustering**: 3 patient groups discovered with distinct risk patterns

---

## 📈 Exploratory Data Analysis

EDA was performed to explore distributions, correlations, and outliers using:
- Histograms, boxplots, violin plots
- Correlation heatmaps
- Grouped bar plots and crosstabs for categorical comparisons

---

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/diabetes-prediction-project.git
   cd diabetes-prediction-project
