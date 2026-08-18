# Predictive Analytics for Academic Probation

> A machine learning project for identifying students at risk of academic probation using academic performance, attendance, previous failures, study behaviour, demographic, and other student-related attributes.

---

## 📌 Project Overview

Academic performance monitoring is an important task for educational institutions because early identification of academically struggling students can allow advisors to provide timely support.

This project develops a **machine learning-based academic probation prediction system** that classifies students into two categories:

- **Not At Risk**
- **At Risk**

The project follows a complete predictive analytics workflow, beginning with data cleaning and exploratory analysis and progressing through feature engineering, machine learning model development, hyperparameter tuning, model evaluation, feature importance analysis, probability-based risk analysis, and academic intervention recommendations.

Two classification approaches were investigated:

- **Decision Tree Classifier**
- **Support Vector Machine (SVM)**

After comparing the optimized models using multiple evaluation metrics, the **Optimized SVM** was selected as the final prediction model.

---

## 🎯 Problem Statement

Universities need to identify students who may be approaching academic probation before their academic performance deteriorates further.

The objective of this project is to develop a predictive classification system that can:

1. Analyze historical student academic and behavioural information.
2. Identify characteristics associated with academic probation.
3. Predict whether a student is at risk of academic probation.
4. Evaluate the predictive performance of different classification models.
5. Identify the major predictors contributing to academic risk.
6. Support academic advisors in planning appropriate interventions.

---

## 🎯 Project Objectives

The project addresses the following objectives:

- Perform data cleaning and preprocessing.
- Conduct exploratory data analysis (EDA).
- Understand academic characteristics of students entering probation.
- Engineer meaningful academic features.
- Develop Decision Tree and SVM classification models.
- Tune model hyperparameters.
- Evaluate models using suitable classification metrics.
- Analyze confusion matrices.
- Compare ROC curves and ROC-AUC scores.
- Identify major predictors of academic probation.
- Visualize academic probation patterns.
- Analyze predicted academic-risk probabilities.
- Recommend suitable academic interventions.

---

## 📊 Dataset

The project uses an academic student dataset containing attributes related to:

### Academic Performance
- G1 — first assessment grade
- G2 — second assessment grade
- G3 — final grade
- Previous academic failures
- Academic performance trends

### Attendance and Study Behaviour
- Absences
- Study time
- School support
- Extra educational support
- Free-time related attributes

### Student Characteristics
- Age
- Sex
- School
- Address
- Family size
- Family relationship information

### Family and Social Factors
- Parents' education
- Parents' occupation
- Family support
- Going-out frequency
- Other behavioural and social attributes

The dataset contains **395 student records**.

---

## 🔬 Methodology

The project follows the following predictive analytics pipeline:

```text
Academic Dataset
       ↓
Data Inspection
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Feature Engineering
       ↓
Academic Risk Target
       ↓
Train-Test Split
       ↓
Preprocessing & Encoding
       ↓
Decision Tree
       ↓
SVM
       ↓
Hyperparameter Tuning
       ↓
Model Evaluation
       ↓
Feature Importance
       ↓
ROC-AUC Analysis
       ↓
Risk Probability Analysis
       ↓
Final Model Selection
       ↓
Academic Intervention Recommendations
