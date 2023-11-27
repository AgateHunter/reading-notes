# States and Props

## Things I Wnat to Know More About
- What happens if you don't re-render when a prop changes, and why.

<br>

## React Lifecycle


1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

In the diagram, the 'render' happens first.

2. What is the very first thing to happen in the lifecycle of React?

The first thing to happen is Mounting, which is when an instance of a compoent is put into the DOM.


3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

> - constructor
> - render
> - React Updates
> - componentDidMount
> - componentWillUnmount


4. What does componentDidMount do?

The *componentDidMount* method is what launches the React code after the componenent has been put in the DOM. It deals with setting up subscriptions. 


## React State vs Props


1. What types of things can you pass in the props?

Things that you want to initialize your compoment to, or what you want your component to render like. You can also can pass things like a title and subtitle.  This is similar to atributes from HTML.

You pass **into** the compoment

2. What is the big difference between props and state?

A *state* is used to manage the data within a component, while a **prop** is used to pass data. 

3. When do we re-render our application?

A componenet rerenders when its props or state changes

4. What are some examples of things that we could store in state?

Since state is inside a componenent, and it's stored data, it can store things like **strings**, **boolean**, **numbers**, and other objects. 


