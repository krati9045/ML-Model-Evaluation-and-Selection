# ML Model Evaluation and Selection

This repository contains hands-on implementations of different techniques used to **evaluate, compare, and improve machine learning models** using Scikit-learn.

## Topics Covered

* K-Fold Cross-Validation
* Stratified K-Fold Cross-Validation
* Cross-validation using `cross_val_score`
* GridSearchCV
* RandomizedSearchCV
* Hyperparameter tuning
* Model comparison and selection
* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1 Score

## Dataset

The implementations use the **Heart Disease dataset** containing 303 records, 13 input features, and a `target` variable.

**Features:** `age`, `sex`, `cp`, `trestbps`, `chol`, `fbs`, `restecg`, `thalach`, `exang`, `oldpeak`, `slope`, `ca`, `thal`

**Target:** `target`

## Approach

The notebooks cover the workflow of:

**Model Training -> Cross-Validation -> Model Comparison -> Hyperparameter Tuning -> Model Evaluation**

Different evaluation metrics are explored to understand model performance beyond accuracy alone, including how **Precision, Recall, and F1 Score** provide different perspectives on classification performance.

## Key Learning

Through these implementations, I gained practical understanding of:

* Evaluating models using cross-validation
* Comparing multiple machine learning models
* Tuning hyperparameters using GridSearchCV and RandomizedSearchCV
* Interpreting confusion matrices
* Understanding the relationship between Precision, Recall, and F1 Score
* Selecting appropriate evaluation metrics for classification problems

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Jupyter Notebook / Google Colab
