# diabetic-prediction-using-ml
Project Overview
This project aims to predict whether a patient has diabetes based on various health metrics using machine learning techniques. The dataset used for this prediction is the famous Pima Indians Diabetes Database. The model is trained using various features such as glucose levels, blood pressure, and insulin levels to predict the likelihood of diabetes.

#Dataset
The dataset used in this project contains the following features:
Pregnancies: Number of times the patient was pregnant.
Glucose: Plasma glucose concentration after 2 hours in an oral glucose tolerance test.
BloodPressure: Diastolic blood pressure (mm Hg).
SkinThickness: Triceps skinfold thickness (mm).
Insulin: 2-Hour serum insulin (mu U/ml).
BMI: Body mass index (weight in kg/(height in m)^2).
DiabetesPedigreeFunction: Diabetes pedigree function.
Age: Age of the patient (years).
Outcome: Class variable (0 if non-diabetic, 1 if diabetic).
#Project Structure
Data Loading: The dataset is loaded using pandas and preliminary analysis is conducted to understand the structure and content.
Data Exploration: Basic statistics and visualizations are performed to gain insights into the dataset.
Modeling: Various machine learning models from sklearn are trained and evaluated to predict the outcome.
Evaluation: The performance of the models is assessed using metrics like accuracy, precision, recall, and F1-score.
#Libraries Used
Pandas: For data manipulation and analysis.
NumPy: For numerical computations.
Scikit-learn: For building and evaluating machine learning models.
Tkinter: Used for creating a simple graphical user interface (if applicable).

#Results
The machine learning models provide predictions on whether a patient has diabetes based on the input features. The best-performing model is evaluated based on its accuracy and other relevant metrics.
