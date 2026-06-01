# PRODIGY_DS_02

# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the famous Titanic dataset from Kaggle. The objective is to analyze passenger data, clean the dataset, visualize important patterns, and identify factors that influenced survival during the Titanic disaster.

The project demonstrates key Data Analytics skills including:

- Data Cleaning
- Missing Value Handling
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Correlation Analysis
- Insight Generation

---

## 🎯 Objective

The primary objective of this project is to:

- Understand the structure of the Titanic dataset.
- Perform data cleaning and preprocessing.
- Analyze survival patterns among passengers.
- Explore relationships between different variables.
- Generate meaningful insights using visualizations.

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📊 Exploratory Data Analysis Performed

### 1. Data Inspection

- Dataset shape
- Data types
- Statistical summary
- Missing value analysis

### 2. Data Cleaning

- Filled missing values in Age column using Median.
- Filled missing values in Embarked column using Mode.
- Removed Cabin column due to excessive missing values.
- Checked and removed duplicate records.

### 3. Univariate Analysis

Visualizations created:

- Survival Distribution
- Gender Distribution
- Passenger Class Distribution
- Age Distribution
- Fare Distribution

### 4. Bivariate Analysis

Relationships explored:

- Survival vs Gender
- Survival vs Passenger Class
- Survival vs Age
- Survival vs Embarked
- Fare vs Survival

### 5. Feature Engineering

Created:

- FamilySize Feature

Formula:

FamilySize = SibSp + Parch + 1

### 6. Correlation Analysis

Generated a correlation heatmap to identify relationships between numerical features.

---

## 📈 Key Insights

### Insight 1

Female passengers had significantly higher survival rates than male passengers.

### Insight 2

Passengers traveling in First Class had the highest survival probability.

### Insight 3

Passengers who paid higher fares were more likely to survive.

### Insight 4

Most passengers were between 20 and 40 years old.

### Insight 5

Passenger Class showed a strong relationship with survival.

### Insight 6

Small family groups had slightly better survival chances.

---
