
## Logical Schema vs. Physical Schema

<details> 

In database design, logical schema and physical schema are two key layers that structure and manage data effectively.

- Logical Schema:

Logical schemas describe data in terms of relational `tables` , `columns`, `relationships` and `constraints`.

 - Example: In a university database, a logical schema might include tables for `Students`, `Courses`, and `Enrollments`, with attributes like `student ID`, `course ID`, `course name` ...etc showing relationships (e.g., many-to-many between students and courses).

- Physical Schema:

The physical schema deals with the actual storage of data on disk (files, indices). 

 - Example: In the same university database, a physical schema might include `setting up indexes` on student ID and course ID for faster search operations, using `partitioning` to separate data by academic year, or defining `file paths where data is stored`.

### Multiple Choice Questions

What is the main purpose of a logical schema?

- A. Define the physical storage of data
- B. Outline the relationships and structure of data
- C. Specify how data is indexed on disk
- D. Detail the partitioning of data across servers
<details> <summary>Answer</summary> **- B. Outline the relationships and structure of data** </details>
Which of the following is a component of a physical schema?

- A. Data relationships
- B. Constraints like foreign keys
- C. Indexing and file structures
- D. Column data types
<details> <summary>Answer</summary> **- C. Indexing and file structures** </details>
In a logical schema, what typically represents entities like "Students" and "Courses"?

- A. Files
- B. Tables
- C. Disks
- D. Partitions

<details> <summary>Answer</summary> **- B. Tables** </details>
In a university database, where would the choice of partitioning data by academic year be defined?

- A. Logical schema
- B. Physical schema
- C. Both schemas
- D. Neither schema
<details> <summary>Answer</summary> **- B. Physical schema** </details>
Which schema would likely involve decisions related to data retrieval speed?

- A. Logical schema
- B. Physical schema
- C. Both schemas
- D. None of the above
<details> <summary>Answer</summary> **- B. Physical schema** </details>

### True/False Questions
The logical schema is typically independent of the hardware used for storage.

<details> <summary>Answer</summary> **True** </details>
Indexes are an aspect of the logical schem- A.

<details> <summary>Answer</summary> **False** - Indexes are typically part of the physical schem- A. </details>
The physical schema is concerned with how data is physically stored and accesse- D.

<details> <summary>Answer</summary> **True** </details>
Both logical and physical schemas are essential for optimizing data organization and retrieval.

<details> <summary>Answer</summary> **True** </details>
Logical schema focuses more on data structure, while physical schema focuses on data performance.

<details> <summary>Answer</summary> **True** </details>

</details>

<hr/>

## Database Key Types 

<details> 
In databases, keys are attributes or sets of attributes that help uniquely identify records and establish relationships between tables. Here are some common types of database keys:


#### 1. Primary Key

A unique identifier for each record in a table. No two records can have the same primary key value, and it cannot be null.
Example: In a Students table, student_id could be the primary key as it uniquely identifies each student.

#### 2. Foreign Key

A field in one table that links to the primary key of another table, creating a relationship between tables.
Example: In an Enrollments table, student_id might be a foreign key that references the student_id primary key in the Students table.

#### 3. Candidate Key

A field or combination of fields that could uniquely identify records in a table. A table can have multiple candidate keys, one of which is selected as the primary key.
Example: In a Students table, both student_id and email could serve as candidate keys.

#### 4. Composite Key

A key that consists of two or more attributes to uniquely identify a record in a table.
Example: In an Enrollments table, a composite key could be a combination of student_id and course_id to uniquely identify each enrollment record.

#### 5. Super Key

A set of one or more attributes that, together, can uniquely identify records in a table. A super key may contain additional attributes that are not necessary for uniqueness.
Example: In a Students table, student_id, or student_id combined with name, can be a super key.

#### 6. Alternate Key

A candidate key that was not chosen as the primary key. It still uniquely identifies records but serves as an alternative to the primary key.
Example: If student_id is the primary key in a Students table, then email could serve as an alternate key.

#### Comparsion

| Aspect           | Primary Key                            | Foreign Key                                |
|------------------|---------------------------------------|--------------------------------------------|
| Definition       | Uniquely identifies each row          | Refers to a primary key in another table   |
| Uniqueness       | Must be unique                        | Can be duplicated                          |
| Null Values      | NOT NULL                        | Can be NULL                                |
| Purpose          | Identifies rows within its own table  | Links two tables together                  |
| Relation         | Self-contained within its table       | Dependent on another table                 |
| Data Integrity   | Ensures uniqueness within the table   | Ensures valid references to another table  |


