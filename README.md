# Mobile_Sales_Performanace_Dashboard.

This project features a comprehensive, interactive dashboard designed to analyze mobile device sales, track performance over time, and uncover actionable insights. Built as a showcase of advanced data visualization and creative data storytelling for a professional portfolio, the dashboard provides a deep dive into geographic trends, brand performance, and time-intelligence KPI calculation logic.

## Project Overview

The dashboard processes raw transaction records from **Order 2023 Dataset.xlsx** and transforms them into an intuitive interface. It allows users to filter data dynamically by Mobile Model, Payment Method, Brand, and custom date ranges, providing both high-level summaries and granular temporal comparisons.

## Core Dashboard Modules

* **Main Sales Dashboard (`R.png`):** Serves as the primary landing page, offering a high-level geographical and categorical overview of performance.
* **Same Period Analysis (`C.png`):** Focuses on Year-over-Year (YoY) comparative analysis, contrasting current sales figures against the exact same period in the previous year.
* **MTD Report (`B.png`):** Provides a detailed Month-to-Date tracking view, illustrating the cumulative buildup of sales throughout each period.

## Key Performance Indicators (KPIs)

The top navigation bar features dynamically calculated KPIs that respond to user filters:

* **Total Sales:** Overall revenue generated.
* **Total Quantity:** Number of individual mobile units sold.
* **Transactions:** Total distinct purchase events.
* **Average Price:** The mean selling price per unit.

## Data Visualizations & Storytelling Elements

* **Geospatial Mapping:** A geographic map visualizing Total Sales by City across India, pinpointing high-revenue regional hubs.
* **Time-Series Analysis:**
* Line charts mapping Total Quantity by Month.
* Step-line charts detailing MTD sales progression across the year.
* Area charts highlighting Total Sales by Day Name to identify weekly purchasing trends.


* **Categorical Breakdowns:**
* Horizontal bar charts ranking Total Sales by Mobile Model.
* Pie charts illustrating Transactions by Payment Method (UPI, Debit Card, Credit Card).
* Funnel charts displaying Customer Ratings by Rating Status (Good, Average, Poor).


* **Comparative Analytics:** Clustered bar charts comparing Total Sales vs. Same Period Last Year broken down by Year, Quarter, and Day.

## Dataset

* **Source File:** `Order 2023 Dataset.xlsx`
* **Key Dimensions:** Date (Year, Quarter, Month, Day), City, Brand, Mobile Model, Payment Method, Rating.
* **Key Measures:** Sales Amount, Quantity, Transaction Count, Price.

## Interactivity & Navigation

The left-hand navigation pane allows seamless switching between the three main report pages. A dedicated month-selector panel (January–December) and top-tier drop-down slicers ensure that users can slice the data precisely to isolate specific market segments or timeframes.
