 
Please check the file Riskscore.ipynb is the complete project

The other files are the experiments with TensorFlow and machinelearning

# Case Study
Objective: Predict RiskScore to assess loan default or financial instability. Developing a RiskScore model to help a bank assess creditworthiness more effectively

# Personal and Demographic Details:
1. ApplicationDate: The date the loan application was submitted.
2. Age: Applicant's age.
3. MaritalStatus: Applicant's marital status (e.g., Single, Married, Divorced).
4. NumberOfDependents: Number of dependents the applicant is supporting.
5. Employment and Education:
6. EmploymentStatus: Applicant's employment status (e.g., Employed, Self-Employed, Unemployed).
7. EducationLevel: Applicant's highest level of education (e.g., High School, Bachelor's, Master's).
8. Experience: Total years of work experience.
9. JobTenure: Length of time at the current job.
# Income and Assets:
1. AnnualIncome: Applicant's annual income.
2. MonthlyIncome: Applicant's monthly income.
3. SavingsAccountBalance: Current balance in the applicant's savings account.
4. CheckingAccountBalance: Current balance in the applicant's checking account.
5. TotalAssets: Total assets owned by the applicant.
6. NetWorth: Applicant's net worth, calculated as TotalAssets - TotalLiabilities.
7. Financial Obligations and Debt:
8. LoanAmount: The amount of loan applied for.
9. LoanDuration: Duration of the loan in months or years.
10. MonthlyLoanPayment: The calculated monthly payment for the loan.
11. TotalLiabilities: Total financial liabilities or debts of the applicant.
12. MonthlyDebtPayments: Total monthly payments toward existing debts.
13. CreditCardUtilizationRate: The percentage of available credit currently used by the applicant.
14. NumberOfOpenCreditLines: Total number of active credit lines.
15. NumberOfCreditInquiries: Number of credit inquiries made recently.
16. DebtToIncomeRatio: Ratio of monthly debt payments to monthly income.
17. TotalDebtToIncomeRatio: A more comprehensive debt-to-income ratio, factoring in all liabilities.
18. UtilityBillsPaymentHistory: Payment history for utility bills (e.g., consistent, delayed).
19. BankruptcyHistory: Indicates if the applicant has a history of bankruptcy (Yes/No).
20. PreviousLoanDefaults: Number of past loan defaults.
# Credit Profile:
1. CreditScore: Applicant's credit score.
2. PaymentHistory: History of payments on previous loans (e.g., On-time, Late, Defaulted).
3. LengthOfCreditHistory: Total years of credit history.
# Loan Details:
1. LoanPurpose: Reason for taking the loan (e.g., Home Purchase, Car Loan, Education).
2. BaseInterestRate: The baseline interest rate for the loan.
3. InterestRate: Final interest rate applied after factoring in risk and other parameters.
# Risk and Approval:
1. LoanApproved: Whether the loan application was approved (Yes/No).
2. RiskScore: A calculated score representing the risk level associated with the applicant.


# Most Important Factors likely to influence Risk Score
DebtToIncomeRatio
CreditScore
MonthlyDebtPayments
NetWorth
SavingsAccountBalance
PaymentHistory
BankruptcyHistory
LoanAmount
NumberOfCreditInquiries
CreditCardUtilizationRate
