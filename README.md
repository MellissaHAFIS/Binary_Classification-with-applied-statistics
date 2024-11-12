# Binary Classification Project

This repository contains a project on binary classification, where we aim to compare the performance of different predictors in a classification task. This project was completed as a collaborative effort between team members Idrissa DICKO, Alois VINCENT, and Me.

## Project Overview

The goal of this project is to evaluate and compare the performance of three models:
1. **No-Skill Model**: A baseline model that predicts randomly.
2. **PCA-Based Model**: A model based on Principal Component Analysis (PCA) for dimensionality reduction, followed by a threshold-based classification.
3. **Logistic Regression Model**: A standard logistic regression classifier.

Through analyzing and computing various evaluation metrics, we assess the effectiveness of each model and identify which model performs best in distinguishing between the two classes.

## Contents of the Repository

- **Notebook**: The Jupyter Notebook (`binary_classification_analysis.ipynb`) contains all code for data preparation, model training, prediction, and evaluation. This notebook guides you through our step-by-step approach to conducting the analysis and computing the metrics for each model.

- **Report**: The detailed report (`binary_classification_report.pdf`) documents our methodology, including:
  - **Model Definition**: Description of each model and the rationale behind their selection.
  - **Training and Evaluation**: Explanation of the training process, metrics computation, and evaluation strategy.
  - **Results and Analysis**: A comparison of models based on various metrics (Sensitivity, Specificity, Precision, NPV, Accuracy, F1 Score) and an interpretation of the results.

## Evaluation Metrics

To evaluate the performance of each model, we computed the following metrics:
- **Sensitivity** (True Positive Rate)
- **Specificity** (True Negative Rate)
- **Precision**
- **Negative Predictive Value (NPV)**
- **Accuracy**
- **F1 Score**

These metrics help us understand each model's strengths and weaknesses, especially in terms of handling imbalanced datasets and achieving high accuracy in binary classification tasks.

## Results Summary

Through our analysis, we found that:
- **Logistic Regression** achieved the highest overall performance, consistently outperforming the baseline and PCA-based models across most metrics.
- **PCA-Based Model** showed variable performance depending on the threshold chosen, and was less effective compared to logistic regression.
- **No-Skill Model** served as a baseline and provided a point of reference to gauge model improvements.

## Team Acknowledgments

This project was a team effort, and we thank all members (A, B, and [Your Name]) for their contributions to the analysis, coding, and reporting aspects of this project.

## Getting Started

1. **Dependencies**: The code requires Python and libraries like `numpy`, `pandas`, `sklearn`, and `matplotlib`.
2. **Running the Notebook**: Load the Jupyter Notebook in a Python environment and follow the steps to reproduce the results.
3. **Viewing the Report**: Refer to `binary_classification_report.pdf` for a comprehensive explanation of our approach and findings.
