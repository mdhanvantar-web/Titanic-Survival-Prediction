# Titanic Survival Prediction - Machine Learning Project

## Project Overview

This project builds and compares multiple machine learning models to predict passenger survival on the Titanic dataset.

The objective is to identify the best-performing classification model using standard evaluation metrics and demonstrate a complete machine learning workflow.

---

## Dataset

The dataset contains information about Titanic passengers, including:

* Passenger Class (Pclass)
* Gender (Sex)
* Age
* Number of Siblings/Spouses (SibSp)
* Number of Parents/Children (Parch)
* Fare
* Port of Embarkation (Embarked)
* Survival Status (Target Variable)

Dataset Source: Titanic Survival Prediction Dataset

---

## Project Workflow

### 1. Data Inspection

* Dataset loading
* Shape and structure analysis
* Missing value detection
* Data type inspection

### 2. Data Preprocessing

* Missing value handling
* Categorical variable encoding
* Removal of irrelevant columns
* Feature preparation

### 3. Feature Engineering

Selected features:

* Pclass
* Sex
* Age
* SibSp
* Parch
* Fare
* Embarked

### 4. Machine Learning Models

The following models were trained and evaluated:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

### 5. Evaluation Metrics

Models were compared using:

* Accuracy
* Precision
* Recall
* F1 Score

### 6. Model Comparison

The best-performing model was selected based on F1 Score and evaluated using a Confusion Matrix.

---

## Results

### Best Model

Random Forest Classifier

### Performance

* Accuracy: 82.12%
* Precision: 80.88%
* Recall: 74.32%
* F1 Score: 77.46%

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## Files

* Titanic_ML_Project.ipynb — Complete machine learning notebook

---

## Conclusion

The Random Forest model achieved the best overall performance for Titanic survival prediction. Proper preprocessing, feature selection, and model comparison enabled the development of an effective classification pipeline.

---

## Author

Monish Dhanvantar
Pluto Academy AI & ML Internship Project 02
