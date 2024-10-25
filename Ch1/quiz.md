# Chapter 1 Quiz - Database Systems

## True or False Questions

1. A database system stores interrelated data and allows multiple users to access it concurrently.
   <details>
   <summary>Answer</summary>
   True
   </details>

2. The relational model is based on tables where rows represent columns and columns represent rows.
   <details>
   <summary>Answer</summary>
   False - Rows represent individual records, and columns represent attributes in the relational model.
   </details>

3. SQL is a procedural language for defining database schema.
   <details>
   <summary>Answer</summary>
   False - SQL is a declarative language.
   </details>

4. Data redundancy is one of the problems that database systems aim to solve.
   <details>
   <summary>Answer</summary>
   True
   </details>

5. The logical level of abstraction deals with how data is physically stored in the database.
   <details>
   <summary>Answer</summary>
   False - The logical level deals with the structure of the data, not how it is physically stored.
   </details>

6. DDL is a language used to access and update the data in a database.
   <details>
   <summary>Answer</summary>
   False - DDL is used to define schema, not to manipulate data.
   </details>

7. The transaction-management component ensures the consistency of a database in case of system failures.
   <details>
   <summary>Answer</summary>
   True
   </details>

8. The storage manager handles user authentication in the database system.
   <details>
   <summary>Answer</summary>
   False - The storage manager handles low-level data storage, not authentication.
   </details>

9. The network model was widely used before the relational model was introduced.
   <details>
   <summary>Answer</summary>
   True
   </details>

10. In a two-tier architecture, the client directly accesses the database without any intermediary.
   <details>
   <summary>Answer</summary>
   True
   </details>

11. Physical data independence refers to the ability to modify the physical schema without affecting the logical schema.
   <details>
   <summary>Answer</summary>
   True
   </details>

12. The query processor optimizes and executes queries written in SQL or other DML languages.
   <details>
   <summary>Answer</summary>
   True
   </details>

13. A transaction is a collection of operations that performs a single logical function in a database application.
   <details>
   <summary>Answer</summary>
   True
   </details>

14. Relational databases rely on network connections for integrity constraints.
   <details>
   <summary>Answer</summary>
   False - Integrity constraints are typically built into the database schema.
   </details>

15. The three-tier architecture includes a client, an application server, and a database server.
   <details>
   <summary>Answer</summary>
   True
   </details>

## Multiple Choice Questions

1. Which of the following is a major purpose of a database system?
   - a) To provide low-level access to the operating system.
   - b) To allow users to abstract and modify interrelated data.
   - c) To process simple mathematical operations.
   - d) To handle only text-based information.
   <details>
   <summary>Answer</summary>
   b) To allow users to abstract and modify interrelated data.
   </details>

2. Which of the following is **not** a feature of database systems?
   - a) Data redundancy and inconsistency.
   - b) Atomicity of updates.
   - c) Concurrent access by multiple users.
   - d) Data abstraction through different levels.
   <details>
   <summary>Answer</summary>
   a) Data redundancy and inconsistency.
   </details>

3. What language is used to define the database schema?
   - a) DML
   - b) SQL
   - c) DDL
   - d) XML
   <details>
   <summary>Answer</summary>
   c) DDL
   </details>

4. The relational data model stores data in:
   - a) Arrays
   - b) Hierarchies
   - c) Tables
   - d) Graphs
   <details>
   <summary>Answer</summary>
   c) Tables
   </details>

5. Which of the following is responsible for ensuring the consistency of the database in case of system failures?
   - a) Storage manager
   - b) Concurrency control manager
   - c) Transaction management component
   - d) Query evaluation engine
   <details>
   <summary>Answer</summary>
   c) Transaction management component
   </details>

6. Which of the following is **not** a type of architecture used in database systems?
   - a) Two-tier architecture
   - b) Object-oriented architecture
   - c) Three-tier architecture
   - d) Centralized architecture
   <details>
   <summary>Answer</summary>
   b) Object-oriented architecture
   </details>

7. Which of the following correctly describes **physical data independence**?
   - a) Changing the physical schema without affecting the logical schema.
   - b) Changing the logical schema without affecting the physical schema.
   - c) Changing both the logical and physical schema simultaneously.
   - d) Having a unified schema for physical and logical levels.
   <details>
   <summary>Answer</summary>
   a) Changing the physical schema without affecting the logical schema.
   </details>

8. What is the main advantage of declarative DML over procedural DML?
   - a) Declarative DML is more flexible in defining complex processes.
   - b) Declarative DML specifies what data is needed, without how to retrieve it.
   - c) Declarative DML provides real-time access to the database.
   - d) Declarative DML allows better indexing for faster retrieval.
   <details>
   <summary>Answer</summary>
   b) Declarative DML specifies what data is needed, without how to retrieve it.
   </details>

9. Which of the following describes the **logical design** of a database?
   - a) Choosing the schema and defining attributes.
   - b) Configuring hardware for database storage.
   - c) Creating data indices for faster access.
   - d) Ensuring network security for database access.
   <details>
   <summary>Answer</summary>
   a) Choosing the schema and defining attributes.
   </details>

10. A distributed database architecture:
   - a) Runs entirely on a single machine.
   - b) Has geographically distributed data.
   - c) Does not support concurrent access.
   - d) Requires minimal data heterogeneity management.
   <details>
   <summary>Answer</summary>
   b) Has geographically distributed data.
   </details>

11. Which of the following components is **not** part of the query processor?
   - a) DML compiler
   - b) Buffer manager
   - c) Query evaluation engine
   - d) DDL interpreter
   <details>
   <summary>Answer</summary>
   b) Buffer manager
   </details>

12. In a university database system, which of the following would **not** be part of the schema?
   - a) Information about students
   - b) Information about courses
   - c) Records of instructor salaries
   - d) Temporary session data from user logins
   <details>
   <summary>Answer</summary>
   d) Temporary session data from user logins
   </details>

13. What is a primary function of a **Database Administrator (DBA)**?
   - a) Managing the operating system.
   - b) Creating and managing schemas.
   - c) Writing application code to access the database.
   - d) Handling all security-related aspects of the organization.
   <details>
   <summary>Answer</summary>
   b) Creating and managing schemas.
   </details>

14. Which of the following describes **data abstraction** in database systems?
   - a) Direct access to the physical data layout.
   - b) Using multiple levels to hide complexity.
   - c) Direct connection between logical and physical levels.
   - d) Application developers managing both physical and logical schemas.
   <details>
   <summary>Answer</summary>
   b) Using multiple levels to hide complexity.
   </details>

15. What does **DDL** stand for in database systems?
   - a) Data Definition Language
   - b) Data Distribution Language
   - c) Data Determination Language
   - d) Data Design Language
   <details>
   <summary>Answer</summary>
   a) Data Definition Language
   </details>
