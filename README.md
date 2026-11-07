# TELECOM CUSTOMER CHURN ANALYSIS USING BUSINESS ANALYTICS AND DATA VISUALIZATION

**Domain:** Business Analytics and Data Visualization
## 1. Objective

To analyse telecom customer churn patterns, identify high-risk customers, and provide actionable business insights using Excel and Power BI dashboards to improve customer retention and reduce revenue loss.

## 2. Introduction

Customer churn is one of the major challenges faced by telecommunications companies. Customer churn occurs when customers discontinue services or switch to competitors. High churn rates negatively impact company revenue, profitability, and market share.

This project focuses on analysing telecom customer data to identify patterns and factors contributing to customer churn. By using Business Analytics and Data Visualization techniques, the project aims to help telecom companies proactively identify customers who are likely to leave and implement effective retention strategies.

The project involves data cleaning, exploratory data analysis, KPI analysis, customer segmentation, and interactive dashboard development using Excel and Power BI.

The final outcome of the project is to provide data-driven business insights that support decision-making and improve customer retention.

## 3. Business Problem Statement

Telecom companies experience significant financial losses due to customer churn. Acquiring new customers is more expensive than retaining existing customers. High churn rates lead to revenue loss, increased operational costs, reduced customer lifetime value, and declining market share.

The company requires a data-driven solution to:

- Identify customers likely to churn.
- Understand the major churn drivers.
- Improve customer retention.
- Reduce revenue loss.
- Support strategic business decision-making.

This project aims to solve these challenges using business analytics and visualization techniques.

## 4. Project Objectives

The main objectives of this project are:

1. To analyze telecom customer data and identify churn patterns.
2. To understand the factors influencing customer churn.
3. To identify high-risk customer segments.
4. To create interactive dashboards for business decision-making.
5. To provide actionable recommendations for customer retention.
6. To estimate the business impact of customer churn.
7. To improve business understanding using data visualization techniques.

## 5. Primary Business Questions

The project focuses on answering the following business questions:

1. Which customers are most likely to churn?
2. Does monthly charge affect customer churn?
3. Which contract types have the highest churn rates?
4. Does technical support reduce churn?
5. Which services contribute most to customer retention?
6. What customer segments are at high risk?
7. What is the financial impact of customer churn?
8. How can telecom companies improve retention strategies?

## 6. Initial Hypotheses

Based on general telecom customer behavior, the following hypotheses were considered for analysis:

1. Customers with month-to-month contracts are more likely to churn.
2. Customers with higher monthly charges have a higher probability of churning.
3. Customers without technical support services are more likely to leave.
4. Customers with shorter tenure are more likely to churn.
5. Customers using bundled services are less likely to churn.

These hypotheses provide a starting point for exploratory data analysis and help identify potential factors influencing customer churn.

## 7. Dataset Overview

The dataset used in this project contains telecom customer information, including demographics, account details, subscribed services, and churn status.

Important dataset features include:

- Customer demographics.
- Contract information.
- Payment methods.
- Internet services.
- Technical support services.
- Monthly and total charges.
- Customer tenure.
- Churn status.

The target variable in the dataset is **Churn**, which indicates whether a customer left the company or stayed.

The dataset provides the necessary information to analyze customer behavior, identify churn patterns, and understand the factors associated with customer attrition.

## 8. Tools and Technologies Used

The following tools and technologies were used to perform data analysis and develop the interactive dashboard.

### 8.1 Microsoft Excel

Microsoft Excel was used for examining and organizing the telecom customer dataset.

- Used for inspecting and understanding the dataset.
- Performed data cleaning and basic data manipulation.
- Supported preliminary analysis of customer information.
- Helped organize customer attributes for further analysis.

### 8.2 Microsoft Power BI

Microsoft Power BI was used to develop interactive dashboards and visual reports.

- Created KPI cards to display important business metrics.
- Developed bar charts, donut charts, scatter plots, and line charts.
- Implemented interactive filters and slicers.
- Presented customer churn patterns and business performance indicators.
- Enabled customer segmentation and comparative analysis.

### 8.3 Business Analytics Techniques

The following analytical techniques were used:

- Exploratory Data Analysis (EDA).
- Customer segmentation.
- KPI monitoring.
- Trend analysis.
- Comparative analysis.
- Data visualization.

## 9. Project Methodology

The project follows a systematic business analytics approach to transform raw telecom customer data into meaningful business insights.

The methodology consists of the following stages:

### 9.1 Data Collection

Obtaining the telecom customer dataset containing customer demographics, subscribed services, contract details, payment methods, and billing information.

