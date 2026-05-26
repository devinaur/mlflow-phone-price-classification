# MLflow Phone Price Classification

This project demonstrates a machine learning workflow for phone price classification using Logistic Regression and MLflow for experiment tracking, metric logging, and model management.

---

## Overview

The project includes:
- Dataset loading and preprocessing
- Train-test split
- Logistic Regression model training
- Model evaluation
- MLflow experiment tracking
- Automatic metric logging
- Model artifact storage

This project was created to explore machine learning operations (MLOps) concepts and reproducible ML workflows.

---

## Technologies Used

- Python
- Pandas
- Scikit-learn
- MLflow
- Conda

---

## Project Structure

```text
.
├── .github/
│   └── workflows/
│       └── ci.yml
├── mlruns/
├── MLflowProject
├── conda.yaml
├── modelling.py
├── phoneprice_preprocessing.csv
├── README.md
└── LICENSE
```

---

## Machine Learning Model

Model used:
- Logistic Regression

Parameters:
- Solver: lbfgs
- Max Iteration: 1000
- C: 1.0

---

## Evaluation Metrics

The project tracks:
- Accuracy
- Precision
- Recall
- F1 Score

Metrics are automatically logged using MLflow.

---

## Features

- Automated experiment tracking
- Parameter logging
- Metric logging
- Model artifact management
- Reproducible ML environments
- MLflow integration

---

## Running the Project

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the training script:

```bash
python src/train_model.py
```

---

## MLflow Integration

MLflow is used to:
- Track experiments
- Store trained models
- Log evaluation metrics
- Manage machine learning workflows
- Reproduce environments
