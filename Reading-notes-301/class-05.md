# Read: Class 05

## React Docs - Thinking in React

1. What is the `single responsibility principle` and how does it apply to components?  
  *The `single responsibility principle` is a technique in React that states that a component should only do one thing. This applies to components because you should decide whether you want to break up a component into smaller subcomponenets.*  

2. What does it mean to build a ‘static’ version of your application?  
  *Building a 'static' version of your application means not adding any interactivity to your application.*  

3. Once you have a static application, what do you need to add?  
  *Once you have a static application, you need to add `state`, which will allow users to change the underlying data model, which will make the application interactive.*  

4. What are the three questions you can ask to determine if something is state?  
    1. *Does it remain unchanged over time?*  
    2. *Is it passed in from a parent via props?*  
    3. *Can you compute it based on existing state or props in your component?*  

5. How can you identify where state needs to live?  
  *You can identify where stat needs to live by identifying every component that uses state, finding the closest common parent of those components, and either deciding the state should live directly in the common parent, a component above the common parent, or a new component created above the common parent component to solely hold the state.*  

## Higher-Order Functions

1. What is a “higher-order function”?  
  *A "higher-order function" is a function that operates on other functions either by taking them as arguments or returning them.*  

2. Explore the `greaterThan` function as defined in the reading. In your own words, what is line 2 of this function doing?  
  *Line 2 of the `greaterThan` function is returning another function that says if m is greater than n, than the value is true.*  

3. Explain how either `map` or `reduce` operates, with regards to higher-order functions.  
  *`map` operates by applying a function to all of an array's elements and building a new array from the returned values, but keeping the new array's lenght the same as the input array.*  