### 9.2 Data Understanding

Examining the dataset structure, identifying important attributes, and understanding the target variable (Churn).

### 9.3 Data Cleaning

Identifying missing values, duplicate records, inconsistent data, and incorrect data formats.

### 9.4 Data Preprocessing

Preparing the dataset for analysis by organizing columns, handling missing values, and ensuring appropriate data types.

### 9.5 Exploratory Data Analysis

Analyzing customer churn patterns across different categories and identifying relationships between customer characteristics and churn behavior.

### 9.6 KPI Analysis

Calculating important business metrics such as total customers, churned customers, active customers, churn rate, average monthly charges, and revenue loss.

### 9.7 Dashboard Development

Creating interactive visualizations using Microsoft Power BI to present important business metrics and customer trends.

### 9.8 Business Insights

Interpreting the results and identifying high-risk customer segments to support customer retention strategies.

## 10. Data Cleaning and Preprocessing

Data cleaning and preprocessing are important steps in ensuring the accuracy and reliability of business analysis.

The telecom customer dataset was examined and prepared before developing the dashboard.

The preprocessing activities include:

- Checking the dataset for missing and null values.
- Identifying and removing duplicate customer records, where applicable.
- Checking data types of numerical and categorical attributes.
- Handling inconsistent values and formatting issues.
- Organizing customer information into meaningful categories.
- Preparing the churn column for customer segmentation.
- Ensuring that numerical attributes such as Monthly Charges and Total Charges are suitable for analysis.

These steps help improve data quality and ensure reliable visualizations.

## 11. Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand customer behavior and identify factors associated with customer churn.

The analysis focused on the following aspects:

### 11.1 Contract Analysis

Examining customer churn across month-to-month, one-year, and two-year contract categories to understand differences in customer retention.

### 11.2 Internet Service Analysis

Studying customer distribution across Fiber Optic, DSL, and No Internet Service categories.

### 11.3 Payment Method Analysis

Comparing churn patterns among customers using electronic check, mailed check, bank transfer, and credit card payment methods.

### 11.4 Tenure Analysis

Examining customer churn across different tenure groups, including new customers, early-stage customers, established customers, and loyal customers.

### 11.5 Monthly Charges Analysis

Studying the relationship between monthly charges and customer churn to understand customer billing patterns.

### 11.6 Device Protection Analysis

Analyzing customer behavior based on the availability of device protection services.

The results of EDA helped identify important customer segments and supported the development of the final dashboard.

## 12. Key Performance Indicators (KPIs)

Key Performance Indicators are used to measure customer retention, customer attrition, and the financial impact of churn.

The dashboard displays the following KPIs:

| KPI                     | Dashboard Value |
|-----------------------  | --------------- |
| Total Customers         | 7.01K           |
| Churned Customers       | 2K              |
| Active Customers        | 5K              |
| Churn Rate              | 26.49%          |
| Average Monthly Charges | 64.89           |
| Revenue Lost            | 138.54K         |

### 12.1 KPI Description

**Total Customers:** Represents the total number of customers included in the analysis.

**Churned Customers:** Represents customers who discontinued the telecom services.

**Active Customers:** Represents customers who continue using the services.

**Churn Rate:** Indicates the percentage of customers who discontinued the services.

**Average Monthly Charges:** Represents the average monthly amount charged to customers.

**Revenue Lost:** Represents the estimated financial impact associated with customer churn, based on the project's calculation.

These KPIs provide an overview of the company's customer retention performance and financial impact.

## 13. Dashboard Development and Visualization

An interactive dashboard was developed using Microsoft Power BI to present customer churn patterns and business performance indicators.

The dashboard combines multiple visualizations into a single interface, allowing users to understand customer behavior and identify important trends.

The dashboard includes:

- KPI cards to display important business metrics.
- Bar charts to compare customer churn across different categories.
- Donut charts to represent customer distribution.
- Scatter plots to analyze monthly charges against churn.
- Line charts to examine churn rates across tenure groups.
- Tabular visualization to display high-risk customer details.
- Interactive slicers to filter customer information.

The dashboard provides a consolidated view of customer churn behavior and supports data-driven business decision-making.

## 14. Dashboard Components

The developed Power BI dashboard consists of the following components:

### 14.1 Customer Filters

Interactive filters are provided for:

- Gender.
- Senior Citizen.
- Contract.
- Internet Service.
- Payment Method.
- Tenure Group.

These filters allow users to explore customer churn patterns based on selected attributes.

### 14.2 Churn by Contract Type

This visualization compares customer churn across month-to-month, one-year, and two-year contracts.

