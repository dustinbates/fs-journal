# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
One-way databinding, using {{}}, and two-way databinding, using v-model
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single Page Application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
SPAs are faster, since only the required data is loaded, and the code is more organized, since everything is broken into individual components. 
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
onMounted executes code when the DOM is loaded
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
V-model creates a connection between the component's data and user input elements. You might use it to actively display data entered in a form that shows up on the page. 
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
@ can be used to create onClick functions. 
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
You could use v-if, v-else, v-show, v-bind. 
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
Every key attribute acts like an id. Whenever something changes, Vue will always take the updated value.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
The slot element is a placeholder inside a component that allows the parent to pass content to the child component. It can be used, for example, to allow a different form to be inserted into an existing Modal. 
```