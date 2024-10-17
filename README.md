### **Detailed Roadmap (Starting 15/10/2024 - Ending 31/12/2024)**  
**Study Schedule: Every Tuesday**  

---

### **Week 1: October 15, 2024**  
#### **Topic**: Introduction to Databases & ERD (Entity-Relationship Diagrams)  
- **Goal**: Understand the basics of databases and the use of ERD to design database structures.  
- **Requirements**: No prior knowledge required; introduction to databases.  
- **Resources**:  
  - **Watch**: CMU 15-445/645 Lecture 1 (Intro to Databases).  
  - **Read**: Chapters 1-2 of the "Concise Guide to Databases".  
  - **Resourses for ERDs** [Visual Paradigm ERD Tutorial](https://www.visual-paradigm.com/support/documents/vpuserguide/3563/3564/85375_drawingentit.html) and [ERD Basics Video](https://www.youtube.com/watch?v=QpdhBUYk7Kk&ab_channel=LucidSoftware)
  - **Practice**: Draw basic ERDs using tools like [Lucidchart](https://www.lucidchart.com) or [draw.io](https://app.diagrams.net/).  
- **Focus**:  
  - **At least**: Understand the concept of ERDs and how they model database structures.  
  - **Preferred**: Create simple ER diagrams for real-world scenarios (e.g., a library or online shopping system).  
  
---

### **Week 2: October 22, 2024**  
#### **Topic**: EERD (Enhanced Entity-Relationship Diagrams) & Data Modeling  
- **Goal**: Learn Enhanced ER Diagrams (EERD) and understand how to model complex database systems with relationships like inheritance.  
- **Requirements**: Familiarity with basic ERD concepts from Week 1.  
- **Resources**:  
  - **Watch**: CMU 15-445/645 Lecture 2 (EER Diagrams).  
  - **Read**: Chapters on EERD from the "Concise Guide to Databases".  
  - **Practice**: Create EERDs using examples from real-world systems, such as a hospital management system or multi-level organization.  
- **Focus**:  
  - **At least**: Learn how to use inheritance and specialization in EERDs.  
  - **Preferred**: Model complex systems involving multiple relationships and generalization.  
  
---

### **Week 3: October 29, 2024**  
#### **Topic**: Relational Models & SQL Basics  
- **Goal**: Understand relational models and basic SQL querying techniques.  
- **Requirements**: Understanding of ERD and EERD (Weeks 1-2).  
- **Resources**:  
  - **Watch**: CMU 15-445/645 Lecture 3 (Relational Models and SQL).  
  - **Read**: Chapter 3 of the "Concise Guide to Databases".  
  - **Practice**: [SQLZoo](https://sqlzoo.net/) tutorials (basic SQL, SELECT, JOIN).  
- **Focus**:  
  - **At least**: Grasp how ERDs translate to relational models (tables, primary/foreign keys).  
  - **Preferred**: Write SQL queries to manipulate and retrieve data from a relational database.  
  
---

### **Week 4: November 5, 2024**  
#### **Topic**: Advanced SQL & Transactions  
- **Goal**: Explore advanced SQL features (joins, subqueries, transactions).  
- **Requirements**: Familiarity with basic SQL from Week 3.  
- **Resources**:  
  - **Watch**: CMU 15-445/645 Lectures 4 & 5 (Advanced SQL).  
  - **Read**: Continue Chapter 3 of "Concise Guide to Databases".  
  - **Practice**: SQLZoo exercises on JOIN, GROUP BY, subqueries, and transactions.  
- **Focus**:  
  - **At least**: Execute advanced SQL queries and learn about transactional integrity (ACID).  
  - **Preferred**: Implement transactions in SQL and practice handling concurrency.  
  
---

### **Week 5: November 12, 2024**  
#### **Topic**: Indexing & Query Optimization  
- **Goal**: Learn about database indexing and optimizing query performance.  
- **Requirements**: Good understanding of SQL (Week 4).  
- **Resources**:  
  - **Watch**: CMU 15-445/645 Lecture 6 (Indexing).  
  - **Read**: Chapter 4 of "Concise Guide to Databases" (Indexing and Query Optimization).  
  - **Practice**: Analyze query performance using [EXPLAIN](https://use-the-index-luke.com/sql/explain-plan/postgresql) and practice creating indexes in SQL databases.  
- **Focus**:  
  - **At least**: Understand indexing types (B-trees, hash indexing) and when to use them.  
  - **Preferred**: Improve the performance of SQL queries by using indexes and analyzing execution plans.  
  
---

### **Week 6: November 19, 2024**  
#### **Topic**: Database Design & Normalization  
- **Goal**: Understand principles of database normalization and design for efficiency.  
- **Requirements**: Knowledge of relational models (Weeks 3-5).  
- **Resources**:  
  - **Watch**: CMU 15-445/645 Lecture 7 (Normalization).  
  - **Read**: Chapter 5 of the "Concise Guide to Databases" (Normalization).  
  - **Practice**: Normalize a given database design up to the 3rd Normal Form (3NF).  
- **Focus**:  
  - **At least**: Understand 1NF, 2NF, and 3NF and the process of normalizing databases.  
  - **Preferred**: Normalize complex database schemas and avoid design pitfalls.  
  
---

### **Week 7: November 26, 2024**  
#### **Topic**: Distributed Databases & NoSQL  
- **Goal**: Explore distributed database systems and NoSQL databases like MongoDB.  
- **Requirements**: Solid understanding of relational databases (Week 6).  
- **Resources**:  
  - **Watch**: CMU 15-445/645 Lecture 8 (Distributed Databases).  
  - **Read**: Chapter 6 of the "Concise Guide to Databases" (NoSQL Databases).  
  - **Practice**: Set up a simple NoSQL database (MongoDB) and perform basic CRUD operations.  
- **Focus**:  
  - **At least**: Understand the basics of NoSQL databases and their use cases (e.g., when to choose NoSQL over SQL).  
  - **Preferred**: Experiment with MongoDB and learn about CAP theorem and eventual consistency in distributed databases.  
  
---

### **Week 8: December 3, 2024**  
#### **Topic**: Query Optimization in Distributed Databases  
- **Goal**: Learn how to optimize queries in distributed environments and NoSQL databases.  
- **Requirements**: Understanding of indexing and distributed databases (Weeks 5 & 7).  
- **Resources**:  
  - **Watch**: CMU 15-445/645 Lecture 9 (Distributed Query Optimization).  
  - **Read**: Continue Chapter 6 of "Concise Guide to Databases" (Distributed Query Processing).  
  - **Practice**: Optimize queries in a distributed NoSQL database.  
- **Focus**:  
  - **At least**: Understand the challenges of optimizing queries in distributed databases.  
  - **Preferred**: Perform query optimizations in a distributed NoSQL database setup.  
  
---

### **Week 9: December 10, 2024**  
#### **Topic**: Transactions in Distributed Systems  
- **Goal**: Learn how transactions work in distributed databases and their consistency models.  
- **Requirements**: Familiarity with transactions in relational databases (Week 4).  
- **Resources**:  
  - **Watch**: CMU 15-445/645 Lecture 10 (Distributed Transactions).  
  - **Read**: Chapter 7 of "Concise Guide to Databases" (Distributed Transactions and CAP Theorem).  
  - **Practice**: Set up distributed transactions and handle consistency challenges.  
- **Focus**:  
  - **At least**: Understand 2-phase commit and other distributed transaction protocols.  
  - **Preferred**: Implement distributed transactions and handle failures.  
  
---

### **Week 10: December 17, 2024**  
#### **Topic**: Cloud Databases & Deployment  
- **Goal**: Understand cloud-based databases and their deployment models.  
- **Requirements**: Good understanding of distributed systems (Weeks 7-9).  
- **Resources**:  
  - **Watch**: CMU 15-445/645 Lecture 11 (Cloud Databases).  
  - **Read**: Chapter 8 of "Concise Guide to Databases" (Cloud Databases).  
  - **Practice**: Deploy a small database on a cloud service (AWS RDS, Google Cloud, or Azure) and interact with it.  
- **Focus**:  
  - **At least**: Understand the advantages of cloud databases and basic deployment.  
  - **Preferred**: Deploy a cloud-based database and manage it using cloud tools (backup, scaling).  
  
---

### **Week 11: December 24, 2024**  
#### **Topic**: Final Project – Database Design & Implementation  
- **Goal**: Create a final project that incorporates everything you’ve learned about database design, query optimization, distributed systems, and cloud deployment.  
- **Requirements**: Complete understanding of the topics covered in previous weeks.  
- **Resources**:  
  - **Project**: Choose