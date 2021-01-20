# Predicting-Bat-Bite-Force
Compares XGBoost regressor with linear regression in predicting maximum bite force in bats.

### Methods Used

* Machine Learning
* Data Visualization
* Predictive Modeling
* XGBoost Regressor
* Linear Regression


### Technologies

* Jupyter Notebook
* Python
* Pandas and Numpy
* Scikit-Learn
* Seaborn and Matplotlib

### Data was obtained from:

Senawi, Juliana; Schmieder, Daniela; Siemers, Björn; Kingston, Tigga (2016), Beyond size – morphological predictors
of bite force in a diverse insectivorous bat assemblage from Malaysia.

Dataset:
https://doi.org/10.5061/dryad.q2n24

## Project Summary

Data was explored and analyzed. After cross validation maximized at 330 boosted rounds, the XGBoost tree model regressor
had a RMSE of 2.0482. This is compared to a linear regression model with a RMSE of 3.203. 
In the boosted tree regressor, the most important feature in the prediction of bite force was the length of the arm of the bat,
followed by weight and head length.
 
