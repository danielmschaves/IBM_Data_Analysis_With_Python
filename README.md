# Data Analysis with Python: House Sales in King County, USA
## Repository Overview
This repository provides a comprehensive data analysis on house sale prices in King County, which includes Seattle. The dataset contains information about houses sold between May 2014 and May 2015.

The goal of this project is to predict house prices using various features such as the number of bedrooms, bathrooms, square footage, and other variables.

## Phases
- Importing Data Sets: In this phase, we import the necessary libraries and load the dataset from the provided CSV file. We also display the first few rows of the dataset and check the data types of each column.

- Data Wrangling: During this phase, we clean and preprocess the data by dropping unnecessary columns, handling missing values, and replacing them with mean values of the respective columns.

- Exploratory Data Analysis: In this phase, we analyze the dataset by generating various visualizations like box plots and regression plots to understand the correlations between different features and the target variable, price.

- Model Development: In this phase, we develop various regression models using features identified during the exploratory data analysis. We create linear regression models and a pipeline to predict house prices and calculate the R^2 values for each model.

- Model Evaluation and Refinement: In the final phase, we evaluate the performance of our models by splitting the dataset into training and testing sets. We use Ridge regression and apply polynomial transformations to improve the performance of our models.

## Conclusion
Through this project, we have successfully developed and evaluated various regression models to predict house prices using different features. By refining our models and applying polynomial transformations, we have achieved better R^2 values, which indicate improved prediction accuracy.
