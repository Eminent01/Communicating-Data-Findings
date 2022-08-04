## Loan Data from Prosper
## by (Ademola Abiodun Saheed)
This repository is for the data analytics project. 3 data project are to be completed during this program for succeful completion of the program. 
The project preview along with the link will be provided below.

## Introduction
This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The loan data from Prosper was obtained originally from Prosper which has several data sources for investors to analyze historical loan performance on the platform.

During the course of these analysis, the data set will be used to answer the following question.

(1)What factors affect a loan’s outcome status?
(2))What affects the borrower’s APR or interest rate?
(3)Are there differences between loans depending on how large the original loan amount was?

For the dataset used in the project click on the link below.
[Dataset]("https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv.")
Data description and explanations of the variables. Click on the link below.
[Explanation]("https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0")

## Summary of the findings
From the analysis, we found that the borrower APR is negatively correlated with original loan amount. The borrower APR decreases with the increasingly better rating. Borrowers with the best Prosper ratings have the lowest APR. It means that the Prosper rating has a strong effect on borrower APR. 

The loan amount increases with better rating. The borrower APR decreases with better rating. Interestingly, the relationship between borrower APR and loan amount turns from negative to slightly positive when the Prosper ratings are increased from HR to A or better.

Also, interestingly, the relationship between borrower APR and loan amount turns from negative to slightly positive when the Prosper ratings are increased from HR to A or better. This is may because people with A or AA ratings tend to borrow more money, increasting APR could prevent them borrow even more and maximize the profit. But people with lower ratings tend to borrow less money, decreasing APR could encourage them to borrow more. It was also found that the borrower APR decrease with the increase of borrow term for people with HR-C ratings. But for people with B-AA ratings, the APR increase with the increase of borrow term.

The loan amount was also found to be positively correlated with the stated monthly income, it makes sense since borrowers with more monthly income could loan more money. The loan amount is also increased with the increase of loan term. Employed, self-employed and full time borrowers have more monthly income and loan amount than part-time, retired and not employed borrowers. 
For interactions between categorical term and Prosper rating features. Proportionally, there are more 60 months loans on B and C ratings. There are only 36 months loans for HR rating borrowers.

## Presentation Summary
For the presentation, We focus on the features that could affect the borrower APR, which are original loan amount, Prosper rating, loan term and started monthly income.  Started by showing the distribution of borrower APR, loan amount and stated monthly income variable. Then, we showed the relationship between APR vs. loan amount, as well as APR vs. rating. We also investigated the effect of rating on ralationship between APR and loan amount, as well as the effect of rating on relationship between borrower APR and term.
Lastly, we also showed the correlation plot of borrower APR and loan original amount, stated monthly income, Borrower Rate and debt to income ratio.
