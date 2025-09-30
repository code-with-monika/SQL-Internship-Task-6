

# Task 6 – Subqueries and Nested Queries

### Objective

The main objective of this task is to understand and implement **subqueries** and **nested queries** in SQL. The focus is on using subqueries effectively in the **SELECT**, **WHERE**, and **FROM** clauses to filter, calculate, and analyze data.


### Key Concepts Learned

* **Subquery**: A query inside another query.
* **Types of Subqueries**:

  * **Scalar Subquery** → returns a single value (e.g., `MAX`, `AVG`).
  * **Correlated Subquery** → inner query depends on the outer query.
  * **EXISTS / IN Subquery** → checks if values or conditions exist.
  * **Derived Table** → subquery in the `FROM` clause, treated as a temporary table.
    
* **Use Cases of Subqueries**:

  * Filtering records dynamically.
  * Comparing with aggregated values.
  * Replacing complex joins in certain scenarios.
  * Building modular and readable SQL logic.

### Dataset Used

The dataset used is a simple **Employees table** with the following fields:

* **Emp_id** → Employee ID
* **Emp_name** → Employee Name
* **Emp_age** → Employee Age
* **Emp_salary** → Employee Salary

## Database Link:
http://localhost/phpmyadmin/index.php?route=/sql&pos=0&db=librarymanagement&table=employee




