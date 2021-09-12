# What does SQL stand for?

- Structured Query Language  
  SQL (pronounced "ess-que-el") stands for Structured Query Language. SQL is used to communicate with a database. According to ANSI (American National Standards Institute), it is the standard language for relational database management systems.

# NoSQL

- A NoSQL database provides a mechanism for storage and retrieval of data that is modeled in means other than the tabular relations used in relational databases. Such databases have existed since the late 1960s, but the name "NoSQL" was only coined in the early 21st century, triggered by the needs of Web 2.0 companies.

### What is the disadvantage of a NoSQL database?

- Disadvantages. NoSQL databases don't have the reliability functions which Relational Databases have (basically don't support ACID). This also means that NoSQL databases offer consistency in performance and scalability.

# SQL and NoSQL

![img](https://i.ytimg.com/vi/QwevGzVu_zk/maxresdefault.jpg)

SQL databases are relational, NoSQL databases are non-relational. SQL databases use structured query language and have a predefined schema. NoSQL databases have dynamic schemas for unstructured data. SQL databases are vertically scalable, while NoSQL databases are horizontally scalable.

# the five key differences between SQL vs. NoSQL are

1. SQL databases are relational, NoSQL databases are non-relational.
2. SQL databases use structured query language and have a predefined schema. NoSQL databases have dynamic schemas for unstructured data.
3. SQL databases are vertically scalable, while NoSQL databases are horizontally scalable.
4. SQL databases are table-based, while NoSQL databases are document, key-value, graph, or wide-column stores.
5. SQL databases are better for multi-row transactions, while NoSQL is better for unstructured data like documents or JSON.

### What kind of data is a good fit for an SQL database?

- If your data is highly structured and associations among the program entities are clearly defined (for instance, if you are developing a point of sale system where you need to store customer orders and product records), conventional SQL based databases are the best fit.

### What kind of data is a good fit a NoSQL database?

- Choose NoSQL if you have or need: Semi-structured or Unstructured data / flexible schema. Limited pre-defined access paths and query patterns. No complex queries, stored procedures, or views.

# MongoDB and Redis

- They are great for small scale, hierarchical data with a relatively small amount of children for each entry.

![img](https://assets-global.website-files.com/5debb9b4f88fbc3f702d579e/60957895922cdf1ccc04cf66_hierarchical-database-diagram.png)

### Which type of database is best for scalability?

- The clear winner with over 1/3 of multiple database type use is the combination of MySQL and MongoDB. While MongoDB is often considered an alternative to MySQL, the two databases do work well together when properly designed. The second most popular combination was MySQL and PostgreSQL together.

# Relational database

- A relational database is a digital database based on the relational model of data, as proposed by E. F. Codd in 1970. A system used to maintain relational databases is a relational database management system. Many relational database systems have an option of using the SQL for querying and maintaining the database.
- The relational model means that the logical data structures—the data tables, views, and indexes—are separate from the physical storage structures. This separation means that database administrators can manage physical data storage without affecting access to that data as a logical structure.

# Database schema

![img](https://francinemassue.weebly.com/uploads/1/3/0/9/13091251/what-is-a-schema-an-organized-mental-representation-of-information-about-the-world-events-or-people-stored-in-long-term-memory_orig.jpg)

- The database schema is its structure described in a formal language supported by the database management system. The term "schema" refers to the organization of data as a blueprint of how the database is constructed.

# MongoDB

![img](https://docs.mongodb.com/manual/images/crud-annotated-collection.bakedsvg.svg)

- MongoDB stores data records as documents (specifically BSON documents) which are gathered together in collections. A database stores one or more collections of documents.
- While MongoDB is more flexible and ensures high and diverse data availability, a SQL Database operates with the ACID (Atomicity, Consistency, Isolation, and Durability) properties and ensures greater reliability of transactions.
