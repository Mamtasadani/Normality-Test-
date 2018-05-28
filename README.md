# Normality-Test-
In statistics, normality tests are used to determine if a data set is well-modeled by a normal distribution and to compute how likely it is for a random variable underlying the data set to be normally distributed.

Normality tests of univariate dataset include the following tests:
1. Shapiro–Wilk test,
2. D'Agostino's K-squared test, 
3. Anderson–Darling test,
4. Cramér–von Mises criterion,
5. Lilliefors test,
6. Kolmogorov–Smirnov test,
7. Jarque–Bera test, and
8. Pearson's chi-squared test.

I have used only first three tests.
The Shapiro-Wilk test is a way to tell if a random sample comes from a normal distribution. The test gives you a W value; small values indicate your sample is not normally distributed (you can reject the null hypothesis that your population is normally distributed if your values are under a certain threshold). The formula for the W value is:
 
where:
xi are the ordered random sample values
ai are constants generated from the covariance’s, variances and means of the sample (size n) from a normally distributed sample.
The test has limitations, most importantly that the test has a bias by sample size. The larger the sample, the more likely you’ll get a statistically significant result.

D'Agostino's K-squared test
The test is based on transformations of the sample kurtosis and skewness, and has power only against the alternatives that the distribution is skewed and/or kurtic.

The Anderson-Darling test is used to test if a sample of data came from a population with a specific distribution. It is a modification of the Kolmogorov-Smirnov (K-S) test and gives more weight to the tails than does the K-S test. The K-S test is distribution free in the sense that the critical values do not depend on the specific distribution being tested. The Anderson-Darling test makes use of the specific distribution in calculating critical values. This has the advantage of allowing a more sensitive test and the disadvantage that critical values must be calculated for each distribution.





Source of Dataset : https://archive.ics.uci.edu/ml/datasets/Cryotherapy+Dataset+
