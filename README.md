# SQL-Queries

Welcome to the SQL-Queries repository! This repository is to showcase my SQL queries and database operations. I will show my learning process of SQL and improving database skills, this repository offers resources of my practice

## Purpose

The main purpose of this repository is to provide a structured environment for practicing SQL. You'll find a variety of exercises and challenges that cover different aspects of SQL querying and database manipulation.

## Features

- **Structured Exercises**: Practice SQL queries across different topics such as SELECT statements, JOIN operations, subqueries, aggregation functions, and more.
## Getting Started

1. **Clone the Repository**: Clone this repository to your local machine using Git.

   ```bash
   git clone https://github.com/Yoritano/SQL-Queries.git
   cd SQL-Queries

<h1>This is a practice scenario from Google cybersecurity professional</h1>
   
<h2>Retrieve after hours failed login attempts</h2>
<b>The following code demonstrates how I created an SQL query to filter for failed login attempts that occurred after business hours:
SELECT *
FROM log_in_attempts
WHERE login_time > ‘18:00’ AND success = FALSE; </b>

![image](https://github.com/YoriTano/SQL-Queries/assets/106491544/99b233ea-d46d-425c-8306-4282d4053828)

<b> My responsibilities include ensuring the system's safety, investigating potential security issues, and updating employee computers as necessary. Below are examples of how I utilized SQL with filters to perform security-related tasks.

Retrieve After-Hours Failed Login Attempts
A potential security incident occurred outside of regular business hours (after 18:00). It is necessary to investigate all failed login attempts that occurred after hours
</b>

<h2>This is a practice scenario from Google cybersecurity professional</h2>

<b>A suspicious event occurred on 2022-05-09. Any login activity that happened on 2022-05-09 or on the day before needs to be investigated.

The following code demonstrates how I created an SQL query to filter for login attempts that occurred on specific dates:
SELECT *
FROM log_in_attempts
WHERE DATE(login_time) IN ('2022-05-08', '2022-05-09');</b>

![image](https://github.com/YoriTano/SQL-Queries/assets/106491544/f746097b-e98b-4f0d-9de8-f7ca77a86159)


<b>This query returns all login attempts that occurred on 2022-05-09 or 2022-05-08. First, I started by selecting all data from the log_in_attempts table. Then, I used a WHERE clause with an OR operator to filter my results to output only login attempts that occurred on either 2022-05-09 or 2022-05-08. The first condition is login_date = '2022-05-09', which filters for logins on 2022-05-09. The second condition is login_date = '2022-05-08', which filters for logins on 2022-05-08.</b>

<b>Retrieve login attempts outside of Mexico
After investigating the organization’s data on login attempts, I believe there is an issue with the login attempts that occurred outside of Mexico. These login attempts should be investigated.

The following code demonstrates how I created a SQL query to filter for login attempts that occurred outside of Mexico. 
SELECT *
FROM log_in_attempts
WHERE NOT country LIKE ‘MEX%’;</b>



![image](https://github.com/YoriTano/SQL-Queries/assets/106491544/7bfb2802-3598-425f-9a8d-98157495b5b8)

<b>This query returns all login attempts that occurred in countries other than Mexico. First, I started by selecting all data from the log_in_attempts table. Then, I used a WHERE clause with NOT to filter for countries other than Mexico. I used LIKE with MEX% as the pattern to match because the dataset represents Mexico as MEX and MEXICO. The percentage sign (%) represents any number of unspecified characters when used with LIKE.</b>

<b>Retrieve employees in Marketing
My team wants to update the computers for certain employees in the Marketing department. To do this, I have to get information on which employee machines to update.

The following code demonstrates how I created a SQL query to filter for employee machines from employees in the Marketing department in the East building.
FROM employees
WHERE department = ‘Marketing’ AND office LIKE ‘EAST%’;</b>

![image](https://github.com/YoriTano/SQL-Queries/assets/106491544/dd287292-e627-4dcf-89e4-10e01d045641)

<b>This query returns all employees in the Finance and Sales departments. First, I started by selecting all data from the employees table. Then, I used a WHERE clause with OR to filter for employees who are in the Finance and Sales departments. I used the OR operator instead of AND because I want all employees who are in either department. The first condition is department = 'Finance', which filters for employees from the Finance department. The second condition is department = 'Sales', which filters for employees from the Sales department.</b>


<b>Retrieve all employees not in IT
My team needs to make one more security update on employees who are not in the Information Technology department. To make the update, I first have to get information on these employees.

The following demonstrates how I created a SQL query to filter for employee machines from employees not in the  Information Technology department.
FROM employees
WHERE NOT department = ‘Information Technology’;</b>

![image](https://github.com/YoriTano/SQL-Queries/assets/106491544/34a2f02a-ef4b-4e16-8597-8277f9e87e07)

<b>The query returns all employees not in the Information Technology department. First, I started by selecting all data from the employees table. Then, I used a WHERE clause with NOT to filter for employees not in this department.</b>

<h2>Summary</h2>
<b>I applied filters to SQL queries to get specific information on login attempts and employee machines. I used two different tables, log_in_attempts and employees. I used the AND, OR, and NOT operators to filter for the specific information needed for each task. I also used LIKE and the percentage sign (%) wildcard to filter for patterns.</b>












