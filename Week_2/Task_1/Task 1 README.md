# Week 2 Task 1: Mushroom Classification

This folder contains the notebook for Week 2 Task 1, where we built and compared different classification models on the Mushroom dataset to predict whether a mushroom is edible or poisonous.

## Model Comparison Summary

| Model | Precision | Recall | F1-Score | ROC-AUC | False Negatives |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Logistic Regression** | 1.0 | 0.9966 | 0.9983 | 1.0000 | 4 |
| **Decision Tree** | 1.0 | 1.0000 | 1.0000 | 1.0000 | 0 |
| **Random Forest** | 1.0 | 1.0000 | 1.0000 | 1.0000 | 0 |

## Recommended Model for Deployment
We recommend deploying the **Random Forest Classifier** (or a constrained Decision Tree). 

**Reasoning:** 
In mushroom classification, predicting a poisonous mushroom as edible (False Negative) is highly critical and fatal. Both tree-based models achieved **0 False Negatives**, whereas Logistic Regression misclassified 4 poisonous mushrooms. Random Forest is preferred as an ensemble model, making it more robust and less prone to overfitting than a single Decision Tree.
