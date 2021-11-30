# Google-Analytics-Customer-Revenue-Prediction
## Predict how much GStore customers will spend

The 80/20 rule has proven true for many businesses–only a small percentage of customers produce most of the revenue. As such, marketing teams are challenged to make appropriate investments in promotional strategies.

In this competition, you’re challenged to analyze a Google Merchandise Store (also known as GStore, where Google swag is sold) customer dataset to predict revenue per customer. Hopefully, the outcome will be more actionable operational changes and a better use of marketing budgets for those companies who choose to use data analysis on top of GA data.


## Root Mean Squared Error (RMSE)
Submissions are scored on the root mean squared error metric. RMSE is defined as:
### sqrt(Sum(y-yhat)^2/n)
where y hat is the natural log of the predicted revenue for a customer and y is the natural log of the actual summed revenue value plus one.
