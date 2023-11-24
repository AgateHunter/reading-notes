# Dive Into React

## A High Level Overview of React



### What is React?
1. React is a User Interface Library: It's used for creating user interfaces like websites and applications. It's anything that a user is going to see in the browser.
2. React also has a **Compoment Architecture**
3. React uses 1 way Data Flow
4. React has Component State - Data can be changed in an application, but it is controlled at the component level 


### What is a component?
A component is a small piece of code that fills part of the user interface. 


### What is the dataflow of React?
It has a ***one way* data flow, and was one of the first to do this, though it is now becoming the standard. It's different than *2 way binding*

### How do we make a React element a DOM element?
To make a Recat element into a DOM element, you have to pass it through ReactDOM.render(); 


### React is a User Interface ______.
*Library*. It can be used anywhere and it's agnostic as to where compoments are sent. It creates interfaces (charts, websites, bars, etc...) It could be a whole or just a part, it doesn't matter. It is different than a **framework**. It's not as big and robust as a full framework, like Angular. It's lightweight and has functions to create user interfaces. 

### Which direction does data flow in React?
Data flows just *one way* in React. This means that we can pass data **down** to the levels below, but the data does not flow back up the opposite direction. There is a way to fetch data from higher up, and it will flow back down. 


### Every component manages its own ____.
DATA
