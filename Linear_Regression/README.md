# Linear Regression Script
---
* This MATLAB algorithm filters outliers from a given x,y data set, computes the linear regression on the filtered data set and computes the r-squared value from the filtered data and the calculated linear regression function. It is useful for creating trendlines and observing trends occuring in data sets while also removing any potential erroneous data.
---
# Function Name: linearRegression
## Function Format: linearRegression(x,y)
### Inputs:
 - x: x-values of the data set
 - y: y-values of the data set

### Outputs:
 - fX: Filtered x-values (i.e. the input x-values but without the outlier points), sorted from smallest to largest
 - fY: Filtered y-values (i.e. the input y-values but without the outlier points), sorted from smallest to largest
 - slope: Slope from the linear regression (m in f(x)=mx+b)
 - intercept: Intercept from the linear regression (b in f(x)=mx+b)
 - Rsquared: Rsquared value
