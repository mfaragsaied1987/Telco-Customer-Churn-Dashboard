# 📊 Telco Customer Churn Dashboard

> An end-to-end **Business Intelligence and Data Analytics project** built with **Power BI** to analyze customer churn, identify high-risk customer segments, understand revenue impact, and translate data-driven insights into actionable retention strategies.

---

## 📌 Project Overview

Customer churn is a major challenge for subscription-based businesses, as losing existing customers directly affects recurring revenue and long-term customer value.

This project analyzes customer demographics, contracts, tenure, charges, payment methods, and support interactions to understand customer churn patterns and identify opportunities for retention.

The dashboard breaks the analysis down by tenure, support tickets, charges, and payment behavior, then rolls everything up into a demographic/executive overview with the core churn KPIs.

---

## 🎯 Business Objectives

- Measure the overall customer churn rate.
- Identify customer segments with higher churn rates (age group, contract type, payment method).
- Analyze the relationship between churn, contract type, and customer tenure.
- Analyze billing, charges, and payment behavior.
- Examine customer support ticket volume (technical vs. administrative).
- Measure the financial impact of customer churn.
- Translate analytical findings into actionable retention recommendations.

---

## 📂 Dataset

The dataset used is the well-known **IBM Telco Customer Churn** sample dataset — anonymized, publicly available data used for churn-analysis training and demos (no real customer PII). It covers:

- 👤 Customer Demographics (gender, senior citizen, partner, dependents)
- 📅 Customer Tenure
- 📄 Contract Type
- 💳 Billing & Payment Methods
- 💰 Monthly & Total Charges
- 🎫 Technical & Administrative Support Tickets
- ❌ Customer Status (Churned / Retained)

---

## 🛠️ Tools & Technologies

- 📊 Power BI
- ⚡ DAX
- 🔄 Power Query
- 🗄️ Data Modeling
- 📈 Data Visualization
- 💼 Business Intelligence

---

# 🖥️ Dashboard Preview

## 👥 Demographic Analysis

![Demographic Analysis](Images/demographic-analysis.png)

The overview page: total customers, churn rate, monthly revenue loss, and a breakdown of the customer base by gender, citizenship (senior/young), partner, and dependents.

---

## 📅 Account Details — Tenure

![Account Details Tenure](Images/account-details-tenure.png)

Average tenure for retained vs. churned customers, and churn rate broken down by contract type (month-to-month, one year, two year).

---

## 🎫 Account Details — Tickets

![Account Details Tickets](Images/account-details-tickets.png)

Administrative and technical support ticket volume, split by customer status and by citizenship segment.

---

## 💰 Account Details — Charge

![Account Details Charge](Images/account-details-charge.png)

Total and average charges for retained vs. churned customers, plus monthly charge and admin-ticket revenue split by citizenship segment.

---

## 💳 Account Details — Payment

![Account Details Payment](Images/account-details-payment.png)

Customer count, churn rate, and average charges broken down by payment method.

---

# 📌 Key KPIs

| KPI                     |        Value |
| ------------------------ | -----------: |
| Total Customers          |         7,043 |
| Churned Customers        |         1,869 |
| Retained Customers       | 5,174 (73.46%) |
| Churn Rate               |           27% |
| Total Monthly Charge     |        $456.12K |
| Monthly Revenue Loss     |        $139.13K |
| Revenue Lost             |           31% |
| Avg. Tenure – Retained   | 37.57 months |
| Avg. Tenure – Churned    | 17.98 months |

---

# 💡 Key Insights

### 1. Payment Method

Customers paying by **Electronic check** churn at **45.29%** — roughly 2.4–3x the rate of mailed check (19.11%), bank transfer (16.71%), or credit card (15.24%) — despite also being the largest payment segment (2,365 customers).

### 2. Contract Type

Month-to-month customers churn at **42.71%**, compared with **11.27%** for one-year contracts and just **2.83%** for two-year contracts.

### 3. Customer Tenure

