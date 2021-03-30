# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Abstraction
Encapsulation
Inheritance
Polymorphism
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
staff[property]
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation gives developers a way of storing data in objects privately, and the only way to access that data is through the object's methods.  As Alan Kay describes it, "local retention and protection and hiding of state-process."
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single-responsibility Principle
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is just a descriptor of something.  It can be as specific as you want but it will only be a descriptor and not exist until it has an instance of it.

A class would be:
Dog (name, species, size, ...)
**it is describing factors of a dog in general, but it is not a specific dog.

An instance of a class would be:
Dog lab = new Dog ('Lassie', caninelupis, medium, ...)
**now we know there is a new dog with those descriptors named Lassie.  Lassie is real.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
As defined by MDN Mozilla: "Enables you to create a proxy for another object, which can intercept and redefine fundamental operations for that object.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
Model View Controller.  To control the flow of data through your application.

View <- -> Controller <- -> Model <- -> Database
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
Handles user input.  Connects to and from the View
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
Handles business logic.  
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
Defines data and control templates.
```

