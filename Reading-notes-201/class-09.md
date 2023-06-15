# Read: Class 09  

## HTML Forms  

1. Why are forms so important in web development?
  *Forms are so important in web development because they are the main points of interaction between a user and a website or app. They allow users to enter data that is sent to the server which then updates the interface of the website or app.*  

2. When designing a form, what are some key things to keep in mind when it comes to user experience?  
  *When designing a form, it is important to design a quick mockup in order to define the right set of data you want to ask your user to enter. It's also important to remember that the bigger the form, the more risk it is as you could frustrate some users. Keeping it simple is the most important thing to remember.*  

3. List 5 form elements and explain their importance.  
    1. *`<form>` - a container element specifically for containing forms and supports specific attributes to configure the way forms behave.*  
    2. *`<label>` - a line of text to label each form element field that is in the data entry portion of the form.*  
    3. *`<input>` - defines the type of form element being used such as text or email.*  
    4. *`<textarea>` - the input field for a textual message.*  
    5. *`<button>` - a button that the user can click to either submit the data, reset the data to the default value, or do nothing (for developers to define what the button does in JavaScript).*

## Learn JS  

1. How would you describe events to a non-technical friend?  
  *Events are things that happen within a webpage or program. The system tells you about them so that the code you write knows how to react.*  

2. When using the `addEventListener()` method, what 2 arguments will you need to provide? 
    1. *The string `"click"`, to indicate that we want to listen to the click event.*  
    2. *A function to call when the event happens.*  

3. Describe the event object. Why is the target within the event object useful?  
  *An event object is a parameter inside an event handler function that is automatically passed to event handlers to provide extra features and information. The target within the event object is useful because it is always a reference to the element the event occured upon.*  

4. What is the difference between event bubbling and event capturing?  
  *The difference is that the order is reversed. For event bubbling, the event fires first on the innermost element targeted and then on successively less nested elements, while, for event capturing the event fires first on the least nested element, and then on the successively more nested elements until the target is reached.*  
