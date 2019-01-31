# prosper-loan-data

## Introduction
In this notebook, I will try to investigate this dataset, get insights from them, then visualization the results. I choose Prosper Loan Dataset because I was a banker before and I have some experience in the Loan process.

Original dataset can be downloadable from the internet: https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv.

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. However, we are not expected to explore all of the variables in the dataset! We will focus our exploration on about 10-15 of them.

For those who are not familiar with financial indexes, this attached link can be useful to refer to any terms you don't know: https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit?usp=sharing

The scope of this analysis is to find some common features of Prosper Loan Clients as well as some factors that may affect their loan status.

## Wrangling the data
We will start with cleaning the dataset, dropping some unneccessary and irrelevant data, filling some missing data with our caculated algorithm, then finally analyzing and visualizing it.

This data frame, in general, is having some issues that need to be solved.

- At first, there are many variables that are not important or we don't need due to the limit of our analysis. Getting rid of them will make the dataset easier to read and understand.

- Secondly, there are too many cells that have Null value, abnormal value and improper types noticed in some columns. Some of them can be calculated/inputted with algorithm. The more comprehensive the dataframe has, the more easier the analysis task is.

## Visualizing the data

### Loan Purpose by Category
Loan purpose is an important index as it can easily tell us the validity of clients' request when they start applying to the loan. When a loan purpose doesn't fit the bank policy, client can be rejected form the beginning process.

### Credit Score by Prosper Score
Credit Score has a big impact on the acceptance rate and borrowing rate of the loan. Prosper Loan Company, on the other hand, has developed their own score to rate their clients. We will see how comparative these two index are when they are placed next to each other.

### Employment Status of the Borrower
Employement status is another category that show the financial status of debtor. The higher chance they are employed and having a full-time job, the higher chance they have their income to pay for their loan installment.

## Conclusion
Prosper Loan Company does a good job in collecting their loan data of clients. However, It takes some steps in cleaning and simplifying the dataset before it ready to be used.
It is a good practice for me to use my skills to analize and visualize these data. And from there, I think the company can have a good understanding of their clients as well as they can create a plan to better their products/services.
