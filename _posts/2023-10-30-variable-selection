### Variable Selection for Regression

Variable selection is aan instrumental part to building regression models. With large amounts of data collected, picking too few variables will result in a model that will not be optimal, and too many variables will result in a model that is overspecified.

Some of the ways in which variables can be selected include forward selection and backwards elimination. In forward selection, the base is an empty model with just an intercept, and each variable is added and tested by a judgement criteria, and the best-performing variable is added. When no additional variables will perform better than the current model, the process stops, and the current model is the final model. 

Backwards elimination works the same way, except that the base model contains all variables, and variables are procedurely removed until any further variable removal would result in a worse model.

Stepwise regression incorporates both forwards and backwards regression, and stops when neither adding nor eliminating a variable will increase the model's performance.

The all-possible subsets method tests each possible subset of variables and returns the best performing model. This guarantees a mdoel of best fit but requires a lot of computation power.

There are multiple metrics that can be used to measure the preformance of a regression model. This includes the coefficient of determination r-squared, adjusted r-squared, which punishes based on number of variables selected, Mallow's Cp, as well as various information criteria, including AIC (Akaike Information Criteria) and BIC (Bayesian Information Criteria).

When I preform linear regression I tend to use stepwise regression, as it does not require a heavy amount of overhead while still having range to produce quality results.
