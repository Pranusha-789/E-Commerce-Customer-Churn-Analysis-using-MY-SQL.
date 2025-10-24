# E-Commerce-Customer-Churn-Analysis-using-MY-SQL.
Overview
In today’s competitive e-commerce world, retaining customers is vital. This project focused on analyzing customer churn using MySQL, with the goal of understanding why users leave and identifying ways to improve satisfaction and loyalty.

Data Preparation
The dataset included fields like tenure, device type, city tier, payment mode, satisfaction score, complaints, order category, coupon usage, and cashback.

I imported the data into MySQL (customer_churn table), handled missing values using mean (numeric) and mode (categorical), removed outliers (distance > 100 km), and standardized values (e.g., "Phone" → "Mobile Phone", "COD" → "Cash on Delivery").

Data Transformation
Renamed columns for clarity (e.g., "HourSpendOnApp" → "HoursSpentOnApp").
Created two new columns:

ChurnStatus ("Churned" or "Active")

ComplaintReceived (Yes/No)

Dropped original Churn and Complain columns after transformation.

Data Analysis
SQL queries revealed:

Churned users had shorter tenure and more complaints.

Tier-3 customers buying laptops/accessories churned more.

Active users preferred UPI, debit cards, and had higher satisfaction.

Mobile users showed high engagement.

Male users used more coupons; fashion was most popular.

Customers far from warehouses churned more, highlighting delivery impact.

Returns Analysis
I created a customer_returns table and joined it with churn data to identify users with returns and complaints—a high-risk segment needing better service.

Business Insights
Prioritize complaint resolution to reduce churn.

Improve delivery for Tier-3 and distant customers.

Offer mobile-only deals and loyalty rewards for satisfied users.

Conclusion
This project enhanced my SQL and data analysis skills. More importantly, it taught me how small user actions reflect larger trends, and how data-driven decisions can improve customer retention in real business scenarios.
