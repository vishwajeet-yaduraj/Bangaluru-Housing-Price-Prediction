# Bangaluru-Housing-Price-Prediction

# Overview
This project focuses on predicting housing prices in Bengaluru, utilizing a dataset from Kaggle. Through comprehensive data cleaning, feature engineering, and the application of multiple regression models, we aim to provide accurate price predictions. This repository contains all the code and datasets used in the project.

# Dataset
The dataset used in this project was sourced from Kaggle and includes various features related to housing prices in Bengaluru, such as area, number of bedrooms, location, and more. After cleaning and preprocessing, the dataset was used to train Linear Regression, Lasso Regression, and Ridge Regression models.

# Requirements
The project is implemented in Python, and the following libraries are required:

NumPy
Pandas
Scikit-learn
You can install these libraries using pip:

pip install numpy pandas scikit-learn 

# Files in the Repository

data cleaning and preprocessing.ipynb: Jupyter notebook containing the data cleaning and preprocessing steps.
model_training.ipynb: Notebook with model training, including Linear Regression, Lasso, and Ridge Regression models.

# Model Performance
The models were evaluated based on the R2 score. Here are the results:

Linear Regression: 0.8145
Lasso Regression: 0.8026
Ridge Regression: 0.8145
These scores indicate that both Linear and Ridge Regression models perform similarly and are suitable for predicting housing prices in Bengaluru with a high degree of accuracy.

# How to Run
To replicate this project, follow these steps:

# Clone the repository.

Install the required libraries.
Run the data cleaning and preprocessing.ipynb notebook to clean the dataset.
Run the model_training.ipynb notebook to train the models and evaluate their performance.

# Contributions
Contributions to this project are welcome! You can contribute in several ways:

Improving the model's performance
Enhancing data preprocessing and feature engineering
Providing visualizations for better understanding of the data and results
Please feel free to fork the project, make your changes, and submit a pull request.

# License
This project is licensed under the MIT License - see the LICENSE file for details.

# Contact
For any queries or discussions regarding this project, please open an issue in the repository.
