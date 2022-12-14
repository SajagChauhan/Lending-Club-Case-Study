# Lending Club Case Study


## Table of Contents
* [Problem Statement](#problem-statement)
* [Business Objective](#Business-objectives)
* [Approach Used](#Approach-used)
* [Observations & Results](#observations-&-results)



## Problem Statement
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The data given contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
In this case study, you will use EDA to understand how **consumer attributes** and **loan attributes** influence the tendency of default.

When a person applies for a loan, there are **two types of decisions** that could be taken by the company:
1. **Loan accepted**: If the company approves the loan, there are 3 possible scenarios described below:
   - **Fully paid**: Applicant has fully paid the loan (the principal and the interest rate)
   - **Current**: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
   - **Charged-off**: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has **defaulted** on the loan 
2. **Loan rejected**: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)


## Business Objectives
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who **default** cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the **driving factors (or driver variables)** behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 


## Approach Used
- Understanding the data.
- Perform the Data Cleaning.
- Perform the Univariate Analysis for insights on Distribution of feature Variables.
- Perform the Bivariate Analysis to explores the association between two variables.
- Visualize the patterns between the Variables.
- Observed the driving factors behind loan Default.   


## Observations & Results
- If Applicant's annual income is less than 20,000 with grade F5,G2,G3 and employment length is more than 10 years then he is most likely to be charged off.
- If Applicant's Home is rented or mortgaged, his purpose of loan is small business and term of repayment is more or equal to 60 months, he/she is most likely to be charged off.
- If loan amount is more than 28000 and interest rate kept is 16 then he is most likely be charged off.


## Contact
Created by [@SajagChauhan] and [@hansa15100] - feel free to contact me!

