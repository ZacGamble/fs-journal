# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Synchronous code executes from the top down 
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
An event listener is a tool that lets us pass in two arguments, a collection and a function.
It 'listens' for any changes in the collection [array] and will execute the given function when changes are assigned.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The open-closed principle.
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
Simply put, it is a function that takes in another function as an argument, or results in returning another function.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise is, in simple terms, when a function has made a network request that has yet to be resolved. It will persist until either successful, it reaches a designated timeout, or receives a failure response from the server.

The simple way we have been taught to handle these is to nest them in a try-catch. I.E. "try" to complete the async await function and move forward, but if that fails to "catch" the error and notify the dev/user.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
We create a network services JS file, a.k.a. AxiosService.js, and declare a base URL we wish to connect to.
A function that calls upon this address must be written that appends an extension to the base URL to receive a desired response.
Finally, we must invoke this chain of functions either upon application load, or triggered by an event.
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application Programming Interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The service layer.
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
Enhances security, lets us better control data flow, and allows developers to separate our concerns to individual files.
This also allows greater expandability for larger applications.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
200 OK
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
A 500 internal server error is a very generic error message, but it lets you know that something has gone wrong on the server's side of a request.
```