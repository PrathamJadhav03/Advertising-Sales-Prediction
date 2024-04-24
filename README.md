# Advertising Sales Prediction using Random Forest Regression
# Overview
In this project, I developed a machine learning model to predict sales based on advertising data. The dataset used in this project is the Advertising dataset from Kaggle, which contains information about the advertising budget and sales for a company.

# Project Objectives
The main objectives of this project were:

* Load and preprocess the dataset, handling any missing values.
* Split the dataset into training and testing sets.
* Train a Random Forest Regression model on the training data.
* Evaluate the model's performance using the mean squared error (MSE) metric.
* Visualize the relationship between the actual and predicted sales.

# Implementation
The project is implemented in Python using the following libraries:

* `pandas`: for data manipulation and analysis
* `sklearn`: for machine learning algorithms and evaluation metrics
* `matplotlib` and `seaborn`: for data visualization

The code is organized in a Jupyter Notebook and can be found in the Advertising_Sales_Prediction.ipynb file.

# Results
After loading and preprocessing the dataset, I split it into training and testing sets. I then trained a Random Forest Regression model on the training data and evaluated its performance on the test set.

The model achieved an MSE of 2.64 on the test set, which indicates a good fit to the data. The low MSE suggests that the model is able to accurately predict sales based on the advertising data.

To visualize the relationship between the actual and predicted sales, I created a scatter plot. The plot shows a strong correlation between the actual and predicted sales, further confirming the model's effectiveness.

# Conclusion
This project demonstrates the use of machine learning techniques, specifically Random Forest Regression, to predict sales based on advertising data. The low MSE achieved by the model suggests that it can be a useful tool for businesses to forecast sales and optimize their advertising strategies.

The code and detailed explanations are available in the Jupyter Notebook. Feel free to explore the project and provide feedback or suggestions for improvement.