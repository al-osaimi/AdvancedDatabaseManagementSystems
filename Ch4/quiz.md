# Chapter 4 Quiz - Intermediate SQL

## True or False Questions

1. A natural join in SQL retains only one copy of each common column in the result.
   <details>
   <summary>Answer</summary>
   True
   </details>

2. A left outer join adds tuples from both relations that do not have a match.
   <details>
   <summary>Answer</summary>
   False - A left outer join adds tuples from the left relation that do not have a match.
   </details>

3. SQL views allow users to see the entire database schema, including all tables and columns.
   <details>
   <summary>Answer</summary>
   False - Views can be used to restrict what parts of the database schema users can see.
   </details>

4. Materialized views are always up to date with the base tables in the database.
   <details>
   <summary>Answer</summary>
   False - Materialized views need to be maintained and updated when base tables are modified.
   </details>

5. A foreign key ensures referential integrity between two relations.
   <details>
   <summary>Answer</summary>
   True
   </details>

6. The `CHECK` constraint in SQL allows arbitrary conditions, including subqueries.
   <details>
   <summary>Answer</summary>
   True
   </details>

7. SQL transactions must end with either a `COMMIT` or a `ROLLBACK`.
   <details>
   <summary>Answer</summary>
   True
   </details>

8. A `JOIN` operation without a `WHERE` clause is equivalent to a Cartesian product.
   <details>
   <summary>Answer</summary>
   True
   </details>

9. An index helps speed up query performance by avoiding a full scan of the table.
   <details>
   <summary>Answer</summary>
   True
   </details>

10. The `GRANT` statement in SQL is used to revoke a user's privileges on a database.
    <details>
    <summary>Answer</summary>
    False - The `GRANT` statement is used to provide privileges, while `REVOKE` is used to remove them.
    </details>

## Multiple Choice Questions

1. Which type of join includes tuples from both relations that do not have matching tuples?
   - a) Natural join
   - b) Inner join
   - c) Outer join
   - d) Cross join
   <details>
   <summary>Answer</summary>
   c) Outer join
   </details>

2. What is the purpose of a view in SQL?
   - a) To store data
   - b) To hide certain data from users
   - c) To perform faster queries
   - d) To maintain referential integrity
   <details>
   <summary>Answer</summary>
   b) To hide certain data from users
   </details>

3. What SQL keyword is used to create a new view?
   - a) `CREATE`
   - b) `DEFINE`
   - c) `INSERT`
   - d) `INDEX`
   <details>
   <summary>Answer</summary>
   a) `CREATE`
   </details>

4. Which of the following is **not** a type of outer join in SQL?
   - a) Left outer join
   - b) Right outer join
   - c) Full outer join
   - d) Cross outer join
   <details>
   <summary>Answer</summary>
   d) Cross outer join
   </details>

5. Which SQL constraint ensures that a column cannot contain `NULL` values?
   - a) `UNIQUE`
   - b) `CHECK`
   - c) `NOT NULL`
   - d) `DEFAULT`
   <details>
   <summary>Answer</summary>
   c) `NOT NULL`
   </details>

6. What does the `ROLLBACK` statement do in a transaction?
   - a) Makes changes to the database permanent
   - b) Discards all changes made in the current transaction
   - c) Starts a new transaction
   - d) Deletes rows from a table
   <details>
   <summary>Answer</summary>
   b) Discards all changes made in the current transaction
   </details>

7. Which SQL clause is used to define conditions for filtering rows in the result of a `JOIN`?
   - a) `WHERE`
   - b) `ON`
   - c) `GROUP BY`
   - d) `HAVING`
   <details>
   <summary>Answer</summary>
   b) `ON`
   </details>

8. What happens when the `CASCADE` option is specified in a foreign key constraint?
   - a) The foreign key is ignored
   - b) Updates or deletes cascade to the child table
   - c) Foreign keys are automatically indexed
   - d) All foreign keys are set to `NULL`
   <details>
   <summary>Answer</summary>
   b) Updates or deletes cascade to the child table
   </details>

9. Which of the following is an SQL command used to remove a table?
   - a) `DELETE`
   - b) `DROP`
   - c) `ALTER`
   - d) `REMOVE`
   <details>
   <summary>Answer</summary>
   b) `DROP`
   </details>

10. Which SQL clause is used to ensure referential integrity between two tables?
    - a) `CHECK`
    - b) `PRIMARY KEY`
    - c) `UNIQUE`
    - d) `FOREIGN KEY`
    <details>
    <summary>Answer</summary>
    d) `FOREIGN KEY`
    </details>
