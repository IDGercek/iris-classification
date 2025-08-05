# Iris Flower Classification

## Overview
This is a supervised machine learning project that aims to predict the species of a flower based on it's sepal and petal width and lengths. The dataset used is the classical Iris Dataset. The project includes model training, evaluation and comparison of multiple different machine learning algorithims, as well as an exploratory data analysis.

## Models Comparison
- Neural Network
    - File: [neural_network.ipynb](/notebooks/models/neural_network.ipynb)
    - Main Library: PyTorch
    - Accuracy: 100%

- Logistic Regression
    - File: [logistic_regression.ipynb](/notebooks/models/logistic_regression.ipynb)
    - Main Library: NumPy
    - Accuracy: 96.67%

- Random Forest
    - File: [random_forest.ipynb](/notebooks/models/random_forest.ipynb)
    - Main Library: NumPy
    - Accuracy: 96.67%

- Decision Tree
    - File: [decision_tree.ipynb](/notebooks/models/decision_tree.ipynb)
    - Main Library: NumPy
    - Accuracy: 90%

- K-Nearest-Neighbors
    - File: [knn.ipynb](/notebooks/models/knn.ipynb)
    - Main Library: NumPy
    - Accuracy: 36.67%

## Folder Structure
```
iris-classification
│
├───data
│   └───images
└───notebooks
    ├───data-analysis
    └───models
```

## General Information
- Dataset: [Iris.csv](data/Iris.csv)
- EDA Notebook: [eda.ipynb](notebooks/data-analysis/eda.ipynb)
- Model Notebooks: [models](notebooks/models/)
- Used Libraries: [requirements.txt](requirements.txt)