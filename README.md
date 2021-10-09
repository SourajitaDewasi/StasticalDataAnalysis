# StasticalDataAnalysis
Implementation, Visualization and Analysis of Stastical Data

<hr>
<p>

## T-TEST
Inferential stastic used to determine if there between the means of two groups/distribution.

It's of two types: 
1. One-sampled T-test - The test will tell us whether the means of the sample and the population are different.
2. Two-sampled T-test - The test compares the means of two independent groups in order to determine whether their associated population means are different.

## PAIRED T-TEST

This is done to compare the samples from the same group.
Because the samples are not independent, we cannot use the Student’s t-test. Instead, we must use a modified version of the test that checks for the fact that the data samples are dependent, called the paired Student’s t-test.

In the example from the website, they have taken there samples to be independent, not paired, we can pretend for the sake of the demonstration that the observations are paired and calculate the statistic.

## ANOVA TEST

The purpose of a one-way analysis of variance (one-way ANOVA) is to compare the means of two or more groups (the independent variable) on one dependent variable to see if the group means are significantly different from each other. ANOVA is a statistical test that assumes that the mean across 2 or more groups are equal. If the evidence suggests that this is not the case, the null hypothesis is rejected and at least one data sample has a different distribution.

[Code Link](https://github.com/SourajitaDewasi/StasticalDataAnalysis/blob/main/Student%20T%20Test%20and%20ANOVA/Student's_T_Test.ipynb)
[Reference 1](https://machinelearningmastery.com/parametric-statistical-significance-tests-in-python/)
[Reference 2](https://machinelearningmastery.com/how-to-code-the-students-t-test-from-scratch-in-python/)
  </p>
</hr>

<p>
 ## Exploring Seaborn Plots
    High level commands to plot useful for stastical data exploration and stastical model fitting. Seaborn API is more convenient than raw Matplolib commands
      [Code Link](https://github.com/SourajitaDewasi/StasticalDataAnalysis/tree/main/Seaborn)
  
  ### 1. Histograms, KDE, and densities
            1.1 plot histograms and joint distributions of variables for stastical data visualization.
  ### 2. Generalizing joint plots to datasets of larger dimensions leads to pair plots.
            2.1 Useful for exploring correlations between multidimensional data to plot all pairs of values against each other.
  ### 3. Faceted Histograms
            3.1 View data via histograms of subsets. 
  ### 4. Factor plots
            4.1 Factor plots is used to view the distribution of a parameter within bins defined by any other parameter.
  ### 5. Joint Distributions
            5.1 Show the joint distribution between different datasets, along with the associated marginal distributions.
  ### 6. Example: Exploring Marathon Finishing Times
            6.1 Violin plots, Time Series Plots, JointPlot
</p>
<p>
  ##Exploring Pandas Visualization
  
  [Code Link](https://github.com/SourajitaDewasi/StasticalDataAnalysis/tree/main/Pandas)
  
  [Code Link of Reference Site](https://nbviewer.org/urls/gist.github.com/fonnesbeck/5850375/raw/c18cfcd9580d382cb6d14e4708aab33a0916ff3e/1.+Introduction+to+Pandas.ipynb)
</p>
