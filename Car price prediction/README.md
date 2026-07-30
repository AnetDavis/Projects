# Car Price Prediction System

## Objective

This project predicts the selling price of used cars using machine learning techniques. A Random Forest Regressor is trained on vehicle-related features such as present price, fuel type, transmission, kilometers driven, and car age. The trained model is deployed as a Flask web application that allows users to estimate the selling price of a used car instantly.

## Dataset

- **Dataset:** Vehicle Dataset from CarDekho
- **Source:** Kaggle
- **Target Variable:** Selling Price
- **Problem Type:** Regression

### Features

- Present Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Number of Owners
- Car Age

## Project Workflow

### 1. Data Collection
- Download the CarDekho dataset.
- Load the dataset using Pandas.

### 2. Data Preprocessing
- Remove unnecessary columns.
- Handle missing values.
- Create the Car Age feature from the manufacturing year.
- Encode categorical variables.

### 3. Data Splitting
- Split the dataset into training and testing sets.

### 4. Model Training

The project uses the following machine learning model:

- Random Forest Regressor

### 5. Model Evaluation

The trained model is evaluated using:

- R² Score
- Root Mean Squared Error (RMSE)

### 6. Model Deployment

- Save the trained model using Pickle.
- Build a Flask web application.
- Predict the selling price based on user inputs.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Flask
- Pickle
- Jupyter Notebook

## Results

The Random Forest Regressor predicts the selling price of used cars based on different vehicle attributes. The model provides accurate price estimations, and the complete evaluation metrics are available in the Jupyter Notebook.

## Conclusion

This project demonstrates the application of machine learning for used car price prediction. By combining data preprocessing, feature engineering, and Random Forest Regression, the system delivers reliable price estimates through an easy-to-use Flask web interface.

## Author

**Name:** Anet Davis

**Registration Number:** 23BHI10146

**Application Number:** IN26011852

**Batch Number:** 1A

**Email ID:** anet.23bhi10146@vitbhopal.ac.in
