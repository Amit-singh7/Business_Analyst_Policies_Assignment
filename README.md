Insurance Policy & Claims Analytics Dashboard

Project Overview

This project simulates an insurance analytics scenario where an insurance company wants to analyze policy sales, claims activity, and portfolio profitability.

The goal of this project is to generate realistic datasets and analyze them using SQL, Python, Excel, and Power BI to identify claim trends, loss ratios, and risk exposure.

The final outcome is an interactive Power BI dashboard that provides insights into premium revenue, claim patterns, and insurance portfolio performance.

Business Problem

Insurance companies must balance premium revenue and claim payouts to remain profitable.

This project simulates 1,000,000 car insurance policies sold in 2024 and analyzes:

Total premium collected

Claims filed in 2025 and 2026

Claim cost trends

Loss ratio and profitability

Future claim liability

The analysis helps understand risk concentration and portfolio sustainability.

Dataset Description

Two datasets were created based on the assignment requirements.

Policy Sales Dataset

This dataset contains simulated records for 1,000,000 policyholders.

Key Fields
Column	Description
Customer_ID	: Unique customer identifier
Vehicle_ID : Unique vehicle identifier
Vehicle_Value : Vehicle value (₹100,000)
Premium :	₹100 × policy tenure
Policy_Purchase_Date :	Date policy was purchased
Policy_Start_Date	: Purchase date + 365 days
Policy_End_Date :	Policy expiry date
Policy_Tenure :	Policy duration (1–4 years)
Policy Tenure Distribution
Tenure	Distribution
1 Year	20%
2 Years	30%
3 Years	40%
4 Years	10%

Policies were evenly distributed across all days in 2024.

Claims Dataset

The claims dataset simulates insurance claims based on predefined business rules.

Claim Conditions (2025)

30% of vehicles purchased on:

7th

14th

21st

28th

file a claim when the policy starts.

Claim Amount:

10% of vehicle value = ₹10,000

Claim Conditions (2026)

Between Jan 1 and Feb 28 2026

10% of 4-year tenure policies file a second claim.

Claims are evenly distributed across 59 days.

Tools & Technologies Used

Python (Pandas) → Data generation & cleaning

SQL → Data analysis & queries

Excel → Data validation

Power BI → Interactive dashboard & visualization

Key KPIs Calculated

The following KPIs were used to evaluate portfolio performance.

KPI	Description
Total Policies	Total number of policies sold
Total Premium	Total revenue collected
Total Claims	Total claims filed
Total Claim Cost	Total claim payout
Loss Ratio	Claims ÷ Premium
Claim Frequency	Claims ÷ Policies
Average Claim Amount	Average cost per claim
Future Claim Liability	Estimated future claim exposure
Power BI Dashboard

The project includes an interactive Power BI dashboard with multiple analytical views.

Dashboard Pages
Portfolio Overview

Total policies

Total premium

Total claims

Loss ratio

Policy distribution by tenure

Claims Analysis

Monthly claim trend

Claim cost by year

Claims by policy tenure

Profitability & Risk

Premium vs claims comparison

Loss ratio by tenure

Future claim liability

Key Insights

Total Premium Collected: ₹240M

Total Claim Cost: ₹493M

Loss Ratio: ~205%

Key observations:

Claims exceed premium revenue, indicating an unprofitable portfolio.

Claim spikes occur in 2025 when policies become active.

3-year policies generate the most premium revenue.

Long tenure policies increase risk exposure.

Project Structure
Insurance-Claims-Analytics
│
├── dataset
│   ├── policy_sales.csv
│   ├── claims_data.csv
│
├── powerbi_dashboard
│   ├── insurance_dashboard.pbix
│
├── analysis
│   ├── sql_queries.sql
│   ├── python_data_generation.ipynb
│
└── README.md
Future Improvements

Possible enhancements for this project include:

Predictive claim modeling using machine learning

Fraud detection analysis

Customer risk segmentation

Premium pricing optimization

Author

Amit
Aspiring Data Analyst / Business Intelligence Analyst
