# Data Analysis with Python: House Sales in King County, USA
## Repository Overview
This repository provides a comprehensive data analysis on house sale prices in King County, which includes Seattle. The dataset contains information about houses sold between May 2014 and May 2015.

The goal of this project is to predict house prices using various features such as the number of bedrooms, bathrooms, square footage, and other variables.

## Phases
- Importing Data Sets: In this phase, I imported the necessary libraries and load the dataset from the provided CSV file. I also displayed the first few rows of the dataset and checked the data types of each column.

- Data Wrangling: During this phase, I cleaned and preprocessed the data by dropping unnecessary columns, handling missing values, and replacing them with mean values of the respective columns.

- Exploratory Data Analysis: In this phase, I analyzed the dataset by generating various visualizations like box plots and regression plots to understand the correlations between different features and the target variable, price.

- Model Development: In this phase, I developed various regression models using features identified during the exploratory data analysis. I created linear regression models and a pipeline to predict house prices and calculate the R^2 values for each model.

- Model Evaluation and Refinement: In the final phase, I evaluated the performance of our models by splitting the dataset into training and testing sets. I used Ridge regression and apply polynomial transformations to improve the performance of our models.

## Conclusion
Through this project, I have successfully developed and evaluated various regression models to predict house prices using different features. By refining the model and applying polynomial transformations, I have achieved better R^2 values, which indicate improved prediction accuracy. Based on the R^2 scores obtained from the various models, we can observe the following:

- Simple Linear Regression: The R^2 score for this model is relatively low, indicating that the single predictor does not provide a strong explanation for the variance in the dependent variable (price).

- Multiple Linear Regression: The R^2 score is higher compared to the Simple Linear Regression model, suggesting that using multiple features to predict the target variable results in a better fit and improved predictive performance.

- Pipeline Model: This model's R^2 score is very close to the Multiple Linear Regression model, indicating that the use of feature scaling and preprocessing in the pipeline has not significantly affected the predictive performance.

- Ridge Regression: The R^2 score for Ridge Regression is lower than the Multiple Linear Regression model, which implies that the regularization term has not improved the model's performance on the test data.

- Polynomial Ridge Regression: The R^2 score for this model is the highest among all the models. By transforming the data into higher-order polynomial features and using Ridge Regression, the model has achieved a better fit and predictive performance on the test data.

| Model  | R^2 Score |
| ------------- | ------------- |
| Simple Linear Regression  | 0.492853  |
| Multiple Linear Regression	  | 0.657695  |
| Pipeline Model	  | 0.751340  |
| Ridge Regression	  | 0.647876  |
| Polynomial Ridge Regression	  | 0.700274  |

In summary, the Polynomial Ridge Regression model has the highest R^2 score, indicating that it is the most successful in predicting the target variable (price) among the evaluated models. This suggests that incorporating polynomial features and regularization can help improve the performance of the model on the test dataset. However, it is essential to consider other factors, such as model complexity, interpretability, and training time, before selecting the best model for a specific application.
