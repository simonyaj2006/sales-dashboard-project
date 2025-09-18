# Sales and Customer Dashboard Tableau Project

Welcome to the **Sales and Customer Dashboard Tableau Project** repository!  
This project demonstrates how to develop a complete end-to-end analytics solution — from raw data transformation to building interactive dashboards in Tableau. Designed as a portfolio project, it reflects industry practices in **data analytics**, **dashboard design**, and **business intelligence**.

---

## Data Architecture

While Tableau is the primary tool used for visualization, this project still follows a structured pipeline approach:

1. **Source Data**: Sales and customer data provided in CSV format (order history, customer demographics, product info).
2. **Data Cleaning**: Performed using Excel and/or SQL — removing nulls, correcting data types, and standardizing categories.
3. **Data Modeling**: Creating relationships between customers, products, and sales (fact and dimension tables).
4. **Visualization Layer**: Tableau dashboards presenting key KPIs and business trends for sales and customer performance.

---

## Project Overview

This project focuses on **retail sales analysis** and **customer segmentation** to help business stakeholders understand performance trends and improve strategic decisions.

This project involves:

1. **Data Preparation**: Cleaning and transforming sales and customer datasets.
2. **Data Modeling**: Structuring the data for optimal use in Tableau.
3. **Dashboard Design**: Creating a dynamic sales and customer performance dashboard in Tableau.
4. **Insights Generation**: Highlighting actionable analytics around **revenue**, **repeat customers**, **top products**, and **sales trends**.

This repository is a great resource for professionals and students looking to demonstrate expertise in:
- Data Cleaning (Excel / SQL)
- Business Intelligence Tools (Tableau)
- Customer Analytics & Sales Metrics
- Data Storytelling

---

## Important Tools & Technologies:

- **Tableau Public** – For building dashboards and data storytelling  
- **Excel / SQL** – For preparing and cleaning datasets  
- **DrawIO / Whimsical** – For data flow diagrams and dashboard layout mockups  
- **GitHub** – For version control and project showcase

---

## User Story - Sales & Customer Dashboard

## Introduction

This user story outlines the specifications for building two dashboards using Tableau to help stakeholders, including sales managers and executives, to analyze sales performance and customer data. 

## Sales Dashboard | Requirements

### Dashboard Purpose
The purpose of the sales dashboard is to present an overview of the sales metrics and trends in order to analyze year-over-year sales performance and understand sales trends. 

### Key Requirements

#### KPI Overview
Display a summary of total sales, profits, and  quantity for the current year and the previous year.

#### Sales Trends
- Present the  data for  each KPI on a monthly basis for both the current year and the previous year.
- Identify months with the highest and lowest sales and make them easy to recognize

#### Production Subcategory Comparison
-  Compare sales performance by different product subcategories for the current year and the previous year.
-  Include a comparison of sales and profit.

#### Weekly Trends for Sales & Profit
- Present weekly sales and profit data for the current year.
- Display the average weekly values.
- Highlight weeks that are above and below the average to draw attention to sales & profit performance.

## Customer Dashboard | Requirements 

### Dashboard Purpose
The customer dashboard aims to provide an overview of customer data, trends, and behaviors. It will help marketing teams and management to understand customer segments and improve customer satisfaction.

### Key Requirements 

#### KPI Overview
Display a summary of the total number of customers, total sales per customer, and total number of orders for the current year and the previous year.

#### Customer Trends
- Present the data for each KPI on a monthly basis for both the current year and the previous year.
- Identify months with the highest and lowest sales and make them easy to recognize.

#### Customer Distribution by Number of Orders
Represent the distribution of customers based on the number of orders they have placed to provide insights into customer behavior, loyalty, and engagement. 

#### Top 10 Customers By Profit
- Present the top 10 customers who have generated the highest profits for the company.
- Show additional information like rank, number of orders, current sales, current profit, and the last order date.

### Design & Interactivity Requirements

#### Dashboard Dynamic
- The Dashboard should allow users to check historical data by offering them the flexibility to select any desired year.
- Provide users with the ability to navigate between the dashboards easily.
- Make the charts and graphs interactive, enabling users to filter data using the charts.

#### data Filters
Allow users to filter data by product information like category and subcategory, and by location information like region, state, and city.

---

## Repository Structure

```
sales-customer-dashboard/
│
├── datasets/                                      # Source CSV files (customers, location, orders, and products)
│   ├── Customers.csv
│   ├── Location.csv
│   ├── Orders.csv
│   └── Products.csv
│
├── images/                                        # Images used for dashboard
│
├── mockup&project_phases/                         # Documentation & design diagrams
│   ├── Dashboard Mockup2.drawio.png               # Dashboard Mockup for sales and customers
│   ├── Dashboard Mockup.drawio.png                # Sales dashboard mockup with filters
│   ├── Step 1 Analyse Requirements.drawio.png     # Analyse requirements process
│   ├── Step 2 Build Data Source.drawio.png        # Build data  source process
│   ├── Step 3 Build Charts.drawio.png             # Building charts process
│   ├── Step 4 Build Dashboard.drawio.png          # Build dashboard process
│   └── Tableau Project Steps.drawio.png           # How all the steps will build the tableau project
│
├── LICENSE                                        # License information
├── README.md                                      # Project overview and instructions
└── Sales & Customer Dashboards.twbx               # Tableau workbook file
``` 

---

## Deliverables

- **Tableau Dashboard**: A comprehensive, interactive dashboard covering sales performance and customer behavior.
- **Insights Report**: A summary of key takeaways and patterns discovered through data visualization.
- **Data Flow Diagram**: Visual overview of the data transformation process from raw input to final dashboard.

---

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

---

##  About Me

Hi there! I'm **Simon Yang**. I’m a College Student on a mission to practice my skills and learn more about working with data.

Let's stay in touch! Feel free to connect with me on the following platforms:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/simon-yang-a5211535a/)
[![Handshake](https://img.shields.io/badge/Handshake-3DDC84?style=for-the-badge&logo=handshake&logoColor=white)](https://app.joinhandshake.com/profiles/ztjfa4)
