# Loan Data from Prosper
## by Oliwia Koteluk


## Dataset
The investigated dataset is the collection of information about more than 110 thousand of loan made by Prosper from 2005 to 2014. There a lot of the information about each loan. It is worth to check what features are best for predicting the amount of loan (LoanOriginalAmount).


## Summary of Findings
In the exploration, I found that there was a close to exponential relationship between the `LoanOriginationAmount` and `MonthlyLoanPayment`. I also found out that amount of loan is also associated with some qualitative features such as: date, loan status, listing category, state, occupation, income range, term and house ownership. Interingly, I found out that the amount of loan seems to be associated with `EmploymentStatus`, not the employment duration. The exploration part showed that there are more than just two features that helps predicting the amount of loan. There are also combinations of features that strengthened each other in terms of predicting the amount of loan. 


## Key Insights for Presentation
For the presentation, I focus on just the influence of the features which might strengthened each other in terms of predicting the amount of loan (`IncomeRange`, date and `isBorrowerHomeowner`). I start by introducing the main variable of interest (`LoanOriginationAmount`) by plotting its distribution. This was followed by the taking closer look at the relationship between loan amount and the rest three categorical variables. In case of `IncomeRange` only the records with income more than $1 was taken. All of this was followed by the visualization of more complex multivariate relationship. 
During explanatory part of the analysis, I've made sure that the plots are clean and easy to read.