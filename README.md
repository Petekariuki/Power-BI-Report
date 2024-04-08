# AdventureWorks Dashboard

![Dashboard Gif](AdventureWorksDemo.gif)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Design](#design)
- [Dashboard](#dashboard)
  - [Executive Summary View](#executive-summary-view)
  - [Map View](#map-view)
  - [Product Detail View](#product-detail-view)
  - [Customer Detail View](#customer-detail-view)
  - [Custom Additions](#custom-additions)


## Introduction

The goal of this project was to create a business intelligence dashboard for AdventureWorks, a fictional cycling equipment company, using Power BI. The purpose for doing this was to demonstrate my ability
to build insightful, accurate, and aesthetic reports in Power BI.


## Features

- Analyze product level trends
- Track key performance indicators (KPIs) related to revenue, sales, returns, and profit
- Compare sales performance across different regions
- Create aesthetic and insightful pages directed at a specific target audience (exec vs manager vs analyst)
- Identify high-value customers
- Utilize latest AI visuals such as decomposition tree and anomaly detection to improve data insights and reduce errors
- Provide dense layers of analysis while maintaining a simple overall presentation for executive level end-users

## Design

1. Connect and transform raw data
2. Build a relational data model
3. Create calculations and measures using DAX
4. Design an interactive and dynamic dashboard

## Dashboard

### Executive Summary View

- High-level KPI tracking for revenue, profit, orders, and return rates
- Target KPIs for month-to-month performance vs expectations
- Top products performance with regard to category
- page level filtering for detailed analysis
- drill-through feature to populate product detail view

### Map View

- Scaled map view of total orders by location
- Slicer for quick filters by region

### Product Detail View

- detailed, per-product performance created by drill-through
- Price adjustment metric for performing "what-if" analysis
- Product metric for trending specific product data such as orders, revenue, profit, returns, and return %

### Customer Detail View

- Overall customer and per-customer analysis

### Custom Additions

- Custom tooltip UI for on-demand metrics
- popup filter pane for year and geography
- sidebar navigation for improved user-experience
