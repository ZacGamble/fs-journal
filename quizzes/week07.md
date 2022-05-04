# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
One way is by using a v-bind:element.
The other way is to wrap a reacive variable in double curly braces {{}}

```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single Page Application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
Single Page Applications can be more performant and easier to maintain than multipage applications.
They are also more approachable for new developers.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
Basically put, as soon as the page gets "mounted" to the dom via the HTML access point it fires off all methods within it.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
The V-model directive allows a user input to reactively update a ref({}) object. (or other data types)
This way you can dynamically create objects from user inputs instead of manufacturing one like you would in vanilla JavaScript.
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
The v-on directive basically subscribes listeners to the associated DOM element. For example v-on:click (@click="doSomething")
A typical use would be to fire off a function when an element is clicked but there are other potential uses.
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
The v-if directive will inject an entire element into the page IF the given statement is true.
Similarly, the v-show directive will toggle the CSS Display:hidden property to show the element if the supplied statment is truthy.
The difference being v-show falsy elements still exist in the document flow and occupy "space" even while hidden.
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
The key attribute is the identifier for each unique node within a collection being iterated through.
This is how you tell indexes apart, and is typically the object's _id but it can be any unique property.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
The <slot> element is used to translate markup into a modal or offcanvas component. 
This enables the modular, reusable aspect of these components. 
Slotting specific families of data lets you re-use the same modal for multiple operations.
```