# Adult Census Income Classification using Machine Learning

## Objective

This project focuses on predicting whether an individual's annual income exceeds $50K using demographic and employment-related information from the Adult Census Income Dataset. Multiple machine learning classification algorithms are trained and evaluated to identify the most effective model for income prediction.

## Dataset

- **Dataset:** Adult Census Income Dataset
- **Source:** Kaggle
- **Total Records:** Approximately 32,500
- **Target Variable:** Income (`>50K` or `<=50K`)
- **Problem Type:** Binary Classification

### Features

- Age
- Workclass
- Education
- Education Number
- Marital Status
- Occupation
- Relationship
- Race
- Sex
- Capital Gain
- Capital Loss
- Hours Per Week
- Native Country

## Project Workflow

### 1. Data Collection
- Download the dataset using KaggleHub.
- Load the dataset into a Pandas DataFrame.

### 2. Data Preprocessing
- Handle missing values.
- Remove duplicate records.
- Clean categorical data.
- Encode categorical variables.
- Scale numerical features.

### 3. Data Splitting
- Split the dataset into training and testing sets.
- Standardize numerical features using StandardScaler.

### 4. Model Training

The following machine learning models are implemented and compared:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

### 5. Model Evaluation

Models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- KaggleHub
- Jupyter Notebook


## Results

The performance of all five classification models is compared using multiple evaluation metrics. The complete results, confusion matrices, and model comparisons are available in the Jupyter Notebook.

## Conclusion

This project demonstrates the use of supervised machine learning techniques for income classification. By applying preprocessing, feature engineering, and model comparison, the project identifies the most suitable algorithm for predicting annual income.

## Author

**Name:** Anet Davis

**Registration Number:** 23BHI10146

**Application Number:** IN26011852

**Batch Number:** 1A

**Email ID:** anet.23bhi10146@vitbhopal.ac.in
