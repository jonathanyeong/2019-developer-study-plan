# 2019 Developer Study plan

- Foundations
  - Data structures
    - Arrays
    - Linked Lists
    - Stack
    - Queue
    - Hash Table
    - Binary Search Tree
    - Priority Queue
    - Heaps
  - Sorting
    - selection
    - insertion
    - heapsort
    - quicksort
    - merge sort
  - Graphs
    - directed
    - undirected
    - adjacency matrix
    - adjacency list
    - Traversals: BFS, DFS
  - Big O notation
  - Bitwise Operations
- Intermediate
  - Databases
    - Relational vs No-sql
    - Normal form
    - Indices
    - Performance/Profiling
    - Joins
  - Web
    - Cookies
    - App Level Caching
    - APIs - RESTful vs Non-RESTful
  - Networking
    - UDP & TCP
    - HTTP
    - SSL and HTTPS
    - SSL/TLS
    - Sockets
  - Security
    - Encryption
    - Authentication
  - Design Patterns
  - Object Oriented Programming
    - Dependency Injection
  - String search and manipulations
- Advanced
  - System design
  - Scalability
  - Data handling
  - Concurrency
    - Deadlocks
    - Threads
  - Containers
- Resources
  - [Anki Web](https://apps.ankiweb.net/)
  - [Interview Cake - Data structures and algorithms](https://www.interviewcake.com/data-structures-and-algorithms-guide?utm_source=triplebyte)
  - [Algorithm design manual](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.471.4772&rep=rep1&type=pdf)
  - [Developer Roadmap 2019](https://github.com/kamranahmedse/developer-roadmap)
  - [Coding Interview University](https://github.com/jwasham/coding-interview-university/blob/master/README.md)
  - [Ruby Array](https://ruby-doc.org/core-2.4.1/Array.html)
  - [Ruby Integer](https://ruby-doc.org/core-2.5.0/Integer.html)
  

## Intermediate
### Databases
    - Normal form
    - Indices
    - Performance/Profiling
    - Joins
    - ORM impedance mistmatch.
    - SQL ACID
    - Referential integrity
    - Scaling and performance of databases
#### Relational vs Non relational (no-sql)
Relational databases like postgresql, mysql, etc. store the data in tables and rows. Non-relational databases such as mongoDB represent data in collections of JSON documents.

Relational databases use SQL (structured query language) to interact with the data. The structure of a relational database lets use link together tables with the use of foreign keys. 

A disadvantage of a relational database is ORM impedance mistmach. This boils down to the fact that relational databases were not designed for OO programming. Once there's a huge amount of data this is when ORM impedance really hurts. This might be when you consider going to a non-relational database model.

Other reasons you may want to go to a non-relational database model is:
- The need to store JSON objects.
- Coding around performance or horizontally scaling issues.
- If you need to join a lot of tables to get information you may want to represent it as a JSON object instead.
- Problems with defining your schema because of the nature of the data model.

There are of course issues with non-relational databases. There's no such thing as joins. You'll need multiple queries to get the data and then manually stitch the data together in the code. 

- [Pluralsight: Relational vs non relational databases](https://www.pluralsight.com/blog/software-development/relational-non-relational-databases)
- [SQL ACID explained](https://www.essentialsql.com/what-is-meant-by-acid/)

## Resources
### Ruby Integer methods
Digits to convert integer to array - https://ruby-doc.org/core-2.5.0/Integer.html#method-i-digits.
