# Loan Data from Prosper
## by Pouyan Ebrahimi


## Dataset

> This document explores a dataset containing 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. •

>[This data dictionary](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit?usp=sharing) explains the variables in the data set. The dataset can be found in the
repository for R's ggplot2 library [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)


## Summary of Findings
>Most of those who completed their loans has a ProsperScore above 3. Most of those who currently has loan, has a ProsperScore of 4, and the minimum count of loaners belong to those who has a ProsperScore of 1. The majority (~50,000) of people who currently has a loan are employed no matter what is their ProsperScore. If their ProsperScore is between 4 and 8, the population of employed loan borrowers in each particular ProsperScore is between 6000 and 8000. In ProsperScore of 2 to 8, the number of loaners who has a salary of 25-49k and 50-74k is more than others salary groups and if the ProsperScore is between 4 and 8, the population of both salaries of 25-49k and 50-74k groups ranges between 2500 and 3900. Plots also show that BorrowerRate has a negative relationship with LoanOriginalAmount and has a positive relationship with ProsperScore. IncomeRange also affect the LoanOriginalAmount in a positive way. The plot of the full data using a violin plot suggests that borrow rate is independant of income range and ranges ~0.15-0.21. TotalCreditLinespast7years does not play a significant role on controling the BorrowerRate and LoanOriginalAmount relationship. At each particular IncomeRange, by increasing the LoanOriginalAmount, the BorrowerRate decreases. Besides, apparently only those who has a IncomeRange above \$100k, are borrowing higher LoanOriginalAmount (\>$25000) and their BorrowerRate is <0.15. apparently, people with lower IncomeRange have higher BorrowerRate at each individual ProsperScore.


## Key Insights for Presentation

> For the presentation, I answer below questions:
- What affects the borrower’s APR or interest rate?
- Are there differences between loans depending on how large the original loan amount was?

> I start by introducing the Borrower Rate, Loan Original, and Prosper Score, followed by the Distribution of Prosper Score in different Employment Status and Income Ranges. Then dig more into the relationships between Borrower Rate and Loan Original Amount and I discovered how it could be affected by Income Ranges, Total Credit Lines-past7 years, and Income Range. Besides, I also presented the effect of Income Range on Prosper Score and Borrower Rate relationship.

> The most important finding is that the Loan Original Amount and Prosper Score significantly affect the Borrow Rate.
