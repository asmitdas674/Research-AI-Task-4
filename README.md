# Research-AI-Task-4

**Task: Predict price of cars from the given dataset using  linear regression**

This repository contains my implementation of **linear regression from scratch** using **NumPy, Pandas, and Matplotlib**.  
Machine learning libraries such as **scikit-learn** were not used.

The project follows the approach taught in Andrew Ng’s supervised machine learning course and focuses on understanding how linear regression works internally rather than relying on library functions.

---

## About the Project

The Automobile dataset was used to predict car prices based on various features such as engine specifications, vehicle dimensions, fuel type, and drivetrain information.

The complete workflow is implemented manually in a Jupyter Notebook.

---

## What was done

- Loaded and explored the dataset using Pandas  

- Handled categorical variables using:
  - Binary mapping  
  - Ordinal mapping  
  - One-hot encoding where required

- Removed non-relevant identifier columns 

- Standardised features using mean and standard deviation  

- Added a bias term explicitly

- Implemented:
  - Linear regression hypothesis  
  - Mean squared error cost function  
  - Batch gradient descent using partial derivatives  

- Visualised cost versus iterations to verify convergence 

- Evaluated the model using MSE, RMSE, and R^2

---

## Results

- RMSE = 2300 (approx.)
- R^2   = 0.91 (approx.)

The model explains most of the variation in car prices and shows good convergence behaviour.

---

## Libraries Used

- NumPy  
- Pandas  
- Matplotlib  

(scikit-learn was not used)

---

## Files

- Jupyter Notebook containing the full implementation and results, the training dataset as a csv file, the corresponding dictionary as xslx file and a README file, the one you have just finished reading.
