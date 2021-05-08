# Testing in Vue

## What are the three main types of testing we can accomplish in Vue? What does each method provide?
<em>Unit Testing</em>: This provides the developer with confidence in their code and ensures that the unit, even if refactored, will still remain functional.
<em>Component Testing</em>: Testing components require specialized testing frameworks that work with your framework specific components, such as Vuex, Vue Router and other Vue specific plugins.
<em>End-To-End (E2E) Testing</em>:While unit and component testing are important for those individual aspects to work as desired, End-to-End testing is what tests all those aspects collectively as a whole and reviels errors the user may run into while operating the application themselves.

## What testing method do you think is the most useful? Why?
While each testing method is desireable for their own reasons, I believe that Unit Testing is the most useful because it is testing your code in steps, one by one as it is being built.  So if you know one part is working, and is confirmed operational through testing, it is safe to more forward with confidence knowing that particular unit will not be the weak link in your chain of code.

## What testing method do you think is the least useful? Why?
The least useful, in my opinion, would probably land on End-to-End Testing.  Although it does have benefits for performing, such testing your application across multiple browser platforms, other aspects of E2E testing should be already covered by the other testing methods, as long as they are used correctly.