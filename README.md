# 🩺 Health Metrics Glucose Prediction

## 📌 Project Overview

This project analyzes cardiovascular health data and develops machine learning models to predict blood glucose levels using patient health indicators.

The workflow includes data cleaning, missing value handling, exploratory data analysis (EDA), feature engineering, regression modeling, and model evaluation.

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 📊 Dataset Features

The dataset contains cardiovascular and lifestyle information including:

* Age
* Gender
* Education Level
* Smoking Status
* Cigarettes Per Day
* Blood Pressure Medication
* Total Cholesterol
* BMI
* Heart Rate
* Systolic Blood Pressure
* Diastolic Blood Pressure
* Diabetes Status
* Glucose Level

---

## 🧹 Data Preprocessing

Data preparation steps:

* Missing value detection
* Median imputation for numerical variables
* Most-frequent imputation for categorical variables
* Smoking-based imputation for cigarette consumption
* Feature-target separation
* Train-test split

---

## 📈 Exploratory Data Analysis

Visualizations include:

* Correlation Heatmap
* Glucose Distribution Histogram
* BMI vs Glucose Scatter Plot
* Glucose by Gender Boxplot

### Key Findings

* BMI shows a positive relationship with glucose levels.
* Several cardiovascular indicators correlate with glucose.
* Glucose distribution contains a small number of extreme values.

---

## 🤖 Machine Learning Models

### Linear Regression

Used as a baseline model to predict glucose levels.

### Decision Tree Regressor

Captures non-linear relationships between health indicators and glucose measurements.

---

## 📊 Model Evaluation

Models were evaluated using:

* Mean Squared Error (MSE)
* R² Score

Performance comparisons were used to determine the most effective regression approach.

---

## 🚀 How to Run

```bash
git clone https://github.com/beepbopskeet/Health-Metrics-Glucose-Prediction.git

cd health-metrics-glucose-prediction

pip install -r requirements.txt

jupyter notebook
```

---

## 🎯 Future Improvements

* Random Forest Regression
* XGBoost Regression
* Hyperparameter Optimization
* Cross Validation
* Healthcare Prediction Dashboard
* Feature Importance Analysis
