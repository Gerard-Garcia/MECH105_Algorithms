# Linear Regression Algorithm
## Created By: Gerard Garcia
### Goal:
Lets recap what you need to do. I'm only partly sorry for writing a problem that needs a table of contents and summary.
1. Filter outliers from your data set.
2. Compute the linear regression on your filtered data set.
3. Compute the  value from your filtered data and your linear regression function.
Here is the function specification. Name: linearRegression
Inputs: 
1. x-values of the data set
2. y-values of the data set
Outputs:
1. Filtered x-values (i.e. the input x-values but without the outlier points), sorted from smallest to largest
2. Filtered y-valeus (i.e. the input y-values but without the outlier points), sorted from smallest to largest
3. Slope from the linear regression (m in )
4. Intercept from the linear regression (b in )
5. Rsquared value
As usual, you can't use very many of the built in matlab functions that would make solving this problem too easy. I'll let you use the mean, median, and sort functions though.
### Inputs:
- x = x values for data set
- y = y values for data set
### Outputs:
- fX = x values with outliers removed
- fY = y values with outliers removed
- slope = slope from linear regression
- intercept = intercept from linear regression
- Rsquared = coefficient of determination, R^2
