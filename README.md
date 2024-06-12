# California Housing Price Prediction

## Background:
The US Census Bureau has published California Census Data containing various metrics such as population, median income, median housing price, etc., for each block group in California. This project aims to build a model to predict median house values in California using the provided dataset.

## Problem Objective:
Build a predictive model to estimate median house values in California based on district-level metrics.

## Analysis Tasks:
1. Load the data:
   - Read the “housing.csv” file into the program.
   - Extract input (X) and output (Y) data from the dataset.
2. Handle missing values:
   - Fill missing values with the mean of the respective column.
3. Encode categorical data:
   - Convert categorical columns to numerical data.
4. Split the dataset:
   - Split the data into 80% training dataset and 20% test dataset.
5. Standardize data:
   - Standardize training and test datasets.
6. Perform Linear Regression:
   - Train a Linear Regression model on the training data.
   - Predict housing prices on the test dataset.
7. Perform Decision Tree Regression:
   - Train a Decision Tree Regression model on the training data.
   - Predict housing prices on the test dataset.
8. Perform Random Forest Regression:
   - Train a Random Forest Regression model on the training data.
   - Predict housing prices on the test dataset.
9. Bonus Exercise - Linear Regression with one independent variable:
   - Extract the median_income column.
   - Train a Linear Regression model to predict housing values based on median_income.
   - Plot the fitted model for training and test data.

## Dataset Description:
- **longitude**: Longitude value for the block in California, USA
- **latitude**: Latitude value for the block in California, USA
- **housing_median_age**: Median age of the house in the block
- **total_rooms**: Total number of rooms (excluding bedrooms) in all houses in the block
- **total_bedrooms**: Total number of bedrooms in all houses in the block
- **population**: Total number of population in the block
- **households**: Total number of households in the block
- **median_income**: Median household income of all the houses in the block
- **ocean_proximity**: Type of the landscape of the block [Values: 'NEAR BAY', '<1H OCEAN', 'INLAND', 'NEAR OCEAN', 'ISLAND']
- **median_house_value**: Median household prices of all the houses in the block

## Dataset Size:
20640 rows x 10 columns