Retained customers average **37.6 months** of tenure vs. **18 months** for churned customers — churn is heavily concentrated in the early customer lifecycle.

### 4. Customer Age Group

Senior citizens churn at **41.68%**, nearly double the **23.61%** churn rate among younger customers, despite being a much smaller segment (1,142 vs. 5,901 customers).

### 5. Customer Support

Churned customers raised proportionally more technical tickets (2,173 among churned vs. 782 among retained), suggesting unresolved support issues are a churn driver.

---

# 📈 Business Recommendations

### 01 | Payment Experience

**Electronic check users churn at 45.29% — by far the highest of any payment method.**

Investigate friction in the electronic check payment flow and encourage migration to auto-pay methods (bank transfer / credit card) which show the lowest churn.

**Expected Impact:** Reduce churn in the largest, highest-risk payment segment.

### 02 | Contract Strategy

**42.71% churn among month-to-month customers.**

Encourage customers to move to longer-term contracts through targeted upgrade offers and loyalty incentives.

**Expected Impact:** Reduce churn and improve customer retention.

### 03 | Early-Tenure Retention

**Churned customers average 17.98 months of tenure vs. 37.57 months for retained customers.**

Strengthen onboarding and introduce proactive retention programs during the first 18 months of the customer relationship.

**Expected Impact:** Increase early-stage retention and reduce avoidable churn.

### 04 | Revenue Protection

**$139.13K monthly revenue loss, representing 31% of monthly revenue.**

Prioritize high-value customers for targeted retention campaigns based on revenue contribution and churn risk.

**Expected Impact:** Protect recurring revenue and minimize revenue loss.

### 05 | Service Experience

**Churned customers raise more technical tickets than retained customers.**

Prioritize faster resolution for technical support tickets and monitor customers with repeated tickets before they escalate.

**Expected Impact:** Improve customer satisfaction and reduce potential churn risk.

### 06 | Senior Citizen Segment

**Senior citizens churn at nearly double the rate of younger customers (41.68% vs. 23.61%).**

Review the senior citizen experience specifically — contract terms, payment options, and support responsiveness.

**Expected Impact:** Reduce churn in a high-risk demographic segment.

---

# 🧠 Analytical Approach

The project follows a business-focused analytical workflow:

**Business Problem**
↓
**Data Preparation**
↓
**Data Modeling**
↓
**KPI Development**
↓
**Exploratory Analysis**
↓
**Dashboard Storytelling**
↓
**Key Insights**
↓
**Business Recommendations**

The dashboard was designed to answer:

> **What is happening? → Who is affected? → Where is churn concentrated? → What is the business impact? → What should we do next?**

---

# 📚 Skills Demonstrated

- Data Modeling and Relationships in Power BI
- DAX Measures for KPI Calculation
- Power Query for Data Shaping
- Dashboard/Report Design for Business Stakeholders
- Customer Segmentation
- Churn Analysis Methodology
- Business Recommendation Development

---

# 📁 Repository Structure

```text
Telco-Customer-Churn-Dashboard/
│
├── Power BI Report/
│   └── Telco_Customer_Churn.pbix
│
├── Images/
│   ├── demographic-analysis.png
│   ├── account-details-tenure.png
│   ├── account-details-tickets.png
│   ├── account-details-charge.png
│   └── account-details-payment.png
│
└── README.md
```

---

# 🚀 Future Improvements

- Churn Prediction using Machine Learning
- Customer Lifetime Value (CLV) Modeling
- Automated Churn Alerts
- What-if Analysis
- Churn Risk Scoring
- Predictive Retention Modeling

---

# 👨‍💻 About Me

Hi! I'm **Mohamed Farag Saied** — an **ERP Systems & Data Analytics Specialist** working across **Data Engineering, Odoo, SAP, and PowerBuilder development**.

My toolkit includes:

**Power BI | Odoo | SAP | PowerBuilder | Python | SQL | Flutter**

I'm passionate about turning data into actionable insights and building systems that support better business decisions.

---

## ⭐ Project

If you found this project useful or interesting, feel free to ⭐ the repository.
