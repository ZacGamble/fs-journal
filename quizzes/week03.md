# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Abstraction, encapsulation, inheritance, and polymorphism.
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
let result = staff[property]

result == 'Tim'
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
It is the idea of bundling like concerns into their own files. The data and the methods which perform operations on that data are kept together. 
This is to restrict and control access for security and data integrity purposes.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility.
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is a blueprint or template for objects, but is not an object itself.
However, an instance of a class is an object. It must have the same properties as the class which ensures uniformity.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
It is an abstraction layer around the app state. 
It could be considered "middleware" for objects. 
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
It makes larger applications more readable and easier to maintain.
It also enhances the application control flow, security, and data integrity.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller is where client inputs/requests are either rejected or sent into the services layer to be processed.

```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service layer is where user submissions or requests are actually modifying data, and then updating values in the app state. 
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
A model contains the class blueprint or template for all instances of that object.
It also houses any methods to be executed upon those specific objects.
```
