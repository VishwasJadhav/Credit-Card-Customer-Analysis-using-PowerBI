# Credit Card Customer & Transaction Analytics Dashboard

## Project Overview

This project analyzes **credit card customer behavior, transaction patterns, and revenue generation** using Power BI. The objective is to transform raw banking data into actionable insights that help understand **customer segments, spending behavior, and financial performance**.

The dashboards provide a comprehensive analytical view of credit card usage by combining **customer demographic data with transaction-level metrics**. The analysis highlights key factors influencing revenue, customer engagement, and credit utilization.

---

## Business Problem

Financial institutions need to monitor customer spending behavior and identify high-value segments while also assessing potential credit risk. Key questions addressed in this analysis include:

* Which customer segments generate the highest revenue?
* How does spending vary across income groups, age groups, and professions?
* Which card categories contribute the most to overall transactions?
* What demographic factors influence credit card usage?
* How do transaction patterns evolve over time?

The Power BI dashboards provide an **interactive environment** for exploring these insights.

---

## Dataset Description

The project uses four datasets representing customer information and credit card transactions.

| Dataset         | Description                                   |
| --------------- | --------------------------------------------- |
| customer.csv    | Customer demographic information              |
| credit_card.csv | Credit card transaction and financial metrics |
| cust_add.csv    | Additional customer records                   |
| cc_add.csv      | Additional credit card records                |

### Key Attributes

Important variables included in the datasets:

* Client_Num – Unique customer identifier
* Customer_Age – Age of customer
* Gender – Customer gender
* Income – Annual income
* Education_Level – Education qualification
* Customer_Job – Occupation category
* Card_Category – Credit card type
* Credit_Limit – Maximum credit allowed
* Total_Trans_Amt – Total transaction amount
* Total_Trans_Vol – Total number of transactions
* Avg_Utilization_Ratio – Credit utilization ratio
* Interest_Earned – Interest generated from customers
* Delinquent_Acc – Indicator for delinquent accounts

---

## Data Model

The analysis uses a **relational data model** to combine customer demographics with transaction activity.

Relationship:

customer table
→ linked via **Client_Num**
→ credit_card table

Relationship Type: **One-to-Many**

This structure enables combining **customer attributes with transaction metrics** to perform detailed segmentation and analysis.

---

## Key Performance Indicators (KPIs)

The dashboards track the following key financial and customer metrics:

* Total Customers
* Total Revenue
* Interest Earned
* Total Transaction Amount
* Total Transaction Volume
* Average Credit Utilization Ratio
* Delinquency Indicator

These KPIs provide a quick overview of **portfolio performance and customer activity**.

---

## Dashboard Features

### 1. Customer Dashboard

The customer dashboard analyzes **demographic and geographic customer patterns**.

Key insights include:

* Revenue contribution by age group
* Revenue by income category
* Geographic revenue distribution by state
* Revenue segmentation by marital status and dependents
* Customer profile insights by job and education

[Customer Dashboard](images/customer_dashboard.png)

---

### 2. Transaction Dashboard

The transaction dashboard focuses on **credit card usage and revenue generation**.

Key insights include:

* Revenue and transaction trends over time
* Distribution of revenue across card categories
* Spending patterns by customer job roles
* Revenue contribution across education levels and family dependents
* Transaction behavior by chip usage type

[Transaction Dashboard](images/transaction_dashboard.png)

---

## Key Insights

Some of the insights identified through the dashboards include:

* **Week-over-Week Revenue Growth:**
Revenue increased by **28.8% week-over-week**, accompanied by a significant rise in both **total transaction amount and transaction volume**, indicating growing credit card activity during the period.

* **Year-to-Date Financial Performance:**
Total credit card revenue reached approximately **$57M**, generated from **$46M in transaction amounts**, highlighting strong overall portfolio performance.

* **Customer Spending by Gender:**
Male customers contributed around **$31M in revenue**, while female customers contributed **$26M**, showing slightly higher spending activity among male customers.

* **Card Category Contribution:**
**Blue and Silver credit cards accounted for nearly 93% of total transactions**, indicating that the majority of customer activity is concentrated in the basic and mid-tier card segments.

---

## Tools & Technologies Used

* Power BI
* Data Modeling
* DAX (Data Analysis Expressions)
* Data Visualization
* Business Intelligence Techniques

---

## Analytical Techniques Applied

This project incorporates several analytical methods including:

* Customer segmentation analysis
* Revenue distribution analysis
* Demographic analysis
* Time series transaction analysis
* Behavioral analysis of credit card usage

These techniques help uncover patterns in **customer spending behavior and financial engagement**.

---

## Future Improvements

Potential enhancements for further analysis:

* Customer Lifetime Value (CLV) estimation
* Credit risk prediction modeling
* Customer churn analysis
* Advanced behavioral segmentation
* Integration with additional financial datasets

---

## Conclusion

This project demonstrates how **business intelligence tools like Power BI can transform raw financial data into meaningful insights**. By combining demographic and transactional data, the dashboards provide valuable information about **customer behavior, revenue drivers, and financial engagement patterns**.

These insights can support better decision-making for **customer strategy, marketing campaigns, and financial risk monitoring**.

---
