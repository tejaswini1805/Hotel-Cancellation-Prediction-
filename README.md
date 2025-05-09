App Link - https://innhotel-kupxpaoz6rx3p6rw7sm2jj.streamlit.app/

# 🏨 Hotel Booking Cancellation Prediction

This project predicts hotel booking cancellations using **machine learning**. The goal is to analyze booking data, build predictive models, and deploy the best-performing model for real-time cancellation predictions.

---

## 🎯 Key Objectives

- Analyze booking data to uncover patterns and insights.
- Build and evaluate ML models to predict cancellations.
- Deploy the model with a user-friendly **Streamlit** interface.

---

## 🚀 Features

- Detailed **EDA** and data preprocessing steps.
- Multiple classification models compared.
- Deployed using **Streamlit** for real-time prediction.

---

## 📝 Project Workflow

### 1. Exploratory Data Analysis (EDA)
- **Visualization:** Analyzed booking patterns, cancellation rates, and correlations using Matplotlib.
- **Outlier Detection:** Identified and handled outliers using box plots and statistical methods.
- **Missing Data Handling:**
  - Dropped columns with excessive null values.
  - Imputed missing values appropriately.

### 2. Inferential Statistics
- Performed statistical tests (e.g., **Mann-Whitney U Test**) to find relationships between variables and cancellations.

### 3. Feature Engineering
- Created new features to boost model performance.
- Encoded categorical variables and normalized numerical features.

### 4. Predictive Modeling
Trained and evaluated multiple models:
- Logistic Regression
- Decision Tree
- Random Forest
- **XGBoost** ✅ (Best Model)
- AdaBoost
- Naive Bayes
- Gradient Boosting

**Metrics Used:**
- Accuracy
- Precision
- Recall
- F1-score

### 5. Model Tuning
- Fine-tuned the **XGBoost** model with hyperparameter optimization.
- Achieved **80% accuracy** on test data.
- Saved the final model using **Pickle**.

### 6. Deployment
- Built an interactive app using **Streamlit**.
- Users can input booking details and get real-time cancellation predictions.

---

## 🛠 Requirements

- Python 3.7+
- Libraries:
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `xgboost`
  - `streamlit`
  - `pickle`

---

## ✅ Results

- **XGBoost** achieved **80%** accuracy, making it the best-performing model.
- A simple and user-friendly **Streamlit interface** for real-world use in the hospitality sector.

---







