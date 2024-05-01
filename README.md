# Tableau User Story | Sales Performance

## Introduction
This user story outlines the specifications for two dashboards using Tableau to help stakeholders, including sales managers and executives, analyze sales performance and customer data.

### Technologies Used
- SQL: Structured Query Language was utilized for data extraction, transformation, and loading (ETL) processes.
- Tableau: The primary tool for data visualization and dashboard creation, enabling interactive exploration of sales metrics and customer data.

## Sales Dashboard | 

### Dashboard Purpose
The purpose of the sales dashboard is to present an overview of sales metrics and trends, facilitating the analysis of year-over-year sales performance and understanding sales trends.

### Key Requirements

1. **KPI Overview**
   - Display a summary of total sales, profits, and quantity for the current year and the previous year.

2. **Sales Trends**
   - Present the data for each KPI on a monthly basis for both the current year and the previous year.
   - Identify months with the highest and lowest sales and make them easy to recognize.

3. **Product Subcategory Comparison**
   - Compare sales performance by different product subcategories for the current year and the previous year.
   - Include a comparison of sales with profit.

4. **Weekly Trends for Sales & Profit**
   - Present weekly sales and profit data for the current year.
   - Display the average weekly values.
   - Highlight weeks that are above and below the average to draw attention to sales & profit performance.

## Customer Dashboard | 

### Dashboard Purpose
The customer dashboard aims to provide an overview of customer data, trends, and behaviors, assisting marketing teams and management in understanding customer segments and improving customer satisfaction.

### Key Requirements

1. **KPI Overview**
   - Display a summary of the total number of customers, total sales per customer, and the total number of orders for the current year and the previous year.

2. **Customer Trends**
   - Present the data for each KPI on a monthly basis for both the current year and the previous year.
   - Identify months with the highest and lowest sales and make them easy to recognize.

3. **Customer Distribution by Number of Orders**
   - Represent the distribution of customers based on the number of orders they have placed to provide insights into customer behavior, loyalty, and engagement.

4. **Top 10 Customers By Profit**
   - Present the top 10 customers who have generated the highest profits for the company.
   - Show additional information like rank, the number of orders, current sales, current profit, and the last order date.

### Design & Interactivity Requirements

1. **Dashboard Dynamic**
   - Allow users to check historical data by offering them the flexibility to select any desired year.
   - Provide users with the ability to navigate between the dashboards easily.
   - Make the charts and graphs interactive, enabling users to filter data using the charts.

2. **Data Filters**
   - Allow users to filter data by product information like category and subcategory and by location information like region, state, and city.

This project integrates SQL for data processing and Tableau for visualization to deliver comprehensive sales performance insights and customer analytics. With interactive dashboards and dynamic filtering capabilities, stakeholders can gain actionable insights to drive strategic decisions and improve business outcomes.
