# House Price Prediction

The original database is available from StatLib

    http://lib.stat.cmu.edu/datasets/

The database has been imported from sklearn.datasets

The data contains 20,640 observations on 9 variables.

This dataset contains the average house value as target variable
and the following input variables (features): average income,
housing average age, average rooms, average bedrooms, population,
average occupation, latitude, and longitude in that order.

Target variable is the median house value for California districts,
expressed in hundreds of thousands of dollars ($100,000). This 
dataset was derived from the 1990 U.S. census, using one row per 
census block group. A block group is the smallest geographical unit 
for which the U.S. Census Bureau publishes sample data (a block group 
typically has a population of 600 to 3,000 people). A household is a
group of people residing within a home. Since the average number of 
rooms and bedrooms in this dataset are provided per household, these 
columns may take surprisingly large values for block groups with few 
households and many empty houses, such as vacation resorts.

I have used XGBoost regression model on this dataset and getting
r squared error value of 0.8445 on testing data with mean absolute error of 0.3030.

References
----------

Pace, R. Kelley and Ronald Barry, Sparse Spatial Autoregressions,
Statistics and Probability Letters, 33 (1997) 291-297.

"""
