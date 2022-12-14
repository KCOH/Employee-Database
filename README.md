# SQL - Employee Database

![sql.png](sql.png)

## Background

It is the first major task is a research project on employees of the corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.

We will design the tables to hold data in the CSVs, import the CSVs into a SQL database, and answer questions about the data. In other words, you will perform:

1. Data Engineering

3. Data Analysis

#### Data Modeling

Inspect the CSVs and sketch out an ERD of the tables.

#### Data Engineering

* To specify data types, primary keys, foreign keys, and other constraints.

* Import each CSV file into the corresponding SQL table. 

#### Data Analysis

1. List the following details of each employee: employee number, last name, first name, sex, and salary.

2. List first name, last name, and hire date for employees who were hired in 1986.

3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

4. List the department of each employee with the following information: employee number, last name, first name, and department name.

5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

6. List all employees in the Sales department, including their employee number, last name, first name, and department name.

7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

## Bonus (Optional)

In order to examine the data, we need to overcome with a creeping suspicion that the dataset is fake. 
Surmise the spurious data in order to test the data engineering skills of a new employee. To confirm my hunch, I have decide to take the following steps to generate a visualization of the data:

1. Import the SQL database into Pandas. 

2. Create a histogram to visualize the most common salary ranges for employees.

3. Create a bar chart of average salary by title.

* Create an image file of your ERD.

* Create a `.sql` file of your table schemata.

* Create a `.sql` file of your queries.

* Create a Jupyter Notebook of the bonus analysis.

