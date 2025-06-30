In this, I created two MySQL tables: Customers and Orders. I defined appropriate fields for each, such as customer_id, name, age, and address for the Customers table, and order_id, customer_id, and amount for the Orders table.

After inserting sample data into both tables, I performed four different types of SQL joins to understand how data relationships work:

INNER JOIN:  returns rows when there is a match in both tables.

LEFT JOIN: returns all rows from the left table, even if there are no matches in the right table.

RIGHT JOIN: returns all rows from the right table, even if there are no matches in the left table.

FULL JOIN: Since MySQL doesn't support FULL JOIN directly, I used UNION of LEFT and RIGHT JOINs to show all records from both tables, matched or not.
