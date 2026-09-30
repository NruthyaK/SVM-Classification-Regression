# Support Vector Machines — Classification & Regression

A hands-on implementation of **Support Vector Machines (SVM)** covering both **classification and regression** using the built-in datasets provided by **Scikit-learn**.

This repository contains two separate Jupyter notebooks:

- **Support Vector Classification (SVC)** using the Iris dataset
- **Support Vector Regression (SVR)** using the Diabetes dataset

The notebooks demonstrate the complete machine learning workflow, including data exploration, train-test splitting, feature scaling, model training, evaluation, kernel comparison, and hyperparameter experimentation.

---

## 📌 Overview

Support Vector Machines are supervised learning algorithms that can be used for both classification and regression problems.

This project focuses on understanding the practical implementation of:

- Support Vector Classification
- Support Vector Regression
- Feature scaling
- Kernel functions
- Hyperparameters
- Model evaluation
- Hyperparameter tuning

Rather than treating SVM as a black-box algorithm, the notebooks explore how different kernels and hyperparameters influence model performance.

---

## 🎯 Objectives

The main objectives of this project are to:

- Understand the practical workflow of Support Vector Machines
- Implement SVM for classification and regression
- Explore the Iris and Diabetes datasets
- Perform train-test splitting
- Apply feature scaling
- Train a Support Vector Classifier
- Train a Support Vector Regressor
- Compare different SVM kernels
- Evaluate classification performance
- Evaluate regression performance
- Investigate the effect of the `C` hyperparameter
- Perform hyperparameter tuning using `GridSearchCV`
- Understand how model configurations affect performance

---

# 📂 Repository Structure

```text
support-vector-machines/
│
├── README.md
├── requirements.txt
├── .gitignore
│
└── notebooks/
    ├── svm_classifier.ipynb
    └── svm_regressor.ipynb