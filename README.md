# SQL Challenge

This repo consists of three deliverables: 
- Data Modeling
- Data Engineering
- Data Analysis 

## Data Modeling
I inspected 6 CSV files (which can be found in the data folder of this repo), and used QuickDBD to create my Entity Relationship Diagram of the tables. After creating a few versions of this ERD, I had a tutor help me change a handful of dependencies on relationships by switching the one to many connection(s) and vice versa. 
- A copy my ERD is saved as a png file within the EmployeeSQL folder of this repo. 

## Data Engineering
By following how I constructed my ERD, I was able to properly create my tables with the correct data types, primary keys, foreign keys, and added constraints.
- I imported each CSV file into its corresponding SQL table.
- To ensure I was able to conduct my data analysis, I imported my 'departments' and 'titles' tables first, as they were the only tables that had no foreign keys. In other words, these tables had no dependencies on other tables. Once these two tables were imported, I successfully imported the remaining 4 tables.
- I saved my table schema as a SQL file within the EmployeeSQL folder of this repo. 

## Data Analysis
In order to answer the following business questions, I wrote 8 SQL scripts that are comprised of multiple keyword functions including: LEFT JOINS, INNER JOINS, ORDER BY, GROUP BY, COUNT AS, AND, and LIKE. 

These queries can be found in my Employee_Queries.sql file within my EmployeeSQL folder of this repo. 

- Listed the employee number, last name, first name, sex, and salary of each employee.
- Listed the first name, last name, and hire date for the employees who were hired in 1986.
- Listed the manager of each department along with their department number, department name, employee number, last name, and first name.
- Listed the department number for each employee along with that employee’s employee number, last name, first name, and department name.
- Listed first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
- Listed each employee in the Sales department, including their employee number, last name, and first name.
- Listed each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
- Listed the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

