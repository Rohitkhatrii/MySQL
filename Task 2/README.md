# MySQL Basic Operations Project

This project demonstrates basic SQL operations on a `Company` table using MySQL. It includes examples of:

- Inserting multiple records
- Updating existing records
- Deleting specific records

# Table Used

**Table Name:** `Company`

**Schema:**
```sql
CREATE TABLE Company (
  id INT NOT NULL,
  name VARCHAR(150) NOT NULL,
  age INT NOT NULL,
  occupation VARCHAR(100) NOT NULL,
  PRIMARY KEY (id)
);

