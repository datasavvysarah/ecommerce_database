# SQL Subqueries and CTEs Assignment Ecommerce_database

📋 Assignment Overview

- This repository contains my complete SQL assignment demonstrating subqueries and Common Table Expressions (CTEs) using a Nigerian e-commerce database.

📁 Files Included

## complete_assignment.sql: 

This single file contains everything;

- Database schema creation (CREATE TABLE statements)
- Sample data insertion (INSERT statements)
- All 4 assignment query solutions
- Comments explaining each solution

## Screenshots: 

Which contains screenshots of
- Query executions in MySQL Workbench
- Results for each assignment question

## Assignment Questions Solved;

Question 1: Employees Above Department Average Salary
- Find employees whose salary is above the average salary for their department.

Question 2: Customer Details for High-Value Orders
- Retrieve customer details for all customers who have placed orders over ₦1000.

Questions 3 & 4: Complex Order Analysis
- Find orders where the total amount is greater than the average order total for that customer, and that customer's total spending is above the global average customer spending.

## How to Run

- Open MySQL Workbench.
- Create a new query tab.
- Copy and paste the entire complete_assignment.sql file.
- Execute the complete script (Ctrl+Shift+Enter).
- View results for each section.

## Database Overview

Tables Created:

- customers - 50 Nigerian customers with realistic data
- products - 50 products across multiple categories
- departments - 7 company departments
- employees - 30 employees with salary variations
- orders - 25 orders with different amounts
- order_items - Detailed order line items

Key Features:

- Realistic Nigerian names, cities, and phone numbers
- JSON columns for flexible data storage
- Salary ranges designed to demonstrate department averages
- Multiple orders per customer for meaningful analysis

## SQL Concepts Demonstrated
- Subqueries
- Scalar subqueries for single-value comparisons
- Subqueries with IN clause for filtering
- Correlated subqueries
- Common Table Expressions (CTEs)
- Simple CTEs for code organization
- Multiple CTEs in single query
- Complex business analytics
- Advanced Features
- JSON data extraction
- Window functions
- Complex aggregations
- Performance optimization

# Screenshots
- The screenshots/ folder contains:
- question_1_results.png - Query 1 execution and results
- question_2_results.png - Query 2 execution and results
- question_3_4_results.png - Query 3&4 execution and results

# Key Learning Outcomes

- Subquery mastery - Different types and use cases
- CTE proficiency - Complex multi-step analysis
- Real-world application - Business analytics scenarios
- JSON handling - Modern database features
- Performance awareness - Efficient query design

# 📝 Notes
- All foreign key constraints removed for easier setup
- Data designed to provide meaningful results for all questions
- Comments throughout the SQL file explain each solution
- Ready to run in any MySQL 8.0+ environment


Student: Sarah Uko

Course: AltSchool Data Engineering Baraka 2025

Date: 23rd July, 2025.
