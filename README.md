# (Prosper Loan Data)

## by (David Karanja Mwangi)


## Dataset

> The prosper loans dataset contains 113,937 rows and 81 columns of data. Important variables used in this project include: loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.The data is downloaded programmatically from this url [data source](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)


## Summary of Findings

> The most popular loan term is 36 months while the least common is 12 months.

> From the data, most loans are active, followed by those that borrowers have completed paying, those charged off and then the defaulted ones.

> California State has the largest number of borrowers which stands at over 14,000. North Dakota state on the contrary has the least number, 52. However, we would need population information to be able to do some feature engineering to decide states with the highest loan uptake rate.

> We see a normal distribution with a bell curve of the Borrower's Annual Percentage Rate. An outlier is noticed on the curve that needs furthur investigation.

> Borrowers are almost split into half. Both those with homes and those without are taking loans. 49.6% do not have morgages while 50.4% of borrowers have morgages.

> Loans with 36 months terms have the highest range of BorrowerAPRs, followed by 12 months loan terms and finally 60 months loans range. The medians are almost similar.

> Estiamted Loss for loans at 12 month terms are low compared to the estimated loss for 36 month Term loans. A couple of outliers are also observed in the 36 month term.

> Highly correlated features: Estimated loss & Borrower Rate. Proper score & Prosper Rating. There is a 0.34 correlation between loan term and Loan original amount. The prosper rating is hihgly correlated with Borrower rate, estimated loss which indicates that the Annual percentage rate is mean to cover the estimated loss ProsperScore is high and CreditScoreRangeLower, BankcardUtilization are medium correlated to ProsperRating.

> for high borrowerRate, past 0.4, the estiamtedLoss is constant and does not seem to change with increase in BorrowerRate. The greatest collection of estiamtedLoss is concentrated between borrowerRates of 0.1 and 0.3

> 36 Months terms loans have the highest EstiamtedReturns followed by 60 months term loans.

> EstiamtedLoss for loans at 12 month term are low compared ot the same for 36 month Term loans.

> The BorrowerRate has a positive correlation wiht the BorrowerAPR for all Loan terms, 12, 36 and 60 months. The BorrowerRate and BorrowerAPR are mainly concentrated between 0.1 and 0.4 for 36 & 60 month term loans

>  Irrespective of term and whether borrower is a homeowner or not, the correlation between Borrower APR and Loan Original Amount is still negative.

> There is a postive correlation between Borrower Rate, Lender Yield and Term.


## Key Insights for Presentation

> The Most common Loan term is 36 months followed by 60 months. 12 months term loans are the least popular based on the data.

> California State has the largest number of borrowers which stands at over 14,000. North Dakota state on the contrary has the least number, 52. However, we would need population information to be able to do some feature engineering to decide states with the highest loan uptake rate.

> Borrowers are almost split into half. Both those with homes and those without are taking loans. 49.6% do not have mortgages while 50.4% of borrowers have mortgages.

> Estimated Loss for loans at 12 month terms are low compared to the estimated loss for 36 month Term loans. A couple of outliers are also observed in the 36 month term.

