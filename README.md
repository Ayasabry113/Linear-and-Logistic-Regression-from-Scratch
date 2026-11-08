# Linear and Logistic Regression — From Scratch

This repository contains two supervised-learning exercises implemented with NumPy and compared against Scikit-learn baselines.

## Part A: Linear Regression
- Synthetic regression dataset
- Batch Gradient Descent (BGD)
- Stochastic Gradient Descent (SGD)
- Mini-Batch Gradient Descent (MBGD)
- Comparison with Scikit-learn Linear Regression
- Test MSE and training-loss curves

## Part B: Logistic Regression
- Breast Cancer Wisconsin dataset
- Feature standardization
- Custom logistic regression using:
  - Batch Gradient Descent
  - Stochastic Gradient Descent
  - Mini-Batch Gradient Descent
- Comparison with Scikit-learn Logistic Regression
- Accuracy, classification report, confusion matrix, and loss curves

## Installation
```bash
pip install -r requirements.txt
```

## Run
Open `Linear_and_Logistic_Regression.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab and run the cells from top to bottom.

## Technologies
Python, NumPy, Pandas, Matplotlib, and Scikit-learn.

## Implementation Notes
The gradient-descent optimization routines and logistic regression classifier are implemented from scratch. Scikit-learn is used for dataset loading, train/test splitting, preprocessing, metrics, and reference baseline models.