### Quiz: Database Key Types

### Multiple Choice Questions

Which key uniquely identifies each record in a table and cannot contain null values?

- A. Foreign Key
- B. Composite Key
- C. Primary Key
- D. Super Key
<details> <summary>Answer</summary> **- C. Primary Key** </details>
In a relationship between two tables, which key references the primary key of another table?

- A. Super Key
- B. Alternate Key
- C. Foreign Key
- D. Candidate Key
<details> <summary>Answer</summary> **- C. Foreign Key** </details>
What type of key can have multiple attributes to uniquely identify a record in a table?

- A. Composite Key
- B. Primary Key
- C. Super Key
- D. Foreign Key
<details> <summary>Answer</summary> **- A. Composite Key** </details>
Which key can uniquely identify records in a table and may contain additional, unnecessary attributes?

- A. Primary Key
- B. Candidate Key
- C. Alternate Key
- D. Super Key
<details> <summary>Answer</summary> **- D. Super Key** </details>
If a candidate key is not selected as the primary key, what is it called?

- A. Foreign Key
- B. Super Key
- C. Composite Key
- D. Alternate Key
<details> <summary>Answer</summary> **- D. Alternate Key** </details>
True/False Questions
A foreign key can have null values.

<details> <summary>Answer</summary> **True** - In some database systems, foreign keys can have null values if a record does not have a corresponding match. </details>
A primary key can be a composite key.

<details> <summary>Answer</summary> **True** - A primary key can consist of multiple fields, making it a composite key. </details>
An alternate key is another term for a primary key.

<details> <summary>Answer</summary> **False** - An alternate key is a candidate key that was not chosen as the primary key. </details>
A super key always contains the minimal attributes needed to uniquely identify records.

<details> <summary>Answer</summary> **False** - A super key may contain additional attributes beyond the minimal needed for uniqueness. </details>
Every primary key is a candidate key, but not every candidate key is a primary key.

<details> <summary>Answer</summary> **True** </details>

</details>

<hr/>

## Data Analytics 

<details>

#### 1. Machine learning 

Techniques are key to finding patterns in data and making predictions.

#### 2. Data mining 

Extends techniques developed by machine-learning communities to run them on very large datasets.

#### 3. Business Intelligence (BI)
The term business intelligence (BI) is synonym for data analytics.

Business intelligence (BI) uses business analytics, data mining, data visualization, and data tools **to help organizations make better data-driven decisions.**

#### 4. Data Warehousing

Warehouse is a repository (archive) of information gathered from multiple sources, stored under a unified schema, at a single site.

#### 5. Online analytical processing (OLAP)

OLAP is optimized for complex **data analysis and reporting**.

#### 6. Online transaction processing (OLTP) 

 OLTP is optimized for **transactional processing** and real-time updates.

</details>


## Application Development 

<details>

- How to secure passweords in database ?
  - Never store passwords in plain.
  - Hash all passwords. 

</details>

## Normalization

<details>
- Advantages to 3NF over BCNF:

 It is always possible to obtain a 3NF design without sacrificing losslessness or dependency preservation. 

- Disadvantages to 3NF:

We may have to use null values to represent some of the possible meaningful relationships among data items.
There is the problem of repetition of information.
</details>

<hr/>

## Indexing

<details>
Two basic kinds of indices:

- **Ordered indices:**  search keys are stored in sorted order
  - **Clustering index**
  - **Nonclustering index**
  - **Index-sequential file**

- **Hash indices:**  search keys are distributed uniformly across “buckets” using a “hash function”. 
    - **Static Hash index**
    - **Dynamic Hash index**

- **B-Tree Indexes**
- **B+-Tree Indexes**
- **Spatial and Temporal Indices:**
Databases can store data types such as lines, polygons, in addition to raster images 

    *Nearest neighbor queries:*, given a point or an object, find the nearest object that satisfies given conditions.

    *Range queries:* deal with spatial regions. e.g., ask for objects that lie partially or fully inside a specified region.
    Queries that compute intersections or unions of regions.

    *Spatial join* 

</details>
<hr/>

## SQL

<details>

Suppose we have a relation employees(ID, salary) that stores the employee ID and their salary. We want to categorize the employees into different salary bands based on the following criteria:

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
