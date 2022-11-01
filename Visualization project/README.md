# Loans Data by Prosper
## by Adegboye Okikioluwa


## Dataset

The Prosper loans data set contains 113,937 loans from Prosper Loans company in the USA, with 81 variables on each loan describing Prosper Company rating on loan applications, their Annual percentage rates on loans, Debt to income ratio, current loan status and informations of the person applying for the loan such as the State they live in, occupation, income etc. This dataset can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv), with feature documentation [here](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&source=editors&ust=1666207848245362&usg=AOvVaw0TJ36wTlE32d2sFx6qljw8)


## Summary of Findings

The APR has a large range with most Loan APR falling between 0.18 and 0.2, and around 0.36. There were many small loans taken in the dataset, but there was also a clear indication that people who applied for loans took high amounts such as 5K, 10K, 15K, 20K and 25K. Prosper loans had many loan request from Carlifonia and most loans were used on Debt consolidation.

BorrowerAPR has a negative correlation with Prosper Rating. The higher the rating (AA - HR) the lower the APR. The APR also has thesame relationship with Loan amount. However, With better ratings from AA to A, the higher the Loan amount the higher the APR showing a positive correletion, while from B to HR ratings, the higher the loan amount the lower the APR showing a negative relationship.
People with better ratings tend to borrow more, increasing the APR will prevent them from borrowing even more, and decreasing the APR for people with low ratings to will allow them to borrow more. A borrower having a high rating and short term will pay less charges on a loan. If a borrower has a low rating, it will be better to have a longer term to pay less charges on loan, although it can not be as low as the later.
High APR is also associated with loans that were Past Due, Defualted or Charged Off.
Low Income and Low Bank card Credit results in low Prosper ratings and vice versa. People with Relatively high bank card credit had low Debt income ratio, while people with relatively high low Bank card credit had high debt income ratio. This affected their ability to pay the loan as a high Debt income ratio resulted in loans being Past Due, Defualted or Charged off.


## Key Insights for Presentation
The presentation is focused on the BorrowerAPR and Features that affect or have a solid relationship with it, and affect the outcome of a loan. This was shown by presenting the distribution of the borrowerAPR. Then showing it's relationship with loan status, loan amount, prosper rating. The relationship between BorrowerAPR, Term and Prosper rating