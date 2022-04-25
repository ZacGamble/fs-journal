# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
Create, read, update, delete.
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
Create represents a 'post' method.
Read represents a 'get' method.
Update represents a 'put' method.
Delete represents a 'delete' method.
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
Object relational mapper.
Mongoose.
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
Post and put.
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
Asynchronous. 
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
import mongoose from 'mongoose'
let Schema = mongoose.Schema
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
It is software that modifies or enhances the functionality between at least two services.
An example might be our use of Axios to connect to APIs, or mongoose to interface our code with a database.
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
Request, response.
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
{ "tag" : "winter" }
```