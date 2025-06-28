# Pizza-sales-dashboard
Pizza Sales Project

PROBLEM STATEMENT

A popular pizza store wants to optimize its sales and marketing strategies to increase revenue and customer satisfaction.To achieve this, the company needs to analyze its sales data to uncover insights into customer preferences, sales trends, and product performance.The goal is to uncover insights from the data and develop actionable recommendations to drive business growth. The Client divided the problem statement into two sections;

KPI’s requirement
We need to analyze the key indicators for our Pizza sales data to gain insights into our business performance, we want to calculate the following metrics :

•	Total Revenue
•	Total Orders
•	Average Order Value
•	Total Pizzas Sold
•	Average Pizzas Per Order
Charts requirement We would like to visualize various aspects of our Pizza sales data to gain insights and understand key trends. We have identified the following requirements for creating charts :

•	Daily trend for Total Orders
•	Monthly trend for Total Orders
•	Percentage of sales by pizza Category
•	Percentage of sales by pizza Size
•	Total pizzas sold by pizza Category
•	Top 5 best selling & Bottom 5 worst selling pizzas

OBJECTIVES
Conduct a comprehensive sales performance analysis for a pizza store using SQL queries and visualize the findings using Power BI. The objective is to gain insights into sales trends, revenue distribution, and top performing products to inform strategic decision-making and optimize sales strategies.

Project Components
1. Data Acquisition
The project begins with the acquisition of raw sales data. This data may include information such as customer orders, product details, order dates, and transaction amounts. Data can be obtained from various sources, including databases, CSV files, or other data storage systems.

2. Data Transformation with SQL
SQL (Structured Query Language) is used to clean, filter, and transform the raw data into a format suitable for analysis. This may involve tasks such as joining tables, aggregating data, handling missing values, and creating new calculated fields.

3. Data Analysis
   
In Power Query Editor,

• To facilitate easy dashboard creation, merged the four datasets into one unified dataset, enabling streamlined analysis and visualization. This consolidated dataset enhances data coherence and simplifies the dashboard creation process.

• Transformed the abbreviations in the "size" column into descriptive names, enhancing comprehension and usability of the dataset. This modification improves clarity and facilitates easier interpretation of the pizza sizes.

• Implemented a custom column named "Total_price" by multiplying the "quantity" with the "unit_price," enhancing the dataset's clarity and facilitating straightforward calculation of total prices for each item.

• Implemented DAX measures to calculate key metrics such as Total Revenue and Average Order Value , providing valuable insights into sales performance. These measures enable stakeholders to make informed decisions based on accurate and easily accessible financial information.

4. BUILDING DASHBOARD

Developed two dynamic dashboards in Power BI to cater to distinct business needs:

• The first dashboard features essential Key Performance Indicators (KPIs), including Total Revenue, Total Orders, Average Order Value, and Total pizzas sold, alongside insightful charts displaying busiest days and times, as well as sales performance trends over specific time periods. This dashboard empowers stakeholders with actionable insights to optimize operational efficiency and strategic decision-making.

• The second dashboard highlights best and worst-selling pizzas through visually engaging charts and tables, providing a comprehensive overview of pizza sales performance. By leveraging intuitive visuals and comparative analysis, this dashboard facilitates informed product management strategies and enables targeted marketing efforts to drive sales growth.

Check out the Pizza Sales Dashboard
Snapshots of Dashboard

![Screenshot 2025-06-26 194004](https://github.com/user-attachments/assets/59989d87-0ad9-41f3-a8c7-36c093fa7550)

![Screenshot 2025-06-28 084237](https://github.com/user-attachments/assets/259e016b-63cc-4aba-9efe-020822deda97)

5. INSIGHTS
   
• FRIDAYS, THURSDAYS and SATURDAYS have the highest sales volume, comprising about 47% of total weekly sales, while Sundays and Tuesdays are typically slower days with lower sales.

• The busiest hours for pizza orders are between 12:00 PM to 1:00 PM and 5:00 PM to 6:00 PM, indicating high demand during lunch time and evening time.

• Peak sales occur during the SECOND QUARTER of the year and JULY being the month with highest sale.

• LARGE-sized pizzas are the most popular choice among customers, representing about 46% of total sales, followed by MEDIUM (30%) and SMALL (22%) sizes.

• Percentage share of total sales by all four Pizza Categories are almost same with CLASSIC category being the highest followed by SUPREME category.

• Among pizzas, THAI CHICKEN PIZZA contributes to maximum sales while CLASSIC DELUXE PIZZA are the most ordered one among the customers and BRIE CARRE PIZZA holds the position of least favoured pizza.

Dependencies
SQL database or data source
Power BI Desktop
