# Rossmann Store Sales Prediction Project

## Overview
This project aims to predict the sales of Rossmann stores using machine learning techniques. The dataset includes information about sales, promotions, competitors, and other factors that may affect sales.

## Dataset
- Two datasets are used in this project: Rossmann Stores Data and Store Data.
- Rossmann Stores Data includes information about sales, customers, dates, and promotions.
- Store Data includes details about the stores, such as competition distance, assortment type, and store type.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Missingno
- Scikit-learn
- Google Colab (for data loading)

## Data Preprocessing
- Merging datasets
- Handling missing values
- Encoding categorical variables
- Feature engineering (e.g., extracting year, month, and date from the date column)

## Exploratory Data Analysis (EDA)
- Visualizing sales trends over time (monthly, yearly)
- Analyzing the impact of promotions, school holidays, and state holidays on sales
- Investigating sales variations based on different store types, assortment types, etc.

## Machine Learning Models
- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R-squared (R2)
- Mean Absolute Percentage Error (MAPE)

## Hyperparameter Tuning
- GridSearchCV for optimizing model hyperparameters

## Results and Visualizations
- Bar plots, point plots, and pie charts to visualize relationships between variables
- Analysis of sales trends, promotional impact, store types, and more

## Usage
1. Clone the repository.
2. Install the required libraries mentioned in `requirements.txt`.
3. Run the Jupyter notebook `Rossmann_Store_Sales_Prediction.ipynb`.
4. Explore the code, data preprocessing, EDA, model building, and evaluation steps.
5. Experiment with different models and hyperparameters for better predictions.

