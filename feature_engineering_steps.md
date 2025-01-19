# Feature Engineering Steps

## Identification of Attribute Types

1. Loaded the dataset using pandas.
2. Displayed the first few rows of the dataset to understand its structure.
3. Identified the types of each attribute in the dataset.

## Handling Missing Data

1. Checked for missing data in the dataset.
2. Identified columns with missing data and the number of missing data points.
3. Imputed missing data with the mean for numeric columns and mode for categorical columns.
4. Provided explanations for handling missing data to ensure the integrity of the dataset.

## Normalization of Numeric Attributes

1. Identified numeric attributes in the dataset.
2. Performed normalization by scaling numeric attributes to have a mean of 0 and a standard deviation of 1.
3. Provided explanations for normalization to improve the performance of machine learning algorithms.

## Analysis of the 5 Most Expensive Cities and Cities with Maximum Unique Zip Codes

1. Analyzed the 5 most expensive cities based on average house price.
2. Analyzed the 5 cities with the maximum number of unique zip codes.
3. Provided explanations for the analysis to understand the distribution of house prices and the diversity of locations.

## Proximity Measures

1. Calculated the proximity measure between house_type and sqm.
2. Calculated the proximity measure between house_type and purchase_price.
3. Calculated the proximity measure between no_rooms and purchase_price.
4. Provided explanations for proximity measures to understand the relationship between different attributes.
5. Calculated Euclidean distance between numeric columns.
6. Calculated Manhattan distance between numeric columns.
7. Calculated Cosine similarity between numeric columns.
8. Calculated Mahalanobis distance between numeric columns.
9. Created a dissimilarity matrix for categorical columns.

## Feature Selection

1. Defined independent variables and the target variable.
2. Applied SelectKBest with f_regression to select the top 5 features.
3. Applied SelectKBest with mutual_info_regression to select the top 5 features.
4. Applied the correlation method to identify relevant features.
5. Applied Pearson coefficient to identify relevant features.
6. Applied Recursive Feature Elimination (RFE) to select the top 5 features.
7. Provided explanations for feature selection to identify the most relevant features for predicting the target variable.

## Comparison of Feature Selection Methods

1. Compared the top 5 features from each feature selection method.
2. Provided explanations for the comparison to understand the consistency and differences between the methods.

## Correlation Plot

1. Plotted the correlation between independent features and the target variable.
2. Provided explanations for the correlation plot to visualize the relationship between different features and the target variable.

## Visualizations and Other Plots for Analysis and Data Preprocessing

1. Created a histogram to visualize the distribution of purchase prices.
2. Created a boxplot to visualize the purchase prices by house type.
3. Created a scatter plot to visualize the relationship between sqm and purchase price.
4. Provided explanations for visualizations to understand the distribution and relationships of different attributes.

## Handling Outliers

1. Calculated z-scores for numeric columns.
2. Identified outliers based on z-scores.
3. Removed outliers from the dataset.
4. Provided explanations for using the z-score approach to handle outliers.

## Techniques Used in Feature Engineering

1. Identification of attribute types.
2. Handling missing data using imputation.
3. Normalization of numeric attributes.
4. Analysis of most expensive cities and cities with maximum unique zip codes.
5. Proximity measures between specified columns.
6. Feature selection using filter methods (f_regression, mutual_info_regression, correlation, Pearson coefficient, RFE).
7. Comparison of feature selection methods.
8. Correlation plot.
9. Visualizations (histograms, boxplots, scatter plots).
10. Handling outliers using the z-score approach.

## Additional Regression Models and Evaluation

1. Implemented and evaluated additional regression models, including Ridge Regression, Lasso Regression, Elastic Net Regression, Decision Tree Regression, Random Forest Regression, Gradient Boosting Regression, Support Vector Regression (SVR), and K-Nearest Neighbors Regression (KNN).
2. Provided detailed explanations for each model and their evaluation.
3. Compared the performance of different regression models using metrics such as Mean Squared Error (MSE) and R-squared (R2) score.
4. Provided visualizations to compare the performance of different regression models.
