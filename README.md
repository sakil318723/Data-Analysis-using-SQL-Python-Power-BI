# Data-Analysis-using-SQL-Python-Power-BI

# Customer Purchase Behavior Analysis  
SQL | Python | Power BI

## Project Overview
This project presents an end-to-end data analysis of customer purchase behavior using SQL, Python, and Power BI.  
The objective is to analyze transactional and customer-level data to uncover patterns that support business decisions related to revenue growth, customer retention, product strategy, and operational efficiency.

The project is designed to reflect a real-world data analyst workflow, from querying raw data to delivering business-ready insights through dashboards.

---

## Objectives
- Analyze revenue and spending behavior across customer segments
- Understand the impact of subscriptions and discounts on revenue
- Identify top-performing and underperforming products
- Segment customers based on purchase history
- Provide actionable insights through data visualization

---

## Tools and Technologies
- SQL (PostgreSQL): Data extraction, aggregation, and segmentation
- Python (Pandas, SQLAlchemy): Data loading, validation, and analysis
- Power BI: Interactive dashboards and reporting
- Jupyter Notebook: Analysis workflow and experimentation

---

## Dataset Description
The dataset contains customer purchase records with the following attributes:
- Customer demographics: age, gender, location
- Product information: product name, category, size, color, season
- Purchase details: purchase amount, previous purchases, frequency
- Marketing attributes: discount applied, subscription status
- Service attributes: shipping type, payment method
- Customer feedback: review rating

---

## Analysis Performed

### Revenue and Spending Analysis
- Revenue comparison between male and female customers
- Revenue contribution by age group and location
- Average and total spending by subscription status
- Customer lifetime value approximation using purchase history

### Customer Segmentation
- Classification of customers into new, returning, and loyal segments
- Analysis of repeat buyer behavior
- Relationship between repeat purchases and subscription adoption

### Product and Category Insights
- Top products by average review rating
- Most purchased products within each category
- Products with the highest discount usage
- Identification of highly rated but low-volume products

### Discount and Promotion Analysis
- Discount adoption rate by product
- Comparison of spending between discounted and non-discounted purchases
- Impact of discounts on repeat and loyal customers

### Operational Insights
- Comparison of purchase amounts between standard and express shipping
- Payment method usage and spending patterns
- Relationship between review ratings and purchase frequency

---

## SQL Analysis
All business questions were answered using PostgreSQL queries.  
The analysis includes:
- Grouping and aggregation
- Conditional logic using CASE statements
- Subqueries and window functions
- Ranking and percentage calculations

Queries are written with clarity and reusability in mind.

---

## Python Workflow
Python was used to:
- Load and validate the dataset
- Connect to PostgreSQL using SQLAlchemy
- Perform sanity checks and exploratory analysis
- Support the SQL analysis where required

The workflow follows clean and reproducible data analysis practices.

---

## Power BI Dashboard
Power BI dashboards were built to visualize key findings, including:
- Revenue trends and breakdowns
- Customer segments and subscription behavior
- Product and category performance
- Discount effectiveness and operational metrics

Dashboards are designed for non-technical stakeholders and decision-makers.

---

## Key Insights
- Subscribed customers generate higher average revenue than non-subscribers
- Loyal and repeat customers contribute a significant share of total revenue
- Certain products receive strong customer ratings but have lower sales volume
- Discounts are more commonly used by repeat buyers
- Shipping type has limited impact on average purchase value

---

## Conclusion
This project demonstrates the ability to translate raw data into meaningful business insights using SQL, Python, and Power BI.  
It reflects practical data analysis skills applicable to real-world business environments.

---

## Author
Sakil Sarkar  
Aspiring Data Analyst  
Skills: SQL, Python, Power BI
