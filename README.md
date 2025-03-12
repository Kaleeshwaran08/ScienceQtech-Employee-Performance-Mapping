# ScienceQtech-Employee-Performance-Mapping
A new company in the data science space is called ScienceQtech. ScienceQtech has worked in the areas of drug discovery, algorithmic early detection of lung cancer, supply chain, market basket, fraud detection, and consumer sentiment. The HR department has requested that you, as the Junior Database Administrator, create reports on employee details, performance, and projects completed by the staff members. You will also need to analyse the employee database and extract specific data based on various requirements, as the annual appraisal cycle draws near. Note: To accomplish the aforementioned goal, you must obtain the dataset from the LMS's course resource section and construct a table.

Dataset Description emp_record_table: It holds all of the employees' data. Description of the variable Employee ID, or EMP_ID The employee's first name is FIRST_NAME. LAST_NAME - The worker's last name GENDER: The worker's gender ROLE: The position of the worker DEPT: The worker's field EXP: The number of years the individual has worked COUNTRY: The home country of the employee at the moment CONTINENT: The nation's geographical location SALARY: The worker's compensation Employee performance rating (EMP_RATING) MANAGER_ID: The manager that the worker is working for PROJ_ID: This is the project that the worker is working on or has worked on. 
Proj_table: This holds project information. PROJECT_ID: The project's identification The project's name is PROJ_Name. Domain: The project's domain DATE OF START Variable: Description EMP_ID: The employee's ID FIRST_NAME: The employee's first name LAST_NAME: The employee's last name GENDER: The employee's gender ROLE: The employee's position DEPT: The employee's field EXP: The employee's years of experience COUNTRY: The nation where the worker currently resides CONTINENT: The continent where the nation is located.

Tasks to Performed: Perform the following tasks on the dataset provided using SQL:

Create a database named employee, then import data_science_team.csv proj_table.csv and emp_record_table.csv into the employee database from the given resources
Create an ER diagram for the given employee database.

Write a query to fetch EMP_ID, FIRST_NAME, LAST_NAME, GENDER, and DEPARTMENT from the employee record table, and make a list of employees and details of their department Tasks to Perform Perform the following tasks on the dataset provided using SQL:

Write a query to fetch EMP_ID, FIRST_NAME, LAST_NAME, GENDER, DEPARTMENT, and EMP_RATING if the EMP_RATING is: • less than two • greater than four • between two and four
Write a query to concatenate the FIRST_NAME and the LAST_NAME of employees in the Finance department from the employee table and then give the resultant column alias as NAME.

Write a query to list only those employees who have someone reporting to them. Also, show the number of reporters (including the President). Tasks to Perform Perform the following tasks on the dataset provided using SQL:

Write a query to list down all the employees from the healthcare and finance departments using union. Take data from the employee record table.

Write a query to list down employee details such as EMP_ID, FIRST_NAME, LAST_NAME, ROLE, DEPARTMENT, and EMP_RATING grouped by dept. Also include the respective employee rating along with the max emp rating for the department.

Write a query to calculate the minimum and the maximum salary of the employees in each role. Take data from the employee record table. Tasks to Perform Perform the following tasks on the dataset provided using SQL:

Write a query to assign ranks to each employee based on their experience. Take data from the employee record table.

Write a query to create a view that displays employees in various countries whose salary is more than six thousand. Take data from the employee record table.

Write a nested query to find employees with experience of more than ten years. Take data from the employee record table. Tasks to Perform Perform the following tasks on the dataset provided using SQL:

Write a query to create a stored procedure to retrieve the details of the employees whose experience is more than three years. Take data from the employee record table. Perform the following tasks on the dataset provided using SQL:

Write a query using stored functions in the project table to check whether the job profile assigned to each employee in the data science team matches the organization’s set standard The standard is given as follows: • Employee with experience less than or equal to 2 years, assign 'JUNIOR DATA SCIENTIST’ • Employee with experience of 2 to 5 years, assign 'ASSOCIATE DATA SCIENTIST’ • Employee with experience of 5 to 10 years, assign 'SENIOR DATA SCIENTIST’ • Employee with experience of 10 to 12 years, assign 'LEAD DATA SCIENTIST’, • Employee with experience of 12 to 16 years, assign 'MANAGER' Tasks to Perform Perform the following tasks on the dataset provided using SQL:

Create an index to improve the cost and performance of the query to find the employee whose FIRST_NAME is ‘Eric’ in the employee table after checking the execution plan.

Write a query to calculate the bonus for all the employees, based on their ratings and salaries (Use the formula: 5% of salary * employee rating).

Write a query to calculate the average salary distribution based on the continent and country. Take data from the employee record table.
![image](https://github.com/user-attachments/assets/27f7a593-3952-4337-a89c-ba07d5806201)
