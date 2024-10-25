# Chapter 10 Quiz - Big Data

## True or False Questions

1. Big Data is characterized by its volume, velocity, and variety.
   <details>
   <summary>Answer</summary>
   True
   </details>

2. Distributed file systems, like Hadoop's HDFS, replicate data to handle hardware failures.
   <details>
   <summary>Answer</summary>
   True
   </details>

3. Sharding is a technique used to partition databases horizontally to scale them.
   <details>
   <summary>Answer</summary>
   True
   </details>

4. Key-value storage systems can only store large-sized data blocks.
   <details>
   <summary>Answer</summary>
   False - Key-value storage systems can store small-sized data records.
   </details>

5. The MapReduce paradigm divides tasks into `map` and `reduce` phases for parallel processing.
   <details>
   <summary>Answer</summary>
   True
   </details>

6. In a MapReduce job, the `reduce` function always operates before the `map` function.
   <details>
   <summary>Answer</summary>
   False - The `reduce` function operates after the `map` function.
   </details>

## Multiple Choice Questions

1. What is one of the primary challenges of **Big Data**?
   - a) Lack of storage solutions
   - b) Handling data that grows rapidly in size and variety
   - c) Reducing query processing time
   - d) Limiting access to small databases
   <details>
   <summary>Answer</summary>
   b) Handling data that grows rapidly in size and variety
   </details>

2. Which of the following is a **distributed file system** commonly used in Big Data?
   - a) NTFS
   - b) Hadoop Distributed File System (HDFS)
   - c) FAT32
   - d) ext4
   <details>
   <summary>Answer</summary>
   b) Hadoop Distributed File System (HDFS)
   </details>

3. What is **sharding** in the context of databases?
   - a) Combining multiple databases into one
   - b) Partitioning a database into smaller pieces across multiple servers
   - c) Encrypting the database for security
   - d) Rebuilding a database after failure
   <details>
   <summary>Answer</summary>
   b) Partitioning a database into smaller pieces across multiple servers
   </details>

4. In the **MapReduce** paradigm, what is the role of the `map` function?
   - a) Combine data across partitions
   - b) Transform input data into key-value pairs
   - c) Filter out invalid data
   - d) Sort the output data
   <details>
   <summary>Answer</summary>
   b) Transform input data into key-value pairs
   </details>

5. What does the **CAP theorem** in distributed systems refer to?
   - a) The trade-off between consistency, availability, and partition tolerance
   - b) The optimal storage technique for key-value databases
   - c) The three stages of data partitioning
   - d) The security risks in Big Data systems
   <details>
   <summary>Answer</summary>
   a) The trade-off between consistency, availability, and partition tolerance
   </details>
