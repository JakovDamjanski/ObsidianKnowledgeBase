MCAR and MAR are cases that are easy to handle with imputation.
MNAR on the other hand is impossible to handle properly. It's good to incorporate a missingness indicator variable in each entry, if the missing value is a predictor.

The main way we handle MCAR and MAR is either by dropping entries (deleting them), or through [[Imputation]].