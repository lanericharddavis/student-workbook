# Dotnet WebAPI's and MySQL Many-to-many Relationships

## What is the difference between a primary key and a foreign key
The primary key is used to specify uniqueness of data in a column.  A foreign key provides a link between data in two tables.

## What is an Alias?
Much like alias in other uses, an alias is used to give a table or column in a table, a temporary name.  Often used to improve readability.

## Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:
```sql
CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)
```

## Link to Afternoon Challenge | Contracted:
https://github.com/lanericharddavis/contracted.git