# Cancer-detection

## Overview
This project focuses on developing machine learning models for the detection of breast cancer using the Breast Cancer Wisconsin (Diagnostic) dataset from scikit-learn. Various classification algorithms, including Naive Bayes, Support Vector Machine (SVM), Decision Tree, Random Forest, and Logistic Regression, are explored to identify the most effective model for breast cancer classification.

## Code Structure
notebooks: Jupyter notebooks containing code for data loading, model training, and evaluation.
venv: Virtual environment for managing project dependencies.
.gitignore: File specifying which files and directories to exclude from version control.

## How to Run Locally

### Prerequisites

- Ensure you have Python 3 installed on your machine.
- Create a virtual environment and install dependencies using the following commands:

  ```bash
  python -m venv venv
  source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
  pip install -r requirements.txt

## Dataset
The dataset includes information about tumor characteristics, such as mean radius, mean texture, mean area, and more. The goal is to predict whether a tumor is malignant or benign based on these features.

## Data Exploration
Loaded dataset using scikit-learn's Breast Cancer Wisconsin dataset.
Explored class labels, feature names, and sample data points.
Transformed class names ('malignant' and 'benign') into binary values (0 and 1).

## Model Evaluation
### Naive Bayes Classifier
Achieved an accuracy of 96.49%.
###  Support Vector Machine (SVM) Classifier
Utilized a linear kernel with an accuracy of 95.32%.
###  Decision Tree Classifier
Achieved an accuracy of 95.91%.
###  Random Forest Classifier
Outperformed other models with an accuracy of 97.08%.
###  Logistic Regression Classifier
Demonstrated an accuracy of 93.57% with a convergence warning.

## Model Selection
The Random Forest classifier achieved the highest accuracy, making it a strong candidate for breast cancer classification.
