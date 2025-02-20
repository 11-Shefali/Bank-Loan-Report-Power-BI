# Bank Loan Report - README

## Problem Statement
Banks need to efficiently analyze loan application data to assess lending performance, monitor loan repayment trends, and manage credit risk. A comprehensive reporting system is required to track key financial metrics, identify potential risks, and optimize decision-making in loan approvals and collections. This report provides a data-driven approach to understanding loan trends, borrower behavior, and financial performance, enabling the bank to enhance operational efficiency and reduce default risks.

## Overview
This Bank Loan Report is created using Power BI and provides a detailed analysis of loan applications, funded amounts, received amounts, interest rates, and loan performance metrics. The report consists of three main sections: **Summary**, **Overview**, and **Table-View**.

## 1. Summary Page
This page provides a high-level overview of the loan performance and key statistics.

### Key Metrics:
- **Total Loan Applications:** 38.6K applications were received in total.
  - **MTD (Month-to-Date):** 4.31K applications.
  - **MoM (Month-over-Month):** 14K applications.
  - *Why this metric?* Tracking total loan applications helps the bank understand demand trends, identify peak loan application periods, and allocate resources efficiently. A rise or fall in applications can signal economic changes or shifts in borrower behavior.

- **Total Funded Amount:** $436M
  - **MTD Funded Amount:** $54M
  - **MoM Growth:** 13.04%
  - *Why this metric?* It shows the actual disbursement of loans, reflecting the bank’s lending activity. Growth in funding suggests increasing market confidence and strong borrower eligibility.

- **Total Amount Received:** $473M
  - **MTD Amount Received:** $58M
  - *Why this metric?* This represents loan repayments and interest collection. It helps assess revenue from lending activities and detect potential repayment issues.

- **Average Interest Rate:** 12.05%
  - **MTD Rate:** 12.4%
  - **MoM Change:** 3.47%
  - *Why this metric?* Monitoring interest rates helps the bank manage risk and profitability. A rising trend might indicate tightening credit conditions, while a decrease could suggest a competitive lending market.

- **Debt-to-Interest Ratio:** 13.33%
  - **MTD:** 13.67%
  - **MoM Change:** 2.73%
  - *Why this metric?* This metric helps assess borrower financial health and risk. A high ratio may indicate increasing borrower leverage, potentially leading to higher defaults.

### Loan Performance Breakdown:
- **Good Loans Issued:** 86.18% of loans are considered good loans.
  - **Total Good Loan Applications:** 33K
  - **Funded Amount for Good Loans:** $370.2M
  - **Total Received Amount from Good Loans:** $435.8M
  - *Why this metric?* A high percentage of good loans indicates strong underwriting policies and lower risk exposure for the bank.

- **Bad Loans Issued:** 13.82% of loans are classified as bad loans.
  - **Total Bad Loan Applications:** 5K
  - **Funded Amount for Bad Loans:** $65.5M
  - **Total Received Amount from Bad Loans:** $37.3M
  - *Why this metric?* Monitoring bad loans helps evaluate credit risk and potential losses. A growing trend could indicate economic distress or weaker lending policies.

### Loan Status Breakdown:
A table summarizes loan applications by status:
- **Charged Off:** 5,333 applications, $65M funded.
- **Current:** 1,098 applications, $18M funded.
- **Fully Paid:** 32,145 applications, $351M funded.
- **Grand Total:** 38,576 applications, $435M funded.
- *Why this metric?* It provides insight into loan repayment trends, helping the bank measure default rates and collection effectiveness.

## 2. Overview Page
This page provides insights into loan applications using visual analytics.

### Visualizations:
- **Total Loan Applications by Month:** 
  - Loan applications show a trend from January (2.3K) to December (4.3K), indicating a gradual increase in applications.
  - *Why this metric?* Seasonal trends can be identified, allowing the bank to plan lending strategies accordingly.

- **Total Loan Applications by State:**
  - A U.S. map representation shows the distribution of applications by state.
  - *Why this metric?* Identifies regions with high demand, helping in market expansion and risk diversification.

- **Total Loan Applications by Term:**
  - **36 Months:** 10K applications (26.8%)
  - **60 Months:** 28K applications (73.2%)
  - *Why this metric?* Helps the bank understand borrower preferences and manage portfolio maturity.

- **Total Loan Applications by Employment Length:**
  - **10+ Years:** 8.9K applications
  - **<1 Year:** 4.6K applications
  - **2 Years:** 4.4K applications
  - **3 Years:** 4.1K applications
  - *Why this metric?* Employment length correlates with borrower stability and default risk assessment.

- **Total Loan Applications by Purpose:**
  - **Debt Consolidation:** 18K applications
  - **Credit Card:** 5K applications
  - **Home Improvement:** 3K applications
  - **Major Purchase:** 2K applications
  - **Small Business:** 2K applications
  - **Car Loans:** 1K applications
  - *Why this metric?* Helps in designing targeted loan products and risk assessment for different purposes.

- **Total Loan Applications by Home Ownership:**
  - Majority of applicants have **mortgages**, followed by those who **rent**.
  - *Why this metric?* Home ownership status is a key factor in assessing collateral security and default risk.

## 3. Table-View Page
This page provides a tabular breakdown of individual loan applications with key attributes.

### Data Fields:
- **ID:** Unique identifier for each loan application.
- **Purpose:** Loan purpose such as debt consolidation, credit card, or small business.
- **Home Ownership:** Applicant's home ownership status (Rent, Mortgage, Own).
- **Grade & Sub-Grade:** Loan grades assigned to applicants.
- **Issue Date:** Date of loan issuance.
- **Total Funded Amount:** Amount funded for the loan.
- **Sum of Interest Rate:** Interest rate assigned to the loan.
- **Sum of Installment:** Total installment payable for the loan.

### Aggregated Totals:
- **Total Funded Amount:** $435.75M
- **Total Sum of Interest Rate:** 4,647.96
- **Total Sum of Installments:** $1.26B

## Steps to Create the Dashboard in Power BI
1. **Data Import:** Import the loan data from a CSV or database into Power BI.
2. **Data Cleaning & Transformation:** Use Power Query to clean missing values, format data types, and create calculated columns.
3. **Creating Relationships:** Establish relationships between tables for effective filtering and analysis.
4. **Measure Creation:** Define key DAX measures such as total funded amount, interest rates, and loan performance metrics.
5. **Visualizations:** Create bar charts, line charts, maps, and tables to display insights.
6. **Filtering & Slicers:** Add interactive filters to allow users to explore data by state, purpose, and loan term.
7. **Dashboard Formatting:** Enhance the design using themes, tooltips, and proper labeling for better readability.

## Conclusion
This Power BI report provides a comprehensive view of the bank's loan data with visual insights, tabular breakdowns, and key performance indicators. The report allows filtering by **State**, **Purpose**, **Grade**, and **Measure** to explore specific insights. The detailed metrics help the bank assess lending performance, track repayments, manage risk, and make data-driven financial decisions.

