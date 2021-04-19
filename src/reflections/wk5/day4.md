# DAY4 | AUTH

## What is a virtual property?
Virtual properties are additional fields in a model, however, the data in virtual properties don't get persisted in the database.  They only exist logically.
## When might you use a virtual property?
Virtual properties are useful for defining a specific portion or combining two part of a Schema but not wanting that to be stored to the database.  For example, a schema of a person could be made up of their first and last name.  You want to make a field that represents that person's full name but don't want it to be stored in data.  So you make a virtual property.  This is done by Virtual Setters.
## How do you search by a virtual properties value?
To search by a virtual property, you use a Virtual Getter.  It is simply a fuction returning the virtual's value.
## Hack-a-thon #1 Project:
https://austinjdowney.github.io/socialmemes/