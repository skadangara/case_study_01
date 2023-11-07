# Lending Club Case Study - Upgrad

# Problem Statement
Lending Club is a consumer finance marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return.

It specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant's profile.

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed.

In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

The core objective of the excercise is to help the company minimise the credit loss. There are two potential sources of credit loss are:

Applicant likely to repay the loan, such an applicant will bring in profit to the company with interest rates.** Rejecting such applicants will result in loss of business**. Applicant not likely to repay the loan, i.e. and will potentially default, then approving the loan may lead to a financial loss* for the company.

# Objective
The goal is to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA using the given dataset, is the aim of this case study.

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

When a person applies for a loan, there are two types of decisions that could be taken by the company:

*Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

*Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

*Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

*Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan

*Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset).

# Overall Approach
- The overall approach is to use EDA (Exploratory Data Analysis) to find the Key Performance Indicators driving towards the defaulters of the loan.
- Major Steps Involved
- Data cleaning and preprocessing
- Univariate and Bivariate analysis
- Data visualization
- Insights and conclusion

# Technologies Used
- Python
- Jupyter Notebook
- Pandas
- Numpy
- Matplotlib and Seaborn
- Anaconda

# Team
- Sajana Kadangara




