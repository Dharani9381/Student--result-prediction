Student Result Prediction System
Abstract
The Student Result Prediction System is a Machine Learning web application built entirely in Python using Streamlit as the front-end framework. It predicts whether a student will PASS or FAIL based on five key academic and lifestyle parameters: study hours per day, class attendance percentage, previous exam marks, number of assignments completed, and average sleep hours. A Logistic Regression classifier is trained on a synthetic dataset of 500 student records and delivers real-time predictions with probability confidence scores. The application is divided into three interactive tabs: Prediction, Data Analysis, and Model Performance, demonstrating the complete Data Science workflow from data generation to deployment. �
Student_Result_Prediction_DPR_Vasanthi.pdf
Objectives
Design and build a Machine Learning web application using Python.
Implement a Logistic Regression binary classifier with proper train/test split and feature scaling.
Predict PASS/FAIL results with confidence percentage.
Display interactive data visualizations in Streamlit.
Show model evaluation metrics such as Accuracy, Precision, Recall, F1 Score, and Confusion Matrix.
Demonstrate the complete Machine Learning lifecycle from data generation to deployment.
Create a reusable and extensible project for future improvements. �
Student_Result_Prediction_DPR_Vasanthi.pdf
Problem Statement
Educational institutions need an efficient way to identify students who are at risk of failing. Manual evaluation is time-consuming and may not be accurate. This project uses Machine Learning to analyze multiple student-related factors and predict whether a student is likely to PASS or FAIL, allowing timely intervention and better academic planning. �
Student_Result_Prediction_DPR_Vasanthi.pdf
Tools and Technologies
Python 3.10+
Streamlit
Scikit-learn
Pandas
NumPy
Matplotlib
Seaborn �
Student_Result_Prediction_DPR_Vasanthi.pdf
Dataset Description
The project uses a synthetic dataset containing 500 student records generated using NumPy. The dataset includes:
Hours_Study (1–12)
Attendance (40–100%)
Previous_Marks (30–100)
Assignments_Done (0–10)
Sleep_Hours (4–10)
Result (0 = FAIL, 1 = PASS) �
Student_Result_Prediction_DPR_Vasanthi.pdf
System Architecture
Data Generation
Data Pre-processing
Model Training
Prediction
Confidence Score Calculation
Data Visualization
Web User Interface �
Student_Result_Prediction_DPR_Vasanthi.pdf
Machine Learning Model
The project uses the Logistic Regression algorithm for binary classification. It predicts the probability of a student passing based on the input features. Logistic Regression is simple, fast, interpretable, and suitable for small structured datasets. The model uses an 80/20 train-test split with feature scaling using StandardScaler before training. �
Student_Result_Prediction_DPR_Vasanthi.pdf
Prediction with Confidence Score
The user's input values are first normalized using the trained StandardScaler. The Logistic Regression model predicts PASS or FAIL and calculates the prediction confidence using the predict_proba() method. The confidence value is displayed as a percentage. �
Student_Result_Prediction_DPR_Vasanthi.pdf
Application Features
Tab 1 – Predict Result
Input sliders for study hours, attendance, previous marks, assignments completed, and sleep hours.
Predict PASS or FAIL.
Display confidence percentage.
Show input summary.
Tab 2 – Data Analysis
Study Hours vs Marks scatter plot.
Attendance vs Marks scatter plot.
PASS/FAIL pie chart.
Marks distribution histogram.
Tab 3 – Model Performance
Accuracy, Precision, Recall, and F1 Score.
Confusion Matrix heatmap.
Feature Importance chart.
Explanation of performance metrics. �
Student_Result_Prediction_DPR_Vasanthi.pdf
Model Performance
The project evaluates the trained model using:
Accuracy
Precision
Recall
F1 Score
Confusion Matrix
The model achieves approximately:
Accuracy: 88–93%
Precision: 87–92%
Recall: 90–95%
F1 Score: 88–93% �
Student_Result_Prediction_DPR_Vasanthi.pdf
Future Scope
Integrate a real database such as MySQL or PostgreSQL.
Compare multiple Machine Learning models.
Deploy the application on Streamlit Cloud.
Implement role-based login.
Add email/SMS alerts for at-risk students.
Generate downloadable PDF reports.
Upgrade to Deep Learning models. �
Student_Result_Prediction_DPR_Vasanthi.pdf
Conclusion
The Student Result Prediction System demonstrates the complete Machine Learning workflow from synthetic data generation to deployment as a Streamlit web application. It uses Python libraries such as Streamlit, Scikit-learn, Pandas, NumPy, Matplotlib, and Seaborn to build an interactive prediction system. The project achieves good prediction accuracy and serves as a strong foundation for future enhancements such as real-time databases, cloud deployment, and advanced Machine Learning models. �
Student_Result_Prediction_DPR_Vasanthi.pdf# Student--result-prediction
Machine Learning-based Student Result Prediction System using Python and Flask to predict student performance based on academic and personal factors with an interactive web interface.
