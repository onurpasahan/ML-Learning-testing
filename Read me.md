# Handwritten Digit Classification Project

This repository contains a complete machine learning pipeline for classifying handwritten digits (0–9) using the official `scikit-learn` Digits dataset. The project compares the performance of a linear model (**Logistic Regression**) against a non-linear model (**Support Vector Machines**) using **5-Fold Cross-Validation** for hyperparameter tuning.

---

## 🚀 Project Overview

- **Dataset:** `sklearn.datasets.load_digits` (1,797 samples, 64 pixel features per sample).
- **Goal:** Multi-class classification of handwritten digits with maximum reliability.
- **Key Practices:** Stratified train-test split, rigorous feature scaling, prevention of data leakage, and systematic hyperparameter tuning (`GridSearchCV`).

---

## 🛠️ Requirements & Installation

To run this Jupyter Notebook successfully, you need **Python 3.xx.x** installed along with the following data science libraries:

```bash
pip install numpy matplotlib scikit-learn