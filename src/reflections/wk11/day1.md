# C# Inheritance and Interfaces

## What does Inheritance accomplish for us in C#?
Inheritance makes it possible for classes to inherit fields and methods from another class.  The class that has members which are inherited from is called the base class.  The class which inherits those members is called the derived class.

## How does Member inheritance work in C#? Does a class inherit all members of the base class?
A derived class inherits the members of it's base class, so if Class1 is the base, Class2 is derived of Class1, Class3 is derived of Class2, that means Class3 would inherit members from both Class2 and Class1.  A member of the base class can be hidden from being inherited by declaring members with the same name and signature.

## How does accessibility affect inheritance?
If a Class is public, it can be inherited from.  If Private, it limits accessibility of members to classes within the defined type.  If Protected, members become accessible only when a child is inherited by the parent.