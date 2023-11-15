# Data Analysis with R

____
<ins>Introduction to Probability and Data with R <ins><div>
____
*Concepts*

  - Quantitative vs Qualitative Data (Continuous, Discrete, Ordinal)
  - Sampling and Bias (Methods and Sources of Bias)
  - Experimental Design
  - Random Sample and Generalizable Qualities
  - Visualizations (Histogram, Scatter Plot, Box Plot, Dot Plot, Intensity Map)
  - Measures of Data (Center and Spread)
  - Data Transformation (Natural Log and Square Roots)
  - Statistical Inference (Null/Alt Hypothesis)
  - Probability
    - Frequrentist Interpretation
    - Bayesian Interpretation
    - Law of Large Numbers
    - Gambler's Fallacy
    - Disjoint/Non-Disjoint
    - Baye's Theorem
    - Probability Trees
    - Bayesian Inference
  - Distribution
    - Normal Distribution (z-score, percentile)
    - Binomial Distribution
      
*R Codes*
  - Loading Data and Packages
  - data()
  - dim()
  - names()
  - ggplot() (geom_point(), geom_line(), geom_histogram(), geom_boxplot(), geom_bar())
  - mutate()
  - str()
  - filter()
  - summarise()
  - grou_by()
  - arrange(desc())
  - sample()
  - table()
  - pnorm()
  - qnorm()
  - dbinom()

___
<ins>Inferential Statistics<ins>
___
*Concepts*
  - Central Limit Theorem
  - Sample vs Sampling Distribution
  - Confidence Interval (mean)
    - Critical Values
    - Conditions
  - Calculating the sample size for targetd margin of error
  - Hypothesis Testing
    - p-value
    - two-sided test
    - one-sided test
  - Significance
    - Point Estimation NOtation
  - Decision Errors
    - Type 1 vs Type 2
    - Error Rate
    - Minimizing Type 1 and Type 2 error rate
  - T-Distribution
    - T-Statistic
    - T-Distribution for one mean
    - T-Distribution with point estimation
    - T-Distribution for two means
    - T-Distribution with point estimation for two means
    - T-distribution for Paird means
  - Power
  - ANOVA
    - F-Distribution
    - Sum of Squares Total
    - Sum of Squares Group
    - Sum of Squares Error
    - Degrees of Freedom
    - Mean Square Error
    - F-value
    - P-value
    - Conditions
  - Modified Significance Level for Multiple Comparisons
  - Bootstrapping
    - Percentile Method
    - Standard Error Method
  - Categorical Variable Inferences
    - Sampling Variability and Central Limit Theorem for Proportions
    - Confidence Interval for Proportions
    - Hypothesis test for Single categorical Variable
    - Confidence Interval for Two proportions
    - Estimating Difference between two proportions
    - Hypothesis test for two categorical variables
  - Simulation Based Inference for Proportions
    - Inference vs Simulation
  - Chi-Squared Test
    - Chi Squared Goodness of Fit
    - Chi Squared Test of Independence
    - 
  
*R Codes*
  - boxplot()
  - summary()
  - by()
  - inference()
  - t.test()
  - slice()
  - data.frame()
  - ggplot( geom_vline()
  - quantile()
  - subset()

____
<ins>Linear Regression and Modeling<ins>
____
*Concepts*
  - Correlation
  - Residuals
  - Lease Squares Fit
  - Conditions for Linear Regression
  - R-Squared
  - Regression with Categorical Variables
  - Outliesr and Regression
    - Hypothesis Testing for linear regression
    - Variability Partitioning (ANOVA)
  - Multiple Regressions
    - Predictors
    - Adjusted R-Squared
    - Collinearity and Parsimony
    - Inference for MLR
    - Model Selection (Stepwise Model Selection)
      - Backwards Eliminatio (adjusted R^2 and P-value)
      - Forward Selection (adjusted R^2 and P-value
        
*R Codes*
  - plot()
  - abline()
  - scatterplot()
  - list()
  - plot_ss()
  - lm()
  - ggplot( stat_smooth(), geom_hline(), geom_jitter())
  - dataset$residual
  - plot(), points() to layer on multiple data groups on a graph
  - hist()
  - qqnorm()
  - qqline()
  - predict()
  - 

