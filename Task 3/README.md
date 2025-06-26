''' 1. SELECT * and Specific Columns
These queries are used to retrieve all or specific columns from the Company table.
'''
SELECT * FROM Company;
SELECT id FROM Company;
SELECT name FROM Company;
SELECT age FROM Company;
SELECT gender FROM Company;
SELECT occupation FROM Company;

''' 2. WHERE, AND, OR, LIKE, BETWEEN
These queries filter records using WHERE, AND, OR, BETWEEN.
'''
SELECT id FROM Company WHERE gender = 'M';
SELECT * FROM Company WHERE gender = 'F' AND age = 21;
SELECT * FROM Company WHERE age = 21 OR age = 25;
SELECT * FROM Company WHERE age BETWEEN 20 AND 26;


''' 3. ORDER BY
This query displays the name column ordered by salary in ascending order by default.
'''
SELECT name FROM Company ORDER BY salary;

