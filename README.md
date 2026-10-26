# Job Fitment Assessment – Python and MySQL

## Overview

This project contains solutions to Python programming and MySQL queries completed as part of the Job Fitment Assessment conducted on 24 October 2026.

## Technologies Used

- **Python 3** — Programming and problem-solving
- **MySQL** — Database creation, data insertion, aggregation, and querying
- **Git and GitHub** — Version control and project submission

## Section A: Python Problem Solving

The Python section covers the following problems:

| Question | Problem | Concepts |
|---|---|---|
| Q1(a) | Separate even and odd numbers | Lists, loops, conditionals |
| Q1(b) | Find the second-largest element without `sort()` or `max()` | Loops, comparisons |
| Q1(c) | Remove duplicates while preserving original order | Lists, membership checking |
| Q2(a) | Reverse a string without slicing | Strings, loops |
| Q2(b) | Count vowels and consonants | Strings, conditions |
| Q2(c) | Count the frequency of each character | Dictionaries |
| Q3(a) | Check whether a number is a palindrome | Functions, loops, arithmetic |
| Q3(b) | Find numbers whose digits are strictly increasing | Strings, loops, comparisons |
| Q3(c) | Find the second-smallest unique element without sorting or `min()`/`max()` | Lists, loops, comparisons |

## Section B: MySQL

### Q1: Employees Table

- Created the `Employees` table with employee details.
- Inserted sample employee records.
- Calculated department-wise employee count and average salary.
- Retrieved employees earning the second-highest distinct salary.

**Concepts:** `CREATE TABLE`, `INSERT`, `GROUP BY`, `HAVING`, `AVG()`, `COUNT()`, `MAX()`, and subqueries.

### Q2: Students Table

- Created the `Students` table and inserted sample records.
- Calculated department-wise average marks and student count.
- Retrieved students scoring above the overall average marks.

**Concepts:** `CREATE TABLE`, `INSERT`, `GROUP BY`, `HAVING`, `AVG()`, and subqueries.

### Q3: Customers and Orders Tables

- Created the `Customers` and `Orders` tables.
- Inserted sample customer and order records.
- Calculated total order amount for each customer, including customers without orders.
- Retrieved customers who have never placed an order.

**Concepts:** Primary keys, foreign keys, `LEFT JOIN`, `SUM()`, `COALESCE()`, and `IS NULL`.

## Key Learning Outcomes

- Improved Python programming and logical problem-solving skills.
- Practiced list and string manipulation.
- Used dictionaries for frequency counting.
- Applied SQL aggregate functions and subqueries.
- Practiced joins and relational database concepts.
- Learned to identify missing relationships using `LEFT JOIN` and `IS NULL`.

## How to Run

### Python

Run an individual Python file from the terminal:

```bash
python filename.py
```

Replace `filename.py` with the name of the Python solution file.

### MySQL

1. Open MySQL Workbench or a MySQL command-line client.
2. Execute the table creation queries.
3. Insert the sample records.
4. Run the required SQL queries.

## Conclusion

This assessment provided practical experience in Python problem-solving and MySQL database operations, including data manipulation, aggregation, joins, and subqueries.
