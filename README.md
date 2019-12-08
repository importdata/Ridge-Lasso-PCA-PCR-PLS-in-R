# Ridge-Lasso-PCA-PCR-PLS-in-R

Task 1:
- Dataset: Consider the Caravan dataset which is a part of the ISLR package. The dataset consists of Purchase, indicating whether or not a given individual purchases a caravan insurance policy, and 85 predictors that measure demographic characteristics of 5,822 individuals.
- Standardized the data set
- Created a test set consisting of the first 1,000 observations and training set consisting of the remaining observations. Use the test data to optimally choose the penalty parameter of a shrinkage method.
- Fitted a logistic regression model using the usual maximum likelihood method. Rather than using 0.5 as the cut-off, predict that a person will make the purchase if the estimated probability of purchase is greater than 0.2. Compute the confusion matrix, sensitivity, specificity, and overall misclassification rate based on the test data.
- Repeated the above using logistic regression, where the model is fit using a penalized maximum likelihood method with ridge penalty.
- Repeated the above using logistic regression, where the model is fit using a penalized maximum likelihood method with lasso penalty.

Task 2:
- Dataset: Consider the data presented in the file mali.csv. These data were collected in a survey as part of a study to assess options for enhancing food security through the sustainable use of natural resources in the Sikasso region of Mali (West Africa). A total of n = 76 farmers were surveyed and observations on the following 9 variables were recorded.
- Standardized the data set
- Performed a principal components analysis (PCA) of the data.
- Created a table showing the correlations of the standardized variables with the components and the cumulative percentage of the total variability explained by the two components. Also, displayed the scores on the two components and the loadings on them using a biplot.

Task 3:
- Dataset: Auto dataset in ISLR package. 
- Fitted a linear model using the least squares method.
- Repeated the above using best-subset selection.
- Repeated the above using ridge regression.
- Repeated the above using lasso.
- Repeated the above using PCR.
- Repeated the above using PLS.
- Made a summary of the parameter estimates and test error rates and compared the results.



