#  Student Performance Prediction System Using Machine Learning

An end-to-end Machine Learning project that analyzes student academic and personal information and predicts a student's final Mathematics grade.

The project follows the complete Machine Learning workflow:

**Data → Cleaning → Analysis → Feature Preparation → Training → Testing → Evaluation → Prediction**

---

## Project Overview

Student academic performance can be influenced by several factors such as previous grades, absences, study time, family background, social activities, and other student-related attributes.

This project uses the **UCI Student Performance Dataset** to build a Machine Learning system capable of predicting the student's final grade (**G3**).

Two Machine Learning regression models were implemented and compared:

- Linear Regression
- Random Forest Regressor

The models were evaluated using:

- MAE
- RMSE
- R² Score

The **Random Forest Regressor** achieved the best performance on the test dataset.

---

##  Project Objectives

The main objectives of this project are:

- Understand and explore student performance data
- Perform data cleaning and quality checks
- Analyze important patterns using EDA
- Prepare numerical and categorical features
- Train multiple Machine Learning models
- Evaluate and compare model performance
- Identify important features
- Predict final student performance
- Document the complete Machine Learning workflow

---

## Dataset

### UCI Student Performance Dataset

Source:

https://archive.ics.uci.edu/dataset/320/student%2Bperformance

For this project, the **Mathematics dataset (`student-mat.csv`)** was used.

### Dataset Information

- Records: **395**
- Features/Columns: **33**
- Target variable: **G3**
- Missing values: **0**
- Duplicate rows: **0**

### Target Variable

`G3` represents the student's final Mathematics grade.

The final grade ranges from **0 to 20**.

---

##  Important Features

The dataset contains academic, demographic, family, social, and lifestyle-related information.

Some important features include:

| Feature | Description |
|---|---|
| `age` | Student age |
| `sex` | Student gender |
| `studytime` | Weekly study time |
| `failures` | Number of previous failures |
| `absences` | Number of school absences |
| `Medu` | Mother's education |
| `Fedu` | Father's education |
| `famrel` | Family relationship quality |
| `goout` | Going out frequency |
| `Dalc` | Workday alcohol consumption |
| `Walc` | Weekend alcohol consumption |
| `health` | Current health status |
| `G1` | First-period grade |
| `G2` | Second-period grade |
| `G3` | Final grade / target |

---

# 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Preparation
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Testing
   ↓
Model Evaluation
   ↓
Model Comparison
   ↓
Feature Importance
   ↓
Final Prediction
