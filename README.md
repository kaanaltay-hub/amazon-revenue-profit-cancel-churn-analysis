# Amazon Sales Data Analysis  
### Multi-Page Power BI Dashboard for Revenue, Profitability, and Cancellation Root Cause Analysis

This project presents an end-to-end **Power BI business intelligence dashboard** built to analyze Amazon sales performance from multiple decision-making angles.  
The dashboard goes beyond standard sales reporting by combining **revenue analysis**, **profitability decomposition**, and **cancellation root cause exploration** into a structured analytical framework.

The goal was to transform raw e-commerce data into a **decision-support system** that helps identify revenue drivers, cost pressure points, operational weaknesses, and financially relevant cancellation patterns.

---

## Executive Summary

E-commerce datasets often contain rich operational and financial signals, but without structured analysis they remain difficult to translate into business decisions.  
This project addresses that gap by developing an interactive Power BI dashboard focused on four major questions:

- Which segments and regions drive revenue?
- Which cost components reduce profitability?
- Where are cancellations concentrated, and what is their financial impact?
- Which operational patterns may be linked to cancelled orders?

The result is a **multi-page dashboard architecture** that provides both high-level KPI monitoring and deeper diagnostic analysis across revenue, profit, and cancellation behavior.

---

## Business Problem

Amazon-style e-commerce operations generate large amounts of data across:

- orders
- revenue
- shipping
- fulfillment
- costs
- categories
- service levels
- order statuses
- geography

Without a structured BI layer, it becomes difficult to answer business-critical questions such as:

- Which customer or order segments generate the most revenue?
- How much of total revenue actually turns into profit?
- Which cost elements are eroding margins?
- Are cancellations randomly distributed, or concentrated in certain products, regions, or delay buckets?
- Which operational variables may indicate elevated cancellation risk?

This project was designed to answer those questions in a way that is both analytically solid and presentation-ready.

---

## Objectives

The main objectives of the project were:

- Build a clean and interactive **Power BI dashboard**
- Analyze **revenue performance over time and across segments**
- Decompose **profitability into core cost drivers**
- Quantify the **financial impact of cancelled orders**
- Explore likely **root causes of cancellations**
- Create a dashboard structure suitable for **business storytelling and stakeholder reporting**

---

## Dataset Overview

The project is based on e-commerce sales and order-level data containing fields related to:

- revenue
- order volume
- quantity
- average order value
- fulfillment channel
- shipping service level
- product category
- order status
- delay buckets
- region / shipping state
- product-level identifiers
- cost and profit metrics

The dataset supports analysis at multiple levels, including:

- time-based trends
- segment-based comparisons
- category-level performance
- state/region concentration
- operational diagnostics

---

## Data Privacy Note

For portfolio-safe sharing, sensitive and identifying fields were **anonymized / masked** where necessary.  
The analytical structure, business logic, and reporting relationships were preserved to maintain the integrity of the analysis.

In other words, the project remains analytically meaningful while respecting privacy and safe sharing principles.

---

## Tech Stack

### BI & Visualization
- Power BI
- Power Query

### Data Modeling & Calculations
- DAX
- Data Modeling
- KPI Design

### Analysis Focus
- Business Intelligence
- Revenue Analytics
- Profitability Analysis
- Cancellation Root Cause Analysis
- Dashboard Storytelling

### Version Control / Portfolio
- GitHub

---

## Methodology

The project followed a structured analytics workflow:

### 1. Data Understanding
Initial review of available sales, cost, fulfillment, and order-status fields to define business-relevant analytical questions.

### 2. Data Cleaning & Structuring
Preparation of fields for time-based, financial, operational, and segmentation analysis.

### 3. KPI & Measure Design
Creation of business-oriented metrics such as:

- Net Revenue USD
- Total Orders
- Total Quantity
- AOV
- Total Profit
- Profit Margin %
- Total Cost
- Cancelled Orders
- Cancelled Rate
- Cancelled Revenue
- Cancelled Profit

### 4. Dashboard Architecture
The dashboard was split into multiple pages to separate executive overview from deeper analysis:

- Home
- Revenue
- Revenue 2
- Revenue 3
- Profit
- Profit 2
- Profit 3
- Cancel
- Cancel 2
- Cancel 3
- Churn
- Churn 2

### 5. Diagnostic Analysis
Revenue and profitability reporting were extended with **root cause-oriented diagnostic analysis**, especially on the cancellation side through:

- delay buckets
- shipping duration
- service level
- category
- region/state
- ASIN concentration
- time-based patterns

---

## Dashboard Pages / Analysis Scope

## 1) Revenue Analysis

The revenue section was designed to answer how sales performance evolves over time and where revenue is concentrated.

### Included analyses:
- Net Revenue by month
- Revenue trends
- 7-day vs 30-day moving average
- Revenue by market region
- Revenue by fulfillment channel
- B2B vs B2C revenue trends
- Revenue by product category
- Revenue by shipping service level
- Single-item vs multi-item revenue mix
- Revenue by ship state / region

### Business value:
This section helps identify revenue concentration, segment contribution, and time-based trends that matter for planning and operational prioritization.

---

## 2) Profitability Analysis

The profitability section was designed to move beyond top-line sales and explain what actually drives or erodes profit.

