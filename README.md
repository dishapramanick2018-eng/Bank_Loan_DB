 Bank Loan Report Analysis
📖 Project Overview
The Bank Loan Report Analysis project is a comprehensive banking analytics solution built using SQL and Business Intelligence concepts. The project analyzes loan application data to provide insights into lending performance, repayment behavior, loan quality, and borrower characteristics.
The dashboard helps stakeholders monitor portfolio health, identify risk patterns, evaluate loan performance, and make data-driven lending decisions.
________________________________________
🎯 Business Objective
Banks handle thousands of loan applications and active loans. This project aims to:
•	Monitor loan portfolio performance.
•	Analyze loan application trends.
•	Track funded and recovered amounts.
•	Identify good and bad loans.
•	Evaluate borrower demographics and risk factors.
•	Support strategic lending decisions.
________________________________________
🛠️ Tools & Technologies
•	SQL Server
•	SQL Server Management Studio (SSMS)
•	Power BI / Tableau
•	Microsoft Excel
•	GitHub
________________________________________
📂 Dataset Information
Table Name: bank_loan_data
The dataset contains information related to:
Borrower Details
•	Loan ID
•	Address State
•	Employee Length
•	Employee Title
•	Home Ownership
•	Annual Income
Loan Details
•	Loan Amount
•	Interest Rate
•	Instalment
•	Loan Term
•	Loan Purpose
Credit Information
•	Grade
•	Sub Grade
•	Verification Status
•	Debt-to-Income Ratio (DTI)
Loan Performance
•	Loan Status
•	Issue Date
•	Last Payment Date
•	Next Payment Date
•	Total Payment
________________________________________
📊 Dashboard 1: Summary Report
The Summary Dashboard provides a high-level overview of lending performance.
Key Performance Indicators (KPIs)
Loan Applications
•	Total Loan Applications
•	Month-to-Date (MTD) Applications
•	Previous Month-to-Date (PMTD) Applications
Funded Amount
•	Total Funded Amount
•	MTD Funded Amount
•	PMTD Funded Amount
Amount Received
•	Total Amount Received
•	MTD Amount Received
•	PMTD Amount Received
Interest Rate Analysis
•	Average Interest Rate
•	MTD Interest Rate
•	PMTD Interest Rate
Debt-to-Income Analysis
•	Average DTI
•	MTD DTI
•	PMTD DTI
________________________________________
Good Loan Analysis
Good Loans Include
•	Fully Paid
•	Current
Metrics
•	Good Loan Percentage
•	Good Loan Applications
•	Good Loan Funded Amount
•	Good Loan Amount Received
Formula
(COUNT(Good Loans) * 100.0) / COUNT(All Loans)
________________________________________
Bad Loan Analysis
Bad Loans Include
•	Charged Off
Metrics
•	Bad Loan Percentage
•	Bad Loan Applications
•	Bad Loan Funded Amount
•	Bad Loan Amount Received
Formula
(COUNT(Bad Loans) * 100.0) / COUNT(All Loans)
________________________________________
Loan Status Analysis
The report provides a detailed breakdown by loan status including:
•	Loan Count
•	Total Funded Amount
•	Total Amount Received
•	Average Interest Rate
•	Average DTI
________________________________________
📈 Dashboard 2: Overview Report
The Overview Dashboard provides detailed segmentation and trend analysis.
________________________________________
Monthly Trends
Measures:
•	Total Loan Applications
•	Total Funded Amount
•	Total Amount Received
Purpose:
•	Identify seasonal lending trends.
•	Monitor business growth over time.
________________________________________
State Analysis
Measures:
•	Loan Applications by State
•	Funded Amount by State
•	Amount Received by State
Purpose:
•	Analyze geographic distribution of lending activities.
________________________________________
Loan Term Analysis
Categories:
•	36 Months
•	60 Months
Purpose:
•	Compare short-term and long-term lending performance.
________________________________________
Employment Length Analysis
Measures loan performance based on employment duration.
Purpose:
•	Evaluate borrower stability and repayment potential.
________________________________________
Loan Purpose Analysis
Examples:
•	Debt Consolidation
•	Credit Card
•	Home Improvement
•	Education
•	Small Business
Purpose:
•	Understand borrower intentions and lending demand.
________________________________________
Home Ownership Analysis
Categories:
•	Rent
•	Mortgage
•	Own
•	Other
Purpose:
•	Assess borrower financial stability.
________________________________________
📋 Data Dictionary
Loan ID
Unique identifier assigned to each loan application.
Business Use
Used to track and manage loans throughout their lifecycle.
________________________________________
Address State
Borrower's state of residence.
Business Use
Helps identify regional lending trends and risk exposure.
________________________________________
Employee Length
Duration of borrower's employment.
Business Use
Measures employment stability and repayment capability.
________________________________________
Employee Title
Borrower's occupation.
Business Use
Used to verify income sources and employment information.
________________________________________
Grade
Loan risk classification.
Business Use
Used for risk assessment and interest rate determination.
________________________________________
Sub Grade
Detailed risk category within a grade.
Business Use
Provides more granular borrower risk segmentation.
________________________________________
Home Ownership
Borrower's housing status.
Business Use
Used to assess financial stability and risk.
________________________________________
Issue Date
Date when loan was issued.
Business Use
Used for portfolio aging and trend analysis.
________________________________________
Loan Status
Current status of loan.
Examples:
•	Fully Paid
•	Current
•	Charged Off
Business Use
Measures loan performance and portfolio health.
________________________________________

