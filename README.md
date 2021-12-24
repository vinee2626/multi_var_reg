## This is a multivariate linear regression performed from scratch on a really small sample dataset to predict the sample flood risk based upon the average rainfall and elevation sample data.

To perform this regression analysis on the sample data, I chose the mathematical approach and used the formulas for performing the regression to gain a better understanding of the regression model, instead of implementing the black-box solution directly.
Although, I have also performed the regression using the sklearn library to cross-check and corroborate my model.

## the main operations performed in this small project are as follows :

- (a)plotting flood risk as a function of each variate.						
- (b)Then remove the biases, and standardize/normalize the data and replot the above. 												
- (c) in your final plot, use the new normalized anomaly data to perform a regression, noting the 						
    correlation coefficient and equation.						
- (d) perform a  residual analysis, and draw your conclusions from (a) to (d)	

## the steps involved throughout the whole process were :
 - Creating the dataFrame from the csv dataset and renaming the columns along with fixing the data-type of the columns for ease of use.
 - performing feature scaling on the dataset to avoid biases in the data and normalized the all the features so that all different magnitudes are scaled in range [0,1]
 - Then computed the normalized anomaly data to get the most accurate prediction.
 - Plotting the graphs for the normalized anomaly and identifying the correlation between the features.
 - Computing the regression mathematically by using the formulas and plugging in the values from the dataFrame.
 - calculating the intercept and the coefficients of the form y = b0 + b1x1 + b2x2 (best fitting line)
 - Made new predictions with the best fitting regression line recieved in the previous step.
 - Performed residual analysis to estimate the accuracy of predictions as compared to the labels.
 - Used the sklearn library to perform multivariate Linear regression.

