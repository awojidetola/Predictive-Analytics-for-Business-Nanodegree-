# Data Clean up Project

The Business Problem
Pawdacity is a leading pet store chain in Wyoming with 13 stores throughout the state. This year, Pawdacity would like to expand and open a 14th store. Your manager has asked you to perform an analysis to recommend the city for Pawdacity’s newest store, based on predicted yearly sales.

Your first step in predicting yearly sales is to first format and blend together data from different datasets and deal with outliers.

Your manager has given you the following information to work with:

The monthly sales data for all of the Pawdacity stores for the year 2010.
NAICS data on the most current sales of all competitor stores where total sales is equal to 12 months of sales.
A partially parsed data file that can be used for population numbers.
Demographic data (Households with individuals under 18, Land Area, Population Density, and Total Families) for each city and county in the state of Wyoming. For people who are unfamiliar with the US city system, a state contains counties and counties contains one or more cities.
Map of Wyoming Counties

Steps to Success
Step 1: Business and Data Understanding
Your project should include a description of the key business decisions that need to be made.

Step 2: Building the Training Set
To properly build the model, and select predictor variables, create a dataset with the following columns:

City
2010 Census Population
Total Pawdacity Sales
Households with Under 18
Land Area
Population Density
Total Families

This dataset will be your training set to help you build a regression model in order to predict sales in the Practice Project in the next lesson. Every row should have sales data because we're trying to predict sales.

Step 3: Dealing with Outliers
Once you have created the dataset, look for outliers and figure out how deal with your outliers. Use the IQR method to determine if there are outlier cities for each of the variables and then justify which city that has at least one outlier value should be removed.
