# Employee Performance and Retention Analysis

* Project Overview
This project examines employee performance and retention factors within a company. It helps HR and management understand key factors influencing employee satisfaction and attrition.

* Table Structure & Schema
1. Employees Table
Column Name	       Data   Type	Description
employee_id	       INT    (PK)	Unique ID for each employee
name	             VARCHAR	    Employee's full name
department	       VARCHAR	    Department where the employee works
hire_date	         DATE	        Date the employee was hired
salary	           DECIMAL	    Employee's salary
performance_score	 INT	        Employee's performance score (1-10)

2. Attrition Table
Column Name	     Data    Type	  Description
attrition_id	   INT     (PK)	  Unique ID for each attrition record
employee_id	     INT     (FK)	  ID of the employee who left
attrition_date	 DATE	          Date of attrition
reason	         VARCHAR	      Reason for leaving (Resigned, Terminated, Retired, etc.)

* Business Insights & Analysis
•	Performance Trends: Identify departments with high/low performance.
•	Retention Insights: Analyze attrition reasons to improve retention strategies.
•	Salary Optimization: Determine if salaries impact employee retention.

* How to Use This Project
1.	Load the dataset into a SQL database (MySQL, PostgreSQL, etc.).
2.	Run queries to analyze sales trends, customer behavior, and business KPIs.
3.	Visualize insights using BI tools like Tableau or Power BI.
4.	Share findings with stakeholders for data-driven decision-making.
