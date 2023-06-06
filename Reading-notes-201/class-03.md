# Read: Class 03

## Learn HTML

1. When should you use an `unordered list` in your HTML document?  
  *You should use an unordered list when grouping a collection of items that don't need to be in a numerical order.*  

2. How do you change the `bullet style` of unordered list items?  
  *You change the `bullet style` of unordered list items by using the `list-style-type` property in CSS.*  

3. When should you use an `ordered list` vs an `unorder list` in your HTML document?  
  *You should use an ordered list when the order is meaningful. You should use an unordered list when the order is not meaningful.*  

4. Describe two ways you can change the numbers on `list items` provided by an `ordered list`?  
  *You can use the attribute `type` to change the ordered list items to be a different numbering type such as roman numerals. You can also use the attribute `reverse` to change the ordered list to go from highest to lowest.  

## Learn CSS

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?  
  *There once was a castle. A knight named Margin stood outside the castle and guarded it. He had a magical but invisible shield that he could increase or decrease depending on the threat level outside of the castle. Inside the castle lived a servant named Padding. His job was to push a magical button that would increase or decrease the size of the castle depending on the number of guests invited to the castle's different events.*
  
2. List and describe the four parts of an HTML elements box as referred to by the box model.  
    1. *Margin - The invisible space outside of the box.*
    2. *Border - The outline of the box between the margin and the padding.*
    3. *Padding - The space between the border and the content used to push the content away from the border.*
    4. *Content - anything that sits within the padding of the box.*  

## Learn JS

1. What data types can you store inside of an Array?  
  *You can store strings, numbers, objects, and other arrays inside an array.*  

2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?  
     *Yes, the people array is a valid JavaScript array. I can access the values stored by chaining two sets of square brackets together*  

  ``` JavaScript
    const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]]; 
  ```  

3. List five shorthand operators for assignment in javascript and describe what they do.  
    1. *`x += f()` - This adds the value of f() to x.*
    2. *`x -= f()` - This subtracts the value of f() from x.*
    3. *`x *= f()` - This multiplies x by the value of f().*
    4. *`x /= f()` - This divides x by the value of f().*
    5. *`x **= f()` - This makes the value of f() an exponent of x.*  

4. Read the code below and evaluate the last expression and explain what the result would be and why.  
  *The result would be `10dog`. This is because you are adding `10` to `false`. `false` is a null value. So it would result in 10. Then you are adding `10` to the string `'dog'` which will result in the number next to the string or `10dog`.*  

  ``` JavaScript
    let a = 10;
    let b = 'dog';
    let c = false;

    // evaluate this
    (a + c) + b;
  ```

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.  
  *A real world example is when a user is taking a quiz and the website needs to spit out a correct or incorrect alert based on the user's answers.*  

6. Give an example of when a Loop is useful in JavaScript.  
  *A loop is useful in JavaScript when a website is password protected and the user has to be asked repeatedly what the password is if they keep getting it wrong.*  
