Experiment 2 - Task 1
Name: ADITYA KUMAR DAS
UID: 24BET10123

Aim
To combine the Arts and Science tables using UNION and output the final stacked table.

Question
Write a query using UNION to stack the table 'Arts' over 'Science' and output the final table.

Note: The UNION statement removes duplicate data in the new table formed.

SQL Queries Used
Combine Arts and Science Tables
/* Write a query using union to stack the table 'Arts' over 'Science' and output the final table */
SELECT * FROM Science
union
SELECT * FROM Arts;
Output
The query stacks the rows from Science and Arts into a single table and removes duplicate rows.
Output Screenshot
Experiment 2 Task 1 Output

Image Explanation
<img width="1905" height="846" alt="image (2)" src="https://github.com/user-attachments/assets/b0893e96-8f54-484c-ad61-cf144173cb0e" />


Result
The Arts and Science tables were combined successfully using UNION, and the final table was produced as expected.
