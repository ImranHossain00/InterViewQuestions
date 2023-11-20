# InterViewQuestions
## Backend
- Differences between **API** and **RESTfull API**:
  |                         API                             |                          RESTful API                          |
  |---------------------------------------------------------|---------------------------------------------------------------|
- Defferences between **RESTfull** and **GraphQL** API:
  |                         RESTfull API                    |                          GraphQL API                          |
  |---------------------------------------------------------|---------------------------------------------------------------|
### DataBase
- Generally 2 types of language are used in Database. 1. DDL(Data Definition Language) and 2. DML(Data Manipulation Language).
  Where table structure is defined by DDL and various queries like reading data, changing and deleting etc. are done with DML.
- When we run a query in a database then database execute this query in several steps.. 
  - Transform SQL query in database format
  - Determines if there are any mistakes in the syntex in the query
  - Examines its semantics
  - Makes execution plan of the query
  - Then adds input variables to the query and
  - In last executes the query and returns the outputs.
<br>

### Problem-solving
### OOP
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
