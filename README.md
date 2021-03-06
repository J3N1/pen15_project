# Website
https://j3n1.github.io/pen15_project/html_template/

# Problem Statement 
We plan to predict home prices using data from the 1990 US Housing Census. 
The problem statement we're exploring is rising housing prices and unpredictability in the market. Using our machine learning model, we hope to educate others to be informed before purchasing their next home.

# Analysis
- Preprocessing the data which involved encoding and translating the data into numerical values
- Used the train test split to train the model into predicting values at 20% for our test size
- The closer the r2 score is closer to one the more accurate the prediction is. 
## Linear Regression
- The r2 scores for the y_test and the y_predict is 62.78% for the linear regression model.
## Decision Tree Regression
- The r2 scores for the y_test and the y_predict is 71.42% for the decision tree regression model.
## Random Forest Regression
- The r2 scores for the y_test and the y_predict is 81.56% for the random forest regression model.
## Lasso Regression
- The r2 scores for the x_test and the y_test is 71.93% for the lasso regression.
## Ridge Regression
- The r2 scores for the x_test and the y_test is 62.78% for the ridge regression.
## ElasticNet Regression
- The r2 scores for the x_test and the y_test is 9.47% for the elasticnet regression.

# Conclusion
- The Random Forest Regression model had the best prediction accuracy at a percentage of 81.56%. The ElasticNet Regression had the worst prediction accuracy at a percentage of 9.47% because it was the farthest from 100%. 