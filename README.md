# LENDING CLUB Case Study
> Lending Club, a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

>- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

>- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.
- Identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
- The driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.
- loan data for all loans issued through the time period 2007 t0 2011.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- 'int_rate' is 49% correlated to 'revol_util' [___SAFE___]
- 'loan_amnt' is 33% correlated with 'revol_bal' [___RISK___]
- 'loan_amnt' increased with recent years, HIGH 'loan_amnt' after COVID have high _Defaults_ [___RISK___]
- HIGH 'int_rate' after COVID have high _Defaults_ [___RISK___]
- HIGH 'int_rate' for LONG 'instalment' have high _Defaults_ but to Compensate it is necessary [___CONTRADICT___]
- HIGHER 'loan_amnt' for LOWER 'annual_inc' have _Defaults_ [___RISK___]
- LOWER 'sub_grade' have HIGHER 'int_rate' [___SAFE___]
- HIGHER 'loan_amnt' for LOWER 'grade' are high _Defaults_ [___RISK___]
- HIGH 'loan_amnt' for LONG 'term' have high _Defaults_ [___RISK___]
- HIGH 'int_rate' for LONG 'term' has more _Defaults_ [___RISK___]
- HIGHER 'loan_amnt' are __Verified__ more often and have huge _Defaults_ [___RISK___]
- HIGH 'int_rate' have more _Defaults_ but needs to impose HIGH 'int_rate' on _Defaults_ [___CONTRADICT___]

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python '3.11.5'
- pandas '2.0.3'
- matplotlib '3.7.2'
- seaborn '0.12.2'

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by live session of upGrad on EDA
- UpGrad tutorials on Exploratory Data Analysis (EDA) on the learning platform


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
