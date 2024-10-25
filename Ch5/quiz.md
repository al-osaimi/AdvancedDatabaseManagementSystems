# Chapter 5 Quiz - Advanced SQL

## True or False Questions

1. SQL can express non-declarative actions such as printing a report or sending results to a graphical interface.
   <details>
   <summary>Answer</summary>
   False - SQL is declarative and cannot express non-declarative actions like printing or interfacing directly with a graphical interface.
   </details>

2. JDBC allows Java programs to interact with a SQL database.
   <details>
   <summary>Answer</summary>
   True
   </details>

3. Prepared statements in SQL are useful to prevent SQL injection attacks.
   <details>
   <summary>Answer</summary>
   True
   </details>

4. SQL functions cannot return tables, they can only return single scalar values.
   <details>
   <summary>Answer</summary>
   False - SQL supports table functions that return entire tables.
   </details>

5. Triggers can only be executed after an event, such as an `INSERT`, `UPDATE`, or `DELETE`.
   <details>
   <summary>Answer</summary>
   False - Triggers can be executed either before or after an event.
   </details>

6. The `ROLLUP` operation generates aggregates at every level of a specified hierarchy.
   <details>
   <summary>Answer</summary>
   True
   </details>

7. SQL allows recursive queries to find transitive relationships.
   <details>
   <summary>Answer</summary>
   True
   </details>

8. External language functions are always more secure than SQL-defined functions.
   <details>
   <summary>Answer</summary>
   False - External language functions can pose security risks if not carefully managed.
   </details>

9. A window function can be used to calculate a moving average in SQL.
   <details>
   <summary>Answer</summary>
   True
   </details>

10. OLAP stands for Online Analytical Processing and is used for interactive analysis of multidimensional data.
    <details>
    <summary>Answer</summary>
    True
    </details>

## Multiple Choice Questions

1. Which of the following is **not** a valid type of join in SQL?
   - a) Inner join
   - b) Natural join
   - c) Recursive join
   - d) Outer join
   <details>
   <summary>Answer</summary>
   c) Recursive join
   </details>

2. Which SQL feature allows iteration over results in a procedure?
   - a) `FOR`
   - b) `WHILE`
   - c) `REPEAT`
   - d) `CURSOR`
   <details>
   <summary>Answer</summary>
   d) `CURSOR`
   </details>

3. What is the main advantage of using window functions in SQL?
   - a) They optimize the database schema.
   - b) They allow aggregation over a specific range of rows.
   - c) They reduce query processing time.
   - d) They enforce data integrity constraints.
   <details>
   <summary>Answer</summary>
   b) They allow aggregation over a specific range of rows.
   </details>

4. Which type of SQL query is used to define recursive relationships such as prerequisites in courses?
   - a) `ROLLUP`
   - b) `WITH RECURSIVE`
   - c) `GROUP BY`
   - d) `JOIN`
   <details>
   <summary>Answer</summary>
   b) `WITH RECURSIVE`
   </details>

5. What is a **trigger** in SQL?
   - a) A type of join that happens automatically
   - b) A statement that is executed automatically as a side effect of a database modification
   - c) A function that returns a table
   - d) A method to handle SQL exceptions
   <details>
   <summary>Answer</summary>
   b) A statement that is executed automatically as a side effect of a database modification
   </details>

6. Which of the following is used to safely update large objects (e.g., `BLOB`s or `CLOB`s) in SQL?
   - a) `INSERT INTO`
   - b) `UPDATE WITH LOB`
   - c) `setBlob()` or `setClob()`
   - d) `ALTER BLOB`
   <details>
   <summary>Answer</summary>
   c) `setBlob()` or `setClob()`
   </details>

7. What SQL keyword is used to divide tuples into partitions for ranking functions?
   - a) `GROUP BY`
   - b) `PARTITION BY`
   - c) `ORDER BY`
   - d) `HAVING`
   <details>
   <summary>Answer</summary>
   b) `PARTITION BY`
   </details>

8. In an OLAP system, which operation changes the dimensions used in a cross-tabulation?
   - a) `Slicing`
   - b) `Dicing`
   - c) `Pivoting`
   - d) `Drilling down`
   <details>
   <summary>Answer</summary>
   c) `Pivoting`
   </details>

9. What does the `ROLLUP` SQL operation do?
    - a) Finds the rank of tuples
    - b) Generates a summary of data at different levels of detail
    - c) Computes recursive relationships
    - d) Combines multiple tables into one
    <details>
    <summary>Answer</summary>
    b) Generates a summary of data at different levels of detail
    </details>
