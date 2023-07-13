# Read: Class 02  

## React lifecycle  

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?  
  *Based off the diagram, the 'render' happens first, then the 'componentDidMount'.*  

2. What is the very first thing to happen in the lifecycle of React?  
  *The very first thing to happen in the lifecycle of React is the calling of constructor for a React component before it is mounted.*  

3. Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor`, `componentWillUnmount`, `React Updates`.
    1. *`constructor`*  
    2. *`render`*
    3. *`React Updates`*
    4. *`componentDidMount`*
    5. *`componentWillUnmount`*  

4. What does `componentDidMount` do?  
  *`componentDidMount` runs right after a component is mounted and contains anything that needs to load using a network request or to initialize the DOM.*  

## React State Vs Props  

1. What types of things can you pass in the props?  
  *You can pass hard-coded elements or attributes into props such as a header or a subtitle.*  

2. What is the big difference between props and state?  
  *The big difference between props and state is that props is used outside the component and must be updated outside of the component, while state is used inside the component and must be updated inside the component.*  

3. When do we re-render our application?  
  *We re-render our application when one of our components changes within our application.*  

4. What are some examples of things that we could store in state?  
  *One example of something that we could store in state is a counter or the number of times someone clicks on something. Another example of something we could store in state is a checkbox from a form that updates when a user clicks on it.*  
