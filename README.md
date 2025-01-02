# Topic: Lita Analysis

### Project Overview: Sales Analysis and Visualization for Lita

- This project analyzes sales data from the Lita dataset to identify key business insights. 
- The analysis is performed using SQL queries and Python libraries (pandas, matplotlib, seaborn) for data manipulation and visualization.


### Data Understanding

The key data points used for analysis include:
- OrderID: Unique identifier for each order.
- Customer Id: Identifier for each customer.
- Product: The name of the product.
- Region: The geographical region of the sale.
- OrderDate: The date of the order.
- Quantity: The number of units sold.
- UnitPrice: The price of a single unit.

### Data Sources:
- The data source for the analysis is an Excel file named "LITA Capstone Dataset 1.xlsx"

### Key Objectives:

1. Sales Performance:
- Calculate total sales by product category and region.
- Identify the highest-selling product and its total sales value.
- Analyze monthly sales totals for the current year (2024).
- Calculate total revenue per product.
- Calculate the percentage of total sales contributed by each region.
- Identify products with no sales in the last quarter.
- Calculate the sum total of sales for the current year.

### Tools

- The analysis involves several queries performed against the 'Lita' table in the SQLite database,
  along with some data manipulation and visualization using pandas, matplotlib, seaborn and plotly.

###  EDA (Exploratory Data Analysis)
 is performed on the dataset using visualization techniques to gain insights about sales trends.  These visualizations include:
- Bar plots: Showing sales by region, and quantity by region
- Pie charts: Showing regional breakdown of sales and product breakdown
- Count plots: Showing the distribution of products across regions and unit prices.
- Relplot (scatter plot matrix): Showing the relationship between regions, unit prices, and products.

### Recommendation

1. Targeted Regional Marketing:
The analysis reveals varying product demand across regions.  For instance, "Jackets" might be a primary need in the North, but less so elsewhere.  Implement targeted marketing campaigns in each region, highlighting products relevant to local needs and climate.  This includes promotions, advertising, and localized product displays.

2. Promotional Pricing Strategies:
Introduce tiered pricing or promotions for products less popular in certain regions.  "Second-class" products (perhaps variations or older models) could be offered at discounted prices to expand market share in regions where they aren't primary needs. This incentivizes trial and adoption, increasing sales and visibility in the long run.  Simultaneously offer these discounted options in primary regions to target price-sensitive customers.

3. Inventory Optimization:
Based on regional sales data, adjust inventory levels to ensure sufficient stock of high-demand products in specific regions while minimizing surplus of low-demand products.  This can improve sales efficiency and reduce storage costs.

4. Customer Segmentation:
Analyze customer purchasing behavior to identify segments with distinct needs and preferences. This allows for more tailored marketing efforts, product recommendations, and loyalty programs.  Combine regional data with customer segmentation to create highly targeted promotions.

5. Data-Driven Decision Making:
Continue to regularly monitor sales data, product performance, and regional trends.  Use dashboards and visualizations to identify emerging patterns and quickly adjust strategies. This ensures agile responses to changing market conditions and customer preferences.

6. Product Diversification (Consideration):
Explore expanding the product line to include items that better cater to the specific needs of underperforming regions.   This may increase sales and expand the customer base in those regions.

7. Enhance Data Collection:
Consider expanding data collection to include additional customer demographics, purchase motivations, and feedback.  This will allow for deeper insights into customer preferences and refined marketing strategies.
