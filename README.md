# Task7
# Breast Cancer Diagnosis using SVM (Support Vector Machines)

This project applies Support Vector Machine (SVM) classifiers to the **Breast Cancer Wisconsin Diagnostic Dataset** to predict whether a tumor is **malignant (M)** or **benign (B)**. It includes data preprocessing, model training with different kernels, hyperparameter tuning, performance evaluation, and decision boundary visualization using PCA.

---

## Dataset

The dataset used is `breast-cancer.csv`, which contains 569 records and 30 numeric features related to cell nuclei characteristics derived from digitized images of fine needle aspirate (FNA) of breast mass.

| Column Type     | Description                                  |
|------------------|----------------------------------------------|
| `id`             | Unique identifier (dropped during analysis)  |
| `diagnosis`      | Target label: M = malignant, B = benign      |
| `features`       | 30 numeric columns like radius_mean, etc.    |

---

## Project Goals

1. Load and prepare the dataset for binary classification.
2. Train SVM models using:
   - Linear kernel
   - RBF (Radial Basis Function) kernel
3. Visualize decision boundaries using 2D projection.
4. Tune hyperparameters `C` and `gamma` using GridSearchCV.
5. Use k-fold cross-validation for performance evaluation.

---

## Technologies Used

- Python 3
- [scikit-learn](https://scikit-learn.org/stable/)
- pandas, numpy
- matplotlib, seaborn

---

## Implementation Steps

### Data Preprocessing

1. Load and prepare a dataset for binary classification.
2. Train an SVM with linear and RBF kernel.
3. Visualize decision boundary using 2D data.
4. Tune hyperparameters like C and gamma.
5. Use cross-validation to evaluate performance.


