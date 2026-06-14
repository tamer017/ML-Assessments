# Machine Learning Assessments

> A curated collection of hands-on machine learning assignments and coursework implementations, covering supervised learning, unsupervised learning, neural networks, and model evaluation from foundational to intermediate level.

[![Language](https://img.shields.io/badge/Language-Python%203.x-blue?style=flat-square)](https://www.python.org/)
[![Domain](https://img.shields.io/badge/Domain-Machine%20Learning%20Education-teal?style=flat-square)]()
[![Framework](https://img.shields.io/badge/Framework-Scikit--learn%20%7C%20TensorFlow%20%7C%20NumPy-orange?style=flat-square)]()

---

## Overview

This repository contains a progression of **machine learning assignments** completed as part of formal coursework training. Each assessment targets a distinct ML concept — from implementing algorithms from scratch to applying high-level libraries on real-world datasets. Together, they form a practical ML portfolio demonstrating both theoretical understanding and applied implementation skills.

---

## Topics Covered

### Supervised Learning
- **Linear Regression** — Gradient descent implementation from scratch; OLS closed-form solution; MSE/R² evaluation
- **Logistic Regression** — Binary and multi-class classification; sigmoid function; cross-entropy loss
- **Decision Trees** — CART algorithm; Gini impurity vs. information gain; depth pruning
- **Support Vector Machines (SVM)** — Hard and soft margin; RBF kernel; hyperparameter tuning with GridSearchCV
- **k-Nearest Neighbours (k-NN)** — Distance metrics (Euclidean, Manhattan); effect of k on bias-variance trade-off
- **Naive Bayes** — Gaussian NB for continuous features; Bernoulli NB for text features

### Unsupervised Learning
- **K-Means Clustering** — Elbow method for k selection; cluster inertia; convergence analysis
- **Hierarchical Clustering** — Dendrogram visualization; Ward, complete, average linkage
- **Principal Component Analysis (PCA)** — Explained variance ratio; scree plot; 2D/3D visualization of high-dimensional data
- **DBSCAN** — Density-based clustering; epsilon and min_samples tuning; outlier detection

### Neural Networks & Deep Learning
- **Feedforward Neural Networks** — From-scratch NumPy implementation; backpropagation; activation functions (ReLU, sigmoid, tanh)
- **Convolutional Neural Networks (CNN)** — Image classification on MNIST and CIFAR; Conv2D, MaxPool, Flatten, Dense layers
- **Regularization Techniques** — L1/L2 weight decay; Dropout; Batch Normalization

### Model Evaluation & Validation
- **Cross-Validation** — k-Fold, Stratified k-Fold; train/val/test split best practices
- **Evaluation Metrics** — Accuracy, Precision, Recall, F1-Score, ROC-AUC, Confusion Matrix
- **Hyperparameter Tuning** — GridSearchCV, RandomizedSearchCV; learning curve analysis
- **Feature Engineering** — One-hot encoding, label encoding, feature scaling, polynomial features

---

## Repository Structure

```
ML-Assessments/
├── assignment_01/          # Linear & Logistic Regression
├── assignment_02/          # Decision Trees & SVM
├── assignment_03/          # K-Means, PCA, Clustering
├── assignment_04/          # Neural Networks from scratch
├── assignment_05/          # CNNs with TensorFlow/Keras
├── datasets/               # Shared datasets used across assignments
├── utils/                  # Shared helper functions (metrics, plotting)
└── README.md
```

Each assignment folder contains:
- A Jupyter Notebook (`.ipynb`) with full analysis and explanations
- Any supplementary Python scripts (`.py`)
- Output figures and plots

---

## Key Libraries

| Library | Used For |
|---|---|
| `NumPy` | Matrix operations, algorithm implementation from scratch |
| `Pandas` | Data loading and preprocessing |
| `Matplotlib` / `Seaborn` | Visualization of results, loss curves, confusion matrices |
| `Scikit-learn` | Model implementations, cross-validation, metrics |
| `TensorFlow` / `Keras` | Deep learning models (CNN, regularization) |
| `Jupyter Notebook` | Interactive experiment documentation |

---

## Getting Started

```bash
git clone https://github.com/tamer017/ML-Assessments.git
cd ML-Assessments
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow jupyter
jupyter notebook
```

Open any assignment notebook and run cells sequentially. Datasets are included in the `datasets/` folder or downloaded automatically.

---

## Skills Demonstrated

`Supervised Learning` `Unsupervised Learning` `Neural Networks` `CNN` `Backpropagation` `Gradient Descent` `Model Evaluation` `Cross-Validation` `Feature Engineering` `Scikit-learn` `TensorFlow` `NumPy` `Matplotlib` `Jupyter Notebook` `Python`
