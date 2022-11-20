# (Loan Data From Prosper)
## by Joshua Olayori


## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. I dropped null values in needed columns. I changed columns’ data type to category as applicable. I dropped duplicates in the listing key column. After wrangling, 101094 records remained with 81 features.


## Summary of Findings

The distributions for both Monthly income and debt to income ratio are right skewed. The most prevalent loan status is completion, followed by current, while about 10000 people's loans are past due between 1 and 15 days. Q3 2007 saw the highest loan collection. California has the highest number of borrowers. Texas, New York, and Florida follow with about 6000 borrowers each. North Dakota has the least number of borrowers. Most of the loans have a 36-month term. About 5000 people in the dataset earn more than 10000 monthly. Highest loan amounts are about 14000. People in the 'other' category for borrowers' occupation have the highest number. The lowest debt to income ratio ranges from 0 to 0.2, and the highest borrower rate is between 0.30 and 0.35

There is a negative correlation between borrower rate and loan amount while there is a positive correlation between loan original amount and the stated monthly income. The higher the loan original amount, the lower the borrower rate. Green loans, debt consolidation, business, and baby & adoption had the highest loan amounts. Most loans taken by people doing full-time work are completed. The highest loan status for debt consolidation is 'current'. The highest loan status in California is 'current'. 'Current' 36-term loans have the highest category for loan status. Green loans have the highest loan amount. The highest green loan amount is a 12-term loan.


## Key Insights for Presentation

* Original Loan Amount of Borrowers
* Loan amounts of different listing categories
* Loan Amount Based on Term Length and Listing Category.
## Dataset Source
Click [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv) to download the dataset
