# Online Retail Sales Analysis Dashboard (Power BI)

## Overview

This project presents a comprehensive analysis of online retail sales data using Microsoft Power BI. The objective was to transform raw transactional data into meaningful business insights that can support strategic decision-making, customer retention, revenue growth, and international expansion.

The dashboard was developed as part of a business intelligence and data visualization exercise, focusing on answering key questions from executive stakeholders through interactive and insightful visualizations.

---

## Business Objectives

The analysis was designed to address the following business questions:

1. How did revenue trend throughout 2011, and are there any seasonal patterns?
2. Which countries generate the highest revenue outside the United Kingdom?
3. Who are the top revenue-generating customers?
4. Which regions demonstrate the highest product demand and present opportunities for future expansion?

---

## Data Preparation and Cleaning

Before creating any visualizations, the dataset was cleaned to ensure accuracy and reliability.

### Data Quality Checks

The following records were excluded from the analysis:

* Transactions where Quantity was less than or equal to zero.
* Transactions where Unit Price was less than or equal to zero.

These records represented returns, cancellations, or invalid data entries that could distort business insights.

### Calculated Field

A new Revenue metric was created using:

Revenue = Quantity × Unit Price

This metric was used throughout the dashboard to evaluate business performance.

---

## Dashboard Visualizations

### 1. Monthly Revenue Trend (2011)

**Visualization:** Line Chart

**Purpose:**

* Analyze monthly revenue performance.
* Identify seasonal trends and peak sales periods.
* Support future forecasting and planning.

**Business Insight:**
Revenue shows clear fluctuations throughout the year, with stronger performance during peak shopping periods, indicating seasonal purchasing behavior.

---

### 2. Top 10 Revenue-Generating Countries

**Visualization:** Clustered Bar Chart

**Purpose:**

* Compare revenue and quantity sold across countries.
* Identify high-performing international markets.
* Exclude the United Kingdom to focus on expansion opportunities.

**Business Insight:**
Several international markets contribute significant revenue and sales volume, highlighting attractive opportunities for targeted growth initiatives.

---

### 3. Top 10 Customers by Revenue

**Visualization:** Column Chart

**Purpose:**

* Identify the most valuable customers.
* Understand customer contribution to overall revenue.
* Support retention and loyalty strategies.

**Business Insight:**
A small group of customers generates a significant portion of total revenue, emphasizing the importance of customer retention and personalized engagement.

---

### 4. Global Demand Analysis

**Visualization:** Map Chart

**Purpose:**

* Visualize product demand by country.
* Identify regions with strong purchasing activity.
* Support market expansion and geographic growth strategies.

**Business Insight:**
Countries with high demand present strong opportunities for market expansion, localized marketing efforts, and increased business investment.

---

## Dashboard Screenshots

### Question 1 – Monthly Revenue Trend

![Monthly Revenue Trend](screenshots/Q1_Monthly_Revenue_Trend.png)

### Question 2 – Top 10 Revenue-Generating Countries

![Top Countries](screenshots/Q2_Top_10_Countries.png)

### Question 3 – Top 10 Customers by Revenue

![Top Customers](screenshots/Q3_Top_10_Customers.png)

### Question 4 – Global Demand Analysis

![Global Demand Map](screenshots/Q4_Global_Demand_Map.png)

---

## Key Skills Demonstrated

* Data Cleaning and Transformation
* Data Modeling
* DAX Calculations
* Business Intelligence Reporting
* Data Visualization
* Customer Analytics
* Revenue Analysis
* Geographic Market Analysis
* Dashboard Development
* Business Storytelling

---

## Tools and Technologies

* Microsoft Power BI
* DAX (Data Analysis Expressions)
* Power Query

---

## Repository Structure

```text
online-retail-sales-analysis-powerbi/
│
├── Online_Retail_Sales_Analysis.pbix
├── README.md
└── screenshots/
    ├── Q1_Monthly_Revenue_Trend.png
    ├── Q2_Top_10_Countries.png
    ├── Q3_Top_10_Customers.png
    └── Q4_Global_Demand_Map.png

```

---

## Key Recommendations

Based on the analysis:

* Leverage seasonal trends to improve forecasting and inventory planning.
* Increase focus on high-performing international markets.
* Strengthen relationships with top revenue-generating customers.
* Prioritize expansion efforts in countries with strong product demand.

---

## Conclusion

This dashboard provides a clear view of revenue performance, customer behavior, international market contribution, and global demand patterns. The insights generated can support data-driven decision-making and help identify future growth opportunities for the business.

---

## Author

**Varun Kumar**

B.Tech Computer Science Engineering
Aspiring Data Analyst | Power BI Developer | Full Stack Developer
