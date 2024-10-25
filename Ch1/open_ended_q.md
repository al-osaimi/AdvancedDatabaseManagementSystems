
1. **This chapter has desribed several major advantages of a database system. What are two disadvantages?**

<details>
   <summary>Answer</summary>

Two disadvantages assoiated with database systems are listed below.
   - a. Setup of the database system requires more knowledge, money, skills, and
time.
- b. The complexity of the database may result in poor performan


</details>

<hr/>

2. List six major steps that you would take in setting up a database for a partiular enterprise.

<details>
<summary>Answer</summary>
Six major steps in setting up a database for a parti
ular enterprise are:

- Define the high-level requirements of the enterprise (this step generates a document known as the system requirements speifation.)
- Define a model ontaining all appropriate types of data and data relationships.
- Define the integrity constraints on the data.
- Define the physial level.
- For each known problem to be solved on a regular basis (e.g., tasks to be arried out by lerks or web users), define a user interface to arry out the task, and write the neessary appliation programs to implement the user interfae.
- Create/initialize the database.
</details>

<hr/>

3. **How do database management systems (DBMS) solve the problems of data redundancy and inconsistency, and why are these issues important in database design?**
 
<details>
   <summary>Answer</summary>
   Database management systems (DBMS) solve the problems of data redundancy and inconsistency by providing a structured and centralized system for storing data. Data redundancy is reduced because the same piece of data is not stored in multiple places, and instead, references are used where necessary. DBMS also enforces rules (integrity constraints) that ensure consistency across different operations on the data. These issues are crucial in database design because redundancy wastes storage and processing resources, and inconsistency can lead to incorrect or conflicting data, which compromises the reliability of applications relying on the data.
</details>

<hr/>

4. **Explain the significance of the three levels of data abstraction (physical, logical, and view) in a database system, and how they contribute to data independence.**
   
<details>
   <summary>Answer</summary>
   The three levels of data abstraction—physical, logical, and view—provide a way to separate concerns in database management. The physical level deals with how the data is actually stored, the logical level focuses on what data is stored and the relationships between data, and the view level allows users to interact with the database in a way that is meaningful to them. Data independence refers to the ability to change the schema at one level without affecting the schema at another level, and these three levels facilitate that independence. Changes to the physical storage can be made without affecting the logical structure, and views can be adjusted without affecting the overall schema.
</details>