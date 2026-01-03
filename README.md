# Bias-Variance-Trade-Off
This repository provides code, data, and scripts for the study on "k-fold cross-validation and the bias–variance trade-off". It includes preprocessing, experiments, and visualisations for analysing how varying k affects bias and variance across SVM, DT, LR, and KNN models on multiple datasets.

**Dataset**
- 12 datasets from multiple open-access sources were evaluated
- 4xLarge; 4xMedium; and 4xSmall Datasets
- The "data" folder contains the bias and variance values (based on the accuracy measure) for different k values across four ML models (three files)

**Data Preprocessing Steps**
- Remove Redundant Records: Deleted rows with identical values across all attributes.
- Remove Duplicate Records: Removed rows with partial overlaps in key features that could bias training.
- Handle Blank Entries and NaN Values: (a) Imputed missing numerical values using median imputation; and (b) Removed rows where missingness exceeded 20% of attributes.
- Convert Categorical Variables: Applied RIDIT scoring to transform non-integer categorical attributes into numeric values.
- Normalise Features: Scaled all features to a range of [0, 1] to prevent disproportionate influence of any feature.

**Models Used**
- Decision Tree
- k-Nearest Neighbours
- Logistic Regression
- Support Vector Machine

**Folder and File Descriptor:**
- Code: Python script for data preprocessing and implementing different ML models to quantify their bias and variance. We used the raw dataset from the online sources in these code files.
- Data: Contains files for bias and variance outcomes for different datasets
- bias_and_variance_plot.ipynb: a unified design for Figures 3-8
