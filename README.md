# Boston-Housing-Price-Prediction-Machine-Learning-
🏠 Boston Housing Price Prediction
📌 Project Overview

   This project predicts housing prices using the Boston Housing Dataset and a supervised machine learning approach. The goal is to build a regression model that estimates the median value of homes based on various socio-economic and property-related features.


🎯 Objective

   To develop a Linear Regression model that accurately predicts house prices using structured data.


📂 Dataset Information

 -> Dataset: Boston Housing Dataset

 -> Total Features: 13

 -> Target Variable: MEDV (Median Value of Owner-Occupied Homes)

Key Features Include:

 -> CRIM – Crime rate

 -> RM – Average number of rooms

 -> TAX – Property tax rate

 -> LSTAT – Percentage of lower status population

And more...


🛠️ Tech Stack

 -> Python

 -> NumPy

 -> Pandas

 -> Scikit-learn

 -> Jupyter Notebook


🔄 Project Workflow

 -> Import required libraries

 -> Load and convert dataset into pandas DataFrame

 -> Perform basic data inspection

 -> Split dataset into training (85%) and testing (15%) sets

 -> Train model using Linear Regression

 -> Evaluate model performance using RMSE


📊 Model Used 'Linear Regression'

 -> Linear Regression is a supervised learning algorithm used for predicting continuous values.

 -> from sklearn.linear_model import LinearRegression

model = LinearRegression()
model.fit(X_train, y_train)


📈 Evaluation Metric

Root Mean Squared Error (RMSE)

 -> Measures the average prediction error

 -> Lower RMSE indicates better model performance


🚀 How to Run the Project

 -> Clone the repository

 -> Install required libraries:

 -> pip install numpy pandas scikit-learn


Open the Jupyter Notebook:

jupyter notebook


Run all cells


📌 What This Project Demonstrates

 -> Understanding of supervised learning

 -> Data preprocessing and train-test split

 -> Regression modeling

 -> Model evaluation techniques

 -> Practical implementation using Scikit-learn


🔮 Future Improvements

 -> Feature scaling

Try advanced models (Random Forest, XGBoost)

Hyperparameter tuning

Cross-validation

Deploy as a web app
