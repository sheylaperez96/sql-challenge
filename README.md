# Unit 9 Homework: Employee Database

In this assignment, I'm working as a new data engineer at Pewlett Hackard. My first major task is a research project on employees of the corporation from the 1980s and 1990s. All that remains of the database of employees from that period are six CSV files. To complete this analysis, I will be modeling the data using an Entity Relationship Diagram (EDR), importing the CSVs into PostgreSQL by creating a schema, and querying the tables to answer questions about the data.

## Data Modeling

The EDR is located [here](/EmployeeSQL/DBD-SQL-Challenge.png).

## Data Engineering

The table schema is located [here](/EmployeeSQL/schema.sql).

## Data Analysis

I answered the following questions in this [analysis](//EmployeeSQL/Data_Analysis.sql):

- 1) List the following details of each employee: employee number, last name, first name, sex, and salary.
- 2) List first name, last name, and hire date for employees who were hired in 1986.
- 3) List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.
- 4) List the department of each employee with the following information: employee number, last name, first name, and department name.
- 5) List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."
- 6) List all employees in the Sales department, including their employee number, last name, first name, and department name.
- 7) List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
- 8) List the frequency count of employee last names (i.e., how many employees share each last name) in descending order.
