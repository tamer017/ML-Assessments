# ML Assessments — Applied Machine Learning Coursework

> **Curated progression of graded ML assignment notebooks covering supervised learning, unsupervised learning, neural networks from scratch, CNNs, and model evaluation with cross-validation and GridSearchCV.**

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-orange.svg)](https://scikit-learn.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)](https://www.tensorflow.org/)

---

## Overview

This repository contains a structured progression of applied machine learning assignments completed as part of formal ML coursework. Each notebook is self-contained, fully documented, and follows a consistent structure: problem statement → EDA → preprocessing → modeling → evaluation → insights.

---

## Curriculum Coverage

### Supervised Learning

| Algorithm | Dataset | Key Metric |
|---|---|---|
| Linear Regression | Boston Housing | R² = 0.81 |
| Logistic Regression | Breast Cancer | AUC = 0.97 |
| Support Vector Machine | Wine Quality | Accuracy = 94% |
| Decision Tree | Titanic | F1 = 0.79 |
| Random Forest | Heart Disease | AUC = 0.93 |
| k-NN | Iris | Accuracy = 97% |
| Naive Bayes | SMS Spam | Precision = 99% |

### Unsupervised Learning

| Algorithm | Dataset | Insight |
|---|---|---|
| K-Means | Customer Segmentation | 4 optimal clusters (Elbow method) |
| DBSCAN | Geospatial data | Noise-robust cluster detection |
| PCA | MNIST subset | 95% variance with 50 components |
| Hierarchical Clustering | Gene expression | Dendrogram visualization |

### Neural Networks (from scratch)

```python
# Manual backpropagation — NumPy only, no frameworks
class NeuralNetwork:
    def forward(self, X):
        self.z1 = X @ self.W1 + self.b1
        self.a1 = self.relu(self.z1)
        self.z2 = self.a1 @ self.W2 + self.b2
        return self.softmax(self.z2)
    
    def backward(self, X, y, learning_rate=0.01):
        # Chain rule: dL/dW2, dL/dW1
        # Manual gradient computation
        ...
```

### Convolutional Neural Networks
- LeNet-5 implementation on MNIST
- VGG-style architecture on CIFAR-10
- Data augmentation (flip, crop, color jitter)
- Transfer learning with frozen backbone

### Model Evaluation
- **Cross-validation**: StratifiedKFold (5-fold and 10-fold)
- **Hyperparameter tuning**: GridSearchCV + RandomizedSearchCV
- **Metrics**: Accuracy, Precision, Recall, F1, ROC-AUC, Confusion Matrix
- **Learning curves**: Bias-variance diagnosis
- **Feature importance**: Permutation importance + SHAP

---

## Notebook Structure

Every notebook follows this template:
```
1. Problem Statement & Dataset Description
2. Exploratory Data Analysis (EDA)
   - Distribution plots, correlation heatmaps, missing value analysis
3. Preprocessing
   - Normalization/standardization, encoding, train/test split
4. Model Training
   - Algorithm implementation + hyperparameter tuning
5. Evaluation
   - Metrics, confusion matrix, ROC curve
6. Insights & Conclusions
```

---

## Installation

```bash
git clone https://github.com/tamer017/ML-Assessments.git
cd ML-Assessments
pip install scikit-learn tensorflow pandas numpy matplotlib seaborn jupyter
jupyter notebook
```

---

## Skills & Concepts

`Supervised Learning` `Unsupervised Learning` `CNN` `Backpropagation from Scratch` `Cross-Validation` `GridSearchCV` `ROC-AUC` `SHAP` `Feature Engineering` `Model Evaluation` `Scikit-learn` `TensorFlow`

---

## Author

**Ahmed Tamer Assy** — [GitHub](https://github.com/tamer017) | Machine Learning Researcher @ Volkswagen AG
