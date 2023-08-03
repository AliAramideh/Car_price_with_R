# Car_price_with_R
Analysis and predict the price of car using R language.

To underestand the dataset please observe `Data Dictionary - carprices.xlsx'.

The following things have been done in this project.
## Load and preprocessing of the dataset
- Plot a boxplot for three selected columns from the dataset of our choice and explain it.
- Address the issue of missing values (we are not allowed to remove any data). Explain our method and the reason behind it.
- Plot a correlation map of the dataset features and propose four hypotheses about the correlation between the features. Test them using the t-test.
- Define dummy variables for categorical data and add them to the dataset.
- Use a selected subset of the available data as the test set and the remaining data as the training set. Explain the ratio of this division.
- Based on the correlation map and the obtained values, predict which features are more influential and which ones have a weaker causal effect on the response variable.

## Processing data with a multiple regression model

In this section, we are required to fit a multiple regression model to the training data. The goal is to perform this task and analyze the results afterward.

- First, fit the model to the training data and report the following measures for both datasets:
  - RSS (Residual Sum of Squares)
  - TSS (Total Sum of Squares)
  - MSE (Mean Squared Error)
  - R-squared
  - Adjusted R-squared

- Explain what each of these measures represents and where they are applicable.

- Plot a comparison map of the coefficient magnitudes. Does a larger coefficient imply higher significance? What if the data scales are the same? Analyze the results.

- Describe the performance of the model on the test data. Explain what can be done to improve this performance (consider interpretability and predictive capability of the model).

## Feature Selection and Analysis

In this section, we need to utilize the results from the previous sections and statistical tests to select important features and improve the performance of our model.

- Based on the t-tests and p-values using the method of your choice, reduce the number of features to a few that would improve the interpretability of your model. How does the performance of your model change in predicting? How do the mentioned metrics change? Explain the reason for selecting your method.

- Perform feature selection using ANOVA and f-statistics and output the top 10 features.

## Other Models (Optional)

Fit a interpretable model on the data and report its results.
