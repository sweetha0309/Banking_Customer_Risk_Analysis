🏦 Banking Risk Analysis Dashboard (Power BI + MySQL + Python EDA)
📌 Project Overview

This project focuses on analyzing customer financial data to help banks make safer and data-driven loan approval decisions.
Using Power BI, MySQL, and Python (EDA), the project identifies financially stable customers and those who pose repayment risks.

The dashboard enables the bank to decide:
✔ Who is financially stable
✔ Who may default
✔ Whether a loan should be approved or rejected

💡 Problem Statement

Banks must carefully evaluate customers before approving a loan.
If loans are issued to customers who cannot repay, the bank faces financial loss.

To solve this, Risk Analytics is used to analyze customer behavior and identify:

Customers with strong financial stability

Customers likely to default

Customers suitable for loan approval

The objective of this project is to analyze customer financial data and minimize the risk of lending to unreliable customers.

🧩 Solution Summary

An interactive Power BI dashboard was developed with rich insights derived from:

MySQL database integration

Python EDA (NumPy, Pandas, Seaborn, Matplotlib)

Relational table modeling in Power BI

The dashboard analyzes key customer factors such as:

Income

Deposits

Loans

Savings

Credit card balance

Risk weight

Business lending

Customer financial behavior over time

This helps the bank decide:
➡ Approve loan → financially strong
➡ Reject loan → high-risk customer

🗂 Dataset Description

The dataset includes multiple relational tables connected via primary & foreign keys:

1️⃣ Banking Relationship Table

Contains details about customer financial activities:

Deposits

Loans

Credit card balance

Savings

Business lending

Risk weighting

2️⃣ Client–Banking Table

Acts as the link between customer information and banking relationship.

3️⃣ Gender Table

Stores gender information (Male / Female).

4️⃣ Investment Advisor Table

Details about advisors assigned to customers.

5️⃣ Period Table

Time-based customer activity (e.g., join date).

These tables were connected inside Power BI using a star schema to enable smooth visual analysis.

🐍 Python EDA (Google Colab)

Before building the dashboard, exploratory data analysis (EDA) was performed using:

NumPy

Pandas

Matplotlib

Seaborn

Python was used to:
✔ Clean the data
✔ Check distributions
✔ Identify outliers
✔ Analyze loan patterns
✔ Understand customer financial behavior

🛢 Database Integration (MySQL → Power BI)

MySQL was used to store the raw customer financial tables.

Power BI was connected directly to MySQL for real-time extraction.

SQL queries were used to filter, join, and prepare data for analysis.

📊 Power BI Dashboard Highlights

The dashboard includes:

KPIs: Total Customers, Income, Loans, Deposits

Loan Risk Score

Customer Stability Rating

Financial Activity Breakdown

Advisor-wise Performance

Risk Weight Analysis

Loan Approval Recommendation Indicators

This helps the bank quickly identify the risk level of every customer.