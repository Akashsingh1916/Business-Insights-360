# AtliQ Business Insights 360

## Project Overview

AltiQ Hardware, a fast-growing company expanding globally, specializes in selling computers and accessories through three main channels: retailers, direct sales, and distributors.

Despite its growth, the company faced unexpected losses after opening a store in America. These setbacks were identified through surveys, intuition, and basic Excel analysis. With competitors boasting robust analytics teams, AltiQ Hardware recognizes the urgent need to develop its analytics capabilities to thrive in the industry.

To surpass competitors and enable data-driven decision-making, the company has decided to implement Power BI for analytics. This project aims to provide stakeholders with insights into finance, sales, marketing, and supply chain, ensuring informed decisions at all levels.

I worked on this project by following the Codebasics PowerBi Course, 

Here is my report link - https://app.powerbi.com/view?r=eyJrIjoiMzUwMTU5ZDctODRhNi00ZjA1LWEzYWItOWMwMGFkNTFiZjg1IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9


Here is my presentation link - https://www.linkedin.com/posts/akash-singh-dataanalyst_datafam-connections-dataanalytics-activity-7185268759052353536-j3zq?utm_source=share&utm_medium=member_desktop


## Datasets:

Before diving into analysis, understanding the datasets is crucial. The datasets consist of two tables:

**Dimension table:** Static data like customer and product details.

**Fact table:** Transaction data.

gdb041:
* dim_customer
* dim_market
* dim_product
* fact_forecast_monthly - This table is used to forecast the customer’s need in advance, which can help in Higher customer satisfaction and reduced cost in warehouses for storage purposes
* fact_sales_monthly - This table is more or less is same as the fact_forecast_monthly table, but the last column has the value of the sold quantity instead of the forecast value.

gdb056:
* freight_cost
* gross_price
* manufacturing_cost
* Pre_invoice_dedutions
* Post_invoice_deductions


### Importing Data and Data Modeling:

Data was imported from MySQL into Power BI, and a data model was created after cleaning and transforming the data. But why data modeling is very important for analysis right??

If you break down the whole work of a data analyst then you will come up with 4 steps of work 

✅ Data Extract ---> ✅ Data Cleaning---> ✅ Data Modelling ---> ✅ Data Analysis

See you can't skip the 3rd step if you want to reach the last step (analysis part), 
Data modeling is essential because it lays the foundation for reports. All visuals are built upon the data model, and poor modeling can affect report performance.

In this project, we have followed the Snowflake schema data modeling method. 


![data model](https://github.com/Akashsingh1916/Business-Insights-360/assets/146354971/2285afcc-e8f4-4b94-abae-ea1d89e6cba9)


## Power BI Dashboard Overview:

The dashboard comprises six pages-->

### Home Page: A landing page with buttons to navigate to different pages.

![home page](https://github.com/Akashsingh1916/Business-Insights-360/assets/146354971/6e2f5d22-f8e6-45a5-816f-bf494b123766)


### Finance Page: Focuses on improving financial planning, budgeting processes, and cost control. Includes Profit and Loss statements, Top and Bottom Products and Customers by Net Sales, and more.

![finance page](https://github.com/Akashsingh1916/Business-Insights-360/assets/146354971/9a5fed55-40fa-471a-a9ef-762870c0bc7a)


### Sales Page: Aims to increase sales revenue and market share. Features Customer performance by Net Sales, Gross Margin, Gross Margin %, and more.

![sales page](https://github.com/Akashsingh1916/Business-Insights-360/assets/146354971/4a1ca097-8c59-4c4d-b5bf-7e9fa5ab3aef)


### Marketing Page: Aims to increase brand visibility and customer engagement. Provides Segment Performance by Gross Margin% and Net Profit%, and more.

![marketing page](https://github.com/Akashsingh1916/Business-Insights-360/assets/146354971/822ac56d-6d9d-494e-88fd-e81ec23df0a2)


### Supply Chain Page: Aims to optimize inventory management and enhance supplier relationships for cost savings. Includes details about Forecast Accuracy, Net error, and more.

![supply chain](https://github.com/Akashsingh1916/Business-Insights-360/assets/146354971/2ac6c4f5-2b34-45f4-94fe-a0cea0b3627c)


### Executive Page: Provides an overview of the organization's performance for top management. Includes Net Sales, Gross Margin%, Net Profit%, Revenue Contribution by channel, Top 5 Customer and Product, Sub Region performance, and more.

![executive page](https://github.com/Akashsingh1916/Business-Insights-360/assets/146354971/cff56379-243d-4e2e-96e5-e21e1624de3f)


## Skills Learned:

During the Codebasics Bootcamp course and this project, I learned:
Power BI fundamentals,
Calculated columns and DAX measures,
Data Modeling, Data Cleaning, Bookmarks, Conditional formatting,
Custom Tooltip usage, Dynamic Title Creation, and more.

### Tools Used:

SQL, Power BI Desktop, DAX language, DAX studio (to reduce file size), Project Charter file.

### Business Terms Learned:

Gross Margin, Gross Margin %, Gross Sales, Gross Sales %, Pre-invoice deductions, Post-invoice deductions, Net sales, Net Invoice Sales, Net Profit, Net Profit %, COGS (cost of goods sold), YTG (year to go), YTD (year to date), Direct, Retailer, Consumer, Distributors.

## Conclusion :

This report empowers decision-making based on data, addressing numerous "why" questions across various scenarios. It serves as a tool to extract insights and guide actions, ultimately aiming to enhance AltiQ's profitability through data-driven decisions.
