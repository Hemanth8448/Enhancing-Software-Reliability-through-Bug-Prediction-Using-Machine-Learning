# Enhancing Software Reliability Through Bug Prediction Using Machine Learning

## Overview

This project focuses on predicting and classifying bug-prone software modules using machine learning models based on object-oriented software metrics. The main objective is to automate bug detection, reduce manual debugging efforts, and enhance software quality assurance.

The dataset includes metrics from real-world open-source software systems such as Eclipse JDT, PDE, Lucene, Equinox, and Mylyn. These metrics provide insights into software complexities, including coupling, cohesion, inheritance, and size, which are essential for identifying defect-prone modules.

---

## Project Objectives

- Predict bug-prone software components based on software metrics.
- Enhance software reliability by early detection and correction of bugs.
- Improve testing efficiency by prioritizing high-risk modules.
- Compare machine learning models to select the most effective one.
- Analyze feature importance to guide software design improvements.

---

## Technologies Used

- Python
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib & Seaborn (for visualization)
- Jupyter Notebook

---

## Dataset

Collected from:
- Eclipse JDT Core
- Eclipse PDE UI
- Equinox Framework
- Lucene
- Mylyn

Key attributes include:


---

## Methodology

1. **Data Collection:** Using open-source software datasets.
2. **Data Preprocessing:** Handling missing values, scaling features, splitting into train-test sets.
3. **Exploratory Data Analysis:** Visualizing distributions, class imbalances, and feature relationships.
4. **Model Training:** Implemented machine learning models:
    - Random Forest Classifier
    - K-Nearest Neighbors (KNN)
    - K-Means Clustering
5. **Evaluation:** Using Accuracy, ROC-AUC, and F1-Score.

---

## Results

| Model                   | Accuracy | ROC-AUC | F1-Score |
|-------------------------|----------|---------|----------|
| K-Nearest Neighbor      | 84.86%   | 0.563   | 0.444    |
| Random Forest Classifier| 85.11%   | 0.567   | 0.457    |
| K-Means Clustering      | 65.01%   | 0.532   | 0.148    |

**Conclusion:** Random Forest Classifier proved to be the most effective in predicting bug-prone modules.

---