It helps identify differences in customer attrition across contract categories.

### 14.3 Churn by Internet Service

This visualization presents the distribution of customers across Fiber Optic, DSL, and No Internet Service categories.

It helps examine customer distribution across different internet service types.

### 14.4 High-Risk Customers

A donut chart displays the distribution of customers classified into high-risk and low-risk groups.

It provides an overview of the customer risk classification.

### 14.5 Churn by Payment Method

This visualization compares customer churn across different payment methods to understand payment-related customer behavior.

### 14.6 Monthly Charges vs Churn

A scatter plot represents the relationship between monthly charges and churn status, helping examine customer billing patterns.

### 14.7 Churn Rate vs Tenure Group

A line chart compares churn rates across new customers, early-stage customers, established customers, and loyal customers.

It helps identify how customer retention changes with tenure.

### 14.8 Churn by Device Protection

This visualization examines customer churn across different device protection categories.

### 14.9 Churn by Tenure Group

A bar chart compares churned and non-churned customers across different customer tenure groups.

### 14.10 Top 10 High-Risk Customers

A table displays the top 10 high-risk customer records along with relevant information such as:

- Contract type.
- Senior citizen status.
- Internet service.
- Monthly charges.
- Payment method.
- Risk score.

This component helps identify individual customer records that may require attention for retention activities.

## 15. Key Findings and Business Insights

The dashboard provides several important insights into telecom customer behavior.

### 15.1 Customer Churn

The dashboard indicates an overall churn rate of 26.49%, highlighting the importance of improving customer retention.

### 15.2 Contract Type

Month-to-month contracts show greater customer churn compared with longer-term contract categories.

### 15.3 Internet Services

The customer distribution across Fiber Optic, DSL, and No Internet Service categories provides an understanding of the service mix.

### 15.4 Payment Methods

Electronic check users represent an important segment for payment-method-based churn analysis.

### 15.5 Customer Tenure

New customers show a higher churn rate compared with established and loyal customers.

### 15.6 Monthly Charges

The scatter plot helps examine the relationship between customer monthly charges and churn behavior.

### 15.7 Customer Risk Analysis

The dashboard identifies high-risk customers and displays their associated risk scores for further investigation.

### 15.8 Financial Impact

The dashboard reports an estimated revenue loss of 138.54K, demonstrating the business impact of customer attrition.

## 16. Business Recommendations

Based on the dashboard analysis, the following recommendations can help telecom companies improve customer retention.

### 16.1 Improve Contract Retention

Introduce attractive long-term contract offers and loyalty benefits to encourage month-to-month customers to continue their subscriptions.

### 16.2 Focus on New Customers

Provide better onboarding experiences, welcome offers, and early-stage customer support to reduce initial churn.

### 16.3 Analyze Payment Issues

Investigate customer dissatisfaction associated with electronic check payments and provide convenient alternative payment methods.

### 16.4 Improve Service Quality

Monitor internet service performance and provide reliable customer support to improve customer satisfaction.

### 16.5 Offer Personalized Pricing

Introduce suitable pricing plans and customized offers for customers with higher monthly charges.

### 16.6 Monitor High-Risk Customers

Use customer risk scores to identify customers who may require additional attention and targeted retention campaigns.

### 16.7 Strengthen Customer Relationships

Introduce loyalty programs, personalized communication, and customer feedback mechanisms.

## 17. Conclusion

The Telecom Customer Churn Analysis project demonstrates how Business Analytics and Data Visualization techniques can be used to understand customer attrition and its impact on business performance.

Using Microsoft Excel and Power BI, the project involved data examination, preprocessing, exploratory data analysis, KPI monitoring, customer segmentation, and interactive dashboard development.

The developed dashboard provides insights into customer churn across contract types, internet services, payment methods, device protection, and tenure groups. It also highlights high-risk customers and presents important business metrics, including a 26.49% churn rate and an estimated revenue loss of 138.54K.

Overall, the project demonstrates the importance of data-driven decision-making in identifying customer churn patterns, understanding business challenges, and supporting effective customer retention strategies.

## 18. Future Scope

The project can be further enhanced through the following improvements:

1. Integrating machine learning models to predict customer churn.
2. Developing automated customer risk scoring systems.
3. Incorporating real-time customer data for continuous churn monitoring.
4. Implementing automated alerts for high-risk customers.
5. Expanding the analysis using customer satisfaction and feedback data.
6. Integrating additional business intelligence features to improve reporting and decision-making.

These enhancements can help transform the current analytical dashboard into a more advanced customer churn prediction and retention management system.
