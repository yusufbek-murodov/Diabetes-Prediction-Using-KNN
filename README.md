# Diabetes Prediction using K-Nearest Neighbors (KNN)

## 📌 Project Overview
This project implements a **K-Nearest Neighbors (KNN)** classifier to predict whether a patient has diabetes based on various health indicators. The dataset used is the **Pima Indians Diabetes Dataset**, which contains medical measurements for female patients.

## 📊 Dataset Information
- **Source**: Pima Indians Diabetes Database
- **Number of Instances**: 768
- **Features**:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI (Body Mass Index)
  - Diabetes Pedigree Function
  - Age
- **Target Variable**: Outcome (0 = No Diabetes, 1 = Diabetes)

## 🏗️ Project Workflow
1. **Exploratory Data Analysis (EDA)**:
   - Visualized feature distributions and correlations
   - Identified missing or zero values in certain features
2. **Data Preprocessing**:
   - Replaced zero values in relevant columns with the median
   - Normalized numerical features using StandardScaler
   - Split dataset into training and test sets (80%-20%)
3. **Model Training**:
   - Implemented KNN classifier with `k=8` (optimized using cross-validation)
   - Used `train_test_split` for model validation
4. **Evaluation**:
   - Measured accuracy, precision, recall, and F1-score
   - Generated confusion matrix and ROC curve
5. **Prediction**:
   - Allowed inputting new patient data for diabetes prediction

## 🚀 Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - Pandas, NumPy (Data Processing)
  - Scikit-Learn (Machine Learning)
  - Matplotlib, Seaborn (Data Visualization)

## 📈 Results
- **Model Accuracy**: 75%
- **Best `k` Value**: 8
- **Confusion Matrix**:
  - True Positives (TP), True Negatives (TN), False Positives (FP), False Negatives (FN) analyzed

---
### **Author:** Yusufbek Murodov  
**GitHub**: [yusufbek-murodov](https://github.com/yusufbek-murodov)  
**LinkedIn**: [Yusufbek Murodov](https://www.linkedin.com/in/yusufbek-murodov-b16103266/)  

---