Purpose
Reason for obtaining the loan.
Business Use
Used to analyze customer borrowing behavior.
________________________________________
Term
Loan repayment duration.
Business Use
Used to evaluate maturity structure of the loan portfolio.
________________________________________
Verification Status
Income verification status.
Business Use
Measures credibility of borrower information.
________________________________________
Annual Income
Borrower's yearly income.
Business Use
Used to determine repayment capability and eligibility.
________________________________________
Debt-to-Income Ratio (DTI)
Ratio of debt obligations to income.
Business Use
Assesses borrower affordability and credit risk.
________________________________________
Instalment
Fixed monthly payment amount.
Business Use
Used to evaluate affordability and repayment schedules.
________________________________________
Interest Rate
Annual borrowing cost.
Business Use
Determines profitability and risk pricing.
________________________________________
Loan Amount
Principal amount borrowed.
Business Use
Represents lending exposure and portfolio size.
________________________________________
🚀 How to Run the Project
Step 1
Create a SQL Server Database.
CREATE DATABASE BankLoanDB;
Step 2
Import the dataset into SQL Server.
Step 3
Execute the SQL queries provided in the project.
Step 4
Connect Tableau to the SQL database.
Step 5
Build the dashboards using the generated KPIs and reports.
________________________________________
💡 Key Insights
•	Track total lending activity and growth.
•	Measure loan repayment performance.
•	Identify high-risk and low-risk loan segments.
•	Analyze borrower demographics.
•	Evaluate regional lending trends.
•	Monitor portfolio health and credit exposure.
________________________________________
🔮 Future Enhancements
•	Loan Default Prediction Model
•	Credit Risk Scoring Dashboard
•	Customer Segmentation Analysis
•	Real-Time Data Integration
•	Branch Performance Analytics
•	Machine Learning-Based Risk Assessment
________________________________________
👨💻 Author
Disha Pramanick
•	LinkedIn: www.linkedin.com/in/disha-pramanick-96545a380
________________________________________


⭐ Project Highlights
✔ Banking Domain Analytics
✔ SQL Data Analysis
✔ KPI Dashboard Reporting
✔ Loan Portfolio Analysis
✔ Credit Risk Monitoring
✔ Business Intelligence & Visualization

