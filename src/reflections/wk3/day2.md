# Day 2 | Encapsulation

## What is the purpose of Encapsulation?
Encapsulation gives developers a way of storing data in objects privately, and the only way to access that data is through the object's methods.  As Alan Kay describes it, "local retention and protection and hiding of state-process."  
## What were some of the problems with closures and the underscore prefix?
Code that is accessed through underscores are most often internal properties and are not intended for users of the API.  Because of this, if they were changed or deleted entirely, developers may not consider that to be a breaking change.  The underscore prefix also is a flag for developers, however some newer developers may not know what it means and change within the files anyway not knowing their error.  It also is a red flag for hackers, giving them more surface API.

## How do we create private variables in a ES6 Class?  Why would you do this?
Through lexical environments.  It is a method which is privileged and has access to the private data inside the containing function's scope.  They have reference-based access to the containing function's variables even after the containing function has returned.

Afternoon Challenge live link: Vending Machine:
https://lanericharddavis.github.io/vending-machine/