1. **How do advanced SQL features such as views, triggers, and stored procedures enhance the functionality and performance of database applications?**
   <details>
   <summary>Answer</summary>
   Advanced SQL features like views, triggers, and stored procedures offer enhanced functionality by encapsulating logic at the database level. Views provide a simplified way to query complex data by encapsulating complex queries in virtual tables. Triggers automate responses to changes in data, such as logging changes or enforcing business rules. Stored procedures allow for complex logic and operations to be stored directly in the database, reducing the need to send multiple queries from the application. Together, these features reduce redundancy, ensure consistency, and improve performance by reducing the load on the application and network.
   </details>

2. **In what ways can recursive queries and common table expressions (CTEs) be used to handle hierarchical or self-referential data structures within a relational database?**
   <details>
   <summary>Answer</summary>
   Recursive queries and CTEs are powerful tools for dealing with hierarchical data, such as organizational charts or bill-of-materials structures, where each record can be related to another record in the same table. A recursive CTE allows you to write a query that iterates through the hierarchy, starting from a base case (e.g., the top-level manager) and then moving through each level of the hierarchy (e.g., employees who report to the manager). This simplifies querying hierarchical data without needing complex joins or application logic.
   </details>