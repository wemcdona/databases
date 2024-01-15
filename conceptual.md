### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL? PostgreSQL is an object-relational database management system, which is used to manage databases by sorting through them in order to find the needed data.

- What is the difference between SQL and PostgreSQL? SQL is a language for database management systems, while PostgreSQL is an actual specific database management system that uses the SQL language.

- In `psql`, how do you connect to a database? through a commandline, run the syntax : "psql -h [hostname] -p [port] -U [username] -d [database]". if the PostgreSQL server is running on the same machine and using default settings, a simple connection might look like: "psql -U your_username -d your_database"

- What is the difference between `HAVING` and `WHERE`? `HAVING` filters the results of aggregate functions based on specified conditions, and is usually used in combination with the `GROUP BY` clause, often in the context of aggregate functions like `SUM`, `COUNT`, `AVG`, etc. `WHERE` is used to filter rows before any grouping or aggregation takes place. It is used with the `SELECT` statement and specifies conditions that must be met by individual rows in the result set. It filters rows based on the values in one or more columns.

- What is the difference between an `INNER` and `OUTER` join? `INNER JOIN` returns only matching rows, while `OUTER JOIN` returns all rows from one table and matching rows from another, with NULL values for columns from the table without a match. The specific type of `OUTER JOIN` (LEFT, RIGHT, or FULL) determines which table's rows are retained in the result set

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join? `LEFT OUTER JOIN` keeps all rows from the left table, while `RIGHT OUTER JOIN` keeps all rows from the right table.

- What is an ORM? What do they do? ORM stands for Object-Relational Mapping. It is a prgramming technique and a tool that enables developers to interact with relational databases using an object-oriented paradigm.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`? AJAX is focused on client-side asynchronous interactions, while server-side requests are typically synchronous and are used for server-side processing and automation.

- What is CSRF? What is the purpose of the CSRF token? CSRF stands for Cross-Site Request Forgery and is used as a type of security vulnerability that occurs when a malicious website tricks a user's browser into making an unintended and unauthorized request to a differenct website where the user is authenticated. A CSRF token helps prevent attackers from forging requests on behalf of the authnticated user because the malicious site won't have access to the user's CSRF token.

- What is the purpose of `form.hidden_tag()`? it is used to generate an HTML `<input>` element that includes a CSRF token.
