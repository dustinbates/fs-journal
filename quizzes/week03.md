# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Encapsulation, inheritance, and polymorphism. Some also say abstraction. 
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
let property = staff.name
console.log(property)

```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is a way to limit what pieces of code can access. "Hide away" and separate code, and place it inside the areas where it is actually needed. 
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single-responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is just the blueprint of something. The instance of a class is the actually built-out thing using the blueprint to know what it needs to be. 
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy is an object that can be used in place of the original object, but can redefine the original object operations. I still don't understand how these work. 
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The purpose is to break up the properties, functions, templates, etc. of many different things on a page, giving them each their own files to reference, to allow cleaner and easier to troubleshoot code. 
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller takes in actions from the user, and draws data to the DOM
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service is where the business logic happens, and handles anything that modifies data. 
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model holds the blueprint for what data in the AppState will look like. 
```
