# Read: Class 03

## React Docs - lists and keys  

1. What does .map() return?  
  *.map returns the same existing array in the same length but modified in the way we ask it to.*  

2. If I want to loop through an array and display each value in JSX, how do I do that in React?  
  *You would use .map() and have the array return in between list item elements and curly braces.*  

3. Each list item needs a unique ____.  
  *key*  

4. What is the purpose of a key?  
  *Keys helps React identify which elements or items have changed, been added, or removed.*  

## The Spread Operator  

1. What is the spread operator?  
  *It is the use of three dots (`...`) to expand an iterable object into the list of arguments.*  

2. List 4 things that the spread operator can do.  
    1. *It can copy an array.*  
    2. *It can combine multiple arrays.*  
    3. *It can add an item to a list.*  
    4. *It can combine objects.*  

3. Give an example of using the spread operator to combine two arrays.  
  *An example of using the spread operator to combine two arrays is if you have an array of student names from one class and an array of student names from another class and you want to combine the two arrays into one array of student names for a whole new class, you will use the spread operator.*  

4. Give an example of using the spread operator to add a new item to an array.  
  *An example of using the spread operator to add a new item to an array is if you have a new student who is joining the class above, you can use the spread operator to add the student's name to the array of student's names for the class.*  

5. Give an example of using the spread operator to combine two objects into one.  
  *An example of using the spread operator to combine two objects into one is if you have a student's information broken out into two objects, for example, their name and their grade, you can combine their name and grade into one object using the spread operator.*  
