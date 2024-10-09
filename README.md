# Prosper Loan Data Exploration
## by (Metasebiya Akililu Bizuneh


## Dataset

> Prosper is the first peer-to-peer lending market place in America. This document is used to visualize a loan data from Prosper. It contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate),current loan status, borrower income, and many others.Once the dataset is loaded on a pandas dataframe, I have wrangled the dataset with some high level analysis by using info(),describe(),head(),dtypes(),shape. Then, I checked if null values exist on some series of columns of the dataset. I used the isnull() and notna to adjust the null values. On top of that, I changed some of the columns to an ordered categorical type. Next, I checked the distribution of the categorical type columns by using the value_counts() function.


## Summary of Findings

> In the exploration process, I figured out which variables affect the loan status of a borrower. I have come up with 11 variables to conduct this exploration. While exploring, I found that some of the variables having a strong correlation. To mension some, BorrowerRate and BorrowerAPR have a strong relationship.Other relationship I have found is the correlation between MonthlyLoan Payment and BorrowerAPR.These two variables have a negative correlation. What I have concluded from this relationship is that when a borrower's monthly loan payment increases, the BorrowerAPR will decrease. On top of exploring the relationship between the chosen variables, I also checked the correlation of some of the variables with LoanStatus. It seams that the loan status of a borrower is highly affected by the EmploymentStatus, MonthlyLoanPayment and PaymentScore. Based on this exploration, borrowers with EmloymentStatus of "employeed" and "other" and a ProsperScore with a high value will pay have a "current" loan status.


## Key Insights for Presentation

> For the Presention part, I will focus on the influence of employement status, monthly loan payment and payment score on the loan status of a borrower. First I will introduce the the categorical variables. On top of that, I will perform data wrangling process to clean the variables I need for this exploration phase. Then I will visualize the distribution of loan status variable.Next, I will check the distribution of the remaining variables. Then I will check the relationship between the 3 variables and loan status. Finally, I will use a multivariate exploration to check the cummulative effect of the  vaiables I choose on loan status.
