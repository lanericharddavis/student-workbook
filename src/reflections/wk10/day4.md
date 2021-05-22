# Welcome to SQL

## In a SQL table, what is the difference between information in a row and information in a column?
A row is layed out horizontally and pending on how you have it assigned, typically shows what an individual items attributes are.

For example:<br>
Table MyAnimals<br>
id | name | type<br>
1  | Denali | Dog  <--This is a Row<br>
This shows that the first animal has an id of 1, name of Denali, and type of Dog.


A column is layed out vertically and pending on how you have it assigned, typically shows a list of a single attribute for multiple items.  
Table MyAnimals<br>
id | name | type<br>
1  | Denali | Dog<br>
2 | Revilla | Cat<br>
^<br>
this is a column, it shows that there are two animals and these are their ids

## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
```
CREATE TABLE characters
name VARCHAR(255) NOT NULL,
age VARCHAR(255) NOT NULL,
description VARCHAR(255) NOT NULL,
id INT NOT NULL AUTO_INCREMENT
```

## What is the difference between the following statements:
```
DELETE FROM table_name;
DROP TABLE table_name;
```
DELETE FROM table_name : This means that you are going to remove all the data from that table.
DROP TABLE table_name : This means you are going to delete the entire table.

## Weekend Challenge: C# BloggerServer with SQL:
https://lanericharddavis.github.io/blogger/