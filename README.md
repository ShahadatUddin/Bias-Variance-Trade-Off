# Bias-Variance-Trade-Off
This repository provides code, data, and scripts for the study on "k-fold cross-validation and the bias–variance trade-off". It includes preprocessing, experiments, and visualisations for analysing how varying k affects bias and variance across SVM, DT, LR, and KNN models on multiple datasets.

**Dataset**
- 12 datasets from multiple open-access sources were evaluated
- 4xLarge; 4xMedium; and 4xSmall Datasets
- The "data" folder contains the bias and variance values (based on the accuracy measure) for different k values across four ML models (three files)

**Models Used**
- Decision Tree
- k-Nearest Neighbors
- Logistic Regression
- Support Vector Machine

**File Descriptor:**
- main.py: Python script for implementing different ML models and calculating their bias and variance.
- bias_and_variance_plot.ipynb: a unified design for different figures
