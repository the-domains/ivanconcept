---
inFeed: false
hasPage: true
inNav: false
inLanguage: null
starred: false
keywords: []
description: ''
datePublished: '2015-12-16T06:24:05.480Z'
dateModified: '2015-12-16T06:23:51.190Z'
title: Hypothesis Testing
author: []
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
sourcePath: _posts/2015-12-16-hypothesis-testing.md
published: true
url: hypothesis-testing/index.html
_type: Blurb

---
# Hypothesis Testing

Purpose:

* Assume hypothesis is true, find out how likely is the outcome based on the hypothesis

Remember:

* Null always '='
* Alternative always '≠'
* Significance level (𝛂) = 5% means 'probability of making Type I error (rejecting true null) is 5%'
* Reject null if p-value 
* Type II error is minimised by collecting strong data and choosing powerful tests

Types of hypotheses:

* Two-tailed: null (=), alternative (≠), for ratio, interval and dichotomy
* One-tailed: null (≤ or ≥), alternative ( or 

One-sample test

* To test for representativeness, or compare variable with benchmark number
* E.g. Is sample of mean 2.92 representative of reported average household size of 2.75?
  * Null: hhsize = 2.75
  * Alternative: hhsize ≠ 2.75
  * Test: Ratio T-test (mean) with test statistic 2.92 - 2.75 = +/-1.607
  * Two-tailed: Sig. = 11% cannot reject null representative

* Reminder:
  * Larger test statistic = smaller p-value (Graph)
  * Ratio, interval and dichotomy = one or two-tailed (if one-tailed, divide SPSS p-value by 2)
  * Ordinal and nominal (MC) = one-tailed (no need to divide)

Independent samples test:

* Compare variable (brand A evaluation) between different samples (e.g. men vs. women)

Paired samples test:

* Compare 2 or more variables (brand A and B evaluations) within same respondents

Choosing the right test:

* Determine:
  * measurement level of variable of interest (choose the variable with higher level)
  * sample
  * K (no. of groups for independent // no. of variables for paired) (determined by the other variable)

* When comparing more than 2 groups/variables (k 2), Always use one-tailed test because cannot compare larger or smaller with 3 groups

# Regression

Why?

* Lower prices lead to higher sales
* But sales also go up due to seasonal demand, and down due to anticipation effect (people delay purchase until end-of-season sales) and post-promotion effect (stock-piling)
* Sales might also go up due to features and display
* Regression can help us find out how many unit sales can we increase by dropping $1

Correlation coefficient (r): strength of relationship between X and Y

* Pearson: interval or ratio
* Spearman: one of the variables is ordinal

Regression analysis: measures effect of X on Y

Step 1: Model specification

* Y: interval or ratio
* X: interval, ratio or dichotomy

* Regression model: Y = βo + β1X1 + β2X2 + ... + error

* Dummy coding (when IVs are nominal (MC) or ordinal)

* Interaction effects
  * E.g. If effectiveness of features depends on display:
  * Moderating high (display = 1)
    * Model: Y = βo + β1Price + β2Feature + β3Display + β4Display\*Feature + error
  * Moderating low (display = 0)
    * Model: Y = βo + β1Price + β2Feature + error
  * Calculate feature = 1 and = 0 for the two cases

Step 2: Model estimation

* Assign numerical values to model parameters: βo, β1

Step 3: Model validation

* Statistical validity

* Significance of model (ANOVA) - p-value

* Model fit (R²) - how many % of change in Y is explained by X

* Significance of parameters
  * Unstandardised beta: used for forecasting
  * Standardised beta: determine more important variables (only look at magnitude)

* Multicollinearity
  * IVs are correlated, making estimates of β unreliable and insignificant
  * Diagnosed through graphs, correlation matrix and VIF (Variance Inflation Factor)
    * If VIF 
    * If VIF 10, collect new and better data, or remove some IVs

* Face validity

Forecasting

* 95% confidence interval of forecast = expected Y + 2 × SE
* Interpolation: forecasting within range
* Extrapolation: forecasting outside range (may not be linear outside)