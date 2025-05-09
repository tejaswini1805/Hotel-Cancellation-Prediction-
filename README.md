App Link - https://innhotel-kupxpaoz6rx3p6rw7sm2jj.streamlit.app/

Hotel Cancellation Prediction
This project focuses on predicting hotel booking cancellations using machine learning. The aim is to analyze booking data, preprocess it, build a predictive model, and deploy the model to predict cancellation probabilities.

Key Objectives
Analyze booking data to uncover patterns and insights.
Build and evaluate machine learning models to predict cancellations.
Deploy the best-performing model with a user-friendly interface.
Features of the Project
Detailed data analysis and preprocessing steps.
Multiple classification models evaluated for optimal performance.
A Gradio-based interface for real-time predictions.
Project Workflow
1. Exploratory Data Analysis (EDA)
Visualization:
Analyze booking patterns, cancellation rates, and feature correlations using Matplotlib.
Outlier Detection:
Use box plots and statistical methods to identify and handle outliers.
Handling Missing Data:
Drop columns with excessive null values.
Impute missing values using appropriate techniques.
2. Inferential Statistics
Perform statistical tests like the Mann-Whitney U Test to examine relationships between variables and cancellations.
3. Feature Engineering
Create new features to enhance model performance.
Encode categorical variables and normalize numerical attributes.
4. Predictive Modeling
Train and evaluate the following models:
Logistic Regression
Decision Trees
Random Forest
XGBoost (best-performing model)
AdaBoost
Naive Bayes
Gradient Boosting
Compare models based on metrics like accuracy, precision, recall, and F1-score.
5. Model Tuning
Fine-tune the XGBoost model using hyperparameter optimization.
The model achieved an accuracy of 80% on the test data.
Save the final model using Pickle for deployment.
6. Deployment
Develop a simple and interactive interface using Gradio.
Allow users to input booking details and get real-time predictions on cancellation likelihood.
Requirements
Programming Language: Python 3.7 or higher
Libraries:
Pandas
Scikit-learn
Matplotlib
Gradio
Pickle
Environment: Jupyter Notebook
Results
The XGBoost model emerged as the best-performing model with an accuracy of 80%.
A user-friendly Gradio interface allows real-time predictions, making the model practical for deployment in the hospitality industry.
About
The Hotel Booking Cancellation Prediction Model predicts cancellations using factors like lead time, room type, customer segment, and past cancellations. It aids hotels in managing overbooking, enhancing customer retention, and optimizing revenue. This project includes code, datasets, and analysis for a comprehensive solution.

Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 1 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Languages
Jupyter Notebook
99.8%
 
Python
0.2%
Footer
© 2025 GitHub, Inc.
Footer navigation
Terms
