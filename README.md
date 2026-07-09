# Chocolate-Sales-Dashboard

An interactive Power BI dashboard created to analyze chocolate sales performance, profit, shipments, products, countries, and salesperson performance.

---

## 1. Project Title / Headline

### Chocolate Sales Dashboard

I created this interactive Chocolate Sales Dashboard using Power BI to analyze the overall performance of a chocolate sales business. The dashboard provides a clear view of important business metrics such as total sales, total profit, total cost, total boxes, shipments, profit percentage, and monthly performance.

---

## 2. Short Description / Purpose

The main purpose of this dashboard is to analyze chocolate sales data and understand business performance across different products, countries, months, and salespersons.

The dashboard allows users to filter the data by product category and country. It also includes a dynamic measure selector that allows users to switch between Sales, Boxes, Shipments, Cost, and Profit to analyze monthly trends.

I created this project to improve my practical knowledge of Power BI, Power Query, data modeling, DAX, interactive slicers, field parameters, and dashboard design.

---

## 3. Tech Stack

The following tools and technologies were used in this project:

- **Power BI Desktop** - Used to create the dashboard and data visualizations.
- **Power Query** - Used for data cleaning, transformation, and preparation.
- **DAX** - Used to create calculated measures and KPIs.
- **Data Modeling** - Used to create relationships between different tables.
- **Excel** - Used to store and organize the dataset.
- **GitHub** - Used to store and showcase the project.

---

## 4. Data Source

This project uses a publicly available chocolate sales dataset for learning and portfolio purposes.

The dataset contains information related to:

- Sales
- Shipments
- Products and product categories
- Salespersons
- Countries
- Costs
- Boxes shipped
- Transaction dates

The main tables used in the project are:

- Calendar
- People
- Products
- Shipments

The Shipments table is the main fact table containing transaction-level information. The Calendar, People, and Products tables are used as supporting dimension tables.

I used Power Query to check the data types, format date columns, organize the tables, and prepare the data for analysis.

---

## 5. Features / Highlights

### Business Problem

The main goal of this project is to understand the overall sales and profitability of a chocolate business and make it easier to analyze performance across products, countries, months, shipments, and salespersons.

The dashboard helps answer questions such as:

- What are the total sales and total profit?
- How many boxes and shipments were completed?
- What is the overall profit percentage?
- How is performance changing from month to month?
- Which product categories are performing better?
- How does performance vary across countries?
- How are individual salespersons performing?
- What percentage of shipments fall under LBS?

### Key Performance Indicators

The dashboard contains the following KPI cards:

- Total Sales
- Total Boxes
- Total Shipments
- Total Cost
- Total Profit
- Profit %
- LBS %

The KPI cards also show the latest month's performance and Month-over-Month percentage change.

### DAX Measures Used

I created the following DAX measures for KPI calculations and performance analysis:

- Total Sales
- Total Boxes
- Total Shipments
- Total Cost
- Total Profit
- Profit %
- LBS Count
- LBS %
- Latest Date
- Total Sales Latest Month
- Month-over-Month Sales Change %
- Month-over-Month Boxes Change %
- Month-over-Month Shipments Change %
- Month-over-Month Costs Change %
- Month-over-Month Profit Change %
- Latest Month-over-Month Sales Change %

These measures are used to calculate overall performance, profitability, shipment analysis, latest-month values, and monthly growth or decline.

### Dynamic Measure Selector

I created a dynamic measure selector that allows users to switch between:

- Sales
- Boxes
- Shipments
- Cost
- Profit

Based on the selected metric, the line chart automatically changes to show the monthly trend for that measure. This avoids creating separate charts for every metric and makes the dashboard more interactive.

### Product Category Filter

The dashboard includes a product category slicer with the following categories:

- Bars
- Bites
- Other

Users can select a category to filter the entire dashboard and analyze the performance of that particular product category.

### Country Filter

The dashboard includes country filters for:

- Australia
- Canada
- India
- New Zealand
- UK
- USA

This allows users to compare business performance across different countries.

### Shipment Analysis

The dashboard contains a shipment analysis chart that shows the distribution of shipments based on the number of boxes.

This helps to understand how shipments are distributed across different box quantities.

### Profit and LBS Analysis

I used gauge charts to display Profit % and LBS %.

The Profit % gauge shows the overall profit margin, while the LBS % gauge shows the percentage of LBS shipments compared with total shipments.

### Salesperson Performance Analysis

The dashboard contains a detailed salesperson performance table showing:

- Salesperson name
- Sales
- Profit
- Profit %
- LBS %

I also used conditional formatting to make salesperson performance easier to compare visually.

### Key Insights

The dashboard helps analyze:

- Overall sales, costs, profit, boxes, and shipments.
- Monthly performance trends.
- Month-over-Month growth or decline.
- Product category performance.
- Country-level performance.
- Overall profit margin.
- LBS shipment percentage.
- Individual salesperson performance.

### What I Learned

Through this project, I improved my practical understanding of:

- Importing data into Power BI.
- Cleaning and transforming data using Power Query.
- Creating relationships between tables.
- Building a data model.
- Creating DAX measures.
- Using variables in DAX.
- Creating Month-over-Month calculations.
- Creating KPI cards.
- Using field parameters for dynamic measure selection.
- Creating interactive slicers.
- Using gauge charts.
- Applying conditional formatting.
- Designing an interactive Power BI dashboard.

---

## 6. Screenshots / Demo

Below is a preview of the Chocolate Sales Dashboard created in Power BI.
[Chocolate Sales Dashboard](Chocolate-Sales-Dashboard.png)

The Power BI template file for this project is available here:
https://github.com/shaktico/Chocolate-Sales-Dashboard/blob/main/Chocolate-Sales-Dashboard.png.jpeg

---

## Project Files

This repository contains:

- Power BI Dashboard Template (.pbit)
- Chocolate Sales Dataset (.xlsx)
- Dashboard Screenshot (.png)
- README.md

---

## Project Purpose

This project was created for learning and portfolio purposes to improve and demonstrate my practical knowledge of Power BI, Power Query, data modeling, DAX, and interactive dashboard development.

