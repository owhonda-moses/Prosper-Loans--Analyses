# Loans Data Visualization
#### _by (Owhonda Moses)_


## INTRODUCTION

> This data set contains 113,937 Prosper loans with 81 variables on each loan,
including loan amount, borrower rate (or interest rate), current loan status,
borrower income, and many others. The dataset can be found in this Google doc
[here](https://docs.google.com/document/d/e/2PACX-1vQmkX4iOT6Rcrin42vslquX2_wQCjIa_hbwD0xmxrERPSOJYDtpNc_3wwK_p9_KpOsfA6QVyEHdxxq7/pub)
with feature documentation available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).
I was interested in analyzing entries with a Prosper score, and subsetting the
dataframe to this criteria trimmed the data down to 84,853 loans with 15 variables. Preliminary wrangling was carried out, reducing the variables to 14.
>> The exploration was structured from simple univariate relationships to
multivariate relationships to summarize the characteristics of features that can
affect the annual percentage rate (APR) and outcome of a loan.


## Summary of Findings

 In the exploration, I found that there was a negative relationship between
`credit scores` and `annual percentage rates`, which were my main features of interest.
Most credit profiles had average credit scores and high APRs and I
saw that APR reduced with increasing orders of Prosper score, Credit score and
Income range. Credit profiles with lengthier loan terms, smaller loan amounts and
larger revolving balance however, had higher APRs.

Investigating further, I found that an increase in number of trades was largely
proportional to an increase in the number of open credit lines, and also,
a fair number of trades in the dataset were delinquent. About 10% of the loans
were either past due, defaulted or charged off, however, excluding current loans,
the proportion of these loans was about 30%.
I also found that defaulted loans slightly correlated with income, annual
percentage rate and employment status.

The majority of loans were current loans
taken out for debt consolidation, and most of these loans were taken by employed
folks with average credit scores, with most loans spanning a period of 36 months.


## Key Insights for Presentation

For the explanatory analysis, I focused on the ordinal features as well
as the Borrower APR, Loan amount and Loan status. I started by introducing the main
features of interest, followed by the ordinal variables and their respective plots.

Next, I explored APR in relation to Credit Score using a violin plot, and then,
using a clustered bar chart, I introduced Income and Prosper score variables with
focus on Credit score. Afterwards, I covered the relationships between the main
features and Income, as well as Loan status, using pointplots. Finally I explored
how loan amounts interacted with the main features using a scatterplot with jitters and a color bar.

I made sure to use different color palettes for each quality variable to ensure
it is clear that they are different between visuals.

#### PACKAGES USED:

- JuPyter notebook
- pandas
- numpy
- matplotlib
- seaborn

_Notable references for this project include -_
- https://stackoverflow.com/
- https://github.com/
- https://www.geeksforgeeks.org/
- https://pandas.pydata.org/
- https://wiki.python.org/
- https://www.w3resource.com/
- https://pythonguides.com/
