# Investigation on a Loan Dataset
## by Reem Abdel-Rahman


## Dataset



> The dataset consists of 113937 loans with 81 attributes, from which 7 attributes were chosen to study the status of the loans, whether they are completed, current, charged off, cancelled or due. The attributes of interest include the duration of the loan, the loan original amount, the employment status and whether the borrower owns a house. 
This dataset can be found here: https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv
with further features explanation here: https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit 


## Summary of Findings

In the investigation of the dataset, we found that the number of people who have houses and take 
loans are greater than the number of people who do not have houses. Does an ownership of a house 
encourage people to take loans? More people with no house completed their loans than people with 
a house. Maybe people with tight financial conditions are more serious about repaying their debts? 
Among the people who have comleted their loans, the largest number have a full time job. The second 
largest number are employmed. Most of the people who take loans are employed. 

There is no apparent relation between the original loan amount and the loan's status. For all the 
status of the loan, the larger amount of loans reside between 0 and around 5000 and decreases while
it reaches 10000. There was no apparent relation between the status and the duration of the loan. 
That might be the case because the nature of the data could be biased as most of the people tend 
to go for a moderate loan duration: 36 month. We could not find a relation between the LoanOriginalAmount
and the BorrowerRate. We can only deduce that the number of loans decreases with increasing amount of 
money. The distribution of the borrower rate is similar for borrowers who own a house and those who do not.

There is a strong positive correlation between the annual rate and the interest rate. For this dataset, 
most of the relations could be spotted in the bivariate analysis. The multivariate visulizations did not 
spot much information. 


## Key Insights for Presentation

For the presentation, I start by visualizing the loan's status and duration. Then, I provide an overview of
the used attributes of the borrowers such as the ownership of a house, the employment status and the duration 
of the employment. I show a figure for the distributiion for each of those variables. Then, I show the relation
between the annual rate and the interest rate as they have a strong positive correlation. 

I use the heatmap and a bar plot to spot the relation between the loan status and the ownership of a house. 
Similar plots are used to spot the relation between the loan status and the employment status. Finally, I 
use a bar plot to find the relation between three variables: loan status, the annual rate and the ownership 
of a house. 

## Resources
https://stackoverflow.com/questions/45846189/how-to-delete-all-columns-in-dataframe-except-certain-ones
https://stackoverflow.com/questions/23307301/replacing-column-values-in-a-pandas-dataframe
https://github.com/mwaskom/seaborn/issues/867
https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.subplots_adjust.html
