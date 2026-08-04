Experiment 2 - Task 3
Name: ADITYA KUMAR DAS

UID: 24BET10123

Aim
To find the list of fruits available in the supermarket using the INTERSECT operator.

Question
Consider a supermarket database.

Table 'fruit' has the list of all fruits available in the market, and some of them could be out of stock. Table 'inventory' has the updated list of items in the supermarket.

Write a query to find the list of fruits available in the supermarket. The f_name column has the name of the fruits and inv_name has the name of the items in the inventory. Output the name of the fruits.


SQL Queries Used
Find Common Fruits
/* Write a query to find the list of fruits available in the supermarket.
(f_name column has the name of the fruits and inv_name has the name of inventories, you are suppose to output the name of the fruits.)*/
SELECT f_name FROM fruit
INTERSECT
SELECT inv_name FROM inventory;



Output
┌────────────┐
│   f_name   │
├────────────┤
│ Banana     │
│ Cherry     │
│ Grape      │
│ Kiwi       │
│ Pear       │
│ Pineapple  │
│ Watermelon │
└────────────┘



Output Screenshot
<img width="1866" height="865" alt="image (4)" src="https://github.com/user-attachments/assets/c826e737-e336-4c42-bae9-900055eadad2" />


Image Explanation
The screenshot shows the INTERSECT query executed in the SQL editor. The result lists only the fruits that are present in both the fruit and inventory tables, which confirms the query works as expected.

Result
The list of available fruits was retrieved successfully using INTERSECT.
