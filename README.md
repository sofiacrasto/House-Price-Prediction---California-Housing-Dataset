# House Price Prediction - California Housing Dataset

Overview

This project utilizes XGBoost Regression to predict house prices in California using the California Housing Dataset. It involves data preprocessing, exploratory data analysis (EDA), correlation analysis, model training, and evaluation to generate accurate price predictions.

Dataset

The dataset is sourced from scikit-learn’s California housing dataset, which contains features like median income, house age, population, and more. The target variable is the median house price in different locations.

Technologies Used

- Python (Data Analysis & Modeling)
  
- Pandas & NumPy (Data Manipulation)
  
- Matplotlib & Seaborn (Visualization)
  
- Scikit-learn (Dataset & Metrics)
  
- XGBoost (Machine Learning Model)

  
Installation

To run this project, install the necessary dependencies using:

pip install xgboost

Steps in the Project

- Data Loading: Fetching the California Housing dataset from scikit-learn
  
- Data Preprocessing: Handling missing values, feature selection
  
- Exploratory Data Analysis (EDA): Understanding feature distributions, correlation analysis
  
- Model Training: -  Applying XGBoost Regressor to train a predictive model.
  
- Model Evaluation – Assessing performance using R² Score, Mean Absolute Error (MAE), and Mean Squared Error (MSE).

- Visualization – Plotting actual vs. predicted house prices to analyze performance.
  
Results & Insights

The trained model effectively predicts house prices based on key features. Evaluation metrics used include:

- R² Score – Measures how well the model explains house price variability.
  
- Mean Absolute Error (MAE) – Indicates the average absolute prediction error.
  
- Mean Squared Error (MSE) – Measures squared prediction deviations.

  
Visualizations
- Feature correlation heatmap – Identifies key relationships between variables.
  
- Scatter plot – Displays actual vs. predicted prices.

  
Usage

Clone the repository and execute the Python script to train and test the model:

python house_price_prediction.py


