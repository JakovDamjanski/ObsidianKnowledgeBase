There are multiple ways to handle outliers, and here are some of the most common:
- deletion - completely remove the outlier datapoint
- transformation - transform all of the values, in order to reduce the distance between the outlier and the group. (Generally done by normalisation(scaling from 0:1), standardisation (turning the distribution of the variable into a standard normal distribution))
- truncation - all variables past a certain threshold are automatically sized down to it (there value is set to the value of the threshold).