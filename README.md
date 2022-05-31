# Data-Cleansing-for-ML
# Introduction
This repository contains information reflecting the amount of work that goes into perform data cleansing. For a machine learning algorithm to perform properly, it needs to be feed clean data and data in the real-world is far from being clean. So great amount of work goes into the data cleansing before any model can be built and functions accurately. This repository demostracted the cleaning of up the auto mobile data that was pulled from Kaggle for the purpose of building a regression model, this knowledge is . Additional reformatting, we have done to the data to ensure it is dirty. Jupyter notebook. 

# About the Data
Using the shape, it reveals that the data have 394 observations and 12 features, further exploration of the data reveals that the data have some missing values which the mile per gallon (MPG) have the great amount of null’s when the isnull function was applied to the data. Also, most of the data type for these data have objects data types which will not be suitable for a regression model. Next the data also shows that the Year column have various entry type which is not in the right format.

# Cleaning Data
The data cleaning process, MPG nulls was filled with the mean of the once that has values on them. The cylinder and origin were dropped because they have discreet values and not continues numeric values which will not be suitable for regression. All object types are converted to numeric types. The year that is not properly formatted was formatted to get the first four values and then it was converted to get the age based on the current year. 

# Checking for relationship
Here each available features were checked against the MPG to see if there is relationship

# Files 
cars.csv
Data Cleansing for Machine Learning.ipynb
Visualizing Relationship.ipynb

# Application
To use this code, you need to have Python and jupyter notebook installed, clone the repo or download as a zip file and create the necessary folder path. 
