Task 2 : Machine Learning Model for Outcome Prediction

Name Sahil Balkrushna Gadge
Company CODETECH IT SOLUTIONS PVT. LTD
ID CT12DR1813
Domain Data Analytics
Duration November 15th 2025 to February 15th 2026
Mentor Neela Santhosh Kumar

Project Overview : 
This project demonstrates the development of a Machine Learning classification model to predict outcomes based on a dataset.
The objective is to showcase the complete machine learning workflow including data generation, preprocessing, feature selection, model training, and evaluation using Python.
The model predicts whether a student will Pass or Fail based on academic and behavioral factors.

Objective : 
To build a classification model that predicts student performance Pass or Fail using machine learning techniques.

Features : 
study_hours
(Number of hours studied)

attendance
(Attendance percentage)

previous_score
(Previous exam score)

assignments_completed
(Number of assignments completed)

Target Variable
(pass)
1 means Pass
0 means Fail
(The target variable is created using logical conditions based on study hours and attendance.)

Tools and Technologies Used :
Python 3
Jupyter Notebook
NumPy
Pandas
Scikit learn

Steps Performed : 

Data Generation : 

Generated 200 records using NumPy
Converted the data into a Pandas DataFrame

Data Preprocessing : 

Separated features and target variable
Applied Min Max Scaling for normalization

Feature Selection : 

Used SelectKBest with f_classif
Selected the top three most relevant features
study_hours
attendance
previous_score

Model Training :

Implemented Logistic Regression
Split the dataset into training and testing sets in 80 is to 20 ratio

Model Evaluation :

Accuracy Score
Confusion Matrix
Classification Report including precision recall and f1 score

Results : 

Accuracy achieved is 95 percent

The model performs well in predicting student outcomes
High precision and recall indicate reliable classification

Insights

Study hours and attendance have a strong impact on student success
Feature selection improves model efficiency and performance
Logistic Regression is effective for binary classification problems
Proper preprocessing significantly improves evaluation metrics

Files in Repository : 

task2.ipynb
Jupyter Notebook containing implementation and results

README.md
Project documentation

Conclusion

This project successfully demonstrates how to build and evaluate a machine learning classification model using a structured dataset.
The approach can be extended to real world educational analytics and similar prediction problems.
