## E-Commerce Sales and Revenue Tableau Dashboard

### Dashboard Link : https://public.tableau.com/app/profile/jini.xu/viz/E-CommerceSalesandRevenue/E-commerceSalesandRevenue?publish=yes

### Insights
1. Analyze sales trends over time to identify seasonal patterns or growth opportunities.
2. Explore the popularity of different product categories across regions.
3. Identify top-selling products within each category to optimize inventory and marketing strategies.
4. Evaluate the performance of specific products or categories in different regions to tailor marketing campaigns accordingly.

### Data
The dataset provides a comprehensive overview of online sales transactions across different product categories. Each row represents a single transaction with detailed information such as the order ID, date, category, product name, quantity sold, unit price, total price, region, and payment method. 

Variables:
- Order ID: Unique identifier for each sales order.
- Date: Date of the sales transaction.
- Category: Broad category of the product sold (e.g., Electronics, Home Appliances, Clothing, Books, Beauty Products, Sports).
- Product Name: Specific name or model of the product sold.
- Quantity: Number of units of the product sold in the transaction.
- Unit Price: Price of one unit of the product.
- Total Price: Total revenue generated from the sales transaction (Quantity * Unit Price).
- Region: Geographic region where the transaction occurred (e.g., North America, Europe, Asia).
- Payment Method: Method used for payment (e.g., Credit Card, PayPal, Debit Card).

Calculated Variables:
- Percentage of Revenue: Revenue/Total Revenue
- Percentage of Units Sold: Units Sold/Total Units Sold

### Technologies Used
- Tableau
- Excel

### Analysis and Summary

There are 240 online sales transactions and 9 variables that include order ID, date, category, product name, quantity sold, unit price, total price, region, and payment method. The two calculated variables are added that are percentage of revenue and percentage of units sold. The variable category contains 5 categories: Electronics, Home Appliances, Clothing, Books, Beauty Products, and Sports; and variable region contains 3 regions: North America, Europe, and Asia. 

The *Weekly Sales and Revenue* plot showed the weekly sales and revenue for all categories and regions and both sales and revenue had a downward trend. The *Monthly Revenue of Categories* plot visulized the decreasing pattern of total revenue.

The *Monthly Revenue of Categories* plot indicated the monthly revenue of each category from January to August. Electronics had the highest revenue and Books and Beauty Products have relative low revenue. Through January to August in 2024, Electronics had 43.4% total revenue and the second largest product type was Home Appliances with 23.1%. Books had the lowest revenue with 2.3%. 

According to plots *Total Revenue of Regions in Percentage* and *Quaterly Revenue of Categories*, North America shared the largest market among 3 regions with 45.7% of total revenue in the first 8 months and it's main sales product type were Electronics and Books, and Asia and Europe had similar market shares. The main sales product type in Asia were Clothing and Sports, and for Europe were Home Appliances and Beauty Products. To keep or increase the market share, each region would be proper to marketing on the most popular product types. 

By selecting the time interval in *Filters* in the dashboard, the user could find out the Top 1 products by sales of each category and increase the inventory for the future if needed.

### Discussion

The sales and revenue data is not available after August 2024 yet so the conclusions above may need to be adjusted when the newest data releases. 
