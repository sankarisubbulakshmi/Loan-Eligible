# Loan Eligible Dataset
## Overview
This dataset contains information about loan applicants and their eligibility for loans. 
It includes various features related to the applicant's personal details, income, loan amount, and loan status. This data is useful for analyzing factors that influence loan approval and assessing eligibility criteria.

## Data Description
The dataset includes the following columns:

1. Loan_ID: Unique identifier for each loan application.
2. Gender: Gender of the applicant (e.g., Male, Female).
3. Married: Marital status of the applicant (e.g., Yes, No).
4. Dependents: Number of dependents of the applicant.
5. Education: Education level of the applicant (e.g., Graduate, Not Graduate).
6. Self_Employed: Whether the applicant is self-employed (e.g., Yes, No).
7. ApplicantIncome: Monthly income of the applicant.
8. CoapplicantIncome: Monthly income of the coapplicant, if any.
9. LoanAmount: Loan amount applied for.
10. Loan_Amount_Term: Term of the loan in months.
11. Credit_History: Credit history status of the applicant (1 for good credit history, 0 for bad credit history).
12. Property_Area: Area of the property (e.g., Urban, Rural, Semiurban).
13. Loan_Status: Status of the loan application (e.g., Y for approved, N for not approved).

## Learning outcomes
This dataset is suitable for various types of analyses:

### Supervised Learning:
Predicting Loan_Status based on features such as Gender, Married, Dependents, Education, Self_Employed, ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, Credit_History, and Property_Area.
Predicting LoanAmount based on other features like ApplicantIncome, CoapplicantIncome, and Credit_History.
### Unsupervised Learning:
Clustering applicants based on features like ApplicantIncome, CoapplicantIncome, LoanAmount, and Credit_History to identify patterns or segments.
Analyzing Property_Area and Credit_History to understand their impact on Loan_Status or other features.

## Data Source
The dataset was sourced from kaggle
