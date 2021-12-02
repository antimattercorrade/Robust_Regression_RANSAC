# Robust Regression For Curve Fitting ⭐

Robust regression is a type of regression analysis in robust statistics that is intended to overcome some of the limitations of traditional parametric and non-parametric methods. The goal of regression analysis is to determine the relationship between one or more independent variables and one or more dependent variables. Certain commonly used regression methods, such as ordinary least squares, have favourable properties when their underlying assumptions are true, but can produce misleading results when those assumptions are violated; thus, ordinary least squares is said to be not robust to assumptions violations. Least squares estimates for regression models, in particular, are extremely sensitive to outliers. While no precise definition exists, outliers are observations that do not follow the pattern of the other observations. This is not normally
a problem if the outlier is simply an extreme observation drawn from the tail of a normal distribution; however, if the outlier is the result of non-normal measurement error or some other violation of standard ordinary least squares assumptions, the validity of the regression results is jeopardised if a non-robust regression technique is used.

## Random Sample Consensus (RANSAC) 🔥

RANSAC is used for parameter estimation of the model because of its robustness, i.e. the number of outliers in the data provided does not adversely affect the accuracy of the prediction results. Although, increase accuracy is accompanied by a increase in computation times and a pre-determined threshold but when time is not a constraint, RANSAC provides much better parameter prediction than simple Linear Regression. RANSAC is preferred over other sampling techniques for robust estimation because it uses minimum possible observations for estimating the model parameters.

RANSAC samples minimum number of data points to estimate the model parameters as an initial guess and then tries to maximize the number of inliers and minimize the outliers to improve the accuracy for estimating model parameters. Every iteration the sampled model is tested to fit the original data by calculating the error in the estimated values and the model that best fits the given data (least error) is returned as the result. During each iteration the max iterations are also adjusted to account for the case when the inlier count is sufficiently reached and the algorithm is stopped to save resources.


## Instructions to Run :runner:

* The dataset is being downloaded from the given hashed link. 

* To run, open the colab file and select the image using the slider given. Then run the corresponding cells to get the results.

## References and Credits 💳

1) Ransom Sample Consensus (RANSAC)
- https://en.wikipedia.org/wiki/Random_sample_consensus
