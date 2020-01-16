# Project 2 - Ames Housing Data and Kaggle Challenge

**Primary Learning Objectives:**
1. Creating and iteratively refining a regression model
2. Using [Kaggle](https://www.kaggle.com/) to practice the modeling process
3. Providing business insights through reporting and presentation.

Task: To create a regression model based on Ames Housing Dataset to predict the price of a house at sale

Datasets were extracted from Kaggle
1) 'sample_sub_reg' is the sample format for how the results of predicted SalePrice to be submitted to Kaggle
2) 'Train' is the Historical Data that is used for modelling
3) 'Test' is the dataframe which the selected model is used together with to do the prediction. 


## The Modeling Process

The train dataset has all the columns needed for generating and refining the model. 
the test dataset has all the columns except the target (SalePrice)

1) Making a data dictionary for easy reference and understanding of each variable's meaning
2) Identified outliers and incorrectly collected datas
3) Adjustments made to the Train dataset, is also done to the Test dataset unless inappropriate
4) Dropping/Merging columns that are refelcting same information(s)
5) Featuring engineering with making sense of the column informations
6) Removing Columns that was used for merging, and variables that exceeded the threshold level reflected by the histogram
7) Addressing and handling Nulls, inputing the appropriate values
8) Identify clearly Continuous variables, Categorical variables, Nominal variables, and Ordinal variables
9) EDA of all columns and noting the necessaries
10) Label-Encoding via mapping for the ordinal variables
11) Using heatmap to find and select features that correlate with SalePrice, at the same time checking for co-linearity
12) One-hot-Encoding for Nominal variables
13) Ensuring same no. of columns in both train and test datasets
14) Creating models with Linear Regression and regularize with Ridge, Lasso & Elastic Net
15) Picked top few variables by studying coefficients by Lasso, 
16) Ran another round of modelling to pick the model with highest score
17) Fitting and predicting SalePrice with the model made 
18) Submit to Kaggle.


### Problem Statement

To make a model that is predictive of the Sale Price of Housing in Ames using 'more useful' informations


