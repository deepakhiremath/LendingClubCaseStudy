# Project Name
Lending Club Case Study

## Project Information
Solving this assignment will give you an idea about how real business problems are solved using EDA. In this case study, apart from applying the techniques you have learnt in EDA, you will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.

## Business Understanding
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company. The data given below contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
In this case study, you will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.
The data given below contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

In this case study, you will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

## EDA
	* Understanding Business Requirement
	* Understanding the data set
	* Data Cleaning 
	* Data Preparation
	* EDA
	
## Conclusions
	* Make sure the loan amount is not exceeding the threshold of dti (derived in previous slide)

	* Higher value loans are at high risk(may be its because of loan grades, which is of higher interest), so decrease the interest of higher value loans, increase it for lower value loans

	* The company should be very cautious while giving loans in small_business sector, better to decrease the loans in this sector by 50%. Increase in Car, Home development sectors

	* Higher the public record of bankruptcies higher is the risk of recovery, stop giving loans to people with higher bankruptcies
