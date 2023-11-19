# Salary Prediction Model
This repository contains a simple Python script for predicting salaries based on years of experience using linear regression. 
The script utilizes the pandas, numpy, matplotlib, and scikit-learn libraries for data manipulation, visualization, and machine learning.

### Dataset
The dataset used for training and testing the model is loaded from a CSV file named "Salary_dataset.csv". 
The dataset includes two columns: "YearsExperience" and "Salary".

### Dependencies
Make sure you have the required dependencies installed. You can install them using the following:
pip install pandas numpy matplotlib scikit-learn

### Running the Code
1- Clone the repository:
git clone https://github.com/PassantAdel/Simple-Linear-Regression-model.git
cd salary-prediction

2- Run the Python script:
python salary_prediction.py

### The script
1- Loads the dataset and drops the first column.
2- Visualizes the data using a scatter plot.
3- Splits the data into training and testing sets.
4- Trains a linear regression model.
5- Predicts salaries for the test set and compares them with the actual values.
6- Calculates and displays the accuracy of the model on both training and testing sets.
7- Plots the regression line on separate graphs for the training and testing sets.

### Model Accuracy
The model achieves the following accuracy:

Training set accuracy: 96.82%
Testing set accuracy: 86.21%
