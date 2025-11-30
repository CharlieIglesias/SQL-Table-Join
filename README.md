# SQL Server - Employee Database Setup and Employee Role Management

## Overview
This SQL script sets up a **CompanyDB** SQL Server database and two related tables — **employee_list** and **employee_role** — to manage employee information and their roles. It demonstrates a structured approach to storing personal and job-related data and how to combine them using a simple **LEFT JOIN**. This setup provides a clear framework for HR reporting, payroll simulations, and operational analytics.  

## Key Features & Benefits
- **Centralised employee data:** `employee_list` stores essential personal information, including first name, middle name (optional), last name, age, and gender.  
- **Role & salary management:** `employee_role` tracks each employee’s job description and salary, maintaining separation of personal and role-based data.  
- **Flexible data queries:** Supports SQL joins to combine employee and role information for reporting, analytics, and decision-making.  
- **Scalable structure:** Easily extendable to include more columns (e.g., department, manager, hire date) or additional tables for projects, attendance, or benefits.  

## Usage
1. Open **SQL Server Management Studio (SSMS)**.  
2. Add the SQL script into a new query window.  
3. Execute the script to create the `CompanyDB` database, `employee_list` and `employee_role` tables.  
4. Insert employee and role records using `INSERT INTO` statements.  
5. Use SQL joins to combine personal and role data, ensuring all employees appear even if no role is assigned.  

## Impact
- **Improved data organisation:** Separates personal and role information for easier maintenance and clarity.  
- **Supports HR and payroll reporting:** Enables straightforward queries for job, salary, and demographic insights.  
- **Prepares for analytics:** Can be combined with performance or project data for dashboards, forecasting, or employee metrics.  
- **Demonstrates best practices:** Shows proper use of primary keys, nullable fields, and joins to maintain relational integrity and query efficiency.  


