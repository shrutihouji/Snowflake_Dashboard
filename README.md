# Cross Shopping Insights- Restuarants

I’ve created a simple dashboard using Snowsight. I got data from the Snowflake Marketplace, created a virtual warehouse, database, and tables, and loaded the data into the Snowflake table. Using Snowflake worksheets, I wrote SQL queries to get the following insights from different charts:
1. Stacked Bar chart for Customer Spend by Location: This chart shows the postal code with the highest number of customers, which is postal code 10036 at Hard Rock Cafe.
2. Stacked Bar chart Number of Customers by Location: This chart can be used to see that postal code 10036 has the second-largest number of customers.
3. Online Spend by Location: This chart allows us to compare with the first graph to see which postal code has the highest online spend. It also shows that postal code 10036 has the second-largest online spend, indicating that most customers from that area enjoy ordering food online.
4. Heat Grid: This chart shows the median spending in different areas with postal codes 10003, 10019, and 10036. It indicates that Hard Rock Cafe has a median spend of $60, while RareBurger has a median spend of $16. This suggests that even though there are many customers, they spend less at specific restaurants. Various factors such as price adjustments, discounts, and location can influence customer spending.
5. Line Graph: This chart shows the daily sales in different states in the US.
