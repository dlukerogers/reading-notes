# Read: Class 09

## Functional Programming Concepts  

1. What is functional programming?  
  *Functional programming is a style of building the structure and elements of computer programs that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.*  

2. What is a pure function and how do we know if something is a pure function?  
  *A pure function is the first fundamental concept to learn when we want to understand funtional programming. We know if something is a pure function if it returns the same result given the same arguments and if it does not cause any observable side effects.*  

3. What are the benefits of a pure function?  
  *The benefits of a pure function are that they are easier to read, they are easier to maintain, and they always return the same result.*  

4. What is immutability?  
  *Immutability is the state where values are not able to be changed. One cannot alter an immutable value.*  

5. What is Referential transparency?  
  *Referential transparency means that an expression can be replaced by its value without changing the state of the program the expression is in.*  

## Node JS Tutorial for Beginners #6 - Modules and require()

1. What is a module?  
  *A module is a separate JavaScript file you can place different blocks of codes into to keep things organized within your Node*  

2. What does the word ‘require’ do?  
  *The word 'require' connects one module to another module in Node.js.*

3. How do we bring another module into the file the we are working in?  
  *We state a variable called `module.exports` inside of the module we want to bring in and equal that to whatever code we want to make available outside of this module. Then we require that module within the file we are working in.*  

4. What do we have to do to make a module available?  
  *We have to set the require function as a variable.*
