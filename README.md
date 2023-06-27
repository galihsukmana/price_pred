# Price Prediction with Linear Regression Model

This repository contains code and resources for predicting prices using a linear regression model. The goal of this project is to demonstrate how a linear regression model can be implemented to forecast prices based on historical data.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Dashboard](#dashboard)
- [Contributing](#contributing)

## Project Overview

In this project, we aim to build a price prediction model using a linear regression algorithm. Linear regression is a supervised machine learning algorithm that models the relationship between a dependent variable (price) and one or more independent variables (features) to predict the value of the dependent variable.

We will be utilizing a dataset of historical prices and corresponding features to train our linear regression model. Once trained, the model can be used to make price predictions on unseen data.

## Dataset

The [dataset](https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma?select=rideshare_kaggle.csv) used in this project consists of historical prices and relevant features. The dataset is provided in a CSV format and can be easily loaded into your preferred data analysis or machine learning tools.


## Installation

To use the code in this repository, you will need to have the following prerequisites:

- Python (version 3.7.16)
- [Required Python packages](requirements.txt)

To set up your environment and install the required packages, please follow these steps:

1. Clone this repository to your local machine (git@github.com:galihsukmana/price_pred.git):
2. Navigate to the project directory:
3. Create and activate a virtual environment (optional but recommended):
4. Install the required packages:


## Usage

To use the linear regression model and make price predictions, follow these steps:

1. Ensure you have installed all the required packages as mentioned in the [Installation](#installation) section.

2. Prepare your data:
- Load the dataset containing historical prices and relevant features.
- Preprocess and clean the data if necessary (handling missing values, feature scaling, etc.).
- Split the data into training and testing sets.

3. Train the linear regression model:
- Use the training data to fit the linear regression model.
- Optimize model hyperparameters if required.

4. Evaluate the model:
- Use the testing data to evaluate the performance of the trained model.
- Calculate relevant evaluation metrics (e.g., mean squared error, R-squared) to assess the model's accuracy.

5. Make price predictions:
- Use the trained model to make predictions on unseen data.
- Analyze and interpret the results.

Please refer to the code in this repository for a detailed implementation example.

## Results

The results of this model is 92% with R2score metric. This directory contains various output files, visualizations, or reports summarizing the model's performance and the predicted prices.

Feel free to explore the results and analyze the accuracy of the predictions.

## Dashboard

[Dashboard link](https://public.tableau.com/views/UberVsLyftDashboard/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link)

## Contributing

Contributions to this project are welcome! If you have any suggestions, improvements, or bug fixes, please submit a pull request. For major changes, please open an issue first to discuss the proposed changes.







