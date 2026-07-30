# Breast Cancer Classification using K-Nearest Neighbors (KNN)

**Author:** Anet Davis  
**Registration Number:** 23BHI10146  
**Application Number:** IN26011852  
**Batch Number:** 1A  
**Email ID:** anet.davis2023@vitbhopal.ac.in

---

## Objective

The objective of this project is to develop a **K-Nearest Neighbors (KNN)** classification model with **k = 5** to classify breast tumors as **Malignant (M)** or **Benign (B)** using diagnostic measurements from the Breast Cancer Wisconsin Diagnostic dataset.

---

## Dataset

**Breast Cancer Wisconsin Diagnostic Dataset**

Kaggle: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

---

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- kaggle

---

## Methodology

### 1. Data Exploration
- Loaded the dataset and examined its structure.
- Identified the numerical features and the target variable (`diagnosis`).
- Verified data types and checked for missing values.

### 2. Data Preprocessing
- Removed unnecessary columns (`id` and `Unnamed: 32`).
- Encoded the target variable:
  - Malignant (M) → 1
  - Benign (B) → 0
- Split the dataset into **80% training** and **20% testing** sets using stratified sampling.
- Standardized all features using **StandardScaler** before training the model.

### 3. Model Development
- Trained a **K-Nearest Neighbors (KNN)** classifier with **k = 5** on the standardized training data.

### 4. Model Evaluation
The model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Results

| Metric | Value |
|---------|--------|
| Accuracy | **95.61%** |
| Precision | **97.44%** |
| Recall | **90.48%** |
| F1-Score | **93.83%** |

---

## Conclusion

The K-Nearest Neighbors (KNN) model achieved an accuracy of **95.61%**, effectively classifying breast tumors as malignant or benign. Applying **StandardScaler** before training improved the model's performance by ensuring that all features contributed equally to the distance calculations. The model performs well on this diagnostic dataset and demonstrates that KNN is a reliable algorithm for binary classification tasks involving structured medical data.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
