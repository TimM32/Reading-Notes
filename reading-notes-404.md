# Reading Notes Class 404

- What type of database is the best fit for the complex query intensive environment? For complex queries: SQL databases are good fit for the complex query intensive environment whereas NoSQL databases are not good fit for complex queries. On a high-level, NoSQL don't have standard interfaces to perform complex queries, and the queries themselves in NoSQL are not as powerful as SQL query language.
- What type of database is the best fit for hierarchical data storage? NoSQL databases
It is called as UnQL, and the syntax for using the Unstructured query language will vary from syntax to syntax. SQL databases do not suit well for hierarchical data storage. NoSQL databases suit best for hierarchical data storage as it follows the key-value pair method for storing the data.
- Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend. SQL is a database that gives your the information, for instance if you have a pokemon card collection. The actual cards are the the information and what the SQL database stores. The folders that hold those cards are the NoSQL. NoSQL just allows for more information to be stored.

- Among data tables, what is a one-to-many relationship and how do we “relate” them? A one-to-many relationship is the most common kind of relationship. In this kind of relationship, a row in table A can have many matching rows in table B. But a row in table B can have only one matching row in table A. For example, the "Publishers" and "Titles" tables have a one-to-many relationship.
- Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.
- Explain the difference between a primary and foreign key. A primary key generally focuses on the uniqueness of the table. It assures the value in the specific column is unique. A foreign key is generally used to build a relationship between the two tables. The table allows only one primary key.

- How do we treat keywords and parameters differently in SQL syntax?
- Define normalization within the context of schemas and data. In normalization, columns are assigned to tables in such a way that each business fact is stored only once, or in other words, a table should not contain duplicate data.
- Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.
  one-to-one relationship can be looked at as a person and their driver's liscense. One person, one liscense that is one-to-one.
  one-to-many relationship is like a coach in charge of his team, one person assigned to many other people.
  many-to-many would be like an ownership group or LLC that owns and run a professional sports team and has many employees under their charge.

## Additional Information
