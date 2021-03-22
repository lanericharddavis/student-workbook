# Day 1 | Intro to JavaScript

## What is Scope?
When thinking of scope, I think of a telescope.  When you look through it, your eye can only see things that are within the view of the scope.  In a sense, this is how scopes with variables work.  It is the area in which that declared variable can work in.
## What is Hoisting?
Hoisting is a mechanism built into JavaScript that is how code is actually interpreted rather than written within their scope.  Hoisting does very much what it sounds like, it hoists or moves variables and function declarations to the top of their scope.  Some variables are hoisted and some are not which is discussed in the next topic.

## In what cases might you use <b><em>let</em></b> vs <b><em>const</em></b> vs <b><em>var</em></b>?
In the beginning, there was VAR, then with the rollout of ES6, LET and CONST entered as players.  Although they are all used to declare variables, there are distinct differences between the three.
<br>
<br>
VAR: VAR is hoisted, scope focused, meaning that it operates within the scope it was written in such as a function.   An example being: a variable <b>hello</b> is written, and then a later down the road, a function is written with a variable inside of it named <b>hello</b>, those two <b>hello</b> variables are two different variables and wouldn't have an impact on the other.  Var can also be updated within its scope.
<br>
<br>
LET: LET is non-hoisted, can be updated but not re-declared, block focused and is the preferred method of variable declaration.  A block is code inside of { }.  
<br>
<br>
CONST: CONST is non-hoisted, can not be updated or reassigned, and is block scoped.