# car_price_prediction


## About

Based on various market surveys, the consulting firm has gathered a large dataset of different types of cars across the American market. 
We're about to explore the world of cars, solve mysteries, and have a good laugh along the way!

The dataset for this project is derived from Kaggle.


## About Data
This car price prediction dataset have 205 rows and 26 colums.From where we have to select a suitable dependent variable 
concerning independent variables. 


|             Columns              |                                   Description     |
|----------------------------------| ---------------------------------------------     |
|CarID                             |  Identification Number for Each Car|
|CarName                            |  Name of the Car Model|
|FuelType                           |  Type of Fuel Used (Gasoline, Diesel, Electric, etc.)|
|Aspiration                         |  Type of Aspiration (Standard or Turbocharged)|
|Doornumbers                          |  Number of Doors on the Car|
|carBody                          |  Style of the Car's Body (Sedan, Coupe, SUV, etc.) |
|DriveWheel                    |  Type of Drive Wheels (Front, Rear, All)|
|EngineLocation                     | Location of the Car's Engine (Front or Rear)|
|Wheelbase                          | Length of the Car's Wheelbase|
|CarLength                          | Overall Length of the Car|
|CarWidth                           | Width of the Car|
|CarHeight                          | Height of the Car|
|CurbWeight                         | Weight of the Car without Passengers or Cargo |
|EngineType                          | Type of Engine (Gas, Diesel, Electric, etc.) |
|Cylindernumber                       | Number of Cylinders in the Engine |
|EngineSize                         | Size of the Car's Engine |
|FuelSystem                         | Type of Fuel Delivery System |
|BoreRatio                          | Bore-to-Stroke Ratio of the Engine |
|Stroke                             | Stroke Length of the Engine |
|CompressionRatio                   | Compression Ratio of the Engine |
|Horsepower                         | Car's Engine Horsepower |
|PeakRPM                            | Engine's Peak RPM (Revolutions Per Minute) |
|CityMPG                            | Miles Per Gallon (MPG) in City Driving |
|HighwayMPG                         | MPG on the Highway |
|CarPrice                           | Price of the Car |


## Problem Statement
1. Predicting the price of cars based on a wide range of attributes and features.
2. Find the most influence variables of the model

## Prepared Dataset:

1. Check Missing values
2. Check Duplicates
3. Check data type
4. Check the number of unique values of each column
5. Check statistics of the dataset
6. Check various categories present in the different categorical column
7. Encoding categorical variables
8. EDA (Explanatory Data Analysis)

## Model Fitting
  ### 1. Variables selection 
  Select the Terget Variables and features variables 
  ### 2. Train_Test_Spilt
  spilt the main data set into trainset(80%) and testset(20%)
  ### 3. Model training
  Fit a multiple linear regression model
  ### 4. Predictions
  Predict the test value
  ### 5. Evaluate the model
  Model |  Value
  ------- | ---------
Train R-squared | 0.9078366070306788
Train RMSE | 2344.4456579001535
Test R-squared | 0.8397192098327357
Test RMSE | 3557.1350895872

    



## Model Diagnostics and Assumption Tests :

1. Check Linearity Assumption
2. Check Multicollinearity (Variance Inflation Factor - VIF)
3. Check for Normality of Residuals
4. Check for Autocorrelation of Residuals

## Results 
Model R-square value is 83% (rsme = 3557.1350895872) which is a good fit.  The most positively affected variables is drivewheel( 826.3772)  and the most negatively affected variable is stroke (-2777.6633)




