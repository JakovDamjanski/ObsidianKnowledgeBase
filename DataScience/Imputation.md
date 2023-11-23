There is a myriad of different ways to impute missing values and here are some of the most common approaches: 
- **Statistical properties**-Impute the mean, median or mode for all missing values in a variable
- **Indicator of missingness** - Create a new variable that is an indicator of missingness, and include it in any model to predict the response (plug in zero or the mean in the actual variable).
- **Hot deck imputation** - for each missing entry randomly select an observed value from the other non missing entries and put it as it's value.
- **Model the imputation** - predict the value of the missing predictors by training models from the other predictors.
- **Model the imputation with uncertainty** - impute the same as the other but we combine the output of our model with a randomly generated number (to serve as an uncertainty metric and to better distinguish between two entries with missing values and identical values for the other attributes ).  