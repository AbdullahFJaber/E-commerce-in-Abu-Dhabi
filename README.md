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
| Removed Columns      | city               | City of the store                           | Outside project's Abu Dhabi scope |
| Removed Columns      | date only          | Raw date field                              | Standardized into OrderDate format |
| Newly Added Columns  | OrderSegment       | Categorizes transactions by size            | Improves segmentation analysis |
| Newly Added Columns  | NetSales           | Calculates actual realized revenue          | More accurate revenue tracking |
| Newly Added Columns  | LostRevenue        | Quantifies financial leakage value          | Identifies missed revenue opportunities |
| Newly Added Columns  | DeliveryCostRatio  | Measures logistics cost efficiency          | Helps optimize delivery costs |
| Newly Added Columns  | Fulfillment        | Tracks order success status                 | Monitors operational performance |
| Newly Added Columns  | Day                | Enables day-of-week analysis                | Supports time-based insights |
