# C# List

## What is a List in C#?
A List in C# is similar to an Array in JavaScript.  A List is a generic type which can be of any type.  Whatever type you choose when creating a new list MUST be declared.
## What List methods seem like you might use them often? Why?
List Constructor: This creates an empty list.
List.Add: This adds to an already exsisting list.
List.Contains: This returns true or false if a list contains a specific item.
List.Sort: This will sort a list.
## How would you retrieve an item from a list? What method could you use?
Depending if you know the item's location in the list or specifically that item is might change how you retrieve it.  You could use a List.Find method if you know there is only one instance of the item, or a List.FindAll if there are multiple of the same item.  If you know the items location in the List, you could use List.IndexOf which would return the item from that location.
## Link to afternoon Challenge | C# GregsList:
https://lanericharddavis.github.io/csgregslist/