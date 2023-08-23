# SQL_challenge

## Background

  On this project, a table was created that holds employees data in the CSVs, import the CSVs into a SQL database, and the data exploration was conducted to answering 
  the research questions, and discussed in the following parts:

1. Data Modelling:

   To model the employee data a basic data modeling technique called Entity-Relationship Diagrams (ERD) was used. By using this technique six employee database     
   entities or tables are identified, these entities are employees, departments, salaries, titles, department managers, and department employees. The attribute or 
   the data type of the entities also presented. At last, the ER diagram was drawn to visualize the relationships between entities/objects (primary key or foreign 
   keys in a database).The detailed description of the employee database.![ERD diagram](https://github.com/Npandya23/SQL_challenge/assets/131489392/a0b5711a-8c92-4d90-888c-28251a4b6a22)


2. Data Engineering:

   By using the available information a table schema for each of the six CSV files was created, and the data types, primary keys, foreign keys, and constraints 
   also developed. The order of the table is based on the primary, and foreign arrangements.

   Note to import each CSV file into the corresponding SQL table the order strictly should be followed to avoid errors.

   [Click the following link to see the actual schema file](schema.sql)


3. Data Analysis:

   After completing the importing process a Postgresql analysiss was perfomed and you can find the full query in this file
   [Click the following link to see the actual query file](query.sql)
