# (ProsperLoanData)
## by (Raghad)


## Dataset Overview

> ## Dataset

> Loan Data from Prosper: This data set contains 113,937 loans with 81 variables on each loan,
ncluding loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others

>**i will invstigate in specifec column which is**

> LoanOriginalAmount BorrowerAPR StatedMonthlyIncome TermProsperRating (Alpha) EmploymentStatus IncomeRange LoanStatus IncomeVerifiable

> **but i will slide the most intersting ones on it**



## Summary of Findings

## Univariate Exploration

> **i made this horizontal countplot to see the distrubtion of the olan stasues and oreder it from the max to the min number
so from the graph it's seems like we have for catgories is the most in the loan states which is	Chargedoff, Completed, Current and the  the others loan states  is less than 10000** 

> **the BorrowerAPR seems it's have normal distrubation  in the big bake and also in the small bake so it' a multibake distrubtion   and we have some outlier between 0.3 and 0.4 also there is a few number is biger than 0.45 also the informtion in this interval is not completed**

> **from the graph we see that the long term is 36 month then 60 then the lowest is 12 month**

> **first the graph looks like it's skweed so we well do a log transformtion to see , after the log transformation we see that the data have binmile model sence it's have tow peak the first one on 3000-4000 and the other one on 10000-20000** .

> -**there is less than or equal to 0.31 percent from broweer take  less than 30000 monthly income**
  -**sence the percent is less than 1% i will consider it as outlier and i will deleat it cause it will not effect**
  
>**we have the most of job stauts that takeing loan is either is Employed or full-time and the other states is less than 10000**

>**the 30K or more from brower taker they take income range from  $25,000-74,999 and more than 15K they take from
75,000 and more than $100,000+ income range and less than 10k either they don't displayed or take income range from $1-24,999 and less than 5k they Not employed or take 0**

>**the most prosper Rating is from C to A and this have almost normal distrubtion**

>**the number of people that have income verifable is bigger than they don't verivy**
B
>**from the grph and this plot we conclude there is a  negtive realtionship between BorrowerAPR and LoanOriginalAmount 
so if LoanOriginalAmount increase the BorrowerAPR will decrase but it's not a strong realtionship**

## Bivariate Exploration

>  the LoanOriginalAmount is increasing with the term increasing
>  the max number  of BorrowerAPR is the same for all EmploymentStatus but the mean of BrowwerAPR for the not Employed is the highest
>  there is an outlier of the StatedMonthlyIncome for the self-employed
>  the ProsperRating (Alpha) is incresing with the satae monthly income
>  the ProsperRating (Alpha) is decresing with the Browwer APR is increasing
> the highest term in all ProsperRating (Alpha) is 36
> the most of browwer they don't Verifiable thier Income is self-employed
> ProsperRating (Alpha) in the employed is the higest that's mean the the employed is the highet one have rating

## Multivariate Exploration

>**Both Rating and incom verving is incresing with the highest number ofriginal Amount
>there is relationship that the most of the income vevible haveing high state monthly income and also loan orginal amout also there alot of them in the higher rating

# these all the explortion that i made but i will not bring all of them i will just show 7 of them

## Key Insights for Presentation

**knowing the StatedMonthlyIncome distrubtion and why to remove spicefc value form the varible**

**made a count plot for ProsperRating (Alpha) and order it from lowest to the highest to know the most and lowest**.
