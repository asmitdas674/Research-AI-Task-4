# Research-AI-Task-4

**Task: Predict price of cars from the given dataset using linear regression**

This repository contains my implementation of **linear regression from scratch** using **NumPy, Pandas, and Matplotlib**.  
Machine learning libraries such as **scikit-learn** were not used.

The project follows the approach taught in Andrew Ng’s supervised machine learning course and focuses on understanding how linear regression works internally rather than relying on library functions.

---

## About the Project

The Automobile dataset was used to predict car prices based on various features such as engine specifications, vehicle dimensions, fuel type, and drivetrain information.

The complete workflow is implemented manually in a Jupyter Notebook, including data preprocessing, model training, and evaluation.

---

## What was done

- Loaded and explored the dataset using Pandas  

- Handled categorical variables using:
  - Binary mapping  
  - Ordinal mapping  
  - One-hot encoding where required  

- Removed non-relevant identifier columns  

- Performed an **80:20 train–test split** to evaluate generalisation performance  

- Standardised features using mean and standard deviation (computed from training data only)  

- Added a bias term explicitly  

- Implemented:
  - Linear regression hypothesis  
  - Mean squared error cost function  
  - Batch gradient descent using partial derivatives  

- Visualised cost versus iterations to verify convergence  

- Evaluated the model using **MSE, RMSE, and R²**

---

## Results

- RMSE ≈ **3125**  
- R² ≈ **0.87**

Given that car prices in the dataset range approximately from INR 5,000 to INR 45,000, an average prediction error of around INR 3,000 is reasonable. The R² value indicates that the model explains about **87% of the variation in car prices**, demonstrating good predictive performance on unseen data.

---

## Libraries Used

- NumPy  
- Pandas  
- Matplotlib  

(scikit-learn was not used)

---

## Files

- Jupyter Notebook containing the complete implementation and outputs  
- Training dataset in CSV format  
- Dataset dictionary in XLSX format  
- README file (this document)

