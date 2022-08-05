# (PROSPER LOAN DATASET PRESENTATION)
## by (Solomon Kwadwo Achinah)


## Dataset

The Loan dataset provided by Prosper is used for the presentation, it contains both quantitative and qualitative features. This data set contains 113,937 rows of loans with 81 columns for variables on each loan, including loan amount, Borrower rate, loan status, borrower's income, Prosper score, loan term and Prosper ratings. This data dictionary explains the variables in the data set and is available at https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0


## Summary of Findings

In the exploration, I found that BorrowerAPR and BorrowerRate looks similar with a slight difference. The APR is always higher than the interest rate since it is the the total cost of the loan. A strong positive relationship exist between BorrowerAPR and BorrowerRate. 
Again, there is strong correlation between prosper rating/score and the borrower’s rate. ProsperRating and ProsperScore have a significant impact on BorrowerRate. BorrowerRate are negatively correlated with ProsperRating. There is also a strong postive relationship between BorrowerAPR and BorrowerRate. 

The top 3 occupations with high monthly loan payment are Judges, Doctors and Pharmacists. The monthly loan payment however must positively correlate with the salary. The plot show consistent with salaries of each occupation. The groups that have lower monthly loan payment are students.

There is a gradual increase in BorrowerRate across the Prosper ratings, with a corresponding upwards trends within each cluster for the loan status feature. It can be observed that only a few borrowers have been classified in the Prosper Rating of AA. The proportion of loans in the lower rating groups are significant higher.

## Key Insights for Presentation

For the presentation, I focus on just how Prosper efficiently predict whether there will be a defaulted loan or not. So Prosper would be able to use this score to set the borrowe’s interest rate.  I start by introducing the
BorrowerAPR and BorrowerRate variable, followed by the pattern in occupational distribition, the created a transformed timeseries Interest rate plot.

Additionally, I converted data types for each of the categorical and datetime variables such as Term, EmployementStatus,LoanOriginationDate,  'ProsperRating (Alpha). I employed the barplot to visualize BorrowerRate against ProsperRating (Alpha) and LoanStatus. I was interested in the impact of increase in BorrowerRate across the Prosper ratings, with a corresponding trends within each cluster for the loan status feature. In the plot, I used the hue, and color to make my plots visually attractive. 