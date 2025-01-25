# SQL---HR-DBMS
The HR Database System is a structured SQL project designed to manage and analyze Human Resources data. It includes a relational database schema for managing employee information, departments, and payroll.

# Features of the HR Database System
Employee Management: Stores detailed information about employees, including their personal details, job roles, and department affiliations.
Payroll Management: Provides functionality for managing employee salaries, bonuses, and payroll details.
Department Allocation: Tracks the assignment of employees to departments and their roles within the organization.
Querying and Reporting: Allows running various SQL queries to generate reports such as employee lists, salary details, and department-wise summaries.
Data Integrity: Includes constraints such as foreign keys, unique constraints, and check constraints to ensure the integrity of the data.
# Project Structure
SQL Schema: HR database system.sql - This file contains the SQL code for creating the database schema, including tables, relationships, and constraints.
Database Model: HR database system.sql.mwb - A MySQL Workbench model file that visually represents the database schema and relationships.
SQL Queries: Sample queries to perform basic operations such as adding employees, retrieving payroll information, and department-wise reporting.
# Tools & Technologies Used
MySQL: The database management system used for this project.
MySQL Workbench: Used for designing the database schema and generating the .mwb model file.
SQL: Structured Query Language for creating tables, relationships, and running queries on the HR data.
# SQL Queries Included
Employee Data Retrieval: Query to fetch detailed employee records.
Salary Reports: Query to calculate and display employee salaries, bonuses, and deductions.
Department Reports: Query to generate department-wise employee distribution.
Custom Queries: Add more complex queries for specific business operations (e.g., employee retention rate, hiring trends).
# Database Schema
*Tables*:
Employees: Stores employee information (ID, name, job title, department, etc.).
Departments: Stores department information (ID, name, location).
Payroll: Stores salary and payroll-related data for employees.
[Add any other tables you have used]
*Relationships*:
One-to-many relationship between departments and employees.
One-to-one relationship between employees and payroll records.
