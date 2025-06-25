# MySQL Company Table Project

This project includes basic MySQL commands to create a table and insert data into it. It is useful for beginners who want to understand how to create and manage a simple database.

## What it does

- Shows all databases
- Uses a database named `rohit1`
- Creates a table named `Company`
- Inserts sample records into the table

## Sample Table Structure

```sql
CREATE TABLE Company (
  id INT NOT NULL,
  name VARCHAR(150) NOT NULL,
  age INT NOT NULL,
  occupation VARCHAR(100) NOT NULL,
  PRIMARY KEY (id)
);

# Sample Data Inserted
sql
Copy
Edit
INSERT INTO Company (id, name, age, occupation) VALUES
(1, 'Praveen', 20, 'Business Man'),
(2, 'Raman', 21, 'Sole Proprietor'),
(3, 'Arpit', 25, 'Business Man'),
(4, 'Mohit', 26, 'Corporate');
