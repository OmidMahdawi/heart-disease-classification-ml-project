# heart-disease-classification-ml-project


This project demonstrates an end-to-end machine learning workflow for predicting whether a patient has heart disease based on clinical parameters. The work is implemented in Python using popular machine learning and data science libraries.


## 📌 Problem Definition

Given clinical parameters about a patient, can we predict whether or not they have heart disease?

This project applies various machine learning algorithms to solve this classification problem.


## 📊 Dataset

Source:

UCI Machine Learning Repository – Heart Disease Dataset

Kaggle Version


## Features:
Some key attributes include:

age: Age of patient

sex: Male/Female

cp: Chest pain type (typical angina, atypical angina, non-anginal, asymptomatic)

trestbps: Resting blood pressure

chol: Serum cholesterol

thalach: Maximum heart rate achieved

exang: Exercise-induced angina (Yes/No)

oldpeak: ST depression induced by exercise

ca: Number of major vessels colored by fluoroscopy

thal: Normal, fixed defect, reversible defect

target: Presence of heart disease (1 = Yes, 0 = No)



## 🎯 Project Goal / Evaluation

The primary evaluation metric is classification accuracy.

A proof-of-concept target: ≥ 95% accuracy in predicting heart disease.



## ⚙️ Tools and Libraries

This project uses the following Python libraries:

pandas, numpy → Data handling & preprocessing

matplotlib, seaborn → Data visualization

scikit-learn → ML models, hyperparameter tuning, and evaluation metrics



## 🚀 Workflow

The project follows these key steps:

1. Problem Definition

2. Data Collection & Preparation

3. Exploratory Data Analysis (EDA)

4. Checking data distribution, correlations, and feature importance

5. Handling missing values and outliers

6. Feature Engineering

7. Modeling

  a. Logistic Regression

  b. K-Nearest Neighbors (KNN)

  c. Random Forest Classifier

8. Hyperparameter Tuning

  a. Using GridSearchCV and RandomizedSearchCV

9. Model Evaluation

Accuracy, Precision, Recall, F1-score, and Confusion Matrix


## 📈 Results

Compared multiple ML models.

Final model selection based on accuracy and balanced evaluation metrics.


## 🔮 Future Improvements

Try more advanced models (XGBoost, LightGBM, Neural Networks).

Use feature scaling and PCA for dimensionality reduction.

Collect more diverse datasets for better generalization.

📂 Project Structure
end-to-end-heart-disease-classification.ipynb   # Jupyter notebook with full workflow
README.md                                       # Project documentation
