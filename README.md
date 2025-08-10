# Predicting Wine Quality Prediction Using Machine Learning

This repository contains the course project report and code for predicting wine quality based on physicochemical properties using various supervised machine learning algorithms.

## Project Overview

Wine quality assessment is traditionally performed by expert sommeliers but can benefit from data-driven approaches for scalable and objective evaluation. This project implements and compares multiple machine learning models to classify wine samples into low and high quality based on measurable chemical features.

The study includes exploratory data analysis, model training, evaluation, and interpretability analysis to identify key factors affecting wine quality.

## Dataset

- The dataset consists of physicochemical measurements of wine samples and corresponding quality ratings.
- It contains 11 features, including acidity, sulphates, alcohol content, and more.
- Data was provided by the course instructor and is pre-partitioned into training and testing sets.
- Wine quality scores were binarized into two classes: Low Quality (scores 3–5) and High Quality (scores 6–9).

## Models Implemented

- Logistic Regression
- Decision Tree Classifier
- k-Nearest Neighbors (KNN)
- Naïve Bayes (Gaussian, Multinomial, Bernoulli variants)
- Random Forest Classifier
- Linear Regression (adapted for classification)

## Evaluation Metrics

Models were evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Training Time

Additionally, classification reports and confusion matrices were generated to analyze per-class performance.

## Key Findings

- Random Forest achieved the best performance with an accuracy of approximately 79.3% and the highest ROC-AUC.
- Feature importance analysis revealed alcohol content, sulphates, and volatile acidity as the most influential predictors.
- Simpler models like Logistic Regression and Gaussian Naïve Bayes provided reasonable baselines.
- Linear Regression, when adapted for classification, did not perform well, demonstrating the need for non-linear modeling in this task.

## Repository Structure

```

.
├── report.pdf            # Project report
├── Dataset/                 # Dataset files (if permitted to share)
├── predict_wine_quality.ipynb              # Python script for the project 
├── README.md             # This file

```

## How to Use

1. Review the `report.pdf` file to read the project report.
2. Explore the `predict_wine_quality.ipynb` folder for code used in data preprocessing, model training, and evaluation.
3. Modify or extend models and parameters as needed for experimentation.
4. Generate figures and tables as per the project requirements.

## Acknowledgments

- Dataset and project guidelines provided by Dr. Samiran Das.

---

Feel free to reach out for questions or suggestions!

---
