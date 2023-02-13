# Prep: Introduction to SQL


SQL, or Structured Query Language, is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database. And due to its simplicity, SQL databases provide safe and scalable storage for millions of websites and mobile applications.

WHERE clause is applied to each row of data by checking specific column values to determine whether it should be included in the results or not.

SQL provides a way to sort your results by a given column in ascending or descending order using the ORDER BY clause.

When an ORDER BY clause is specified, each row is sorted alpha-numerically based on the specified column's value.

Using the JOIN clause in a query, we can combine row data across two separate tables using this unique key. The INNER JOIN is a process that matches rows from the first table and the second table which have the same key (as defined by the ON constraint) to create a result row with the combined columns from both tables.

To add data into a database, we need to use an INSERT statement, which declares which table to write into, the columns of data that we are filling, and one or more rows of data to insert.

Updating existing data can be done using an UPDATE statement. Similar to the INSERT statement, you have to specify exactly which table, columns, and rows to update. In addition, the data you are updating has to match the data type of the columns in the table schema. 

To delete data from a table in the database, you can use a DELETE statement, which describes the table to act on,  and the rows of the table to delete through the WHERE clause.

When you have new entities and relationships to store in your database, you can create a new database table using the CREATE TABLE statement.

The structure of the new table is defined by its table schema, which defines a series of columns. Each column has a name, the type of data allowed in that column, an optional table constraint on values being inserted, and an optional default value. 

SQL provides a way for you to update your corresponding tables and database schemas by using the ALTER TABLE statement to add, remove, or modify columns and table constraints.

to remove an entire table including all of its data and metadata, and to do so, you can use the DROP TABLE statement, which differs from the DELETE statement in that it also removes the table schema from the database entirely.
