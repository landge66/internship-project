# Amazon Sales Report Analysis
Project Overview
This project analyzes an Amazon Sales Report dataset with the aim of uncovering insights such as:

* Sales Trends: Understanding the variation in sales over time.
* Product Popularity: Identifying best-selling products and categories.
* Fulfillment Methods: Analyzing order fulfillment performance.
* Customer Segmentation: Grouping customers based on buying behavior.
* Geographical Sales Distribution: Evaluating which locations drive the most sales.
# Data Structure 
the dataset contains the following columns:
* Date: The date of the sale in mm-dd-yyyy format.
* Amount: The sale amount for each transaction.
* Order ID: Unique identifier for each order.
* Status: Status of each order (e.g., shipped, canceled).
* Fulfilment: The method of order fulfillment.
* Sales Channel: Platform through which the sale was made.
* Category: Product category.
* Size: Product size information.
* Courier Status: Status of delivery by courier.
* Qty: Quantity sold in each transaction.
* currency: Currency in which the sale amount is reported.
* ship-city: The city where the product was shipped.
* ship-state: The state of the shipping destination.
* ship-postal-code: Postal code of the shipping destination.
* ship-country: Country to which the product was shipped.
* B2B: Indicator of whether the transaction was B2B.
* fulfilled-by: Entity responsible for fulfilling the order (e.g., Amazon, third-party).
# Missing Data and Cleaning Decisions
* Columns like new and pendings were dropped as they were empty.
* Amount: Missing values were set to 0 to reflect transactions with no recorded sale amount.
* Currency and Fulfilled-by: Missing values were set to 'Unknown'.
* Geographical Data (ship-city, ship-state, ship-country): Missing values were also set to 'Unknown' to maintain data consistency.
* Date: Missing dates were filled based on the observed pattern, keeping the month and year constant and decrementing the day where necessary.

# data Analysis and Insights
Sales Trend Analysis
* Line charts to show the total sales(amount) over time
* Insights into peak sale periods,average sales per day,and general sales trends.
# Fulfillment and Sales Channel Analysis
* Analysis of different fulfillment methods and their efficiency.
* Breakdown of sales by fulfillment method and sales channel to gauge performance.

# Product and Category Analysis
* Top-selling products and categories identified based on sales volume and revenue.
* Insights into customer preferences across product categories.

# Geographical Analysis
* Sales distribution across cities, states, and countries.
* Identification of high-performing regions and potential areas for expansion

# Visualizations

visualizations include
* Sales Over Time: Line chart showing daily/weekly sales.
* Order Status Distribution: Bar chart of various order statuses.
* Fulfillment Method Distribution: Pie chart or bar chart for fulfillment types.
* Top Product Categories: Bar chart showing best-selling product categories.
* Geographical Sales Distribution: Heat map showing sales concentration in different regions.

# Results and Findings
Summarize the key takeaways from the analysis here, such as:

* High Sales Periods: The months with the highest sales.
* Popular Categories: Categories that perform well across various metrics.
* Fulfillment Insights: Performance comparison between Amazon fulfillment and third-party fulfillment.

 # Troubleshooting
* Date Errors: Ensure dates are in the correct format and fill missing values as described in the cleaning steps.
* Missing Columns: Verify the dataset structure if certain columns are missing from the analysis output.
* Visualizations Not Displaying: Check that all libraries (e.g., Matplotlib, Seaborn) are installed and that plots are correctly generated. 
  

  
