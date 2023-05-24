# Apply-filters-to-SQL-queries
## Project description
* A company is attempting to increase the security of their system. My responsibility is to ensure the security of the system, look into any potential security concerns, and update employee computers as necessary. 

* The following steps provide examples of how  SQL is uded with filters to perform security-related tasks.
## Retrieve after hours failed login attempts

There was a potential security incident that occurred after business hours (after 18:00). All after hours login attempts that failed need to be investigated.
The following code demonstrates how I created a SQL query to filter for failed login attempts that occurred after business hours.

<img width="100" alt="sq1" src="https://github.com/Melaku23/Apply-filters-to-SQL-queries/assets/24359349/ef455dc4-fe48-40f6-a3d9-2f5865546c06">
##Retrieve login attempts on specific dates.

* A suspicious event occurred on 2022-05-09. Any login activity that happened on 2022-05-09 or on the day before needs to be investigated.
* The following code demonstrates how I created a SQL query to filter for login attempts that occurred on specific dates.


<img width="479" alt="sq2" src="https://github.com/Melaku23/Apply-filters-to-SQL-queries/assets/24359349/c9c3df7a-ba03-424e-b91b-979f26eca79e">

The first condition is login_date = '2022-05-09', which filters for logins on 2022-05-09. The second condition is login_date = '2022-05-08', which filters for logins on 2022-05-08.

## Retrieve login attempts outside of Mexico

After looking over the company's data on login attempts, seems there is a problem with the login attempts that took place outside of Mexico. We need to look at these login attempts.

The following code demonstrates how SQL query to filter for login attempts that occurred outside of Mexico. 


<img width="487" alt="sq3" src="https://github.com/Melaku23/Apply-filters-to-SQL-queries/assets/24359349/46e4a7ef-c37a-49e2-8b06-7560ffa787f4">


<img width="476" alt="sq4" src="https://github.com/Melaku23/Apply-filters-to-SQL-queries/assets/24359349/bd506a84-b9f0-4b56-a084-298f2fdf5ae2">

<img width="476" alt="sq5" src="https://github.com/Melaku23/Apply-filters-to-SQL-queries/assets/24359349/40753c55-d2bd-4dcc-ae07-d8b693c2c5ad">


<img width="475" alt="sq6" src="https://github.com/Melaku23/Apply-filters-to-SQL-queries/assets/24359349/e6c35d14-1c79-4c09-a12a-7969c269b319">

