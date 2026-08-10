# Telco Customer Churn Dashboard

A Power BI dashboard analyzing customer churn behavior for a telecom company, built to help stakeholders understand why customers leave and where to focus retention efforts.

## Project Overview

Customer churn directly affects recurring revenue. This dashboard breaks down the customer base by contract type, payment method, tenure, and support activity to surface the segments most at risk of churning, and quantifies the revenue impact of that churn.

## Business Objectives

- Measure overall churn rate and track it against retained customers
- Identify which contract types and payment methods correlate with higher churn
- Quantify monthly revenue lost to churned customers
- Highlight the effect of support ticket volume (admin/technical) on customer retention
- Give stakeholders a KPI view they can act on without digging into raw data

## Dataset Description

The dataset (`01 Churn-Dataset`) is the well-known **IBM Telco Customer Churn** sample dataset — anonymized, publicly available sample data used for churn-analysis training and demos (no real customer PII). Key fields used in this report:

| Field | Description |
|---|---|
| `gender`, `Partner`, `Dependents` | Customer demographics |
| `tenure` | Months the customer has stayed with the company |
| `Contract` | Contract type (month-to-month, one year, two year) |
| `PaymentMethod` | How the customer pays |
| `MonthlyCharges`, `TotalCharges` | Billing amounts |
| `Customer status` | Active / Churned |
| `numAdminTickets`, `numTechTickets` | Support tickets raised by the customer |

A separate `KPIS Measures` table holds the calculated DAX measures (Churn Rate, Retained Customers, Monthly Revenue Loss, % of Revenue, Total Customers, Total Monthly Charge).

## Tools & Technologies

- Power BI Desktop (data modeling, DAX measures, report design)
- DAX for KPI calculations
- Power Query for data shaping

## Dashboard Preview

> _Screenshots pending — export pages from Power BI Desktop (File → Export → PDF or a screen capture of each page) and drop them in the `Images/` folder, then reference them here, e.g.:_
> `![Overview page](Images/overview.png)`

## Key KPIs

| Metric | Value |
|---|---|
| Total Customers | _fill in from dashboard_ |
| Churn Rate | _fill in from dashboard_ |
| Churned Customers | _fill in from dashboard_ |
| Retained Customers | _fill in from dashboard_ |
| Monthly Revenue Loss | _fill in from dashboard_ |
| % of Revenue (lost) | _fill in from dashboard_ |

## Key Insights

_Add 3–4 findings once you review the dashboard, e.g. which contract type churns most, whether support tickets correlate with churn, which payment method has the highest churn rate._

## Business Recommendations

_Add actionable recommendations based on the insights above (e.g. incentivize longer contracts, follow up with customers who raise multiple support tickets, etc.)._

## Repository Structure

```
Telco-Customer-Churn-Dashboard/
├── Power BI/
│   └── Customers.pbix
├── Images/
│   └── (dashboard screenshots)
└── README.md
```

## Skills Demonstrated

- Data modeling and relationships in Power BI
- DAX measures for KPI calculation
- Dashboard/report design for business stakeholders
- Churn analysis methodology

## About the Author

Mohamed Farag Saied
