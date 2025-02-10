# Real-Estate-Price-Prediction-LinearRegression

# Overview

This project implements a Linear Regression model with Batch Gradient Descent to predict real estate prices based on square footage. The dataset contains property listings from San Luis Obispo County, and the model aims to estimate house prices by minimizing the Mean Squared Error (MSE).

# Dataset

The dataset consists of real estate listings with the following fields:

*MLS – Unique identifier for the listing

*Price – Listing price (in USD)

*Bedrooms – Number of bedrooms

*Bathrooms – Number of bathrooms

*Size – House size (square feet)

*Price/SQ.ft – Price per square foot

# For this project, we focus on Size (square footage) as the primary feature to predict house prices.

# Implementation Details

1. Data Preprocessing

*Feature Scaling: Min-Max Normalization applied to standardize square footage.

*Data Splitting: Dataset divided into training and testing sets.

2. Model Training: Batch Gradient Descent

*Parameters Initialization: Random values assigned to w0 and w1.

*Learning Rate (α): Set to 0.5 for effective convergence.

*Epochs: Model trained for 2000 iterations to minimize error.

*Cost Function: Mean Squared Error (MSE) used to evaluate performance.

*Regression Line: Model learns to fit a linear function mapping square footage to price.

# Results

📉 MSE vs. Number of Epochs

<img width="626" alt="Screenshot 2025-02-09 at 6 30 05 PM" src="https://github.com/user-attachments/assets/d6cb5047-b52b-459c-8041-83f661127660" />

A plot showcasing the decrease in MSE over 2000 epochs.

🏡 Regression Line Plot

<img width="583" alt="Screenshot 2025-02-09 at 6 30 55 PM" src="https://github.com/user-attachments/assets/6c282c75-9165-44f2-a15e-57c9257ff21e" />

A visualization of the regression line fitted over training data.

# 📊 Price Prediction Example

Example: Estimated price for a 5000 sq. ft. house (after normalizing input).



