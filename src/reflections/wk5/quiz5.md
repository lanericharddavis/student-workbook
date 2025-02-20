# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
C: Create
R: Read
U: Update
D: Delete
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
Post: C: Create: Used to send data to the server
Get: R: Read: Used to retrieve information from the server
Put: U: Update: Used to edit/update information on the server
Delete: D: Delete: Used to remove information from the server
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
Object-relational mapping.  
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
Post and Put
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
synchronous and asynchronous
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
import mongoose from "mongoose";
let Schema = mongoose.Schema
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
Middleware runs before your route Handler is executed and it augments your Request object with additional information.  This provides you the ability to create more maintainable applications with less code.
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
request and response
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
http://www.webaddress.com/searchresults?tag=winter
```