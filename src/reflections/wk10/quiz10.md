# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
It provides the "Name" for the space where you are writing the code.  It is because of the namespace that you are able to write Class names with the title of the namespace.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Class is a reference type, Struct is a value type.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
return
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public: can be accessed by any other code in the same assembly or another assembly that references it.
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
String is declaration that the Start method will be reference data type of string.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
The 'abstract' is saying that the class Car must be overridden by it's child.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The virtual is used to modify the method Start(). 
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public, private, protected, and internal.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
It can only be accessed by code in the same class or struct.
```