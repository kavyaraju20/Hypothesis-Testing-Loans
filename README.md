# Lending Club Loans Data Analysis

## Business Problem 1

### Background
Lending Club is a peer-to-peer lending platform where members can lend and borrow money. The platform provides anonymized data on loans and borrowers, which can be used for analysis.

### Business Problem
Using Lending Club loans data, the team aims to test the following hypotheses to understand the relationships between various factors:

1. **Interest rate variation with loan amount**: Higher loan amounts are charged lower interest rates.
2. **Loan length impact on interest rate**: Loan length directly affects the interest rate.
3. **Interest rate differences based on loan purpose**: Interest rates vary depending on the purpose of the loan.
4. **Relationship between FICO scores and home ownership**: Individuals who own homes tend to have higher FICO scores.

---

## Dataset Information

### File: `LoansData.csv`

The dataset contains the following variables:

| Variable Name | Data Type | Description |
|--------------|----------|-------------|
| `Amount.Requested` | Numeric | Loan amount requested by the applicant (in dollars). |
| `Amount.Funded.By.Investors` | Numeric | Loan amount funded by investors (in dollars). |
| `Interest.rate` | Character | Interest rate charged to the borrower. |
| `Loan.length` | Character | Duration of the loan (in months). |
| `Loan.Purpose` | Categorical | Stated purpose of the loan. |
| `Debt.to.Income.Ratio` | Character | Percentage of consumer’s gross income used for debt repayment. |
| `State` | Character | U.S. state abbreviation of the applicant. |
| `Home.ownership` | Character | Indicates whether the applicant owns, rents, or has a mortgage. |
| `Monthly.income` | Categorical | Monthly income of the applicant (in dollars). |
| `FICO.range` | Categorical | FICO score range of the applicant (e.g., "650-655"). |
| `Open.CREDIT.Lines` | Numeric | Number of open lines of credit at the time of application. |
| `Revolving.CREDIT.Balance` | Numeric | Total outstanding balance across all lines of credit. |
| `Inquiries.in.the.Last.6.Months` | Numeric | Number of credit inquiries in the last six months. |
| `Employment.Length` | Character | Length of employment at the current job. |

---

## Analysis Plan
To validate the hypotheses, the following statistical methods will be used:
- **Hypothesis testing** (e.g., t-tests, ANOVA) to determine relationships between interest rates, loan amounts, loan purposes, and loan lengths.
- **Correlation analysis** to explore the relationship between FICO scores and home ownership.
- **Data visualization** to identify trends and patterns in the dataset.

---

## How to Use
1. Load the dataset into a data analysis tool such as Python (Pandas, NumPy) or R.
2. Perform data cleaning and preprocessing (handling missing values, converting data types, etc.).
3. Apply statistical tests and visualize results to draw insights.
4. Validate the hypotheses and summarize findings.

---
## License

This dataset is publicly available and used for analytical purposes only. Please ensure compliance with data usage policies.





