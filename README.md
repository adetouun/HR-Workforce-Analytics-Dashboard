# 📊 HR Workforce Analytics Dashboard

This project demonstrates an end-to-end data analysis workflow, using Microsoft Excel as the exclusive tool for cleaning, feature engineering, and visualization.
The core objective was to transform a raw, messy HR dataset (1,020 records) into a strategic, actionable dashboard that addresses critical business questions regarding workforce health and performance.

## 🚀 Deliverable

HR Strategy Dashboard divided into three sections:

- **Status Check** – Monitors employee statuses

- **Distribution** – Shows workforce and salary spread across departments  

- **Performance** – Evaluates employee performance and compensation equity

## 🧽 Data Cleaning & Transformation

**Challenges**:

- Merged columns (e.g., DevOps-California)

- Missing salary values

- Inconsistent numeric and string formats

**Excel Solutions**:

- Text-to-Columns / Formulas: Split Department_Region

- Data Cleaning: Cleaned phone numbers and salaries using SUBSTITUTE and VALUE

- Feature Engineering:

  -  Performance Grade (1–4)

  -  Years Spent (tenure)

  -  Salary Band (Low / Medium / High)

## 📈 Key Insights

**1. ⚠️ Operational Status Alert**

- **CRITICAL DATA QUALITY ISSUE**: 34.9% (356 employees) are marked with a Pending status. This compromises all calculations for Active Headcount and Attrition.

- *Dashboard Visual*: Prominent Red Highlighted KPI Card ensures this data governance issue receives immediate attention.

**2. 🌍 Distribution & Investment**

- **Departmental Balance**: The distribution across departments is relatively even, with two specific outliers:

- **Investment Focus**: Cloud Tech has the lowest headcount (146 employees).

- **Largest Department**: Devops has the highest headcount (189 employees).

- *Dashboard Visual*: The Horizontal Bar Chart makes the low headcount of Cloud Tech immediately visible for strategic discussion.

**3. ⚖️ Performance & Compensation Equity**

- **Talent Uplift Opportunity**: 216 employees are rated Poor. Focusing development efforts here is key to boosting overall capability (Poor is the largest single group of performers).

- *Dashboard Visual*: The Column Chart shows that 'Poor' is the largest single segment of performers

## 🎯 Strategic Recommendations

Based on these validated insights, the following actions are recommended for HR Leadership:

1. Data Governance Priority: Initiate an immediate audit to resolve the 356 Pending records, restoring integrity to all key workforce metrics.

2. Strategic Staffing Review: Launch a targeted recruitment drive for the Cloud Tech department to address low staffing, mitigating future technological risk.

3. Targeted Training: Implement performance coaching and specialized training for the 216 employees currently categorized as 'Poor' to boost overall organizational capability.

## 🛠 Tools & Technologies

- Data Preparation & Analysis: Microsoft Excel (Formulas, Functions, Pivot Tables, Pivot Charts)

- Visualization: Excel dashboards 

- Documentation: Markdown
