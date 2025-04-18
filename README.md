# Diagnose-Diabetes
🩺 Diabetes Diagnosis Using Machine Learning
📌 Overview
This project aims to diagnose diabetes using machine learning techniques applied to structured medical data. By training a classification model on features like glucose level, BMI, insulin, and more, we predict whether an individual is diabetic or non-diabetic. The project focuses on maximizing evaluation metrics such as accuracy, precision, and recall — making it highly applicable to real-world medical diagnostics.

🚀 Features
📊 Data preprocessing with scaling and cleaning

🔍 Model training using XGBoost for high accuracy

📈 Evaluation using confusion matrix and classification report

📉 Visualization of model performance with heatmaps

📦 Clean and modular Python code for reproducibility

🧪 Dataset
Name: Pima Indians Diabetes Dataset

Source: UCI Machine Learning Repository

Features:

Pregnancies

Glucose

Blood Pressure

Skin Thickness

Insulin

BMI

Diabetes Pedigree Function

Age

Outcome (target: 0 = non-diabetic, 1 = diabetic)

🧠 Models Used
Random Forest (baseline)

XGBoost (final choice)

Tuned for better accuracy (>85%)

📊 Evaluation Metrics
Accuracy

Precision

Recall

F1-Score

Confusion Matrix (with heatmap)

Classification Report
Project Structure:-
├── data/
│   └── 2. Diagnose Diabetes.csv
├── src/
│   ├── preprocessing.py
│   ├── model_training.py
│   └── evaluation.py
├── visuals/
│   └── confusion_matrix_heatmap.png
├── README.md
└── main.py
