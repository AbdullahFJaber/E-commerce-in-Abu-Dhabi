# E-commerce-in-Abu-Dhabi

"Strategic E-commerce analytics in Abu Dhabi. Features 4 interactive Power BI dashboards covering Financial KPIs, Operational efficiency, and Revenue Loss analysis. High priority was given to Data Cleaning and DAX optimization. The project integrates AI-powered Forecasting and UTM campaign tracking to transform raw data into actionable insights."

## 🎯 Project Objectives

- Data Transformation: Processing and cleaning raw transactional data to ensure high-quality, reliable reporting.

- Operational Visibility: Providing a comprehensive view of sales performance, logistics efficiency, and market share.

- Loss Identification: Pinpointing revenue leakage areas and cancellation drivers to mitigate financial risk.

- Trend Prediction: Implementing AI-based forecasting to assist in proactive inventory and resource planning.

## 📖 Case Study Scenario

An E-commerce platform operating in the Abu Dhabi market faces challenges in tracking performance across multiple stores, delivery partners, and marketing campaigns. The raw dataset requires significant refinement to move from basic record-keeping to strategic intelligence. This project acts as a bridge, converting thousands of transaction rows into four distinct, interactive dashboards tailored for executive-level decision-making.

## 💡 Business Need

In a competitive E-commerce environment, rapid response to market shifts is essential. Management requires a solution to:

Monitor real-time performance of diverse brands and organizations.

Analyze the cost-effectiveness of various delivery partners to optimize logistics spending.

Evaluate the ROI of marketing (UTM) campaigns to allocate budgets effectively.

Predict future sales volume to manage operational capacity

## 📊 Scope & KPIs

The analytics model focuses on four key dimensions, monitored through specific metrics:

- Financial Performance: Tracked via Total Net Sales, Gross Order Value, and Realized Revenue.

- Operational Efficiency: Measured through Collection Efficiency %, Fulfillment Rate, and Avg Delivery Fee.

- Revenue Integrity: Monitored using Total Lost Revenue, Cancellation Rate, and Revenue Leakage.

- Market Dynamics: Segmented by Order Size (Large, Medium, Small), Store Location, and UTM Campaign impact.

## 🛠️ Data Transformation Log
1. Removed Columns
Column Name,Reason for Removal
StoreID,Redundant; Store name is sufficient.
city,Outside project's Abu Dhabi scope.
date only,Standardized into OrderDate format.

2. Newly Added Columns
Column Name,Reason for Addition
OrderSegment,Categorizes transactions by size.
NetSales,Calculates actual realized revenue.
LostRevenue,Quantifies financial leakage value.
DeliveryCostRatio,Measures logistics cost efficiency.
Fulfillment,Tracks order success status.
Day,Enables day-of-week analysis.
