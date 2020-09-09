# Statistics
This page will help you to understand below statistics concepts and their implementation in Python
1. Decriptive Statistics
2. Confidence Interval

## 1. <ins>Decriptive Statistics</ins> (DescriptiveStatistics.ipynb)

<b> So what is descriptive statistics?</b><br>
Descriptive statistics is used to describe or summarize data in a ways that it is meaningful and useful. Descriptive statistics is at the heart of all quantitative analysis.

<b>How do we describe data?</b><br>
There are two ways: measures of central tendency and measures of variability, or dispersion.

<b>How this code is going to help to summarize descriptive statistics for my data?</b><br>
This code would provide the descriptive statistics for any input data which is CSV or excel format.<br>
Just set the value of <b>"file_name"</b> variable in _Step 2_

<b>How the output of this code going to help me?</b><br>
_Step 4_ would help to summarize:
* probable type of variable
* amount of missing data
* measures of central tendency
* measures of variability
* unique values

<b>Does this code provides any kind of plots of variables?</b><br>
Yes, step 5 to 7 provides different types of plot of different variables<br>
_Step 5_ provides count plot for categorical variables<br>
_Step 6_ provides count plot for binary variables<br>
_Step 5_ provides boxplot for numerical variables

## 2. <ins>Confidence Interval</ins> (ConfidenceInterval.ipynb)
This code will help to understand the concept of Confidence Interval.<br>

<b>So what is Confidence Interval?</b><br>
The confidence interval (CI): A confidence interval is an estimate of an interval in statistics that may contain a population parameter. The unknown population parameter is found through a sample parameter calculated from the sampled data. For example, the population mean μ is found using the sample mean $\bar{x}$.

<b>How is confidence interval defined</b>
The interval is generally defined by its lower and upper bounds. The confidence interval is expressed as a percentage (the most frequently quoted percentages are 90%, 95%, and 99%). The percentage reflects the confidence level.

<b>How the output of this code going to help me?</b><br>
Output in _Step 4_ states how increase in smaple size affects capturing of population mean<br>
_Step 5_ provies statistics for output in tabular format

<b>Does this code provides any kind of plots?</b><br>
Yes, _Step 6_ provides plot of percent of samples capturing population mean vs log of sample size. Here log of sample size is taken since without it points would be scattered too far on the plot

<b>Can the statistics be extarcted in excel</b><br>
Yes, in _Step 8_ the statistics can exported in excel
