# DAY3 | RELATIONSHIPS

## In simple terms what is a sub-document?
A sub-document is a schema nested inside another schema.  Mongoose helps you with this when you nest an object inside another object.
## When might you use a sub-document?
Sub-documents are useful for all sorts of applications where you want an object of objects.  For example, a character in a fighting game and the moves they can perform.
## How do you add to a collection of sub-documents? What about editing them?
There are two ways to do this: Passing the entire object, and adding subdocuments later.  The first method would will work if you know of everything that is going to be in that object so you can just pass it whole sale.  If you plan on adding to it later, you can just create the base object, say a character in a game, and then add moves later on thus evolving the character's scope.  This is done by just editing the character's object and adding moves at a given time and saving it to the character's object.
## Afternoon Challenge | Planet Relationships
https://lanericharddavis.github.io/planets/