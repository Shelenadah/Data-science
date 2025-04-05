# Housing price prediction
🏡 Housing Price Prediction

This repository contains a Jupyter Notebook for building and evaluating a Linear Regression Model to predict housing prices. The project walks through the full data science pipeline—from data exploration to model evaluation—using Python.

📁 Dataset
The dataset used is Housing.csv, which includes various features related to housing conditions that influence price predictions.

🔧 Tools & Libraries
Python

Pandas

NumPy

Seaborn

Matplotlib

Scikit-learn (Linear Regression, RFE)

Statsmodels

📊 Workflow
1. Data Exploration & Visualization
Understand dataset structure

Visualize correlations and distributions using heatmaps and pairplots

2. Preprocessing
Rescaling data using standardization

Splitting into training and testing sets

Separating independent (X) and dependent (y) variables

3. Model Building
Linear Regression with Statsmodels

Feature selection using:

Recursive Feature Elimination (RFE)

Variance Inflation Factor (VIF) to handle multicollinearity

Iterative refinement by adding/dropping variables

4. Model Evaluation
Residual analysis for model assumptions

Predicting on test data

Plotting actual vs. predicted values

Calculating performance metrics (e.g., R²)

📌 Highlights
Used Recursive Feature Elimination (RFE) for automated feature selection

Addressed multicollinearity using VIF

Applied both manual and automated model refinement techniques

Final model tested and evaluated with real-world metrics
