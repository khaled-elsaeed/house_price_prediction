# California Housing Price Prediction

## About Dataset
**Description**

The US Census Bureau has published California Census Data, containing 10 types of metrics such as population, median income, median housing price, and more for each block group in California. This dataset serves as input for project scoping and aims to specify the functional and nonfunctional requirements for it.

**Problem Objective**

The project's primary objective is to build a model for predicting housing prices and estimating median house values in California using the provided dataset. This model should learn from the data and be capable of predicting the median housing price in any district, given all other relevant metrics.

Districts or block groups represent the smallest geographical units for which the US Census Bureau publishes sample data, with each block group typically having a population of 600 to 3,000 people. In this dataset, there are a total of 20,640 districts.

**Domain:** Finance and Housing

## Analysis Tasks
1. **Build a Model for Housing Price Prediction**
    - Develop a model to predict median house values in California using the dataset.
    - Train the model to learn from the data, enabling it to predict the median housing price for any district, considering all other relevant metrics.
    - Utilize machine learning algorithms, including Linear Regression and GradientBoostingRegressor, for modeling.

2. **Predict Housing Prices based on Median Income**
    - Predict housing prices based on the median_income feature.

## Getting Started
1. **Load the Data**
   - Read the "housing.csv" file from the project folder into your program.
   - Print the first few rows of the dataset.
   - Extract input (X) and output (Y) data from the dataset.

2. **Handle Missing Values**
   - Fill missing values with the mean of the respective column.

3. **Encode Categorical Data**
   - Convert categorical columns in the dataset to numerical data, ensuring compatibility with machine learning algorithms.
   - Use one-hot encoding to represent categorical variables as binary vectors.

4. **Split the Dataset**
   - Split the data into three sets:
     - 70% for training.
     - 15% for testing.
     - 15% for validation.
   - This allows for model training, evaluation, and validation on separate datasets to assess performance accurately.

5. **Standardize Data**
   - Standardize the training, testing, and validation datasets to ensure consistent and reliable model training.

6. **Perform Regression Analysis**
   - Utilize machine learning algorithms, such as Linear Regression and GradientBoostingRegressor, on the training data to build predictive models.
   - Predict the output for the test dataset using the trained models.
   - Calculate and print the root mean squared error (RMSE) as a measure of model performance.
