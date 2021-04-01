# Day 3 | Forms and Templates

## What are the two common operations that we will set in the handler?
Get and Set

## What do you have to make sure you are doing with every Get to insure the value does not become undefined?
You need to create a proxy object.  Creating a proxy object creates custom logic specified by the handler object for 'get' and 'set'.

## What are some of the benefits of the proxy object that we are using in our structure for applications?
You can make private properties or custom validations.  You can make a 'traps' where you can add custom validation before a value is set.  If it is not meet the validation, you can make an error message.

## Afternoon Challenge | Gregs-List
https://lanericharddavis.github.io/gregs-list/