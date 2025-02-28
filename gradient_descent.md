# Gradient Descent for Linear Regression
### Overview
This Jupyter Notebook explores and implements the gradient descent algorithm for optimizing the parameters of a univariate linear regression model. The goal is to find the best values for *`w`* and *`b`*  by minimizing the cost function using an iterative approach. This notebook is useful for those who want to understand how gradient descent works and how it can be applied to train a linear regression model.
### Features
- Introduction to gradient descent for linear regression
- Implementation of the cost function and its gradient
- Iterative optimization of parameters using gradient descent
- Visualization of gradient descent in action
- Use of NumPy for numerical computations
- Use of Matplotlib for data visualization
- Local plotting routines for enhanced visualization
### Requirements
To run this notebook, ensure you have the following dependencies installed:
- Python (>=3.7)
- Jupyter Notebook
- NumPy
- Matplotlib

**You can install the required packages using:**
```
pip install numpy matplotlib jupyter
```
### Dataset
The notebook uses a small dataset containing two data points:
|Size (1000 sqft)|Price (1000s of dollars)|
|----------------- |-----------------------|
|1.0|300.0|
|2.0|500.0|  

This dataset helps illustrate how gradient descent updates parameters to minimize the cost function.
### Notebook Structure
- **Introduction:** Overview of gradient descent and its role in optimization.
- **Problem Statement:** Predicting house prices based on size.
- **Data Representation:** Loading and displaying the dataset.
- **Mathematical Background:** Explanation of the cost function and gradient descent.
- **Code Implementation:** Writing Python code to implement gradient descent.
- **Visualization:** Plotting contour maps and gradient descent steps.
