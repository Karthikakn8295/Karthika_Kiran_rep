# Project: Lending Club Case Study
> This project mainly focusses on Exploratory Data Analysis in the banking and risk analytics field. EDA is done to identify patterns which indicate if a person is 
likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate,
etc.


## Table of Contents
* General Info
* Dataset Used
* Technologies Used
* Conclusions


## General Information
The loan providing companies find it hard to give loans to the people due to their insufficient or non-existent credit history. Because of that, some consumers use it as
their advantage by becoming a defaulter. Suppose you work for a consumer finance company which specialises in lending various types of loans to urban customers. 
You have to use EDA to analyse the patterns present in the data. This will ensure that the applicants are capable of repaying the loan are not rejected.

When the company receives a loan application, the company has to decide for loan approval based on the applicant’s profile. Two types of risks are associated with the
bank’s decision:

1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

All other cases: All other cases when the payment is paid on time.

When a client applies for a loan, there are four types of decisions that could be taken by the client/company):

Approved:
The Company has approved loan Application

Cancelled:
The client cancelled the application sometime during approval. Either the client changed her/his mind about the loan or in some cases due to a higher risk 
of the client he received worse pricing which he did not want.

Refused:
The company had rejected the loan (because the client does not meet their requirements etc.).

Unused offer:
Loan has been cancelled by the client but on different stages of the process.

Different Risks Associated with Customers availing for a loan:

1. Credit risk
When an individual applies for a loan or any kind of credit, a process called underwriting begins. This process often begins with an automated screening based on 
credit scores, payment history, and debt to income ratio.

However, other factors also go into calculating credit risk, such as geographical locations or the borrower’s occupation. As a result, the practice can be vulnerable
to human bias – a danger that automated risk analysis mitigates against. Helping to create a system that is fairer and more efficient.

Risk analysis can also be harnessed to better manage and leverage a bank’s assets. For example, it can help to inform important decisions about what credit to pay off,
what to maintain, and when to increase cash reserves rather than borrow.

2. Market risk
Banks are also subject to factors beyond their control, such as market variations. 
Unsurprisingly, the market has been exceedingly volatile over the last few years with the knock-on impacts of COVID-19 and other international factors like the 
Ukraine War. Market volatility is always a risk, it can be impacted by everything from interest rates to energy demands making it unpredictable and hard to navigate.

Risk analysis can help banks understand the potential impact of market and external forces, as well as make predictions, based on previous information and scenarios.
This again can provide insights that will help to shape future decisions and better protect the business’ interests.

3. Operational risk
Operational risk is present in any business and is essentially the risk of loss resulting from inadequate or failed internal processes, 
people, and systems or from external events. But banks – namely due to the lure of financial gain and sensitive information,
 can be especially vulnerable to things like cyberattacks, theft, and fraud.

Many of these risks can be mitigated using approaches such as training and operational security, but risk analytics can go a step further, helping to banks to take 
proactive steps to pre-empt risks, rather than working reactively, after an incident has occurred. For example, risk analysis software can help by modelling certain
scenarios that enable the development of preventative solutions  before a problem occurs. This can enable banks to evaluate security risks, prepare for the worst-case
scenario, and put response plans in place.


## Dataset Used:
The dataset used is named as loan.csv. It contains details about the customer_id, employment details,address, loan amount availed, interest rate, whether the customers
have defaulted or not etc. This dataset can be used to get the patterns required to see how a customer has defualted.

## Technologies Used
Jupyter notebook has been used for analysis purposes in Python. Following Libraries have been used
- pandas- version 1.0.1
- numpy- version 1.18.1
- seaborn- version 0.10.0

## Conclusions
1. More stringent verification processes need to be placed in the system as majority of the defaulted customers 
do not have their income or income source verified.
2. Customers who have their house on mortgage or are staying on rent should be charged higher rates of interest.
3. Customers having job experience less than 1 year or above 10 years should be charged higher rates of interest 
as they are more prone to default.
4. Customers who are taking loan for debt consolidation should be charged higher rate of interest.
5. Higher DTI ratios suggest higher risk of defaulting so such customers should be recognized and thoroughly verified.
6. Customers with higher number of delinquencies are at a higher risk of defaulting. 
So lenders should be careful while providing loan to such customers.

## Contact
Created by  
Karthika K Namboothiri

Kiran Hunagund
