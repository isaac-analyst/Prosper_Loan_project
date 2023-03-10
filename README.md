#  Prosper Loan Data Exploration
## by  Isaac Godwin


## Dataset
 The dataset being used for this project is the Prosper loan Dataset, which was provided by Udacity. the data contains 113,937 observations with 81 variables. in which
 Most of the  variables were numeric and categorical.
The dataset can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000).

## Summary of Findings

 For this exploratory analysis, my main interest was to analyze the information related to the profile of the borrowers and the loan borrowed.
 Exploring the distribution of uni variables of interest, one of the insightful information discovered was that most of the borrowers were employed and fultime, looking
 also further to their occupations and it was observed that vast majority of the borrowers occupations were OTHERS which was an indication that thier occupation were not
 amongs the ones listed, i looked at Borrower's state and discovered CA (califonia) has the highest borrowers and Their monthly income distribution is skewed to the
 right and they are usually less than 30k. the borrowers income mostly ranges from 25,000-74,999. Their monthly income distribution is skewed to the right and they are
 usually less than 30k. Their income ratio is right skewed. Most of the loans have a loan term of 36 months, instead of 12 or 60 months.when i extracted the months and
 years of the loans from the loan original date and I discovered alot of loans were taken in 2013.
Investigating further to observe the relationships between 2 variables each of the data, then i discovered that the borrower interest Rate is negatively correlated with
the loan original amount, which mean the more the loan amount, the lower the Borrower Rate. It also shows that at different size of the loan amount, the Rate has a large
range, but the range of interest Rate decrease with the increase of loan amount. The loan original amount is positively correlated with the stated monthly income. That
is, the higher their stated monthly income, the higher the loan amount borrowed. Borrowers with verified income tend to have a higher average loan amount than borrowers
without verified income. Borrowers who are employed and fulltime on average take out larger loans than other groups. I observed that Borrowers with income ranging from
50,000-100,000+ aremostly homeowners and also Borrowers with full time employment status tend to take loans with term duration of 12 months Employed borrowers tend to
take loans of term duration as 36months. i also observed that from the visuals is can be observed that thereare a strong positive relationship between term and loan
amount that is the longer the loan term, the larger the loan I observed that in 2009 there was a large dip in loan origination then went back up in 2013.
Further investigation using multiple variables,i found out that loan term doesn't really seems to have an effect on the relationship between borrower rate and loan
original amount and i also observed that those who earn 100,000+ and have verified their income tend to get larger loan original amount than those whose income are not
verifiable. The borrowers with verified incomes tend to get higher loan.

## Key Insights for Presentation

For the presentation, I focus on the journey of exploring the features of interest to discover the relationship between the borrowers and the loan borrowed. I introduced
the variable of interest, and by how they relate to each another and eventually how their correlation is affected by another variable. The variable include: Borrowers'
employment status, their income range, stated monthly income and the loan original amount.
