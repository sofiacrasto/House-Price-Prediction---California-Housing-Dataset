# House Price Prediction - California Housing Dataset

Overview

This project implements house price prediction using the California Housing Dataset and the XGBoost Regressor. It involves data preprocessing, exploratory data analysis (EDA), feature correlation analysis, and model evaluation using various metrics.

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
  
- Model Training: Using XGBoost Regressor to fit the training data
  
- Evaluation: Computing metrics like R² score, mean absolute error, and mean squared error
  
Results

After training the model on the dataset, the performance was evaluated using:

- R² Score: Measures how well the model explains variability in house prices
  
- Mean Absolute Error (MAE): Measures average absolute prediction error
  
- Mean Squared Error (MSE): Measures average squared prediction error
  
Visualizations

- A heatmap of feature correlations to understand relationships between variables
  
- Scatter plots and histograms for feature distributions
  
Usage

Clone this repository and run the Python script to train and evaluate the model:

python house_price_prediction.py


