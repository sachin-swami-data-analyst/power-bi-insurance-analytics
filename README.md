# Insurance Analytics Dashboard | Power BI

## 📊 Project Overview

This project is an end-to-end Insurance Analytics Dashboard developed using Microsoft Power BI.

The dashboard analyzes insurance business performance across Claims, Policies, Customers, and Agents. It provides interactive KPIs, trends, comparisons, and business insights to support data-driven decision-making.

---

## 🎯 Business Objective

The main objective of this project is to analyze insurance operations and identify trends in:

* Claim amounts and claim trends
* Claim settlement and rejection performance
* Policy and premium performance
* Agent productivity and target achievement
* Customer segmentation and claim behavior

---

## 🛠️ Tools & Technologies

* Power BI
* Power Query
* DAX
* Microsoft Excel
* Data Modeling

---

## 🗂️ Data Model

The project uses a dimensional data model consisting of:

### Dimension Tables

* DIM_Customer
* DIM_Policy
* DIM_Agent

### Fact Table

* FACT_Claims

The data model is designed to support analysis across customers, policies, claims, and agents.

---

# 📈 Dashboard Pages

## 1. Executive_Overview

The Claims Overview dashboard provides a high-level view of insurance claim performance.

### Key Metrics

* Total Claims Amount
* Total Claims Filed
* Claim Settlement Ratio
* Loss Ratio
* Previous Year Claims
* YoY Growth %

### Analysis

* Total Claim Amount by Year
* Total Active Policies by Policy Type
* Total Claim Amount by State
* Year and Policy Type filtering

The dashboard contains claim trends from 2019 to 2024.

---

## 2. Claims_Analysis

This page provides detailed analysis of claim processing and claim status.

### Key Metrics

* Total Claims Amount
* Total Approved Amount
* Claim Rejection Rate
* Average Processing Days
* Fraud Claims Amount

### Analysis

* Claims by Policy Type
* Claims by Claim Status
* Claim Amount vs Processing Days
* Claim Category Analysis
* Rolling 3-Month Claims
* Year-wise Claim Trends

The dashboard includes Approved, Partially Approved, Pending, Rejected, and Under Review claim statuses.

---

## 3. Policy_Performance

This dashboard analyzes policy portfolio and premium performance.

### Key Metrics

* Total Active Policies
* Active Policy Premium
* Lapsed Policies
* Weighted Average Premium

### Analysis

* Annual Premium by Policy Type
* Premium by Payment Frequency
* Policy Count by Year
* Premium and Active Policies by Channel
* Policy Status Analysis

The report analyzes channels including Agent, Bank, Broker, Direct, and Online.

---

## 4. Agent_Performance

This dashboard evaluates agent productivity and target performance.

### Key Metrics

* Total Agents
* Total Annual Premium
* Agents Hit Target
* Active Agents

### Analysis

* Agent-wise Premium
* Target vs Actual Premium
* Agent Target Status
* Agent Ranking
* Regional Performance
* Agent Type Analysis
* Experience vs Premium

The dashboard includes agent target achievement and regional performance analysis.

---

## 5. Customer_Insights

This dashboard provides customer-level analysis.

### Key Metrics

* Total Customers
* Premium Segment %
* Average Annual Income
* Average Age
* Distinct Claimants

### Analysis

* Customers by Customer Segment
* Claims by Gender
* Claims by Policy Type
* Total Claims Amount
* Approved Claims Amount
* Customer-level Claim Analysis
* State and Customer Segment filtering

The report includes Basic, Standard, and Premium customer segments.

---

# 📌 Key DAX Measures

The project uses DAX measures for business KPIs and analytical calculations, including:

* Total Claims Amount
* Total Approved Amount
* Claim Settlement Ratio
* Loss Ratio
* Claim Rejection Rate
* Average Processing Days
* Fraud Claims Amount
* YoY Growth %
* Rolling 3-Month Claims
* Total Active Policies
* Weighted Average Premium
* Agent Target Status

---

# 💡 Business Insights

The dashboard enables analysis of:

* Year-wise claim trends
* State-wise claim contribution
* Policy-type performance
* Claim approval and rejection patterns
* Claim processing efficiency
* Fraud-related claim amounts
* Premium performance across channels
* Agent target achievement
* Regional agent performance
* Customer segment and claim behavior

---

# 📁 Repository Structure

```text
Insurance-PowerBI-Analytics/
│
├── README.md
├── Insurance_Analytics.pbix
│
├── DAX/
│   └── DAX_Measures.md
│
└── Screenshots/
    ├── 01_Claims_Overview.png
    ├── 02_Claims_Analysis.png
    ├── 03_Policy_Analysis.png
    ├── 04_Agent_Analysis.png
    └── 05_Customer_Analysis.png
```

---

# 🚀 Skills Demonstrated

* Data Cleaning
* Data Transformation
* Data Modeling
* Power Query
* DAX
* KPI Development
* Interactive Dashboard Development
* Business Analysis
* Data Visualization
* Insurance Domain Analytics

---

## 👨‍💻 Project Type

**Power BI | Insurance Analytics | Business Intelligence | Data Analytics**

---

## 📷 Dashboard Preview

Dashboard screenshots are available in the `Screenshots` folder.
