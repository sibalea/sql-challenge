# sql-challenge
This Challenge is divided into three parts: data modeling, data engineering, and data analysis.
Data Modeling.

## Data Modeling
We inspect Inspect the [CSV files in the data folder](./data/), and sketch an [Entity Relationship Diagram](./EmployeeSQL/ER%20diagram.png) of the tables using [QuickDBD](http://www.quickdatabasediagrams.com/). Adjustments were made to the diagram to reflect what the final table should look like.

## Data Engineering
After creating a A Postgres SQL database named [`employeedb`](./EmployeeSQL/create_db.sql), we create a table schema for each of the six CSV files. we specify the data types, primary keys, foreign keys, and other constraints. Next, we import each CSV file into its corresponding SQL table (see [create_db.sql](./EmployeeSQL/create_db.sql)).

Data Analysis
The [queries.sql](./EmployeeSQL/queries.sql) SQL script generates the various tables to answer the following SQL queries:

1. List the employee number, last name, first name, sex, and salary of each employee.
2. List the first name, last name, and hire date for the employees who were hired in 1986.
3. List the manager of each department along with their department number, department name, employee number, last name, and first name.
4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
5. List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
6. List each employee in the Sales department, including their employee number, last name, and first name.
7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

## Acknowledgment
Adding Module5 assignment done with the expertise of [@rosericazondekon](https://github.com/rosericazondekon).