# Breast Cancer Classification using Logistic Regression

## Overview

This project builds a Machine Learning model to classify breast cancer tumors as **Malignant** or **Benign** using the **Logistic Regression algorithm**.

The model is trained on the **Breast Cancer Wisconsin dataset** available in the Scikit-learn library. The project includes **data preprocessing, exploratory data analysis, model training, evaluation, and a predictive system**.

---

## Live Demo

You can try the deployed application here:

**Streamlit App:**  
https://breast-cancer-prediction-ms25nioupnxxas4ssyxeuk.streamlit.app/

The app allows users to input tumor feature values and get a prediction indicating whether the tumor is **Malignant** or **Benign**.

---

## Dataset Information

The dataset is loaded using:

```
sklearn.datasets.load_breast_cancer()
```

Dataset details:

- Total samples: **569**
- Total input features: **30**
- Target classes:
  - **0 → Malignant**
  - **1 → Benign**

Dataset shape:

```
(569, 31)
```

(30 features + 1 label column)

---

## Technologies Used

- Python  
- Google Colab  
- NumPy  
- Pandas  
- Scikit-learn  
- Streamlit

---

## Project Workflow

### 1. Import Libraries

Libraries used:

- numpy  
- pandas  
- sklearn  

---

### 2. Data Collection and Processing

The dataset is loaded from **Scikit-learn** and converted into a **Pandas DataFrame**.

A label column is added to the dataset.

---

### 3. Exploratory Data Analysis

Performed:

- Displayed first and last rows  
- Checked dataset shape  
- Checked dataset information  
- Statistical summary using `describe()`  
- Checked distribution of the target variable  

---

### 4. Feature and Target Separation

Features stored in:

```
X
```

Target stored in:

```
Y
```

---

### 5. Train Test Split

Dataset split into:

- **Training data → 80%**
- **Testing data → 20%**

Training shape:

```
(455, 30)
```

Testing shape:

```
(114, 30)
```

---

### 6. Model Training

Model used:

**Logistic Regression**

The model is trained using the training dataset.

---

### 7. Model Evaluation

Accuracy on **Training Data**:

```
95.60%
```

Accuracy on **Testing Data**:

```
95.61%
```

The model performs well and generalizes properly.

---

### 8. Predictive System

A predictive system is implemented where the user inputs tumor feature values and the model predicts the result.

Example outputs:

```
The breast cancer is Malignant
```

or

```
The breast cancer is Benign
```
