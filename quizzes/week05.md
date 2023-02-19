# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
Create, Read, Update, Destroy
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
Create - Post
Read - Get
Update - Put
Destroy - Delete
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
Object Relational Mapping. We use Mongoose
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
Post and Put
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
Async/await   /  synchronous 
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
import { Something } from "mongoose"
let Schema = Something.Schema
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
Middleware is a type of computer software that provides services to software applications beyond those available from the operating system. Such as a web server that connects websites to the backend database.
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
Front-end, back-end? HTTPGET / HTTPRESPONSE? 
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
https://thiscatdoesnotexist.com/?tag=winter#
```