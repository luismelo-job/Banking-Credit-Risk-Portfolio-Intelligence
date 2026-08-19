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

1. How large is the outstanding portfolio, and how has it changed over time?
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

The data was structured around monthly loan account snapshots, enabling the analysis of portfolio performance and credit risk over time.

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

The project was built using a dimensional data model based on a Star Schema approach.

The central fact table contains monthly loan account snapshots, including financial exposure and credit risk metrics.

Supporting dimension tables provide descriptive attributes for customers, loans and reporting dates.

This structure supports efficient aggregation, filtering and time-based analysis across the dashboard.

### Main Model Components

#### Fact Loans

Contains:

- Loan-level monthly snapshots
- Outstanding balances
- Days Past Due
- Default indicators
- Non-performing indicators
- Expected Loss
- Credit Score information

#### Dimension Tables

Supporting dimensions were used to analyse the portfolio across:

- Dates
- Customers
- Loan Types
- Customer Segments
- Geographic Attributes

---

## 📐 Key DAX Measures & Calculations

Several DAX measures and calculated columns were developed to calculate portfolio KPIs and support interactive analysis.

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

A transparent DAX-based risk scoring framework was created to classify individual loans into four risk categories:

- 🟢 **Low Risk**
- 🟡 **Medium Risk**
- 🟠 **High Risk**
- 🔴 **Critical Risk**

The classification considers indicators such as:

- Days Past Due
- Default Status
- Non-Performing Status

The risk score was then converted into a business-friendly risk classification, allowing portfolio exposure to be analysed by risk level.

This approach was designed to keep the risk methodology transparent and understandable for business stakeholders.

---

# 📊 Dashboard Structure

## 1️⃣ Executive Overview

Provides a high-level view of the lending portfolio and overall credit risk.

### Key KPIs

- Total Portfolio
- Total Outstanding
- Default Rate
- Non-Performing Exposure
- Risk Exposure %
- Average Credit Score

### Key Visualisations

- Portfolio Evolution
- Outstanding Balance by Loan Type
- Default Rate by Loan Type

### Business Insight

Provides an executive-level snapshot of portfolio size, credit quality and risk exposure, helping management quickly identify key trends and areas requiring attention.

---

## 2️⃣ Portfolio Composition & Exposure

Focuses on understanding how the lending portfolio is structured and where exposure is concentrated.

### Key KPIs

- Total Portfolio
- Total Outstanding
- Active Loans
- Average Credit Score

### Key Visualisations

- Outstanding Balance Evolution
- Outstanding Balance by Loan Type
- Outstanding Balance by Region

### Business Insight

Analyses portfolio composition and concentration across products and regions while tracking how outstanding exposure evolves over time.

---

## 3️⃣ Credit Risk & Delinquency Monitor

Monitors portfolio credit quality and delinquency performance.

### Key KPIs

- Default Rate
- Non-Performing Exposure
- Risk Exposure %
- Total Outstanding

### Key Visualisations

- Non-Performing Exposure Evolution
- Default Rate by Loan Type
- Default Rate by Region

### Business Insight

Monitors default and non-performing exposure across loan types and regions, helping identify areas where credit quality requires closer attention.

---

## 4️⃣ Customer Profile & Lending Performance

Analyses customer segments to identify differences in credit quality and lending performance.

### Key Visualisations

- Average Credit Score by Customer Segment
- Default Rate by Customer Segment
- Expected Loss by Customer Segment
- Average Days Past Due by Customer Segment

### Business Insight

Explores credit quality, default rates, expected loss and payment delinquency across customer segments, highlighting profiles with higher risk and potential financial impact.

---

## 5️⃣ Risk Prioritisation & Collections

Focuses on the most actionable areas of portfolio risk.

### Key KPIs

- Total Outstanding
- Expected Loss
- Critical Exposure
- Critical Exposure %

### Key Visualisations

- Expected Loss by Loan Type
- Portfolio Risk Distribution
- Top 10 Collection Priorities

The collection priorities table identifies individual loans requiring attention based on:

- Risk Level
- Outstanding Balance
- Expected Loss
- Days Past Due
- Loan Type

### Business Insight

Identifies the most critical areas of portfolio exposure and prioritises individual loans for collections based on risk level, outstanding balance, expected loss and days past due.

---

# 💡 Key Insights

The dashboard highlights several important business insights.

### Mortgage exposure represents a major concentration of potential financial loss

Mortgage products represent a significant portion of outstanding exposure and expected loss, making them an important area for continued risk monitoring.

### Most portfolio exposure is classified as Low Risk

The majority of the current portfolio is classified as Low Risk, indicating that most outstanding exposure does not fall into the highest risk categories.

### Critical exposure represents a smaller but financially important portion of the portfolio

Critical Risk represents a smaller share of the overall portfolio, but these loans require closer attention because of their higher potential financial impact.

### Customer segments show different credit quality profiles

Differences in credit score, default rate, expected loss and delinquency across customer segments provide additional insight into customer-level risk patterns.

### Collections prioritisation can focus resources on high-impact cases

Combining Expected Loss, Outstanding Balance, Days Past Due and Risk Level allows collections teams to focus their efforts on loans with the greatest potential financial impact.

---

# 🎯 Business Value

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

# 📈 Skills Demonstrated

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
Conclusion 

This project was developed as an end-to-end Business Intelligence case study combining financial domain knowledge, data modelling, DAX calculations and interactive dashboard design.
The final solution provides a structured view of portfolio performance, credit quality, risk exposure and collections priorities.
Beyond technical dashboard development, the main objective was to demonstrate the ability to translate business questions into data-driven analysis and actionable insights.
The project reflects a Business Intelligence approach focused on one central question:
How can data be transformed into meaningful insights that support better business decisions?
