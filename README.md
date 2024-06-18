# SQL-Queries

Welcome to the SQL-Queries repository! This repository is designed to help you practice SQL queries and database operations. Whether you're learning SQL for the first time or honing your skills, this repository offers exercises and resources to strengthen your understanding.

## Purpose

The main purpose of this repository is to provide a structured environment for practicing SQL. You'll find a variety of exercises and challenges that cover different aspects of SQL querying and database manipulation. By working through these exercises, you'll gain confidence in writing SQL queries and handling databases effectively.

## Features

- **Structured Exercises**: Practice SQL queries across different topics such as SELECT statements, JOIN operations, subqueries, aggregation functions, and more.
  
- **Database Setup**: Instructions and scripts to set up sample databases for practicing SQL queries. You can use these databases locally or on a SQL server.
  
- **Solutions and Examples**: Detailed solutions and examples for each exercise to help you understand the concepts and improve your query writing skills.

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



