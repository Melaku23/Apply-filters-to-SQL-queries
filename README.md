# Apply-filters-to-SQL-queries
## Project description
* A company is attempting to increase the security of their system. My responsibility is to ensure the security of the system, look into any potential security concerns, and update employee computers as necessary. 

* The following steps provide examples of how  SQL is used with filters to perform security-related tasks.

## Retrieve after hours failed login attempts

* There was a potential security incident that occurred after business hours (after 18:00). All after hours login attempts that failed need to be investigated.
* The following code demonstrates how I created a SQL query to filter for failed login attempts that occurred after business hours.

<img width="1000" alt="sq1" src="https://github.com/Melaku23/Apply-filters-to-SQL-queries/assets/24359349/ef455dc4-fe48-40f6-a3d9-2f5865546c06">

## Retrieve login attempts on specific dates.

* A suspicious event occurred on 2022-05-09. Any login activity that happened on 2022-05-09 or on the day before needs to be investigated.
* The following code demonstrates how I created a SQL query to filter for login attempts that occurred on specific dates.

<img width="1000" alt="sq2" src="https://github.com/Melaku23/Apply-filters-to-SQL-queries/assets/24359349/c9c3df7a-ba03-424e-b91b-979f26eca79e">

* The first condition is login_date = '2022-05-09', which filters for logins on 2022-05-09. The second condition is login_date = '2022-05-08', which filters for logins on 2022-05-08.

## Retrieve login attempts outside of Mexico

* After looking over the company's data on login attempts, seems there is a problem with the login attempts that took place outside of Mexico. We need to look at these login attempts.

* The following code demonstrates how SQL query to filter for login attempts that occurred outside of Mexico. 

<img width="1000" alt="sq3" src="https://github.com/Melaku23/Apply-filters-to-SQL-queries/assets/24359349/46e4a7ef-c37a-49e2-8b06-7560ffa787f4">

* LIKE with MEX%  used as the pattern to match because the dataset represents Mexico as MEX and MEXICO. The percentage sign (%) represents any number of unspecified characters when used with LIKE. 

## Retrieve employees in Marketing

* The following code demonstrates how I created a SQL query to filter for employee machines from employees in the Marketing department in the East building.

<img width="1000" alt="sq4" src="https://github.com/Melaku23/Apply-filters-to-SQL-queries/assets/24359349/bd506a84-b9f0-4b56-a084-298f2fdf5ae2">

* The first condition is the department = 'Marketing' portion, which filters for employees in the Marketing department. The second condition is the office LIKE 'East%' portion, which filters for employees in the East building.

## Retrieve employees in Finance or Sales

* The machines for employees in the Finance and Sales departments also need to be updated. 
* The following code demonstrates how I created a SQL query to filter for employee machines from employees in the Finance or Sales departments.

<img width="1000" alt="sq5" src="https://github.com/Melaku23/Apply-filters-to-SQL-queries/assets/24359349/40753c55-d2bd-4dcc-ae07-d8b693c2c5ad">

* The first condition is department = 'Finance', which filters for employees from the Finance department. The second condition is department = 'Sales', which filters for employees from the Sales department.
 
## Retrieve all employees not in IT

* The following demonstrates how I created a SQL query to filter for employee machines from employees not in the  Information Technology department.

<img width="1000" alt="sq6" src="https://github.com/Melaku23/Apply-filters-to-SQL-queries/assets/24359349/e6c35d14-1c79-4c09-a12a-7969c269b319">

* The first part of the screenshot is my query, and the second part is a portion of the output. The query returns all employees not in the Information Technology department. First, I started by selecting all data from the employees table. Then, I used a WHERE clause with NOT to filter for employees not in this department.

## Summary

* I applied filters to SQL queries to get specific information on login attempts and employee machines. I used two different tables, log_in_attempts and employees. I used the AND, OR, and NOT operators to filter for the specific information needed for each task. I also used LIKE and the percentage sign (%) wildcard to filter for patterns.


