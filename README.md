# Deep-Learning-2025-26-Sana-Khan

📌 Overview
This repository contains a collection of Python scripts and Jupyter Notebook conversions demonstrating the implementation of various Machine Learning algorithms, Data Preprocessing techniques, and Deep Learning basics. The code covers Supervised and Unsupervised learning using popular libraries such as scikit-learn, pandas, numpy, and tensorflow.

📂 File Structure
1. machine_learning_py.py
This file focuses on fundamental Machine Learning algorithms and data cleaning techniques. It includes manual implementations and sklearn library usages.

Key Concepts Covered:

Data Cleaning: Handling missing values (Mean imputation, Most Frequent imputation), dropping NaN rows.

Linear Regression: Simple and Multiple Linear Regression (predicting height from weight, exam scores).

Logistic Regression: Binary classification on Salary/Purchase data and Car data.

K-Nearest Neighbors (KNN): Implementation on Handwritten Digits and Breast Cancer datasets.

Decision Trees: Classification based on Age and Salary.

Naive Bayes: Gaussian NB for weather prediction (Play Cricket dataset).

Support Vector Machine (SVM): Fruit classification (Apple vs. Orange).

Ensemble Methods: Bagging and AdaBoost implementations.

Unsupervised Learning: PCA (Dimensionality Reduction) and DBSCAN Clustering.

2. sana_ibm_sem3.py
This file appears to be aligned with an IBM Semester 3 curriculum, featuring advanced ensemble techniques, visualizations, and an introduction to Deep Learning.

Key Concepts Covered:

Data Preprocessing: Feature scaling, mode/mean imputation, and manual data entry.

Visualizations: Regression lines, Confusion Matrices, and Decision Boundaries using matplotlib and seaborn.

Advanced Ensembles:

Random Forest: Species classification on the Iris dataset.

Stacking: Combining SVM and KNN with a Logistic Regression meta-learner.

Gradient Boosting & XGBoost: High-performance classification on the Iris dataset.

Deep Learning: A simple Neural Network using TensorFlow/Keras (Sequential model with Dense layers).

Clustering: K-Means and Hierarchical Clustering (Dendrograms).

🛠️ Libraries & Dependencies
To run these scripts, you will need the following Python libraries installed:

Bash

pip install pandas numpy scikit-learn matplotlib seaborn xgboost tensorflow scipy
📊 Datasets Used
The notebooks utilize a mix of synthetic datasets created within the code and standard external datasets, including:

Titanic Dataset: For survival prediction (Logistic Regression).

Iris Dataset: For multiclass classification (Random Forest, SVM, XGBoost).

Breast Cancer Dataset: For KNN classification.

Digits Dataset: For image classification.

Healthcare/Car Data: Custom CSV imports.

👤 Author Details
Name: SANA KHAN

ID: 2410031378

Batch: 2CSE22

🚀 How to Run
Ensure all dependencies are installed.

If using Google Colab or Jupyter Notebook, copy the content into code cells.

Ensure external CSV files (e.g., machinelearning.data, Titanic-Dataset.csv) are uploaded to your working directory before running the data loading cells.
