Database: saleswalmart
The analysis was conducted on sales data stored in a database named saleswalmart. This dataset represents sales transactions across various branches of Walmart, capturing detailed sales information including customer demographics, product information, and sales metrics.


Table: sales
The main table used for analysis was the sales table, which contains the following fields:

invoice_id: Unique identifier for each transaction.
branch: Represents the store branch where the sale took place.
city: City location of the branch.
customer_type: Type of customer (e.g., Member or Normal).
gender: Gender of the customer (Male/Female).
product_line: Product category sold (e.g., Electronics, Clothing).
unit_price: Price per unit of the product.
quantity: Number of units sold.
VAT: Value-Added Tax applied.
total: Total amount of the transaction.
date: Date of the transaction.
time: Time of the transaction.
payment_method: Payment method used (e.g., Cash, Credit).
cogs: Cost of Goods Sold (COGS).
gross_margin_per: Gross margin percentage for the sale.
gross_income: Gross income from the transaction.
rating: Customer rating of the transaction.


Techniques Used:
SQL Functions: Used SQL's built-in functions like DAYNAME(), MONTHNAME(), and DISTINCT for date manipulation and data aggregation.
Case Statements: Employed CASE logic for time-based categorization of sales.
Grouping and Aggregation: Applied GROUP BY and aggregation functions (COUNT()) for summarizing key metrics, such as the most common payment method and top-selling product lines.


Achievements:
Successfully categorized transaction times into different parts of the day to uncover patterns.
Extracted insights such as top-selling product lines and the most popular payment methods.
Enhanced the dataset with additional features like day and month names to support time-series analysis.
