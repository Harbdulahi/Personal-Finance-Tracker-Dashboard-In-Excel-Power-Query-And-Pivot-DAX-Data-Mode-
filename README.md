# Personal Finance Tracker Dashboard

## Overview
This project is a personal finance analytics dashboard focused on tracking income, expenses, and savings over time.  
The goal is to provide a single, decision-oriented view of financial behavior, not raw transaction logs.

The dashboard answers one core question:
**How effectively is income being converted into savings, and where is money being spent?**

## Objective
- Track total income, expenses, and savings.
- Monitor trends over time.
- Identify dominant income sources.
- Identify expense drivers by category and payment method.
- Enable quick financial assessment without manual calculations.

## Key Features
- **KPI Cards**
  - Total Income
  - Expense Rate (%)
  - Savings / Balance (%)
  - Month-over-Month comparison

- **Time Series Analysis**
  - Income vs Expense vs Savings trend

- **Distribution Analysis**
  - Income sources share
  - Expense sources by category
  - Expense sources by payment method

- **Filtering**
  - Year and quarter slicers for time-based analysis

## Metrics Defined
- **Income**: Total inflow for the selected period.
- **Expenses**: Total outflow for the selected period.
- **Savings**: Income minus expenses.
- **Expense %**: Expenses / Income.
- **Savings %**: Savings / Income.

## Data Model
- **Fact Table**
  - Transactions (amount, date, type, category, payment method)

- **Dimension Tables**
  - Date

## Tools
- Data modeling
- DAX
- Dashboard design
- Excel(source data)

## DAX Concepts Used
- Measures instead of calculated columns
- Time intelligence
- Percentage calculations
- Context-aware aggregations

## Insights Demonstrated
- Expense growth relative to income.
- Categories responsible for cost spikes.
- Mortgage and Credit Card payments are driving most expenses.
- Periods where the savings rate declines despite stable income.

## Limitations
- Sample / simulated data.
- No automated bank integration.
- No forecasting or ML-based predictions.


## Screenshots
![Personal Finance Tracker](https://github.com/Harbdulahi/Personal-Finance-Tracker-Dashboard-In-Excel-Power-Query-And-Pivot-DAX-Data-Mode-/blob/main/PFT/Screenshot%202025-12-14%20095351.jpg?raw=true)

## Why This Project Matters
This project demonstrates:
- Business-focused dashboard design
- Clear metric definitions
- Proper data modeling
- Ability to turn raw transactions into insights

---

**Author**: Abdulahi Salaudeen  
**Role Focus**: Data Analyst / BI Analyst  
**Skills Demonstrated**: Data Modeling, KPI and Dashboard Design, Financial Analysis

