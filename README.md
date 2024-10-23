# Lending Club Case Study
> Lending Club, a consumer finance company which specialises in lending various types of loans to urban customers. 
Company faces a challenge in managing its loan approval process based on the applicant’s profile.


## Table of Contents
- [General Information](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)
- [Collaborators](#collaborators)



## General Information

- Lending Club, a consumer finance company which specialises in lending various types of loans to urban customers. 
- Company faces a challenge in managing its loan approval process based on the applicant’s profile.
- This case study aims to achieve this goal through exploratory data analysis (EDA) using the provided [dataset](./loan.csv)
- Applicant labeled as "charged-off" if he/she not paid the installments in due time for a long period of time, this may lead to a financial loss for the company.

Objective of this exercise is to identify:

1. Applicants likely to repay their loans which can generate profits for the company. 
2. Risky applicants who not likely to repay and lead to financial losses for the company.



## Technologies Used

- [Python] - version 3.10.12
- [Matplotlib] - version 3.7.1
- [Numpy] - version 1.26.4
- [Pandas] - version 2.2.2
- [Seaborn] - version 0.13.2



## Conclusions

- Applicant’s Grade: Most charged off loan applicants belonging to Grades B, C, and D.

- Sub - Grade: Within the B grade category, Sub-Grades B3, B4, and B5 show a higher likelihood of "Charged Off" loans.

- Employment Tenure: Approximately 25% of loan applicants have 10+ years of employment tenure.

- Loan Term Length: Loan applicants opting for 60-month loan terms have a significantly higher rate.

- House Stability: Applicants who live in rented or mortgaged homes are more likely to default on loans.

- Loan Purpose: 49.3% of charged-off loan applicants indicated that debt consolidation was their primary loan purpose.

- Geographic Risk: Borrowers from California, Florida, and New York are more likely to default. The company should keep an eye on these states and 
consider adjusting lending strategies or rates to reduce risk.

- High Loan Amounts: Applicants receiving loan amounts of $15,000 or higher are more likely to default.

- Low Annual Income: 28.34% of loan applicants who defaulted had annual salaries below 40,000.

- DTI and Interest Rates: A loan participants who charged off, had very high debt-to-income and had interest rates between 13% and 17%.



## Acknowledgements
- This project was inspired by live session of upGrad on EDA by Prof.Akash
- UpGrad tutorials on Exploratory Data Analysis (EDA) on the learning platform


## Collaborators

Created by [@akanksha-1206](https://github.com/akanksha-1206) and [@Kamar-p](https://github.com/Kamar-p)
