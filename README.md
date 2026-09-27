# Cancer Prediction Using Machine Learning

## Project Overview

This project applies machine learning to classify breast tumor diagnoses as
Malignant or Benign using the Breast Cancer Wisconsin Dataset.

The project covers data preprocessing, exploratory data analysis, feature
selection, feature scaling, Logistic Regression model training, prediction,
and model evaluation using standard classification metrics.

The implementation was developed in Python using Google Colab and
scikit-learn.
---

## Problem Statement

The objective of this project is to build a binary classification model that
predicts whether a tumor is Malignant or Benign based on diagnostic features
available in the dataset.

The project focuses on applying a complete machine learning workflow, from
data preprocessing and feature preparation to model training and evaluation.
---

## Dataset Information

The project uses the Breast Cancer Wisconsin Dataset.

### Dataset Details

- **Records:** 569
- **Target Variable:** Diagnosis
- **Classes:**
  - `M` — Malignant
  - `B` — Benign

The dataset contains numerical diagnostic features describing characteristics
of cell nuclei, including:

- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Symmetry
- Fractal Dimension

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Missing Value Analysis
4. Data Cleaning
5. Feature Selection
6. Train-Test Split
7. Feature Scaling
8. Logistic Regression Model Training
9. Prediction
10. Model Evaluation
11. Result Analysis

---

## Model Used

### Logistic Regression

Logistic Regression is a supervised Machine Learning algorithm used for binary classification problems. It is widely used in healthcare applications because of its simplicity, efficiency, and interpretability.

---

## Evaluation Metrics

The model was evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

These metrics help measure the model's prediction performance and reliability.

---

## Results

The trained model successfully classified tumors as malignant or benign with high accuracy.

Key outcomes:

* Accurate prediction of cancer diagnosis
* Efficient classification performance
* Demonstration of Machine Learning in healthcare applications

---

## Repository Structure

```text
Cancer-Prediction-Using-Machine-Learning/
│
├── Cancer_Prediction_Using_Machine_Learning.ipynb
├── Cancer.csv
├── README.md
└── screenshots/
```

---

## Future Enhancements

* Implement advanced Machine Learning algorithms
* Compare multiple classification models
* Deploy as a web application
* Integrate real-time healthcare datasets
* Develop an AI-assisted diagnostic system

---

## Machine Learning Workflow

1. Load the dataset
2. Inspect the dataset structure
3. Analyze missing values
4. Clean and preprocess the data
5. Select relevant features
6. Separate features and target variable
7. Split the dataset into training and testing sets
8. Apply feature scaling
9. Train the Logistic Regression model
10. Generate predictions
11. Evaluate model performance
12. Analyze the classification results

## Conclusion

This project demonstrates the practical implementation of Machine Learning in healthcare. Using Logistic Regression and data preprocessing techniques, the model effectively predicts breast cancer diagnosis and highlights the importance of AI-driven medical decision support systems.

---

## Author

**Hemanth Gandhi**

Internship Project – YBI Foundation
