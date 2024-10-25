1. **What challenges arise from the '3 Vs' of Big Data (Volume, Velocity, and Variety), and how do distributed file systems like Hadoop's HDFS address these challenges?**
   <details>
   <summary>Answer</summary>
   The '3 Vs' of Big Data—Volume, Velocity, and Variety—represent the challenges of storing and processing large, fast-moving, and diverse data sets. Hadoop's HDFS addresses these challenges by distributing data across many machines, which allows for the storage of huge volumes of data. It also supports fault tolerance through replication, so data remains available even if some nodes fail. Additionally, HDFS is optimized for high throughput, making it suitable for processing data that arrives at high velocity. The system is also capable of handling a variety of data types, from structured to unstructured.
   </details>

2. **Discuss the trade-offs between using traditional relational databases versus NoSQL databases in managing big data, particularly in terms of scalability and data consistency.**
   <details>
   <summary>Answer</summary>
   Traditional relational databases are strong in enforcing ACID (Atomicity, Consistency, Isolation, Durability) properties and are suitable for applications that require strict consistency. However, they struggle to scale horizontally, which is necessary for managing Big Data. NoSQL databases, on the other hand, sacrifice some ACID properties (such as strong consistency) for better scalability and performance in distributed environments. NoSQL databases use horizontal scaling and are more flexible in handling unstructured data, making them a better fit for applications requiring high availability and