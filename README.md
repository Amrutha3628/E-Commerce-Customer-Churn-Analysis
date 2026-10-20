E-Commerce Customer Churn Analysis

Project Overview

This project focuses on analyzing customer churn in an e-commerce business using MySQL. The analysis includes data cleaning, data transformation, customer segmentation, churn analysis, and business-oriented SQL queries to identify customer behavior and churn patterns.

Tools & Technologies

* MySQL
* Data Cleaning
* Data Transformation
* Data Analysis

Project Objectives

* Clean and prepare customer data for analysis
* Handle missing values using mean and mode imputation
* Identify and remove invalid/outlier values
* Standardize inconsistent categorical values
* Create meaningful customer status and complaint indicators
* Analyze customer churn and purchasing behavior
* Identify patterns related to payment mode, order category, satisfaction, coupons, and warehouse distance
* Analyze customer returns for churned and complaining customers

Data Cleaning

The project includes the following data-cleaning steps:

* Mean imputation for missing numerical values
* Mode imputation for missing categorical/count values
* Removal of records where WarehouseToHome is greater than 100
* Standardization of login device, order category, and payment mode values

Data Transformation

The following transformations were performed:

* Renamed PreferedOrderCat to PreferredOrderCat
* Renamed HourSpendOnApp to HoursSpentOnApp
* Created ComplaintReceived to identify customers who complained
* Created ChurnStatus to classify customers as Churned or Active
* Removed the original Churn and Complain columns after transformation

SQL Analysis

The project analyzes:

1. Churned and active customer counts
2. Average tenure and total cashback of churned customers
3. Percentage of churned customers who complained
4. Churn by city tier and preferred order category
5. Preferred payment mode among active customers
6. Order amount hike based on customer and order-category conditions
7. Average devices registered by payment mode
8. Customer distribution by city tier
9. Coupon usage by gender
10. Customer count and maximum app usage by order category
11. Total order count for Credit Card customers with the maximum satisfaction score
12. Average satisfaction score of customers who complained
13. Preferred order categories among customers using more than five coupons
14. Top three order categories by average cashback
15. Payment modes based on tenure and order count
16. Customer churn breakdown based on warehouse distance
17. Order details for selected customer conditions

Customer Returns Analysis

A separate customer_returns table was created to analyze return information.

The project uses SQL JOIN operations to identify return details and customer information for customers who are both:

* Churned
* Complaint received

Key SQL Concepts Used

* SELECT
* WHERE
* CASE
* COUNT()
* SUM()
* AVG()
* MAX()
* GROUP BY
* ORDER BY
* HAVING
* DISTINCT
* Subqueries
* UPDATE
* ALTER TABLE
* DELETE
* JOIN

Project Outcome

This project demonstrates practical SQL skills in data cleaning, transformation, exploratory analysis, aggregation, filtering, subqueries, and relational data analysis. The analysis helps identify customer churn patterns and provides a foundation for customer retention insights.

Author

Amrutha Asokan

Data Analyst Trainee
Kozhikode, Kerala
