Experiment 2 - Task 2
Name: ADITYA KUMAR DAS

UID: 24BET10123

Aim
To combine employee names from the employee and pt_employee tables using UNION ALL while preserving duplicate records.

Question
Write a query to output a single table with the names of employees in both the table 'employee' and 'pt_employee'.

Employee names are added on the field emp_name in both the tables.

Note: Do not remove the duplicate names while combining both the tables.

SQL Queries Used
Combine Employee Tables
SELECT  emp_name FROM Employee
UNION ALL
SELECT  emp_name FROM pt_employee;
Output
The query returns all employee names from both tables, including duplicates, in a single column named emp_name.
Output Screenshot
<img width="958" height="487" alt="Screenshot 2026-07-21 121752" src="https://github.com/user-attachments/assets/f99e173a-4f4c-4e8e-9e4a-692538afe033" />


Image Explanation
This task focuses on UNION ALL output only. The query combines both employee tables without removing duplicate names, which is the required result.

Result
The employee names from Employee and pt_employee were combined successfully using UNION ALL, and duplicate names were retained.
