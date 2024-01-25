# InterViewQuestions
## Backend
- Defference between **Byte-Code** and **Machine Code**:
  |                         **Byte-Code**                             |                          **Machine Code**                          |
  |-------------------------------------------------------------------|--------------------------------------------------------------------|
  |It is a intermediate representation of a program that is generated |Also known as `native code` which is the low-level binary           |
  |by a `compiler`.                                                   |representation of instruction that can be executed by a computer's  |
  |                                                                   |CPU.                                                                |
  |-------------------------------------------------------------------|--------------------------------------------------------------------|
  |Platform indepentent.                                              |Platform specific may not run without modification in different     |
  |                                                                   |architecture.                                                       |
  |-------------------------------------------------------------------|--------------------------------------------------------------------|
  |Not executable by hardwar.It needs an interpreter or a `JVM`.      |Machine code is executed directly by the hardware.                  |
  |-------------------------------------------------------------------|--------------------------------------------------------------------|
  |Java bytecode (.class files), Common Intermediate Language (CIL)   |Assembly language instructions and binary executable files          |
  |in .NET (.dll files), and Python bytecode (.pyc files) are examples|(e.g. .exe on Windows) contain machine code. Assembly language is a |
  |of intermediate code or bytecode.                                  |low-level programming language that represents a one-to-one         |
  |                                                                   |correspondence with machine code instructions.
- Defference between **API** and **Libarery**: 
- Differences between **API** and **RESTfull API**:
  |                         API                             |                          RESTful API                          |
  |---------------------------------------------------------|---------------------------------------------------------------|
- Defferences between **RESTfull** and **GraphQL** API:
  |                         RESTfull API                    |                          GraphQL API                          |
  |---------------------------------------------------------|---------------------------------------------------------------|
## DataBase
- Generally 2 types of language are used in Database. 1. DDL(Data Definition Language) and 2. DML(Data Manipulation Language).
  Where table structure is defined by DDL and various queries like reading data, changing and deleting etc. are done with DML.
- When we run a query in a database then database execute this query in several steps.. 
  - Transform SQL query in database format
  - Determines if there are any mistakes in the syntex in the query
  - Examines its semantics
  - Makes execution plan of the query
  - Then adds input variables to the query and
  - In last executes the query and returns the outputs.
- **Types of SQL Commands:**
  1. **DDL (Data Definition Language):** create, alter, rename, truncate & drop
  2. **DQL (Data Query Language):** select
  3. **DML (Data Manipulation Language):** insert, update & delete
  4. **DCL (Data Control Language):** grant & revoke permission to users
  5. **TCL (Transaction Control Language):** start transaction, commit, rollback
<br>

## Problem-solving
## Java 
- GO TO -> [here](https://github.com/ImranHossain00/JavaPractice)
## OOP
- The 4 Base concepts of the **OOP** are:
  1. **Abstraction:**
  2. **Polymorphism:**
  3. **Inheritance:**
  4. **Encapsulation:**
- Defferenece between argument and parameter in methods/functions:
  ```js
  // Here in sleep funtion 'name' and 'time' are parameters
  // which is part of function definition
  function sleep(name, time) {
      console.log(name + " is sleeping form " + time);
  }

  // Here "Imran" and "10 pm" are the actual value
  // that is passed to the sleep function when it is calling
  sleep("Imran", "10 pm");
  sleep("Hossain", "12 pm");
  ```
## FrontEnd