### Included analyses:
- Total Profit
- Profit Margin %
- Total Product Cost
- Total Cost
- Waterfall-style cost decomposition
- Profit and margin by month
- Profit by fulfillment channel
- B2B vs B2C profit
- Regional/state profit contribution
- Successful vs lost value framing

### Business value:
This section connects revenue with cost structure and shows how shipping, promotions, and product costs affect overall profitability.

---

## 3) Cancellation Analysis

The cancellation section is one of the strongest components of the project.  
Rather than reporting cancelled orders only as a volume metric, the dashboard explores **their operational and financial drivers**.

### Included analyses:
- Total Cancelled Orders
- Cancelled Rate
- Cancelled Revenue
- Cancelled Profit
- Cancelled Orders by date
- Cancelled quantity by price segment
- Cancellation concentration by ASIN
- Cancellation rate by shipping duration
- Cancellation by state / region
- Revenue loss by product category
- Cancellation by delay bucket
- Cumulative cancellations by delay bucket
- Early vs late cancellation
- Cancellation behavior by shipping service level and delay bucket

### Business value:
This section helps reveal where cancellations are concentrated and which operational factors are most likely linked to them.

It supports questions such as:
- Are delays associated with more cancellations?
- Are some service levels more problematic than others?
- Which categories or products generate disproportionate cancellation loss?
- Which regions deserve operational attention?

---

## 4) Additional Churn Exploration

Although churn was not the main focus of the sprint scope, it was explored as an additional analytical extension.

### Included analyses:
- Churn-related KPI cards
- Churn rate by delay and service level
- Churned revenue by postal code
- Churned revenue by week
- Loyalty segment distribution
- Customer-oriented exploratory visuals

### Business value:
This section adds an early customer retention perspective and can be extended into a stronger predictive or segmentation-focused module in future iterations.

---

## Key KPIs

The dashboard includes a range of decision-oriented KPIs, including:

- **Net Revenue USD**
- **Total Orders**
- **Total Quantity**
- **AOV**
- **Total Profit**
- **Profit Margin %**
- **Total Product Cost**
- **Total Cost**
- **Cancelled Orders**
- **Cancelled Rate**
- **Cancelled Revenue**
- **Cancelled Profit**
- **Churned Customers**
- **Churned Revenue**
- **Churned Profit**
- **Churn Rate (%)**

---

## Key Insights

Some of the most important analytical takeaways from the project structure are:

- Revenue is not evenly distributed across regions, categories, service levels, and order segments.
- Profitability depends not only on sales volume but also on shipping cost, promotions, and product cost structure.
- Cancelled orders create visible **revenue and profit loss**, making cancellation analysis financially relevant, not just operationally interesting.
- Cancellation patterns appear concentrated in specific **delay buckets**, **regions**, **categories**, and **products**.
- Service level and shipping-related operational metrics provide useful signals for diagnostic root cause analysis.
- Churn-oriented exploratory views suggest that customer behavior can be analyzed further in future iterations.

---

## Technical / Modeling Highlights

- Multi-page dashboard design for clearer storytelling
- KPI card architecture for executive summaries
- DAX-based business measures
- Trend analysis with moving averages
- Segment analysis across order type, category, service level, and fulfillment channel
- Geographic analysis by state / region
- Waterfall logic for cost and profit explanation
- Diagnostic cancellation root cause analysis
- Business-oriented visual storytelling

---

## Challenges & Learnings

This project involved several important technical and analytical challenges:

### Translating raw operational data into business language
It was necessary to move from raw order and cost fields toward decision-oriented KPIs.

### Balancing overview and depth
A dashboard that is too simple misses important patterns; a dashboard that is too detailed becomes hard to present.  
This project required a careful balance between **executive-level clarity** and **analytical depth**.

### Connecting revenue, profit, and cancellations
Instead of treating these areas separately, the dashboard was structured to show how they influence each other.

### Building root cause analysis in Power BI
The cancellation side required a diagnostic design approach based on segmentation, delay buckets, service levels, and concentration analysis.

### Preserving analytical value with privacy-safe presentation
Sensitive elements needed to be anonymized while keeping the analytical relationships meaningful.

---

## Future Improvements

Potential next steps for this project include:

- deeper statistical validation of cancellation drivers
- predictive modeling for cancellations
- stronger churn modeling and customer retention analysis
- drillthrough pages for executive storytelling
- a stakeholder summary page
- Streamlit or web-app extension for interactive portfolio presentation

---

## Installation & Usage

### Option 1: Open the Power BI file
1. Download or clone the repository
2. Open the `.pbix` file in **Power BI Desktop**
3. Explore the dashboard pages and slicers interactively

### Option 2: Review the portfolio materials
- dashboard screenshots
- README documentation
- presentation / sprint summary files if included

---

## Project Structure

```bash
amazon-sales-data-analysis/
│
├── data/
│   └── masked_or_portfolio_safe_data_files
│
├── dashboard/
│   └── Sprint_2_Sunum.pbix
│
├── images/
│   ├── home_page.png
│   ├── revenue_page.png
│   ├── revenue_geo_page.png
│   ├── revenue_segment_page.png
│   ├── profit_page.png
│   ├── profit_region_page.png
│   ├── cancel_page.png
│   ├── cancel_region_page.png
│   └── cancel_delay_page.png
│
├── presentation/
│   └── sprint_summary_materials
│
└── README.md
