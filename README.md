🧬 Diabetes Prediction Using Machine Learning (SVM and Ensemble Models) 

This project builds and compares multiple Machine Learning models to predict whether a person is diabetic based on medical attributes.  
It includes **data preprocessing, model training, evaluation using multiple metrics, and a simple predictive system** for new patient data.

Project Overview

The goal of this project is to:
- Use health-related features (like glucose level, BMI, age, etc.) to predict **diabetes outcome**.
- Compare the performance of different ML classification algorithms.
- Build a **scalable predictive pipeline** that can be reused for inference.
The project is implemented in Python using **Scikit-Learn**.

The dataset used is a tabular diabetes dataset with:
- **Features**: Numeric medical attributes (e.g. number of pregnancies, glucose level, blood pressure, BMI, etc.).
- **Target**: `Outcome` (0 = Not Diabetic, 1 = Diabetic).

Models Used:
Several classification models are trained and evaluated:
K-Nearest Neighbors (KNN)
Decision Tree Classifier
Random Forest Classifier
Logistic Regression
Support Vector Classifier (SVM) with linear kernel

Model Evaluation
The following metrics are used to compare models:
Accuracy
Precision
Recall
F1-Score

Libraries:
pandas, numpy
matplotlib, seaborn (for exploration/visualization)
scikit-learn (for preprocessing, modeling, metrics)
warnings (to suppress warnings for cleaner outputs)

