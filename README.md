# Decision Tree Assignment

## Overview
This repository contains `ML_Assignment_3.ipynb`, which explores decision tree-based learning methods for both classification and regression.

### Contents
- `ML_Assignment_3.ipynb`: Jupyter notebook with the full assignment implementation.

## Assignment Tasks
1. **Classification — Car Evaluation Dataset**
   - Preprocessing categorical features with `OrdinalEncoder`.
   - Training a CART decision tree using the Gini criterion.
   - Finding optimal tree depth using 5-fold cross-validation.
   - Evaluating Bagging with bootstrapped decision trees.
   - Evaluating a Random Forest classifier with a specified `m` feature subset size.

2. **Regression — Boston Housing Dataset**
   - Training a regression tree with `min_samples_leaf = 4`.
   - Finding the best Bagging ensemble size using cross-validation.
   - Evaluating a Random Forest regressor with `m = 7`.

3. **AI Usage Declaration**
   - The notebook includes a statement describing limited AI assistance.

## Dependencies
The notebook is written for Python and uses the following packages:

- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`

## Data
The notebook expects the following datasets to be mounted and available in Google Colab:

- Car Evaluation dataset: `/content/drive/MyDrive/MLCode/dataset/C/C.csv`
- Boston Housing dataset: `/content/drive/MyDrive/MLCode/dataset/C/boston_housing.csv`

> Update the file paths in the notebook if your dataset files are stored elsewhere.

## How to Run
1. Open `ML_Assignment_3.ipynb` in Jupyter or Google Colab.
2. Ensure the dataset paths are correct and datasets are accessible.
3. Execute the notebook cells sequentially.

## Notes
- The notebook uses `drive.mount('/content/drive')`, so it is designed to run in Google Colab by default.
- Visualizations include accuracy and error curves, as well as decision tree plots.
