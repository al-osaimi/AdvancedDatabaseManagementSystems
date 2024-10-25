1. **In what ways can SQL's declarative nature simplify the process of querying databases for both developers and users, and how does it compare to procedural programming languages?**
   <details>
   <summary>Answer</summary>
   SQL’s declarative nature allows developers and users to specify *what* data they want rather than *how* to retrieve it. This contrasts with procedural programming languages where you need to explicitly define the steps to get the result. In SQL, a user can simply write a query like `SELECT * FROM customers WHERE age > 30;` and the database management system (DBMS) handles the details of retrieving the data. This makes SQL simpler and more intuitive for users, and reduces the complexity of writing queries as the DBMS optimizes the execution plan.
   </details>

<hr/>

2. **Discuss how the use of joins in SQL enables the combination of data from multiple tables, and explain a scenario where multiple types of joins would be necessary.**
   <details>
   <summary>Answer</summary>
   Joins in SQL allow data from multiple tables to be combined based on a related column between them. This is useful when data is normalized and split across different tables. For example, in an e-commerce database, customer details might be stored in one table and their orders in another. A join can be used to combine these tables to get a report showing customer names alongside their orders. Different types of joins (INNER, LEFT, RIGHT, FULL OUTER) are useful depending on the scenario. For instance, a LEFT JOIN can show all customers, even those who haven't made any orders, while an INNER JOIN would only show customers who have placed orders.
   </details>

<hr/>

3. Suppose that we have a relation marks(ID, score) and we wish to assign grades to students based on the score as follows: 
- grade F if score < 40, 
- grade C if 40 ≥ score < 60, 
- grade B if 60 ≥ score < 80,
- and grade A if 80 ≥ socre. 

Write SQL queries to do the following:
a. Display the grade for ea
h student, based on the marks relation.
b. Find the number of students with each grade.

  <details>
   <summary>Answer</summary>

a. Display the grade for each student, based on the marks relation.

```sql
select ID,
case
   when score < 40 then 'F'
   when score < 60 then 'C'
   when score < 80 then 'B'
   else 'A'
end
from marks
```

b. Find the number of students with each grade.


```sql
with grades as
(
   select ID,
   case
   when score < 40 then 'F'
   when score < 60 then 'C'
   when score < 80 then 'B'
   else 'A'
   end as grade
   from marks
)
select grade, count(ID)
from grades
group by grade

```

> [!TIP]
> As an alternative, the with clause can be removed, and instead the definition of grades can be made a subquery of the main query.


```sql
SELECT grade, COUNT(ID) AS student_count
FROM (
    SELECT 
        ID,
        CASE
            WHEN score < 40 THEN 'F'
            WHEN score >= 40 AND score < 60 THEN 'C'
            WHEN score >= 60 AND score < 80 THEN 'B'
            ELSE 'A'
        END AS grade
    FROM marks
) AS graded_students
GROUP BY grade;

```

*I prefer this way:*

```sql 
SELECT 
    CASE
        WHEN score < 40 THEN 'F'
        WHEN score >= 40 AND score < 60 THEN 'C'
        WHEN score >= 60 AND score < 80 THEN 'B'
        ELSE 'A'
    END AS grade,
    COUNT(ID) AS student_count
FROM marks
GROUP BY grade;
```

</details>

<hr/>

4. Suppose we have a relation employees(ID, salary) that stores the employee ID and their salary. We want to categorize the employees into different salary bands based on the following criteria:

- Band D if the salary is less than 30000.
- Band C if the salary is between 30000 and 49999.
- Band B if the salary is between 50000 and 79999.
- Band A if the salary is 80000 or above.

Write SQL queries to do the following:

1. Display the salary band for each employee based on the employees relation.
2. Find the number of employees in each salary band.

  <details>
   <summary>Answer</summary>

1. Display the salary band for each employee:

```sql
SELECT ID, salary_band
FROM (
    SELECT 
        ID,
        CASE
            WHEN salary < 30000 THEN 'D'
            WHEN salary >= 30000 AND salary <= 49999 THEN 'C'
            WHEN salary >= 50000 AND salary <= 79999 THEN 'B'
            ELSE 'A'
        END AS salary_band
    FROM employees
) AS categorized_employees;
```

2. Find the number of employees in each salary band:

```sql

SELECT salary_band, COUNT(ID) AS employee_count
FROM (
    SELECT 
        ID,
        CASE
            WHEN salary < 30000 THEN 'D'
            WHEN salary >= 30000 AND salary <= 49999 THEN 'C'
            WHEN salary >= 50000 AND salary <= 79999 THEN 'B'
            ELSE 'A'
        END AS salary_band
    FROM employees
) AS categorized_employees
GROUP BY salary_band;

-- OR simple way

SELECT 
    CASE
        WHEN salary < 30000 THEN 'D'
        WHEN salary >= 30000 AND salary <= 49999 THEN 'C'
        WHEN salary >= 50000 AND salary <= 79999 THEN 'B'
        ELSE 'A'
    END AS salary_band
    COUNT(ID) AS categorized_employees
FROM employees
GROUP BY salary_band;

```

</details>