# Passing Functions as Props

## Things I Want to Know More About

## List and Keys

### What does .map() return?

.map( ) returns a new array with the results having the function applied to it. 

### If I want to loop through an array and display each value in JSX, how do I do that in React?

You would create a for each loop, and use the .map function 

### Each list item nees a unique ___.

Key

### What is the purpose of a key?

Keys allows for a unique identification of an item. That way, even when things get deleted or inserted or reordered, React knows what happened. 

## The Spread Operator

### What is the spread operator?

**Spread** allows things that can be itterated, like an array or a string, to expand to places where arugments or elements are typically expected. It adds the key-value pairs to the object; it *expands* an arry into elements. 

### List 4 things that the spread operator can do.

1. Conditionally add values to an array
2. Replace apply
3. Apply for new operator
4. Copy an array

### Give an example of using the spread operator to combine two arrays.

let example1 = [5, 10, 15];
const example2 = [4, 8, 16];

example 1 = [...example1, ...example2];


### Give an example of using the spread operator to add a new item to an array.

const trees = ["pine", "cedar", "birch" ..."oak"];

### Give an example of using the spread operator to combine two objects into one.

const test1 = { jump: "up", x: 50};
const test2 = { run: "fast", y: 100};

const mergedTest = {...test1, ...test2};

## How to Pass Functions Between Components

