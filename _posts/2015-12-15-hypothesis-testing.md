---
inFeed: false
hasPage: true
inNav: false
inLanguage: null
starred: false
keywords: []
description: ''
datePublished: '2015-12-15T17:47:46.962Z'
dateModified: '2015-12-15T17:47:39.269Z'
title: Hypothesis Testing
author: []
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
sourcePath: _posts/2015-12-15-hypothesis-testing.md
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
* Significance level 𝛂 = 5% means 'probability of making Type I error (rejecting true null) is 5%'
* Reject null if p-value 
* Type II error is minimised by collecting strong data and choosing powerful tests

Types of hypotheses:

* Two-tailed: null (=), alternative (≠), for ratio, interval and dichotomy
* One-tailed: null (≤ or ≥), alternative ( or 

**One-sample tests:**

* To test for representativeness, or compare variable with benchmark number
* E.g. Is sample of mean 2.92 representative of reported average household size of 2.75?

Null: hhsize = 2.75  
Alternative: hhsize ≠ 2.75  
Test: Ratio T-test (mean) with test statistic 2.92 - 2.75 = +/-1.607  
Two-tailed: Sig. = 11% cannot reject null representative
* Reminder:  
Larger test statistic = smaller p-value (Graph)  
Ratio, interval and dichotomy = one or two-tailed (if one-tailed, divide SPSS p-value by 2)  
Ordinal and nominal (MC) = one-tailed (no need to divide)

**Independent samples test:**

* Compare variable (brand A evaluation) between different samples (e.g. men vs. women)

**Paired samples test:**

* Compare 2 or more variables (brand A and B evaluations) within same respondents

Choosing the right test:

* Determine:   
measurement level of **variable of interest **(choose the variable with higher level)  
sample  
K (no. of groups for independent // no. of variables for paired) (determined by the other variable)

* When comparing more than 2 groups/variables, k 2  
Always use one-tailed test because cannot compare larger or smaller with 3 groups

# Regression