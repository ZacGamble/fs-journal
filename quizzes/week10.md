# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
A set of "signs" that are used to easily identify their internal objects and methods.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
There is one notable difference.
Structs are what are called "value type". 
These house the value represented by their variables.
Classes are what are called "reference type". 
These point to, or reference, the actual data stored somewhere else in memory.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Void

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
"Public" is the access modifier.

```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
String denotes what the data type must be, in this case of course a string.
It could be an integer, double, or even a "var" which interprets the type for you.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
Abstract prevents the class from being instantiated directly. 
It defines functionality but does not directly execute.
It could be used to extend another class.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
It allows the string to be overridden in a derived class.
For instance, in can be overridden by any class that inherits/extends it.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public, private, protected, and internal.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Access is limited to the containing type.
In other words, its scope is limited to the code block where it is instantiated.
```