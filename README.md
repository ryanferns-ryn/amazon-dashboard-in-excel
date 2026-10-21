 Amazon India Sales Dashboard | Excel Data Analytics

An Excel-based dashboard project focused on analysing Amazon India sales data to understand sales performance, profitability, product categories, order status, and regional trends.

The project uses data analysis and visualisation techniques to transform sales records into a dashboard that helps users explore business performance and identify patterns.

---

 Dashboard Preview

<!-- Add your actual dashboard screenshot to the assets folder and update the path below. -->

![Amazon India Sales Dashboard](assets/dashboard-preview.png)

*Interactive dashboard built in Microsoft Excel.*

---

Project Overview

E-commerce businesses generate large amounts of sales and order data. Analysing this information can help identify profitable product categories, understand customer purchasing patterns, and monitor operational performance.

This project explores Amazon India sales data through an Excel dashboard, bringing key performance indicators and visual summaries into one place.

 Objectives

* Analyse overall sales and profitability.
* Identify top-performing product categories and products.
* Track order statuses, including cancellations and returns.
* Examine sales performance across different states.
* Compare payment and fulfilment methods.
* Understand changes in sales performance over time.
* Present business metrics through a clear, interactive dashboard.

---

 Tools & Technologies

| Tool                      | Purpose                                         |
| ------------------------- | ----------------------------------------------- |
| Microsoft Excel           | Data analysis and dashboard development         |
| Excel formulas            | Calculating key performance indicators          |
| PivotTables               | Summarising and grouping sales data             |
| PivotCharts               | Visualising sales trends and comparisons        |
| Excel filters and slicers | Exploring data interactively, where implemented |

*Only retain the techniques that are actually used in your workbook.*

---

Key Performance Indicators

The dashboard is designed to examine the following metrics, subject to the fields available in the dataset.

| KPI                 | Description                                       |
| ------------------- | ------------------------------------------------- |
| Total Sales         | Total sales value represented in the dataset      |
| Total Profit        | Total profit, if profit data is available         |
| Total Orders        | Number of distinct orders                         |
| Units Sold          | Total quantity of products sold                   |
| Average Order Value | Average sales value per order                     |
| Profit Margin       | Profit as a percentage of sales                   |
| Cancellation Rate   | Percentage of eligible orders that were cancelled |
| Return Rate         | Percentage of eligible orders that were returned  |

### KPI Calculations

**Average Order Value (AOV)**

Average Order Value measures the average sales value per order.

`AOV = Total Sales / Number of Distinct Orders`

**Profit Margin**

Profit Margin measures profit relative to sales.

`Profit Margin (%) = (Total Profit / Total Sales) × 100`

**Cancellation Rate**

`Cancellation Rate (%) = (Cancelled Orders / Eligible Orders) × 100`

**Return Rate**

`Return Rate (%) = (Returned Orders / Eligible Orders) × 100`

The denominator for cancellation and return rates must be defined consistently with the dataset. If the dataset does not contain profit, costs, or distinct order identifiers, the corresponding metrics should not be presented as verified results.

---

 Dashboard Analysis

 1. Sales Performance

Examines overall sales activity and changes over time.

Key questions:

* How much sales value is represented in the dataset?
* Which months have the highest and lowest sales?
* Are there noticeable changes in sales over time?
* How does order volume change across the reporting period?

### 2. Product & Category Analysis

Examines the contribution of different product categories and products.

Key questions:

* Which categories contribute the most to sales?
* Which products generate the highest sales?
* Do the highest-selling categories also generate the highest profit?
* Which categories may require further investigation?

 3. Order Status Analysis

Examines order outcomes and operational performance.

Key questions:

* What proportion of orders was delivered?
* How many orders were cancelled or returned?
* Which categories have relatively high cancellation or return rates?
* Are there patterns that warrant further investigation?

 4. Regional Analysis

Examines sales performance across available geographic regions.

Key questions:

* Which states contribute the most to sales?
* How does order volume vary across states?
* Are there differences between regional sales and profitability?

 5. Payment & Fulfilment Analysis

Explores the distribution of orders across available payment and fulfilment methods.

Key questions:

* Which payment methods account for the most orders?
* How are orders distributed across fulfilment methods?
* Do sales outcomes vary between fulfilment categories?

---

 Dataset

**Dataset file:** `Amazon Sales Data India.xlsx`

The repository contains the Excel dataset used for the project.

Before interpreting the results, the dataset should be reviewed to establish:

* Original source and attribution.
* Reporting period.
* Number of records.
* Available columns and their meanings.
* Missing values and duplicate records.
* Whether sales, profit, costs, returns, and cancellations are explicitly recorded.

**Data source:** [Add the original dataset URL or source attribution here.]

The dataset should be described according to its actual provenance. Its presence in this project does not, by itself, establish that it contains official or internal Amazon business data.

---

 Methodology

The analysis follows a structured workflow.

1. **Data inspection** — Review the dataset's structure, column names, data types, and completeness.
2. **Data cleaning** — Identify missing values, duplicates, inconsistent formats, and invalid records where applicable.
3. **Data preparation** — Prepare the fields required for analysis and ensure that calculations use consistent definitions.
4. **KPI calculation** — Calculate relevant sales, order, and profitability metrics supported by the data.
5. **Data summarisation** — Use Excel formulas and PivotTables, where implemented, to aggregate and compare performance.
6. **Visualisation** — Present key metrics and comparisons through charts and dashboard elements.
7. **Validation** — Cross-check totals and calculations against the underlying data.
8. **Interpretation** — Examine patterns and identify findings supported by the results.

---

 Key Business Insights

This section should contain findings verified from the completed workbook.

Examples of questions to investigate:

* Which product category contributes the most to total sales?
* Which category generates the highest total profit, if profit data is available?
* Which products have the highest sales values?
* Which months show the strongest and weakest sales?
* Which states contribute the most to overall sales?
* Which categories have the highest cancellation or return rates?

For each finding, include the relevant value, the comparison used, and its potential business implication.

*Actual findings will be added after the dashboard calculations and results have been verified. The questions above are analytical objectives, not claims about the dataset.*

---

 How to Use

1. Open the repository and download the Excel workbook.
2. Open the workbook in Microsoft Excel.
3. Navigate to the dashboard worksheet.
4. Use the available filters or slicers to explore the data, if implemented.
5. Review the KPI summaries and charts.
6. Consult the underlying worksheets for supporting data and calculations.

If the workbook uses PivotTables, refresh them when appropriate. External data connections or macros, if present, may require additional configuration.

**Main workbook:** `ryan amazon.xlsx`

---

 Limitations

* Findings depend on the completeness and reliability of the available dataset.
* The analysis cannot establish information that is absent from the source data.
* Sales value should not be treated as profit.
* Correlations and patterns do not independently establish causation.
* Return and cancellation rates depend on the definitions and status fields available in the dataset.
* Results should not be interpreted as official Amazon corporate performance unless the dataset's provenance supports that interpretation.

---

## Future Improvements

Potential improvements include:

* Adding more detailed time-based comparisons.
* Improving data validation and documenting cleaning decisions.
* Adding additional interactive filters where useful.
* Comparing sales and profitability across categories and regions.
* Documenting verified business findings with supporting figures.
* Automating data refreshes if a reliable source and appropriate workflow are available.

---

Author

**Ryan Joe Fernandes**

BCA Student | Aspiring Data Analyst & Data Engineer

GitHub: [ryanferns-ryn](https://github.com/ryanferns-ryn)

---

*This project was developed for learning and portfolio purposes, demonstrating the use of Excel for sales analysis, KPI reporting, and dashboard visualisation.*
