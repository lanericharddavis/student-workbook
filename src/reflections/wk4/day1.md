# Day1 | Asynchronous Code | Part 1

## What are some of the signs and causes of Callback Hell?
  When you start seeing a large pyramid shape in your code, you may have some 'callback hell'.  Most the time, this is caused by developers writing their code where their JS execution is happening from top to bottom, immediately returning a result before moving on to the next action.

## What does the asynchronous mean and how are callbacks involved?
  Asynchronous, or 'async' for short, is a fancy word meaning, 'this happens in the future, not right now'. The action involve may still happen, but the execution of it may not necessarily be called until later.

## Summarize the 3 ways to avoid / fix Callback Hell
    *Elaborate on these...
  1) Keep code shallow
  2) Modularize
  3) Handle every single error