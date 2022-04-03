# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let, var, and const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is a subprogram designed to carry out a specific task.
It can take in arguments as parameters and must be invoked() somewhere to execute. 
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility
Open-closed
Liskov Substitution 
Interface Segregation 
Dependency Inversion
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
[2] due to zero indexing. Starting at zero and being in third position.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if(5 > 2){
  console.log('hello world')
}
It will only print if the statement inside the parenthesis evaluates true, which in this case it is.
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
It is an 'increment statement' that applies to 'i' on each loop iteration. 
To increase the initialized variable 'i' after each iteration by one, I would write i++ in the blank spot.
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model.
The HTML document is looked at first.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
Primitive values
Boolean type
Null type
Undefined type
Number type
BigInt type
String type
Symbol type
Objects 
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
A parameter is a placeholder reference word.
An argument is the actual data being passed into a function and acted upon.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
A primitive is a single point of simple data such as a number, string, or bool.
A reference value would be an array or object that can contain many items.
```