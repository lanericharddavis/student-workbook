# Day2 | Asynchronous Code Part 2> 

## What are the three states of a Promise?
Pending: This is when the promise is made before it has had a chance to succeed or fail.<br>
Resolved: This is when a promise is completed.
Rejected: This is when a promise fails.
## How do promises seek to resolve the issues of "callback hell"?
Callback Hell is resolved with the use of Chaining.  Chaining is where callbacks can by linked one after another, thus cleaning up the callback hell pyramid.
## What is the difference between .then() and .catch()?
Once a Promise is resolved or completed, the ".then()" method is called.  This is where we define what action happens after the promise is completed.
The ".catch()" method is then used on a rejected or failed promise to decide on what action to take. 
## Link for Afternoon Challenge | GregsList MVC: API Practice:
https://lanericharddavis.github.io/spring21-gregslist-mvc/