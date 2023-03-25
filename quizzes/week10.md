# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
The primary purpose of a namespace is to prevent naming conflicts between code elements that have the same name but are defined in different parts of the program.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Class is a reference type, struct is a value type. 
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
A constructor
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
Public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
It indicates that the method will return a string value of "Vroom"
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
It is preventing the Car class from being instantiated directly
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
Virtual is indicating that the Start() method can be overridden in derived classes.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public, private, internal, protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only code within the same class can access it
```