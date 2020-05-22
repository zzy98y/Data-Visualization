# Prosper Loan Data Exploration Analysis
## by Zhengyang Zhang


## Dataset

> I used one of the dataset provided by Udacity. It's about Prosper Loan. It has 113937 rows and 81 columns. My main interests in this dataset is ProsperScore. And some of the features I believe are related to this ProsperScore are DebtToIncomeRatio,TotalInquiries,ListingCategory,MonthlyLoanPayment,TotalProsperPaymentsBilled,IsBorrowerHomeowner.

## Summary of Findings

> In the univariate exploration, I plot histogram and horizontal bar plot for the feature I investigated, it seems most of the variable are skewed to the right in the histogram, except the main feature of interests, ProsperScore. 

> In the bivariate exploration, I have three graph. 

> From the first scatterplot, we can say Debt to Income Ratio plays an important factor in Prosper Score, we can see a lot of the pink-ish area are range from Total Inqueries range from 0 to 20, but Debt to Income to Ratio has stay within a certain range. What's also interesting is that those Debt to Income Ratio are particularly high like close to 10 even have a 6 or 7 ProsperScore, that gets me thinking maybe both factors play important roles in affecting ProsperScore.

>In the second heatmap, we're able to see that most number are clustered on payments less than 20, and majority are clustered less than 40 on time payments, and the score really varies on the ProsperScore, but it seems as long you make more than 10 on time payment, you will have a score ranging from 6 to 8.

>In the third clustered bar chart, we're able to see that there are more non-homeowner take out loan than homeowner. But surprisingly, more homeowner take out loan for Debt Consolidation than non-homeowner, it's probably because they have so many small debt, they want to put it all together and pay off with the loan they take out from Prosper.

> In the multivariate exploration, I have three graph as well. 

>In the above scatterplot with Prosper Score as a third variable, we're able to see that most people have good prosperscore are either with high monthly loan payment with less total payment made or with less payment and more payments history.

>In the above scatterplot with Prosper Score as a third variable, we're able to see that most people have good prosperscore are either with high monthly loan payment with less total payment made or with less payment and more payments history.

>From the pointplot, we can say in general, non-homeowners' monthly payments are smaller than homeowner. And ProsperScore of 1 and 11 have high variability in terms of the monthly payment, that also indicates that there are one more factors affecting the prosperscore other than Monthly Payment amount.

## Key Insights for Presentation

> Currently None. 
