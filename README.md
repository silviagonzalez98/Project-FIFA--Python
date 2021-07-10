# FIFA Project

## Objective of the project
- Understand all the python concepts and apply them in a real data project
- Create a linear regression model to predict the market value of a player

## Explanation of how the data was processed 
The data has been analyzed and and then properly categorized. 
1) Null data. Null values in numericals have been replaced with mean of the column (except 'loan_date' column deletion due to high number of nulls).
2) Column types. Columns needed to delete specific characters (Currency, weight and height) to transition to numerical type
3) Choose variables. Selected a total of 60 out of 107 in the model based on correlation model and non-repeated/redundant information.

### Cleaning 
1) Checked and removed outliers from numerical columns to create a proper linear regression model.
2) Finally normalized the dataframe

### Linear Regression Results
Positively, the result of the Linear Regression Model has been of 0.9, maintaining more than 50% of the original columns in order to not lose a high amount of data.

## Libraries 
For this project, I used Python including following libraries:
- pandas
- matplotlib
- seaborn
- scipy.stats
- os
- statsmodels.api
- sklearn
