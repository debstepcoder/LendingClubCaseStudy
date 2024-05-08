# Lending Club Case Study
> Solving this Project will give you an idea of how real business problems are addressed using EDA. In this case study, besides applying the techniques learned in EDA, you'll also develop a basic understanding of risk analytics in banking and financial services. You'll understand how data is utilized to minimize the risk of losing money while lending to customers.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
You work for a consumer finance company specializing in lending various types of loans to urban customers. When the company receives a loan application, it has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
2. If the applicant is not likely to repay the loan, i.e., he/she is likely to default, then approving the loan may lead to a financial loss for the company.

The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns that indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

When a person applies for a loan, there are two types of decisions that could be taken by the company:

**Loan accepted:**
If the company approves the loan, there are 3 possible scenarios described below:

- **Fully paid:** Applicant has fully paid the loan (the principal and the interest rate).
- **Current:** Applicant is in the process of paying the installments, i.e., the tenure of the loan is not yet completed. These candidates are not labeled as 'defaulted'.
- **Charged-off:** Applicant has not paid the installments in due time for a long period, i.e., he/she has defaulted on the loan.

**Loan rejected:**
The company had rejected the loan (because the candidate does not meet their requirements, etc.). Since the loan was rejected, there is no transactional history of those applicants with the company, and thus this data is not available in this dataset.

### Business Objectives
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labeled as 'charged-off' are the 'defaulters'.

If one is able to identify these risky loan applicants, then such loans can be reduced, thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e., the variables which are strong indicators of default. The company can utilize this knowledge for its portfolio and risk assessment.

To develop your understanding of the domain, you are advised to independently research a little about risk analytics (understanding the types of variables and their significance should be enough).

### Presentation of the Overall Approach of the Analysis
- Mention the problem statement and the analysis approach briefly.
- Explain the results of univariate, bivariate analysis, etc., in business terms.
- Include visualizations and summarize the most important results in the presentation.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Lending club should reduce the high interest loans for 60 months tenure, they are prone to loan default.
- Lending Club should control their number of loan issues to borrowers who are from CA, FL and NY to make profits.
- Borrowers with mortgage home ownership are taking higher loans and defaulting the approved loans. Lending club should stop giving loans to this category when loan amount requested is more than 12000.
- Small business loans are defaulted more. Lending club should stop/reduce issuing the loans to them.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python v3.10
- Matplotlib v3.5.0
- Numpy v1.21.5
- Pandas v1.3.5
- Seaborn v0.11.2


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was inspired by...
- References if any...
- This project was based on [UpGrad tutorials on Exploratory Data Analysis (EDA) on the learning platform : ](https://www.upgrad.com/machine-learning-ai-pgd-iiitb/).


## Contact
Created by [@debstepcoder] - feel free to contact me!




