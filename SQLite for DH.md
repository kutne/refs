## Getting acquainted with SQLite

### 1. Foundations 

#### 1a. Check out the first two parts of this tutorial at Data Carpentry. You can do more if you'd like, but definitely start with these two.
   - [Part 1: important information about terminology and the role of primary keys](https://datacarpentry.org/sql-socialsci/01-relational-database/index.html)
   - [Part 2: setting up and getting started with DB Browser for SQLite](https://datacarpentry.org/sql-socialsci/02-db-browser/index.html)

#### 1b. Try your hand at working directly with writing SQL statements via the free interactive lessons from [Codecademy](https://www.codecademy.com/learn/learn-sql)
   1. [Manipulation]()
   1. [Queries]()
   1. [Aggregate Functions]()
   1. [Multiple Tables]()

### 2. Diagramming Relationships

### 2. Take a look at this sample database diagram from [SQLiteTutorial.net](https://www.sqlitetutorial.net/sqlite-sample-database/) and think about what what you learned in the Data Carpentry tutorial.  
- Questions to answer:
  1. How many tables are there?  
  1. What information does each table seem to capture?  
  1.  Which tables refer to another table?  
     
![database diagram](https://cdn.sqlitetutorial.net/wp-content/uploads/2015/11/sqlite-sample-database-color.jpg)  

- You can view descriptions of the tables [here](https://www.sqlitetutorial.net/sqlite-sample-database/). 
   - How do the description align or not with your interpretation of diagram

### 3. Download the [sample database](https://www.sqlitetutorial.net/sqlite-sample-database/), open it in DB Browser for SQLite, and explore how it is set up.  
1. In DB Browswer, try to execute different different [SELECT](https://www.sqlitetutorial.net/sqlite-select/) statements  
1. Experiment with manipulating those query results using [ORDER BY](https://www.sqlitetutorial.net/sqlite-order-by/) and [WHERE](https://www.sqlitetutorial.net/sqlite-where/) clauses  
1. Try using the wildcards with the [LIKE](https://www.sqlitetutorial.net/sqlite-like/) operator
Whenever I need to figure out how to write a SQLite statement to execute, this tutorial is one of my first stops.



### 4. Read about the [database design](http://www.mappingsenufo.org/database-design) for the "MAPPING SENUFO: ART AND PLACE IN A DYNAMIC WEST AFRICAN REGION" project  
   - How did this project accomodate uncertainties like variant spelling?
   - Where did this project use [many-to-many](https://en.wikipedia.org/wiki/Many-to-many_(data_model)) relationships?  
  
![mapping senufo database diagram](http://www.mappingsenufo.org/wp-content/uploads/2016/12/Figure3_Senufo_diagram-2.jpg)  

### 5. Plan your potential database.  
   - Don't forget to include primary keys!  
   - Identify what information you might include in each table and the type of data (integer, datetime, etc)  
   - Draw lines between tables to show likely relationships  
   - Consider where you might need m2m (many-to-many) relationships
  
