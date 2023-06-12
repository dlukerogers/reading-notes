# Read: Class 06

## JavaScript Object Basics

1. How would you describe an object to a non-technical friend you grew up with?  
  *An object is a section in JavaScript where related data is put into and commands are run.*  

2. What are some advantages to creating object literals?  
  *Some advantages to creating object literals are when you want to transfer a set of related data to a server because it is much more efficient to send a collection of data in an object literal than separate items individually. It is also much easier to send than arrays when you want to identify objects by name.*  

3. How do objects differ from arrays?  
  *Objects differ from arrays because instead of using an index number, you are using the name associated with each number's value when you select an item.*  

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.  
  *An example when you would need to use bracket notation instead of dot notation is when an object property name is held in a variable.*  

5. Evaluate the code below. What does the term `this` refer to and what is the advantage to using this?  
  *The term `this` refers to the current object the code is being written inside. It enables you to use the same method definition for for every object you create.*  

  const dog = {
    name: 'Spot',
    age: 2,
    color: 'white with black spots',
    humanAge: function (){
      console.log(`${this.name} is ${this.age*7} in human years`);
    }
  }

## Introduction To The DOM

1. What is the DOM?  
  *It is a programming interface for web document and it represents the page so programs can change the format, style, and content of the page.  

2. Briefly describe the relationship between the DOM and JavaScript.  
  *JavaScript needs the DOM to access the document and the objects within it. Without the DOM, JavaScript would have no model or notion of web pages, HTML documents, SVG documents, or their component parts.*
