# 🏦 Banking Credit Risk & Portfolio Intelligence Dashboard

## 📊 Project Overview

This project is an end-to-end Business Intelligence case study developed in Power BI for a retail and SME banking environment.

The objective was to transform monthly loan portfolio data into an interactive management dashboard that provides visibility into portfolio size, credit quality, risk exposure and potential financial losses.

The dashboard enables decision-makers to analyse key areas such as portfolio evolution, default rates, non-performing exposure, expected loss, customer risk profiles and loan prioritisation for collections.

The final solution was structured across five analytical pages:

1. Executive Overview
2. Portfolio Composition & Exposure
3. Credit Risk & Delinquency Monitor
4. Customer Profile & Lending Performance
5. Risk Prioritisation & Collections

More than simply presenting KPIs, the project focuses on turning lending data into actionable insights that support portfolio management, risk monitoring and collections prioritisation.

---

## 🎯 Business Problem

The bank has a growing multi-product loan portfolio, but its monthly management review is fragmented across different data sources and metrics.

Portfolio and risk leaders need to quickly understand where lending exposure is concentrated, whether credit quality is deteriorating and which segments require closer attention.

The key challenge was to transform monthly loan account snapshots into a consistent Business Intelligence solution that provides visibility into:

- Portfolio size and evolution over time
- Credit quality and default performance
- Non-performing exposure and risk concentration
- Expected financial losses
- Customer risk profiles
- High-priority loans for collections

The objective was to support faster and more informed decisions across portfolio management, credit risk and collections.

---

## ❓ Business Questions

The dashboard was designed to answer the following business questions:

1. How large is the outstanding portfolio, and how has it changed month by month?
2. What percentage of the portfolio is defaulted or non-performing?
3. Which loan types combine high outstanding exposure with high default rates or expected losses?
4. Where is non-performing exposure geographically concentrated?
5. Which customer segments demonstrate higher credit risk?
6. Which loans should be prioritised by collections teams?
7. What share of the portfolio is classified as Low, Medium, High or Critical Risk?
8. Which portfolio areas represent the greatest potential financial loss?

---

## 🗂️ Dataset

The project uses a synthetic banking dataset representing a retail and SME loan portfolio.

The data was structured around monthly loan account snapshots, enabling the analysis of portfolio performance over time.

Key information includes:

- Loan ID and Loan Type
- Outstanding Balance
- Snapshot Date
- Days Past Due
- Default and Non-Performing Flags
- Expected Loss
- Credit Score
- Customer Segment
- Geographic Information
- Customer Profile Data

The use of monthly snapshots allows the same loan to be analysed across different reporting periods, making it possible to monitor changes in portfolio size, credit quality and risk exposure over time.

---

## 🛠️ Tools & Technologies

- **Power BI** — Dashboard development and interactive reporting
- **Power Query** — Data cleaning and transformation
- **DAX** — Measures, KPIs and risk calculations
- **Data Modeling** — Star schema and relationship management
- **GitHub** — Project documentation and portfolio publishing

---

## 🧩 Data Model

The project was built using a dimensional data model.

The central fact table contains monthly loan account snapshots, including financial exposure and credit risk metrics.

Supporting dimension tables provide descriptive attributes for customers, loans and reporting dates.

This structure supports efficient aggregation, filtering and time-based analysis across the dashboard.

### Main Model Components

**Fact Loans**

Contains:

- Loan-level monthly snapshots
- Outstanding balances
- Days past due
- Default indicators
- Non-performing indicators
- Expected loss
- Credit score information

**Dimension Tables**

Supporting dimensions were used to analyse the portfolio across:

- Dates
- Customers
- Loan Types
- Customer Segments
- Geographic Attributes

---

## 📐 Key DAX Measures

Several DAX measures were developed to calculate portfolio KPIs and support interactive analysis.

### Total Outstanding

Calculates the outstanding balance for the latest available portfolio snapshot.

### Default Rate

Calculates the percentage of the portfolio classified as defaulted.

### Non-Performing Exposure

Measures the outstanding balance associated with non-performing loans.

### Risk Exposure %

Calculates the percentage of total outstanding exposure classified as non-performing.

### Expected Loss

Measures the potential financial loss associated with the lending portfolio.

### Critical Exposure

Calculates the outstanding balance classified as Critical Risk.

### Critical Exposure %

Measures the percentage of the current portfolio classified as Critical Risk.

---

## ⚠️ Risk Classification

A transparent DAX-based risk score was created to classify loans into four risk categories:

- 🟢 **Low Risk**
- 🟡 **Medium Risk**
- 🟠 **High Risk**
- 🔴 **Critical Risk**

The classification considers indicators such as:

- Days Past Due
- Default Status
- Non-Performing Status

