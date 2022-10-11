### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?

PostgreSQL is an open source object-relational database system.

- What is the difference between SQL and PostgreSQL?

The main difference is that SQL is a more barebones database management system for querying and storage of data. PostgresSQL adds additional features and capabilities such as foreign keys, sub queries, triggers, and different user defined types and functions.

- In `psql`, how do you connect to a database?

\c __base_datos__

- What is the difference between `HAVING` and `WHERE`?

The "WHERE" clause is used to filter the records from the table or used while joining more than one table. Only those records will be extracted who are satisfying the specified condition in WHERE clause. The "HAVING" clause is used to filter the records from the groups based on the given condition in the HAVING Clause. Those groups who will satisfy the given condition will appear in the final result. HAVING Clause can only be used with SELECT statement.

- What is the difference between an `INNER` and `OUTER` join?

For an inner join, only the rows that both tables have in common are returned. However, for a full outer join, all rows from both tables are returned.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?

For a left outer join, all rows from the left table will be returned plus the rows that the right table had in common. In contrast, for a right outer join, all rows from the right table will be returned plus the rows that the left table had in common.

- What is an ORM? What do they do?

ORM stands for, "Object-Relational Mapping".
An ORM library is a completely ordinary library written in your language of choice that encapsulates the code needed to manipulate the data, so you don't use SQL anymore; you interact directly with an object in the same language you're using.


- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
  
  AJAX makes asyncronous requests while server side makes syncronous requests. Server requests will keep keys private while AJAX does not do it by default.

- What is CSRF? What is the purpose of the CSRF token?

CSRF stands for, "Cross-Site Request Forgery" Attack. The CSRF token is a secure random token that is used to prevent CSRF attacks. The token needs to be unique per user session and should be of large random value to make it difficult to guess.

- What is the purpose of `form.hidden_tag()`?

The form.hidden_tag() can be applied to code in order to render all hidden tokens into one block.