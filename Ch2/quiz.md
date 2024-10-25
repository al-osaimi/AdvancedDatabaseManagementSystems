# Chapter 2 Quiz - Introduction to Relational Model

## True or False Questions

1. **True or False**: In a relational model, the order of tuples (rows) in a relation is significant.
   <details>
   <summary>Answer</summary>
   False - In a relational model, the order of tuples is irrelevant.
   </details>

2. **True or False**: A candidate key is a minimal superkey.
   <details>
   <summary>Answer</summary>
   True
   </details>

3. **True or False**: A database schema is the structure or logical design of a database, while a database instance is the data within the database at a specific point in time.
   <details>
   <summary>Answer</summary>
   True
   </details>

4. **True or False**: The projection operation in relational algebra removes duplicate rows in the result.
   <details>
   <summary>Answer</summary>
   True
   </details>

5. **True or False**: The Cartesian product operation combines every tuple in one relation with every tuple in another relation.
   <details>
   <summary>Answer</summary>
   True
   </details>

6. **True or False**: Foreign key constraints enforce referential integrity between relations.
   <details>
   <summary>Answer</summary>
   True
   </details>

7. **True or False**: The union operation in relational algebra can be applied to relations with different sets of attributes.
   <details>
   <summary>Answer</summary>
   False - The union operation requires relations with the same set of attributes.
   </details>

8. **True or False**: Relational algebra is a non-procedural language.
   <details>
   <summary>Answer</summary>
   False - Relational algebra is a procedural language.
   </details>

9. **True or False**: Null values are allowed in all domains in the relational model.
   <details>
   <summary>Answer</summary>
   True
   </details>

10. **True or False**: The rename operation in relational algebra is used to assign a temporary name to the result of an expression.
    <details>
    <summary>Answer</summary>
    True
    </details>

## Multiple Choice Questions

1. Which of the following best describes a relation schema?
   - a) A snapshot of the data in the database at a specific time
   - b) The structure or design of a relation, including attribute names and types
   - c) A collection of tables with no specified attributes
   - d) The set of all keys in a relation
   <details>
   <summary>Answer</summary>
   b) The structure or design of a relation, including attribute names and types
   </details>

2. What is a superkey?
   - a) A set of attributes that uniquely identifies tuples in a relation
   - b) A key that has no duplicate attributes
   - c) A minimal set of attributes used to identify a tuple
   - d) A key that can reference tuples in another relation
   <details>
   <summary>Answer</summary>
   a) A set of attributes that uniquely identifies tuples in a relation
   </details>

3. Which relational algebra operation would you use to retrieve only specific columns from a relation?
   - a) Select
   - b) Project
   - c) Union
   - d) Cartesian Product
   <details>
   <summary>Answer</summary>
   b) Project
   </details>

4. The Cartesian product of two relations:
   - a) Returns only tuples with matching values in both relations
   - b) Combines every tuple in one relation with every tuple in another relation
   - c) Combines only distinct tuples in both relations
   - d) Requires a join condition to execute
   <details>
   <summary>Answer</summary>
   b) Combines every tuple in one relation with every tuple in another relation
   </details>

5. Which operation would you use in relational algebra to eliminate duplicate rows?
   - a) Union
   - b) Select
   - c) Project
   - d) Rename
   <details>
   <summary>Answer</summary>
   c) Project
   </details>

6. In relational algebra, which operator is used to filter tuples that satisfy a given predicate?
   - a) Project
   - b) Select
   - c) Union
   - d) Cartesian Product
   <details>
   <summary>Answer</summary>
   b) Select
   </details>

7. What is the purpose of a foreign key in a relational model?
   - a) To uniquely identify each tuple in a relation
   - b) To link records across different relations, enforcing referential integrity
   - c) To serve as an alternative name for attributes
   - d) To filter tuples in a relation based on a condition
   <details>
   <summary>Answer</summary>
   b) To link records across different relations, enforcing referential integrity
   </details>

8. Which of the following is **not** a basic operation in relational algebra?
   - a) Union
   - b) Set difference
   - c) Aggregation
   - d) Cartesian product
   <details>
   <summary>Answer</summary>
   c) Aggregation
   </details>

9. The `set-difference` operation in relational algebra:
   - a) Returns tuples present in one relation but not in the other
   - b) Combines tuples from both relations
   - c) Filters tuples based on a predicate
   - d) Returns tuples present in both relations
   <details>
   <summary>Answer</summary>
   a) Returns tuples present in one relation but not in the other
   </details>

10. Which of the following relational algebra operations combines relations based on common attributes?
    - a) Join
    - b) Union
    - c) Set-difference
    - d) Select
    <details>
    <summary>Answer</summary>
    a) Join
    </details>
