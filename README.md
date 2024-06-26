# Lending Club Case Study
> The Data in this Case Study contains data from a Finance Company  known for lending various loans to consumers. 
> Out of those loans, some loans are fully paid back whereas some are not.
> We have to analyze the data and find relationship among the various parameters and try to find out the ones actually can lead the loan to be a bad loan.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- The dataset being used here is lending club case study dataset.
- The goal of this analysis project is to find out the parameters which are essential to determine whether a loan can be a bad loan or not so that the future loans can be secured.

## Conclusions
### Univariate Analysis
- “total_pymnt” and “total_pymnt_inv” exhibit similar behavior. Thus, there's not much difference in the regular account v/s accounts funded by investors
- Maximum people have experience more than 10 years
- Maximum accounts are from state CA
- The highest number of accounts are assigned Grade-B
 - Max people who took loan are staying in Rented accommodation
- Maximum number of people have taken loans to clean another loan and to clearn credit card bills
- For max accounts, income source was not verified before giving loans
- A total of 13.6% loans are Charged Off (Bad Loans)

### Bivariate Analysis
#### Numerical Variables
- Higher the loan_amount, funded_amount or funded_amount_inv, higher the chances of bad loans.
- Lower the Total Payment, higher the chances of Charged Off Loans
- Higher Interest Rate leads to Hinger Charged Off Loans
- Lower the Annual Income, higher is the chances of Charged Off Loans
- Higher the DTI, higher is the chance of Charged Off Loans
- Higher the Revolving Line Utilization Rate, higher is the chance of Charged Off Loans

#### Categorical Variables
- Longer the loan tenure, higher the chances of Charged Off Loans¶
- Higher the Derogatory Public Record, Higher the chances of Charged Off Loans
- Lower the Grade/Sub-Grade assigned by LC, higher the chances of Charge Off
- Higher the number of public bankruptcies, higher the chance of Charge Off
- Small Business Loans have the higher chances of Charge Off
- Surprisingly, The Verified Loans have higher chances of Charge Off
- One more Surprising observation is related to House Ownership. Mortgaged House Owners have the lowest chances of Charge Off
- More the number of credit inquiries, more is the chance of Bad Loan


## Technologies Used
- python-3
- pandas
- numpy
- matplotlib
- seaborn

## Acknowledgements
Give credit here.


## Contact
Created by [@asimananda] and [@ashitajain] - feel free to contact us!
