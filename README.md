App Link - https://innhotel-kupxpaoz6rx3p6rw7sm2jj.streamlit.app/

Hotel Booking Cancellation Prediction 🏨🔮
This project focuses on predicting hotel booking cancellations using machine learning. The goal is to analyze booking data, preprocess it, build predictive models, and deploy the best model to predict cancellation probabilities in real time.

🔥 Key Objectives
Analyze booking data to uncover patterns and insights.

Build and evaluate machine learning models to predict cancellations.

Deploy the best-performing model with a user-friendly Streamlit interface.

🚩 Features of the Project
Detailed data analysis and preprocessing steps.

Multiple classification models evaluated for optimal performance.

A Streamlit-based interactive interface for real-time predictions.

📊 Project Workflow
1. Exploratory Data Analysis (EDA)
Visualization:
Analyzed booking patterns, cancellation rates, and feature correlations using Matplotlib.

Outlier Detection:
Used box plots and statistical methods to identify and handle outliers.

Handling Missing Data:

Dropped columns with excessive null values.

Imputed missing values using appropriate techniques.

2. Inferential Statistics
Performed statistical tests (e.g., Mann-Whitney U Test) to examine relationships between variables and cancellations.

3. Feature Engineering
Created new features to enhance model performance.

Encoded categorical variables and normalized numerical attributes.

4. Predictive Modeling
Trained and evaluated the following models:

Logistic Regression

Decision Trees

Random Forest

XGBoost (Best-Performing Model 🚀)

AdaBoost

Naive Bayes

Gradient Boosting

Compared models using:

Accuracy

Precision

Recall

F1-score

5. Model Tuning
Fine-tuned the XGBoost model using hyperparameter optimization.

Achieved an accuracy of 80% on the test data.

Saved the final model using Pickle for deployment.

6. Deployment
Developed an interactive interface using Streamlit.

Allows users to input booking details and get real-time predictions on cancellation likelihood.

🛠 Requirements

Libraries:

pandas

scikit-learn

matplotlib

xgboost

streamlit

pickle

Environment:
Jupyter Notebook, Streamlit App

✅ Results
The XGBoost model emerged as the best-performing model with an accuracy of 80%.

A user-friendly Streamlit interface enables real-time predictions, making the model practical for deployment in the hospitality industry.



