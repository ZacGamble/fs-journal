# Single Page Applications with Vue

**1.** What is the entrypoint of an application?
<!-- enter you answer in the space below -->
```
It is the point in which the execution of code first begins, and has access to command line arguments.
```
**2.** What is the difference between a vue `component` and `page`?
<!-- enter you answer in the space below -->
```
A page is the landing point and parent for components.
The components are smaller reusable modules that are nested/injected within pages. 

```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
The first thing that comes to mind is the v-for.
It allows you to iterate over a collection of data and inject an instance of a component for each index of said collection.
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
<Template>, for dynamic HTML injection,
<script>, for JavaScript, &
<style> for custom CSS styling.
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Liskov substitution principle.
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
There is the router-view, which exists on the App.vue file.

```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
The AppState is where we define what unique data we wish to capture and store for our application.
The state object is where everything is stored. It is considered the single point of truth.
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
The services main job is to send and receive information from the backend, as well as handle updating the AppState data.
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
The App.vue file links directly to what was our base document in the MVC pattern, index.html.
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
The <style> tag is where all the css is written, with the exception of inline styles.
Adding the "SCOPED" keyword will limit those custom CSS classes to that component or page's local scope.
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
Vue offers many tools for creating reactive data. 
Reactive, ref, watchEffect, and others. 
These makes it possible to bind data to elements in the DOM and get real-time updates.
```