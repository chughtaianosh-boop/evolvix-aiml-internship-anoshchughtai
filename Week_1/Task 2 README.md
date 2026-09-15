# Week 1 Task 2: First Machine Learning Model

## Overview
This task involves training a baseline Machine Learning classification model using `scikit-learn` to predict the 'User Behavior Class' from the dataset. 

## Files Included
- `Week_1_Task_2_Anosh.ipynb`: The Jupyter Notebook containing the data preprocessing, model training, and evaluation.
- `baseline_model.pkl`: The saved Logistic Regression model.

## Model Evaluation Metrics
A Logistic Regression model was trained and evaluated on a 20% test split. Here are the performance metrics based on the test set:

| Metric | Value | Meaning |
| :--- | :--- | :--- |
| **Accuracy** | 1.0000 | The model correctly predicted 100% of the user behavior classes in the test set. |
| **Precision** | 1.0000 | Out of all the positive predictions made by the model, 100% were actually correct. |
| **Recall** | 1.0000 | The model successfully identified 100% of the actual positive cases. |
| **F1-Score** | 1.0000 | The harmonic mean of precision and recall is perfect, indicating a perfectly balanced model. |
