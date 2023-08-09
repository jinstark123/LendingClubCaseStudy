# Lending Club Case Study
> Lending Club is a finance company which specialises in lending various types of loans to urban customers.
> When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
> * If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
> * If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company


## Table of Contents
* [Problem Statement](#problem-statement)
* [General Info](#general-information)
* [Conclusions](#conclusions)

## Problem Statement
### Business Understanding
When a person applies for a loan, there are two types of decisions that could be taken by the company:

Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

* Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

* Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

* Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)
### Business Objectives
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

To develop your understanding of the domain, you are advised to independently research a little about risk analytics (understanding the types of variables and their significance should be enough).

## General Information
- Steps for EDA :
<ol>
    <li>Data Understanding</li>
    <li>Data Cleaning</li>
    <li>Univariate Analysis</li>
    <li>Bivariate Analysis</li>
    <li>Multivariate Analysis</li>
    <li>Conclusion</li>
</ol>
- Data Set : Loan Lending Club loans 

## Conclusions
<ol>
    <li>Univariate analysis show that Loan status of fully paid is greater than charged off.</li>
    <li>Univariate analysis show that mostly loan amount is between 5k to 20k.</li>
    <li>Univariate analysis show that grades of A,B,C greater than other grades.</li>
    <li>Bivariate analysis show that as grades moves from A to G than loan status also moves linearly fully paid to charged off.</li>
    <li>Bivariate analysis show that as interest rate increase than chance of charged off loan status also increase.</li>
    <li>Bivariate analysis show that if purpose of loan is small business than the chance of charged off loan status are more than other purpose.</li>
    <li>Bivariate analysis show that if annual incomes is low than chance of charged off loan status also increase.</li>
    <li>Segmented Univariate Analysis show that if team is increase low than chance of charged off loan status also increase.</li>
    <li>Segmented Univariate Analysis show that if interest rate is increase with purpose of debet consolidation than chance of charged off loan status also increase.</li>
    <li>Heat map show that loan amount is directly depend on funded amount,funded amount investment and installments. and loan status depends on interest rate ,loan amount,funded amount,funded amount investment and installments.</li>
</ol>

### Contributors
- Deepak Jain









