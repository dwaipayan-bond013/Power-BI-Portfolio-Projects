## Car Sales Analysis
<p align="center">
  <img src="Poster.PNG" width="1100px">
</p>

## 📊 Overview

The objective of this project is to design and implement a comprehensive business intelligence dashboard using Power BI to monitor, analyze, and derive insights from car sales data. This dashboard is intended to serve as a decision-support system for automotive dealership executives, sales managers, and operational teams by providing a real-time, visual representation of key sales metrics and patterns.

## Dataset Used

| **Column Name** | **Description**                                | **Data Type** | **Example Value**                     |
| --------------- | ---------------------------------------------- | ------------- | ------------------------------------- |
| `Car_id`        | Unique identifier for the car                  | Object        | `C_CND_000001`                        |
| `Date`          | Date of the car sale                           | DateTime      | `2022-01-02`                          |
| `Customer Name` | Full name of the customer                      | Object        | `Geraldine`                           |
| `Gender`        | Gender of the customer                         | Object        | `Male`                                |
| `Annual Income` | Customer’s reported yearly income              | Integer       | `13500`                               |
| `Dealer_Name`   | Name of the car dealership                     | Object        | `Buddy Storbeck's Diesel Service Inc` |
| `Company`       | Car manufacturing brand                        | Object        | `Ford`                                |
| `Model`         | Specific model of the car                      | Object        | `Expedition`                          |
| `Engine`        | Engine type of the car                         | Object        | `Double Overhead Camshaft`            |
| `Transmission`  | Type of transmission (e.g., Auto, Manual)      | Object        | `Auto`                                |
| `Color`         | Color of the vehicle sold                      | Object        | `Black`                               |
| `Price ($)`     | Final sale price of the vehicle                | Integer       | `26000`                               |
| `Dealer_No`     | Unique code for the dealership                 | Object        | `06457-3834`                          |
| `Body Style`    | Body type of the vehicle (e.g., SUV, Sedan)    | Object        | `SUV`                                 |
| `Phone`         | Contact number (possibly masked or incomplete) | Integer       | `8264678`                             |
| `Dealer_Region` | Geographic region or location of the dealer    | Object        | `Middletown`                          |

## 📊 Key Analysis Areas
<p align="center">
  <img src="Overview.PNG" width="1000px">
</p>

The dashboard analyzes the following key dimensions:
  - **Monitor Sales Performance at Scale**
     - Track key performance indicators (KPIs) such as total revenue, units sold, and average selling price across various dimensions (time, brand, region, model, etc.) to evaluate overall and segmented performance

  - **Identify Product & Customer Trends**
     - Analyze vehicle sales by body style, color, model, and brand to identify which products are most in demand, enabling more data-driven inventory and marketing strategies

  - **Regional & Dealer-Level Evaluation**
     - Compare sales performance across geographical regions and dealership networks to spotlight high-performing areas and uncover underperforming zones that may need attention or strategic intervention

  - **Understand Sales Seasonality & Timing**
     - Visualize weekly sales trends to uncover seasonal patterns, peak performance weeks, and monthly fluctuations, supporting more effective forecasting and promotional planning

  - Support Data-Driven Decision Making
     - Empower stakeholders to make faster, more informed decisions by replacing manual reporting with interactive, filterable dashboards that provide instant access to granular insights

  - Enhance Profitability & Efficiency
     - Use the insights to optimize pricing strategies, reduce slow-moving inventory, and improve sales conversion by focusing efforts on high-margin products and top-selling dealers

## 📈 Insights and Recommendations

 1.  KPI Summary

  | Metric                | Value                         | Insight                                                                                                        |
  | --------------------- | ----------------------------- | -------------------------------------------------------------------------------------------------------------- |
  | **YTD Total Sales**   | \$371M (↑ \$70.8M / +23.59%)  | Strong year-to-date growth — indicates increased demand or successful sales campaigns.                         |
  | **YTD Average Price** | \$28K (↓ \$0.22K / –0.79%)    | Slight dip in average pricing — possibly due to discounting or selling more budget models.                     |
  | **YTD Cars Sold**     | 13K units (↑ 2.62K / +24.57%) | Strong volume growth; aligns with revenue increase. Possibly more units sold at slightly lower price per unit. |

  Volume-led revenue growth suggests expansion into lower-priced or mid-tier vehicles is working. Margin management might be a concern due to lower average price.

  2. YTD Sales ($) by Week 
     - Consistent weekly growth with a peak at week 35 (~$14.9M)
     - Likely a successful seasonal campaign (e.g., summer sales or new model release)

  3. YTD Sales by Body Style (Donut Chart)
     - SUVs and Sedans are dominant styles and Hatchbacks, Passenger, Hardtop are smaller segments
     - Customer preference leans toward SUVs and Sedans. These segments should continue to be the product focus
