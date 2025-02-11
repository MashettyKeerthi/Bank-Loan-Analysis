# Bank-Loan-Analysis

## **Objective**
This project aims to develop an interactive analytics dashboard for monitoring loan performance and extracting valuable insights. The dashboard will feature Key Performance Indicators (KPIs), dynamic grid views, and data visualizations to help financial analysts and loan officers make data-driven decisions.

## **Summary**
The dashboard uses interactive visualizations and key financial metrics to monitor loan trends, assess risks, and categorize loans as Good Loans or Bad Loans. It processes loan data using Power Query and DAX functions, ensuring accurate reporting with Month-to-Date (MTD), Year-to-Date (YTD), and Month-over-Month (MoM) calculations.

## **Key Features**

 **A. Loan Performance Metrics(KPIs)**

**1. Total Loan Applications**
- Calculate the total number of loan applications received within a specified period.
- Track Month-to-Date (MTD) Loan Applications to measure recent application trends.
- Monitor Month-over-Month (MoM) changes to analyze loan application growth or decline.

**2. Total Funded Amount**
- Measure the total funds disbursed as loans over a given period.
- Track the MTD Total Funded Amount to assess recent loan disbursements.
- Analyze MoM variations to understand changes in loan funding trends.

**3. Total Amount Received**
- Monitor the total repayments collected from borrowers.
- Evaluate the MTD Total Amount Received to track recent collections.
- Observe MoM changes to identify repayment patterns and trends.

**4. Average Interest Rate**
- Calculate the average interest rate across all loans.
- Track MTD Average Interest Rate to assess recent loan costs.
- Monitor MoM fluctuations to analyze changes in lending rates.

**5. Average Debt-to-Income Ratio (DTI)**
- Evaluate the average DTI of borrowers to gauge their financial health.
- Compute MTD DTI to track recent borrower affordability.
- Analyze MoM changes to assess financial risk trends.

**B. Good Loan vs. Bad Loan Analysis**

**1.Good Loan KPIs:**

- Good Loan Application Percentage
- Good Loan Applications Count
- Good Loan Funded Amount
- Good Loan Total Received Amount
  
**2. Bad Loan KPIs:**

- Bad Loan Application Percentage
- Bad Loan Applications Count
- Bad Loan Funded Amount
- Bad Loan Total Received Amount

**C. Loan Status Grid View**

A table that categorizes loans based on status, showing:
- Total Applications, Funded Amount, Received Amount
- MTD Funded & Received Amount
- Average Interest Rate & DTI

## Charts & Visualizations

**1. Monthly Trends by Issue Date (Area Chart)**
- **Objective:** Identify seasonality and long-term lending trends.
- **Insights:** Helps analyze peak loan issuance periods and fluctuations over time.

**2️. Regional Analysis by State (Shape Map)**
- **Objective:** Identify regions with significant lending activity and assess regional disparities.
- **Insights:** Highlights geographical lending patterns and risk-prone areas.

**3️. Loan Term Analysis (Donut Chart)**
- **Objective:** Understand the distribution of loans across various term lengths.
- **Insights:** Assists in evaluating borrower preferences for short-term vs. long-term loans.

**4️. Employee Length Analysis (Bar Chart)**
- **Objective:** Assess how employment history impacts loan applications.
- **Insights**: Examines loan approval likelihood based on borrower job stability.

**5️. Loan Purpose Breakdown (Bar Chart)**
- **Objective:** Provide a breakdown of loan metrics based on stated loan purposes.
- **Insights:** Identifies the primary reasons borrowers seek financing.

**6️. Home Ownership Analysis (Tree Map)**
- **Objective**: Visualize how home ownership status affects loan applications and disbursements.
- **Insights:** Evaluates borrower profiles based on property ownership.

**Metrics for Visualizations:**
- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Dashboard interaction

## Workflow & Data Processing

- **Data Import** – Load loan data from CSV files.
- **Data Cleaning** – Remove duplicates, handle missing values.
- **Data Modeling** – Establish relationships between data tables.
- **Power Query Transformation** – Process and structure data.
- **DAX Calculations** – Use formulas for KPIs and comparisons (MTD, YTD, MoM).

## Technical Features
- **Date Tables:** Use date tables for time-based calculations.
- **Time Intelligence Functions:** Implement Month-to-Date (MTD), Year-to-Date (YTD), and Month-over-Month (MoM) calculations.
- **DAX Functions:** Date Functions,Text Functions,Filter Functions,CALCULATE,SUM/SUMX

## Dashboard Creation

- **KPIs:** Create and display key metrics using Card visuals.
- **Charts:** Design interactive charts for trend and comparative analysis.
- **Formatting Visuals:** Ensure visuals are consistent and easy to interpret.
- **Navigation:** Add buttons or bookmarks for seamless navigation within the dashboard.

This dashboard is designed to help financial analysts and loan officers make data-driven decisions by providing clear and insightful loan performance tracking. 
 
