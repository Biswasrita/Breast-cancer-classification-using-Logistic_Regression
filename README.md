# Breast Cancer Classification using Logistic Regression

## Overview

This project builds a Machine Learning model to classify breast cancer tumors as **Malignant** or **Benign** using the **Logistic Regression algorithm**.

The model is trained on the **Breast Cancer Wisconsin dataset** available in the Scikit-learn library. The project includes data preprocessing, exploratory data analysis, model training, evaluation, and a predictive system.

---

## Dataset Information

The dataset is loaded using:

sklearn.datasets.load_breast_cancer()

Dataset details:

- Total samples: 569
- Total input features: 30
- Target classes:
  - 0 → Malignant
  - 1 → Benign

Dataset shape:

(569, 31)

(30 features + 1 label column)

---

## Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Scikit-learn

---

## Project Workflow

### 1. Import Libraries

Libraries used:

- numpy
- pandas
- sklearn

---

### 2. Data Collection and Processing

Dataset loaded from sklearn and converted into Pandas DataFrame.

Label column added to dataset.

---

### 3. Exploratory Data Analysis

Performed:

- Displayed first and last rows
- Checked dataset shape
- Checked dataset information
- Statistical summary using describe()
- Checked distribution of target variable

---

### 4. Feature and Target Separation

Features stored in:

X

Target stored in:

Y

---

### 5. Train Test Split

Dataset split into:

- Training data → 80%
- Testing data → 20%

Training shape:

(455, 30)

Testing shape:

(114, 30)

---

### 6. Model Training

Model used:

Logistic Regression

Model trained using training data.

---

### 7. Model Evaluation

Accuracy on Training Data:

95.60%

Accuracy on Testing Data:

95.61%

The model performs very well and generalizes properly.

---

### 8. Predictive System

A predictive system is built where user input is given and model predicts:

Output example:

The Breast cancer is Malignant

or

The Breast cancer is Benign
