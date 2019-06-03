# Loan Data from Prosper

## Dataset

The dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
The dataset can be found in the following link: https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1559103484084000

With a variable dictionary here: https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0

## Main Findings

1. There is a high correlation between APRs, Loan Rates, and Lender Yields.
2. However, none of the variables chosen for this study could predict a Loan's APR.
3. Car Loans are more expensive on average than boat loans. 
The average loan APR for buying a boat would be the lowest category, and loans like Auto are one of the highest. Buying a boat being a less frequent and niche market than buying a car, I was expecting the opposite result. One hypothesis for why this happened is that people who buy boats have more money or financial stability and that warrants a lower APR. However, Boat loan borrowers don't have a specially high income. Our assumption was wrong.
4. One of the highest earners and one of the lowest APR occupations are Doctors. However, being a doctor doesn't correlate with having a lower APR. While we can see that doctors tend to be higher earners than average, their APR is still dispersed across the range.
5. The second peak we find in the distribution of APRs near the 0.35 range is made up of mostly consolidated debt for employees. The fees associated with this loans are higher than the rest of the dataset.

## To View Presentation

Remember to write the following in the terminal:
jupyter nbconvert presentation.ipynb --to slides --template output_toggle.tpl --post serve


### Resources:
1. Udacity Courses and Examples.
2. Udacity Knowledge Center
3. https://stackoverflow.com/
4. https://jakevdp.github.io/PythonDataScienceHandbook/04.06-customizing-legends.html
5. http://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html