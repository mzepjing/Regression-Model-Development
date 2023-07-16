# Regression-Model-Development

# Project Summary

## Introduction
- Meal kits have gained popularity in the US due to convenience and healthy options.
- The goal is to forecast future revenue in the meal kit industry using a regression model.

## Step 1: Explore the Data
- Visualize the data to identify patterns, trends, and outliers.
- Most data is numerical, with a few irrelevant columns and missing data.
- Identify the data types of each variable and develop a histogram for the distribution of the dependent variable (revenue).
- Analyze the correlation between each feature and revenue.

## Step 2: Feature Engineering
- Refine the data to improve the accuracy and performance of the regression model.
- Create new variables such as total meals ordered and unique meals purchased ratio.
- Sort email domains for targeting specific demographics.
- Transform continuous data, including log transformation, to improve linearity and normalize the data.

## Step 3: Regression Model
- Use a regression model to predict revenue.
- Determine the statistical significance of predictor variables using p-values.
- Exclude variables with p-values higher than 0.05 from the model.
- Evaluate the performance of the model using testing scores.
- Consider applying regularization or pruning techniques to improve generalization performance.

## Final Result
- The Unpruned GBM model performs well on the test dataset with a testing score of 0.8085.
- However, there is a slight overfitting issue, indicated by the gap between the training and testing scores.
- Applying regularization or pruning techniques may enhance the model's generalization performance.
