### Explain generally, what is meant by a NoSQL database.

A NoSQL (originally referring to “non SQL”) database provides a mechanism for storage and retrieval of data which is modeled in means other than the tabular relations used in relational databases. 
NoSQL databases are increasingly used in big data and real-time web applications.

In short terms they are characteristics by being:
- Non-relational
- Distributed
- Open-sourced
- Horizontally scalable
- Schema-less

--------------------------------------------------------------------------------------------------------------------

### Explain Pros & Cons in using a NoSQL database like MongoDB as your data store, compared to a traditional Relational SQL Database like MySQL.

- NoSQL databases like MongoDB and Redis
  - Pros:
    - Support large volumes of data by running on clusters.
    - Gains simplicity of design and control over availability.
    - Easy to gain access to information about an object.
    - Makes some operations faster, due to the way data is structures in a NoSQL database (key-value, wide column, graph or document).
  - Cons:
    - Most NoSQL stores lack true ACID transactions.
    - Eventual consistency. NoSQL databases take a while to update, and therefor queries for data might not return updated data immediately.
- Relational databases
  - Pros:
    - Different kinds of data are divided and repeating data like zip codes are avoided.
    - Ease of use, the revision of any information as tables consisting of rows and columns are easy to understand.
    - Flexibility
    - Precision
    - Security
    - Data independence
  - Cons:
    - Performance
    - Physical storage consumption
    - Slow extraction of meaning from data

--------------------------------------------------------------------------------------------------------------------

### Explain how databases like MongoDB and redis would be classified in the NoSQL world

MongoDB is a document storage type of NoSQL database.

Redis is an in-memory persistent key-value storage type of NoSQL database.
