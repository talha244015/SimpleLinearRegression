# SimpleLinearRegression
This project implements a simple linear regression model using only NumPy, without relying on machine learning libraries like scikit-learn. It allows fitting a straight line to training data and making predictions on new inputs.
# 🧠 What Is Simple Linear Regression?
Simple Linear Regression models the relationship between two variables by fitting a straight line:
# y=mx+b
m: Slope (how much y changes per unit x)
b: Intercept (value of y when x = 0)
## Methods:
# __init__()
Initializes the model with m (slope) and b (intercept) set to None.
# fit(x_train, y_train)
Computes the slope and intercept using the least squares method.
Inputs must be 1D NumPy arrays.
# predict(x_test)
Returns predictions for the input x_test using the fitted model.
# Model Training Summary
The linear regression model was trained on a dataset containing students' CGPA and their corresponding salary package offers (in LPA). This dataset captures the relationship between academic performance and placement outcomes.
# Model Behavior:
The model assumes a linear relationship between CGPA and Package.Once trained, it can predict salary offers for new CGPA values.

