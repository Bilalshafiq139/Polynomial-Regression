# Polynomial-Regression
This repository contains a Python script that implements Polynomial Regression to predict sales revenue based on advertising budget.

# Polynomial Regression Model

## Overview
This repository contains a Python script that implements **Polynomial Regression** to predict sales revenue based on advertising budget. The model captures nonlinear relationships between the variables, making it more effective than simple linear regression in certain scenarios.

---

## **Problem Statement**
Marketing teams often need to predict the return on advertising investments. This project aims to build a **Polynomial Regression** model that predicts **sales revenue** based on **advertising budget**, capturing nonlinear trends that indicate diminishing returns on ad spend.

### **How the Model Helps**
- Helps marketing teams optimize their **advertising budget allocation**.
- Provides better predictions compared to linear models when the relationship between variables is nonlinear.
- Avoids overspending on ads by identifying optimal spending points.

### **Dataset Description**
The dataset contains two columns:
- **advertising_budget**: The amount spent on advertising (in dollars).
- **sales_revenue**: The corresponding sales revenue (in dollars).

---

## **How the Script Works**
1. **Data Loading**: The script reads the dataset from a CSV file.
2. **Data Exploration**:
   - Visualizes the relationship between `advertising_budget` and `sales_revenue` using a scatter plot.
3. **Feature Transformation**:
   - Converts `advertising_budget` into polynomial features (e.g., degree 2 or 3).
4. **Model Training**:
   - Splits the dataset into **training (80%)** and **testing (20%)** sets.
   - Trains a **Polynomial Regression** model using `sklearn.linear_model.LinearRegression()`.
5. **Prediction & Evaluation**:
   - Makes predictions on the test dataset.
   - Evaluates the model using **Mean Squared Error (MSE)** and **R-Squared Score (R²)**.
6. **Visualization**:
   - Plots the polynomial regression curve against the actual data points to visualize the model’s fit.

---

## **Dependencies**
Ensure you have the following Python libraries installed:
```sh
pip install numpy pandas matplotlib scikit-learn
```

---

## **How to Run the Script**
1. Clone the repository:
   ```sh
   git clone <repository_url>
   ```
2. Navigate to the project folder:
   ```sh
   cd <project_folder>
   ```
3. Run the Python script:
   ```sh
   python polynomial_linear_regression.py
   ```
4. Follow the output to view predictions and visualization plots.

---

## **Contributing**
Contributions are welcome! Feel free to fork this repository and submit a pull request with improvements or additional features.


