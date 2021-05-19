# C# Data Type

## What are the three categories of data types? How are they different?
1) Value type: If a data value can be held within it's own memory space.  Variables of these data types directly contain values.
  Examples of value types are:
    bool, byte, char, decimal, double, enum, float, int, long, sbyte, short, struct, uint, ulong, ushort.
2) Reference type: A reference type does not store it's value directly.  It stores the reference address where the value is being stored.
  Examples of reference types are:
    string, class, arrays, delegate
3) Pointer type:  Can be either a type or void.  These options are called referent types.  A pointer cannot point to a reference or to a struct that contains references.

## What are the Value-type data types? What differences do you notice from JavaScript?
bool, byte, char, decimal, double, enum, float, int, long, sbyte, short, struct, uint, ulong, ushort.

There are a lot more options, mainly because C# is strictly type based language so data types need to be specified better than how they are in JavaScript.

## In your own words how do Reference types get stored in memory? How does this differ from Value types?
A reference type is essentially storing a placeholder for the key, that placeholder is assigned a specific spot in memory, then the value to that key is then assigned a different spot in memory, so in order to access the value, you need to first get the placeholder which is the key for that value.

This differs from a value type because value type's value is directly stored on the variable.

## Link to afternoon challenge | Rock Paper Scissors in C#:
https://lanericharddavis.github.io/rockpaperscissors/