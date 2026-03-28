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

| Column Status          | Column Name        | Description                                  | Reason                     |
|----------------------|--------------------|----------------------------------------------|----------------------------|
| Removed Columns      | StoreID            | Store identifier                            | Redundant; Store name is sufficient |
| Removed Columns      | city               | City of the store                           | only Abu Dhabi City,No other cities |
| Removed Columns      | date only          | Raw date field                              | It has no relevance to the order date |

| Newly Added Columns  | OrderSegment       | Categorizes transactions by size            | Improves segmentation analysis |
| Newly Added Columns  | NetSales           | Calculates actual realized revenue          | More accurate revenue tracking |
| Newly Added Columns  | LostRevenue        | Quantifies financial leakage value          | Identifies missed revenue opportunities |
| Newly Added Columns  | DeliveryCostRatio  | Measures logistics cost efficiency          | Helps optimize delivery costs |
| Newly Added Columns  | Fulfillment        | Tracks order success status                 | Monitors operational performance |
| Newly Added Columns  | Day                | Enables day-of-week analysis                | Supports time-based insights |



## 🖥️ Dashboard Pages Overview

### 📈 Executive Overview
- Focus: Financial Performance & Market Share.
- Tracks Net Sales, Fulfillment Rates, and organizational Market Share through high-level KPIs.
- Provides a macro-view of business health across different segments.

<img width="985" height="552" alt="image" src="https://github.com/user-attachments/assets/137400c5-2f79-4ec9-bc87-cd154e47e7df" />

--------------------------------------------------------------------------------------------------------------------------------

### 🔍 Loss Analysis
- Focus: Revenue Leakage & Cancellations.
- Pinpoints financial losses and order cancellations segmented by Store, Week, and Marketing Campaign.
- Identifies specific pain points to minimize revenue drain.

<img width="983" height="556" alt="image" src="https://github.com/user-attachments/assets/d9f22564-36d7-46f2-8393-4c7e8e750d1c" />
--------------------------------------------------------------------------------------------------------------------------------

### 🚚 Operational Time & Cost
- Focus: Logistics Efficiency & Delivery Performance.
- Evaluates Delivery Partner performance, Delivery Fees, and Order Density.
- Measures cost-effectiveness to optimize logistics spending and supply chain speed.

<img width="983" height="554" alt="image" src="https://github.com/user-attachments/assets/8ecccd41-7319-43ac-975d-f3de5b960953" />
--------------------------------------------------------------------------------------------------------------------------------

### 🔭 Strategic Insights
- Focus: Future Planning & Campaign ROI.
- Leverages AI-driven Sales Forecasting and trend analysis for long-term decision-making.
- Measures the ROI of UTM Campaigns to guide future marketing investments.

<img width="984" height="554" alt="image" src="https://github.com/user-attachments/assets/ccfec1f9-79d5-4e0e-aa6c-df5a4d493e2b" />
--------------------------------------------------------------------------------------------------------------------------------


## 🗂 Files in This Repository

- Multi-Brand E-commerce Order Tracking & Delivery Performance - Original.xlsx
- Multi-Brand E-commerce in Abu Dhabi .xlsx
- Multi-Brand E-commerce in Abu Dhabi.pbix

## 🔗 Interactive Dashboard

https://bit.ly/4dlu5qh

You can explore the fully interactive dashboard online without needing Power BI Desktop. Click the link below to view the report:
 ‏‏

Note: The dashboard works best on desktop browsers. Mobile browsers may have limited functionality.

