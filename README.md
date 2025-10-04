### Walmart_Sales_Data_Analysis_with-SQL
About
We are analysing Walmart's sales data to identify high-performing branches and products, analyze the sales patterns of various products, and understand customer behavior. The primary objective is to enhance and optimize sales strategies. The dataset utilized in this project is sourced from the Kaggle Walmart Sales Forecasting Competition.

Purposes of the Project
The main goal of this project is to calculate KPI(Key Performance Indices) in walmart sales and to evaluate sales data,exploring the various factors that influence sales across different branches..

About Data
This project's data was obtained from the Kaggle Walmart Sales Forecasting Competition and it encompasses sales transactions from three Walmart branches situated in Mandalay, Yangon, and Naypyitaw, respectively. The data contains 17 columns and 1000 rows:

Data set Overview
invoice_id	Unique identifier for each sales transaction
branch	Store branch where the sale occurred (e.g., A, B, C).
city	The city where the branch is located
customer_type	Whether the customer is a Member (loyalty program) or Normal
gender	Gender of the customer (Male / Female).
product_line	The category of the product sold (e.g., Health and beauty, Electronic accessories).
unit_price	Price of one unit of the product.
quantity	Number of units purchased.
Tax 5%	The tax amount applied (5% of the cost of goods sold).
total	The total cost of the purchase	
date	The date on which the purchase was made	
time	The time at which the purchase was made	
payment	The total amount paid	
cogs	Cost Of Goods sold	
gross_margin_pct	Profit margin percentage
gross_income	Gross profit from the sale.
rating	Customer satisfaction rating (scale of 1 to 10).

Analysis List:
Product Analysis
Perform an analysis on the data to gain insights into different product lines, determine the top-performing product lines, and identify areas for improvement in other product lines.

Sales Analysis
The objective of this analysis is to address the inquiry regarding the sales trends of the product. The outcomes of this analysis can assist in evaluating the efficiency of each applied sales strategy in the business and determining necessary modifications to increase sales.

Customer Analysis
This analysis is focused on identifying various customer segments, understanding purchasing trends, and evaluating the profitability associated with each of these customer segments.

Business Questions to Answer
Generic Questions
How many distinct cities are present in the dataset?
In which city is each branch situated?
Product Analysis
How many distinct product lines are there in the dataset?
What is the most common payment method?
What is the most selling product line?
What is the total revenue by month?
Which month recorded the highest Cost of Goods Sold (COGS)?
Which product line generated the highest revenue?
Which city has the highest revenue?
Which product line incurred the highest VAT?
Retrieve each product line and add a column product_category, indicating 'Good' or 'Bad,' based on whether its sales are above the average.
Which branch sold more products than average product sold?
What is the most common product line by gender?
What is the average rating of each product line?
Sales Analysis
Number of sales made in each time of the day per weekday
Identify the customer type that generates the highest revenue.
Which city has the largest tax percent/ VAT (Value Added Tax)?
Which customer type pays the most VAT?
Customer Analysis
How many unique customer types does the data have?
How many unique payment methods does the data have?
Which is the most common customer type?
Which customer type buys the most?
What is the gender of most of the customers?
What is the gender distribution per branch?
Which time of the day do customers give most ratings?
Which time of the day do customers give most ratings per branch?
Which day of the week has the best avg ratings?
Which day of the week has the best average ratings per branch?
