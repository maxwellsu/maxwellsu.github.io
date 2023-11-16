### Diabetes Data Analysis

I recently collaborated on an analysis of diabetes data: <https://sarahpagan.github.io/558-project3/>

In this analysis various predictors were used to predict the presence of diabetes in patients. Data was taken from the 2015 Behavioral Risk Factor Surveillance System survey. The data was then transformed into a more usable form, and then partitioned into training and testing datasets.

The data analysis was split into multiple parts based on the educational level of the subjects. After performing EDA on the data to aid in variable selection, various models were fit to determine the best fit for the data. These included logistic regression, LASSO regression, classification trees, random forest, linear discriminant analysis, and conditional inference trees. Models were judged on the resulting log loss from fitting the model to the testing data.

On reflection, some changes could include modifications to the ways that variables were processed, and the addition of other candidtate models, including support vector machines and naive bayes classification. Some of the difficulty arose from variable selection, and the biggest takeaway is just how many methods to build classification models are, and that many should examined and tested in order to determine the best.

Link to github repository: <https://github.com/sarahpagan/558-project3>
