# ChurnQuest: Telecom Customer Churn Analysis

**Customer Churn Analysis | Excel | Power Query | PivotTables | Data Visualization | Business Analytics**

## Overview

ChurnQuest is an end-to-end customer churn analysis project focused on identifying customer behaviors and service characteristics associated with customer attrition in the telecommunications industry.

Using a dataset of **4,250 customers**, the project explores churn patterns across customer tenure, service subscriptions, calling behavior, customer support interactions, and geographic locations.

The analysis was conducted using **Microsoft Excel**, with Power Query for data preparation, PivotTables for exploratory analysis, and a dashboard for communicating key findings.

The project translates customer-level data into actionable insights to support customer retention strategies.

## Business Problem

Customer churn directly affects recurring revenue, customer lifetime value, and business growth.

Understanding which customer segments exhibit higher churn rates enables telecommunications companies to identify potential retention opportunities and make more informed business decisions.

This project addresses four primary questions:

- What is the overall customer churn rate?
- Which customer characteristics are associated with higher churn?
- How do service usage and customer support interactions relate to churn?
- Which customer segments should be prioritized for further investigation and retention initiatives?

## Dataset

The analysis uses a telecommunications customer churn dataset containing **4,250 records and 20 original features**.

The dataset includes:

| Category              | Features                                     |
| --------------------- | -------------------------------------------- |
| Customer Profile      | State, Account Length                        |
| Service Subscriptions | International Plan, Voicemail Plan           |
| Calling Behavior      | Day, Evening, Night, and International Usage |
| Billing Information   | Calling Charges                              |
| Customer Support      | Customer Service Calls                       |
| Target Variable       | Churn                                        |

## Tools & Technologies

| Tool            | Application                                |
| --------------- | ------------------------------------------ |
| Microsoft Excel | Data analysis and dashboard development    |
| Power Query     | Data import, cleaning, and transformation  |
| PivotTables     | Data aggregation and customer segmentation |
| Excel Charts    | KPI visualization and comparative analysis |

## Project Workflow

### 1. Data Preparation

Imported the raw CSV dataset into Power Query and performed data quality checks.

- Validated data types and column consistency.
- Checked for missing values and duplicate records.
- Created a binary `Churn_Flag` variable.
- Grouped customers by account tenure.
- Segmented customers based on customer service call frequency.

### 2. Exploratory Data Analysis

Conducted **12 business-focused analyses** covering:

- Overall customer churn and retention
- Customer tenure and churn patterns
- International and voicemail plan subscriptions
- Customer service interactions
- Calling usage and charges
- Geographic churn distribution
- Multi-variable customer segmentation
- Customer retention opportunities

### 3. Dashboard Development

Developed an Excel dashboard featuring four KPI cards and five visualizations.

**Key Performance Indicators**

| KPI                |  Value |
| ------------------ | -----: |
| Total Customers    |  4,250 |
| Retained Customers |  3,652 |
| Churned Customers  |    598 |
| Churn Rate         | 14.07% |

**Dashboard Visualizations**

1. Overall Customer Churn Distribution
2. Customer Tenure vs. Churn Rate
3. Churn Rate by Customer Service Calls
4. Churn Rate by International Plan
5. Churn Rate by High-Risk Customer Segments

## Key Findings

### 1. Customer Service Interactions Are Strongly Associated With Churn

Customers making **four or more service calls** recorded a churn rate of **50.75%**, compared with **10.93%** among customers making fewer calls.

Although these customers represent only **7.88%** of the dataset, they account for approximately **28.43%** of all churned customers.

**Business implication:** Frequent support interactions are an important indicator for prioritizing customer experience investigations.

### 2. International Plan Subscribers Exhibit Higher Churn

| International Plan | Churn Rate |
| ------------------ | ---------: |
| No                 |     11.18% |
| Yes                |     42.17% |

International plan subscribers recorded approximately **3.77 times the churn rate** of non-subscribers.

**Business implication:** International plan pricing, benefits, and customer expectations warrant further evaluation.

### 3. Voicemail Subscribers Show Lower Churn

Customers with voicemail subscriptions recorded a churn rate of **7.37%**, compared with **16.44%** among non-subscribers.

**Business implication:** Service adoption and customer engagement patterns may provide useful information for retention analysis.

### 4. Churned Customers Have Higher Daytime Usage

| Customer Status | Average Daytime Minutes |
| --------------- | ----------------------: |
| Retained        |                  175.56 |
| Churned         |                  208.99 |

Churned customers averaged **19.04% more daytime calling minutes** than retained customers.

**Business implication:** Calling-plan suitability and usage-related charges may be useful areas for further investigation.

### 5. Customer Segmentation Reveals High-Risk Groups

The highest observed churn rate, **79.17%**, occurred among customers with:

- Four or more customer service calls
- An international plan
- No voicemail subscription

This segment contained 24 customers, so its churn rate should be interpreted cautiously.

A larger segment of **225 customers**, characterized by four or more service calls, no international plan, and no voicemail plan, recorded a churn rate of **51.56%**, accounting for 116 churned customers.

**Business implication:** Retention priorities should consider both segment churn rates and the number of customers affected.

## Business Recommendations

Based on the analysis, the following initiatives are recommended for further evaluation:

| Priority    | Recommendation                  | Rationale                                                 |
| ----------- | ------------------------------- | --------------------------------------------------------- |
| High        | Proactive customer support      | Frequent service calls are associated with elevated churn |
| High        | International plan evaluation   | International plan subscribers exhibit higher churn       |
| Medium      | Usage-aligned calling plans     | Churned customers show higher daytime usage               |
| Medium      | Customer engagement initiatives | Voicemail subscription is associated with lower churn     |
| Investigate | Geographic churn assessment     | Churn rates vary across states                            |

These recommendations are based on descriptive analysis and should be validated through additional customer research and controlled testing before implementation.

## Project Deliverables

The repository contains the following project components:

- **Excel Analysis Workbook:** Cleaned data, PivotTables, customer segmentation, and churn dashboard.
- **Case Study:** Business context, problem statement, objectives, and analytical questions.
- **Solution Guide:** Detailed analysis, findings, interpretations, and recommendations.

## Limitations

- The analysis identifies associations rather than causal relationships.
- The dataset does not contain detailed customer feedback or complaint-resolution information.
- Some customer segments have small sample sizes.
- The analysis does not include a predictive machine learning model.
- The findings are limited to the available customer records.

## Future Enhancements

Potential extensions include:

- Predictive churn modeling using Python and machine learning.
- Customer lifetime value analysis.
- Advanced customer segmentation.
- Integration of customer satisfaction and complaint data.
- Interactive Power BI dashboard development.
- Evaluation of retention strategies through A/B testing.

## Conclusion

ChurnQuest demonstrates how Excel-based exploratory data analysis can identify meaningful customer churn patterns and support data-driven business decisions.

The analysis highlights customer service interactions, international plan subscriptions, and calling behavior as important characteristics associated with churn.

By combining descriptive analytics, customer segmentation, and dashboard reporting, the project provides a practical foundation for investigating customer retention opportunities.

---

**Project Type:** Data Analytics Portfolio Project
**Domain:** Telecommunications | Customer Analytics
**Primary Skills:** Excel, Power Query, Data Cleaning, Exploratory Data Analysis, Customer Segmentation, Data Visualization, Business Insights
