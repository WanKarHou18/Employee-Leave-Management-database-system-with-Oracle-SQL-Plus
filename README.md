# Employee-Leave-Management-database-system-with-Oracle-SQL-Plus
SQL database for Employee Leave Management System which aim for manage of employee leave

### Entity Relation Diagram for database

![image](https://user-images.githubusercontent.com/91049876/137591044-dc3c1598-09f5-4369-a222-47e330be3e60.png)

### Description for the concept and structure of database system:

Every employee of Company YY has a unique employee ID and the details of the employee will be stored in the database such as employee name, hire date, phone number and most important record of the leave record. The employee will be assigned to a department, every employee only can have one department, and one supervisor can also assign to the employee to guide them in the work. The system database will record the leave record of the employee to track their leave status. Each department will have one or more supervisors, but the supervisor only belongs to one department. In addition, the supervisor also can have one to many employees, the supervisor also the person who approved the leave of the employee. The leave record of the employee in the same department will be recorded in the department employee leave record table. Other than that, leave tables record all the leave records of employees including the leave type etc. Each type of leave has a unique leave code. Each employee will have different types of leave depending on their position or specific condition. Then, the system database also will record the days of leave left for each employee and the leave status of the employee. The days of leave available for an employee this year can be carried forward to next year under condition and restriction.

### Tools involved:
1.  Orcalce SQL *Plus 

### File Description:

1.  SourceCode.sql – SQL code to create database system. 
2.  Function.txt – List of functions to perform certain operations in SQL database.
3.  StoredProcedure.txt – List of Stored Procedure that could use in this SQL database.
4.  Queries.txt – List of Queries that could be used in this SQL database.
5.  Data Dictionary.pdf - Data Dictionary of ERD.
6.  Business Rule.pdf - Business Rule of Leave Management System.




