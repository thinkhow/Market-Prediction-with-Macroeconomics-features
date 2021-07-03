# Final Modeling Jupyter Notebooks

## Scenario 1 Model Selection

We try to predict future S&P 500 prices using past index prices.
We ran several models at the beginning of the project and included the following in our final code: FB Prophet, ARIMA, and a random forest model.
The most successsful model at this stage was the FB Prophet model.

## Scenario 1

We split the total dataset into the training and testing part, where testing data contains 252 samples (~ trading days in a year) and training data contains total data minus 252 samples. We use the first samples (~ total data minus 2520) as training1 in the training data to fit the Facebook prophet model and make predictions on the data set training2 (~ 2300 samples). On training2, we also incorporate macroeconomic features to fit a linear model. Finally, we make predictions on testing.

## Scenario 2

We try to improve FB Prophet. 
Specifically, we try to find coefficients for a linear model that minimizes the difference between actual S&P 500 prices and the FB Prophet predictions. 
Our features are macroeconomic data, and we later included some interaction terms between those linear features.

## General Notes

In both scenarios, we focus on using macroeconomic data (unemployment rate, federal funding rate, earning-per-share, etc.), rather than market data (price-to-earnings ratio, other stock prices, etc.).
