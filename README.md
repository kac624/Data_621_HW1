# Overview
In this homework assignment, you will explore, analyze and model a data set containing approximately 2200
records. Each record represents a professional baseball team from the years 1871 to 2006 inclusive. Each record
has the performance of the team for the given year, with all of the statistics adjusted to match the performance of
a 162 game season.
Your objective is to build a multiple linear regression model on the training data to predict the number of wins
for the team. You can only use the variables given to you (or variables that you derive from the variables
provided). 
## Deliverables:
 A write-up submitted in PDF format. Your write-up should have four sections. Each one is described
below. You may assume you are addressing me as a fellow data scientist, so do not need to shy away
from technical details.
 Assigned predictions (the number of wins for the team) for the evaluation data set.
 Include your R statistical programming code in an Appendix.
Write Up:
### 1. DATA EXPLORATION (25 Points)
Describe the size and the variables in the moneyball training data set. Consider that too much detail will cause a
manager to lose interest while too little detail will make the manager consider that you aren’t doing your job. Some
suggestions are given below. Please do NOT treat this as a check list of things to do to complete the assignment.
You should have your own thoughts on what to tell the boss. These are just ideas.
a. Mean / Standard Deviation / Median
b. Bar Chart or Box Plot of the data
c. Is the data correlated to the target variable (or to other variables?)
d. Are any of the variables missing and need to be imputed “fixed”?
### 2. DATA PREPARATION (25 Points)
Describe how you have transformed the data by changing the original variables or creating new variables. If you
did transform the data or create new variables, discuss why you did this. Here are some possible transformations.
a. Fix missing values (maybe with a Mean or Median value)
b. Create flags to suggest if a variable was missing
c. Transform data by putting it into buckets
d. Mathematical transforms such as log or square root (or use Box-Cox)
e. Combine variables (such as ratios or adding or multiplying) to create new variables
### 3. BUILD MODELS (25 Points)
Using the training data set, build at least three different multiple linear regression models, using different variables
(or the same variables with different transformations). Since we have not yet covered automated variable
selection methods, you should select the variables manually (unless you previously learned Forward or Stepwise
selection, etc.). Since you manually selected a variable for inclusion into the model or exclusion into the model,
indicate why this was done.
Discuss the coefficients in the models, do they make sense? For example, if a team hits a lot of Home Runs, it
would be reasonably expected that such a team would win more games. However, if the coefficient is negative
(suggesting that the team would lose more games), then that needs to be discussed. Are you keeping the model
even though it is counter intuitive? Why? The boss needs to know.
### 4. SELECT MODELS (25 Points)
Decide on the criteria for selecting the best multiple linear regression model. Will you select a model with slightly
worse performance if it makes more sense or is more parsimonious? Discuss why you selected your model.
For the multiple linear regression model, will you use a metric such as Adjusted R2, RMSE, etc.? Be sure to
explain how you can make inferences from the model, discuss multi-collinearity issues (if any), and discuss other
relevant model output. Using the training data set, evaluate the multiple linear regression model based on (a)
mean squared error, (b) R2, (c) F-statistic, and (d) residual plots. Make predictions using the evaluation data set.
