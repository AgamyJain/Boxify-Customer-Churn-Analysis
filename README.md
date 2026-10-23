# Boxify E-commerce Customer Churn Analysis

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/Analytics-Customer%20Retention-4472C4" alt="Customer Retention">
  <img src="https://img.shields.io/badge/Status-Completed-green" alt="Completed">
</p>

<p align="center">
  <strong>A Power BI analytics project investigating customer churn, engagement, subscription behavior, and opportunities to improve customer retention.</strong>
</p>

---

## Table of Contents

- [Project Abstract](#project-abstract)
- [Business Scenario](#business-scenario)
- [Business Objectives](#business-objectives)
- [Business Questions](#business-questions)
- [Dataset Overview](#dataset-overview)
- [Tools and Techniques](#tools-and-techniques)
- [Methodology](#methodology)
- [Dashboard Preview](#dashboard-preview)
- [Key Findings](#key-findings)
- [Business Recommendations](#business-recommendations)
- [Project Structure](#project-structure)
- [How to Review the Project](#how-to-review-the-project)
- [Limitations](#limitations)
- [Author](#author)

---

## Project Abstract

Boxify is an e-commerce subscription business case study focused on understanding customer churn and identifying opportunities to improve retention. The project uses customer-level data and Power BI to explore churn patterns, subscription behavior, customer engagement, and differences between customer segments.

The analysis is designed to help identify groups that may require closer retention monitoring and to support practical recommendations for improving customer engagement. The dashboard presents key metrics and comparisons to make customer behavior easier to evaluate.

The project emphasizes descriptive analysis and business interpretation. Any relationship between engagement and churn should be interpreted as an observed association unless a suitable predictive or causal analysis has been performed.

## Business Scenario

Boxify is presented as an online subscription box service delivering lifestyle products monthly. Management has observed customers cancelling their subscriptions before completing six months and wants to understand the patterns associated with churn.

## Business Objectives

- Examine customer churn and subscription behavior.
- Identify customer segments with comparatively high churn.
- Investigate engagement patterns in relation to churn.
- Compare available customer and subscription measures.
- Recommend retention strategies for further testing.

## Business Questions

1. Which customer segments show higher churn?
2. How does engagement relate to churn?
3. How do churned and active customers differ across available measures?
4. Which groups may benefit from targeted retention efforts?
5. What actions could improve subscription retention?

## Dataset Overview

| Attribute | Description |
|---|---|
| Dataset | `boxify_customers.csv` |
| Format | CSV |
| Analysis tool | Microsoft Power BI |
| Business domain | Subscription analytics and customer retention |

The CSV contains the customer-level data used by the analysis. Refer to the dataset and report for the actual fields, definitions, and scope.

## Tools and Techniques

- Microsoft Power BI
- Data inspection and preparation
- KPI cards and summary measures
- Customer segmentation
- Churn comparisons
- Engagement analysis
- Dashboard visualization
- Business recommendations

## Methodology

### 1. Data Preparation

Inspect the customer dataset and prepare the fields required for analysis.

### 2. KPI Analysis

Evaluate the churn and customer measures available in the dataset.

### 3. Segment Comparison

Compare churn across the available customer characteristics and subscription groups.

### 4. Engagement Analysis

Explore engagement measures alongside churn status to identify potential patterns.

### 5. Dashboard and Recommendations

Present the analysis in Power BI and translate the observed patterns into retention recommendations.

## Dashboard Preview

![Boxify Customer Churn Dashboard](images/Boxify_Customer_Churn_Dashboard.png)

[Open the dashboard PDF](dashboard/Boxify_Customer_Churn_Dashboard.pdf)

## Key Findings

The project examines churn patterns, engagement levels, and differences across customer segments.

Refer to the final dashboard and report for the calculated results. Avoid interpreting an engagement threshold or customer characteristic as a proven cause of churn unless the analysis establishes that relationship.

## Business Recommendations

- Monitor customer segments with relatively high churn.
- Review engagement patterns to identify customers who may need additional support.
- Test targeted retention communications and offers.
- Compare retention results before and after interventions.
- Track churn consistently using a clearly defined customer population and reporting period.

## Project Structure

```text
Boxify-Customer-Churn-Analysis/
├── README.md
├── data/
│   └── boxify_customers.csv
├── dashboard/
│   ├── Boxify_Customer_Churn_Dashboard.pbix
│   └── Boxify_Customer_Churn_Dashboard.pdf
├── report/
│   ├── Boxify_Customer_Churn_Report.docx
│   └── Boxify_Customer_Churn_Report.pdf
└── presentation/
    ├── Boxify_Executive_Presentation.pptx
    └── Boxify_Executive_Presentation.pdf
