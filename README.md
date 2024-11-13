# Bank Loan Analysis Dashboard
This repository contains a Bank Loan Analysis Dashboard created in Power BI, along with the SQL queries used for data extraction and transformation. The dashboard provides insights into loan applications, funding patterns, and borrower demographics. The project is organized into three main dashboards: Summary, Overview, and Details.

## View Dashboard
You can view the published Power BI dashboard [here](https://app.powerbi.com/view?r=eyJrIjoiZjBiMTRjMjctZTRmNi00OGM5LWI3NWUtYmFmYWEwYWU4ZmQ2IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9).

## Dashboard Sections
### 1. Summary Dashboard
The Summary Dashboard provides a high-level overview of key metrics in the loan portfolio:

Key Metrics: Total loan applications, Total Funded Amount, Total Received Amount, Average Interest Rate, and Average debt-to-income (DTI) Ratio.
Loan Quality Breakdown: Pie charts indicating proportions of Good Loans and Bad Loans.
Loan Status Breakdown: Distribution of Fully Paid, Charged Off, and Current loan statuses.

### 2. Overview Dashboard
The Overview Dashboard gives a detailed breakdown of loan distribution and application trends across categories:

Monthly Trends: Visualization of funded amount, received amount, and loan applications by month.
Category Breakdown: Analysis by State, Loan Term, Employee Length, Loan Purpose, and Home Ownership.

### 3. Details Dashboard
The Details Dashboard contains a table with customer-specific data, providing a granular view of loan applications, terms, and borrower profiles.

## SQL Queries
The repository includes SQL scripts used to prepare and aggregate data for the dashboard, covering:

- Data extraction
- Calculations for key metrics like funded and received amounts, average interest rate, and DTI ratio
- Aggregations by month, state, and other categories

