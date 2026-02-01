

# Predictive Analysis Using Machine Learning

**Intern Details:**
Name: Sahil Balkrushna Gadge
Company: CODETECH IT SOLUTIONS PVT. LTD
ID: CT12DR1813
Domain: Data Analytics
Duration: November 15th 2025 to February 15th 2026
Mentor: Neela Santhosh Kumar

---

**Project Overview:**
This project demonstrates the development of a Machine Learning classification model to predict outcomes based on a dataset. The objective is to showcase the complete machine learning workflow including data generation, data preprocessing, feature selection, model training, and model evaluation using Python.

The model predicts whether a student will pass or fail based on academic and behavioral factors.

---

**Objective:**
To build a machine learning classification model that predicts student performance in terms of pass or fail using structured data and standard ML techniques.

---

**Dataset:**
The dataset used in this project is synthetically generated using NumPy to simulate real-world student academic data. A total of 200 records are generated to train and evaluate the model.

---

**Features:**

* **study_hours**: Represents the number of hours a student studies
* **attendance**: Represents the attendance percentage of the student
* **previous_score**: Represents the student’s score in the previous examination
* **assignments_completed**: Represents the number of assignments completed by the student

---

**Target Variable:**

* **pass**

  * Value 1 → Pass
  * Value 0 → Fail

The target variable is created using logical conditions based on study hours and attendance percentage.

---

**Tools and Technologies Used:**
Python 3
Jupyter Notebook
NumPy
Pandas
Scikit-learn

---

**Steps Performed:**

**1) Data Generation:**

* Generated 200 student records using NumPy
* Converted the generated data into a Pandas DataFrame

**2) Data Preprocessing:**

* Separated independent features and target variable
* Applied Min-Max Scaling to normalize feature values

**3) Feature Selection:**

* Used SelectKBest with f_classif
* Selected the top three most important features:

  * study_hours
  * attendance
  * previous_score

**4) Model Training:**

* Implemented Logistic Regression for classification
* Split the dataset into training and testing sets using an 80:20 ratio

**5) Model Evaluation:**

* Evaluated the model using Accuracy Score
* Generated Confusion Matrix
* Generated Classification Report including precision, recall, and F1-score

---

**Results:**

* The model achieved an accuracy of 95 percent on the test dataset.
* High precision and recall values show that the classification is reliable and consistent.

---

**Insights:**

* Study hours and attendance play a major role in student success
* Feature selection improves model efficiency and prediction performance
* Logistic Regression is effective for binary classification problems
* Proper preprocessing significantly improves overall evaluation metrics

---

**Files in Repository:**

* `task2.ipynb`: Jupyter Notebook containing the complete implementation and results
* `README.md`: Project documentation

---

**Conclusion:**
This project successfully demonstrates the complete process of building and evaluating a machine learning classification model using a structured dataset. The methodology used can be extended to real-world educational analytics and similar prediction-based applications.

---

