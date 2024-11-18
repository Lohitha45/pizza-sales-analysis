# Pizza-Sales-Analysis
This project analyzes pizza sales data using Excel and SQL. It includes data cleaning, creating pivot tables and dashboards in Excel, and performing SQL queries to analyze KPIs and trends. The goal is to identify top-selling pizzas, uncover sales trends, and optimize sales strategies.
### Table of Contents
### Data Sources
The dataset used for this analysis is "Pizza_Sales_Data.csv" file, containing detailed information . You can download from hear [Pizza_Sales_Data.csv](https://github.com/Lohitha45/pizza-sales-analysis/blob/main/Pizza_Sales_Data%20.csv)

### PROBLEM STATEMENT

#### KPI'S REQUIREMENT:

We need to analyze key indicators for our pizza sales data to gain insights into our business performance. Specifically, we want to calculate the following metrics:

<b>1. Total Revenue:</b> The sum of the total price of all pizza orders.

<b>2. Average Order Value:</b> The average amount spent per order, calculated by dividing the total revenue by the total number of orders.

<b>3. Total Pizzas Sold:</b> The sum of the quantities of all pizzas sold.

<b>4. Total Orders:</b> The total number of orders placed.

<b>5. Average Pizzas Per Order:</b> The average number of pizzas sold per order, calculated by dividing the total number of pizzas sold by the total number of orders.
   
#### CHARTS REQUIREMENT:

   We would like to visualize various aspects of our pizza sales data to gain insights and understand key trends. We have identified the following requirements for creating charts:

<b>1.Daily Trend for Total Orders:</b>

Create a bar chart that displays the daily trend of total orders over a specific time period. This chart will help us identify any patterns or fluctuations in order volumes on a daily basis.

<b>2.Hourly Trend for Total Orders:</b>

Create a line chart that illustrates the hourly trend of total orders throughout the day. This chart will allow us to identify peak hours or periods of high order activity.

<b>3.Percentage of Sales by Pizza Category:</b>

Create a pie chart that shows the distribution of sales across different pizza categories. This chart will provide insights into the popularity of various pizza categories and their contribution to overall sales.
CHARTS REQUIREMENT

<b>4.Percentage of Sales by Pizza Size:</b>

Generate a pie chart that represents the percentage of sales attributed to different pizza sizes. This chart will help us understand customer preferences for pizza sizes and their impact on sales.

<b>5.Total Pizzas Sold by Pizza Category:</b>

Create a funnel chart that presents the total number of pizzas sold for each pizza category. This chart will allow us to compare the sales performance of different pizza categories.

<b>6.Top 5 Best Sellers by Total Pizzas Sold:</b>

Create a bar chart highlighting the top 5 best-selling pizzas based on the total number of pizzas sold.

This chart will help us identify the most popular pizza options.

<b>7.Bottom 5 Worst Sellers by Total Pizzas Sold:</b>

Create a bar chart showcasing the bottom 5 worst-selling pizzas based on the total number of pizzas sold. This chart will enable us to identify underperforming or less popular pizza options.

### Data Cleaning and Processing
- <b>Steps Taken:</b>
   1. Identified inconsistent entries in the <b>"pizza_size"</b> column (S, M, L, XL, XXL).
   2. Extracted the day of the week from the <b>"order_date"</b> column to analyze sales trends based on weekdays.
- <b>Issues Encountered and Resolutions:</b>
  - The values in the pizza_size column (S, M, L, XL, XXL) were updated to more descriptive names for better clarity:
<b>S → Regular,
M → Medium,
L → Large,
XL → X-Large,
XXL → XX-Large.</b>
  - Added a new column named <b>"order_day"</b> that represents the day of the week (e.g., Monday, Tuesday, etc.).
### SQL Queries for Data Analysis
SQL queries were used to analyze pizza sales data, focusing on key performance indicators (KPIs) like total sales, top-selling pizzas, and sales trends by day and region. These queries helped address the problem statement and uncover valuable insights for optimizing sales strategies. For the complete list of SQL queries, click [here]().
### Data Analysis
### Result and Findings
### Recomendations
### Limitations
### References