The risk score was then converted into a business-friendly risk classification, enabling portfolio exposure to be analysed by risk level.

---

# 📊 Dashboard Structure

## 1️⃣ Executive Overview

Provides a high-level view of the lending portfolio and overall credit risk.

Key metrics include:

- Total Portfolio
- Total Outstanding
- Default Rate
- Non-Performing Exposure
- Risk Exposure %
- Average Credit Score

Key visualisations include:

- Portfolio Evolution
- Outstanding Balance by Loan Type
- Default Rate by Loan Type

---

## 2️⃣ Portfolio Composition & Exposure

Focuses on understanding how the lending portfolio is structured and where exposure is concentrated.

Key areas include:

- Portfolio Composition
- Outstanding Balance Evolution
- Exposure by Loan Type
- Exposure by Region
- Active Loans
- Average Credit Score

---

## 3️⃣ Credit Risk & Delinquency Monitor

Monitors portfolio credit quality and delinquency performance.

Key metrics include:

- Default Rate
- Non-Performing Exposure
- Risk Exposure %
- Total Outstanding

Key visualisations analyse:

- Non-Performing Exposure over time
- Default Rate by Loan Type
- Default Rate by Region

This page helps identify areas where credit quality may be deteriorating.

---

## 4️⃣ Customer Profile & Lending Performance

Analyses customer segments to identify differences in credit quality and lending performance.

Key visualisations include:

- Average Credit Score by Customer Segment
- Default Rate by Customer Segment
- Expected Loss by Customer Segment
- Average Days Past Due by Customer Segment

This analysis helps identify customer profiles associated with higher risk and potential financial impact.

---

## 5️⃣ Risk Prioritisation & Collections

Focuses on the most actionable areas of portfolio risk.

Key KPIs include:

- Total Outstanding
- Expected Loss
- Critical Exposure
- Critical Exposure %

Key visualisations include:

- Expected Loss by Loan Type
- Portfolio Risk Distribution
- Top 10 Collection Priorities

The collection priorities table identifies individual loans requiring attention based on:

- Risk Level
- Outstanding Balance
- Expected Loss
- Days Past Due
- Loan Type

---

## 💡 Key Insights

The dashboard highlights several important business insights:

### Mortgage exposure represents a major concentration of potential financial loss

Mortgage products show significant outstanding exposure and expected loss, making them a key area for risk monitoring.

### Most portfolio exposure is classified as Low Risk

The majority of the portfolio is classified as Low Risk, indicating a relatively healthy overall portfolio.

### Critical exposure represents a smaller but financially important portion of the portfolio

A smaller share of the portfolio is classified as Critical Risk, but these loans require immediate attention due to their potential financial impact.

### Customer segments show different credit quality profiles

The analysis highlights differences in credit scores, default rates, expected loss and delinquency across customer segments.

### Collections prioritisation can focus resources on high-impact cases

By combining Expected Loss, Outstanding Balance, Days Past Due and Risk Level, the dashboard helps identify the loans that should be prioritised for collection actions.

---

## 🎯 Business Value

The final dashboard provides decision-makers with a centralised view of the lending portfolio.

It supports:

- Portfolio monitoring
- Credit risk assessment
- Risk concentration analysis
- Identification of deteriorating credit quality
- Expected loss monitoring
- Customer risk analysis
- Collections prioritisation

The project demonstrates how Business Intelligence tools can transform fragmented monthly loan data into actionable insights for portfolio and risk management.

---

## 📈 Skills Demonstrated

This project demonstrates practical experience with:

- Power BI
- DAX
- Power Query
- Data Cleaning & Transformation
- Data Modeling
- Star Schema
- KPI Development
- Risk Analysis
- Financial & Portfolio Analytics
- Credit Risk Monitoring
- Data Visualization
- Business Intelligence
- Business Analysis
- Dashboard Design
- Data Storytelling

---

## 🖥️ Dashboard Preview

### Executive Overview

![Executive Overview](images/executive-overview.png)

### Portfolio Composition & Exposure

![Portfolio Composition](images/portfolio-composition.png)

### Credit Risk & Delinquency Monitor

![Credit Risk](images/credit-risk.png)

### Customer Profile & Lending Performance

![Customer Profile](images/customer-profile.png)

### Risk Prioritisation & Collections

![Risk Prioritisation](images/risk-prioritisation.png)

---

## 📁 Project Structure

```text
Banking-Credit-Risk-Portfolio-Intelligence/
│
├── README.md
│
├── PowerBI/
│   └── Banking_Credit_Risk_Dashboard.pbix
│
├── Dataset/
│   └── [Source data files]
│
└── images/
    ├── executive-overview.png
    ├── portfolio-composition.png
    ├── credit-risk.png
    ├── customer-profile.png
    └── risk-prioritisation.png
