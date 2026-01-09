🧪 Glass Identification using Machine Learning
📌 Project Overview

This project implements a multiclass machine learning classification system to identify different types of glass based on their chemical composition and physical properties. The dataset is sourced from the UCI Machine Learning Repository and is widely used in forensic science and material classification problems.

The goal is to train multiple machine learning models, evaluate their performance using standard metrics, and compare results to determine the most effective approach for glass type classification.

📂 Dataset Information

Source: UCI Machine Learning Repository

Samples: 214

Features: 9 numerical features

Target: Type of Glass (Multiclass Classification)

🔬 Features

Refractive Index (RI)

Sodium (Na)

Magnesium (Mg)

Aluminum (Al)

Silicon (Si)

Potassium (K)

Calcium (Ca)

Barium (Ba)

Iron (Fe)

🔧 Technologies Used

Python

Pandas & NumPy

Scikit-learn

XGBoost

Matplotlib & Seaborn

⚙️ Project Workflow

Data loading and exploration

Data preprocessing and feature-target separation

Label encoding (applied for XGBoost)

Train-test split

Model training

Hyperparameter tuning using GridSearchCV

Model evaluation and comparison

🤖 Machine Learning Models

Random Forest Classifier

XGBoost Classifier

Logistic Regression

Support Vector Machine (SVM)

📊 Model Evaluation Metrics

Accuracy

Precision (Macro & Weighted)

Recall (Macro & Weighted)

F1-Score (Macro & Weighted)

Confusion Matrix

Classification Report

▶️ How to Run the Project
pip install -r requirements.txt

python glass_identification.py

🎯 Results

The models were evaluated and compared based on performance metrics. Tree-based models such as Random Forest and XGBoost showed strong performance due to their ability to capture nonlinear relationships in the data.
