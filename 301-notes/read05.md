# Putting it All Together

## Things I Want to Know More About

## React Docs - Thinking in React

1. What is the *single responsibility principle* and how does it apply to **components**?

This is a technique in which a **component** should ideally do just one things. If the component starts growing, it should be broken down into smaller ***sub***components.

2. What does it mean to build a '***static***' version of your application?

If you want to build a static version of an application, you are essentially building a version that does not have interactivity. The application renders the user interface through the data model; all the data is *static*.

3. Once you have a static application, what do you need to add?

After the static version is built, you will need to add *state* so that users can change the underlying data, and you must identify where state will live.

4. What are the three questions you can ask to determine if something is state?

> - Does the data change over time? 
> - Does the data control a component? 
> - Does the data get re-used?

5. How can you identify where state needs to live?

To know where state needs to live, you need to identify which component owns the state, and is repsponsible for changing it. Here are the steps, as outlined on www.react.dev:

> 1. Identify every component that renders something based on that state.
> 2. Find their closest common parent component—a component above them all in the hierarchy.
> 3. Decide where the state should live:

> > - Often, you can put the state directly into their common parent.
> > - You can also put the state into some component above their common parent.
> > - If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common parent component.

## Higher-Order Functions

1. What is a "higher-order function"?

This is a function that exist on other functions as an *argument*, or by *returning* them to the function they live in. 

2. Explore the **greaterThan** function as defined in the reading. In your own words, what is line 2 of this function doing?

The *greaterThan* function returns another function ( arrow function "m" ) and it checks 'm' against 'n' to see if it is greater. 


3. Explain how either **map** or **reduce** operates, with regards to higher-order functions. 

Both of these functions impact arrays to change or lump togetheer the data in an array. **Map** changes each eleemnt based on a callback function, and it returns a brand new array with the result having the callback function applied. 

On the other hand, the **reduce** function gathers the values of an array into just one value. So if you have an array of numbers and use *reduce*, the new result will be the array added up to be just one value. 

