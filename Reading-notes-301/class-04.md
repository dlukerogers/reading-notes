# Read: Class 04

## React Docs - Forms

1. What is a ‘Controlled Component’?  
  *A 'Controlled Component' is an input form element whose value is controlled by React in such a way that the React component that renders a form also controls what happens in that form on subsequent user input.*  

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.  
  *We should update the state with their responses as soon as they enter them because this can give us more control over the user's input and we can update the form on the fly as a user goes through it.*

3. How do we target what the user is entering if we have an event handler on an input field?  
  *We can target what the user is entering if we have an event handler on an input field by assigning the value attribute to the input and putting the value under state. So essentially, assigning `this.state.value` to the value attribute of an input element.*

## The Conditional (Ternary) Operator Explained

1. Why would we use a ternary operator?  
  *We would use a ternary operator so that we can make `if` conditional statements into one line of code.*

2. Rewrite the following statement using a ternary statement:

```javascript
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
```

*Rewritten:*

```javascript
x===y ? console.log(true) : console.log(false)
```
