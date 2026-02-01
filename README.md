- Name: Sahil Balkrushna Gadge
- Company: CODETECH IT SOLUTIONS PVT. LTD
- ID: CT12DR1813
- Domain: Data Analytics
- Duration: November 15th 2025 to February 15th 2026
- Mentor: Neela Santhosh Kumar

Task 2: Machine Learning Model for Outcome Prediction
Project Overview
This project demonstrates the development of a Machine Learning classification model to predict outcomes based on a dataset.
The objective is to showcase the complete ML workflow including data generation, preprocessing, feature selection, model training, and evaluation using Python.
The model predicts whether a student will pass or fail based on academic and behavioral factors.

Objective
To build a classification model that predicts student performance (Pass / Fail) using machine learning techniques.

Dataset
The dataset is synthetically generated using NumPy to simulate real-world student data.

Features
study_hours – Number of hours studied
attendance – Attendance percentage
previous_score – Previous exam score
assignments_completed – Number of assignments completed

Target Variable
pass
1 → Pass
0 → Fail
The target variable is created using logical conditions based on study hours and attendance.

Tools & Technologies Used
Python 3
Jupyter Notebook
NumPy
Pandas
Scikit-learn

Steps Performed

Data Generation
Generated 200 records using NumPy
Converted data into a Pandas DataFrame

Data Preprocessing
Separated features and target variable
Applied Min-Max Scaling for normalization

Feature Selection
Used SelectKBest with f_classif
Selected the top 3 most relevant features
study_hours
attendance
previous_score

Model Training
Implemented Logistic Regression
Split data into training and testing sets (80:20)

Model Evaluation
Accuracy Score
Confusion Matrix
Classification Report (Precision, Recall, F1-score)

Results
Accuracy: 95%
The model performs well in predicting student outcomes
High precision and recall indicate reliable classification

Insights
Study hours and attendance have a strong impact on student success
Feature selection improves model efficiency and performance
Logistic Regression is effective for binary classification problems
Proper preprocessing significantly improves evaluation metrics

Files in Repository
Task2_ML_Classification.ipynb → Jupyter Notebook containing implementation and results
README.md → Project documentation

Conclusion
This project successfully demonstrates how to build and evaluate a machine learning classification model using a structured dataset.
The approach can be extended to real-world educational analytics and similar prediction problems.
