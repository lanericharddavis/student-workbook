# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
v-bind & :
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single Page Application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
SPAs are fast and responsive, when updating content, they don't update the entire page, only what needs to be.  They also provide a linear user experience.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
The onMounted method tells the page to do this action(most likely loading content)when the page first fires off. 
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
V-model is used when binding data to something else.  It was used when attaching form input data to an object.
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
v:on or the @ is vue's take on onClick or onSubmit.  ei. @click or @submit.
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
The v-if is used to conditionally render elements.  It basically says, IF this condition is met, then you can render this element.  It can be used to verify account users can only access certain elements (such as a delete button) or something as simple as having a element change colors.
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
The 'key' attribute is what tells the dynamic component how to differenciate between they multiple items you are going to see.  Such as when itterating over an array of objects, the way to tell those objects apart is the object ID.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
Vue.js explains slots as, a content distribution API inspired by the Web Components spec draft, using the <slot> element to serve as distribution outlets for content.
```