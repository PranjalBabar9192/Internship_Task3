# Internship_Task3

# Task 3: Basic SELECT Queries

## Objective
Learn to extract data from tables using `SELECT`.

## 🛠 Tools
- DB Browser for SQLite  
- MySQL Workbench

## Deliverable
SQL script using:  
- `SELECT`, `WHERE`, `AND`, `OR`, `LIKE`, `BETWEEN`, `ORDER BY`, `LIMIT`

## Key Concepts
- `SELECT *` – all columns  
- `SELECT col1, col2` – specific columns  
- `WHERE` – filter rows  
- `AND`/`OR` – combine conditions  
- `LIKE '%val%'` – pattern match  
- `BETWEEN a AND b` – range filter  
- `ORDER BY col DESC` – sort  
- `LIMIT n` – limit rows  
- `DISTINCT` – remove duplicates  
- `AS` – aliasing

## Example
```sql
SELECT name AS EmployeeName
FROM Employees
WHERE department = 'Sales'
ORDER BY salary DESC
LIMIT 5;
