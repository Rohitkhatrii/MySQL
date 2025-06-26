1. SELECT * and Specific Columns

SELECT * FROM Company;

SELECT id FROM Company;

SELECT name FROM Company;

SELECT age FROM Company;

SELECT gender FROM Company;

SELECT occupation FROM Company;

#These queries are used to retrieve all or specific columns from the Company table.

2. WHERE, AND, OR, LIKE, BETWEEN
   
SELECT id FROM Company WHERE gender = 'M';

SELECT * FROM Company WHERE gender = 'F' AND age = 21;

SELECT * FROM Company WHERE age = 21 OR age = 25;

Select * from company WHERE name LIKE 'P%';

SELECT * FROM Company WHERE age BETWEEN 20 AND 26;

#These queries filter records using WHERE, AND, OR, LIKE, BETWEEN.

3. ORDER BY

SELECT name FROM Company ORDER BY salary;

#This query displays the name column ordered by salary in ascending order by default.



